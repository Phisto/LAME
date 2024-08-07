[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/github/license/phisto/Lame.svg)](https://github.com/Phisto/LAME)

## Overview

This is a mirror of the [LAME](https://lame.sourceforge.io) 3.100 source and will build a dynamic framework for macOS.

It is slightly tuned to address some XCode warnings and uses the project settings recommended by XCode. 

The framework will build with its [config file](https://github.com/Phisto/LAME/blob/master/lame-source/config.h) created on my developer machine. It should be valid for most current Apple computers, but you can create your own config file from source (run configure) an replace the provided one.


## Requirements

- macOS 10.13+
- Xcode 15.4+


## Installation

### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks. To integrate LAME into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "Phisto/LAME" ~> 3.0
```

### Manually

If you prefer not to use Carthage, you can integrate LAME into your project manually.
You need to build and add the LAME framework (Lame.framework) to your project yourself. 


## Usage

I really dont know a source for how to use the LAME framework, but you can check out my [CoreAudioConverter](https://github.com/Phisto/CoreAudioConverter) project to see how i use it.


## License

LAME is released under the [GNU Lesser General Public License (LGPL)](https://www.gnu.org/licenses/). 



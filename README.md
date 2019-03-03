[![Carthage Compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/github/license/phisto/Lame.svg)](https://github.com/Phisto/LAME)

## Overview

This is a mirror of the LAME 3.99.5 source and will build a dynamic framework for macOS.

It is slightly tuned to address some XCode warnings and uses the project settings recommended by XCode.


## Requirements

- macOS 10.10+
- Xcode 10.1+


## Installation

### Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks. To integrate LAME into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "Phisto/LAME" ~> 3.0
```


### Manually

If you prefer not to use Carthage, you can integrate LAME into your project manually.
You only need to build and add the LAME framework (Lame.framework) to your project. 


## Usage

I really dont know a source for how to use the lame framework, but you can check out my [CoreAudioConverter](https://github.com/Phisto/CoreAudioConverter) project to see how i use it.


## License

LAME is released under the [GNU Lesser General Public License (LGPL)](https://www.gnu.org/licenses/). 






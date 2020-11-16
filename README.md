<p align="center">
    <img src="mantis_logo.png" width="160" max-width="40%" alt="Imagine Engine" />
</p>
<p align="center">
    <img src="https://travis-ci.org/kylef/Stencil.svg?branch=master" />
    <img src="https://img.shields.io/cocoapods/p/Layout.svg?style=flat" />
    <img src="https://img.shields.io/badge/Swift-4.0-orange.svg" />
    <img src="https://img.shields.io/badge/Xcode-9.0-blue.svg" />
    <a href="https://github.com/Carthage/Carthage">
        <img src="https://img.shields.io/badge/carthage-compatible-4BC51D.svg?style=flat" alt="Carthage" />
    </a>
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat" />    

</p>


# Mantis
**⛵️Mantis helps you build apps quickly**



## Kit & Version

|Framework|Version|Desc|
|:---|:----:|:----|
|[MTUIFlash]()|3.0.0|控件封装库|
|[MTNetworkManager]()|3.0.0|网络访问库|
|[MTCobwebs]()|3.0.0|基类公共库|
|[CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift)|1.0.0||
|[Alamofire](https://github.com/Alamofire/Alamofire)|5.0.0-beta.4||


## Requirements

- iOS 10.0+
- Swift 5.0
- Xcode 10.2

## Docments
http://ued.pccb.com/iosUtils/Documents/
user: `pccb`
password: `pccb@ued`

## Installation

### Carthage
[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.


To integrate the Mantis into your Xcode project using Carthage, specify it in your `Cartfile`:

```
# A binary only framework
binary "https://my.domain.com/release/MyFramework.json" ~> 2.3
```
```
git "https://gitee.com/Bagle/Mantis.git"
```

每次更新前，最好清空carthage 缓存（同一版本号更新会直接使用缓存）：
 ```
 rm -r ~/Library/Caches/carthage/
 rm -r ~/Library/Caches/org.carthage.CarthageKit
 ```

Run `carthage update` or `carthage update --platform iOS` to build the framework and drag the built `xxx.framework` into your Xcode project.

####更新carthage 
  - brew update
  - brew outdated carthage || brew upgrade carthage

## Usage

#### For import:

``` swift
import MTUIFlash
```
## Make Docs
in Mantis root path

``` shell
sh make.sh ./
``` 		
or

``` shell
./make.sh ./
```

## License

Mantis is released under the MIT license.
See [LICENSE](./LICENSE) for details.


## About
author:八哥 
See our other [open-source projects](https://gitee.com/Bagle) .
Email: springlo@126.com



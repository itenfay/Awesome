## Weex

- [Weex](https://github.com/apache/incubator-weex) - A framework for building Mobile cross-platform UI. 

| platform | status |
| :--------: | :------: |
| Android | [sdk](https://bintray.com/weex/Android/sdk/_latestVersion) Or [sdk_legacy](https://bintray.com/weex/Android/sdk_legacy/_latestVersion) |
| iOS | [![Pod version](https://badge.fury.io/co/WeexSDK.svg)](https://cocoapods.org/pods/WeexSDK) [![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage) |
| [Mobile Web](https://github.com/weexteam/weex-vue-render) | [![npm version](https://badge.fury.io/js/weex-html5.svg)](https://www.npmjs.com/package/weex-vue-render) |


## Use Weex

* [Tutorial](http://weex.apache.org/guide/)
* [Documents](http://weex.apache.org/references)

### Android
**You should install [android environment](./HOW-TO-BUILD.md#android) before building.**

You can either build Weex from IDE (*Android Studio*) or command line.

#### Build From Android Studio
1. Open `android` directory in Android Studio.
2. Run `git submodule update --init --remote` in `android` directory if this is the first time you try to run Weex.

#### Build From Command Line
Please read [How To Build](./HOW-TO-BUILD.md) for detail.

### iOS
**You should install [iOS environment](./HOW-TO-BUILD.md#ios) before building.**

You can either build Weex from IDE (*XCode*) or command line.

#### Build From XCode
* Run playground
  * `cd ios/playground`
  * `pod install`
  * Open `WeexDemo.xcworkspace` in Xcode
  * Click <img src="http://img1.tbcdn.cn/L1/461/1/5470b677a2f2eaaecf412cc55eeae062dbc275f9" height="16" > (`Run` button) or use default shortcut `cmd + r` in Xcode
  * If you want to run the demo on your device, don't need to modify `CURRENT_IP` manually. ~~In `DemoDefine.h`(you can search this file by Xcode default shortcut `cmd + shift + o`), modify `CURRENT_IP` to your local IP~~
* integrate to your application

  - **[CocoaPods](https://cocoapods.org)**

     Add the following line to your Podfile:
   ```
     pod 'WeexSDK'
   ```
    run `pod install`

  - **[Carthage](https://github.com/carthage/carthage)**

    Add the following line to your Cartfile:
   ```
     github "apache/incubator-weex"
   ```
   Run `carthage update`, and you should now have the latest version of   `WeexSDK` in your `Carthage` folder.

#### Build From Command Line
Please read [How To Build](./HOW-TO-BUILD.md) for detail.

### Mobile Web
**Vue Render for Apache Weex is a third party plugin, and not developed nor maintained by Apache Weex.**

see [Vue Render for Apache Weex](https://github.com/weexteam/vue-render-for-apache-weex).


## Meet Weex

* Install [Weex Playground](https://weex.apache.org/tools/playground.html) to see examples we already written.
* If you want to write a demo, install [weex-cli](https://www.npmjs.com/package/weex-toolkit) in [Node.js 8.0+](http://nodejs.org/) and
* Run weex init to generate & start a simple project in an empty folder.
* Follow the instructions in the project README.
* Enjoy it.


## Third part plugin

There is a third party plugin provides for debugging purpose.

  - [Android](https://weex.apache.org/guide/debug/integrate-devtool-to-android.html)
  - [iOS](https://weex.apache.org/guide/debug/integrate-devtool-to-ios.html)

You can also view this page for all [third party plugin](https://weex.apache.org/tools).


## Weex Community

* [Mailing List](https://weex-project.io/contributing.html#join-in-discussions) Weex Mailing List, where most discussion happens.
* [StackOverflow](http://stackoverflow.com/questions/tagged/weex): Ask questions about Weex.
* [SegmentFault (cn)](https://segmentfault.com/t/weex): 中文交流与讨论
* [FAQ](https://weex.apache.org/faq.html)
* [Articles (cn)](https://github.com/weexteam/article/issues): Weex 相关文章集合
* [Telegram Russian Community Group](https://telegram.me/weex_ru)

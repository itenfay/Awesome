## OpenSource
汇总实用的开源项目

## iOS Project

- [史上最全的iOS开源项目分类汇总](http://blog.csdn.net/arodung/article/details/50846546)

### 强大的组件
- [YYKit](https://github.com/ibireme/YYKit) - 组庞大、功能丰富的 iOS 组件。<br />
  [YYModel](https://github.com/ibireme/YYModel) - 高性能的 iOS JSON 模型框架。<br />
  [YYCache](https://github.com/ibireme/YYCache) - 高性能的 iOS 缓存框架。<br />
  [YYImage](https://github.com/ibireme/YYImage)  - 功能强大的 iOS 图像框架。<br />
  [YYWebImage](https://github.com/ibireme/YYWebImage) - 高性能的 iOS 异步图像加载框架。<br />
  [YYText](https://github.com/ibireme/YYText) - 功能强大的 iOS 富文本框架。<br />
  [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) - iOS 键盘监听管理工具。<br />
  [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS 全局并发队列管理工具。<br />
  [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS 异步绘制与显示的工具。<br />t
  [YYCategories](https://github.com/ibireme/YYCategories) - 功能丰富的 Category 类型工具库。

- [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift ([RxExample](https://github.com/ReactiveX/RxSwift/tree/master/RxExample)). <br />
RxSwift comprises five separate components depending on eachother in the following way:
```
┌──────────────┐    ┌──────────────┐
│   RxCocoa    ├────▶   RxRelay    │
└───────┬──────┘    └──────┬───────┘
        │                  │        
┌───────▼──────────────────▼───────┐
│             RxSwift              │
└───────▲──────────────────▲───────┘
        │                  │        
┌───────┴──────┐    ┌──────┴───────┐
│    RxTest    │    │  RxBlocking  │
└──────────────┘    └──────────────┘
````

- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Reactive extensions to Cocoa frameworks, built on top of [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)), It Offers composable, declarative and flexible primitives that are built around the grand concept of streams of values over time. These primitives can be used to uniformly represent common Cocoa and generic programming patterns that are fundamentally an act of observation. <br />
![](https://github.com/ReactiveCocoa/ReactiveCocoa/raw/master/Logo/PNG/logo.png)


### 网络

- [BANetManager](https://github.com/boai/BANetManager) - 基于AFNetworking 3.0、3.1最新版本的封装，集成了 get / post / put / delete 方法请求数据，单图/多图上传，视频上传/下载，网络监测 等多种网络请求方式。<br />


### 导航条 & 状态栏

- [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) - 超简单！！！ 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等。（[Swift版](https://github.com/dgynfi/WRNavigationBar_swift)）
![](https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/拉钩App首页.gif) ![](https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/新浪微博个人中心.gif) ![](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/蚂蚁森林.gif) 
  
- [NNNavigationBar](https://github.com/amisare/NNNavigationBar) - 实现导航条背景渐变过渡动画的轻量级框架。
![](https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_00.gif) ![](https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_01.gif)


### 播放器

- [ABigFishTV](https://github.com/clyhs/ABigFishTV) - 大鱼电视直播 基于ijkplayer的播放器 700多个电视台 包括央视，各地方台，卫视，熊猫直播，社会化分享，登陆，仿微博等 (支持iphonex)。<br />
![](https://github.com/clyhs/ABigFishTV/blob/master/images/ABigFishTV.gif)

- [CLPlayer](https://github.com/JmoVxia/CLPlayer) - 自定义支持全屏的播放器。<br />
![](https://github.com/JmoVxia/CLPlayer/blob/master/效果图.gif)

- [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS (iPhone, iPad).

- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support ([FFmpeg](http://ffmpeg.org)).


### 逆向开发

- [WeChatRedEnvelopesHelper](https://github.com/luckysine/WeChatRedEnvelopesHelper) - iOS版微信抢红包插件，支持后台抢红包，tweak源文件。<br />
![](https://github.com/luckysine/WeChatRedEnvelopesHelper/blob/master/screenshots/step.png)


### 蓝牙

- [EasyBluetooth]( https://github.com/chenliangloveyou/EasyBluetooth) - 一款iOS BLE蓝牙调试工具，非常简单容易，也可以作为一个蓝牙库，快速集成和开发。 可以两步搞定蓝牙开发操作。第一步连接设备，第二步特征读写数据。<br />
![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_3.png) 
![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_4.png) <br />
![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_1.gif)  ![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_2.gif) 

- [WHBLEDemo](https://github.com/remember17/WHBLEDemo) - 📱CoreBluetooth central and peripheral demo with OC/Swift (iOS蓝牙中心设备和外设开发,包含OC/Swift版本) <br />
![](https://camo.githubusercontent.com/3ba378f9a697f5e30d6937f64ba8a97498bb3513/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d613731636537393634653834613263652e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) <br />
![](https://camo.githubusercontent.com/47b0012be03c0f3f6c59c7169fa4563ff6380d7c/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d353334626433303463346537393765362e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970)

- [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 简单易用的蓝牙库，基于CoreBluetooth的封装，并兼容ios和mac osx。<br />
![](https://github.com/coolnameismy/BabyBluetooth/blob/master/logo.png)

- [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE.


### 扫码器

- [MMScan](https://github.com/MinMao-Hub/MMScan) - 一个简单的二维码以及条码扫描工具，使用Objective-C语言开发，有一套自定义的扫描动画以及界面，还包括生成二维码以及条码。
![](https://github.com/MinMao-Hub/MMScan/blob/master/gifs/mmscan.gif)

- [QRCode](https://github.com/kingcong/QRCode-master) - 仿微信二维码扫描。

### x

- [XHPayKit](https://github.com/CoderZhuXH/XHPayKit) - 不用官方SDK实现微信支付、支付宝支付。

- [NNMacros](https://github.com/amisare/NNMacros) - NNMacros通过宏的方式来简化iOS开发中OC的语法和Api的操作。

- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - 一个可以很容易地为iOS创建漂亮的、高度可定制的动画复选框。<br />
![](https://github.com/Boris-Em/BEMCheckBox/blob/master/.assets/BEMCheckBox.gif)

- [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 向UIView对象类添加Toast通知的Swift扩展。<br />
![](https://github.com/scalessec/Toast-Swift/blob/master/toast_swift_screenshot.jpg)

- [EasyShowView](https://github.com/chenliangloveyou/EasyShowView) - 一款超级简单的展示工具，包括吐丝指示器，loding加载框，空白页提示，alertview，actionsheet的定制。可任意定制自己想要的各种样式，自定义动画，显示样式等各种操作，使各种展示更加easy。<br />
![](https://github.com/chenliangloveyou/EasyShowView/blob/master/show_preview/preview_text.gif) ![](https://github.com/chenliangloveyou/EasyShowView/blob/master/show_preview/preview_loding.gif)

- [RSSliderView](https://github.com/rsimenok/RSSliderView) - Custom slider based on UIView for iOS. <br />
![](https://camo.githubusercontent.com/7a7a899104ae97a30b0aae97bb2ce7d80a8a0f25/687474703a2f2f692e70696363792e696e666f2f69392f61666463643862353032396531663238623862643333663762643338323263312f313432343131383133392f31323632322f3738303432352f3132332e706e67)

- [ZZHotKeysMenu](https://github.com/zhouXiaoR/ZZHotKeysMenu) - ZZHotKeysMenu自定义布局，继承自UICollectionViewLayout。<br />
![](https://github.com/zhouXiaoR/ZZHotKeysMenu/blob/master/运行效果.gif)

- [LCSlideMenu](https://github.com/ChinaHackers/LCSlideMenu) - A powerful and easy to use slider menu. <br />
![](https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/LCSlideMenu.png) <br />
![](https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast01.gif) ![](https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast03.gif)

- [JMColumnMenu](https://github.com/JunAILiang/JMColumnMenu) - 仿腾讯新闻、今日头条栏目管理。

- [MLMenu](https://github.com/MrDML/MLMenu) - 仿微信QQ右上角菜单功能。<br />
![](https://github.com/MrDML/MLMenu/blob/master/MLMenuGif.gif)

- [JMDropMenu](https://github.com/JunAILiang/JMDropMenu) - 仿QQ、微信下拉菜单封装，支持自定义样式。<br />
![](https://raw.githubusercontent.com/JunAILiang/JMDropMenu/master/JMDropMenu/JMDropMenu.gif)

- [XYMenu](https://github.com/HeathHsia/XYMenu) -  简易集成的弹出菜单。<br />
![](https://github.com/dgynfi/XYMenu/blob/master/img/demo.gif)

- [SHESelectTable](https://github.com/shelly8219/SHESelectTableDemo) - 下拉选择的列表。<br />
![](https://github.com/shelly8219/SHESelectTableDemo/blob/master/source/screenclip.jpg)

- [iOSProject](https://github.com/NJHu/iOSProject) - iOS project of collected some demos for iOS App.（[Swift版](https://github.com/dgynfi/WRNavigationBar_swift)）<br />
![](https://raw.githubusercontent.com/NJHu/iOSProject/master/images//home.gif) ![](https://raw.githubusercontent.com/NJHu/iOSProject/master/images/anidynquar.gif)

- [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) - iOS平台利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志。<br />
![](https://github.com/Lede-Inc/LDNetDiagnoService_IOS/blob/master/LDNetDiagnoServiceDemoTests/netdiagnosis_ios.jpg)

- [ZLAdvertDemo](https://github.com/ZLFighting/ZLAdvertDemo) - 启动页加载广告。<br />
![](https://github.com/ZLFighting/ZLAdvertDemo/blob/master/ZLAdvertDemo/启动页跳过广告.gif)



- [iOS-getClientInfo](https://github.com/PengfeiWang666/iOS-getClientInfo) - 📲iOS中获取各种设备信息。

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - CryptoSwift是在Swift中实现的越来越多的标准和安全密码算法的集合。 

- [TOSMBClient](https://github.com/TimOliver/TOSMBClient) -  A small library that serves as a simple SMB (Server Message Block ) client for iOS apps. The library allows connecting to SMB devices, downloading file metadata, and subsequently allows asynchronous downloading of files from an SMB device straight to an iOS device. It is an Objective-C wrapper around Defective SMb, or libDSM, a low level SMB client library built in C built by some of VideoLabs' developers. A copy of libDSM has been specially cross-compiled for iOS device architectures and embedded in this library, so this project has no external dependencies.

- [iOSAnimation](https://github.com/BranPeng/iOSAnimation) - 好玩的iOS动画。

- [iOS-Swift-Animation](https://github.com/BranPeng/iOS-Swift-Animation) - iOS Swift动画框架。

- [iOS-Swift-UI](https://github.com/BranPeng/iOS-Swift-UI) - iOS-Swift-UI。

- [iOS-Project](https://github.com/BranPeng/iOS-Project) - 收集的一些比较好的iOS打样工程。

- [LYThemeChange](https://github.com/lanyasheng/LYThemeChange) - 主题更换。


## 比特币 & 以太坊 & 区块链

- [go-ethereum](https://github.com/ethereum/go-ethereum)  - 以太坊协议的官方的Go语言实现。<br />
   [Download Geth](https://geth.ethereum.org/downloads/) - Binary archives are published.

- [web3swift](https://github.com/BANKEX/web3swift) - Elegant Web3js functionality in Swift. Native ABI parsing and smart contract interactions on Ethereum network. <br />
![](https://user-images.githubusercontent.com/3356474/34412791-5b58962c-ebf0-11e7-8460-5592b12e6e9d.png)
- [web3.swift-Example](https://github.com/MercuryProtocol/web3.swift-Example) - Example on how to use web3.swift. 

- [web3j](https://github.com/web3j/web3j) - web3j is a lightweight, highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network. <br />
![](https://raw.githubusercontent.com/web3j/web3j/master/docs/source/images/web3j_network.png)  

- [py-geth](https://github.com/ethereum/py-geth) - Python wrapping for running Go-Ethereum as a subprocess.

- [EthersWallet-ios](https://github.com/ethers-io/EthersWallet-ios) - Ethereum Wallet and Dapp Browser for iOS.

- [breadwallet-ios](https://github.com/voisine/breadwallet-ios) - Bread is the best way to get started with bitcoin. <br />
![](https://github.com/voisine/breadwallet-ios/blob/2.0/images/screenshots.jpg)

- [dashwallet](https://github.com/QuantumExplorer/dashwallet) - Dashwallet (breadwallet fork) is a real standalone Dash client. <br />
![](https://github.com/QuantumExplorer/dashwallet/blob/master/images/screenshot2.jpg)

- [ethers.io](https://github.com/ethers-io/ethers.io) - The frontend website HTML, JavaScript and CSS for ethers.io. 
- [ethers.objc](https://github.com/ethers-io/ethers.objc) - Fast, simple and complete library for Ethereum in Objective-C.


## 棋牌

- [qipai_algorithm](https://github.com/yuanfengyun/qipai_algorithm) - 棋牌的胡牌算法，包括麻将、跑胡子、扑克。实现 lua 、c++ 、c# 、golang 、js 、java 、python 版本。

## cocos2d

- [cocos2d-x](https://github.com/cocos2d/cocos2d-x) - Cocos2d-x is a suite of open-source, cross-platform, game-development tools used by millions of developers all over the world. http://www.cocos2d-x.org
  ![](https://github.com/cocos2d/cocos2d-x/blob/v3/docs/framework_architecture.jpg)

## C++

- [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.

## Flutter

**Flutter && Dart** 

- [Flutter中文网](https://flutterchina.club) 
- [Flutter SDK Archive](https://flutter.io/sdk-archive/#macos) 
- [Dart Packages](https://pub.flutter-io.cn)
- [Dart2 中文文档](https://www.kancloud.cn/marswill/dark2_document/709087) 


**Flutter Project**

- [dart_crypto](https://github.com/dgynfi/dart_crypto) - 🔥集成Base64, MD5, AES, RSA等算法。

- [grab_ethtoken_info](https://github.com/dgynfi/grab_ethtoken_info) - 🔥爬取etherscan的一个钱包地址的所有token信息( address, name, balance, symbol, value)，并编写界面进行展示。

- [flutter_study](https://github.com/dgynfi/flutter_study) - Flutter基础，Dart基础，实践教学 <br>
  ![](https://raw.githubusercontent.com/luhenchang/IMAGE/master/img_bizhan/WeChat3d4501c5ea03165d48b5270ac7944463.png)
  
  


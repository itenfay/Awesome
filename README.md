## OpenSource
🔥🔥🔥 汇总实用的开源项目 🔥🔥🔥

## iOS Project

- [史上最全的iOS开源项目分类汇总](http://blog.csdn.net/arodung/article/details/50846546)

### 🔥🔥🔥👍👍👍
- [YYKit](https://github.com/ibireme/YYKit) - 一组庞大、功能丰富的 iOS 组件。<br />
  [YYModel](https://github.com/ibireme/YYModel) - 高性能的 iOS JSON 模型框架。<br />
  [YYCache](https://github.com/ibireme/YYCache) - 高性能的 iOS 缓存框架。<br />
  [YYImage](https://github.com/ibireme/YYImage)  - 功能强大的 iOS 图像框架。<br />
  [YYWebImage](https://github.com/ibireme/YYWebImage) - 高性能的 iOS 异步图像加载框架。<br />
  [YYText](https://github.com/ibireme/YYText) - 功能强大的 iOS 富文本框架。<br />
  [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) - iOS 键盘监听管理工具。<br />
  [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS 全局并发队列管理工具。<br />
  [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS 异步绘制与显示的工具。<br />
  [YYCategories](https://github.com/ibireme/YYCategories) - 功能丰富的 Category 类型工具库。

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful networking framework for iOS, macOS, watchOS, and tvOS. 
<div align=center>
<img src="https://camo.githubusercontent.com/1560be050811ab73457e90aee62cd1cd257c7fb9/68747470733a2f2f7261772e6769746875622e636f6d2f41464e6574776f726b696e672f41464e6574776f726b696e672f6173736574732f61666e6574776f726b696e672d6c6f676f2e706e67" />
</div>

**NSURLSession:**
- `AFURLSessionManager `
- `AFHTTPSessionManager`

**Reachability:**
- `AFNetworkReachabilityManager`

**Security:**
- `AFSecurityPolicy`

**Serialization:**
* `<AFURLRequestSerialization>`
    - `AFHTTPRequestSerializer`
    - `AFJSONRequestSerializer`
    -  `AFPropertyListRequestSerializer`
* `<AFURLResponseSerialization>`
    - `AFHTTPResponseSerializer`
    - `AFJSONResponseSerializer`
    - `AFXMLParserResponseSerializer`
    - `AFXMLDocumentResponseSerializer (macOS)`
    - `AFPropertyListResponseSerializer`
    - `AFImageResponseSerializer`
    - `AFCompoundResponseSerializer`

**UIKit:**
- Adding property in the form of catagory.

---

- [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift.<br />
![](https://raw.githubusercontent.com/Alamofire/Alamofire/master/alamofire.png)

**Core目录下各个文件的功能简述:**
- Alamofire.swift -- 该文件中主要是给用户提供一些便利的调用方法，用户可以直接调用该文件中的便利方法来使用Alamofire相关功能。
- Manager.swift -- Manager中定义了Session对象，Session相关的Delegate，以及Delegate执行的队列等相关信息，在Manager中创建Request对象发起请求。Manager管理的就是各种请求，Manager对象是以单例的形式对外开放的。
- Request.swift -- 该文件如其名，就是负责创建Session的各种task的，并执行相关的SessionTask，并调用相关书籍解析的功能模块对数据进行解析并通过回调返回给用户。
- ParameterEncoding.swift -- 负责请求参数的各种编码（URL、URLEncodedInURL、JSON、PropertyList等编码），并将编码后的数据与URLRequest结合后的结果进行返回。
- Result.swift -- 对解析后的数据封装成Result对象。
- Response.swift -- 负责将服务器相应的数据进行封装生成Response对象，该对象中就包括上述的Result对象，用户最终会通过闭包回调的形式获取到该Response的对象。
- Notifications.swift -- 其中是一个Notification结构体，该结构体中定义了一些字符串，这些字符串就是所需通知的Key，当网络请求DidResume、DidSuspend、DidCancel、DidComplete都会发出通知。
- Error.swift -- 其中是一个Error的结构体，其中封装的是各种错误状态。

**Features目录下各个文件的功能简述:**
- Download.swift -- 对Manager和Request类进行扩展，使其支持Down Task，其中封装了NSURLSessionDownloadDelegate相关代理方法。
- Upload.swift -- 在该文件中也是对Manager和Request类进行的扩展，使其支持Upload Task，其中封装了NSURLSessionDataDelegate中获取上传数据进度的代理方法，也就是taskDidSendBodyData代理方法。
- MultipartFormData.swift -- 该文件从名字就可以看出是为了组织多表单数据上传的数据的，在Upload Task中就使用到了MultipartFormData。
- Stream.swift -- 和Download和Upload文件相似，该文件中也是对Manager和Rquest做延展，主要使其支持数据流的传输，其中主要封装和实现了NSURLSessionStreamDelegate相关的代理方法。
- ResponseSerialization.swift -- 该文件中主要是对Request类进行数据解析的延展的。其中封装了各种对响应数据的解析方式，其中包括Data、String、JSON、PropertyList等解析方式。
- NetworkReachabilityManager.swift -- 该文件主要是对SystemConfiguration.framework中的SCNetworkReachability相关的东西进行封装的，主要用来管理和监听网络状态的变化。
- ServerTrustPolicy.swift -- 这个文件主要是对NSURLSession做的延展，其中定义了各种网络请求的认证策略，主要证书认证相关东西。
- Timeline.swift -- 该文件是为了方便调试而生的，其中记录了相关操作的时间点，并且对其进行记录，便于在Debug时使用到。
- Validation.swift -- 主要是用来验证请求是否成功，如果出错了就做相应的处理。

---

- [SDWebImage](https://github.com/SDWebImage/SDWebImage) - This library provides an async image downloader with cache support. For convenience, we added categories for UI elements like UIImageView, UIButton, MKAnnotationView ([Examples](https://github.com/SDWebImage/SDWebImage/tree/master/Examples)). 
<div align=center>
<img src="https://raw.githubusercontent.com/SDWebImage/SDWebImage/master/SDWebImage_logo.png" width="50%" />
</div>

**Coders for additional image formats**
- SDWebImageWebPCoder - coder for WebP image format. Based on libwebp
- SDWebImageHEIFCoder - coder to support HEIF image without Apple's Image/IO framework, iOS 8+/macOS 10.10+ support.
- SDWebImageBPGCoder - coder for BPG format
- SDWebImageFLIFCoder - coder for FLIF format
- and more from community!

**Loaders**
- SDWebImagePhotosPlugin - plugin to support loading images from Photos (using Photos.framework)

**Integration with 3rd party libraries**
- SDWebImageFLPlugin - plugin to support FLAnimatedImage as the engine for animated GIFs
- SDWebImageYYPlugin - plugin to integrate YYImage & YYCache for image rendering & caching
- SDWebImageProgressiveJPEGDemo - demo project for using SDWebImage + Concorde library for Progressive JPEG decoding

**Make our lives easier**
- libwebp-Xcode - A wrapper for libwebp + an Xcode project.
- libheif-Xcode - A wrapper for libheif + an Xcode project.
- and more third-party C/C++ image codec libraries with CocoaPods/Carthage support.

---

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

---

- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Reactive extensions to Cocoa frameworks, built on top of [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)), It Offers composable, declarative and flexible primitives that are built around the grand concept of streams of values over time. These primitives can be used to uniformly represent common Cocoa and generic programming patterns that are fundamentally an act of observation. <br />
![](https://github.com/ReactiveCocoa/ReactiveCocoa/raw/master/Logo/PNG/logo.png)

---

- [Weex](https://github.com/apache/incubator-weex) - A framework for building Mobile cross-platform UI. <br  />

| platform | status |
| -------- | ------ |
| Android | [![Download](https://api.bintray.com/packages/alibabaweex/maven/weex_sdk/images/download.svg)](https://bintray.com/alibabaweex/maven/weex_sdk/_latestVersion) |
| iOS | [![Pod version](https://badge.fury.io/co/WeexSDK.svg)](https://cocoapods.org/pods/WeexSDK) [![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage) |
| [Mobile Web](https://github.com/weexteam/weex-vue-render) | [![npm version](https://badge.fury.io/js/weex-html5.svg)](https://www.npmjs.com/package/weex-vue-render) |

**Weex Community**
* [Mailing List](https://weex-project.io/contributing.html#join-in-discussions) Weex Mailing List, where most discussion happens.
* [StackOverflow](http://stackoverflow.com/questions/tagged/weex): Ask questions about Weex.
* [SegmentFault (cn)](https://segmentfault.com/t/weex): 中文交流与讨论
* [FAQ](https://weex.apache.org/faq.html)
* [Articles (cn)](https://github.com/weexteam/article/issues): Weex 相关文章集合
* [Telegram Russian Community Group](https://telegram.me/weex_ru)

---

### 网络封装

- [BANetManager](https://github.com/boai/BANetManager) - 基于AFNetworking 3.0、3.1最新版本的封装，集成了 get / post / put / delete 方法请求数据，单图/多图上传，视频上传/下载，网络监测 等多种网络请求方式。<br />

- [HYBNetworking](https://github.com/CoderJackyHuang/HYBNetworking) - 基于AFNetworking3.0以上版本封装的网络层。提供常用的GET/POST接口、上传下载图片、文件接口、支持缓存等。

### 导航条 & 状态栏

- [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) - 超简单！！！ 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等（[Swift版](https://github.com/wangrui460/WRNavigationBar_swift)）。
![](https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/拉钩App首页.gif)  ![](https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/新浪微博个人中心.gif)  ![](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/蚂蚁森林.gif) 
  
- [NNNavigationBar](https://github.com/amisare/NNNavigationBar) - 实现导航条背景渐变过渡动画的轻量级框架。<br />
![](https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_00.gif)  ![](https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_01.gif)

- [RTRootNavigationController](https://github.com/rickytan/RTRootNavigationController) - Implicitly make every view controller has its own navigation bar. <br />
![](https://user-images.githubusercontent.com/1250207/30429339-abb20914-9989-11e7-9058-c967839315f4.gif)

- [GKNavigationController](https://github.com/QuintGao/GKNavigationController) - iOS自定义导航栏-导航条联动（仿网易新闻、网易云音乐等导航栏滑动效果）。<br />
![](https://github.com/QuintGao/GKNavigationController/blob/master/GKNavigationControllerDemo/001.png)

- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. <br />
![](https://raw.githubusercontent.com/forkingdog/FDFullscreenPopGesture/master/Snapshots/snapshot0.gif)

### 播放器

- [ABigFishTV](https://github.com/clyhs/ABigFishTV) - 大鱼电视直播 基于ijkplayer的播放器 700多个电视台 包括央视，各地方台，卫视，熊猫直播，社会化分享，登陆，仿微博等 (支持iphonex)。<br />
![](https://github.com/clyhs/ABigFishTV/blob/master/images/ABigFishTV.gif)

- [CLPlayer](https://github.com/JmoVxia/CLPlayer) - 自定义支持全屏的播放器。
<div align=left>
<img src= "https://github.com/JmoVxia/CLPlayer/blob/master/效果图.gif" width="50%" />
</div>

- [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS (iPhone, iPad).

- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support ([FFmpeg](http://ffmpeg.org)).

- [ffmpeg-avplayer-for-ios-tvos](https://github.com/imoreapps/ffmpeg-avplayer-for-ios-tvos) - A tiny but powerful iOS and Apple TV OS av player framework that's based on the FFmpeg library. <br />

- [LyricsAnalysis](https://github.com/wsl2ls/LyricsAnalysis) - iOS音乐播放器之锁屏效果（仿网易云音乐和QQ音乐）+ 歌词解析 ：锁屏歌曲信息、控制台远程控制音乐播放：暂停/播放、上一首/下一首、快进/快退、列表菜单弹框和拖拽控制台的进度条调节进度（结合了QQ音乐和网易云音乐在锁屏状态下的效果）、歌词解析并随音乐滚动显示。
<div align=left>
<img src="https://camo.githubusercontent.com/a7f8d7a5c4d556835a74a48e47287699879ce9c0/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d613833663765343062303165346635302e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width=300 /> <img src="https://camo.githubusercontent.com/3fc34b6daa5822c88ddec99295f2dc33b376b67b/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d373265306262333661633033353330302e504e473f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width=300 />
</div>

### 逆向开发

- [fishhook](https://github.com/facebook/fishhook) - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS. <br />
![](https://camo.githubusercontent.com/18243516844d12b1bd158ce3687635d6e48d2e2e/687474703a2f2f692e696d6775722e636f6d2f4856587148437a2e706e67)

- [WeChatRedEnvelopesHelper](https://github.com/luckysine/WeChatRedEnvelopesHelper) - iOS版微信抢红包插件，支持后台抢红包，tweak源文件。
<div align=left>
<img src="https://github.com/luckysine/WeChatRedEnvelopesHelper/blob/master/screenshots/step.png" width="50%" />
</div>

- [FishChat](https://github.com/yulingtianxia/FishChat) - Hook WeChat.app on non-jailbroken devices. [blog](http://yulingtianxia.com/blog/2017/02/28/Make-WeChat-Great-Again/) 
<div align=left>
<img src="https://github.com/yulingtianxia/FishChat/blob/master/Images/weichat_ignore_chatroom.PNG" width="30%" /> <img src="https://github.com/yulingtianxia/FishChat/blob/master/Images/wechat_setting_keyboard.PNG" width="30%" />
</div>

### IM

- [AtChat](https://github.com/boyssimple/AtChat) - IOS聊天项目、基于XMPP框架开发，实现了登陆注册(注册以手机号码注册、短信验证) 、发送消息、接收消息、接收好友请求、发起好友请求 、图片消息、语音消息、视频语音、聊天历史记录、最近联系人、二维码添加好友、用户头像上传、朋友圈、发朋友圈、异地登录退出等功能。<br />
![](https://github.com/boyssimple/AtChat/blob/master/images/020.png) ![](https://github.com/boyssimple/AtChat/blob/master/images/014.png)

- [BAWeChat](https://github.com/BAHome/BAWeChat) - 博爱微信，使用原生 frame + MVVM + MVC + QMUIKit + BAKit 开源的微信。<br />
![](https://github.com/boai/BAWeChat/blob/master/Images/通讯录.png) ![](https://github.com/boai/BAWeChat/blob/master/Images/评论.png)

- [TGTV](https://github.com/targetcloud/TGTV) - TGTV直播APP用Swift3.1编写，采用MVVM架构，本demo运用protobuf实现即时聊天（弹幕）、礼物动画等。
<div align=left >
<img src="https://github.com/targetcloud/TGTV/blob/master/1.gif" width=300/> <img src="https://github.com/targetcloud/TGTV/blob/master/屏幕快照%202017-04-13%20下午5.22.09.png" width=300 />
</div>

- [PLMediaStreamingKit](https://github.com/pili-engineering/PLMediaStreamingKit) - PLMediaStreamingKit 是七牛推出的一款适用于 iOS 平台的推流 SDK，支持 RTMP 推流，h.264 和 AAC 编码，硬编、软编支持。具有丰富的数据和状态回调，方便用户根据自己的业务定制化开发。具有直播场景下的重要功能，如：美颜、背景音乐、水印等功能。

### 蓝牙

- [EasyBluetooth]( https://github.com/chenliangloveyou/EasyBluetooth) - 一款iOS BLE蓝牙调试工具，非常简单容易，也可以作为一个蓝牙库，快速集成和开发。 可以两步搞定蓝牙开发操作。第一步连接设备，第二步特征读写数据。<br />
![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_1.gif) ![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_2.gif) <br />
![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_3.png) ![](https://github.com/chenliangloveyou/EasyBluetooth/blob/master/EasyBlueTooth/EasyBlueTooth/preview/preview_4.png) 

- [WHBLEDemo](https://github.com/remember17/WHBLEDemo) - 📱CoreBluetooth central and peripheral demo with OC/Swift (iOS蓝牙中心设备和外设开发,包含OC/Swift版本) 。
<div  align=left >
<img src="https://camo.githubusercontent.com/3ba378f9a697f5e30d6937f64ba8a97498bb3513/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d613731636537393634653834613263652e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="50%" />
<img src="https://camo.githubusercontent.com/47b0012be03c0f3f6c59c7169fa4563ff6380d7c/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d353334626433303463346537393765362e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width="50%" />
</div>

- [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 简单易用的蓝牙库，基于CoreBluetooth的封装，并兼容ios和mac osx。<br />
![](https://github.com/coolnameismy/BabyBluetooth/blob/master/logo.png)

- [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE.

- [MultipeerConnectivity](https://github.com/xiangzuhua0209/MultipeerConnectivity) - 蓝牙MultipeerConnectivity。

### 扫码器

- [MMScan](https://github.com/MinMao-Hub/MMScan) - 一个简单的二维码以及条码扫描工具，使用Objective-C语言开发，有一套自定义的扫描动画以及界面，还包括生成二维码以及条码。<br />
![](https://github.com/MinMao-Hub/MMScan/blob/master/gifs/mmscan.gif)

- [QRCode](https://github.com/kingcong/QRCode-master) - 仿微信二维码扫描。

- [LBXScan](https://github.com/MxABC/LBXScan) - A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing、ZBar、iOS系统AVFoundation扫码封装，扫码界面效果封装)。<br>
![](https://github.com/MxABC/Resource/blob/master/scan12.gif)

- [swiftScan](https://github.com/dgynfi/swiftScan) - A barcode and qr code scanner( 二维码 各种码识别，生成，界面效果)。<br />
![](https://github.com/MxABC/swiftScan/blob/master/ScreenShots/page1.jpg) ![](https://github.com/MxABC/swiftScan/blob/master/ScreenShots/page4.jpg)

- [SGQRCode](https://github.com/kingsic/SGQRCode) - The easy to use QRCode scan library for iOS【iOS 原生二维码生成与扫描 -> 高仿微信】。
<div align=left>
<img src="https://raw.githubusercontent.com/kingsic/SGQRCode/master/Picture/sorgle1.png" width="40%" /> <img src="https://raw.githubusercontent.com/kingsic/SGQRCode/master/Picture/sorgle4.png" width="40%" />
</div>

- [EFQRCode](https://github.com/EFPrefix/EFQRCode) - A better way to operate QR Code in Swift, support iOS, macOS, watchOS and tvOS. 
<div align=left>
<img src="https://raw.githubusercontent.com/EFPrefix/EFQRCode/assets/QRCodeGIF6.gif" width="20%" />
</div>

### 安全密码算法

- [DYFCryptoUtils](https://github.com/dgynfi/DYFCryptoUtils) - 一行代码实现 iOS Base64, MD5, DES, AES, RSA算法。

- [AESCipher-iOS](https://github.com/WelkinXie/AESCipher-iOS) - AES encryption working between Objective-C and Java.

- [RSADemo](https://github.com/DullDevil/RSADemo) - RSA加解密相关方方法，以及密钥格式的生成与转换。

- [Encryptions](https://github.com/iamlay/Encryptions) - this project is for many kinds odf encryption. <br />
![](https://github.com/iamlay/Encryptions/blob/master/Encryption/encryption.gif)

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - CryptoSwift是在Swift中实现的越来越多的标准和安全密码算法的集合。 

### Others

- [iOSProject](https://github.com/NJHu/iOSProject) - iOS project of collected some demos for iOS App.（[Swift版](https://github.com/dgynfi/WRNavigationBar_swift)）
<div align=left>
<img src="https://raw.githubusercontent.com/NJHu/iOSProject/master/images//home.gif" width=300 /> <img src="https://raw.githubusercontent.com/NJHu/iOSProject/master/images/anidynquar.gif" width=300 />
</div>

- [IAPHelper](https://github.com/saturngod/IAPHelper) - IAP helper for Apple in app purchases. It uses ARC and blocks for ease of use. Ready to use with newsstand subscriptions. No more maintenance for this repo. Please use the [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)

- [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - SwiftyStoreKit is a lightweight In App Purchases framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+. 
<div align=left>
<img src="https://github.com/bizz84/SwiftyStoreKit/raw/master/Screenshots/Preview.jpg" width="50%" />
</div>

- [XHPayKit](https://github.com/CoderZhuXH/XHPayKit) - 不用官方SDK实现微信支付、支付宝支付。

- [NNMacros](https://github.com/amisare/NNMacros) - NNMacros通过宏的方式来简化iOS开发中OC的语法和Api的操作。

- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - 一个可以很容易地为iOS创建漂亮的、高度可定制的动画复选框。<br />
![](https://github.com/Boris-Em/BEMCheckBox/blob/master/.assets/BEMCheckBox.gif)

- [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 向UIView对象类添加Toast通知的Swift扩展。<br />
![](https://github.com/scalessec/Toast-Swift/blob/master/toast_swift_screenshot.jpg)

- [EasyShowView](https://github.com/chenliangloveyou/EasyShowView) - 一款超级简单的展示工具，包括吐丝指示器，loding加载框，空白页提示，alertview，actionsheet的定制。可任意定制自己想要的各种样式，自定义动画，显示样式等各种操作，使各种展示更加easy。<br />
![](https://github.com/chenliangloveyou/EasyShowView/blob/master/show_preview/preview_text.gif)  ![](https://github.com/chenliangloveyou/EasyShowView/blob/master/show_preview/preview_loding.gif)

- [SDPhotoBrowser](https://github.com/gsdios/SDPhotoBrowser) - A image browser which is easy for using. 非常简单易用的图片浏览器，模仿微博图片浏览器动感效果，综合了图片展示和存储等多项功能。<br />
![](https://camo.githubusercontent.com/a2e87ee4bd1c7b97913e2f9de8b416302032157c/687474703a2f2f63646e2e636f63696d672e636f6d2f6262732f6174746163686d656e742f4669645f31392f31395f3434313636305f3633313963353063333465643633632e676966)

- [YHPhotoBrowser](https://github.com/hackxhj/YHPhotoBrowser) - 轻量级网络图片浏览器 优化性能 Gif播放性能 类新浪微博打开关闭动画 类微信图片浏览下拉图片消失。<br />
![](https://raw.githubusercontent.com/hackxhj/YHPhotoBrowser/master/png/yh.gif) 

- [SensorDemo](https://github.com/wsl2ls/SensorDemo) - 指纹识别、运动传感器、加速计、环境光感、距离传感器、指南针、陀螺仪等传感器示例集锦。<br />
![](https://camo.githubusercontent.com/339dfa9c656084dc5d29496ec168c43426a8e201/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d373764333332623832386363336261332e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970)

- [BAPrivacyManager](https://github.com/boai/BAPrivacyManager) - iOS 所有隐私权限封装，定位、蓝牙、通知、运动、日历、相册、相机等 14 种权限封装！
<div align=left >
<img src="https://github.com/BAHome/BAPrivacyManager/blob/master/Images/BAPrivacyManager1.png" width="50%" />
</div>

- [RSSliderView](https://github.com/rsimenok/RSSliderView) - Custom slider based on UIView for iOS. <br />
![](https://camo.githubusercontent.com/7a7a899104ae97a30b0aae97bb2ce7d80a8a0f25/687474703a2f2f692e70696363792e696e666f2f69392f61666463643862353032396531663238623862643333663762643338323263312f313432343131383133392f31323632322f3738303432352f3132332e706e67)

- [ZLSecurityCode](https://github.com/ZLFighting/ZLSecurityCode) - iOS-字符图片验证码。<br />
![](https://github.com/ZLFighting/ZLSecurityCode/blob/master/ZLSecurityCode/验证码图.gif)

- [ZZHotKeysMenu](https://github.com/zhouXiaoR/ZZHotKeysMenu) - ZZHotKeysMenu自定义布局，继承自UICollectionViewLayout。<br />
![](https://github.com/zhouXiaoR/ZZHotKeysMenu/blob/master/运行效果.gif)

- [LCSlideMenu](https://github.com/ChinaHackers/LCSlideMenu) - A powerful and easy to use slider menu. 
<div align=left>
<img src="https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/LCSlideMenu.png" width="70%" />
<img src="https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast01.gif" width="40%" /> <img src="https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast03.gif" width="40%" />
</div>

- [JMColumnMenu](https://github.com/JunAILiang/JMColumnMenu) - 仿腾讯新闻、今日头条栏目管理。

- [MLMenu](https://github.com/MrDML/MLMenu) - 仿微信QQ右上角菜单功能。
<div align=left>
<img src="https://github.com/MrDML/MLMenu/blob/master/MLMenuGif.gif" width="50%" />
</div>

- [JMDropMenu](https://github.com/JunAILiang/JMDropMenu) - 仿QQ、微信下拉菜单封装，支持自定义样式。
<div align=left>
<img src="https://raw.githubusercontent.com/JunAILiang/JMDropMenu/master/JMDropMenu/JMDropMenu.gif" width="50%"  />
</div>

- [XYMenu](https://github.com/HeathHsia/XYMenu) -  简易集成的弹出菜单。<br />
![](https://github.com/HeathHsia/XYMenu/blob/master/img/demo.gif)

- [SHESelectTable](https://github.com/shelly8219/SHESelectTableDemo) - 下拉选择的列表。
<div align=left>
<img src="https://github.com/shelly8219/SHESelectTableDemo/blob/master/source/screenclip.jpg" width="50%" />
</div>

- [MMPopupView](https://github.com/adad184/MMPopupView) - A basic Pop-Up Kit allows you to easily create Pop-Up view. You can focus on the only view you want to show.Besides, it comes with 2 common Pop-Up view, MMAlertView & MMSheetView. You can easily use & customize it. <br />
![](https://github.com/adad184/MMPopupView/blob/master/Images/0.jpg) 

- [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) - iOS平台利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志。<br />
![](https://github.com/Lede-Inc/LDNetDiagnoService_IOS/blob/master/LDNetDiagnoServiceDemoTests/netdiagnosis_ios.jpg)

- [ZLAdvertDemo](https://github.com/ZLFighting/ZLAdvertDemo) - 启动页加载广告。<br />
![](https://github.com/ZLFighting/ZLAdvertDemo/blob/master/ZLAdvertDemo/启动页跳过广告.gif)

- [XDProgressView](https://github.com/Tbwas/XDProgressView) - XDProgressView可以由你心情任意设置高度，也可在上面显示文字。

- [iOS-getClientInfo](https://github.com/PengfeiWang666/iOS-getClientInfo) - 📲iOS中获取各种设备信息。

- [TOSMBClient](https://github.com/TimOliver/TOSMBClient) -  A small library that serves as a simple SMB (Server Message Block ) client for iOS apps. The library allows connecting to SMB devices, downloading file metadata, and subsequently allows asynchronous downloading of files from an SMB device straight to an iOS device. It is an Objective-C wrapper around Defective SMb, or libDSM, a low level SMB client library built in C built by some of VideoLabs' developers. A copy of libDSM has been specially cross-compiled for iOS device architectures and embedded in this library, so this project has no external dependencies.

- [dSYMTools](https://github.com/answer-huang/dSYMTools) - dSYM analyze. <br />
![](https://camo.githubusercontent.com/e4d2bc52e9f048c7c14af6cfc4339f055fab5e38/687474703a2f2f616e737765726875616e672e626a2e626365626f732e636f6d2f626c6f672f6473796d546f6f6c2e706e67)

- [iOSAnimation](https://github.com/BranPeng/iOSAnimation) - 好玩的iOS动画。

- [iOS-Swift-Animation](https://github.com/BranPeng/iOS-Swift-Animation) - iOS Swift动画框架。

- [iOS-Swift-UI](https://github.com/BranPeng/iOS-Swift-UI) - iOS-Swift-UI。

- [iOS-Project](https://github.com/BranPeng/iOS-Project) - 收集的一些比较好的iOS打样工程。

- [iOS_Demo](https://github.com/darren90/iOS_Demo) - iOS开发中一些实用的Demo。

- [LYThemeChange](https://github.com/lanyasheng/LYThemeChange) - 主题更换。


## H5

- [canvas](https://github.com/airingursb/canvas) - 《Canvas：Draw on the Web》，[本书GitBook]( https://airingursb.gitbooks.io/canvas/)


## Flutter

### Flutter && Dart

- [Flutter中文网](https://flutterchina.club) 
- [Flutter SDK Archive](https://flutter.io/sdk-archive/#macos) 
- [Dart Packages](https://pub.flutter-io.cn)
- [Dart2 中文文档](https://www.kancloud.cn/marswill/dark2_document/709087) 

### Flutter Project

- [dart_crypto](https://github.com/dgynfi/dart_crypto) - 🔥集成Base64, MD5, AES, RSA等算法。

- [grab_ethtoken_info](https://github.com/dgynfi/grab_ethtoken_info) - 🔥爬取etherscan的一个钱包地址的所有token信息( address, name, balance, symbol, value)，并编写界面进行展示。

- [flutter_study](https://github.com/dgynfi/flutter_study) - Flutter基础，Dart基础，实践教学 <br />
![](https://raw.githubusercontent.com/luhenchang/IMAGE/master/img_bizhan/WeChat3d4501c5ea03165d48b5270ac7944463.png)


## 比特币 & 以太坊（区块链）

- [go-ethereum](https://github.com/ethereum/go-ethereum)  - 以太坊协议的官方的Go语言实现。<br />
   [Download Geth](https://geth.ethereum.org/downloads/) - Binary archives are published.

- [web3swift](https://github.com/BANKEX/web3swift) - Elegant Web3js functionality in Swift. Native ABI parsing and smart contract interactions on Ethereum network ([web3.swift-Example](https://github.com/MercuryProtocol/web3.swift-Example) - Example on how to use web3.swift). <br />
![](https://user-images.githubusercontent.com/3356474/34412791-5b58962c-ebf0-11e7-8460-5592b12e6e9d.png)

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

- [HuPaiMJ](https://github.com/pinorr/HuPaiMJ) - C++麻将胡牌算法 优点：1.速度快，900万次多赖子胡牌用时500ms左右。2.支持多个赖子。3.查错方便，直接查表就可知道。


## cocos2d

- [cocos2d-x](https://github.com/cocos2d/cocos2d-x) - Cocos2d-x is a suite of open-source, cross-platform, game-development tools used by millions of developers all over the world. http://www.cocos2d-x.org.<br />
  ![](https://github.com/cocos2d/cocos2d-x/blob/v3/docs/framework_architecture.jpg)


## C++

- [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.


## Script

### Python

- [xlrd](https://github.com/python-excel/xlrd) - Library for developers to extract data from Microsoft Excel (tm) spreadsheet files. [python-excel](http://www.python-excel.org)

- [xlwt](https://github.com/python-excel/xlwt) - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform. [python-excel](http://www.python-excel.org)

- [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - [A Python module for creating Excel XLSX files. ](https://xlsxwriter.readthedocs.io)

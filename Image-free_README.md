[如果你觉得能帮助到你，请给一颗小星星。谢谢！(If you think it can help you, please give it a star. Thanks!)](https://github.com/dgynfi/OpenSource)

[![License MIT](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](LICENSE)&nbsp;

## OpenSource

🔥🔥🔥 👍👍👍

汇总好用的开源项目，涵盖了iOS, Mac, Blockchain, Flutter, Weex, H5, Games, C++, Script等各个方面的内容，其中，iOS包涵以下几个方面：
1. 常用第三方库：AFNetworking & Alamofire, SDWebImage, ReactiveCocoa & RxSwift, Masonry & SnapKit, YYKit；
2. 导航栏和状态栏；
3. 侧边菜单 (Side Menu) ；
4. 支付: 内购 (IAP), ApplePay和第三方支付；
5. 播放器: 视频播放器和音乐播放器；
6. IM和直播；
7. 数据持久 (Data Persistence) ；
8. 逆向开发；
9. 安全攻防和应用加固, 数据安全和算法；
10. 蓝牙, 手势指纹面容ID密码解锁, 图像渲染和绘制 (OpenGLES, Metal, GPUImage, CoreGraphics), 图片浏览器, 扫码器, 下拉刷新和上拉加载, 指示器, Toast, Menu和弹出视图, WebView和进度条, 动画, 选择器, 搜索, 分享, 图片验证码, 获取设备相关信息, 广告, Sensor, Privacy, 高仿项目和项目Demo。

🔥🔥🔥 👍👍👍

## 目录

- [iOS](#iOS)
   - [常用第三方库](#常用第三方库)
      - [AFNetworking和Alamofire](#AFNetworking和Alamofire)
      - [SDWebImage](#SDWebImage)
      - [ReactiveCocoa和RxSwift](#ReactiveCocoa和RxSwift)
      - [Masonry和SnapKit](#Masonry和SnapKit)
      - [YYKit](#YYKit)
   - [网络相关](#网络相关)
   - [导航栏和状态栏](#导航栏和状态栏)
   - [Side Menu](#Side-Menu)
   - [支付](#支付)
      - [内购IAP](#内购IAP)
      - [ApplePay](#ApplePay)
      - [第三方支付](#第三方支付)
   - [播放器](#播放器)
      - [视频播放器](#视频播放器) 
      - [音乐播放器](#音乐播放器)
   - [IM和直播](#IM和直播)
   - [Data Persistence](#Data-Persistence)
   - [逆向开发](#逆向开发)
      - [fishhook](#fishhook)
      - [逆向辅助工具](#逆向辅助工具)
      - [逆向案例](#逆向案例)
   - [安全攻防和应用加固](#安全攻防和应用加固)
   - [数据安全和算法](#数据安全和算法)
   - [蓝牙](#蓝牙)
   - [手势指纹面容ID密码解锁](#手势指纹面容ID密码解锁)
   - [布局](#布局)
   - [图像渲染和绘制](#图像渲染和绘制)
      - [OpenGLES](#OpenGLES)
      - [Metal](#Metal)
      - [GPUImage](#GPUImage)
      - [CoreGraphics](#CoreGraphics)
   - [图像模糊化](#图像模糊化)
   - [图片浏览器](#图片浏览器)
   - [扫码器](#扫码器)
   - [下拉刷新和上拉加载](#下拉刷新和上拉加载)
   - [指示器](#指示器)
   - [Toast](#Toast)
   - [Menu和弹出视图](#Menu和弹出视图)
   - [WebView和进度条](#WebView和进度条)
   - [动画](#动画)
   - [选择器](#选择器)
   - [搜索](#搜索)
   - [分享](#分享)
   - [图片验证码](#图片验证码)
   - [获取设备相关信息](#获取设备相关信息)
   - [广告](#广告)
   - [高仿项目和项目Demo](#高仿项目和项目Demo)
   - [Others](#Others)
      - [Sensor](#Sensor)
      - [Privacy](#Privacy)
      - [未归类](#未归类)
      - [其他汇总](#其他汇总)
   - [类目](#类目)
   - [越狱检测](#越狱检测)
- [Mac](#Mac)
- [区块链](#区块链)
- [Flutter](#Flutter)
    - [Flutter和Dart](#Flutter和Dart)
    - [Flutter Project](#Flutter-Project)
- [Weex](#Weex)
- [H5](#H5)
- [游戏](#游戏)
   - [Cocos2d](#Cocos2d)
   - [棋牌](#棋牌)
   - [游戏示例](#游戏示例)
- [C-plus-plus](#C-plus-plus)
- [Script](#Script)
   - [Shell](#Shell)
   - [Python](#Python)


## iOS

### 常用第三方库

#### AFNetworking和Alamofire

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful networking framework for iOS, macOS, watchOS, and tvOS. 

**NSURLSession:**
- `AFURLSessionManager `
- `AFHTTPSessionManager`

**Security:**
- `AFSecurityPolicy`

**Reachability:**
- `AFNetworkReachabilityManager`

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
- Adding properties in the form of catagory.

---

- [Alamofire](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift.

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

#### SDWebImage

- [SDWebImage](https://github.com/SDWebImage/SDWebImage) - This library provides an async image downloader with cache support. For convenience, we added categories for UI elements like UIImageView, UIButton, MKAnnotationView ([Examples](https://github.com/SDWebImage/SDWebImage/tree/master/Examples)). 

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

#### ReactiveCocoa和RxSwift

*响应式编程*

- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Reactive extensions to Cocoa frameworks, built on top of [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)), It Offers composable, declarative and flexible primitives that are built around the grand concept of streams of values over time. These primitives can be used to uniformly represent common Cocoa and generic programming patterns that are fundamentally an act of observation. 

- [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift ([RxExample](https://github.com/ReactiveX/RxSwift/tree/master/RxExample)). 
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

#### Masonry和SnapKit

*链式编程，AutoLayout*

- [Masonry](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax. Supports iOS and OSX Auto Layout.
```ObjC
UIEdgeInsets padding = UIEdgeInsetsMake(10, 10, 10, 10);

[view1 mas_makeConstraints:^(MASConstraintMaker *make) {
    make.top.equalTo(superview.mas_top).with.offset(padding.top); //with is an optional semantic filler
    make.left.equalTo(superview.mas_left).with.offset(padding.left);
    make.bottom.equalTo(superview.mas_bottom).with.offset(-padding.bottom);
    make.right.equalTo(superview.mas_right).with.offset(-padding.right);
}];
```

- [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & OS X ([http://snapkit.io](http://snapkit.io).
```Swift
import SnapKit

class MyViewController: UIViewController {
    lazy var box = UIView()

    override func viewDidLoad() {
        super.viewDidLoad()
        self.view.addSubview(box)
        box.snp.makeConstraints { (make) -> Void in
            make.width.height.equalTo(50)
            make.center.equalTo(self.view)
        }
    }
}
```

#### YYKit

- [YYKit](https://github.com/ibireme/YYKit) - 一组庞大、功能丰富的 iOS 组件。
    - [YYModel](https://github.com/ibireme/YYModel) - 高性能的 iOS JSON 模型框架。
    - [YYCache](https://github.com/ibireme/YYCache) - 高性能的 iOS 缓存框架。
    - [YYImage](https://github.com/ibireme/YYImage)  - 功能强大的 iOS 图像框架。
    - [YYWebImage](https://github.com/ibireme/YYWebImage) - 高性能的 iOS 异步图像加载框架。
    - [YYText](https://github.com/ibireme/YYText) - 功能强大的 iOS 富文本框架。
    - [YYKeyboardManager](https://github.com/ibireme/YYKeyboardManager) - iOS 键盘监听管理工具。
    - [YYDispatchQueuePool](https://github.com/ibireme/YYDispatchQueuePool) - iOS 全局并发队列管理工具。
    - [YYAsyncLayer](https://github.com/ibireme/YYAsyncLayer) - iOS 异步绘制与显示的工具。
    - [YYCategories](https://github.com/ibireme/YYCategories) - 功能丰富的 Category 类型工具库。

### 网络相关

*网络相关内容：AFNetworking的封装，NSURLSession的封装, Reachability, CocoaHTTPServer, GCDWebServer.*

- [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests.

- [BANetManager](https://github.com/boai/BANetManager) - 基于[AFNetworking](#AFNetworking和Alamofire) 3.0、3.1最新版本的封装，集成了 get / post / put / delete 方法请求数据，单图/多图上传，视频上传/下载，网络监测 等多种网络请求方式。

- [HYBNetworking](https://github.com/CoderJackyHuang/HYBNetworking) - 基于AFNetworking3.0以上版本封装的网络层。提供常用的GET/POST接口、上传下载图片、文件接口、支持缓存等。

- [HLNetworking](https://github.com/wangshiyu13/HLNetworking) - 基于[AFNetworking](#AFNetworking和Alamofire)的高阶网络请求管理器。

- [CCPAFNNetworking](https://github.com/iccpeng/CCPAFNNetworking) -  [AFN](#AFNetworking和Alamofire)与MBProgressHUD的组合使用。

- [Reachability](https://github.com/tonymillion/Reachability) - ARC and GCD Compatible Reachability Class for iOS and MacOS. Drop in replacement for Apple Reachability.

- [CocoaWebResource](https://github.com/robin/cocoa-web-resource) - A file transfer solution for iPhone and iPod Touch. Support uploading, download and delete files via browser.

- [GCDWebServer](https://github.com/swisspol/GCDWebServer) - A modern and lightweight GCD based HTTP 1.1 server designed to be embedded in iOS, macOS & tvOS apps. 

- [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for Mac OS X or iOS applications.

### 导航栏和状态栏

- [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) - 超简单！！！ 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等。([Swift版](https://github.com/wangrui460/WRNavigationBar_swift))

- [NNNavigationBar](https://github.com/amisare/NNNavigationBar) - 实现导航条背景渐变过渡动画的轻量级框架。

- [RTRootNavigationController](https://github.com/rickytan/RTRootNavigationController) - Implicitly make every view controller has its own navigation bar. 

- [GKNavigationController](https://github.com/QuintGao/GKNavigationController) - iOS自定义导航栏-导航条联动（仿网易新闻、网易云音乐等导航栏滑动效果）。

- [EasyNavigation](https://github.com/chenliangloveyou/EasyNavigation) - 一款超级简单的导航条管理工具。完全自定义导航条。没有UINavigationBar 和 UINavigationItem 这两个类。完全是对UIView的操作。 所有操作都能一行代码，操作之间完全独立，互不影响。

- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. 

- [JZNavigationExtension](https://github.com/JazysYu/JZNavigationExtension) - JZNavigationExtension integrates some convenient features for UINavigationController and easy to use.

- [BBGestureBack](https://github.com/Bonway/BBGestureBack) - OC and Swift full screen return gesture（纯OC 和 纯Swift编写，类淘宝、京东等全屏滑动返回效果）。

### Side Menu

- [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) - A lightweight, easy to use, Side Drawer Navigation Controller.

- [RESideMenu](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect.

### 支付

#### 内购IAP

- [RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases.

- [MKStoreKit](https://github.com/MugunthKumar/MKStoreKit) - The "Goto" In App Purchases Framework for iOS 8+.

- [IAPHelper](https://github.com/saturngod/IAPHelper) - IAP helper for Apple in app purchases. It uses ARC and blocks for ease of use. Ready to use with newsstand subscriptions. No more maintenance for this repo. Please use the [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)

- [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - SwiftyStoreKit is a lightweight In App Purchases framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+. 

- [Receipt Validation Programming Guide](https://developer.apple.com/library/archive/releasenotes/General/ValidateAppStoreReceipt/Introduction.html#//apple_ref/doc/uid/TP40010573-CH105-SW1)

- [VerifyStoreReceiptiOS](https://github.com/rmaddy/VerifyStoreReceiptiOS) - A helper class for verifying App Store receipts under iOS.

#### ApplePay

- [YasinZhou - ApplePayDemo](https://github.com/YasinZhou/ApplePayDemo) - ApplePay苹果支付demo。

- [lintide - ApplePayDemo](https://github.com/lintide/ApplePayDemo) -  Apple Pay demo 苹果支付示例。

- [ApplePayExample](https://github.com/jflinter/ApplePayExample) -  ApplePay Example.

- [iTofu - ApplePayDemo](https://github.com/iTofu/ApplePayDemo) -   Pay Demo with Swift. 

#### 第三方支付

- [XHPayKit](https://github.com/CoderZhuXH/XHPayKit) - 不用官方SDK实现微信支付、支付宝支付。

- [PayDemo](https://github.com/codewpf/PayDemo) - 支付宝和微信支付两种方式集成。

### 播放器

#### 视频播放器

- [CLPlayer](https://github.com/JmoVxia/CLPlayer) - 自定义支持全屏的播放器。

- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support ([FFmpeg](http://ffmpeg.org)).

- [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Support customization of any player SDK and control layer (支持定制任何播放器SDK和控制层)。

- [BMPlayer](https://github.com/BrikerMan/BMPlayer) - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brightness and seek by slide, support subtitles.

- [SJVideoPlayer](https://github.com/changsanjiang/SJVideoPlayer) - Video Player. Support cocoapods & Generate GIF & Export & Localization & Play in View(UIView || TableHeader || TableCell || CollectionCell) & Keyboard Orientation & StatusBar(Style&Hide).

- [kxmovie](https://github.com/kolyvan/kxmovie) - movie player for iOS using ffmpeg.

- [ffmpeg-avplayer-for-ios-tvos](https://github.com/imoreapps/ffmpeg-avplayer-for-ios-tvos) - A tiny but powerful iOS and Apple TV OS av player framework that's based on the FFmpeg library. 

- [Eleven](https://github.com/kaixinsoft/Eleven) - Eleven Player is a simple powerful video player.use ffmpeg.
  - [iOS配置FFmpeg框架](http://cnbin.github.io/blog/2015/05/19/iospei-zhi-ffmpegkuang-jia/) 
  - [Vitamio测试网络视频地址](https://www.vitamio.org/docs/Basic/2013/0508/14.html) 
    
- [SBPlayer](https://github.com/henusjj/SBPlayer) - 基于AVPlayer封装的轻量级播放器，可以播放本地网络视频，易于定制，可以横屏竖屏，支持M3u8、mp4等格式视频本地播放或者网络播放，通过masonry约束，适配各种尺寸iPhone。

- [VKVideoPlayer](https://github.com/viki-org/VKVideoPlayer) - he same battle tested video player used in our [Viki iOS App](https://itunes.apple.com/app/id445553058?mt=8) enjoyed by millions of users all around the world.

- [KRVideoPlayer](https://github.com/36Kr-Mobile/KRVideoPlayer) - 类似Weico的播放器，支持竖屏模式下全屏播放。

- [PBJVideoPlayer](https://github.com/piemonte/PBJVideoPlayer) - ▶️ video player, simple way to play and stream media on iOS/tvOS.

- [MRVLCPlayer](https://github.com/Maru-zhang/MRVLCPlayer) - 一款基于VLC的播放器,支持常用的各大手势功能，支持几乎所有主流格式。

- [ALMoviePlayerController](https://github.com/lobianco/ALMoviePlayerController) -  A drop-in replacement for MPMoviePlayerController that exposes the UI elements and allows for maximum customization.

#### 音乐播放器

- [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS (iPhone, iPad).

- [LyricsAnalysis](https://github.com/wsl2ls/LyricsAnalysis) - iOS音乐播放器之锁屏效果（仿网易云音乐和QQ音乐）+ 歌词解析 ：锁屏歌曲信息、控制台远程控制音乐播放：暂停/播放、上一首/下一首、快进/快退、列表菜单弹框和拖拽控制台的进度条调节进度（结合了QQ音乐和网易云音乐在锁屏状态下的效果）、歌词解析并随音乐滚动显示。

- [GKWYMusic](https://github.com/QuintGao/GKWYMusic) - iOS基于FreeStreamer的仿网易云音乐播放器。

- [ios-audio-remote-control](https://github.com/MosheBerman/ios-audio-remote-control) - This repo demonstrates how to control the software based audio remote control in iOS.

### IM和直播

- [AtChat](https://github.com/boyssimple/AtChat) - IOS聊天项目、基于XMPP框架开发，实现了登陆注册(注册以手机号码注册、短信验证) 、发送消息、接收消息、接收好友请求、发起好友请求 、图片消息、语音消息、视频语音、聊天历史记录、最近联系人、二维码添加好友、用户头像上传、朋友圈、发朋友圈、异地登录退出等功能。

- [BAWeChat](https://github.com/BAHome/BAWeChat) - 博爱微信，使用原生 frame + MVVM + MVC + QMUIKit + BAKit 开源的微信。

- [MomentKit](https://github.com/ChellyLau/MomentKit) - MVC模式实现WeChat朋友圈功能，代码整洁易读。支持富文本(链接/表情/电话/邮箱等)、点赞、评论/回复评论、图片预览、文字拷贝等功能。

- [ABigFishTV](https://github.com/clyhs/ABigFishTV) - 大鱼电视直播 基于ijkplayer的播放器 700多个电视台 包括央视，各地方台，卫视，熊猫直播，社会化分享，登陆，仿微博等 (支持iphonex)。

- [TGTV](https://github.com/targetcloud/TGTV) - TGTV直播APP用Swift3.1编写，采用MVVM架构，本demo运用protobuf实现即时聊天（弹幕）、礼物动画等。

- [MGMiaoBo](https://github.com/LYM-mg/MGMiaoBo) - 首创房间内多视频直播模式，移动直播新体验，多人秀场更好玩。随时随地与主播聊天互动亲密接触，清纯美女、校花嫩模、吃货萌妹、通通都有…… 1.项目引导页业使用ijkPlayer播放视频；2.首页使用父子控制器进行界面之间的切换；3.自定义MJRefresh刷新控件，替换头部刷新gif图片；4.使用分类理由贝塞尔曲线为UIImageView添加圆角；5.服务器交互使用的是https，用json格式，面向模型开发;其他：全局网络请求封装，页面数据缓存处理，通知，动画，基础控制器封装，使用xib的AutoLayout和Masonry第三方库等。

- [MGDYZB](https://github.com/LYM-mg/MGDYZB) - Xcode8以上版本，已升级为Swift3.x语法。斗鱼-每个人的直播平台提供高清、快捷、流畅的视频直播和游戏赛事直播服务，包含英雄联盟lol直播、穿越火线cf直播、dota2直播、美女直播等各类热门游戏赛事直播等。

- [PLPlayerKit](https://github.com/pili-engineering/PLPlayerKit) - PLPlayerKit 是七牛推出的一款免费的适用于 iOS 平台的播放器SDK，采用全自研的跨平台播放内核，拥有丰富的功能和优异的性能，可高度定制化和二次开发。([ios-playback-end-the-sdk](https://developer.qiniu.com/pili/sdk/1211/ios-playback-end-the-sdk))

- [PLMediaStreamingKit](https://github.com/pili-engineering/PLMediaStreamingKit) - PLMediaStreamingKit 是七牛推出的一款适用于 iOS 平台的推流 SDK，支持 RTMP 推流，h.264 和 AAC 编码，硬编、软编支持。具有丰富的数据和状态回调，方便用户根据自己的业务定制化开发。具有直播场景下的重要功能，如：美颜、背景音乐、水印等功能。

### Data Persistence

*DB, Keychain, NSUserDefaults, Write*

- [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS, watchOS, tvOS and macOS. Makes using Keychain APIs as easy as NSUserDefaults.

- [GenericKeychain](https://developer.apple.com/library/archive/samplecode/GenericKeychain/Introduction/Intro.html) - This sample shows how to add, query for, remove, and update a keychain item of generic class type. It also demonstrates the use of shared keychain items.

- [fmdb](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite.

- [JQFMDB](https://github.com/gaojunquan/JQFMDB) - FMDB的封装，操作简单，线程安全，扩展性强，直接操作model或dictionary。

### 逆向开发

#### fishhook

- [fishhook](https://github.com/facebook/fishhook) - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS. 

#### 逆向辅助工具

- [iOSOpenDev](http://iosopendev.com) - [Github](https://github.com/kokoabim/iOSOpenDev)
- [theos](http://iphonedevwiki.net/index.php/Theos/Setup) - 一个越狱开发工具包 ([Github](https://github.com/theos/theos).)
- [class-dump](https://github.com/nygard/class-dump) - Generate Objective-C headers from Mach-O files. 
- [Clutch](https://github.com/KJCracks/Clutch) - a high-speed iOS decryption tool. It supports the iPhone, iPod Touch, and iPad.
- [optool](https://github.com/alexzielenski/optool) - Command Line Tool for interacting with MachO binaries on OSX/iOS.
- [Hook-Tools](https://github.com/dgynfi/WeChat_tweak/tree/master/Hook-Tools)
- [HackAppTool](https://github.com/jackrex/FakeWeChatLoc/tree/master/HackAppTool) 
- [Tools](https://github.com/east520/AutoGetRedEnv/tree/master/Tools)

#### 逆向案例

- [WeChat_tweak](https://github.com/dgynfi/WeChat_tweak) - iOS 版功能较全的微信插件，具备抢红包，修改微信运动步数，伪定位（朋友圈和附近的人），屏蔽消息和群消息，过滤群，防撤回消息和信息内容页的背景透明等功能。

- [WeChatRedEnvelop](https://github.com/buginux/WeChatRedEnvelop) - iOS版微信抢红包Tweak。
    - [iOS微信抢红包Tweak安装教程](http://www.swiftyper.com/2016/01/25/ios-tweak-install-guide)
    - [免越狱版 iOS 抢红包插件](http://www.swiftyper.com/2016/12/26/wechat-redenvelop-tweak-for-non-jailbroken-iphone)

- [FakeWeChatLoc](https://github.com/jackrex/FakeWeChatLoc) - iOS伪装微信位置。
    - [iOS逆向论坛](http://bbs.iosre.com) 

- [FakeWeChatLocation](https://github.com/PandaraWen/FakeWeChatLocation) - A tweak that can fake location info in WeChat.

- [WeChatRedEnvelopesHelper](https://github.com/luckysine/WeChatRedEnvelopesHelper) - iOS版微信抢红包插件，支持后台抢红包，tweak源文件。

- [AutoGetRedEnv](https://github.com/east520/AutoGetRedEnv) - 微信自动抢红包。

- [WXAccountSwitcher](https://github.com/iosre/WXAccountSwitcher) - Fast switch WeiXin account.

- [FishChat](https://github.com/yulingtianxia/FishChat) - Hook WeChat.app on non-jailbroken devices. ([blog](http://yulingtianxia.com/blog/2017/02/28/Make-WeChat-Great-Again/)) 
    
- [WeTransparentChat](https://github.com/PandaraWen/WeTransparentChat) - Use back camera capturing make WeChat's message content page's background transparent.

### 安全攻防和应用加固

- [mixplaintext](https://github.com/danleechina/mixplaintext) - 对 Xcode 项目工程所有的 objective-c 文件内包含的明文进行加密混淆，提高逆向分析难度。

- [iOS app 进行安全加固](https://danleechina.github.io/ios-app-security-reinforce/) 

- [iOS安全攻防（四）：阻止GDB依附](https://blog.csdn.net/yiyaaixuexi/article/details/18222339) 
- [iOS安全攻防（九）：使用Keychain-Dumper导出keychain数据](https://blog.csdn.net/yiyaaixuexi/article/details/18404343)
- [iOS安全攻防（十三）：数据擦除](https://blog.csdn.net/yiyaaixuexi/article/details/18669201)
- [iOS安全攻防（十七）：Fishhook](https://blog.csdn.net/yiyaaixuexi/article/details/19094765)
- [iOS安全攻防（十九）：基于脚本实现动态库注入](https://blog.csdn.net/yiyaaixuexi/article/details/19642621)
- [iOS安全攻防（二十）：越狱检测的攻与防](https://blog.csdn.net/yiyaaixuexi/article/details/20286929)
- [iOS安全攻防（二十二）：static和被裁的符号表](https://blog.csdn.net/yiyaaixuexi/article/details/21469769)
- [iOS安全攻防（二十三）：Objective-C代码混淆](https://blog.csdn.net/yiyaaixuexi/article/details/29201699)
- [iOS安全攻防（二十四）：敏感逻辑的保护方案（1）](https://blog.csdn.net/yiyaaixuexi/article/details/29210413)

### 数据安全和算法

- [DYFCryptoUtils](https://github.com/dgynfi/DYFCryptoUtils) - 🔥一行代码实现 iOS Base64, 32/16位MD5, DES, AES, RSA算法，操作简单好用。(Achieves Base64, 32/16 bit MD5, DES, AES and RSA algorithms for iOS with one line of code. The operation is simple and easy to use.)

- [AESCipher-iOS](https://github.com/WelkinXie/AESCipher-iOS) - AES encryption working between Objective-C and Java. ([AESCipher-Java](https://github.com/WelkinXie/AESCipher-Java))

- [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.

- [RSADemo](https://github.com/DullDevil/RSADemo) - RSA加解密相关方方法，以及密钥格式的生成与转换。

- [Encryptions](https://github.com/iamlay/Encryptions) - this project is for many kinds odf encryption. 

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - CryptoSwift是在Swift中实现的越来越多的标准和安全密码算法的集合。 

- [Security-iOS](https://github.com/cocoajin/Security-iOS) - 封装了一些iOS上使用的NSData分类，主要用于 RSA加密、AES加密、数据签名、签名校验、MD5、SHA1、SHA256 常用hash等工具。

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - Encrypt/Decrypt: AES. Hash: MD5, SHA(SHA1, SHA224, SHA256, SHA384, SHA512). Encode/Decode: Base64, Hex.

- [BBRSACryptor](https://github.com/NianJi/BBRSACryptor) - 使用OpenSSL进行公钥和私钥的加解密。

- [BBRSACryptor-XHAdd](https://github.com/CoderZhuXH/BBRSACryptor-XHAdd) - 1行代码调用RSA公钥、私钥生成、客户端RSA加密、解密、RSA签名、签名验证等。

- [3desDemo](https://github.com/Thomaszhouwu/3desDemo) - 3des Demo.

- [Base64](https://github.com/ekscrypto/Base64) - Objective-C Base64 Additions for NSData and NSString.

- [CryptoCompatibility](https://developer.apple.com/library/mac/samplecode/CryptoCompatibility/Introduction/Intro.html) - CryptoCompatibility shows how to do common cryptographic operations using Apple APIs such that the results match other common cryptographic APIs, most notably OpenSSL.

### 蓝牙

- [EasyBluetooth]( https://github.com/chenliangloveyou/EasyBluetooth) - 一款iOS BLE蓝牙调试工具，非常简单容易，也可以作为一个蓝牙库，快速集成和开发。 可以两步搞定蓝牙开发操作。第一步连接设备，第二步特征读写数据。

- [WHBLEDemo](https://github.com/remember17/WHBLEDemo) - 📱CoreBluetooth central and peripheral demo with OC/Swift (iOS蓝牙中心设备和外设开发,包含OC/Swift版本) 。

- [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 简单易用的蓝牙库，基于CoreBluetooth的封装，并兼容ios和mac osx。

- [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE.

- [MultipeerConnectivity](https://github.com/xiangzuhua0209/MultipeerConnectivity) - 蓝牙MultipeerConnectivity。

- [WEBlueToothManager](https://github.com/yuhanle/WEBlueToothManager) - 🐱一个蓝牙4.0的智能硬件架构。([blog](https://latehorse.github.io))

- [MPBluetoothKit](https://github.com/MacPu/MPBluetoothKit) - This is a block-based framework for building Bluetooth iOS apps using the CoreBluetooth Framework.Its a very powerful and useful,and very easy to use it.

### 手势指纹面容ID密码解锁

- [DYFAuthIDAndGestureLock](https://github.com/dgynfi/DYFAuthIDAndGestureLock) - 手势密码解锁 和 TouchID（指纹）/ FaceID（面容）解锁，代码简洁，高效。(Gesture passcode unlocking and TouchID (fingerprint) / FaceID (facial features) unlocking, concise code and efficient.)

- [XGTouchDemo](https://github.com/XGPASS/XGTouchDemo) - 手势密码解锁和指纹TouchID解锁的demo。
    
- [TouchIDAndGestureLock](https://github.com/bugaoshuni/TouchIDAndGestureLock) - 指纹解锁、手势解锁。

- [YLSwipeLockView](https://github.com/XiaoYulong/YLSwipeLockView) - A swipe password view to unlock an application written in objective-c.

- [YZAuthID](https://github.com/micyo202/YZAuthID)  - TouchID（指纹）/ FaceID（面容）验证类库，代码简洁，高效。

- [BiometricAuthentication](https://github.com/rushisangani/BiometricAuthentication) - Use Apple FaceID or TouchID authentication in your app using BiometricAuthentication.

### 布局

- [WSCollectionViewFlowLayout](https://github.com/ONECATYU/WSCollectionViewFlowLayout) - 可替代UICollectionViewFlowLayout的标签流布局，支持固定有规则的布局形式。实现了UICollectionViewDelegateFlowLayout协议方法。使用形式和系统Flowlayout相同。

### 图像渲染和绘制

#### OpenGLES

- [Apple OpenGLES Programming Guide](https://developer.apple.com/library/archive/documentation/3DDrawing/Conceptual/OpenGLES_ProgrammingGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008793-CH1-SW1)

- [kesalin - OpenGLES](https://github.com/kesalin/OpenGLES)

- [uwuneng - OpenGLES](https://github.com/uwuneng/OpenGLES)

- [XanderXu - OpenGLESExamples](https://github.com/XanderXu/OpenGLESExamples)

- [goosers - OpenGL](https://github.com/goosers/cube/wiki/OpenGL)

#### Metal

- [Apple Metal](https://developer.apple.com/metal/) 

- [Apple Metal Sample-code](https://developer.apple.com/metal/sample-code/) 

#### GPUImage

- [GPUImage](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing. [http://www.sunsetlakesoftware.com/2012/02/12/introducing-gpuimage-framework](http://www.sunsetlakesoftware.com/2012/02/12/introducing-gpuimage-framework)

- [GPUImage2](https://github.com/BradLarson/GPUImage2) - A BSD-licensed Swift framework for GPU-accelerated video and image processing.

- [GPUImage3](https://github.com/BradLarson/GPUImage3) - A BSD-licensed Swift framework for GPU-accelerated video and image processing using Metal.

#### CoreGraphics

- [Graphs](https://github.com/candy7/Graphs) - 通过bezierPath，画出曲线图，并且加入动画。

- [LXBezierPath](https://github.com/LXManMan/LXBezierPath) - 进度条绘制。

### 图像模糊化

- [BlurViewExample](https://github.com/Vanbein/BlurViewExample) - iOS实现模糊效果的几种方法和示例。

- [SVBlurView](https://github.com/TransitApp/SVBlurView) - A simple reimplementation of FXBlurView for iOS 7.

- [iOS-blur](https://github.com/JagCesar/iOS-blur) - Blur a UIView.

### 图片浏览器

- [SDPhotoBrowser](https://github.com/gsdios/SDPhotoBrowser) - A image browser which is easy for using. 非常简单易用的图片浏览器，模仿微博图片浏览器动感效果，综合了图片展示和存储等多项功能。

- [YHPhotoBrowser](https://github.com/hackxhj/YHPhotoBrowser) - 轻量级网络图片浏览器 优化性能 Gif播放性能 类新浪微博打开关闭动画 类微信图片浏览下拉图片消失。

- [HZPhotoBrowser](https://github.com/chennyhuang/HZPhotoBrowser) - 图片浏览器，photoBrowser ，新浪微博，picture, pictureBrowser, sina, weibo.

- [KSPhotoBrowser](https://github.com/skx926/KSPhotoBrowser) - A beautiful photo browser with interactive dismissal animation. 一个小而美的图片浏览器。 

### 扫码器

*二维码，条形码相关内容*

- [DYFCodeScanner](https://github.com/dgynfi/DYFCodeScanner) - 一个二维码/条形码的扫码器，代码简洁，高效。(A QR code and Barcode scanner for iOS. concise code and efficient.)

- [MMScan](https://github.com/MinMao-Hub/MMScan) - 一个简单的二维码以及条码扫描工具，使用Objective-C语言开发，有一套自定义的扫描动画以及界面，还包括生成二维码以及条码。

- [QRCode](https://github.com/kingcong/QRCode-master) - 仿微信二维码扫描。

- [LBXScan](https://github.com/MxABC/LBXScan) - A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing、ZBar、iOS系统AVFoundation扫码封装，扫码界面效果封装)。
  
- [swiftScan](https://github.com/MxABC/swiftScan) - A barcode and qr code scanner( 二维码 各种码识别，生成，界面效果)。

- [SGQRCode](https://github.com/kingsic/SGQRCode) - The easy to use QRCode scan library for iOS【iOS 原生二维码生成与扫描 -> 高仿微信】。

- [EFQRCode](https://github.com/EFPrefix/EFQRCode) - A better way to operate QR Code in Swift, support iOS, macOS, watchOS and tvOS. 

- [JB_ZBarSDK_Demo](https://github.com/jaybinhe/JB_ZBarSDK_Demo) - 通过[ZBar SDK](https://github.com/bmorton/ZBarSDK)，实现IOS扫描、生成二维码的功能。

### 下拉刷新和上拉加载

- [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - An easy way to use pull-to-refresh.

- [SDRefreshView](https://github.com/gsdios/SDRefreshView) - 简单易用的上拉和下拉刷新（多版本细节适配）。Pull To Refresh.

### 指示器

- [EasyShowView](https://github.com/chenliangloveyou/EasyShowView) - 一款超级简单的展示工具，包括吐司指示器，loding加载框，空白页提示，alertview，actionsheet的定制。可任意定制自己想要的各种样式，自定义动画，显示样式等各种操作，使各种展示更加easy。

- [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - MBProgressHUD + Customizations. [http://www.bukovinski.com/](http://www.bukovinski.com/)

- [MBProgressHUD-JDragon](https://github.com/lyc59621/MBProgressHUD-JDragon) - MBProgressHUD 封装。

- [JGProgressHUD](https://github.com/JonasGessner/JGProgressHUD) - An elegant and simple progress HUD for iOS and tvOS, compatible with Swift and ObjC.

- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS and tvOS app. 

- [MMMaterialDesignSpinner](https://github.com/misterwell/MMMaterialDesignSpinner) - An iOS activity spinner modeled after Google's Material Design Spinner.

- [SCSkypeActivityIndicatorView](https://github.com/stefanceriu/SCSkypeActivityIndicatorView) - Activity indicator view similar to the one seen in the Skype apps.


- [MDFlickrActivityIndicatorView](https://github.com/kirsis/MDFlickrActivityIndicatorView) - Flickr-like activity indicator view for iOS.

### Toast

- [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 向UIView对象类添加Toast通知的Swift扩展。([Objective-C版](https://github.com/scalessec/Toast))

- [XHToast](https://github.com/CoderZhuXH/XHToast) - 简洁轻便提示工具,一行代码既可完成提示信息显示 - 支持自定义显示位置及停留时间。

- [iToast-iOS](https://github.com/Tim9Liu9/iToast-iOS) - iToast的ARC版本。

- [toast-notifications-ios](https://github.com/ecstasy2/toast-notifications-ios) - We at Guru software really love toast notifications available on android OS, so we've built a similar feature for the IOS enabled devices.

- [JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications) - An iOS UIView for presenting a minimalistic notification that doesn't block the UI and is highly configurable.

### Menu和弹出视图

- [kxmenu](https://github.com/kolyvan/kxmenu) - KxMenu is a vertical popup menu for using in iOS applications.

- [LCSlideMenu](https://github.com/ChinaHackers/LCSlideMenu) - A powerful and easy to use slider menu. 

- [JMColumnMenu](https://github.com/JunAILiang/JMColumnMenu) - 仿腾讯新闻、今日头条栏目管理。

- [WJPageManager](https://github.com/WJCha/WJPageManager) - WJPageManager提供了可以快速完成项目中常见的标题栏以及对应的分页控制器创建与逻辑处理。

- [YNPageScrollViewController](https://github.com/yongyuandouneng/YNPageScrollViewController) - 一个强大的PageScrollViewController滑动库。菜单多种样式选择，支持悬浮样式、导航条样式、顶部样式。

- [YNPageViewController](https://github.com/yongyuandouneng/YNPageViewController) - 特斯拉组件、QQ联系人布局、多页面嵌套滚动、悬停效果、美团、淘宝、京东、微博、腾讯新闻、网易新闻、今日头条等标题滚动视图。 (YNPageScrollViewController重构版)

- [LTScrollView](https://github.com/gltwy/LTScrollView) - ScrollView嵌套ScrolloView（UITableView 、UICollectionView）解决方案， 支持OC / Swift.

- [MLMenu](https://github.com/MrDML/MLMenu) - 仿微信QQ右上角菜单功能。

- [JMDropMenu](https://github.com/JunAILiang/JMDropMenu) - 仿QQ、微信下拉菜单封装，支持自定义样式。

- [XYMenu](https://github.com/HeathHsia/XYMenu) -  简易集成的弹出菜单。

- [YCMenuView](https://github.com/WellsYC/YCMenuView) - a popup menu which can be highly customized. (一个可以根据关联点和关联视图弹出的菜单，类似QQ导航栏右侧菜单。可满足高度自定义需求。) 

- [REMenu](https://github.com/romaonthego/REMenu) - Dropdown menu inspired by Vine.

- [PopMenu](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app.

- [SHESelectTable](https://github.com/shelly8219/SHESelectTableDemo) - 下拉选择的列表。

- [MMComboBox](https://github.com/YYWDark/MMComboBox) - A comboBox contained three kinds of style.

- [CustomPopoverView](https://github.com/maltsugar/CustomPopoverView) - 一款小巧灵活的自定义弹出视图, 可以做自定义AlertView、弹出窗口等等。A tiny and sweet custom popView (pop popup).

- [MMPopupView](https://github.com/adad184/MMPopupView) - A basic Pop-Up Kit allows you to easily create Pop-Up view. You can focus on the only view you want to show.Besides, it comes with 2 common Pop-Up view, MMAlertView & MMSheetView. You can easily use & customize it. 

- [JianShuPopViewDemo](https://github.com/linsyorozuya/JianShuPopViewDemo) - 简书、淘宝弹出效果动画demo。

- [UIAlertView-Blocks](https://github.com/jivadevoe/UIAlertView-Blocks) - A category for UIAlertView which allows you to use blocks to handle the pressed button events rather than implementing a delegate.

- [BAAlertController](https://github.com/BAHome/BAAlertController) - UIAlertController 的分类，一个block 搞定系统 alert 和 actionSheet 的 iPhone 和 iPad 版本适配！

### WebView和进度条

- [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. Currently, UIWebView doesn't have official progress interface. You can implement progress bar for your in-app browser using this module.

- [BAWKWebView](https://github.com/BAHome/BAWKWebView) - 用分类封装 WKWebView，一行代码搞定 request、URL、URLString、本地 HTML文件、HTMLString等请求，一个 block 搞定 title、progress、currentURL、当前网页的高度等等。

- [YQLWebViewProgress](https://github.com/Dogndxt/YQLWebViewProgress) - 网页进度条显示，WebViewProgress.

- [WYWebViewDemo](https://github.com/wangyansnow/WYWebViewDemo) - 进度条加载网页。

- [CHWebView](https://github.com/chausson/CHWebView) - 简化UIWebView和WKWebView的API使用，在此基础上实现进度条和简单JS交互事件。

- [WKWebViewDemo](https://github.com/SSiming/WKWebViewDemo) - WKWebView实际使用中遇到的注意点，以及WKWebView和JavaScript交互。具体介绍请戳[WKWebView使用及注意点(keng)](http://www.jianshu.com/p/9513d101e582)。

- [XDProgressView](https://github.com/Tbwas/XDProgressView) - XDProgressView可以由你心情任意设置高度，也可在上面显示文字。

- [SDProgressView](https://github.com/gsdios/SDProgressView) - Progress Indicator View. 简便美观的进度指示器。

### 动画

- [MGTrasitionPractice](https://github.com/LYM-mg/MGTrasitionPractice) - 自定义转场练习。

- [pop](https://github.com/facebook/pop) - An extensible iOS and OS X animation library, useful for physics-based interactions.

- [PopAnimationDemo](https://github.com/crossPQW/PopAnimationDemo) - 使用pop完成一些的动画效果。

- [CustomPopAnimation](https://github.com/zys456465111/CustomPopAnimation) - Runtime实现自定义Pop手势动画。

- [CATransitionDemo](https://github.com/lizelu/CATransitionDemo) - CATransition动画实现。
```
// 一些私有API, 有些效果在APPStore中是不能使用的，私有API如下：
NSString *const kCATransitionCube = @"cube";  
NSString *const kCATransitionSuckEffect = @"suckEffect"; 
NSString *const kCATransitionOglFlip = @"oglFlip";  
NSString *const kCATransitionRippleEffect = @"rippleEffect";  
NSString *const kCATransitionPageCurl = @"pageCurl"; 
NSString *const kCATransitionPageUnCurl = @"pageUnCurl";   
NSString *const kCATransitionCameraIrisHollowOpen = @"cameraIrisHollowOpen";
NSString *const kCATransitionCameraIrisHollowClose = @"cameraIrisHollowClose";

// 而下方这些可以放心使用：
// CAAnimation.h
// Common transition types. 
CA_EXTERN NSString * const kCATransitionFade
__OSX_AVAILABLE_STARTING (__MAC_10_5, __IPHONE_2_0);
CA_EXTERN NSString * const kCATransitionMoveIn
__OSX_AVAILABLE_STARTING (__MAC_10_5, __IPHONE_2_0);
CA_EXTERN NSString * const kCATransitionPush
__OSX_AVAILABLE_STARTING (__MAC_10_5, __IPHONE_2_0);
CA_EXTERN NSString * const kCATransitionReveal
__OSX_AVAILABLE_STARTING (__MAC_10_5, __IPHONE_2_0);
```

- [iOSAnimation](https://github.com/BranPeng/iOSAnimation) - 好玩的iOS动画。

- [iOS-Swift-Animation](https://github.com/BranPeng/iOS-Swift-Animation) - iOS Swift动画框架。

### 选择器

- [BRPickerView](https://github.com/91renb/BRPickerView) - 封装的是iOS中常用的选择器组件。高度封装，只需一句代码即可完成调用，使用比较灵活支持自定义主题颜色。选择器类型主要包括：日期选择器、时间选择器、地址选择器、自定义字符串选择器。

### 搜索

- [PYSearch](https://github.com/ko1o/PYSearch) - 🔍 An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad) .

### 分享

-- [ShareSDK-for-iOS](https://github.com/MobClub/ShareSDK-for-iOS) - ShareSDK是一个完全免费的社会化分享组件，为移动端的iOS App提供社会化功能。([MobTech](http://www.mob.com))

- [U-Share SDK](https://www.umeng.com/social) - 帮助应用或游戏快速具备国内外多平台分享、第三方登录功能，SDK包小，集成成本低，平台覆盖全，并基于友盟+大数据，提供权威、实时的用户画像、分享回流等数据分析，助力产品开发与推广。([友盟](https://www.umeng.com))

- [TTOpenInAppActivity](https://github.com/honkmaster/TTOpenInAppActivity) - TTOpenInAppActivity is a UIActivity subclass that provides an "Open In ..." action to a UIActivityViewController. TTOpenInAppActivity uses an UIDocumentInteractionController to present all Apps that can handle the document specified with by the activity items.

### 图片验证码

- [ZLSecurityCode](https://github.com/ZLFighting/ZLSecurityCode) - iOS-字符图片验证码。

- [MQVerCodeView](https://github.com/meiqi1992/MQVerCodeView) - 类似图片验证码，点击可刷新。

- [YanZhengCode](https://github.com/wsl2ls/YanZhengCode) - 图片验证码和滑块验证码。

### 获取设备相关信息

- [iOS-getClientInfo](https://github.com/PengfeiWang666/iOS-getClientInfo) - 📲iOS中获取各种设备信息。

- [ZGInfoCollection](https://github.com/ScottZg/ZGInfoCollection) - 获取iPhone相关信息以及网络状态等等。

### 广告

- [ZLAdvertDemo](https://github.com/ZLFighting/ZLAdvertDemo) - 启动页加载广告。

- [SplashScreenADView](https://github.com/wxzwork/SplashScreenADView) - 启动图和开屏广告页，类似网易。可根据广告的有效时间显示或关闭广告页，以及定制广告页停留的时间。

- [LaunchAd](https://github.com/ScottZg/LaunchAd) - 启动页广告。

- [ADScrollView](https://github.com/Thomaszhouwu/ADScrollView) - 下载一张网页图片，无线滑动图片展示各种广告图片，点击某个广告图片做出相应的操作。

### 高仿项目和项目Demo

- [iOSProject](https://github.com/NJHu/iOSProject) - iOS project of collected some demos for iOS App. ([Swift版](https://github.com/NJHu/iOSProject))

- [ZFZhiHuDaily](https://github.com/renzifeng/ZFZhiHuDaily) - 知乎日报swift版(精仿)。

- [YiYuanYunGou](https://github.com/JxbSir/YiYuanYunGou) - 高仿一元云购IOS应用（高仿自一元云购安卓客户端）。

- [BingFenShiJia](https://github.com/hurryupcheng/BingFenShiJia) -  缤微纷购。

- [ifanr](https://github.com/iCodeForever/ifanr) - 高仿 爱范儿。

- [meituan](https://github.com/lookingstars/meituan) - 高仿美团iOS版，版本号5.7。截图链接：[http://blog.csdn.net/l863784757/article/details/46912223](http://blog.csdn.net/l863784757/article/details/46912223)

- [nuomi](https://github.com/lookingstars/nuomi) - 高仿百度糯米iOS版，版本号5.13.0。

- [U17](https://github.com/spicyShrimp/U17) - 精仿有妖气漫画(Swift5)。

- [MobileProject](https://github.com/wujunyang/MobileProject) - 是一个以MVC模式搭建的开源功能集合，基于Objective-C上面进行编写，意在解决新项目对于常见功能模块的重复开发，MobileProject对于项目的搭建也进行很明确的划分，各个模块职责也比较明确，MobileProject也引入的一些常用第三方插件、宏定义、工具帮助类等；整个项目也是在不断更新跟维护中，功能点也会不断更新；代码支持iOS7以后版本。

- [WSLAPP](https://github.com/wsl2ls/WSLAPP) - 音乐播放器，新闻，壁纸，画板，二维码，计分器，一个我自己做的完整的项目源码。

- [iOS_Demo](https://github.com/darren90/iOS_Demo) - iOS开发中一些实用的Demo。

- [iOS-Project](https://github.com/BranPeng/iOS-Project) - 收集的一些比较好的iOS打样工程。

- [ZJKitTool](https://github.com/Dzhijian/ZJKitTool) - 快速添加UIKit控件可以结合Masonry，以及其他工具类的简单使用，评论列表、瀑布流、压缩图片、倒计时、筛选、自定义PickerView 时间日期选择器、性别选择器、WKWebView 的应用。

- [coolnameismy - blog](https://github.com/coolnameismy/demo) - coolnameismy的技术博客文章对应的demo。

- [LiuAGeIOS](https://github.com/6ag/LiuAGeIOS) - 六阿哥网iOS版，资讯类客户端。 

- [MGSinaWeibo](https://github.com/LYM-mg/MGSinaWeibo) - 高仿新浪微博访客视图，首页，发布界面等 使用技术：MVVM设计模式，使用纯代码和Xib混合开发，使用SnapKit做UI布局，AFN网络数据请求，MJExtension进行字典转模型数据，使用SDWebImage进行图片加载，二维码的扫描和生成，图文混排，不等高cell的计算，表情键盘，图片上传和图片浏览器等技术。

- [MGBaisi](https://github.com/LYM-mg/MGBaisi) - 高度仿写百思不得姐项目，实现精华，新帖，发布，关注，我的五大功能模块，运用了很多技术。 使用技术：MVC设计模式，使用纯代码和Xib混合开发，使用Masonry和AutoLayout做UI布局，首页精华模块充分使用父子控制器，音频视频的播放，集成系统自带新浪分享，评论详情界面，发布集成pop动画，关注界面充分利用Xib的优势，使用SDWebImage进行图片加载，MBProessHUD进行遮盖提示，清除缓存功能，UIWebView进行网页加载等技术。

- [MGDemo](https://github.com/LYM-mg/MGDemo) - 涉及导航栏随着tableView滑动是否隐藏，随着tableView的滑动让TabBar隐藏，停止滑动显示TabBar。还有NavigationController的titleView动态缩放效果，还加了UITableView分区展开与收起。后来又加了录制视频的功能和在相册中选择视频的功能。tableView的一些常用知识点，还有搜索框的使用。后来又整合了UICollectionView的使用,ShareSDK分享等。

- [MGLoveFreshBeen](https://github.com/LYM-mg/MGLoveFreshBeen) - 一款电商App，实现首页功能以及个人中心和分类，购物车模块。1.MVC设计模式 2.使用纯代码和Xib混合开发，使用Masonry和AutoLayout做UI布局；3.集成友盟分享 4.使用SDWebImage进行图片加载 5.SVProessHUD和MBProessHUD进行遮盖提示 6.UITableView的联动效果 7.首页UICollectionView进行数据显示 8.UIWebView加载网页等技术。

- [DBFMDemo](https://github.com/LYM-mg/DBFMDemo) - 豆瓣电台，一个豆瓣电台demo，可以选择播放顺序，可以通过选择频道获取歌曲数据，进行歌曲播放。

### Others

#### Sensor

- [SensorDemo](https://github.com/wsl2ls/SensorDemo) - 指纹识别、运动传感器、加速计、环境光感、距离传感器、指南针、陀螺仪等传感器示例集锦。

#### Privacy

- [BAPrivacyManager](https://github.com/boai/BAPrivacyManager) - iOS 所有隐私权限封装，定位、蓝牙、通知、运动、日历、相册、相机等 14 种权限封装！

#### 未归类

- [MSWeakTimer](https://github.com/mindsnacks/MSWeakTimer) - Thread-safe NSTimer alternative that doesn't retain the target and supports being used with GCD queues.

- [NNMacros](https://github.com/amisare/NNMacros) - NNMacros通过宏的方式来简化iOS开发中OC的语法和Api的操作。

- [Ono](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & macOS.

- [NSString-URLEncode](https://github.com/kevinrenskers/NSString-URLEncode) - Category that adds URLEncode and URLDecode to NSString.

- [EasyIOS](https://github.com/zhuchaowe/EasyIOS) - A new generation of development framework based on Model-View-ViewModel.
    - [EasyRSS](https://github.com/zhuchaowe/EasyRSS) - A rss reader for ios based on easyios.

- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - 一个可以很容易地为iOS创建漂亮的、高度可定制的动画复选框。

- [YXCollectionView](https://github.com/yixiangboy/YXCollectionView) - UICollection学习总结以及案例集合。

- [NJKScrollFullScreen](https://github.com/ninjinkun/NJKScrollFullScreen) - Scroll to full screen like Facebook app.

- [ScrollShowHeaderDemo](https://github.com/Cloudox/ScrollShowHeaderDemo) - 上下滑动列表时展现和隐藏顶部视图的demo。

- [HYBSnapkitAutoCellHeight](https://github.com/CoderJackyHuang/HYBSnapkitAutoCellHeight) - 基于[SnapKit](#Masonry与SnapKit)写的自动计算cell的高度的扩展。

- [timeLineiOS](https://github.com/romaHerman/timeLineiOS) - DropIn TimeLine with progress animatiom.

- [MGCollectionView](https://github.com/LYM-mg/MGCollectionView) - 环形图片排布以及花瓣形排布。

- [SCIndexView](https://github.com/TalkingJourney/SCIndexView) - SCIndexView provide a index view like Wechat.

- [HotOrConcernCityListChoose](https://github.com/ScottZg/HotOrConcernCityListChoose) - 添加热门城市和关注城市。

- [RTLabel](https://github.com/honcheng/RTLabel) - Rich text formatting based on HTML-like markups for iOS.

- [UICountingLabel](https://github.com/dataxpress/UICountingLabel) - Adds animated counting support to UILabel. 

- [TKPhoneformat](https://github.com/kangtian/TKPhoneformat) - 一款输入手机号码格式的控件。

- [CopyLabel](https://github.com/TUTUDeveloper/CopyLabel) - iOS拥有复制功能的Label。

- [LYThemeChange](https://github.com/lanyasheng/LYThemeChange) - 主题更换。

- [iOS-Swift-UI](https://github.com/BranPeng/iOS-Swift-UI) - iOS-Swift-UI.

- [jiaModuleDemo](https://github.com/wujunyang/jiaModuleDemo) - 一个针对iOS模块化开发的解决方案。

- [DraggingSort](https://github.com/HelloYeah/DraggingSort) - 长按拖拽排序。

- [RSSliderView](https://github.com/rsimenok/RSSliderView) - Custom slider based on UIView for iOS.

- [JMMarkSlider](https://github.com/joamafer/JMMarkSlider) - Fully customizable slider that allows you to set marks on it. You can set the color of the bar, marks and handler, the width of the marks and even an image for the handler.

- [ZZHotKeysMenu](https://github.com/zhouXiaoR/ZZHotKeysMenu) - ZZHotKeysMenu自定义布局，继承自UICollectionViewLayout。

- [corelib](https://github.com/wwwxiaowen/corelib) - iOS常用封装类库。

- [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) - iOS平台利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志。

- [TOSMBClient](https://github.com/TimOliver/TOSMBClient) -  A small library that serves as a simple SMB (Server Message Block ) client for iOS apps. The library allows connecting to SMB devices, downloading file metadata, and subsequently allows asynchronous downloading of files from an SMB device straight to an iOS device. It is an Objective-C wrapper around Defective SMb, or libDSM, a low level SMB client library built in C built by some of VideoLabs' developers. A copy of libDSM has been specially cross-compiled for iOS device architectures and embedded in this library, so this project has no external dependencies.

- [SimulateIDFA](https://github.com/youmi/SimulateIDFA) - iOS10 IDFA AD tracking limit solution.

- [model-identifiers](https://github.com/kluivers/model-identifiers) - Apple model identifiers. Gives you an approximation of the device based on the model identifier.

- [iOSTips](https://github.com/DarielChen/iOSTips) - 记录iOS开发中的一些知识点、小技巧。

- [EGOImageLoading](https://github.com/enormego/EGOImageLoading) - What if images on the iPhone were as easy as HTML? 

- [EGOCache](https://github.com/enormego/EGOCache) - Fast Caching for Objective-C (iPhone & Mac Compatible).

- [UncaughtExceptionHandler](https://github.com/minibear0523/UncaughtExceptionHandler) - 一个iOS崩溃异常的捕捉处理源代码，帮助更好的调试程序。

- [SPUncaughtExceptionHandler](https://github.com/kshipeng/SPUncaughtExceptionHandler) - APP闪退时，由用户决定是否继续。

#### 其他汇总

- [awesome-ios](https://github.com/vsouza/awesome-ios) - A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects.

- [arodung-blog](http://blog.csdn.net/arodung/article/details/50846546) - Github上最全的iOS开源项目分类汇总。

### 类目

- [JKCategories](https://github.com/shaojiankui/JKCategories) - JKCategories(iOS-Categories,Category), a collection of useful Objective-C Categories extending iOS Frameworks such as Foundation,UIKit,CoreData,QuartzCore,CoreLocation,MapKit Etc.

- [UIButtonEdgeInsets](https://github.com/CenterY/UIButtonEdgeInsets) - 通过类别和继承方式实现按钮的图片和标题布局，调整 UIButton的imageEdgeInsets 和 titleEdgeInsets属性。

- [nsstring-extensions](https://github.com/ToshMeston/nsstring-extensions) - This is a category for NSString that adds commonly used methods such as trim, urlEncode, urlDecode, parseIntWithDefaultValue.

### 越狱检测

- [iOS Jailbreak Detector](https://github.com/diwu/ios-jail-break-detector) - A drop-in class that dynamically detects whether the iOS device your app is running on has been jailbroken or not. 100% App Store Submission Safe. No Private API.

## Mac

- [dSYMTools](https://github.com/answer-huang/dSYMTools) - dSYM analyze. 

- [IPAPkgTool](https://github.com/dgynfi/IPAPkgTool) - 一款自动化打包ipa的MacOS应用。(A MacOS application that packs ipa automatically.)

- [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) - This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device. ([Instructions](https://dantheman827.github.io/ios-app-signer/))

- [iReSign](https://github.com/maciekish/iReSign) - ReSign allows iDevice app bundles (.ipa) files to be signed or resigned with a digital certificate from Apple for disibution. This tool is aimed at enterprises users, for enterprise deployment, when the person signing the app is different than the person(s) developing it.

- [EasyResigny](https://github.com/niyaoyao/EasyResigny) - A Mac tool for user to resign iOS App.

- [Resign](https://github.com/LigeiaRowena/) - OSX utility to resign the IPA files.

- [FinderGo](https://github.com/onmyway133/FinderGo) - 🐢 Open terminal quickly from Finder. ([blog](https://onmyway133.github.io/))

- [iOS-Images-Extractor](https://github.com/devcxm/iOS-Images-Extractor) - A Mac app to decode and extract images from iOS apps, support png/jpg/ipa/Assets.car files.

- [cartool](https://github.com/steventroughtonsmith/cartool) - Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

- [Pusic](https://github.com/peterHchina/Pusic) - An audio player for mac.

- [My12306Cocoa](https://github.com/fanjunwei/My12306Cocoa) - 12036自动订票max ox版。

- [12306Client](https://github.com/w11h22j33/12306Client) - 12306Client.

- [AYProgressBar](https://github.com/buddax2/AYProgressBar) - Customized NSProgressIndicator. Basically its just two-colored line with active color and passive color.

- [GRProgressIndicator](https://github.com/insidegui/GRProgressIndicator) - reimplementation of NSProgressIndicator with some customization support.

- [VVDocumenter](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write documentation comment easier, for both Objective-C and Swift.

- [ESJsonFormat-Xcode](https://github.com/EnjoySR/ESJsonFormat-Xcode) - 将JSON格式化输出为模型的属性。

- [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.

- [XAlign](https://github.com/qfish/XAlign) - An amazing Xcode Source Editor extension to align regular code. It can align Xnything in any way you want.

- [FirTools](https://github.com/sdaduanbilei/FirTools) - 一个 swift 写的 OS X 的Menu Bar 程序。

## 区块链

*比特币、以太坊、区块链相关内容*

- [go-ethereum](https://github.com/ethereum/go-ethereum)  - 以太坊协议的官方的Go语言实现。
  - [Download Geth](https://geth.ethereum.org/downloads/) - Binary archives are published.

- [web3swift](https://github.com/BANKEX/web3swift) - Elegant Web3js functionality in Swift. Native ABI parsing and smart contract interactions on Ethereum network ([web3.swift-Example](https://github.com/MercuryProtocol/web3.swift-Example) - Example on how to use web3.swift). 

- [web3j](https://github.com/web3j/web3j) - web3j is a lightweight, highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network. 

- [py-geth](https://github.com/ethereum/py-geth) - Python wrapping for running Go-Ethereum as a subprocess.

- [EthersWallet-ios](https://github.com/ethers-io/EthersWallet-ios) - Ethereum Wallet and Dapp Browser for iOS.

- [breadwallet-ios](https://github.com/voisine/breadwallet-ios) - Bread is the best way to get started with bitcoin. 

- [dashwallet](https://github.com/QuantumExplorer/dashwallet) - Dashwallet (breadwallet fork) is a real standalone Dash client. 

- [imToken](https://github.com/ywzqhl/imToken) - ETHWallet.

- [ethers.io](https://github.com/ethers-io/ethers.io) - The frontend website HTML, JavaScript and CSS for ethers.io. 

- [ethers.objc](https://github.com/ethers-io/ethers.objc) - Fast, simple and complete library for Ethereum in Objective-C.


## Flutter

### Flutter和Dart

- [Flutter中文网](https://flutterchina.club) 
- [Flutter SDK Archive](https://flutter.io/sdk-archive/#macos) 
- [Dart Packages](https://pub.flutter-io.cn)
- [Dart2 中文文档](https://www.kancloud.cn/marswill/dark2_document/709087) 

### Flutter Project

- [dart_crypto](https://github.com/dgynfi/dart_crypto) - 🔥集成Base64, MD5, AES, RSA等算法。

- [grab_ethtoken_info](https://github.com/dgynfi/grab_ethtoken_info) - 🔥爬取etherscan的一个钱包地址的所有token信息( address, name, balance, symbol, value)，并编写界面进行展示。

- [flutter_study](https://github.com/dgynfi/flutter_study) - Flutter基础，Dart基础，实践教学。


## Weex

- [Weex](https://github.com/apache/incubator-weex) - A framework for building Mobile cross-platform UI. 

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


## H5

- [HTML5中文教程-极客学院Wiki](http://wiki.jikexueyuan.com/project/html5/)

- [W3school - HTML5](http://www.w3school.com.cn/html5/index.asp)

- [HTML5 教程 | 菜鸟教程](http://www.runoob.com/html/html5-intro.html)

- [canvas](https://github.com/airingursb/canvas) - 《Canvas：Draw on the Web》，[本书GitBook]( https://airingursb.gitbooks.io/canvas/)

- [JavaScript教程](http://www.w3school.com.cn/b.asp)

- [JavaScript 参考手册](http://www.w3school.com.cn/jsref/index.asp)


## 游戏

### Cocos2d

- [Cocos2d-x](https://github.com/cocos2d/cocos2d-x) - Cocos2d-x is a suite of open-source, cross-platform, game-development tools used by millions of developers all over the world. http://www.cocos2d-x.org.


### 棋牌

- [qipai_algorithm](https://github.com/yuanfengyun/qipai_algorithm) - 棋牌的胡牌算法，包括麻将、跑胡子、扑克。实现 lua c++ c# golang js  java  python版本。

- [HuPaiMJ](https://github.com/pinorr/HuPaiMJ) - C++麻将胡牌算法。优点：1.速度快，900万次多赖子胡牌用时500ms左右；2.支持多个赖子；3.查错方便，直接查表就可知道。

### 游戏示例

- [Hardest](https://github.com/ZhongTaoTian/Hardest) - 史上最困难的游戏-By Objective-C。


## C-plus-plus

- [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.


## Script

### Full

- [Script](https://github.com/dgynfi/Script) - 编写了iOS自动化打包脚本，编写和收集Shell, Python, Ruby等其它的实用脚本。(Writes automated packaging scripts for iOS, writes and collects some useful scripts about Shell, Python, Ruby, etc.)

### Shell

- [dgynfi - Shell](https://github.com/dgynfi/Script/tree/master/Shell) - Some shell tools for iOS or Mac.

- [FFmpeg-iOS-build-script](https://github.com/wuqiong/FFmpeg-iOS-build-script) - Shell script to build FFmpeg for iOS.

### Python

- [SpoofMAC](https://github.com/feross/SpoofMAC) - 💼 Change your MAC address for debugging. [http://feross.org/spoofmac/](http://feross.org/spoofmac/)

- [xlrd](https://github.com/python-excel/xlrd) - Library for developers to extract data from Microsoft Excel (tm) spreadsheet files. [python-excel](http://www.python-excel.org)

- [xlwt](https://github.com/python-excel/xlwt) - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform. [python-excel](http://www.python-excel.org)

- [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - [A Python module for creating Excel XLSX files. ](https://xlsxwriter.readthedocs.io)

- [jdcal](https://github.com/phn/jdcal) - Julian dates, stored as two numbers, from proleptic Gregorian and Julian calendars.

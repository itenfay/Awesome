[如果你觉得能帮助到你，请给一颗小星星。谢谢！(If you think it can help you, please give it a star. Thanks!)](https://github.com/dgynfi/OpenSource)

## OpenSource

🔥🔥🔥

汇总好用的开源项目，涵盖了iOS，Mac，区块链，Flutter，Weex，H5，Cocos2d，C++，棋牌，Script等各个方面的内容，其中，iOS包涵以下几个方面：
1. 常用第三方库：YYKit, AFNetworking & Alamofire, SDWebImage, ReactiveCocoa & RxSwift, Masonry & SnapKit；
2. 导航栏和状态栏；
3. 侧边菜单(Side Menu)；
4. 支付: 内购(IAP)和第三方支付；
5. 播放器: 视频播放器，音乐播放器；
6. IM和直播；
7. 数据持久(Data Persistence)；
8. 逆向开发；
9. 数据安全相关；
10. 蓝牙, 扫码器, 下拉刷新和上拉加载, 指示器, Toast, Menu, 图片浏览器, 进度条, 动画, 搜索, 分享, 图片验证码, 获取设备相关信息, 广告, Sensor, Privacy, 高仿项目和项目Demo。

🔥🔥🔥


## 目录

- [iOS](#iOS)
   - [常用第三方库](#常用第三方库)
     - [YYKit](#YYKit)
     - [AFNetworking和Alamofire](#AFNetworking和Alamofire)
     - [SDWebImage](#SDWebImage)
     - [ReactiveCocoa和RxSwift](#ReactiveCocoa和RxSwift)
     - [Masonry和SnapKit](#Masonry和SnapKit)
   - [网络相关](#网络相关)
   - [导航栏和状态栏](#导航栏和状态栏)
   - [Side Menu](#Side-Menu)
   - [支付](#支付)
     - [内购IAP](#内购IAP)
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
   - [数据安全相关](#数据安全相关)
   - [蓝牙](#蓝牙)
   - [扫码器](#扫码器)
   - [下拉刷新和上拉加载](#下拉刷新和上拉加载)
   - [指示器](#指示器)
   - [Toast](#Toast)
   - [Menu](#Menu)
   - [图片浏览器](#图片浏览器)
   - [进度条](#进度条)
   - [动画](#动画)
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
     - [分享其他分类汇总](#分享其他分类汇总)
- [Mac](#Mac)
- [区块链](#区块链)
- [Flutter](#Flutter)
    - [Flutter和Dart](#Flutter和Dart)
    - [Flutter Project](#Flutter-Project)
- [Weex](#Weex)
- [H5](#H5)
- [Cocos2d](#Cocos2d)
- [C++](#c++)
- [棋牌](#棋牌)
- [Script](#Script)


## iOS

### 常用第三方库

*🔥🔥🔥👍👍👍*

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

#### AFNetworking和Alamofire

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - A delightful networking framework for iOS, macOS, watchOS, and tvOS. 
    <div align=center>
    <img src="https://camo.githubusercontent.com/1560be050811ab73457e90aee62cd1cd257c7fb9/68747470733a2f2f7261772e6769746875622e636f6d2f41464e6574776f726b696e672f41464e6574776f726b696e672f6173736574732f61666e6574776f726b696e672d6c6f676f2e706e67" width="50%" />
    </div>

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
    <div align=center>
    <img src="https://raw.githubusercontent.com/Alamofire/Alamofire/master/alamofire.png"  width="50%" />
    </div>

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

#### ReactiveCocoa和RxSwift

*响应式编程*

- [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa) - Reactive extensions to Cocoa frameworks, built on top of [ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)), It Offers composable, declarative and flexible primitives that are built around the grand concept of streams of values over time. These primitives can be used to uniformly represent common Cocoa and generic programming patterns that are fundamentally an act of observation. 
    <div align=center>
    <img src="https://github.com/ReactiveCocoa/ReactiveCocoa/raw/master/Logo/PNG/logo.png" width="50%" />
    </div>

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

### 网络相关

- [BANetManager](https://github.com/boai/BANetManager) - 基于AFNetworking 3.0、3.1最新版本的封装，集成了 get / post / put / delete 方法请求数据，单图/多图上传，视频上传/下载，网络监测 等多种网络请求方式。

- [HYBNetworking](https://github.com/CoderJackyHuang/HYBNetworking) - 基于AFNetworking3.0以上版本封装的网络层。提供常用的GET/POST接口、上传下载图片、文件接口、支持缓存等。

- [HLNetworking](https://github.com/wangshiyu13/HLNetworking) - 基于AFNetworking的高阶网络请求管理器。
    <div align=center>
    <img src="https://raw.githubusercontent.com/QianKun-HanLin/HLNetworking/master/loge.png" width="50%" />
    </div>

- [CCPAFNNetworking](https://github.com/iccpeng/CCPAFNNetworking) -  AFN与MBProgressHUD的组合使用。

- [Reachability](https://github.com/tonymillion/Reachability) - ARC and GCD Compatible Reachability Class for iOS and MacOS. Drop in replacement for Apple Reachability.

- [CocoaWebResource](https://github.com/robin/cocoa-web-resource) - A file transfer solution for iPhone and iPod Touch. Support uploading, download and delete files via browser.

- [GCDWebServer](https://github.com/swisspol/GCDWebServer) - A modern and lightweight GCD based HTTP 1.1 server designed to be embedded in iOS, macOS & tvOS apps. 

- [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for Mac OS X or iOS applications.

### 导航栏和状态栏

- [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) - 超简单！！！ 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等。([Swift版](https://github.com/wangrui460/WRNavigationBar_swift))
    <div align=center>
    <img src="https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/拉钩App首页.gif" width=200 /> <img src="https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/新浪微博个人中心.gif" width=200 /> <img src="https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/蚂蚁森林.gif" width=200 />
    </div>
  
- [NNNavigationBar](https://github.com/amisare/NNNavigationBar) - 实现导航条背景渐变过渡动画的轻量级框架。
    <div align=center>
    <img src="https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_00.gif" width=260 /> <img src="https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_01.gif" width=260 />
    </div>

- [RTRootNavigationController](https://github.com/rickytan/RTRootNavigationController) - Implicitly make every view controller has its own navigation bar. 
    <div align=center>
    <img src="https://user-images.githubusercontent.com/1250207/30429339-abb20914-9989-11e7-9058-c967839315f4.gif" width=260 />
    </div>

- [GKNavigationController](https://github.com/QuintGao/GKNavigationController) - iOS自定义导航栏-导航条联动（仿网易新闻、网易云音乐等导航栏滑动效果）。
    <div align=center>
    <img src="https://github.com/QuintGao/GKNavigationController/raw/master/GKNavigationControllerDemo/001.png" width=260 />
    </div>

- [EasyNavigation](https://github.com/chenliangloveyou/EasyNavigation) - 一款超级简单的导航条管理工具。完全自定义导航条。没有UINavigationBar 和 UINavigationItem 这两个类。完全是对UIView的操作。 所有操作都能一行代码，操作之间完全独立，互不影响。
    <div align=center>
    <img src="https://github.com/chenliangloveyou/EasyNavigation/raw/master/logo/horizontal-color.png" width="50%" />
    </div> 

- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. 
    <div align=center>
    <img src="https://raw.githubusercontent.com/forkingdog/FDFullscreenPopGesture/master/Snapshots/snapshot0.gif" width=260 />
    </div>

- [JZNavigationExtension](https://github.com/JazysYu/JZNavigationExtension) - JZNavigationExtension integrates some convenient features for UINavigationController and easy to use.
    <div align=center>
    <img src="https://raw.githubusercontent.com/JazysYu/JZNavigationExtension/master/Snapshots/JZNavigationExtensionDemo.gif" width=260 />
    </div>

- [BBGestureBack](https://github.com/Bonway/BBGestureBack) - OC and Swift full screen return gesture（纯OC 和 纯Swift编写，类淘宝、京东等全屏滑动返回效果）。
    <div align=center>
    <img src="https://camo.githubusercontent.com/de8758c8283c6aa4745044e2a677410880335726/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f31303939313737302d656465636265633933643164376538622e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width=260 />
    </div>

### Side Menu

- [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) - A lightweight, easy to use, Side Drawer Navigation Controller.
    <div align=center>
    <img src="https://camo.githubusercontent.com/5c4050ef64d7b9836b6a56b89b458ed5c8fdfb7f/687474703a2f2f6d757475616c6d6f62696c652e6769746875622e696f2f4d4d447261776572436f6e74726f6c6c65722f4578616d706c65496d616765732f6578616d706c65322e706e67" width="30%" />
    </div>

- [RESideMenu](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect.
    <div align=center>
    <img src="https://raw.githubusercontent.com/romaonthego/RESideMenu/master/Demo.gif?2" width=260 />
    </div>

### 支付

#### 内购IAP

- [IAPHelper](https://github.com/saturngod/IAPHelper) - IAP helper for Apple in app purchases. It uses ARC and blocks for ease of use. Ready to use with newsstand subscriptions. No more maintenance for this repo. Please use the [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)

- [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - SwiftyStoreKit is a lightweight In App Purchases framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+. 
    <div align=center>
    <img src="https://github.com/bizz84/SwiftyStoreKit/raw/master/Screenshots/Preview.jpg" width="30%" />
    </div>

#### 第三方支付

- [XHPayKit](https://github.com/CoderZhuXH/XHPayKit) - 不用官方SDK实现微信支付、支付宝支付。

### 播放器

#### 视频播放器

- [CLPlayer](https://github.com/JmoVxia/CLPlayer) - 自定义支持全屏的播放器。
    <div align=center>
    <img src="https://github.com/JmoVxia/CLPlayer/raw/master/效果图.gif" width="40%" />
    </div>

- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support ([FFmpeg](http://ffmpeg.org)).

- [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Support customization of any player SDK and control layer (支持定制任何播放器SDK和控制层)。
    <div align=center>
    <img src="https://camo.githubusercontent.com/48200df0498350786ba386f31336f7e6c8f07552/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3633353934322d303932343237653537313735363330392e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="50%" />
    <img src="https://camo.githubusercontent.com/dbee14e8706d7d044c9951be77097aeb2115f5e9/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3633353934322d653939643736343938636230316166622e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="50%" /> <br />
    <img src="https://camo.githubusercontent.com/af4de47d93b0b02197464c9118b0081ea51cf59c/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3633353934322d316230653233623766356561626439652e6a70673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="50%" />
    </div>

- [BMPlayer](https://github.com/BrikerMan/BMPlayer) - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brightness and seek by slide, support subtitles.
    <div align=center>
    <img src="https://github.com/BrikerMan/resources/raw/master/BMPlayer/demo.gif" width="50%" />
    </div>

- [SJVideoPlayer](https://github.com/changsanjiang/SJVideoPlayer) - Video Player. Support cocoapods & Generate GIF & Export & Localization & Play in View(UIView || TableHeader || TableCell || CollectionCell) & Keyboard Orientation & StatusBar(Style&Hide).
    <div align=center>
    <img src="https://user-images.githubusercontent.com/37614260/43947531-922a0712-9cb2-11e8-8f8d-4823a21308d3.png" width="50%" />
    </div>

- [kxmovie](https://github.com/kolyvan/kxmovie) - movie player for iOS using ffmpeg.
    <div align=center>
    <img src="https://camo.githubusercontent.com/ce6bc94079ae115bf2f9959020e427511f689742/68747470733a2f2f7261772e6769746875622e636f6d2f6174656c69657264756d6f62696c652f46466d706567506c617965722d694f532f6d61737465722f726561646d652d6d656469612f73637265656e73686f742d6d6f7669652d6c616e6473636170652e706e67" width="50%" />
    </div>

- [ffmpeg-avplayer-for-ios-tvos](https://github.com/imoreapps/ffmpeg-avplayer-for-ios-tvos) - A tiny but powerful iOS and Apple TV OS av player framework that's based on the FFmpeg library. 

- [Eleven](https://github.com/kaixinsoft/Eleven) - Eleven Player is a simple powerful video player.use ffmpeg.
  - [iOS配置FFmpeg框架](http://cnbin.github.io/blog/2015/05/19/iospei-zhi-ffmpegkuang-jia/) 
  - [Vitamio测试网络视频地址](https://www.vitamio.org/docs/Basic/2013/0508/14.html) 
    
- [SBPlayer](https://github.com/henusjj/SBPlayer) - 基于AVPlayer封装的轻量级播放器，可以播放本地网络视频，易于定制，可以横屏竖屏，支持M3u8、mp4等格式视频本地播放或者网络播放，通过masonry约束，适配各种尺寸iPhone。
    <div align=center>
    <img src="https://github.com/henusjj/SBPlayer/raw/master/Images/2.gif" width=260 />
    </div>

- [VKVideoPlayer](https://github.com/viki-org/VKVideoPlayer) - he same battle tested video player used in our [Viki iOS App](https://itunes.apple.com/app/id445553058?mt=8) enjoyed by millions of users all around the world.

- [KRVideoPlayer](https://github.com/36Kr-Mobile/KRVideoPlayer) - 类似Weico的播放器，支持竖屏模式下全屏播放。
    <div align=center>
    <img src="https://github.com/36Kr-Mobile/KRVideoPlayer/raw/master/kr_player.gif" width=260 />
    </div>

- [PBJVideoPlayer](https://github.com/piemonte/PBJVideoPlayer) - ▶️ video player, simple way to play and stream media on iOS/tvOS.

- [MRVLCPlayer](https://github.com/Maru-zhang/MRVLCPlayer) - 一款基于VLC的播放器,支持常用的各大手势功能，支持几乎所有主流格式。

#### 音乐播放器

- [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS (iPhone, iPad).

- [LyricsAnalysis](https://github.com/wsl2ls/LyricsAnalysis) - iOS音乐播放器之锁屏效果（仿网易云音乐和QQ音乐）+ 歌词解析 ：锁屏歌曲信息、控制台远程控制音乐播放：暂停/播放、上一首/下一首、快进/快退、列表菜单弹框和拖拽控制台的进度条调节进度（结合了QQ音乐和网易云音乐在锁屏状态下的效果）、歌词解析并随音乐滚动显示。
    <div align=center>
    <img src="https://camo.githubusercontent.com/a7f8d7a5c4d556835a74a48e47287699879ce9c0/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d613833663765343062303165346635302e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width=260 /> <img src="https://camo.githubusercontent.com/3fc34b6daa5822c88ddec99295f2dc33b376b67b/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d373265306262333661633033353330302e504e473f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width=260 />
    </div>

### IM和直播

- [AtChat](https://github.com/boyssimple/AtChat) - IOS聊天项目、基于XMPP框架开发，实现了登陆注册(注册以手机号码注册、短信验证) 、发送消息、接收消息、接收好友请求、发起好友请求 、图片消息、语音消息、视频语音、聊天历史记录、最近联系人、二维码添加好友、用户头像上传、朋友圈、发朋友圈、异地登录退出等功能。
    <div align=center >
    <img src="https://github.com/boyssimple/AtChat/raw/master/images/020.png" width=260 /> <img src="https://github.com/boyssimple/AtChat/raw/master/images/014.png" width=260 />
    </div> 

- [BAWeChat](https://github.com/BAHome/BAWeChat) - 博爱微信，使用原生 frame + MVVM + MVC + QMUIKit + BAKit 开源的微信。
    <div align=center >
    <img src="https://github.com/boai/BAWeChat/raw/master/Images/通讯录.png" width=260 /> <img src="https://github.com/boai/BAWeChat/raw/master/Images/评论.png" width=260 />
    </div> 

- [ABigFishTV](https://github.com/clyhs/ABigFishTV) - 大鱼电视直播 基于ijkplayer的播放器 700多个电视台 包括央视，各地方台，卫视，熊猫直播，社会化分享，登陆，仿微博等 (支持iphonex)。
    <div align=center>
    <img src="https://github.com/clyhs/ABigFishTV/raw/master/images/ABigFishTV.gif" width="30%" />
    </div> 

- [TGTV](https://github.com/targetcloud/TGTV) - TGTV直播APP用Swift3.1编写，采用MVVM架构，本demo运用protobuf实现即时聊天（弹幕）、礼物动画等。
    <div align=center >
    <img src="https://github.com/targetcloud/TGTV/raw/master/1.gif" width=260 /> <img src="https://github.com/targetcloud/TGTV/raw/master/屏幕快照%202017-04-13%20下午5.22.09.png" width=260 />
    </div>

- [MGMiaoBo](https://github.com/LYM-mg/MGMiaoBo) - 首创房间内多视频直播模式，移动直播新体验，多人秀场更好玩。随时随地与主播聊天互动亲密接触，清纯美女、校花嫩模、吃货萌妹、通通都有…… 1.项目引导页业使用ijkPlayer播放视频；2.首页使用父子控制器进行界面之间的切换；3.自定义MJRefresh刷新控件，替换头部刷新gif图片；4.使用分类理由贝塞尔曲线为UIImageView添加圆角；5.服务器交互使用的是https，用json格式，面向模型开发;其他：全局网络请求封装，页面数据缓存处理，通知，动画，基础控制器封装，使用xib的AutoLayout和Masonry第三方库等。
    <div align=center >
    <img src="https://camo.githubusercontent.com/75db51c6486a07e0817d8a1b498740620ecb0f1f/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d396361383335623732613562303533612e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width=260 /> <img src="https://camo.githubusercontent.com/1807bcb191968c41603e13ccc9639adbdf6f1f27/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d393064646435626566333361313539352e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width=260 />
    </div> 

- [MGDYZB](https://github.com/LYM-mg/MGDYZB) - Xcode8以上版本，已升级为Swift3.x语法。斗鱼-每个人的直播平台提供高清、快捷、流畅的视频直播和游戏赛事直播服务，包含英雄联盟lol直播、穿越火线cf直播、dota2直播、美女直播等各类热门游戏赛事直播等。
    <div align=center >
    <img src="https://camo.githubusercontent.com/0b93ec631006cb13a26ae52771763f5ffb869534/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d666262356535623431326334343363662e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width=260 /> <img src="https://camo.githubusercontent.com/a7e7ead1a95fd7fc9c3f6445f49ecb08ef26ed1f/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d366437326262323634303831353932642e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width=260 />
    </div> 

- [PLPlayerKit](https://github.com/pili-engineering/PLPlayerKit) - PLPlayerKit 是七牛推出的一款免费的适用于 iOS 平台的播放器SDK，采用全自研的跨平台播放内核，拥有丰富的功能和优异的性能，可高度定制化和二次开发。([ios-playback-end-the-sdk](https://developer.qiniu.com/pili/sdk/1211/ios-playback-end-the-sdk))

- [PLMediaStreamingKit](https://github.com/pili-engineering/PLMediaStreamingKit) - PLMediaStreamingKit 是七牛推出的一款适用于 iOS 平台的推流 SDK，支持 RTMP 推流，h.264 和 AAC 编码，硬编、软编支持。具有丰富的数据和状态回调，方便用户根据自己的业务定制化开发。具有直播场景下的重要功能，如：美颜、背景音乐、水印等功能。

### Data Persistence

*FMDB & Keychain & NSUserDefaults*

- [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS, watchOS, tvOS and macOS. Makes using Keychain APIs as easy as NSUserDefaults.

### 逆向开发

#### fishhook

- [fishhook](https://github.com/facebook/fishhook) - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS. 
    <div align=center>
    <img src="https://camo.githubusercontent.com/18243516844d12b1bd158ce3687635d6e48d2e2e/687474703a2f2f692e696d6775722e636f6d2f4856587148437a2e706e67" width="60%" />
    </div>

#### 逆向辅助工具

- [iOSOpenDev](http://iosopendev.com)
- [theos](http://iphonedevwiki.net/index.php/Theos/Setup) - 一个越狱开发工具包 ([Github](https://github.com/theos/theos).)
- [class-dump](https://github.com/nygard/class-dump) - Generate Objective-C headers from Mach-O files. 
- [Clutch](https://github.com/KJCracks/Clutch) - a high-speed iOS decryption tool. It supports the iPhone, iPod Touch, and iPad.
- [optool](https://github.com/alexzielenski/optool) - Command Line Tool for interacting with MachO binaries on OSX/iOS.
- [HackAppTool](https://github.com/jackrex/FakeWeChatLoc/tree/master/HackAppTool) 
- [Tools](https://github.com/east520/AutoGetRedEnv/tree/master/Tools)

#### 逆向案例

- [WeChatRedEnvelop](https://github.com/buginux/WeChatRedEnvelop) - iOS版微信抢红包Tweak。
  - [iOS微信抢红包Tweak安装教程](http://www.swiftyper.com/2016/01/25/ios-tweak-install-guide/)
  - [免越狱版 iOS 抢红包插件](http://www.swiftyper.com/2016/12/26/wechat-redenvelop-tweak-for-non-jailbroken-iphone/)
  <div align=center>
  <img src="https://github.com/buginux/WeChatRedEnvelop/raw/master/ScreenShots/Setting.jpeg" width=260 /> <img src="https://github.com/buginux/WeChatRedEnvelop/raw/master/ScreenShots/AssistantSetting.jpeg" width=260 />
  </div>

- [WeChatRedEnvelopesHelper](https://github.com/luckysine/WeChatRedEnvelopesHelper) - iOS版微信抢红包插件，支持后台抢红包，tweak源文件。
    <div align=center>
    <img src="https://github.com/luckysine/WeChatRedEnvelopesHelper/raw/master/screenshots/step.png" width="60%" />
    </div>

- [AutoGetRedEnv](https://github.com/east520/AutoGetRedEnv) - 微信自动抢红包。

- [FakeWeChatLoc](https://github.com/jackrex/FakeWeChatLoc) - iOS伪装微信位置。
    - [iOS逆向论坛](http://bbs.iosre.com) 
    <div align=center>
    <img src="https://raw.githubusercontent.com/jackrex/FakeWeChatLoc/master/pic/1464391571144.png" width=260 /> <img src="https://raw.githubusercontent.com/jackrex/FakeWeChatLoc/master/pic/1464391684987.png" width=260 />
    </div>

- [FakeWeChatLocation](https://github.com/PandaraWen/FakeWeChatLocation) - A tweak that can fake location info in WeChat.

- [FishChat](https://github.com/yulingtianxia/FishChat) - Hook WeChat.app on non-jailbroken devices. ([blog](http://yulingtianxia.com/blog/2017/02/28/Make-WeChat-Great-Again/)) 
    <div align=center>
    <img src="https://github.com/yulingtianxia/FishChat/raw/master/Images/logo.png" width="20%" /> <br /> 
    <img src="https://github.com/yulingtianxia/FishChat/raw/master/Images/weichat_ignore_chatroom.PNG" width="30%" /> <img src="https://github.com/yulingtianxia/FishChat/raw/master/Images/wechat_setting_keyboard.PNG" width="30%" />
    </div>
    
- [WeTransparentChat](https://github.com/PandaraWen/WeTransparentChat) - Use back camera capturing make WeChat's message content page's background transparent.
    <div align=center>
    <img src="https://github.com/PandaraWen/WeTranslateparentChat/raw/master/images/IMG_0018.PNG" width="40%" />
    </div>

### 数据安全相关

- [DYFCryptoUtils](https://github.com/dgynfi/DYFCryptoUtils) - 🔥一行代码实现 iOS Base64, MD5, DES, AES, RSA算法，操作简单好用。

- [AESCipher-iOS](https://github.com/WelkinXie/AESCipher-iOS) - AES encryption working between Objective-C and Java. ([AESCipher-Java](https://github.com/WelkinXie/AESCipher-Java))

- [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.

- [RSADemo](https://github.com/DullDevil/RSADemo) - RSA加解密相关方方法，以及密钥格式的生成与转换。

- [Encryptions](https://github.com/iamlay/Encryptions) - this project is for many kinds odf encryption. 
    <div align=center>
    <img src="https://github.com/Flying-Einstein/Encryptions/raw/master/Encryption/encryption.gif" width="30%" />
    </div>

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - CryptoSwift是在Swift中实现的越来越多的标准和安全密码算法的集合。 

- [Security-iOS](https://github.com/cocoajin/Security-iOS) - 封装了一些iOS上使用的NSData分类，主要用于 RSA加密、AES加密、数据签名、签名校验、MD5、SHA1、SHA256 常用hash等工具。

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - Encrypt/Decrypt: AES. Hash: MD5, SHA(SHA1, SHA224, SHA256, SHA384, SHA512). Encode/Decode: Base64, Hex.

### 蓝牙

- [EasyBluetooth]( https://github.com/chenliangloveyou/EasyBluetooth) - 一款iOS BLE蓝牙调试工具，非常简单容易，也可以作为一个蓝牙库，快速集成和开发。 可以两步搞定蓝牙开发操作。第一步连接设备，第二步特征读写数据。
    <div align=center >
    <img src="https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_1.gif" width=260 /> <img src="https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_2.gif" width=260 /> <br />
    <img src="https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_3.png" width=260 /> <img src="https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_4.png" width=260 />
    </div> 

- [WHBLEDemo](https://github.com/remember17/WHBLEDemo) - 📱CoreBluetooth central and peripheral demo with OC/Swift (iOS蓝牙中心设备和外设开发,包含OC/Swift版本) 。
    <div  align=center >
    <img src="https://camo.githubusercontent.com/3ba378f9a697f5e30d6937f64ba8a97498bb3513/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d613731636537393634653834613263652e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="70%" />
    <img src="https://camo.githubusercontent.com/47b0012be03c0f3f6c59c7169fa4563ff6380d7c/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d353334626433303463346537393765362e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width="60%" />
    </div> 

- [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 简单易用的蓝牙库，基于CoreBluetooth的封装，并兼容ios和mac osx。
    <div align=center >
    <img src="https://github.com/coolnameismy/BabyBluetooth/raw/master/logo.png" width="50%" /> 
    </div> 

- [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE.

- [MultipeerConnectivity](https://github.com/xiangzuhua0209/MultipeerConnectivity) - 蓝牙MultipeerConnectivity。

- [WEBlueToothManager](https://github.com/yuhanle/WEBlueToothManager) - 🐱一个蓝牙4.0的智能硬件架构。([blog](https://latehorse.github.io))
    <div align=center>
    <img src="https://camo.githubusercontent.com/d35e114d02c6b82ccea90e1547d268607362ee41/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3534353735352d343837633230623536646461623832322e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="50%" /> 
    <img src="https://camo.githubusercontent.com/d1f9847a9232542113ffdd226ea5b3773f26b5f1/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3534353735352d303161616262356533396130613735302e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430" width="50%" /> 
    </div>

### 手势指纹面容ID密码解锁

- [XGTouchDemo](https://github.com/XGPASS/XGTouchDemo) - 手势密码解锁和指纹TouchID解锁的demo。
    <div align=center>
    <img src="https://github.com/XGPASS/XGTouchDemo/raw/master/images/develop.gif" width="40%" />
    </div>

### 图像绘制

#### Graphs

- [Graphs](https://github.com/candy7/Graphs) - 通过bezierPath，画出曲线图，并且加入动画。
    <div align=center>
    <img src="https://camo.githubusercontent.com/955dab2a5598a7dcb509b3c448b12a37a1760570/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f323035353836362d333233653639333130323262353461662e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width="50%" />
    </div>

### 扫码器

*二维码，条形码相关内容*

- [MMScan](https://github.com/MinMao-Hub/MMScan) - 一个简单的二维码以及条码扫描工具，使用Objective-C语言开发，有一套自定义的扫描动画以及界面，还包括生成二维码以及条码。
    <div align=center>
    <img src="https://github.com/MinMao-Hub/MMScan/raw/master/gifs/mmscan.gif" width="40%" />
    </div>

- [QRCode](https://github.com/kingcong/QRCode-master) - 仿微信二维码扫描。

- [LBXScan](https://github.com/MxABC/LBXScan) - A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing、ZBar、iOS系统AVFoundation扫码封装，扫码界面效果封装)。
    <div align=center>
    <img src="https://github.com/MxABC/Resource/raw/master/scan12.gif" width="30%" />
    </div>
  
- [swiftScan](https://github.com/MxABC/swiftScan) - A barcode and qr code scanner( 二维码 各种码识别，生成，界面效果)。
    <div align=center>
    <img src="https://github.com/MxABC/swiftScan/raw/master/ScreenShots/page1.jpg" width="30%" /> <img src="https://github.com/MxABC/swiftScan/raw/master/ScreenShots/page2.jpg" width="30%" />
    </div>

- [SGQRCode](https://github.com/kingsic/SGQRCode) - The easy to use QRCode scan library for iOS【iOS 原生二维码生成与扫描 -> 高仿微信】。
    <div align=center>
    <img src="https://raw.githubusercontent.com/kingsic/SGQRCode/master/Picture/sorgle1.png" width="30%" /> <img src="https://raw.githubusercontent.com/kingsic/SGQRCode/master/Picture/sorgle4.png" width="30%" />
    </div>

- [EFQRCode](https://github.com/EFPrefix/EFQRCode) - A better way to operate QR Code in Swift, support iOS, macOS, watchOS and tvOS. 
    <div align=center>
    <img src="https://raw.githubusercontent.com/EFPrefix/EFQRCode/assets/QRCodeGIF6.gif" width="20%" />
    </div>

### 下拉刷新和上拉加载

- [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - An easy way to use pull-to-refresh.
    <div align=center>
    <img src="https://camo.githubusercontent.com/15577b87be4403d9e2ede4d5cd5b9fccbd1d03ae/687474703a2f2f696d61676573302e636e626c6f67732e636f6d2f626c6f67323031352f3439373237392f3230313530362f3134313230343334333438363135312e676966" width=260 /> <img src="https://camo.githubusercontent.com/911191d46157ea3961728b16696aea4440ffeb92/687474703a2f2f696d61676573302e636e626c6f67732e636f6d2f626c6f67323031352f3439373237392f3230313530362f3134313230343430323233383338392e676966" width=260 />
    </div>

### 指示器

- [EasyShowView](https://github.com/chenliangloveyou/EasyShowView) - 一款超级简单的展示工具，包括吐司指示器，loding加载框，空白页提示，alertview，actionsheet的定制。可任意定制自己想要的各种样式，自定义动画，显示样式等各种操作，使各种展示更加easy。
    <div align=center>
    <img src="https://github.com/chenliangloveyou/EasyShowView/raw/master/show_preview/preview_text.gif" width=260 /> <img src="https://github.com/chenliangloveyou/EasyShowView/raw/master/show_preview/preview_loding.gif" width=260 />
    </div>

- [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - MBProgressHUD + Customizations. [http://www.bukovinski.com/](http://www.bukovinski.com/)

- [MBProgressHUD-JDragon](https://github.com/lyc59621/MBProgressHUD-JDragon) - MBProgressHUD 封装。
    <div align=center>
    <img src="https://github.com/lyc59621/MBProgressHUD-JDragon/raw/master/MBProgressHUD-JDragon.gif" width=260 />
    </div>

- [JGProgressHUD](https://github.com/JonasGessner/JGProgressHUD) - An elegant and simple progress HUD for iOS and tvOS, compatible with Swift and ObjC.
    <div align=center>
    <img src="https://github.com/JonasGessner/JGProgressHUD/raw/master/Examples/Screenshots/Presentation.png" width="50%" />
    </div>

- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS and tvOS app. 

### Toast

- [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 向UIView对象类添加Toast通知的Swift扩展。([Objective-C版](https://github.com/scalessec/Toast))
    <div align=center>
    <img src="https://github.com/scalessec/Toast-Swift/raw/master/toast_swift_screenshot.jpg" width=260 />
    </div>

- [XHToast](https://github.com/CoderZhuXH/XHToast) - 简洁轻便提示工具,一行代码既可完成提示信息显示 - 支持自定义显示位置及停留时间。
    <div align=center>
    <img src="https://camo.githubusercontent.com/5e94289a5930fe4de9e844f94a308b6d3919e59b/687474703a2f2f682e686970686f746f732e62616964752e636f6d2f696d6167652f7069632f6974656d2f303233623562623563396561313563653239373365343339626530303361663333613837623236342e6a7067" width=260 />
    </div>

- [toast-notifications-ios](https://github.com/ecstasy2/toast-notifications-ios) - We at Guru software really love toast notifications available on android OS, so we've built a similar feature for the IOS enabled devices.

- [JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications) - An iOS UIView for presenting a minimalistic notification that doesn't block the UI and is highly configurable.

### Menu

- [kxmenu](https://github.com/kolyvan/kxmenu) - KxMenu is a vertical popup menu for using in iOS applications.
    <div align=center>
    <img src="https://camo.githubusercontent.com/d28144796042a6c6bddf7d0c097be831cea8810a/68747470733a2f2f7261772e6769746875622e636f6d2f6b6f6c7976616e2f6b786d656e752f6d61737465722f73637265656e73686f742f6578616d706c652e676966" width="60%" />
    </div>

- [LCSlideMenu](https://github.com/ChinaHackers/LCSlideMenu) - A powerful and easy to use slider menu. 
    <div align=center>
    <img src="https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/LCSlideMenu.png" width="60%" /> <br /> 
    <img src="https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast01.gif" width=260 /> <img src="https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast03.gif" width=260 />
    </div>

- [JMColumnMenu](https://github.com/JunAILiang/JMColumnMenu) - 仿腾讯新闻、今日头条栏目管理。

- [WJPageManager](https://github.com/WJCha/WJPageManager) - WJPageManager提供了可以快速完成项目中常见的标题栏以及对应的分页控制器创建与逻辑处理。
    <div align=center>
    <img src="https://github.com/WJCha/WJPageManager/raw/master/resource/title.gif" width=260 /> <br />
    <img src="https://github.com/WJCha/WJPageManager/raw/master/resource/page.gif" width=260 />
    </div>

- [MLMenu](https://github.com/MrDML/MLMenu) - 仿微信QQ右上角菜单功能。
    <div align=center>
    <img src="https://github.com/MrDML/MLMenu/raw/master/MLMenuGif.gif" width=260 />
    </div>

- [JMDropMenu](https://github.com/JunAILiang/JMDropMenu) - 仿QQ、微信下拉菜单封装，支持自定义样式。
    <div align=center>
    <img src="https://raw.githubusercontent.com/JunAILiang/JMDropMenu/master/JMDropMenu/JMDropMenu.gif" width=300  />
    </div>

- [XYMenu](https://github.com/HeathHsia/XYMenu) -  简易集成的弹出菜单。
    <div align=center>
    <img src="https://github.com/HeathHsia/XYMenu/raw/master/img/demo.gif" width="30%" />
    </div>

- [REMenu](https://github.com/romaonthego/REMenu) - Dropdown menu inspired by Vine.
    <div align=center>
    <img src="https://raw.githubusercontent.com/romaonthego/REMenu/master/Demo.gif" width=260 />
    </div>

- [PopMenu](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app.
    <div align=center>
    <img src="https://github.com/xhzengAIB/LearnEnglish/raw/master/Screenshots/XHSinaMenuViewExample.gif" width=260 />
    </div>

- [SHESelectTable](https://github.com/shelly8219/SHESelectTableDemo) - 下拉选择的列表。
    <div align=center>
    <img src="https://github.com/shelly8219/SHESelectTableDemo/raw/master/source/screenclip.jpg" width=260 />
    </div>

- [MMComboBox](https://github.com/YYWDark/MMComboBox) - A comboBox contained three kinds of style.
    <div align=center>
    <img src="https://camo.githubusercontent.com/30c25cfaecb29ebfb9a59a5fe93a6751342d163a/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3330373936332d353837313561313431633063653630302e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width="40%" />
    </div>

### 图片浏览器

- [SDPhotoBrowser](https://github.com/gsdios/SDPhotoBrowser) - A image browser which is easy for using. 非常简单易用的图片浏览器，模仿微博图片浏览器动感效果，综合了图片展示和存储等多项功能。
    <div align=center>
    <img src="https://camo.githubusercontent.com/a2e87ee4bd1c7b97913e2f9de8b416302032157c/687474703a2f2f63646e2e636f63696d672e636f6d2f6262732f6174746163686d656e742f4669645f31392f31395f3434313636305f3633313963353063333465643633632e676966" width="40%" />
    </div>

- [YHPhotoBrowser](https://github.com/hackxhj/YHPhotoBrowser) - 轻量级网络图片浏览器 优化性能 Gif播放性能 类新浪微博打开关闭动画 类微信图片浏览下拉图片消失。
    <div align=center>
    <img src="https://raw.githubusercontent.com/hackxhj/YHPhotoBrowser/master/png/yh.gif" width="60%" />
    </div>

### WebView和进度条

- [XDProgressView](https://github.com/Tbwas/XDProgressView) - XDProgressView可以由你心情任意设置高度，也可在上面显示文字。

- [YQLWebViewProgress](https://github.com/Dogndxt/YQLWebViewProgress) - 网页进度条显示，WebViewProgress.

- [WYWebViewDemo](https://github.com/wangyansnow/WYWebViewDemo) - 进度条加载网页。
    <div align=center>
    <img src="https://github.com/wangyansnow/WYWebViewDemo/raw/master/WYWebViewDemo/screenShot/webViewLoading.gif" width="60%" />
    </div>

- [CHWebView](https://github.com/chausson/CHWebView) - 简化UIWebView和WKWebView的API使用，在此基础上实现进度条和简单JS交互事件。
    <div align=center>
    <img src="https://github.com/chausson/CHWebView/raw/master/Resource/WebView.gif" width="50%" /> <br />
    <img src="https://github.com/chausson/CHWebView/raw/master/Resource/CHWebView.png" width="40%" />
    </div>

### 动画

- [MGTrasitionPractice](https://github.com/LYM-mg/MGTrasitionPractice) - 自定义转场练习。
    <div align=center>
    <img src="http://upload-images.jianshu.io/upload_images/1429890-db65965fb55e23ed.gif?imageMogr2/auto-orient/strip" width="60%" />
    </div>

- [iOSAnimation](https://github.com/BranPeng/iOSAnimation) - 好玩的iOS动画。

- [iOS-Swift-Animation](https://github.com/BranPeng/iOS-Swift-Animation) - iOS Swift动画框架。

### 选择器

- [BRPickerView](https://github.com/91renb/BRPickerView) - 封装的是iOS中常用的选择器组件。高度封装，只需一句代码即可完成调用，使用比较灵活支持自定义主题颜色。选择器类型主要包括：日期选择器、时间选择器、地址选择器、自定义字符串选择器。
    <div align=center>
    <img src="https://github.com/91renb/BRPickerView/raw/master/BRPickerViewDemo/效果图/效果图1.gif?raw=true" width="30%" /> <img src="https://github.com/91renb/BRPickerView/raw/master/BRPickerViewDemo/效果图/效果图2.gif?raw=true" width="30%" />
    </div>

### 搜索

- [PYSearch](https://github.com/ko1o/PYSearch) - 🔍 An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad) .
    <div align=center>
    <img src="https://github.com/iphone5solo/learngit/raw/master/imagesForPYSearch/logo.png" width="40%" /> 
    </div>
    <div align=center>
    <img src="https://raw.githubusercontent.com/ko1o/learngit/master/imagesForPYSearch/hotSearchStyle01.png" width=260 /> <img src="https://github.com/ko1o/learngit/raw/master/imagesForPYSearch/hotSearchStyle02.png" width=260 />
    </div>

### 分享


- [TTOpenInAppActivity](https://github.com/honkmaster/TTOpenInAppActivity) - TTOpenInAppActivity is a UIActivity subclass that provides an "Open In ..." action to a UIActivityViewController. TTOpenInAppActivity uses an UIDocumentInteractionController to present all Apps that can handle the document specified with by the activity items.
    <div align=center>
    <img src="https://github.com/honkmaster/TTOpenInAppActivity/raw/master/Screenshot.png" width="50%" />
    </div>

### 图片验证码

- [ZLSecurityCode](https://github.com/ZLFighting/ZLSecurityCode) - iOS-字符图片验证码。
    <div align=center>
    <img src="https://github.com/ZLFighting/ZLSecurityCode/raw/master/ZLSecurityCode/验证码图.gif" width="30%" />
    </div>

- [MQVerCodeView](https://github.com/meiqi1992/MQVerCodeView) - 类似图片验证码，点击可刷新。
    <div align=center>
    <img src="https://github.com/meiqi1992/MQVerCodeView/raw/master/verCodeView.gif" width=260 />
    </div>

- [YanZhengCode](https://github.com/wsl2ls/YanZhengCode) - 图片验证码和滑块验证码。
    <div align=center>
    <img src="https://camo.githubusercontent.com/2a26c12270d298a74738691b13578d53e962835c/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d303566316430626239646431313537372e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width=260 />
    </div>

### 获取设备相关信息

- [iOS-getClientInfo](https://github.com/PengfeiWang666/iOS-getClientInfo) - 📲iOS中获取各种设备信息。

- [ZGInfoCollection](https://github.com/ScottZg/ZGInfoCollection) - 获取iPhone相关信息以及网络状态等等。

### 广告

- [ZLAdvertDemo](https://github.com/ZLFighting/ZLAdvertDemo) - 启动页加载广告。
    <div align=center>
    <img src="https://github.com/ZLFighting/ZLAdvertDemo/raw/master/ZLAdvertDemo/启动页跳过广告.gif" width="30%" />
    </div>

- [SplashScreenADView](https://github.com/wxzwork/SplashScreenADView) - 启动图和开屏广告页，类似网易。可根据广告的有效时间显示或关闭广告页，以及定制广告页停留的时间。

### 高仿项目和项目Demo

- [iOSProject](https://github.com/NJHu/iOSProject) - iOS project of collected some demos for iOS App. ([Swift版](https://github.com/NJHu/iOSProject))
    <div align=center>
    <img src="https://raw.githubusercontent.com/NJHu/iOSProject/master/images//home.gif" width=260 /> <img src="https://raw.githubusercontent.com/NJHu/iOSProject/master/images/anidynquar.gif" width=260 />
    </div>

- [ZFZhiHuDaily](https://github.com/renzifeng/ZFZhiHuDaily) - 知乎日报swift版(精仿)。

- [BingFenShiJia](https://github.com/hurryupcheng/BingFenShiJia) -  缤微纷购。

- [ifanr](https://github.com/iCodeForever/ifanr) - 高仿 爱范儿。

- [MobileProject](https://github.com/wujunyang/MobileProject) - 是一个以MVC模式搭建的开源功能集合，基于Objective-C上面进行编写，意在解决新项目对于常见功能模块的重复开发，MobileProject对于项目的搭建也进行很明确的划分，各个模块职责也比较明确，MobileProject也引入的一些常用第三方插件、宏定义、工具帮助类等；整个项目也是在不断更新跟维护中，功能点也会不断更新；代码支持iOS7以后版本。

- [WSLAPP](https://github.com/wsl2ls/WSLAPP) - 音乐播放器，新闻，壁纸，画板，二维码，计分器，一个我自己做的完整的项目源码。

- [iOS_Demo](https://github.com/darren90/iOS_Demo) - iOS开发中一些实用的Demo。

- [iOS-Project](https://github.com/BranPeng/iOS-Project) - 收集的一些比较好的iOS打样工程。

- [coolnameismy - blog](https://github.com/coolnameismy/demo) - coolnameismy的技术博客文章对应的demo。

- [LiuAGeIOS](https://github.com/6ag/LiuAGeIOS) - 六阿哥网iOS版，资讯类客户端。 

- [MGSinaWeibo](https://github.com/LYM-mg/MGSinaWeibo) - 高仿新浪微博访客视图，首页，发布界面等 使用技术：MVVM设计模式，使用纯代码和Xib混合开发，使用SnapKit做UI布局，AFN网络数据请求，MJExtension进行字典转模型数据，使用SDWebImage进行图片加载，二维码的扫描和生成，图文混排，不等高cell的计算，表情键盘，图片上传和图片浏览器等技术。

- [MGBaisi](https://github.com/LYM-mg/MGBaisi) - 高度仿写百思不得姐项目，实现精华，新帖，发布，关注，我的五大功能模块，运用了很多技术。 使用技术：MVC设计模式，使用纯代码和Xib混合开发，使用Masonry和AutoLayout做UI布局，首页精华模块充分使用父子控制器，音频视频的播放，集成系统自带新浪分享，评论详情界面，发布集成pop动画，关注界面充分利用Xib的优势，使用SDWebImage进行图片加载，MBProessHUD进行遮盖提示，清除缓存功能，UIWebView进行网页加载等技术。

- [MGDemo](https://github.com/LYM-mg/MGDemo) - 涉及导航栏随着tableView滑动是否隐藏，随着tableView的滑动让TabBar隐藏，停止滑动显示TabBar。还有NavigationController的titleView动态缩放效果，还加了UITableView分区展开与收起。后来又加了录制视频的功能和在相册中选择视频的功能。tableView的一些常用知识点，还有搜索框的使用。后来又整合了UICollectionView的使用,ShareSDK分享等。

- [MGLoveFreshBeen](https://github.com/LYM-mg/MGLoveFreshBeen) - 一款电商App，实现首页功能以及个人中心和分类，购物车模块。1.MVC设计模式 2.使用纯代码和Xib混合开发，使用Masonry和AutoLayout做UI布局；3.集成友盟分享 4.使用SDWebImage进行图片加载 5.SVProessHUD和MBProessHUD进行遮盖提示 6.UITableView的联动效果 7.首页UICollectionView进行数据显示 8.UIWebView加载网页等技术。

### Others

#### Sensor

- [SensorDemo](https://github.com/wsl2ls/SensorDemo) - 指纹识别、运动传感器、加速计、环境光感、距离传感器、指南针、陀螺仪等传感器示例集锦。
    <div align=center>
    <img src="https://camo.githubusercontent.com/339dfa9c656084dc5d29496ec168c43426a8e201/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d373764333332623832386363336261332e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width="30%" />
    </div> 

#### Privacy

- [BAPrivacyManager](https://github.com/boai/BAPrivacyManager) - iOS 所有隐私权限封装，定位、蓝牙、通知、运动、日历、相册、相机等 14 种权限封装！
    <div align=center >
    <img src="https://github.com/BAHome/BAPrivacyManager/raw/master/Images/BAPrivacyManager1.png" width="30%" />
    </div>

#### 未归类

- [MSWeakTimer](https://github.com/mindsnacks/MSWeakTimer) - Thread-safe NSTimer alternative that doesn't retain the target and supports being used with GCD queues.

- [NNMacros](https://github.com/amisare/NNMacros) - NNMacros通过宏的方式来简化iOS开发中OC的语法和Api的操作。

- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - 一个可以很容易地为iOS创建漂亮的、高度可定制的动画复选框。
    <div align=center>
    <img src="https://github.com/Boris-Em/BEMCheckBox/raw/master/.assets/BEMCheckBox.gif" width="30%" />
    </div>

- [SCIndexView](https://github.com/TalkingJourney/SCIndexView) - SCIndexView provide a index view like Wechat.
    <div align=center>
    <img src="https://github.com/TalkingJourney/SCIndexView/raw/master/SCIndexViewDemo/Snapshots/demo_default.gif" width="30%" /> <img src="https://github.com/TalkingJourney/SCIndexView/raw/master/SCIndexViewDemo/Snapshots/demo_center_toast.gif" width="30%" />
    </div>

- [UICountingLabel](https://github.com/dataxpress/UICountingLabel) - Adds animated counting support to UILabel. 
    <div align=center>
    <img src="https://github.com/dataxpress/UICountingLabel/raw/master/demo.gif" width="60%" />
    </div>

- [LYThemeChange](https://github.com/lanyasheng/LYThemeChange) - 主题更换。

- [iOS-Swift-UI](https://github.com/BranPeng/iOS-Swift-UI) - iOS-Swift-UI.

- [BAAlertController](https://github.com/BAHome/BAAlertController) - UIAlertController 的分类，一个block 搞定系统 alert 和 actionSheet 的 iPhone 和 iPad 版本适配！
    <div align=center>
    <img src="https://github.com/BAHome/BAAlertController/raw/master/Images/BAAlertController4.png" width="40%" />
    <img src="https://github.com/BAHome/BAAlertController/raw/master/Images/BAAlertController7.png" width="40%" />
    </div>

- [MMPopupView](https://github.com/adad184/MMPopupView) - A basic Pop-Up Kit allows you to easily create Pop-Up view. You can focus on the only view you want to show.Besides, it comes with 2 common Pop-Up view, MMAlertView & MMSheetView. You can easily use & customize it. 
    <div align=center>
    <img src="https://github.com/adad184/MMPopupView/raw/master/Images/0.jpg" width="50%" />
    </div>

- [jiaModuleDemo](https://github.com/wujunyang/jiaModuleDemo) - 一个针对iOS模块化开发的解决方案。
    <div align=center>
    <img src="https://github.com/wujunyang/jiaModuleDemo/raw/master/jiaModuleDemo/ProjectImage/1.png" width="60%" />
    </div>

- [DraggingSort](https://github.com/HelloYeah/DraggingSort) - 长按拖拽排序。
    <div align=center>
    <img src="https://camo.githubusercontent.com/bab591bc633afc9a316d5aedad2c45d42da2b91d/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313333383034322d646431356539306464396537353266632e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970" width="50%" />
    </div>

- [RSSliderView](https://github.com/rsimenok/RSSliderView) - Custom slider based on UIView for iOS.
    <div align=center>
    <img src="https://camo.githubusercontent.com/7a7a899104ae97a30b0aae97bb2ce7d80a8a0f25/687474703a2f2f692e70696363792e696e666f2f69392f61666463643862353032396531663238623862643333663762643338323263312f313432343131383133392f31323632322f3738303432352f3132332e706e67" width="30%" />
    </div> 

- [ScrollShowHeaderDemo](https://github.com/Cloudox/ScrollShowHeaderDemo) - 上下滑动列表时展现和隐藏顶部视图的demo。
    <div align=center>
    <img src="https://github.com/Cloudox/ScrollShowHeaderDemo/raw/master/demo.gifdth="60%" />
    </div>

- [CopyLabel](https://github.com/TUTUDeveloper/CopyLabel) - iOS拥有复制功能的Label。

- [WKWebViewDemo](https://github.com/SSiming/WKWebViewDemo) - WKWebView实际使用中遇到的注意点，以及WKWebView和JavaScript交互。具体介绍请戳[WKWebView使用及注意点(keng)](http://www.jianshu.com/p/9513d101e582)。

- [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) - iOS平台利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志。
    <div align=center>
    <img src="https://github.com/Lede-Inc/LDNetDiagnoService_IOS/raw/master/LDNetDiagnoServiceDemoTests/netdiagnosis_ios.jpg"  width="30%" />
    </div>

- [TOSMBClient](https://github.com/TimOliver/TOSMBClient) -  A small library that serves as a simple SMB (Server Message Block ) client for iOS apps. The library allows connecting to SMB devices, downloading file metadata, and subsequently allows asynchronous downloading of files from an SMB device straight to an iOS device. It is an Objective-C wrapper around Defective SMb, or libDSM, a low level SMB client library built in C built by some of VideoLabs' developers. A copy of libDSM has been specially cross-compiled for iOS device architectures and embedded in this library, so this project has no external dependencies.

- [ZZHotKeysMenu](https://github.com/zhouXiaoR/ZZHotKeysMenu) - ZZHotKeysMenu自定义布局，继承自UICollectionViewLayout。
    <div align=center>
    <img src="https://github.com/zhouXiaoR/ZZHotKeysMenu/raw/master/运行效果.gif" width="30%" />
    </div>

#### 分享其他分类汇总

- [awesome-ios](https://github.com/vsouza/awesome-ios) - A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects.

- [arodung-blog](http://blog.csdn.net/arodung/article/details/50846546) - Github上最全的iOS开源项目分类汇总。


## Mac

- [dSYMTools](https://github.com/answer-huang/dSYMTools) - dSYM analyze. 
    <div align=center>
    <img src="https://camo.githubusercontent.com/e4d2bc52e9f048c7c14af6cfc4339f055fab5e38/687474703a2f2f616e737765726875616e672e626a2e626365626f732e636f6d2f626c6f672f6473796d546f6f6c2e706e67" width="60%" />
    </div>

- [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) - This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device. ([Instructions](https://dantheman827.github.io/ios-app-signer/))

- [iReSign](https://github.com/maciekish/iReSign) - ReSign allows iDevice app bundles (.ipa) files to be signed or resigned with a digital certificate from Apple for disibution. This tool is aimed at enterprises users, for enterprise deployment, when the person signing the app is different than the person(s) developing it.

- [EasyResigny](https://github.com/niyaoyao/EasyResigny) - A Mac tool for user to resign iOS App.

- [Resign](https://github.com/LigeiaRowena/) - OSX utility to resign the IPA files.

- [FinderGo](https://github.com/onmyway133/FinderGo) - 🐢 Open terminal quickly from Finder. ([blog](https://onmyway133.github.io/))
    <div align=center>
    <img src="https://github.com/onmyway133/FinderGo/raw/master/Images/Icon.png" width="20%" /> <br />
    <img src="https://github.com/onmyway133/FinderGo/raw/master/Images/go1.gif" width="60%" />
    </div>

- [iOS-Images-Extractor](https://github.com/devcxm/iOS-Images-Extractor) - A Mac app to decode and extract images from iOS apps, support png/jpg/ipa/Assets.car files.

- [cartool](https://github.com/steventroughtonsmith/cartool) - Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

- [VVDocumenter](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write documentation comment easier, for both Objective-C and Swift.
    <div align=center>
    <img src="https://camo.githubusercontent.com/58e452b57245cd79c2e59ac7926609be4dffbfd8/68747470733a2f2f7261772e6769746875622e636f6d2f6f6e65766361742f5656446f63756d656e7465722d58636f64652f6d61737465722f7676646f63756d656e7465722d73776966742e676966" width="60%" /> 
    </div>

- [ESJsonFormat-Xcode](https://github.com/EnjoySR/ESJsonFormat-Xcode) - 将JSON格式化输出为模型的属性。

- [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.

- [XAlign](https://github.com/qfish/XAlign) - An amazing Xcode Source Editor extension to align regular code. It can align Xnything in any way you want.
    <div align=center>
    <img src="https://camo.githubusercontent.com/f61bfc31e144ad6a9d7ca26fa19547a3af5da8c6/687474703a2f2f7166692e73682f58416c69676e2f696d616765732f646566696e652e676966" width="40%" /> 
    </div>


## 区块链

*比特币、以太坊、区块链相关内容*

- [go-ethereum](https://github.com/ethereum/go-ethereum)  - 以太坊协议的官方的Go语言实现。
  - [Download Geth](https://geth.ethereum.org/downloads/) - Binary archives are published.

- [web3swift](https://github.com/BANKEX/web3swift) - Elegant Web3js functionality in Swift. Native ABI parsing and smart contract interactions on Ethereum network ([web3.swift-Example](https://github.com/MercuryProtocol/web3.swift-Example) - Example on how to use web3.swift). 
   <div align=center>
   <img src="https://user-images.githubusercontent.com/3356474/34412791-5b58962c-ebf0-11e7-8460-5592b12e6e9d.png" width="50%" />
   </div>

- [web3j](https://github.com/web3j/web3j) - web3j is a lightweight, highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network. 
  <div align=center>
  <img src="https://raw.githubusercontent.com/web3j/web3j/master/docs/source/images/web3j_network.png" width="60%" />
  </div>

- [py-geth](https://github.com/ethereum/py-geth) - Python wrapping for running Go-Ethereum as a subprocess.

- [EthersWallet-ios](https://github.com/ethers-io/EthersWallet-ios) - Ethereum Wallet and Dapp Browser for iOS.

- [breadwallet-ios](https://github.com/voisine/breadwallet-ios) - Bread is the best way to get started with bitcoin. 
    <div align=center>
    <img src="https://github.com/voisine/breadwallet-ios/raw/2.0/images/screenshots.jpg" width="50%" />
    </div>

- [dashwallet](https://github.com/QuantumExplorer/dashwallet) - Dashwallet (breadwallet fork) is a real standalone Dash client. 
  <div align=center>
  <img src="https://github.com/QuantumExplorer/dashwallet/raw/master/images/screenshot2.jpg" width="50%" />
  </div>

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
    <div align=center>
    <img src="https://raw.githubusercontent.com/luhenchang/IMAGE/master/img_bizhan/WeChat3d4501c5ea03165d48b5270ac7944463.png" width="60%" />
    </div>


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

- [canvas](https://github.com/airingursb/canvas) - 《Canvas：Draw on the Web》，[本书GitBook]( https://airingursb.gitbooks.io/canvas/)


## 游戏

### Cocos2d

- [Cocos2d-x](https://github.com/cocos2d/cocos2d-x) - Cocos2d-x is a suite of open-source, cross-platform, game-development tools used by millions of developers all over the world. http://www.cocos2d-x.org.
    <div align=center>
    <img src="https://github.com/cocos2d/cocos2d-x/raw/v3/docs/framework_architecture.jpg" width="60%" />
    </div>

### 棋牌

- [qipai_algorithm](https://github.com/yuanfengyun/qipai_algorithm) - 棋牌的胡牌算法，包括麻将、跑胡子、扑克。实现 lua c++ c# golang js  java  python版本。

- [HuPaiMJ](https://github.com/pinorr/HuPaiMJ) - C++麻将胡牌算法。优点：1.速度快，900万次多赖子胡牌用时500ms左右；2.支持多个赖子；3.查错方便，直接查表就可知道。

### 游戏示例

- [Hardest](https://github.com/ZhongTaoTian/Hardest) - 史上最困难的游戏-By Objective-C。
    <div align=center>
    <img src="https://camo.githubusercontent.com/3b9be0d8b67e009fb492411881a173004f41bdfd/687474703a2f2f7777342e73696e61696d672e636e2f6d773639302f30303638755275316a773166347778393263636a396a3330616a3069706771382e6a7067" width="60%" />
    </div>


## C-plus-plus

- [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.


## Script

### Python

- [SpoofMAC](https://github.com/feross/SpoofMAC) - 💼 Change your MAC address for debugging. [http://feross.org/spoofmac/](http://feross.org/spoofmac/)

- [xlrd](https://github.com/python-excel/xlrd) - Library for developers to extract data from Microsoft Excel (tm) spreadsheet files. [python-excel](http://www.python-excel.org)

- [xlwt](https://github.com/python-excel/xlwt) - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform. [python-excel](http://www.python-excel.org)

- [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - [A Python module for creating Excel XLSX files. ](https://xlsxwriter.readthedocs.io)

- [jdcal](https://github.com/phn/jdcal) - Julian dates, stored as two numbers, from proleptic Gregorian and Julian calendars.

---

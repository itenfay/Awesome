## OpenSource

iOS精选列表，包括Objective-C和Swift项目(A curated list of awesome iOS, including Objective-C and Swift Projects.)。

[![License MIT](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](LICENSE)&nbsp;


## Group

|  ID             |  QRCode                                  | Description                             |
| :-------------: | :--------------------------------------: | :-------------------------------------: |
| 614799921 | ![614799921](https://github.com/chenxing640/OpenSource/raw/master/images/g614799921.jpg)  | Technology communication group for iOS & macOS X |
| 155353383 | ![155353383](https://github.com/chenxing640/OpenSource/raw/master/images/qq155353383.jpg) | Technology communication group for other development language |


## 目录

- [OpenSource](#OpenSource)
- [Group](#Group)
- [iOS](#iOS)
    - [TOP100](#TOP100)
      - [AFNetworking和Alamofire](#AFNetworking和Alamofire)
      - [SDWebImage](#SDWebImage)
      - [ReactiveCocoa和RxSwift](#ReactiveCocoa和RxSwift)
      - [Masonry和SnapKit](#Masonry和SnapKit)
      - [YYKit](#YYKit)
      - [Moya](#Moya)
      - [Kingfisher](#Kingfisher)
      - [Charts](#Charts)
      - [Messages](#Messages)
      - [EmptyDataSet](#EmptyDataSet)
      - [JSON](#JSON)
      - [KeyboardManager](#KeyboardManager)
      - [SVG](#SVG)
      - [PhotoPicker](#PhotoPicker)
      - [Deeplink](#Deeplink)
      - [SwiftKit](#SwiftKit)
      - [Hero](#Hero)
      - [SegmentPageView](#SegmentPageView)
      - [CycleScrollView](#CycleScrollView)
      - [Code Quality](#Code-Quality)
      - [Permission](#Permission)
      - [Socket](#Socket)
      - [R.swift](#Rswift)
      - [AnimatedTabBar](#AnimatedTabBar)
      - [AcknowList](#AcknowList)
      - [FloatingPanel](#FloatingPanel)
      - [HTTPCache](#HTTPCache)
      - [ListView](#ListView)
      - [Date](#Date)
      - [Reachability](#Reachability)
      - [CocoaLumberjack](#CocoaLumberjack)
      - [AR和VR](#AR和VR)
   - [支付](#支付)
      - [内购IAP](#内购IAP)
      - [ApplePay](#ApplePay)
      - [第三方支付](#第三方支付)
   - [播放器](#播放器)
      - [视频播放器](#视频播放器) 
      - [音乐播放器](#音乐播放器)
   - [IM和直播](#IM和直播)
   - [图像处理和绘制](#图像处理和绘制)
      - [OpenGL和OpenGLES](#OpenGL和OpenGLES)
      - [Metal](#Metal)
      - [GPUImage](#GPUImage)
      - [CoreGraphics](#CoreGraphics)
   - [逆向开发](#逆向开发)
      - [fishhook](#fishhook)
      - [逆向辅助工具](#逆向辅助工具)
      - [逆向案例](#逆向案例)
   - [安全攻防和应用加固](#安全攻防和应用加固)
   - [数据安全和算法](#数据安全和算法)
   - [区块链](#区块链)
   - [网络相关](#网络相关)
   - [导航栏和状态栏](#导航栏和状态栏)
   - [Runtime](#Runtime)
   - [Data Persistence](#Data-Persistence)
   - [Side Menu](#Side-Menu)
   - [蓝牙](#蓝牙)
   - [手势指纹面容ID密码解锁](#手势指纹面容ID密码解锁)
   - [布局](#布局)
   - [图像模糊化](#图像模糊化)
   - [图片浏览器](#图片浏览器)
   - [扫码](#扫码)
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
   - [StarView](#StarView)
   - [类目](#类目)
   - [越狱检测](#越狱检测)
   - [Sensor](#Sensor)
   - [Uncategorized](#Uncategorized)
   - [高仿项目与Demo](#高仿项目与Demo)
- [Mac](#Mac)


## Others Development

- [Apple Developer](#Apple-Developer)
- [Flutter](#Flutter)
- [Weex](#Weex)
- [H5](#H5)
- [MiniProgram](#MiniProgram)
- [Games](#Games)
- [C++](#Cplusplus)
- [Scripts](#Scripts)
- [Database](#DB)
- [Blockchain](#Blockchain)
- [Others](#Others)


## iOS

### TOP100

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

- [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & OS X ([http://snapkit.io](http://snapkit.io)).
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

#### Moya

- [Moya](https://github.com/Moya/Moya) - Network abstraction layer written in Swift. 
    <div align=center>
    <img src="https://github.com/Moya/Moya/raw/master/web/logo_github.png" width="30%" />
    </div>

#### Kingfisher

- [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight, pure-Swift library for downloading and caching images from the web.
    <div align=center>
    <img src="https://raw.githubusercontent.com/onevcat/Kingfisher/master/images/logo.png" width="50%" />
    </div>
    
#### Charts

- [Charts](https://github.com/danielgindi/Charts) - Beautiful charts for iOS/tvOS/OSX! The Apple side of the crossplatform MPAndroidChart.

#### Messages

- [SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS written in Swift.

#### EmptyDataSet

- [DZNEmptyDataSet](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display.

- [EmptyDataSet-Swift](https://github.com/Xiaoye220/EmptyDataSet-Swift) - DZNEmptyDataSet implement with Swift.A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display. DZNEmptyDataSet with Swift.

#### JSON

- [HandyJSON](https://github.com/alibaba/HandyJSON) - A handy swift json-object serialization/deserialization library.

- [ObjectMapper](https://github.com/tristanhimmelman/ObjectMapper) - Simple JSON Object mapping written in Swift.

- [Moya-ObjectMapper](https://github.com/alibaba/Moya-ObjectMapper) - ObjectMapper bindings for Moya and RxSwift.

#### KeyboardManager

- [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView. Neither need to write any code nor any setup required and much more.
    <div align=center>
    <img src="https://raw.githubusercontent.com/hackiftekhar/IQKeyboardManager/master/Demo/Resources/icon.png" width="30%" />
    </div>

- [IQKeyboardManagerSwift](https://github.com/acegg/IQKeyboardManagerSwift) - IQKeyboardManager 's Swift Module.

#### SVG

- [SVGAPlayer-iOS](https://github.com/svga/SVGAPlayer-iOS) - Similar to Lottie. Render After Effects / Animate CC (Flash) animations natively on Android and iOS, Web. 使用 SVGAPlayer 在 Android、iOS、Web中播放 After Effects / Animate CC (Flash) 动画。【[svga.io](https://svga.io/)】

- [SVGKit](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / OS X, using native rendering (CoreAnimation).

#### PhotoPicker

- [HXPHPicker](https://github.com/SilenceLove/HXPHPicker) - Photo/Video Selector-Supports LivePhoto, GIF selection, online download of resources on iCloud, and editing of photos/videos.
    <div align=center>
    <img src="https://camo.githubusercontent.com/475f8b33413bf52e66e133447845477e5915c7566aa3a26423dea92682c7a4a9/687474703a2f2f74736e72686170702e6f73732d636e2d68616e677a686f752e616c6979756e63732e636f6d2f63686172746c652f687870687069636b6572707265766965772e706e67" width="50%" />
    </div>

- [HXPhotoPicker](https://github.com/SilenceLove/HXPhotoPicker) - 图片/视频选择器 - 支持LivePhoto、GIF图片选择、3DTouch预览、在线下载iCloud上的资源、编辑图片/视频、浏览网络图片 功能 Imitation wx photo/image picker - support for LivePhoto, GIF image selection, 3DTouch preview, Download the resources on iCloud online, browse the web image function.
    <div align=center>
    <img src="https://camo.githubusercontent.com/cb83c5169e00c04ee716035909869de54116899d0c4b4325361920cb11d8a4a2/687474703a2f2f74736e72686170702e6f73732d636e2d68616e677a686f752e616c6979756e63732e636f6d2f63686172746c652f73686f775f7469705f322e706e67" width="30%" />
    </div>
    
- [TZImagePickerController](https://github.com/banchichen/TZImagePickerController) - 一个支持多选、选原图和视频的图片选择器，同时有预览、裁剪功能，支持iOS6+。 A clone of UIImagePickerController, support picking multiple photos、original photo、video, also allow preview photo and video, support iOS6+.

- [PhotoBrowser](https://github.com/JiongXing/PhotoBrowser) - Elegant photo browser in Swift. 图片与视频浏览器。

- [ZYImagePickerAndBrower](https://github.com/RainManGO/ZYImagePickerAndBrower) - 2018iOS微信相册，朋友圈imagePicker UI仿，微信照片选择器 多选序号

#### Deeplink

- [URLNavigator](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift

- [DeepLinkKit](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links.
    <div align=center>
    <img src="https://cloud.githubusercontent.com/assets/10621371/7642874/8c90f72a-fa62-11e4-9092-dfff96c24f01.png" width="50%" />
    </div>
    
- [Appz](https://github.com/SwiftKitz/Appz) - 📱 Launch external apps, and deeplink, with ease using Swift!

- [Deeplink](https://github.com/TizianoCoroneo/Deeplink) - A library to parse deeplinks and their arguments using String interpolation.

#### SwiftKit

- [CXSwiftKit](https://github.com/chenxing640/CXSwiftKit) - CXSwiftKit provides rich extensions of swift language, also supports Objective-C.

- [SwifterSwift](https://github.com/SwifterSwift/SwifterSwift) - A handy collection of more than 500 native Swift extensions to boost your productivity.
    <div align=center>
    <img src="https://camo.githubusercontent.com/284deb34c480c679df9bf0f752ab4872b049411ab99680d06d3e61a077a3a956/68747470733a2f2f63646e2e7261776769742e636f6d2f5377696674657253776966742f5377696674657253776966742f6d61737465722f4173736574732f6c6f676f2e737667" width="50%" />
    </div>
    
#### Hero

- [Hero](https://github.com/HeroTransitions/Hero) - Elegant transition library for iOS & tvOS.
    <div align=center>
    <img src="https://camo.githubusercontent.com/f08f23e762f9ebbeba87366fc3c7e0164c6840a3bc37f1affe25261837f37901/68747470733a2f2f63646e2e7261776769742e636f6d2f6c6b7a68616f2f4865726f2f343237643566322f5265736f75726365732f4865726f2e737667" width="50%" />
    </div>
    
#### SegmentPageView

- [JXSegmentedView](https://github.com/pujiaxin33/JXSegmentedView )- A powerful and easy to use segmented view (segmentedcontrol, pagingview, pagerview, pagecontrol, categoryview)'
    <div align=center>
    <img src="https://github.com/pujiaxin33/JXSegmentedView/raw/master/Example/JXSegmentedViewExample/Image/JXSegmentedViewSmall.png" width="50%" />
    </div>

- [GXSegmentPageView](https://github.com/gsyhei/GXSegmentPageView) - Swift版分段分页组件，（网易新闻、腾讯新闻、新浪微博、今日头条等Tab效果）

- [LTScrollView](https://github.com/gltwy/LTScrollView) - ScrollView嵌套ScrolloView（UITableView 、UICollectionView）解决方案， 支持OC / Swift（持续更新中...）

#### CycleScrollView

- [SDCycleScrollView](https://github.com/gsdios/SDCycleScrollView) - Autoscroll Banner. 无限循环图片、文字轮播器

- [ZCycleView](https://github.com/MQZHot/ZCycleView)- 使用UICollectionView实现常见图片无限轮播，支持自定义cell，自定义pageControl，以及轮播样式

- [WRCycleScrollView](https://github.com/wangrui460/WRCycleScrollView) - Swift 自动无限轮播用
    <div align=center>
    <img src="https://github.com/wangrui460/WRCycleScrollView/raw/master/screenshots/WRCycleScrollView.png" width="50%" />
    </div>
    
#### Code Quality

- [FLEX](https://github.com/FLEXTool/FLEX) - An in-app debugging and exploration tool for iOS.

- [BonMot](https://github.com/Rightpoint/BonMot) - Beautiful, easy attributed strings in Swift.

#### Permission

- [PermissionsKit](https://github.com/sparrowcode/PermissionsKit) - Universal API for request permission and get its statuses.

- [Permission](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS.

- [BAPrivacyManager](https://github.com/boai/BAPrivacyManager) - iOS 所有隐私权限封装，定位、蓝牙、通知、运动、日历、相册、相机等 14 种权限封装！
    <div align=center>
    <img src="https://github.com/BAHome/BAPrivacyManager/raw/master/Images/BAPrivacyManager1.png" width="20%" />
    </div>

#### Socket

- [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS.

- [SocketRocket](https://github.com/facebookincubator/SocketRocket) - A conforming Objective-C WebSocket client library.

- [SocketIO](https://github.com/socketio/socket.io-client-swift) - Socket.IO-client for iOS/OS X.

- [Starscream](https://github.com/daltoniam/Starscream) - Websockets in swift for iOS and OSX

- [SwiftWebSocket](https://github.com/tidwall/SwiftWebSocket) - Fast Websockets in Swift for iOS and OSX.

#### Rswift

- [R.swift](https://github.com/mac-cain13/R.swift) - Strong typed, autocompleted resources like images, fonts and segues in Swift projects.

#### AnimatedTabBar

- [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a Swift UI module library for adding animation to iOS tabbar items and icons. iOS library made by @Ramotion

#### AcknowList

- [AcknowList](https://github.com/vtourraine/AcknowList) - Acknowledgements screen displaying a list of licenses, for example from CocoaPods and Swift Package Manager dependencies.

#### FloatingPanel

- [FloatingPanel](https://github.com/scenee/FloatingPanel) - A clean and easy-to-use floating panel UI component for iOS.

- [OverlayController](https://github.com/snail-z/OverlayController) - OverlayController easily pop your custom view and provide optional transition animation. written in swift 5.0.
    <div align=center>
    <img src="https://github.com/snail-z/OverlayController/raw/master/Preview/ovclogo.jpg?raw=true" width="50%" />
    </div>

#### HTTPCache

- [KTVHTTPCache](https://github.com/ChangbaDevs/KTVHTTPCache) - A powerful media cache framework.

#### ListView

- [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating.【[Preview](https://cloud.githubusercontent.com/assets/219689/7244961/4209de32-e816-11e4-87bc-b161c442d348.png)】

- [ZJTableViewManager](https://github.com/jzhang0480/ZJTableViewManager) - Powerful data driven tableView，make tableView build so easy.

- [TagListView](https://github.com/ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view, in Swift.

- [ParallaxHeader](https://github.com/romansorochak/ParallaxHeader) - Simple way to add parallax header to UIScrollView/UITableView written in Swift.

#### Localize

- [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - Swift friendly localization and i18n with in-app language switching.

#### Date

- [SwiftDate](https://github.com/malcommac/SwiftDate) - Toolkit to parse, validate, manipulate, compare and display dates, time & timezones in Swift.

#### Reachability

- [Reachability](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures.

#### CocoaLumberjack

- [CocoaLumberjack](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS.

#### AR和VR

- [Lee-VR-Source](https://github.com/GeekLiB/Lee-VR-Source) - VR developers necessary resources(VR 开发者必备资源汇总).

- [ARVideoKit](https://github.com/AFathi/ARVideoKit) - Capture & record ARKit videos 📹, photos 🌄, Live Photos 🎇, and GIFs 🎆.

- [viro](https://github.com/viromedia/viro) - ViroReact: AR and VR using React Native.

- [ARCoreInsideOutTrackingGearVr](https://github.com/ChristophGeske/ARCoreInsideOutTrackingGearVr) - Inside Out Positional Tracking (6DoF) for GearVR/Cardboard/Daydream using ARCore v1.6.0.

- [arcore-unity-sdk](https://github.com/google-ar/arcore-unity-sdk) - ARCore SDK for Unity.

- [HeavenMemoirs](https://github.com/SherlockQi/HeavenMemoirs) - AR相册 Photo Album For AR.

- [ARKit-Emperor](https://github.com/kboy-silvergym/ARKit-Emperor) - Power! Unlimited power for ARKit 2.0!

- [ARKit-Cardboard-VR](https://github.com/andrewnakas/ARKit-Cardboard-VR) - ARkit + GVR to make VR and Mixed Reality 6dof AR for iphone.


### 支付

#### 内购IAP

- [DYFStore-Swift](https://github.com/chenxing640/DYFStore) - A lightweight and easy-to-use iOS library for In-App Purchases. `DYFStore` uses blocks and notifications to wrap `StoreKit`, provides receipt verification and transaction persistence and doesn't require any external dependencies. ( [DYFStoreKit](https://github.com/chenxing640/DYFStoreKit) (Objective-C) )

- [RMStore](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases.

- [MKStoreKit](https://github.com/MugunthKumar/MKStoreKit) - The "Goto" In App Purchases Framework for iOS 8+.

- [IAPHelper](https://github.com/saturngod/IAPHelper) - IAP helper for Apple in app purchases. It uses ARC and blocks for ease of use. Ready to use with newsstand subscriptions. No more maintenance for this repo. Please use the [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)

- [SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit) - SwiftyStoreKit is a lightweight In App Purchases framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+. 【 [Priview 1](https://github.com/bizz84/SwiftyStoreKit/raw/master/Screenshots/Preview.jpg) 】

- [OfferingCompletingAndRestoringInAppPurchases.zip](https://docs-assets.developer.apple.com/published/cc0d0e0844/OfferingCompletingAndRestoringInAppPurchases.zip) - Offering completing and restoring In-App Purchases.

- [Receipt Validation Programming Guide](https://developer.apple.com/library/archive/releasenotes/General/ValidateAppStoreReceipt/Introduction.html#//apple_ref/doc/uid/TP40010573-CH105-SW1)

- [DYFStoreReceiptVerifier_Swift](https://github.com/chenxing640/DYFStoreReceiptVerifier_Swift) - This class is developed in Swift language, which is used to verify App Store receipts.

- [DYFStoreReceiptVerifier](https://github.com/chenxing640/DYFStoreReceiptVerifier_Swift) - This class is developed in Objective-C language, which is used to verify App Store receipts.

- [VerifyStoreReceiptiOS](https://github.com/rmaddy/VerifyStoreReceiptiOS) - A helper class for verifying App Store receipts under iOS.

#### ApplePay

- [YasinZhou - ApplePayDemo](https://github.com/YasinZhou/ApplePayDemo) - ApplePay苹果支付demo。

- [lintide - ApplePayDemo](https://github.com/lintide/ApplePayDemo) -  Apple Pay demo 苹果支付示例。

- [ApplePayExample](https://github.com/jflinter/ApplePayExample) -  ApplePay Example.

- [iTofu - ApplePayDemo](https://github.com/iTofu/ApplePayDemo) -   Pay Demo with Swift. 

#### 第三方支付

- [XHPayKit](https://github.com/CoderZhuXH/XHPayKit) - 不用官方SDK实现微信支付、支付宝支付。

- [PayDemo](https://github.com/codewpf/PayDemo) - 支付宝和微信支付两种方式集成。

- [App支付 - [支付宝开放平台](https://open.alipay.com/platform/home.htm)](https://opendocs.alipay.com/open/54/104509/) - APP支付适用于商家在 App 应用中集成支付宝支付功能。商家APP调用支付宝提供的 SDK，SDK 再调用支付宝APP内的支付模块。如果用户已安装支付宝 APP，商家 APP 会跳转到支付宝中完成支付，支付完后跳回到商家APP内，最后展示支付结果。如果用户没有安装支付宝 APP，商家 APP 内会调起支付宝网页支付收银台，用户登录支付宝账户，支付完后展示支付结果。目前支持手机系统有：iOS（苹果）、Android（安卓）。

- [APP支付 - [微信支付商户平台](https://pay.weixin.qq.com/index.php/core/home/login?return_url=%2F)](https://pay.weixin.qq.com/wiki/doc/api/app/app.php?chapter=8_1) - APP支付是指商户通过在移动端应用APP中集成开放SDK调起微信支付模块来完成支付。适用于在移动端APP中集成微信支付功能的场景。


### 播放器

#### 视频播放器

- [ijkplayer](https://github.com/bilibili/ijkplayer) - Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support ([FFmpeg](http://ffmpeg.org)).

- [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Support customization of any player SDK and control layer (支持定制任何播放器SDK和控制层)。【 [Priview 1](https://camo.githubusercontent.com/48200df0498350786ba386f31336f7e6c8f07552/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3633353934322d303932343237653537313735363330392e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) | [Priview 2](https://camo.githubusercontent.com/dbee14e8706d7d044c9951be77097aeb2115f5e9/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3633353934322d653939643736343938636230316166622e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) | [Priview 3](https://camo.githubusercontent.com/af4de47d93b0b02197464c9118b0081ea51cf59c/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3633353934322d316230653233623766356561626439652e6a70673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) 】

- [CLPlayer](https://github.com/JmoVxia/CLPlayer) - 自定义支持全屏的播放器。【 [Priview 1](https://github.com/JmoVxia/CLPlayer/raw/master/效果图.gif) 】

- [QPlayer](https://github.com/chenxing640/QPlayer) - A powerful video player that you can't miss, supports m4v, wmv, 3gp, mp4, mov, avi, mkv, mpeg, mpg, flv, rm, rmvb, mp3 format. Enter any HTTP, RTSP, RTMP, HLS address play network streaming or live. QPlayer use ffmpeg，you can transfer files via wifi. It aggregates several live, video and short video platforms, and you can watch live, video and short video online. 【 [Priview 1](https://github.com/chenxing640/QPlayer/raw/master/images/web_video.png) | [Priview 2](https://github.com/chenxing640/QPlayer/raw/master/images/mainstream_live.png) | [Priview 3](https://github.com/chenxing640/QPlayer/raw/master/images/tv_radio.png) | [Priview 4](https://github.com/chenxing640/QPlayer/raw/master/images/local_video.png) 】

- [BMPlayer](https://github.com/BrikerMan/BMPlayer) - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brightness and seek by slide, support subtitles. 【 [Priview 1](https://github.com/BrikerMan/resources/raw/master/BMPlayer/demo.gif) 】

- [SJVideoPlayer](https://github.com/changsanjiang/SJVideoPlayer) - Video Player. Support cocoapods & Generate GIF & Export & Localization & Play in View(UIView || TableHeader || TableCell || CollectionCell) & Keyboard Orientation & StatusBar(Style&Hide). 【 [Priview 1](https://user-images.githubusercontent.com/37614260/43947531-922a0712-9cb2-11e8-8f8d-4823a21308d3.png) 】

- [kxmovie](https://github.com/kolyvan/kxmovie) - movie player for iOS using ffmpeg. 【 [Priview 1](https://camo.githubusercontent.com/ce6bc94079ae115bf2f9959020e427511f689742/68747470733a2f2f7261772e6769746875622e636f6d2f6174656c69657264756d6f62696c652f46466d706567506c617965722d694f532f6d61737465722f726561646d652d6d656469612f73637265656e73686f742d6d6f7669652d6c616e6473636170652e706e67) 】

- [ffmpeg-avplayer-for-ios-tvos](https://github.com/imoreapps/ffmpeg-avplayer-for-ios-tvos) - A tiny but powerful iOS and Apple TV OS av player framework that's based on the FFmpeg library. 

- [Eleven](https://github.com/kaixinsoft/Eleven) - Eleven Player is a simple powerful video player.use ffmpeg.
  - [iOS配置FFmpeg框架](http://cnbin.github.io/blog/2015/05/19/iospei-zhi-ffmpegkuang-jia/) 
  - [Vitamio测试网络视频地址](https://www.vitamio.org/docs/Basic/2013/0508/14.html) 
    
- [SBPlayer](https://github.com/henusjj/SBPlayer) - 基于AVPlayer封装的轻量级播放器，可以播放本地网络视频，易于定制，可以横屏竖屏，支持M3u8、mp4等格式视频本地播放或者网络播放，通过masonry约束，适配各种尺寸iPhone。【 [Priview 1](https://github.com/henusjj/SBPlayer/raw/master/Images/2.gif) 】

- [VKVideoPlayer](https://github.com/viki-org/VKVideoPlayer) - he same battle tested video player used in our [Viki iOS App](https://itunes.apple.com/app/id445553058?mt=8) enjoyed by millions of users all around the world. 

- [KRVideoPlayer](https://github.com/36Kr-Mobile/KRVideoPlayer) - 类似Weico的播放器，支持竖屏模式下全屏播放。【 [Priview 1](https://github.com/36Kr-Mobile/KRVideoPlayer/raw/master/kr_player.gif) 】

- [PBJVideoPlayer](https://github.com/piemonte/PBJVideoPlayer) - ▶️ video player, simple way to play and stream media on iOS/tvOS.

- [vlc-ios](https://github.com/videolan/vlc-ios) - VLC for iOS and tvOS official mirror.

- [vlckit](https://github.com/videolan/vlckit) - VLCKit is a generic multimedia library for any audio or video playback needs on macOS, iOS and tvOS.

- [MRVLCPlayer](https://github.com/Maru-zhang/MRVLCPlayer) - 一款基于VLC的播放器,支持常用的各大手势功能，支持几乎所有主流格式。

- [LMIJKPlayer](https://github.com/lixiaonan/LMIJKPlayer) - 基于IJKPlayer，支持横屏、竖屏，上下滑动调节音量、屏幕亮度，左右滑动调节播放进度, 支持横竖屏UI不同的完整播放器Demo。

- [LMAVPlayer](https://github.com/lixiaonan/LMAVPlayer) - 基于苹果原生AVPlayer，支持横屏、竖屏，上下滑动调节音量、屏幕亮度，左右滑动调节播放进度, 支持横竖屏UI不同的完整播放器Demo.

- [Eleven](https://github.com/sinabio/Eleven) - a simple powerful video player. Support m4v, wmv, 3gp, mp4, mov, avi, mkv, mpeg, mpg, flv, vob format.Enter any HTTP, RTSP, RTMP, RTP address play network streaming or live.Eleven player use ffmpeg.

- [KSYMediaPlayer_iOS](https://github.com/ksvc/KSYMediaPlayer_iOS) - 金山云iOS播放SDK（KSYUN Live Streaming player SDK），支持RTMP HTTP-FLV HLS 协议（supporting RTMP HTTP-FLV HLS protocol），直播延时2-3秒（Living delay 2 or 3 seconds） 。与系统播放器MPMoviePlayerController接口一致，可以无缝快速切换至KSYMediaPlayer；本地全媒体格式支持, 并对主流的媒体格式(mp4, avi, wmv, flv, mkv, mov, rmvb 等 )进行优化；支持广泛的流式视频格式, HLS, RTMP, HTTP Rseudo-Streaming 等；低延时直播体验，配合金山云推流sdk，可以达到全程直播稳定的4秒内延时；实现快速满屏播放，为用户带来更快捷优质的播放体验；支持画面旋转，音量调节等各种功能；

- [MRDLNA](https://github.com/MQL9011/MRDLNA) - 纯OC实现的iOS DLNA 投屏功能, 支持各大主流电视盒子(小米,华为,乐视,移动魔百盒等), 可以播放,暂停,快进退,调音量,退出.

- [DLNA](https://github.com/FuruyamaTakeshi/DLNA) - DLNA sample code using CyberLink Objective-C Wrapper. This sample can browse contents from DMS and play content at DMR. 

- [DLNA_iOS_Platinum](https://github.com/wangshuaidavid/DLNA_iOS_Platinum) - DLNA server on iOS using Platinum. This APP is an implementation of a DLNA media server powered by Platinum libs. It can publish the media files in iTunes and Photo Album to any DLNA player which is in the same network enviroment.

- [ALMoviePlayerController](https://github.com/lobianco/ALMoviePlayerController) -  A drop-in replacement for MPMoviePlayerController that exposes the UI elements and allows for maximum customization. 【 [Priview 1](https://camo.githubusercontent.com/30ca7db1413516773bb464f2a1fe1e1a3ff2d387/687474703a2f2f6c6f6269616e636f2e6769746875622e696f2f414c4d6f766965506c61796572436f6e74726f6c6c65722f73637265656e73686f74732f73637265656e73686f74322e706e67) 】

#### 音乐播放器

- [StreamingKit](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS (iPhone, iPad).

- [LyricsAnalysis](https://github.com/wsl2ls/LyricsAnalysis) - iOS音乐播放器之锁屏效果（仿网易云音乐和QQ音乐）+ 歌词解析 ：锁屏歌曲信息、控制台远程控制音乐播放：暂停/播放、上一首/下一首、快进/快退、列表菜单弹框和拖拽控制台的进度条调节进度（结合了QQ音乐和网易云音乐在锁屏状态下的效果）、歌词解析并随音乐滚动显示。【 [Priview 1](https://camo.githubusercontent.com/a7f8d7a5c4d556835a74a48e47287699879ce9c0/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d613833663765343062303165346635302e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) | [Priview 2](https://camo.githubusercontent.com/3fc34b6daa5822c88ddec99295f2dc33b376b67b/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d373265306262333661633033353330302e504e473f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) 】

- [GKWYMusic](https://github.com/QuintGao/GKWYMusic) - iOS基于FreeStreamer的仿网易云音乐播放器。【 [Priview 1](https://github.com/QuintGao/GKWYMusic/raw/master/list_play.gif) | [Priview 2](https://github.com/QuintGao/GKWYMusic/raw/master/album.gif) 】

- [ios-audio-remote-control](https://github.com/MosheBerman/ios-audio-remote-control) - This repo demonstrates how to control the software based audio remote control in iOS.

- [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote).


### IM和直播

- [AtChat](https://github.com/boyssimple/AtChat) - IOS聊天项目、基于XMPP框架开发，实现了登陆注册(注册以手机号码注册、短信验证) 、发送消息、接收消息、接收好友请求、发起好友请求 、图片消息、语音消息、视频语音、聊天历史记录、最近联系人、二维码添加好友、用户头像上传、朋友圈、发朋友圈、异地登录退出等功能。【 [Priview 1](https://github.com/boyssimple/AtChat/raw/master/images/020.png) | [Priview 2](https://github.com/boyssimple/AtChat/raw/master/images/014.png) 】

- [BAWeChat](https://github.com/BAHome/BAWeChat) - 博爱微信，使用原生 frame + MVVM + MVC + QMUIKit + BAKit 开源的微信。【 [Priview 1](https://github.com/boai/BAWeChat/raw/master/Images/通讯录.png) | [Priview 2](https://github.com/boai/BAWeChat/raw/master/Images/评论.png) 】

- [MomentKit](https://github.com/ChellyLau/MomentKit) - MVC模式实现WeChat朋友圈功能，代码整洁易读。支持富文本(链接/表情/电话/邮箱等)、点赞、评论/回复评论、图片预览、文字拷贝等功能。【 [Priview 1](https://github.com/ChellyLau/MomentKit/raw/master/Screenshot/screenshot_2.png) | [Priview 2](https://github.com/ChellyLau/MomentKit/raw/master/Screenshot/screenshot_4.png) 】

- [ABigFishTV](https://github.com/clyhs/ABigFishTV) - 大鱼电视直播 基于ijkplayer的播放器 700多个电视台 包括央视，各地方台，卫视，熊猫直播，社会化分享，登陆，仿微博等 (支持iphonex)。【 [Priview 1](https://github.com/clyhs/ABigFishTV/raw/master/images/ABigFishTV.gif) 】

- [TGTV](https://github.com/targetcloud/TGTV) - TGTV直播APP用Swift3.1编写，采用MVVM架构，本demo运用protobuf实现即时聊天（弹幕）、礼物动画等。【 [Priview 1](https://github.com/targetcloud/TGTV/raw/master/1.gif) | [Priview 2](https://github.com/targetcloud/TGTV/raw/master/屏幕快照%202017-04-13%20下午5.22.09.png) 】

- [MGMiaoBo](https://github.com/LYM-mg/MGMiaoBo) - 首创房间内多视频直播模式，移动直播新体验，多人秀场更好玩。随时随地与主播聊天互动亲密接触，清纯美女、校花嫩模、吃货萌妹、通通都有…… 1.项目引导页业使用ijkPlayer播放视频；2.首页使用父子控制器进行界面之间的切换；3.自定义MJRefresh刷新控件，替换头部刷新gif图片；4.使用分类理由贝塞尔曲线为UIImageView添加圆角；5.服务器交互使用的是https，用json格式，面向模型开发;其他：全局网络请求封装，页面数据缓存处理，通知，动画，基础控制器封装，使用xib的AutoLayout和Masonry第三方库等。【 [Priview 1](https://camo.githubusercontent.com/75db51c6486a07e0817d8a1b498740620ecb0f1f/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d396361383335623732613562303533612e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) | [Priview 2](https://camo.githubusercontent.com/1807bcb191968c41603e13ccc9639adbdf6f1f27/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d393064646435626566333361313539352e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) 】

- [MGDYZB](https://github.com/LYM-mg/MGDYZB) - Xcode8以上版本，已升级为Swift3.x语法。斗鱼-每个人的直播平台提供高清、快捷、流畅的视频直播和游戏赛事直播服务，包含英雄联盟lol直播、穿越火线cf直播、dota2直播、美女直播等各类热门游戏赛事直播等。【 [Priview 1](https://camo.githubusercontent.com/0b93ec631006cb13a26ae52771763f5ffb869534/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d666262356535623431326334343363662e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) | [Priview 2](https://camo.githubusercontent.com/a7e7ead1a95fd7fc9c3f6445f49ecb08ef26ed1f/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d366437326262323634303831353932642e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) 】

- [LFLiveKit](https://github.com/LaiFengiOS/LFLiveKit) -  LaiFeng IOS Live Kit,H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate.

- [LXPlayerLive](https://github.com/SoftProgramLX/LXPlayerLive) - 一步步搭建视频直播系统，基于LFLiveKit＋ijkplayer＋rtmp（iOS端）。

- [inke-demo](https://github.com/shawn-tangsc/inke-demo) - 仿映客直播app（最新）原版礼物列表,直播弹幕，最新热门页面，原版动画登陆页，实现了oc项目使用Socket.IO-Client-Swift 绑定后台node服务器实现实时聊天功能。

- [WZHLiveShow](https://github.com/wzhios/WZHLiveShow) - IOS视频直播 + 推流实现 采用当前主流开源框架B站的ijkplayer 以及优酷土豆旗下的LFLiveKit实现推流。

- [ATijkplayeriOS](https://github.com/allentsing/ATijkplayeriOS) - 1、编译ijkPlayer，支持RTSP拉流播放，支持http等格式。2、加入了MD360Player4iOS，实现视频的全景渲染。3、MovieRecorder用实时拉过来的音视频数据进行录视频。4、LFLiveKit用拉流过来的原始音视频数据(YUV、PCM)进行推流直播。

- [LFLiveKit_Record_Recode](https://github.com/jiangzhibin/LFLiveKit_Record_Recod) - 因为个人项目需要，对边推边录可定制性要求较高，LFLiveKit录制功能可定制性较低，此项目重构了其录制接口，方便项目需要。

- [LiveVideoCoreSDK](https://github.com/runner365/LiveVideoCoreSDK) - LiveVideoCoreSDK是基于IOS的视频直播SDK(支持IOS8.1以上,基于开源videocore进行了改进)，多滤镜IOS推流SDK: 基于GPUImage的多滤镜拍摄, 滤镜资源丰富. GPUImageRtmpPush。

- [PLPlayerKit](https://github.com/pili-engineering/PLPlayerKit) - PLPlayerKit 是七牛推出的一款免费的适用于 iOS 平台的播放器SDK，采用全自研的跨平台播放内核，拥有丰富的功能和优异的性能，可高度定制化和二次开发。([ios-playback-end-the-sdk](https://developer.qiniu.com/pili/sdk/1211/ios-playback-end-the-sdk))

- [PLMediaStreamingKit](https://github.com/pili-engineering/PLMediaStreamingKit) - PLMediaStreamingKit 是七牛推出的一款适用于 iOS 平台的推流 SDK，支持 RTMP 推流，h.264 和 AAC 编码，硬编、软编支持。具有丰富的数据和状态回调，方便用户根据自己的业务定制化开发。具有直播场景下的重要功能，如：美颜、背景音乐、水印等功能。

- [MessageKit](https://github.com/MessageKit/MessageKit) - A community-driven replacement for JSQMessagesViewController.


### 图像处理和绘制

#### OpenGL和OpenGLES

- [goosers·OpenGL](https://github.com/goosers/cube/wiki/OpenGL)

- [Apple OpenGLES Programming Guide](https://developer.apple.com/library/archive/documentation/3DDrawing/Conceptual/OpenGLES_ProgrammingGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008793-CH1-SW1)

- [kesalin·OpenGLES](https://github.com/kesalin/OpenGLES)

- [uwuneng·OpenGLES](https://github.com/uwuneng/OpenGLES)

- [XanderXu·OpenGLESExamples](https://github.com/XanderXu/OpenGLESExamples)

#### Metal

- [Apple Metal](https://developer.apple.com/metal/) 

- [Apple Metal Sample-code](https://developer.apple.com/metal/sample-code/) 

#### GPUImage

- [GPUImage](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing. [http://www.sunsetlakesoftware.com/2012/02/12/introducing-gpuimage-framework](http://www.sunsetlakesoftware.com/2012/02/12/introducing-gpuimage-framework)【 [Priview 1](https://camo.githubusercontent.com/68ce8767f20b6a40f2a695c56396d30234363431/687474703a2f2f73756e7365746c616b65736f6674776172652e636f6d2f73697465732f64656661756c742f66696c65732f475055496d6167654c6f676f2e706e67) 】

- [GPUImage2](https://github.com/BradLarson/GPUImage2) - A BSD-licensed Swift framework for GPU-accelerated video and image processing.

- [GPUImage3](https://github.com/BradLarson/GPUImage3) - A BSD-licensed Swift framework for GPU-accelerated video and image processing using Metal.

#### CoreGraphics

- [Graphs](https://github.com/candy7/Graphs) - 通过bezierPath，画出曲线图，并且加入动画。【 [Priview 1](https://camo.githubusercontent.com/955dab2a5598a7dcb509b3c448b12a37a1760570/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f323035353836362d333233653639333130323262353461662e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】

- [LXBezierPath](https://github.com/LXManMan/LXBezierPath) - 进度条绘制。【 [Priview 1](https://github.com/liuxinixn/LXBezierPath/raw/master/gif.gif) 】


### 逆向开发

#### fishhook

- [fishhook](https://github.com/facebook/fishhook) - A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS. 
    <div align=center>
    <img src="https://camo.githubusercontent.com/18243516844d12b1bd158ce3687635d6e48d2e2e/687474703a2f2f692e696d6775722e636f6d2f4856587148437a2e706e67" width="50%" />
    </div>

#### 逆向辅助工具

- [iOSOpenDev](http://iosopendev.com) - [Github](https://github.com/kokoabim/iOSOpenDev)
- [theos](http://iphonedevwiki.net/index.php/Theos/Setup) - 一个越狱开发工具包 ([Github](https://github.com/theos/theos))
- [class-dump](https://github.com/nygard/class-dump) - Generate Objective-C headers from Mach-O files. 
- [Clutch](https://github.com/KJCracks/Clutch) - a high-speed iOS decryption tool. It supports the iPhone, iPod Touch, and iPad.
- [optool](https://github.com/alexzielenski/optool) - Command Line Tool for interacting with MachO binaries on OSX/iOS.
- [Hook-Tools](https://github.com/chenxing640/WeChat_tweak/tree/master/Hook-Tools)
- [HackAppTool](https://github.com/jackrex/FakeWeChatLoc/tree/master/HackAppTool) 
- [Tools](https://github.com/east520/AutoGetRedEnv/tree/master/Tools)

#### 逆向案例

- [WeChat_tweak](https://github.com/chenxing640/WeChat_tweak) -iOS版功能最全的微信插件，支持最新版微信，具备自动抢红包，屏蔽消息和群消息，过滤特定的群聊，防止撤回消息，伪定位 (朋友圈和附近的人)，修改微信运动步数和实时取景做聊天页的背景等功能。【 [Priview 1](https://github.com/chenxing640/WeChat_tweak/raw/master/images/wcplugin_settings.png) | [Priview 2](https://github.com/chenxing640/WeChat_tweak/raw/master/images/wcplugin_xwtx1.png) | [Priview 3](https://github.com/chenxing640/WeChat_tweak/raw/master/images/wcplugin_xwtx2.png) | [Priview 4](https://github.com/chenxing640/WeChat_tweak/raw/master/images/wcplugin_pbqxx.png) | [Priview 5](https://github.com/chenxing640/WeChat_tweak/raw/master/images/fake_location.png)  | [Priview 6](https://github.com/chenxing640/WeChat_tweak/raw/master/images/prevent_msg_revoc.png) 】

- [WeChatRedEnvelop](https://github.com/buginux/WeChatRedEnvelop) - iOS版微信抢红包Tweak。【 [Priview 1](https://github.com/buginux/WeChatRedEnvelop/raw/master/ScreenShots/Setting.jpeg) | [Priview 2](https://github.com/buginux/WeChatRedEnvelop/raw/master/ScreenShots/AssistantSetting.jpeg) 】
    - [iOS微信抢红包Tweak安装教程](http://www.swiftyper.com/2016/01/25/ios-tweak-install-guide)
    - [免越狱版 iOS 抢红包插件](http://www.swiftyper.com/2016/12/26/wechat-redenvelop-tweak-for-non-jailbroken-iphone)

- [FakeWeChatLoc](https://github.com/jackrex/FakeWeChatLoc) - iOS伪装微信位置。【 [Priview 1](https://raw.githubusercontent.com/jackrex/FakeWeChatLoc/master/pic/1464391571144.png) | [Priview 2](https://raw.githubusercontent.com/jackrex/FakeWeChatLoc/master/pic/1464391684987.png) 】
    - [iOS逆向论坛](http://bbs.iosre.com) 

- [FakeWeChatLocation](https://github.com/PandaraWen/FakeWeChatLocation) - A tweak that can fake location info in WeChat.

- [WeChatRedEnvelopesHelper](https://github.com/luckysine/WeChatRedEnvelopesHelper) - iOS版微信抢红包插件，支持后台抢红包，tweak源文件。【 [Priview 1](https://github.com/luckysine/WeChatRedEnvelopesHelper/raw/master/screenshots/step.png) 】

- [AutoGetRedEnv](https://github.com/east520/AutoGetRedEnv) - 微信自动抢红包。

- [WXAccountSwitcher](https://github.com/iosre/WXAccountSwitcher) - Fast switch WeiXin account.

- [FishChat](https://github.com/yulingtianxia/FishChat) - Hook WeChat.app on non-jailbroken devices. ([blog](http://yulingtianxia.com/blog/2017/02/28/Make-WeChat-Great-Again/)) 【 [Priview 1](https://github.com/yulingtianxia/FishChat/raw/master/Images/logo.png) | [Priview 2](https://github.com/yulingtianxia/FishChat/raw/master/Images/weichat_ignore_chatroom.PNG) | [Priview 3](https://github.com/yulingtianxia/FishChat/raw/master/Images/wechat_setting_keyboard.PNG) 】

- [WeTransparentChat](https://github.com/PandaraWen/WeTransparentChat) - Use back camera capturing make WeChat's message content page's background transparent. 【 [Priview 1](https://github.com/PandaraWen/WeTranslateparentChat/raw/master/images/IMG_0018.PNG) 】


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

- [DYFCryptoUtils](https://github.com/chenxing640/DYFCryptoUtils) - 🔥一行代码实现 iOS Base64, 32/16位MD5, DES, AES, RSA算法，操作简单好用。(Achieves Base64, 32/16 bit MD5, DES, AES and RSA algorithms for iOS with one line of code. The operation is simple and easy to use.)【 [Priview 1](https://github.com/chenxing640/DYFCryptoUtils/raw/master/images/CryptoUtilsPreview.gif) 】

- [AESCipher-iOS](https://github.com/WelkinXie/AESCipher-iOS) - AES encryption working between Objective-C and Java. ([AESCipher-Java](https://github.com/WelkinXie/AESCipher-Java))

- [AESCrypt-ObjC](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.

- [RSADemo](https://github.com/DullDevil/RSADemo) - RSA加解密相关方方法，以及密钥格式的生成与转换。

- [Encryptions](https://github.com/iamlay/Encryptions) - this project is for many kinds odf encryption. 【[Priview 1](https://github.com/Flying-Einstein/Encryptions/raw/master/Encryption/encryption.gif) 】

- [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) - CryptoSwift是在Swift中实现的越来越多的标准和安全密码算法的集合。

- [Security-iOS](https://github.com/cocoajin/Security-iOS) - 封装了一些iOS上使用的NSData分类，主要用于 RSA加密、AES加密、数据签名、签名校验、MD5、SHA1、SHA256 常用hash等工具。

- [CocoaSecurity](https://github.com/kelp404/CocoaSecurity) - Encrypt/Decrypt: AES. Hash: MD5, SHA(SHA1, SHA224, SHA256, SHA384, SHA512). Encode/Decode: Base64, Hex.

- [BBRSACryptor](https://github.com/NianJi/BBRSACryptor) - 使用OpenSSL进行公钥和私钥的加解密。

- [BBRSACryptor-XHAdd](https://github.com/CoderZhuXH/BBRSACryptor-XHAdd) - 1行代码调用RSA公钥、私钥生成、客户端RSA加密、解密、RSA签名、签名验证等。

- [3desDemo](https://github.com/Thomaszhouwu/3desDemo) - 3des Demo.

- [Base64](https://github.com/ekscrypto/Base64) - Objective-C Base64 Additions for NSData and NSString.

- [CryptoCompatibility](https://developer.apple.com/library/mac/samplecode/CryptoCompatibility/Introduction/Intro.html) - CryptoCompatibility shows how to do common cryptographic operations using Apple APIs such that the results match other common cryptographic APIs, most notably OpenSSL.


### 区块链

*比特币、以太坊、区块链相关内容*

- [go-ethereum](https://github.com/ethereum/go-ethereum) - 以太坊协议的官方的Go语言实现。
  - [Download Geth](https://geth.ethereum.org/downloads/) - Binary archives are published.

- [web3swift](https://github.com/zeriontech/Web3Swift) - Elegant Web3js functionality in Swift. Native ABI parsing and smart contract interactions on Ethereum network ([web3.swift-Example](https://github.com/MercuryProtocol/web3.swift-Example) - Example on how to use web3.swift). 
   <div align=center>
   <img src="https://user-images.githubusercontent.com/3356474/34412791-5b58962c-ebf0-11e7-8460-5592b12e6e9d.png" width="50%" />
   </div>

- [web3j](https://github.com/web3j/web3j) - web3j is a lightweight, highly modular, reactive, type safe Java and Android library for working with Smart Contracts and integrating with clients (nodes) on the Ethereum network. 【 [Priview 1](https://github.com/web3j/web3j-docs/blob/master/docs/img/web3j_network.png) 】

- [web3](https://github.com/MercuryProtocol/web3.swift) - Web3 and Geth wrapper utility in swift [www.mercuryprotocol.com](https://www.mercuryprotocol.com/)

- [py-geth](https://github.com/ethereum/py-geth) - Python wrapping for running Go-Ethereum as a subprocess.

- [EthersWallet-ios](https://github.com/ethers-io/EthersWallet-ios) - Ethereum Wallet and Dapp Browser for iOS.

- [breadwallet-ios](https://github.com/voisine/breadwallet-ios) - Bread is the best way to get started with bitcoin. 【 [Priview 1](https://github.com/voisine/breadwallet-ios/raw/2.0/images/screenshots.jpg) 】

- [dashwallet](https://github.com/QuantumExplorer/dashwallet) - Dashwallet (breadwallet fork) is a real standalone Dash client. 【 [Priview 1](https://github.com/QuantumExplorer/dashwallet/raw/master/images/screenshot2.jpg) 】

- [imToken](https://github.com/ywzqhl/imToken) - ETHWallet.

- [ethers.io](https://github.com/ethers-io/ethers.io) - The frontend website HTML, JavaScript and CSS for ethers.io. 

- [ethers.objc](https://github.com/ethers-io/ethers.objc) - Fast, simple and complete library for Ethereum in Objective-C.


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

- [WRNavigationBar](https://github.com/wangrui460/WRNavigationBar) - 超简单！！！ 一行代码设置状态栏、导航栏按钮、标题、颜色、透明度，移动等。【 [Swift版](https://github.com/wangrui460/WRNavigationBar_swift) | [Priview 1](https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/拉钩App首页.gif) | [Priview 2](https://raw.githubusercontent.com/wangrui460/WRNavigationBar_swift/master/screenshots/新浪微博个人中心.gif) | [Priview 3](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/蚂蚁森林.gif) 】

- [NNNavigationBar](https://github.com/amisare/NNNavigationBar) - 实现导航条背景渐变过渡动画的轻量级框架。【 [Priview 1](https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_00.gif) | [Priview 2](https://raw.githubusercontent.com/amisare/Screenshots/master/NNNavigationBar/Screenshots_01.gif) 】

- [RTRootNavigationController](https://github.com/rickytan/RTRootNavigationController) - Implicitly make every view controller has its own navigation bar. 【 [Priview 1](https://user-images.githubusercontent.com/1250207/30429339-abb20914-9989-11e7-9058-c967839315f4.gif) 】

- [GKNavigationController](https://github.com/QuintGao/GKNavigationController) - iOS自定义导航栏-导航条联动（仿网易新闻、网易云音乐等导航栏滑动效果）。【 [Priview 1](https://github.com/QuintGao/GKNavigationController/raw/master/GKNavigationControllerDemo/001.png) 】

- [EasyNavigation](https://github.com/chenliangloveyou/EasyNavigation) - 一款超级简单的导航条管理工具。完全自定义导航条。没有UINavigationBar 和 UINavigationItem 这两个类。完全是对UIView的操作。 所有操作都能一行代码，操作之间完全独立，互不影响。【 [Priview 1](https://github.com/chenliangloveyou/EasyNavigation/raw/master/logo/horizontal-color.png) 】

- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture) - An UINavigationController's category to enable fullscreen pop gesture in an iOS7+ system style with AOP. 【 [Priview 1](https://raw.githubusercontent.com/forkingdog/FDFullscreenPopGesture/master/Snapshots/snapshot0.gif) 】

- [JZNavigationExtension](https://github.com/JazysYu/JZNavigationExtension) - JZNavigationExtension integrates some convenient features for UINavigationController and easy to use. 【 [Priview 1](https://raw.githubusercontent.com/JazysYu/JZNavigationExtension/master/Snapshots/JZNavigationExtensionDemo.gif) 】

- [BBGestureBack](https://github.com/Bonway/BBGestureBack) - OC and Swift full screen return gesture（纯OC 和 纯Swift编写，类淘宝、京东等全屏滑动返回效果）。【[Priview 1](https://camo.githubusercontent.com/de8758c8283c6aa4745044e2a677410880335726/68747470733a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f31303939313737302d656465636265633933643164376538622e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】


### Side Menu

- [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) - A lightweight, easy to use, Side Drawer Navigation Controller. 【 [Priview 1](https://camo.githubusercontent.com/5c4050ef64d7b9836b6a56b89b458ed5c8fdfb7f/687474703a2f2f6d757475616c6d6f62696c652e6769746875622e696f2f4d4d447261776572436f6e74726f6c6c65722f4578616d706c65496d616765732f6578616d706c65322e706e67) 】

- [RESideMenu](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect. 【 [Priview 1](https://raw.githubusercontent.com/romaonthego/RESideMenu/master/Demo.gif?2) 】


### Runtime

- [ObjC runtime opensource](https://opensource.apple.com/source/objc4/) - Source code comes from Apple opensource.

- [DYFSwiftRuntimeProvider](https://github.com/chenxing640/DYFSwiftRuntimeProvider) - Swift Runtime 包装，可快速使用字典转模型、归档解档、添加一个方法、交换两个方法、获取所有属性名和方法名。

- [DYFRuntimeProvider](https://github.com/chenxing640/DYFRuntimeProvider) -  Objective-C Runtime 包装，可快速使用字典转模型、归档解档、添加一个方法、交换两个方法、获取所有属性名和方法名。

- [Runtime Exploration](https://github.com/chenxing640/Runtime-exploration) - Runtime是iOS系统中重要的组成部分，面试也是必问的问题，所以Runtime是一个iOS工程师必须掌握的知识点。

- [探秘 Runtime - Runtime 介绍](https://www.jianshu.com/p/ce97c66027cd)
- [探秘Runtime - 剖析 Runtime 结构体](https://www.jianshu.com/p/5b7e7c8075ef)
- [探秘 Runtime - Runtime 源码分析](https://www.jianshu.com/p/3019605a4fc9)
- [探秘 Runtime - Runtime 加载过程](https://www.jianshu.com/p/4fb2d7014e9e)
- [探秘 Runtime - Runtime 消息发送机制](https://www.jianshu.com/p/014af0de67cd)
- [探秘 Runtime - 深入剖析 Category](https://www.jianshu.com/p/0dc2513e117b)
- [探秘 Runtime - Runtime Message Forward](https://www.jianshu.com/p/f313e8e32946)
- [iOS 黑魔法 - Runtime Method Swizzling](https://www.jianshu.com/p/ff19c04b34d0)
- [探秘 Runtime - Runtime 的应用](https://www.jianshu.com/p/4a22a39b69c5)

- [Objc -- Runtime 简单入门 (代码实例) ](https://blog.csdn.net/demon_jiao/article/details/50961687)

- [iOS源码解析：runtime<一> isa，class底层结构窥探](https://www.jianshu.com/p/bbc33b55d4b7)
- [iOS源码解析：runtime<二> objc_msgSend()消息机制的完整过程](https://www.jianshu.com/p/0653af5d02ae)

- [笔记-runtime源码解析之让你彻底了解底层源码](https://www.jianshu.com/p/52782535d38e)

- [从 ObjC Runtime 源码分析一个对象创建的过程](https://www.jianshu.com/p/8e4887a43bd7)

- [探秘Runtime - Runtime源码分析](https://www.jianshu.com/p/3019605a4fc9)

- [objc_msgSend arm64 崩溃问题](https://blog.csdn.net/chenyong05314/article/details/42121001)


### Data Persistence

*DB, Keychain, NSUserDefaults, Write*

- [DYFSwiftKeychain](https://github.com/chenxing640/DYFSwiftKeychain) - `DYFSwiftKeychain` is used to save text and data in Keychain securely for iOS, OS X, tvOS and watchOS. ( [DYFKeychain](https://github.com/chenxing640/DYFKeychain) (Objective-C) )

- [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS, watchOS, tvOS and macOS. Makes using Keychain APIs as easy as NSUserDefaults.

- [GenericKeychain](https://developer.apple.com/library/archive/samplecode/GenericKeychain/Introduction/Intro.html) - This sample shows how to add, query for, remove, and update a keychain item of generic class type. It also demonstrates the use of shared keychain items.

- [fmdb](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite.

- [JQFMDB](https://github.com/gaojunquan/JQFMDB) - FMDB的封装，操作简单，线程安全，扩展性强，直接操作model或dictionary。

- [wcdb](https://github.com/Tencent/wcdb) - WCDB is a cross-platform database framework developed by WeChat.


### 蓝牙

- [EasyBluetooth]( https://github.com/chenliangloveyou/EasyBluetooth) - 一款iOS BLE蓝牙调试工具，非常简单容易，也可以作为一个蓝牙库，快速集成和开发。 可以两步搞定蓝牙开发操作。第一步连接设备，第二步特征读写数据。【 [Priview 1](https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_1.gif) | [Priview 2](https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_2.gif) | [Priview 3](https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_3.png) | [Priview 4](https://github.com/chenliangloveyou/EasyBluetooth/raw/master/EasyBlueTooth/EasyBlueTooth/preview/preview_4.png) 】

- [WHBLEDemo](https://github.com/remember17/WHBLEDemo) - 📱CoreBluetooth central and peripheral demo with OC/Swift (iOS蓝牙中心设备和外设开发,包含OC/Swift版本) 。【 [Priview 1](https://camo.githubusercontent.com/3ba378f9a697f5e30d6937f64ba8a97498bb3513/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d613731636537393634653834613263652e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) | [Priview 2](https://camo.githubusercontent.com/47b0012be03c0f3f6c59c7169fa4563ff6380d7c/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f333837333030342d353334626433303463346537393765362e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】

- [BabyBluetooth](https://github.com/coolnameismy/BabyBluetooth) - 简单易用的蓝牙库，基于CoreBluetooth的封装，并兼容ios和mac osx。【 [Priview 1](https://github.com/coolnameismy/BabyBluetooth/raw/master/logo.png) 】

- [BluetoothKit](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE.

- [MultipeerConnectivity](https://github.com/xiangzuhua0209/MultipeerConnectivity) - 蓝牙MultipeerConnectivity。

- [WEBlueToothManager](https://github.com/yuhanle/WEBlueToothManager) - 🐱一个蓝牙4.0的智能硬件架构。([blog](https://latehorse.github.io))【 [Priview 1](https://camo.githubusercontent.com/d35e114d02c6b82ccea90e1547d268607362ee41/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3534353735352d343837633230623536646461623832322e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) | [Priview 2](https://camo.githubusercontent.com/d1f9847a9232542113ffdd226ea5b3773f26b5f1/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3534353735352d303161616262356533396130613735302e706e673f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970253743696d61676556696577322f322f772f31323430) 】

- [MPBluetoothKit](https://github.com/MacPu/MPBluetoothKit) - This is a block-based framework for building Bluetooth iOS apps using the CoreBluetooth Framework.Its a very powerful and useful,and very easy to use it.


### 手势指纹面容ID密码解锁

- [DYFAuthIDAndGestureLock](https://github.com/chenxing640/DYFAuthIDAndGestureLock) - 手势密码解锁 和 TouchID（指纹）/ FaceID（面容）解锁，代码简洁高效。(Gesture passcode unlocking and TouchID (fingerprint) / FaceID (facial features) unlocking, concise code and efficient.)【 [Priview 1](https://github.com/chenxing640/DYFAuthIDAndGestureLock/raw/master/images/AuthIDAndGestureLockPreview.gif) 】

- [XGTouchDemo](https://github.com/XGPASS/XGTouchDemo) - 手势密码解锁和指纹TouchID解锁的demo。【 [Priview 1](https://github.com/XGPASS/XGTouchDemo/raw/master/images/develop.gif) 】

- [TouchIDAndGestureLock](https://github.com/bugaoshuni/TouchIDAndGestureLock) - 指纹解锁、手势解锁。

- [YLSwipeLockView](https://github.com/XiaoYulong/YLSwipeLockView) - A swipe password view to unlock an application written in objective-c. 【 [Priview 1](https://github.com/XiaoYulong/YLSwipeLockView/raw/master/example.gif) 】

- [YZAuthID](https://github.com/micyo202/YZAuthID)  - TouchID（指纹）/ FaceID（面容）验证类库，代码简洁，高效。【 [Priview 1](https://github.com/micyo202/YZAuthID/raw/master/auth_finger_2.png) | [Priview 2](https://github.com/micyo202/YZAuthID/raw/master/auth_finger_3.png) 】

- [BiometricAuthentication](https://github.com/rushisangani/BiometricAuthentication) - Use Apple FaceID or TouchID authentication in your app using BiometricAuthentication. 


### 布局

- [WSCollectionViewFlowLayout](https://github.com/ONECATYU/WSCollectionViewFlowLayout) - 可替代UICollectionViewFlowLayout的标签流布局，支持固定有规则的布局形式。实现了UICollectionViewDelegateFlowLayout协议方法。使用形式和系统Flowlayout相同。
| [Priview 1](https://github.com/ONECATYU/WSCollectionViewFlowLayout/raw/master/Demo.gif) |


### 图像模糊化

- [BlurViewExample](https://github.com/Vanbein/BlurViewExample) - iOS实现模糊效果的几种方法和示例。【 [Priview 1](https://github.com/Vanbein/BlurViewExample/raw/master/BlurEffectsPreview/blurEffect.png) | [Priview 2](https://github.com/Vanbein/BlurViewExample/raw/master/BlurEffectsPreview/GPUImage.png) | [Priview 3](https://github.com/Vanbein/BlurViewExample/raw/master/BlurEffectsPreview/UIImage+ImageEffects.png) 】

- [SVBlurView](https://github.com/TransitApp/SVBlurView) - A simple reimplementation of FXBlurView for iOS 7. 【 [Priview 1](https://camo.githubusercontent.com/69cc3bbb72c4e787275c953d7547a4906031afe2/687474703a2f2f662e636c2e6c792f6974656d732f31713144306b3138307a32593075324a337832662f694f5325323053696d756c61746f7225323053637265656e25323073686f7425323031392532304f63742c25323032303133253230352e33342e3231253230504d2e706e67) 】

- [iOS-blur](https://github.com/JagCesar/iOS-blur) - Blur a UIView. 【 [Priview 1](https://camo.githubusercontent.com/1a3847644269c1e9706c31c6ea9525bd5fc385b4/68747470733a2f2f7261772e6769746875622e636f6d2f4a616743657361722f694f532d626c75722f6d61737465722f73637265656e73686f742e706e67) 】


### 图片浏览器

- [SDPhotoBrowser](https://github.com/gsdios/SDPhotoBrowser) - A image browser which is easy for using. 非常简单易用的图片浏览器，模仿微博图片浏览器动感效果，综合了图片展示和存储等多项功能。【 [Priview 1](https://camo.githubusercontent.com/a2e87ee4bd1c7b97913e2f9de8b416302032157c/687474703a2f2f63646e2e636f63696d672e636f6d2f6262732f6174746163686d656e742f4669645f31392f31395f3434313636305f3633313963353063333465643633632e676966) 】

- [YHPhotoBrowser](https://github.com/hackxhj/YHPhotoBrowser) - 轻量级网络图片浏览器 优化性能 Gif播放性能 类新浪微博打开关闭动画 类微信图片浏览下拉图片消失。【 [Priview 1](https://raw.githubusercontent.com/hackxhj/YHPhotoBrowser/master/png/yh.gif) 】

- [HZPhotoBrowser](https://github.com/chennyhuang/HZPhotoBrowser) - 图片浏览器，photoBrowser ，新浪微博，picture, pictureBrowser, sina, weibo. 【 [Priview 1](https://github.com/chennyhuang/HZPhotoBrowser/raw/master/1.gif) 】

- [KSPhotoBrowser](https://github.com/skx926/KSPhotoBrowser) - A beautiful photo browser with interactive dismissal animation. 一个小而美的图片浏览器。【 [Priview 1](https://camo.githubusercontent.com/cfdefe604fd779c1c3ea62c8a2aed91a3e1ab44b/68747470733a2f2f7261772e6769746875622e636f6d2f736b783932362f4b5350686f746f42726f777365722f6d61737465722f496d616765732f426c75722e676966) | [Priview 2](https://camo.githubusercontent.com/1bb75bf6ede320b6824dc799b0afba8e3c5e4ff4/68747470733a2f2f7261772e6769746875622e636f6d2f736b783932362f4b5350686f746f42726f777365722f6d61737465722f496d616765732f436f726e65722e676966) 】

- [TZImagePickerController](https://github.com/banchichen/TZImagePickerController) - 一个支持多选、选原图和视频的图片选择器，同时有预览、裁剪功能，支持iOS6+。 A clone of UIImagePickerController, support picking multiple photos、original photo、video, also allow preview photo and video, support iOS6+.


### 扫码

*二维码，条形码相关内容*

- [DYFCodeScanner](https://github.com/chenxing640/DYFCodeScanner) - 一个二维码/条形码的扫码器，代码简洁高效。(A QR code and Barcode scanner for iOS. Its code is concise and efficient.) 【 [Priview 1](https://github.com/chenxing640/DYFCodeScanner/raw/master/images/CodeScannerPreview.gif) 】

- [MMScan](https://github.com/MinMao-Hub/MMScan) - 一个简单的二维码以及条码扫描工具，使用Objective-C语言开发，有一套自定义的扫描动画以及界面，还包括生成二维码以及条码。【 [Priview 1](https://github.com/MinMao-Hub/MMScan/raw/master/gifs/mmscan.gif) 】

- [QRCode](https://github.com/kingcong/QRCode-master) - 仿微信二维码扫描。

- [LBXScan](https://github.com/MxABC/LBXScan) - A barcode and qr code scanner (二维码、扫码、扫一扫、ZXing、ZBar、iOS系统AVFoundation扫码封装，扫码界面效果封装)。【 [Priview 1](https://github.com/MxABC/Resource/raw/master/scan12.gif) 】
  
- [swiftScan](https://github.com/MxABC/swiftScan) - A barcode and qr code scanner( 二维码 各种码识别，生成，界面效果)。【 [Priview 1](https://github.com/MxABC/swiftScan/raw/master/ScreenShots/page1.jpg) | [Priview 2](https://github.com/MxABC/swiftScan/raw/master/ScreenShots/page2.jpg) 】

- [SGQRCode](https://github.com/kingsic/SGQRCode) - The easy to use QRCode scan library for iOS【iOS 原生二维码生成与扫描 -> 高仿微信】。【 [Priview 1](https://raw.githubusercontent.com/kingsic/SGQRCode/master/Picture/sorgle1.png) | [Priview 2](https://raw.githubusercontent.com/kingsic/SGQRCode/master/Picture/sorgle4.png) 】

- [EFQRCode](https://github.com/EFPrefix/EFQRCode) - A better way to operate QR Code in Swift, support iOS, macOS, watchOS and tvOS. 【 [Priview 1](https://raw.githubusercontent.com/EFPrefix/EFQRCode/assets/QRCodeGIF6.gif) 】
    
- [JB_ZBarSDK_Demo](https://github.com/jaybinhe/JB_ZBarSDK_Demo) - 通过[ZBar SDK](https://github.com/bmorton/ZBarSDK)，实现IOS扫描、生成二维码的功能。【 [Priview 1](https://github.com/jaybinhe/JB_ZBarSDK_Demo/raw/master/JB_ZBarSDK_Demo/screenshots/customScan.gif) | [Priview 2](https://github.com/jaybinhe/JB_ZBarSDK_Demo/raw/master/JB_ZBarSDK_Demo/screenshots/create.gif) 】


### 下拉刷新和上拉加载

- [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - An easy way to use pull-to-refresh. 【 [Priview 1](https://camo.githubusercontent.com/15577b87be4403d9e2ede4d5cd5b9fccbd1d03ae/687474703a2f2f696d61676573302e636e626c6f67732e636f6d2f626c6f67323031352f3439373237392f3230313530362f3134313230343334333438363135312e676966) | [Priview 2](https://camo.githubusercontent.com/911191d46157ea3961728b16696aea4440ffeb92/687474703a2f2f696d61676573302e636e626c6f67732e636f6d2f626c6f67323031352f3439373237392f3230313530362f3134313230343430323233383338392e676966) 】

- [SDRefreshView](https://github.com/gsdios/SDRefreshView) - 简单易用的上拉和下拉刷新（多版本细节适配）。Pull To Refresh. 【 [Priview 1](https://camo.githubusercontent.com/1febdd6e24be7611d1059d512804437ea35f4a8f/687474703a2f2f63632e636f63696d672e636f6d2f6262732f6174746163686d656e742f4669645f31392f31395f3434313636305f6431333261633664623135626361632e676966) 】

- [KafkaRefresh](https://github.com/BeatsKitano/KafkaRefresh) - About Animated, customizable, and flexible pull-to-refresh framework for faster and easier iOS development.


### 指示器

- [EasyShowView](https://github.com/chenliangloveyou/EasyShowView) - 一款超级简单的展示工具，包括吐司指示器，loding加载框，空白页提示，alertview，actionsheet的定制。可任意定制自己想要的各种样式，自定义动画，显示样式等各种操作，使各种展示更加easy。【 [Priview 1](https://github.com/chenliangloveyou/EasyShowView/raw/master/show_preview/preview_text.gif) | [Priview 2](https://github.com/chenliangloveyou/EasyShowView/raw/master/show_preview/preview_loding.gif) 】

- [MBProgressHUD](https://github.com/jdg/MBProgressHUD) - MBProgressHUD + Customizations. [http://www.bukovinski.com/](http://www.bukovinski.com/)

- [MBProgressHUD-JDragon](https://github.com/lyc59621/MBProgressHUD-JDragon) - MBProgressHUD 封装。【 [Priview 1](https://github.com/lyc59621/MBProgressHUD-JDragon/raw/master/MBProgressHUD-JDragon.gif) 】

- [JGProgressHUD](https://github.com/JonasGessner/JGProgressHUD) - An elegant and simple progress HUD for iOS and tvOS, compatible with Swift and ObjC. 【 [Priview 1](https://github.com/JonasGessner/JGProgressHUD/raw/master/Examples/Screenshots/Presentation.png) 】

- [SVProgressHUD](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS and tvOS app. 

- [MMMaterialDesignSpinner](https://github.com/misterwell/MMMaterialDesignSpinner) - An iOS activity spinner modeled after Google's Material Design Spinner. 【 [Priview 1](https://raw.githubusercontent.com/misterwell/MMMaterialDesignSpinner/master/Demo.gif) 】

- [SCSkypeActivityIndicatorView](https://github.com/stefanceriu/SCSkypeActivityIndicatorView) - Activity indicator view similar to the one seen in the Skype apps. 【 [Priview 1](https://camo.githubusercontent.com/baff2b55b9c0b3f488e1d109e5f970962bfff6d1/68747470733a2f2f64726976652e676f6f676c652e636f6d2f75633f6578706f72743d646f776e6c6f61642669643d3042794c436b554f39306c746f4e47646a63324d79636a426b563155) | [Priview 2](https://camo.githubusercontent.com/6d0c318bc2c952b9ee358d04f97bde4a8ebb5647/68747470733a2f2f64726976652e676f6f676c652e636f6d2f75633f6578706f72743d646f776e6c6f61642669643d3042794c436b554f39306c746f535446615831497a4e33524465466b) 】

- [MDFlickrActivityIndicatorView](https://github.com/kirsis/MDFlickrActivityIndicatorView) - Flickr-like activity indicator view for iOS. 【 [Priview 1](https://github.com/kirsis/MDFlickrActivityIndicatorView/raw/master/images/MDFlickrActivityIndicatorView_Preview.png) 】


### Toast

- [DYFToast](https://github.com/chenxing640/DYFToast) - Fully imitating the Android toast, using chain programming, through point operation, it can achieve the properties settings and display of the toast, the code is concise and efficient.

- [Toast-Swift](https://github.com/scalessec/Toast-Swift) - 向UIView对象类添加Toast通知的Swift扩展(A Swift extension that adds toast notifications to the UIView object class.)。([Objective-C版](https://github.com/scalessec/Toast)) 【 [Priview 1](https://github.com/scalessec/Toast-Swift/raw/master/toast_swift_screenshot.jpg) 】

- [Toaster](https://github.com/devxoul/Toaster) - 🍞 Toast for Swift

- [XHToast](https://github.com/CoderZhuXH/XHToast) - 简洁轻便提示工具,一行代码既可完成提示信息显示 - 支持自定义显示位置及停留时间。【 [Priview 1](https://camo.githubusercontent.com/5e94289a5930fe4de9e844f94a308b6d3919e59b/687474703a2f2f682e686970686f746f732e62616964752e636f6d2f696d6167652f7069632f6974656d2f303233623562623563396561313563653239373365343339626530303361663333613837623236342e6a7067) 】

- [iToast-iOS](https://github.com/Tim9Liu9/iToast-iOS) - iToast的ARC版本。

- [toast-notifications-ios](https://github.com/ecstasy2/toast-notifications-ios) - We at Guru software really love toast notifications available on android OS, so we've built a similar feature for the IOS enabled devices.

- [JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications) - An iOS UIView for presenting a minimalistic notification that doesn't block the UI and is highly configurable.


### Menu和弹出视图

- [kxmenu](https://github.com/kolyvan/kxmenu) - KxMenu is a vertical popup menu for using in iOS applications. 【 [Priview 1](https://camo.githubusercontent.com/d28144796042a6c6bddf7d0c097be831cea8810a/68747470733a2f2f7261772e6769746875622e636f6d2f6b6f6c7976616e2f6b786d656e752f6d61737465722f73637265656e73686f742f6578616d706c652e676966) 】

- [LCSlideMenu](https://github.com/ChinaHackers/LCSlideMenu) - A powerful and easy to use slider menu. 【 [Priview 1](https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/LCSlideMenu.png) | [Priview 2](https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast01.gif) | [Priview 3](https://raw.githubusercontent.com/ChinaHackers/LCSlideMenu/master/Screencast/Screencast03.gif) 】

- [JMColumnMenu](https://github.com/JunAILiang/JMColumnMenu) - 仿腾讯新闻、今日头条栏目管理。

- [WJPageManager](https://github.com/WJCha/WJPageManager) - WJPageManager提供了可以快速完成项目中常见的标题栏以及对应的分页控制器创建与逻辑处理。【 [Priview 1](https://github.com/WJCha/WJPageManager/raw/master/resource/title.gif) | [Priview 2](https://github.com/WJCha/WJPageManager/raw/master/resource/page.gif) 】

- [YNPageScrollViewController](https://github.com/yongyuandouneng/YNPageScrollViewController) - 一个强大的PageScrollViewController滑动库。菜单多种样式选择，支持悬浮样式、导航条样式、顶部样式。【 [Priview 1](https://github.com/yongyuandouneng/YNPageScrollViewController/raw/master/GifAndImage/myProject.gif) | [Priview 2](https://github.com/yongyuandouneng/YNPageScrollViewController/raw/master/GifAndImage/Demo.gif) 】

- [YNPageViewController](https://github.com/yongyuandouneng/YNPageViewController) - 特斯拉组件、QQ联系人布局、多页面嵌套滚动、悬停效果、美团、淘宝、京东、微博、腾讯新闻、网易新闻、今日头条等标题滚动视图。 (YNPageScrollViewController重构版) 【 [Priview 1](https://camo.githubusercontent.com/4c18ea3624dff75c20df1093bb143e9b36339f34/687474703a2f2f706178646c72646b372e626b742e636c6f7564646e2e636f6d2f594e5061676556696577436f6e74726f6c6c65724769662e676966) 】

- [LTScrollView](https://github.com/gltwy/LTScrollView) - ScrollView嵌套ScrolloView（UITableView 、UICollectionView）解决方案， 支持OC / Swift. 【 [Priview 1](https://github.com/gltwy/LTScrollView/raw/master/demo.gif) 】

- [MLMenu](https://github.com/MrDML/MLMenu) - 仿微信QQ右上角菜单功能。【 [Priview 1](https://github.com/MrDML/MLMenu/raw/master/MLMenuGif.gif) 】

- [JMDropMenu](https://github.com/JunAILiang/JMDropMenu) - 仿QQ、微信下拉菜单封装，支持自定义样式。【 [Priview 1](https://raw.githubusercontent.com/JunAILiang/JMDropMenu/master/JMDropMenu/JMDropMenu.gif) 】

- [XYMenu](https://github.com/HeathHsia/XYMenu) -  简易集成的弹出菜单。【 [Priview 1](https://github.com/HeathHsia/XYMenu/raw/master/img/demo.gif) 】

- [YCMenuView](https://github.com/WellsYC/YCMenuView) - a popup menu which can be highly customized. (一个可以根据关联点和关联视图弹出的菜单，类似QQ导航栏右侧菜单。可满足高度自定义需求。) 【 [Priview 1](https://github.com/WellsYC/YCMenuView/raw/master/logo/original-horizontal.png) | [Priview 2](https://github.com/WellsYC/YCMenuView/raw/master/menuView.gif) 】】

- [REMenu](https://github.com/romaonthego/REMenu) - Dropdown menu inspired by Vine. 【 [Priview 1](https://raw.githubusercontent.com/romaonthego/REMenu/master/Demo.gif) 】

- [PopMenu](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app. 【 [Priview 1](https://github.com/xhzengAIB/LearnEnglish/raw/master/Screenshots/XHSinaMenuViewExample.gif) 】

- [SHESelectTable](https://github.com/shelly8219/SHESelectTableDemo) - 下拉选择的列表。【 [Priview 1](https://github.com/shelly8219/SHESelectTableDemo/raw/master/source/screenclip.jpg) 】

- [MMComboBox](https://github.com/YYWDark/MMComboBox) - A comboBox contained three kinds of style. 【 [Priview 1](https://camo.githubusercontent.com/30c25cfaecb29ebfb9a59a5fe93a6751342d163a/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f3330373936332d353837313561313431633063653630302e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】

- [CustomPopoverView](https://github.com/maltsugar/CustomPopoverView) - 一款小巧灵活的自定义弹出视图, 可以做自定义AlertView、弹出窗口等等。A tiny and sweet custom popView (pop popup). 【 [Priview 1](https://camo.githubusercontent.com/d3fb0b4d5ef8712421cd7da8228ec33ceaf703f7/687474703a2f2f7777332e73696e61696d672e636e2f6d773639302f373261626137656667773166336368303077777778673230616c306a336771702e676966) | [Priview 2](https://camo.githubusercontent.com/548226495b29d0db044add98a61f6f0c18a2d4ac/687474703a2f2f7777322e73696e61696d672e636e2f6d773639302f3732616261376566677731663364636b6e6c667068673230616d306a33646d362e676966) 】

- [MMPopupView](https://github.com/adad184/MMPopupView) - A basic Pop-Up Kit allows you to easily create Pop-Up view. You can focus on the only view you want to show.Besides, it comes with 2 common Pop-Up view, MMAlertView & MMSheetView. You can easily use & customize it. 【 [Priview 1](https://github.com/adad184/MMPopupView/raw/master/Images/0.jpg) 】

- [JianShuPopViewDemo](https://github.com/linsyorozuya/JianShuPopViewDemo) - 简书、淘宝弹出效果动画demo。【 [Priview 1](https://github.com/LinBling/JianShuPopViewDemo/raw/master/2016-02-03%2016_20_30.gif) 】

- [UIAlertView-Blocks](https://github.com/jivadevoe/UIAlertView-Blocks) - A category for UIAlertView which allows you to use blocks to handle the pressed button events rather than implementing a delegate.

- [BAAlertController](https://github.com/BAHome/BAAlertController) - UIAlertController 的分类，一个block 搞定系统 alert 和 actionSheet 的 iPhone 和 iPad 版本适配！【 [Priview 1](https://github.com/BAHome/BAAlertController/raw/master/Images/BAAlertController4.png) | [Priview 2](https://github.com/BAHome/BAAlertController/raw/master/Images/BAAlertController7.png) 】

- [FWPopupView](https://github.com/choiceyou/FWPopupView) - 弹窗控件：支持AlertView、Sheet、自定义视图的PopupView。AlertView中可以嵌套自定义视图，各组件的显示隐藏可配置；Sheet仿微信样式；同时提供自定义弹出。更多配置请参考”可设置参数“，提供OC使用Demo。

- [DropDown](https://github.com/AssistoLab/DropDown) - A Material Design drop down for iOS.


### WebView和进度条

- [DYFProgressView](https://github.com/chenxing640/DYFProgressView) - Super useful progress bar and web page progress bar, the operation is simple and easy to use. 【 [Priview 1](https://github.com/chenxing640/DYFProgressView/raw/master/images/ProgressViewPreview.gif) 】

- [WebViewJavascriptBridge](https://github.com/marcuswestin/WebViewJavascriptBridge) - About An iOS/OSX bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews.
```
  #ITMS-90809: Deprecated API Usage - Apple will stop accepting submissions of apps that use UIWebView APIs
  #删除WebViewJavascriptBridge中的WebViewJavascriptBridge.h和WebViewJavascriptBridge.m文件
  pre_install do |installer|
    dir_web = File.join(installer.sandbox.pod_dir('WebViewJavascriptBridge'), 'WebViewJavascriptBridge')
    Dir.foreach(dir_web) {|x|
      real_path = File.join(dir_web, x)
      if (!File.directory?(real_path) && File.exists?(real_path))
        if(x == 'WebViewJavascriptBridge.h' || x == 'WebViewJavascriptBridge.m')
          File.delete(real_path)
        end
      end
    }
  end
```

- [NJKWebViewProgress](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. Currently, UIWebView doesn't have official progress interface. You can implement progress bar for your in-app browser using this module. 【 [Priview 1](https://camo.githubusercontent.com/082fc708cc461dc53832b7d14d5affdf475dd57b/68747470733a2f2f7261772e6769746875622e636f6d2f6e696e6a696e6b756e2f4e4a4b5765625669657750726f67726573732f6d61737465722f44656d6f4170702f53637265656e73686f742f73637265656e73686f74312e706e67) 】

- [BAWKWebView](https://github.com/BAHome/BAWKWebView) - 用分类封装 WKWebView，一行代码搞定 request、URL、URLString、本地 HTML文件、HTMLString等请求，一个 block 搞定 title、progress、currentURL、当前网页的高度等等。

- [YQLWebViewProgress](https://github.com/Dogndxt/YQLWebViewProgress) - 网页进度条显示，WebViewProgress. 【 [Priview 1](https://github.com/BAHome/BAWKWebView/raw/master/Images/BAWKWebView.gif) 】

- [WYWebViewDemo](https://github.com/wangyansnow/WYWebViewDemo) - 进度条加载网页。【 [Priview 1](https://github.com/wangyansnow/WYWebViewDemo/raw/master/WYWebViewDemo/screenShot/webViewLoading.gif) 】

- [CHWebView](https://github.com/chausson/CHWebView) - 简化UIWebView和WKWebView的API使用，在此基础上实现进度条和简单JS交互事件。【 [Priview 1](https://github.com/chausson/CHWebView/raw/master/Resource/WebView.gif) | [Priview 2](https://github.com/chausson/CHWebView/raw/master/Resource/CHWebView.png) 】

- [WKWebViewDemo](https://github.com/SSiming/WKWebViewDemo) - WKWebView实际使用中遇到的注意点，以及WKWebView和JavaScript交互。具体介绍请戳[WKWebView使用及注意点(keng)](http://www.jianshu.com/p/9513d101e582)。

- [XDProgressView](https://github.com/Tbwas/XDProgressView) - XDProgressView可以由你心情任意设置高度，也可在上面显示文字。

- [SDProgressView](https://github.com/gsdios/SDProgressView) - Progress Indicator View. 简便美观的进度指示器。【 [Priview 1](https://camo.githubusercontent.com/cce98893ac0d661d152c266dd564fb4e0544869e/687474703a2f2f63632e636f63696d672e636f6d2f6262732f6174746163686d656e742f4669645f31392f31395f3434313636305f3537656366623037633235376564662e676966) 】

- [MultiProgressView](https://github.com/mac-gallagher/MultiProgressView) - 📊 An animatable view that depicts multiple progresses over time. Modeled after UIProgressView.

- [WebController](https://github.com/pikachu987/WebController) - Quick WKWebView 😄.


### 动画

- [MGTrasitionPractice](https://github.com/LYM-mg/MGTrasitionPractice) - 自定义转场练习。【 [Priview 1](http://upload-images.jianshu.io/upload_images/1429890-db65965fb55e23ed.gif?imageMogr2/auto-orient/strip) 】

- [pop](https://github.com/facebook/pop) - An extensible iOS and OS X animation library, useful for physics-based interactions.

- [PopAnimationDemo](https://github.com/crossPQW/PopAnimationDemo) - 使用pop完成一些的动画效果。【 [Priview 1](https://github.com/crossPQW/PopAnimationDemo/raw/master/PopAnimationDemo/screenShot/animationList.gif) | [Priview 2](https://github.com/crossPQW/PopAnimationDemo/raw/master/PopAnimationDemo/screenShot/plusRotate.gif) 】

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

- [BRPickerView](https://github.com/91renb/BRPickerView) - 封装的是iOS中常用的选择器组件。高度封装，只需一句代码即可完成调用，使用比较灵活支持自定义主题颜色。选择器类型主要包括：日期选择器、时间选择器、地址选择器、自定义字符串选择器。【 [Priview 1](https://github.com/91renb/BRPickerView/raw/master/BRPickerViewDemo/效果图/效果图1.gif?raw=true) | [Priview 2](https://github.com/91renb/BRPickerView/raw/master/BRPickerViewDemo/效果图/效果图2.gif?raw=true) 】


### 搜索

- [PYSearch](https://github.com/ko1o/PYSearch) - 🔍 An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad) . 【 [Priview 1](https://github.com/iphone5solo/learngit/raw/master/imagesForPYSearch/logo.png) | [Priview 2](https://raw.githubusercontent.com/ko1o/learngit/master/imagesForPYSearch/hotSearchStyle01.png) | [Priview 3](https://github.com/ko1o/learngit/raw/master/imagesForPYSearch/hotSearchStyle02.png) 】


### 分享

- [ShareSDK-for-iOS](https://github.com/MobClub/ShareSDK-for-iOS) - ShareSDK是一个完全免费的社会化分享组件，为移动端的iOS App提供社会化功能。([MobTech](http://www.mob.com))

- [U-Share SDK](https://www.umeng.com/social) - 帮助应用或游戏快速具备国内外多平台分享、第三方登录功能，SDK包小，集成成本低，平台覆盖全，并基于友盟+大数据，提供权威、实时的用户画像、分享回流等数据分析，助力产品开发与推广。([友盟](https://www.umeng.com))

- [TTOpenInAppActivity](https://github.com/honkmaster/TTOpenInAppActivity) - TTOpenInAppActivity is a UIActivity subclass that provides an "Open In ..." action to a UIActivityViewController. TTOpenInAppActivity uses an UIDocumentInteractionController to present all Apps that can handle the document specified with by the activity items. 【 [Priview 1](https://github.com/honkmaster/TTOpenInAppActivity/raw/master/Screenshot.png) 】

- [MonkeyKing](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you to post messages to Chinese Social Networks.


### 图片验证码

- [ZLSecurityCode](https://github.com/ZLFighting/ZLSecurityCode) - iOS-字符图片验证码。【[Priview 1](https://github.com/ZLFighting/ZLSecurityCode/raw/master/ZLSecurityCode/验证码图.gif) 】

- [MQVerCodeView](https://github.com/meiqi1992/MQVerCodeView) - 类似图片验证码，点击可刷新。【 [Priview 1](https://github.com/meiqi1992/MQVerCodeView/raw/master/verCodeView.gif) 】

- [YanZhengCode](https://github.com/wsl2ls/YanZhengCode) - 图片验证码和滑块验证码。【 [Priview 1](https://camo.githubusercontent.com/2a26c12270d298a74738691b13578d53e962835c/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d303566316430626239646431313537372e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】

- [KeenCodeUnit](https://github.com/chongzone/KeenCodeUnit) - 自定义的验证码、支付密码文本框，支持明文、密文输入等，支持内容的验证错误处理。


### 获取设备相关信息

- [iOS-getClientInfo](https://github.com/PengfeiWang666/iOS-getClientInfo) - 📲iOS中获取各种设备信息。

- [ZGInfoCollection](https://github.com/ScottZg/ZGInfoCollection) - 获取iPhone相关信息以及网络状态等等。


### 广告

- [ZLAdvertDemo](https://github.com/ZLFighting/ZLAdvertDemo) - 启动页加载广告。【 [Priview 1](https://github.com/ZLFighting/ZLAdvertDemo/raw/master/ZLAdvertDemo/启动页跳过广告.gif) 】

- [SplashScreenADView](https://github.com/wxzwork/SplashScreenADView) - 启动图和开屏广告页，类似网易。可根据广告的有效时间显示或关闭广告页，以及定制广告页停留的时间。

- [LaunchAd](https://github.com/ScottZg/LaunchAd) - 启动页广告。【 [Priview 1](https://camo.githubusercontent.com/0781275d51a7e7eea96a0e689dad36f802057fb0/68747470733a2f2f6f6f6f2e306f302e6f6f6f2f323031352f31312f32302f353634656237656632363135352e676966) 】

- [ADScrollView](https://github.com/Thomaszhouwu/ADScrollView) - 下载一张网页图片，无线滑动图片展示各种广告图片，点击某个广告图片做出相应的操作。


### StarView

- [ZYStarView](https://github.com/RainManGO/ZYStarView) - Swift4.0 星星选择封装

- [SwiftyStarRatingView](https://github.com/Jerrrr/SwiftyStarRatingView) - A simple star rating view written in pure swift, lightweight but powerful.


### 高仿项目与Demo

- [LBXMLYFM-Swift](https://github.com/lb2281075105/LBXMLYFM-Swift) - Swift5项目仿写喜马拉雅App，采用MVC+MVVM设计模式，Moya+SwiftyJSON+HandyJSON网络框架和数据解析。数据来源抓包及部分本地json文件。

- [iOSProject](https://github.com/NJHu/iOSProject) - iOS project of collected some demos for iOS App. ([Swift版](https://github.com/NJHu/swiftProject)) 【 [Priview 1](https://raw.githubusercontent.com/NJHu/iOSProject/master/images/home.gif) | [Priview 2](https://raw.githubusercontent.com/NJHu/iOSProject/master/images/anidynquar.gif) 】

- [ZFZhiHuDaily](https://github.com/renzifeng/ZFZhiHuDaily) - 知乎日报swift版(精仿)。

- [YiYuanYunGou](https://github.com/JxbSir/YiYuanYunGou) - 高仿一元云购IOS应用（高仿自一元云购安卓客户端）。【| [Priview 1](https://raw.githubusercontent.com/JxbSir/YiYuanYunGou/master/shootscreen/1.png) | [Priview 2](https://raw.githubusercontent.com/JxbSir/YiYuanYunGou/master/shootscreen/3.png) 】

- [BingFenShiJia](https://github.com/hurryupcheng/BingFenShiJia) -  缤微纷购。

- [ifanr](https://github.com/iCodeForever/ifanr) - 高仿 爱范儿。

- [meituan](https://github.com/lookingstars/meituan) - 高仿美团iOS版，版本号5.7。【 [Priview 1](http://blog.csdn.net/l863784757/article/details/46912223) 】

- [nuomi](https://github.com/lookingstars/nuomi) - 高仿百度糯米iOS版，版本号5.13.0。【 [Priview 1](https://github.com/lookingstars/nuomi/raw/master/nuomi/ScreenShot/dtt1.gif) | [Priview 2](https://github.com/lookingstars/nuomi/raw/master/nuomi/ScreenShot/dtt2.gif) 】

- [U17](https://github.com/spicyShrimp/U17) - 精仿有妖气漫画(Swift5)。【 [Priview 1](https://github.com/spicyShrimp/U17/raw/master/Images/1@2x.png) | [Priview 2](https://github.com/spicyShrimp/U17/raw/master/Images/6@2x.png) | [Priview 3](https://github.com/spicyShrimp/U17/raw/master/Images/7@2x.png) | [Priview 4](https://github.com/spicyShrimp/U17/raw/master/Images/8@2x.png) 】

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


### 类目

- [JKCategories](https://github.com/shaojiankui/JKCategories) - JKCategories(iOS-Categories,Category), a collection of useful Objective-C Categories extending iOS Frameworks such as Foundation,UIKit,CoreData,QuartzCore,CoreLocation,MapKit Etc.

- [UIButtonEdgeInsets](https://github.com/CenterY/UIButtonEdgeInsets) - 通过类别和继承方式实现按钮的图片和标题布局，调整 UIButton的imageEdgeInsets 和 titleEdgeInsets属性。【 [Priview 1](https://github.com/CenterY/UIButtonEdgeInsets/raw/master/images/image_left.png) | [Priview 2](https://github.com/CenterY/UIButtonEdgeInsets/raw/master/images/image_right.png) 】

- [nsstring-extensions](https://github.com/ToshMeston/nsstring-extensions) - This is a category for NSString that adds commonly used methods such as trim, urlEncode, urlDecode, parseIntWithDefaultValue.


### 越狱检测

- [iOS-Jailbreak-Detector](https://github.com/diwu/ios-jail-break-detector) - A drop-in class that dynamically detects whether the iOS device your app is running on has been jailbroken or not. 100% App Store Submission Safe. No Private API.


### Sensor

- [SensorDemo](https://github.com/wsl2ls/SensorDemo) - 指纹识别、运动传感器、加速计、环境光感、距离传感器、指南针、陀螺仪等传感器示例集锦。【 [Priview 1](https://camo.githubusercontent.com/339dfa9c656084dc5d29496ec168c43426a8e201/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313730383434372d373764333332623832386363336261332e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】


### Uncategorized

- [MSWeakTimer](https://github.com/mindsnacks/MSWeakTimer) - Thread-safe NSTimer alternative that doesn't retain the target and supports being used with GCD queues.

- [NNMacros](https://github.com/amisare/NNMacros) - NNMacros通过宏的方式来简化iOS开发中OC的语法和Api的操作。

- [Ono](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & macOS.

- [NSString-URLEncode](https://github.com/kevinrenskers/NSString-URLEncode) - Category that adds URLEncode and URLDecode to NSString.

- [EasyIOS](https://github.com/zhuchaowe/EasyIOS) - A new generation of development framework based on Model-View-ViewModel.
    - [EasyRSS](https://github.com/zhuchaowe/EasyRSS) - A rss reader for ios based on easyios.

- [BEMCheckBox](https://github.com/Boris-Em/BEMCheckBox) - 一个可以很容易地为iOS创建漂亮的、高度可定制的动画复选框。

- [YXCollectionView](https://github.com/yixiangboy/YXCollectionView) - UICollection学习总结以及案例集合。【 [Priview 1](https://camo.githubusercontent.com/9b11a11b979f8b24f9db663d5b987cd9e4d702c6/687474703a2f2f696d672e6d792e6373646e2e6e65742f75706c6f6164732f3230313531322f32342f313435303932343933375f313132312e676966) | [Priview 2](https://camo.githubusercontent.com/2aa2d9fbb4922d683bb19fcee7d1aa7b141e1c8b/687474703a2f2f696d672e6d792e6373646e2e6e65742f75706c6f6164732f3230313531322f32342f313435303932343933385f353335332e676966) 】

- [NJKScrollFullScreen](https://github.com/ninjinkun/NJKScrollFullScreen) - Scroll to full screen like Facebook app. 【 [Priview 1](https://github.com/ninjinkun/NJKScrollFullScreen/raw/master/Screenshots/screencast.gif) 】

- [ScrollShowHeaderDemo](https://github.com/Cloudox/ScrollShowHeaderDemo) - 上下滑动列表时展现和隐藏顶部视图的demo。【 [Priview 1](https://github.com/Cloudox/ScrollShowHeaderDemo/raw/master/demo.gif) 】

- [HYBSnapkitAutoCellHeight](https://github.com/CoderJackyHuang/HYBSnapkitAutoCellHeight) - 基于[SnapKit](#Masonry与SnapKit)写的自动计算cell的高度的扩展。【 [Priview 1](https://github.com/CoderJackyHuang/HYBSnapkitAutoCellHeight/raw/master/snapkitcellheight.gif) 】

- [timeLineiOS](https://github.com/romaHerman/timeLineiOS) - DropIn TimeLine with progress animatiom. 【 [Priview 1](https://github.com/romaHerman/timeLineiOS/raw/master/output_ppeLRI.gif) 】

- [MGCollectionView](https://github.com/LYM-mg/MGCollectionView) - 环形图片排布以及花瓣形排布。【 [Priview 1](https://camo.githubusercontent.com/95feca7ac46c128b4574875ea15db0faa079d422/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313432393839302d646337363365663161666134666437352e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】

- [SCIndexView](https://github.com/TalkingJourney/SCIndexView) - SCIndexView provide a index view like Wechat. 【 [Priview 1](https://github.com/TalkingJourney/SCIndexView/raw/master/SCIndexViewDemo/Snapshots/demo_default.gif) | [Priview 2](https://github.com/TalkingJourney/SCIndexView/raw/master/SCIndexViewDemo/Snapshots/demo_center_toast.gif) 】

- [HotOrConcernCityListChoose](https://github.com/ScottZg/HotOrConcernCityListChoose) - 添加热门城市和关注城市。【 [Priview 1](https://camo.githubusercontent.com/9d2ffddf2f1f58cb3a9dc819efc735507d39e5c5/68747470733a2f2f6f6f6f2e306f302e6f6f6f2f323031362f30372f32322f353739316332353837643061632e676966) 】

- [RTLabel](https://github.com/honcheng/RTLabel) - Rich text formatting based on HTML-like markups for iOS. 【 [Priview 1](https://github.com/honcheng/RTLabel/raw/master/screenshot.png) 】

- [UICountingLabel](https://github.com/dataxpress/UICountingLabel) - Adds animated counting support to UILabel. 【 [Priview 1](https://github.com/dataxpress/UICountingLabel/raw/master/demo.gif) 】

- [TKPhoneformat](https://github.com/kangtian/TKPhoneformat) - 一款输入手机号码格式的控件。【 [Priview 1](https://github.com/kangtian/TKPhoneformat/raw/master/TKPhoneformat/TKPhoneformat/4.gif) 】

- [CopyLabel](https://github.com/TUTUDeveloper/CopyLabel) - iOS拥有复制功能的Label。

- [LYThemeChange](https://github.com/lanyasheng/LYThemeChange) - 主题更换。

- [iOS-Swift-UI](https://github.com/BranPeng/iOS-Swift-UI) - iOS-Swift-UI.

- [jiaModuleDemo](https://github.com/wujunyang/jiaModuleDemo) - 一个针对iOS模块化开发的解决方案。【 [Priview 1](https://github.com/wujunyang/jiaModuleDemo/raw/master/jiaModuleDemo/ProjectImage/1.png) 】

- [DraggingSort](https://github.com/HelloYeah/DraggingSort) - 长按拖拽排序。【 [Priview 1](https://camo.githubusercontent.com/bab591bc633afc9a316d5aedad2c45d42da2b91d/687474703a2f2f75706c6f61642d696d616765732e6a69616e7368752e696f2f75706c6f61645f696d616765732f313333383034322d646431356539306464396537353266632e6769663f696d6167654d6f6772322f6175746f2d6f7269656e742f7374726970) 】

- [RSSliderView](https://github.com/rsimenok/RSSliderView) - Custom slider based on UIView for iOS. 【 [Priview 1](https://camo.githubusercontent.com/7a7a899104ae97a30b0aae97bb2ce7d80a8a0f25/687474703a2f2f692e70696363792e696e666f2f69392f61666463643862353032396531663238623862643333663762643338323263312f313432343131383133392f31323632322f3738303432352f3132332e706e67) 】

- [JMMarkSlider](https://github.com/joamafer/JMMarkSlider) - Fully customizable slider that allows you to set marks on it. You can set the color of the bar, marks and handler, the width of the marks and even an image for the handler.

- [ZZHotKeysMenu](https://github.com/zhouXiaoR/ZZHotKeysMenu) - ZZHotKeysMenu自定义布局，继承自UICollectionViewLayout。【 [Priview 1](https://github.com/zhouXiaoR/ZZHotKeysMenu/raw/master/运行效果.gif) 】

- [corelib](https://github.com/wwwxiaowen/corelib) - iOS常用封装类库。

- [LDNetDiagnoService_IOS](https://github.com/Lede-Inc/LDNetDiagnoService_IOS) - iOS平台利用ping和traceroute的原理，对指定域名（通常为后台API的提供域名）进行网络诊断，并收集诊断日志。【 [Priview 1](https://github.com/Lede-Inc/LDNetDiagnoService_IOS/raw/master/LDNetDiagnoServiceDemoTests/netdiagnosis_ios.jpg) 】

- [TOSMBClient](https://github.com/TimOliver/TOSMBClient) -  A small library that serves as a simple SMB (Server Message Block ) client for iOS apps. The library allows connecting to SMB devices, downloading file metadata, and subsequently allows asynchronous downloading of files from an SMB device straight to an iOS device. It is an Objective-C wrapper around Defective SMb, or libDSM, a low level SMB client library built in C built by some of VideoLabs' developers. A copy of libDSM has been specially cross-compiled for iOS device architectures and embedded in this library, so this project has no external dependencies.

- [SimulateIDFA](https://github.com/youmi/SimulateIDFA) - iOS10 IDFA AD tracking limit solution.

- [model-identifiers](https://github.com/kluivers/model-identifiers) - Apple model identifiers. Gives you an approximation of the device based on the model identifier.

- [iOSTips](https://github.com/DarielChen/iOSTips) - 记录iOS开发中的一些知识点、小技巧。

- [EGOImageLoading](https://github.com/enormego/EGOImageLoading) - What if images on the iPhone were as easy as HTML? 

- [EGOCache](https://github.com/enormego/EGOCache) - Fast Caching for Objective-C (iPhone & Mac Compatible).

- [UncaughtExceptionHandler](https://github.com/minibear0523/UncaughtExceptionHandler) - 一个iOS崩溃异常的捕捉处理源代码，帮助更好的调试程序。

- [SPUncaughtExceptionHandler](https://github.com/kshipeng/SPUncaughtExceptionHandler) - APP闪退时，由用户决定是否继续。


## Mac

- [dSYMTools](https://github.com/answer-huang/dSYMTools) - dSYM analyze. 【 [Priview 1](https://camo.githubusercontent.com/e4d2bc52e9f048c7c14af6cfc4339f055fab5e38/687474703a2f2f616e737765726875616e672e626a2e626365626f732e636f6d2f626c6f672f6473796d546f6f6c2e706e67) 】

- [IPAPkgTool](https://github.com/chenxing640/IPAPkgTool) - 一款自动化打包ipa的MacOS应用。(A MacOS application that packs ipa automatically.) 【 [Priview 1](https://github.com/chenxing640/IPAPkgTool/raw/master/Images/login_page.png) 】

- [ios-app-signer](https://github.com/DanTheMan827/ios-app-signer) - This is an app for OS X that can (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device. ([Instructions](https://dantheman827.github.io/ios-app-signer/))

- [iReSign](https://github.com/maciekish/iReSign) - ReSign allows iDevice app bundles (.ipa) files to be signed or resigned with a digital certificate from Apple for disibution. This tool is aimed at enterprises users, for enterprise deployment, when the person signing the app is different than the person(s) developing it.

- [EasyResigny](https://github.com/niyaoyao/EasyResigny) - A Mac tool for user to resign iOS App.

- [Resign](https://github.com/LigeiaRowena/) - OSX utility to resign the IPA files.

- [FinderGo](https://github.com/onmyway133/FinderGo) - 🐢 Open terminal quickly from Finder. ([blog](https://onmyway133.github.io/)) 【 [Priview 1](https://github.com/onmyway133/FinderGo/raw/master/Images/Icon.png) | [Priview 2](https://github.com/onmyway133/FinderGo/raw/master/Images/go1.gif) 】

- [iOS-Images-Extractor](https://github.com/devcxm/iOS-Images-Extractor) - A Mac app to decode and extract images from iOS apps, support png/jpg/ipa/Assets.car files.

- [cartool](https://github.com/steventroughtonsmith/cartool) - Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

- [Pusic](https://github.com/peterHchina/Pusic) - An audio player for mac.

- [My12306Cocoa](https://github.com/fanjunwei/My12306Cocoa) - 12036自动订票max ox版。

- [12306Client](https://github.com/w11h22j33/12306Client) - 12306Client.

- [AYProgressBar](https://github.com/buddax2/AYProgressBar) - Customized NSProgressIndicator. Basically its just two-colored line with active color and passive color. 【 [Priview 1](https://github.com/buddax2/AYProgressBar/raw/master/screenshot.png?raw=true) 】

- [GRProgressIndicator](https://github.com/insidegui/GRProgressIndicator) - reimplementation of NSProgressIndicator with some customization support.

- [VVDocumenter](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write documentation comment easier, for both Objective-C and Swift. 【 [Priview 1](https://camo.githubusercontent.com/58e452b57245cd79c2e59ac7926609be4dffbfd8/68747470733a2f2f7261772e6769746875622e636f6d2f6f6e65766361742f5656446f63756d656e7465722d58636f64652f6d61737465722f7676646f63756d656e7465722d73776966742e676966) 】

- [ESJsonFormat-Xcode](https://github.com/EnjoySR/ESJsonFormat-Xcode) - 将JSON格式化输出为模型的属性。

- [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.

- [XAlign](https://github.com/qfish/XAlign) - An amazing Xcode Source Editor extension to align regular code. It can align Xnything in any way you want. 【 [Priview 1](https://camo.githubusercontent.com/f61bfc31e144ad6a9d7ca26fa19547a3af5da8c6/687474703a2f2f7166692e73682f58416c69676e2f696d616765732f646566696e652e676966) 】

- [FirTools](https://github.com/sdaduanbilei/FirTools) - 一个 swift 写的 OS X 的Menu Bar 程序。【 [Priview 1](https://github.com/sdaduanbilei/FirTools/raw/master/images/pic_7.png) 】


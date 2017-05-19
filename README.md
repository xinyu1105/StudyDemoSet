iOS资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。awesome-ios 就是 vsouza 发起维护的 iOS 资源列表，内容包括：框架、组件、测试、Apple Store、SDK、XCode、网站、书籍等。Swift 语言写成的项目会被标记为 ★ ，AppleWatch 的项目则会被标记为 ▲。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

我们要做什么？

基于 awesome-ios 资源列表，我们将对各个资源项进行编译整理。
整理后的内容，将收录在伯乐在线资源频道。可参考已整理的内容：
《BlockAlertsAnd-ActionSheets：一个支持block的弹出框》
《MBProgressHUD：一个不错的进度提示工具》
《Wonderful：不仅仅是一个酷炫的颜色库》
如何参与本项目？

从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

英文还不错，能读懂英文并用自己的话复述；
有 iOS 开发经验；
如有兴趣，请加 QQ：50872495。加 Q 时请注明「iOS大全」

本项目的参与者

维护者：tangyouhua

贡献者：ARIGATO、星满苍穹、天道、You

注：名单不分排名，不定期补充更新

目录

入门
库和框架
音频
动画
Apple TV
桥接
缓存
Core Data
图表
数据库
硬件
动作
蓝牙
位置
iBeacon
HUD
事件总线（ EventBus ）
文件
JSON
布局
日志
地图
媒体
图片
视频
PDF
消息
网络
推送通知
Passbook
权限
文本
浏览 / 介绍 / 教程
URL Scheme
UI
Websocket
代码质量
分析
支付
产品化工具
实用工具
安全
安装项目
依赖 / 包管理
测试
测试驱动开发（TDD） / 行为驱动开发（BDD）
UI测试
Beta 测试
其他测试
工具链
工具
敏捷开发
部署
App Store
SDK
Xcode
插件
主题
其他 Xcode 相关
编码规范
一些好网站
新闻, 博客等
UIKIt 文档
论坛和讨论列表
教程和 Keynotes
原型
Twitter
Facebook 群组
播客（Podcasts）
书籍
其他优秀的列表
资源
入门

Road Map iOS - 开发 iOS 应用从今天开始，苹果指南。★
Lifehacker - 我想写一个 iOS 应用，该从哪里开始？
Codeproject - 入门 iPhone 和 iOS 应用开发。
Ray Wenderlich - 学习 iOS 应用开发。
Stanford - Developing Apps to iOS - 斯坦福在 iTunes U 上的 iOS App 开发课程（音频和视频）。
Stanford - Developing iOS 8 Apps with Swift - 斯坦福在 iTunes U 上用 Swift 开发 App 的课程（2015版）。★
库和框架

音频

AudioBus：下一代 App 到 App 的实时音频路由。官网
AudioKit：一个强大的音频合成，处理和分析的工具集。官网
EZAudio：一个基于 Core Audio 的 iOS/OSX 音频可视化框架。用于实时，低延迟的音频处理和可视化功能的开发。官网
novocaine：应用于 OSX 和 iOS 的高性能音频框架。官网
QHSpeechSynthesizerQueue：一个 AVSpeechSynthesizer（iOS文本发音） 的队列管理系统。官网
StreamingKit - 一个针对 OSX 和 iOS 中 AudioPlayer/AudioStreamer 快捷的无缝扩展。官网
sound-fader-ios：一个 Swift 写的 AVAudioPlayer 的声音控制器 官网★
动画

Pop：一个 iOS 和 OS X 动画库，可以方便地实现由物理效果的交互。官网
AnimationEngine - 可以在 iOS 上方便地构建高级自定义动画。
Awesome-iOS-Animation：一个动画项目的集合。官网
RZTransitions：iOS View Controller 过场动画库。官网
DCAnimationKit：iOS 动画集合。很简单，只需要添加流水动画。官网
Spring：一个简单的 Swift iOS 动画库。官网
Canvas：无需代码就可以在 Xcode 中显示动画 http://canvaspod.io。官网
Fluent：便捷的 Swift 动画框架。 ★官网
Cheetah：便捷的 iOS 动画库，由 Swift2 编写。 ★官网
RadialLayer：针对可点击元素的动画（类似于 Youtube Music）★官网
Apple TV

Voucher：方便 tvOS App 通过 iOS 设备上相应的程序来认证的库。官网
桥接

JSPatch：JSPatch 利用 Objective-C 运行时桥接了 Objective-C 和 Javascript。你仅需引入一个小的引擎，就可以使用 JS 调用任何 Objective-C 的类。JSPatch 通常用来对 iOS App 做热修复（hotfix）。官网
缓存

SDURLCache：URLCache的子类，可以为 iPhone/iPad 应用提供的本地磁盘缓存。官网
Awesome Cache：让人喜爱的本地缓存 ★官网
mattress：iOS Web 内容的离线缓存 ★官网
Carlos：简单但却灵活的缓存 ★官网
图表

ios-charts - 一个强大的图表框架，MPAndroidChart 在 iOS 上的移植。★
JTChartView - JTChartView 是一个完全可定制的轻量级图表解决方案。
PNChart - 一个简单漂亮的图表库，Pinner 和 CoinsMan 的iOS客户端中使用了这个框架。
BEMSimpleLineGraph - 优雅的折线图框架。
JBChartView - 基于 iOS 的图表库，包含折线图和直方图。
iOSPlot - iOS 图表库。
XYPieChart - 一个有动画的饼图框架。
TEAChart - 简单易用的 iOS 图表库。包括了贡献图、时钟图、直方图。
EChart - iOS/iPhone/iPad 图表。提供了事件处理和动画支持。
FSLineChart - 一个 iOS 折线图库。
chartee - 一个为移动平台设计的图表库。
ANDLineChartView - 使用 ANDLineChartView 可以便捷的在视图类中显示有动画效果的折线图。
TWRCharts - 一个 ChartJS 的 iOS 封装。结合 Obj-C 原生代码便捷地构建有动画的图表。
Core Data

CWCoreData - 方便并发环境下 CoreData 框架开发的扩展与实用工具。
ObjectiveRecord - ActiveRecord 的 Objective-C 版本。
SSDataKit - 消除使用 CoreData 产生的样板代码。
ios-queryable - ios-queryable 是一个基于 CoreData 的 IQueryable/IEnumerable 实现。
ReactiveCoreData - ReactiveCoreData (RCD) 是一个将 CoreData 带入 ReactiveCocoa 世界的尝试。
Ensembles - 一个 CoreData 同步框架。
SLRESTfulCoreData - 根据 Objc 命名习惯，在运行时自动生成访问器，URL替换和智能属性映射。
Mogenerator - 自动生成 CoreData 代码。
HardCoreData - 不会阻塞 UI 线程的 CoreData 栈和控制器。
encrypted-core-data - 使用 SQLClipher 对 CoreData 的 SQLite 存储进行加密。
MagicalRecord - 非常优秀的 CoreData 便捷存取框架。
QueryKit - 一个简洁的类型安全的 CoreData 查询语言 ★
CoreStore - 强大的 CoreData 框架，解决了增量迁移、获取、观察等问题。★
数据库

Realm - CoreData 和 SQLite 的替代品。简洁、现代、快速。
YapDatabase - YapDatabase 是一个 iOS 和 Mac 上可扩展的数据库。
Couchbase Mobile - Couchbase，有云同步支持的移动平台上的文档存储。
FMDB - SQLite 的 Cocoa/Objective-C 封装。
Akaibu-NSUserDefaults - Swift 键/值存储，只需要一行代码就可以对 NSObject 对象进行归档。类的属性会自动映射和归档。
FCModel - 为那些喜欢直接使用 SQL 进行数据库操作的人提供的 CoreData 的替代品。
Zephyr - 轻松地通过 iCloud 同步 NSUserDefaults ★
Prephirences - Prephirences 是一个提供了有用的协议和便捷的方法来管理应用的偏好设置，配置和应用状态的 Swift 库。★
加密

AESCrypt-ObjC - 一个简单固执的 AES 加密／解密类，然而它就是可以很好的工作。
硬件

动作

MotionKit - 只需要两行或者很少的几行代码就可以从加速度传感器、陀螺仪和磁力传感器获取数据。现在 CoreMotion 让这些变得前所未有的简单。
 

蓝牙

Discovery - 这是个很简单的库，用来从附近的设备上发现和获取数据（即便 peer app 在后台工作）。
LGBluetooth - 基于 CoreBluetooth 的一个轻量级库，基于 block 制作。它能够让你程序中的 CoreBluetooth 相关的代码更加简洁。
PeerKit 一个用于事件驱动，零配置的 Multipeer 连接应用程序的开源 Swift 框架。★
simple-share - 一个基于蓝牙 LE 共享的框架，易于实现附近设备的连接。
BluetoothKit - 使用 BLE 在 iOS/OSX 设备之间通讯的框架★
位置

IngeoSDK - 总是处于开启状态的 iOS 位置显示框架。
Proxitee - 允许开发者利用 iBeacons 和地理围栏创建近场感知的应用。
LocationManager - 实现了一次性或者持续请求当前位置的功能，提供了基于 block 的异步 API。
LocationKit - 高级位置 SDK － 只使用很少的电量和上下文相关的位置信息就可以提供高精确度的位置数据。
iBeacon

Proxitee - 允许开发者利用 iBeacons 和地理围栏创建近场感知的应用。
OWUProximityManager - 一个方便的 iBeacon + CoreBluetooth 管理器。
Vicinity - 复制邻近的 iBeacons （通过分析RSSI），并支持在后台广播和检测 BLE 设备。
BeaconEmitter - 把你的 Mac 变成一个 iBeacon。
OWUProximityManager - iBeacons + CoreBluetooth.
HUD

MBProgressHUD - 用于显示一个半透明的 HUD。当任务在后台线程结束时可以在上边显示一个指示器和／或者标签。
SVProgressHUD - 一个为你的 iOS 应用制作的简洁，轻量级的进度指示 HUD。
ProgressHUD - ProgressHUD 是一个轻量易用的 HUD。
M13ProgressSuite - 一个包含了很多 iOS 上用于显示进度信息工具的套装。
JHProgressHUD - 一个简单轻量的 Swift 框架，用于在 iOS 应用中显示★
PKHUD - 用 Swift 重新实现了 Apple 的原生 HUD，支持 iOS 8 以上★
CozyLoadingActivity - 轻量的载入动作指示 HUD ★
事件总线

Caravel - 用于 UIWebView 和 JS 的 Swift 事件总线。★
SwiftEventBus - 一个真对 iOS 8 优化的发布／订阅事件总线。★
PromiseKit - iOS 和 OS X 上的 Promises 实现。
Bolts - Bolts 是一个试图使构建移动应用更简单的一个底层库集合。包括了任务（promises）和应用关联（deep links）。
SwiftTask - Swift 实现的 Promise + progress + pause + cancel + retry。 ★
文件

FileKit - Swift 实现的简单快捷的文件管理工具。★
 

JSON

JSONKit - Objective-C JSON 工具。
TouchJSON - 一个 Objective-C 的 JSON 框架。
JSON-Framework - 这个框架用 Objective-C 实现了一个严格的 JSON 解释器和生成器。
Mantle - 面向 Cocoa 和 Cocoa Touch 的模型框架 Model 。
Groot - 实现呃 JSON 字典或者数组和 Core Data Mangement 对象之间的转换。
KZPropertyMapper - 以最少的代码实现数据映射和验证。
JSONModel - 神奇的基于 JSON 的数据模型化框架。创建了一系列敏捷便利，自动并且智能的模型类。
SwiftyJSON - 使用 Swift 处理 JSON 数据的好方法。★
FastEasyMapping - 快速地序列化和反序列化 JSON 数据。
OCMapper - Objective-C & Swift 通用的快速 JSON 模型转化框架。 ★
ObjectMapper - 在模型对象（包括 class 和 struct）和 JSON 之间转换的 Swift 框架。★
JASON - 性能优秀操作便捷的 JSON 解析。★
Gloss - 一个 Swift 写的 JSON 解析库。★
Cereal - Swift 对象序列化 ★
SwiftyJSONAccelerator - 使用 SwiftyJSON 或者 ObjectMapper 根据 JSON 生成 Swift 模型。支持 NSCoding 并且提供了使用 JSON 来表示模型的方法。★
布局

ios-flexboxkit - 一个封装了 Flexbox 布局的简单 UIKit 扩展。
Masonry - 利用简单的，链式的语法发挥出自动布局 NSLayoutConstraints 的强大功能。
FLKAutoLayout - 让使用代码做约束更加简便的 UIView 类别。
Façade - 可编程的视图布局，一个 autolayout 的替代品。
PureLayout - 终极的 iOS 和 OS X 上的 Autolayout API，极其简单又异常强大。同时适用于 Objective-C 和 Swift。
SnapKit - 一个 iOS 和 OS X 的 Swift Autolayout 领域专用语言（DSL）。★
Cartography - 一个 Swift 编写的声明式 Auto Layout 领域专用语言（DSL）。★
AutoLayoutPlus - 给 Auto Layout 加的一点料，由 Swift 驱动。 ★
日志

CleanroomLogger - 一个基于 Swift 可配置可扩展的日志 API，简洁、轻量并且高效。★
CocoaLumberjack - 一个快捷强大灵活的日志框架，可用于 iOS & Mac。
NSLogger - 一个高性能的日志工具，它可以显示运行在 OS X、iOS 和 Android 上客户端应用的踪迹。
Aardvark - 一个高性能日志框架，它使得创建可操作的 bug 报告变得非常简单。
BlockTypeDescription - 在日志记录 block 的时候显示类型签名。
QorumLogs — 为 Xcode 和 Google Docs 设计的 Swift 日志工具。★
地图

Route-me - iOS 开源地图框架
NAMapKit - 允许你在 iPhone 应用使用自定义地图，并尝试模仿 Mapkit 框架的一些行为。
Mapbox GL - 一个 iOS 上使用 OpenGL 渲染 Mapbox 矢量地图块的框架。
CMMapLauncher - 用于 iOS 中在各种地图应用中显示方向的便捷框架。
百度地图iOS SDK：一套功能丰富的地图开发工具包。官网
百度鹰眼轨迹iOS SDK：一套能够进行绑路纠偏的轨迹开发工具包。官网
媒体

图片

GPU Image - 一个基于 GPU 的 iOS 开源的图像和视频处理框架。
UIImage DSP - iOS UIImage 处理功能，它使用 vDSP/Accelerate 框架来提高速度。
QR Code Scanner - 二维码扫描器。
AsyncImageView - UIImageView 的异步图像加载和显示扩展，不会阻塞 UI 线程。
SDWebImage - 异步的图像下载器，提供了缓存支持。以 UIImageView 类别的方式提供。
DFImageManager - 从多种数据源获取图像的现代框架。无需配置，并具有高度的可定制性和扩展性。使用了 NSURLSession。
MapleBacon - 一个 Swift iOS 图像下载和缓存库 ★
NYTPhotoViewer - 抽屉菜单和照片查看器。
IDMPhotoBrowser - 图片浏览器／查看器。
JTSImageViewController - iOS 交互式图片浏览器。
Concorde - 下载和解码连续的 JPEG 图像。
SCRecorder - 类似 Vine 的点击拍摄，动画过滤器，慢镜头，片段编辑相机引擎。
HanekeSwift - 一个 Swift 编写的 iOS 平台的轻量级通用缓存框架，还有对图像的更多支持。★
TOCropViewController - 一个可以允许用户修改 UIImage 对象的视图控制器。
YXTMotionView - 一个自定义的图片视图，它实现了依靠设备运动来滚动图片。
PINRemoteImage - 一个线程安全、高性能、特性丰富的图像获取器。
SABlurImageView - 可以轻松地为图片添加模糊动画效果。★
FastImageCache - 在滚动时快速显示图片的 iOS 框架。
BKAsciiImage - 将图片渲染为 ASCII art 的库。
YLGIFImage - 异步的 GIF 图像解码和图片浏览器。支持 GIF 图动画，但只消耗少量的内存。
AlamofireImage - 一个为 Alamofire 制作的图像组件库。★
Nuke - 高级的图片管理框架。★
FlagKit - 供 app 和 web 页面上使用的漂亮旗标。★
YYWebImage - 异步图像加载框架（支持 WebP，APNG，GIF 格式）。
视频

VIMVideoPlayer - 一个对 AVPlayer 和 AVPlayerLayer 类的简单封装。
MobilePlayer - 一个强大完善且完全可定制的 iOS 媒体播放器。
PDF

Reader - 一个 iOS PDF 阅读器的核心。
UIView 2 PDF - 使用 UIViews （或配合着 XIB）的 PDF 生成器。
消息

LayerKit - 一个对于 Layer 的 iOS 开发组件,。是将消息（文字，照片，视频，数据）添加到移动或 Web 应用中最简单的解决方案。
Twilio - 驱动着现代的交流方式，构建下一代音频与 SMS 应用。
Plivo - SMS API、音频 API 和 全球运营商。
XMPPFramework - 一个 iOS 和 Mac 上的 XMPP 协议通讯框架。
网络

AFNetworking - 一个得心应手的 iOS 和 OSX 上的网络请求框架。
RestKit - RestKit 是一个 iOS Objective-C 框架，是为了让和 RESTful web 服务交互变的简单、快捷、有趣。
FSNetworking - 稳固的 iOS 网络库。
ASIHTTPRequest - Objective-C 编写的 HTTP 网络请求库。它是对 CFNetwork 易用的封装。支持 Mac OS X 和 iPhone。
Overcoat - 小巧但是很强大的库，让创建一个 REST 客户端简便和有趣。
ROADFramework - 面向属性的 web 服务交互方式。框架有内建的 json 和 xml 请求响应序列化方法，十分方便扩展。
MBNetworkMonitor - 苹果 Reachability 类的现代化替代品，使用了 CoreTelephony 来传达更多有关用户网络连接状况的信息。
MBNetworkIndicator - 提供了简单的方式在多个请求之间协调设备网络指示器。
Alamofire - Alamofire 是一个 Swift 写的 HTTP 网络库，由 AFNetworking 的作者编写。★
Transporter - 让上传下载更便捷的小代码库。★
CDZPinger - 使用方便的 ICMP Ping 框架。
NSRails - 将客户端的对象／类映射到远程 REST API 的对象／ORM。
NKMultipeer - 一个建立在多重链接上的可测试的抽象。★
CocoaAsyncSocket - 用于 Mac 和 iOS 的异步 socket 网络库。
Siesta - 优雅的 RESTful 资源抽象，将状态解藕。是基于回调或者代理的网络库的替代品。★
Reachability.swift - 用 Swift 和闭包重新实现了苹果的 Reachablility 框架。★
NetworkEye - 一个 iOS 网络调试库，可以显示 App 中的 HTTP 请求和请求的相关信息。
推送通知

Orbiter - 在 iOS 中注册推送通知。
PEM - 为推送服务器自动生成 profile。
Parse Push - 完全免费的后台推送通知，提供了创建分段，调度甚至 A/B 测试的能力。
Urban Airship - 付费的推送通知后台。
Growth Push - 付费的推送通知。 它是在日本最受开发者喜爱的工具之一。
APNS-Pusher - 苹果推送通知服务的调试器。
Passbook

passbook - 为 Passbook 创建 pkpass 文件。
Dubai - 生成和预览 Passbook 的 Pass。
Passkit - 设计、创建并验证 Passbook 的 Pass。
权限

PermissionScope - 智能的 iOS 授权 UI 和 统一的 API（支持位置、通知、照片、联系人、日历、照片、麦克风、BT、进度指示、HealthKit 和 CloudKit）。★
Proposer - 便捷地请求用户权限（支持相机、照片、麦克风、联系人、位置）。★
ICanHas - 简化 iOS 用户权限请求（支持位置、推送通知、相机、联系人、日历、照片）。★
VWWPermissionKit - 可视化的 iOS 授权管理器。
ISHPermissionKit - 为 iOS 提供请求用户权限的统一方法。
JLPermissions - iOS 预授权工具，开发者用它来制作询问用户是否授权的对话框，支持日历、联系人、位置、照片、备忘录、twitter、推送通知和其他需要授权的操作。
文本

Twitter Text Obj - Twitter 的文本处理库的 Objective-C 实现。
Nimbus - Nimbus 是一个为高级 iOS 软件设计师制作工具包。
NSStringEmojize - 一个将 Emoji 表情符号转换为等价的 Unicode 字串的 NSString 类别。
MMMarkdown - 用于将 Markdown 转换为 HTML 的 Objective-C 静态库。
DTCoreText - 利用 CoreText 使用 HTML 代码的方法。
DTRichTextEditor - 一个 iOS 的富文本编辑器。
NBEmojiSearchView - 一个支持搜索并且可以集成到文本控件中的 emoji 下拉列表视图。
ios-fontawesome - NSString + FontAwesome。
Pluralize.swift - 强大的 Swift String 单数转换复数扩展。★
RichEditorView - RichEditorView 是一个简单、模块化的富文本编辑器视图。★
Money - 为与钱和现金相关工作的的 Swift 值类型。★
PhoneNumberKit - 用于解析，格式化和验证国际电话号码的 Swift 框架，由谷歌的 libphonenumber 库支持。★
YYText - iOS 上用于显示和编辑富文本的强大文本框架。
功能漫游 / 介绍 / 教程

Onboard - 用一点点代码就可以创建一个漂亮的吸附效果的实践。
EAIntroView - 高度可定制非侵入式的欢迎页面解决方案。
MYBlurIntroductionView - 在 MYIntroductionView 上完善的，用于构建可定制的 app 介绍或者教程页面的框架。
BWWalkthrough - 一个自定义 iOS App 的功能漫游页面的框架。★
GHWalkThrough - 一个基于 UICollectionView 的非侵入式介绍页面组件。
ICETutorial - 一个很好的教程框架，类似 Path 3.X 版本的 App 中的样式。
JazzHands - Jazz Hands 是一个简单的 UIKit 关键帧动画框架。动画是可以使用手势、滚动视图、KVO 或者 ReactiveCocoa 来控制的。
RazzleDazzle - 简单的基于关键帧的 iOS 动画框架，由 Swift 编写。最适合用于 App 的滚动介绍页面。★
Instructions - 向你的 iOS 项目中添加自定义的操作方式指导的简单办法。★
SwiftyWalkthrough - 创建一个体验绝佳的功能漫游的最简单方法，Swift 编写。★
URL Scheme

WAAppRouting - iOS 的路由实现。同时处理了 URL 识别和利用控制器显示解析后的参数。全部这些只要一行代码就可以搞定，控制器堆栈还会被自动保留！
DeepLinkKit - 杰出的路由匹配框架，使用基于 block API 处理你的深链接。
IntentKit - 一个便捷的方法来在 iOS app 中处理第三方 URL schemes。
JLRoutes - 使用了 block API 的 iOS URL 路由框架。
UI

Chameleon - 一个 iOS 性能强大的轻量级扁平化颜色框架，可以用于 Objective-C 和 Swift。★
ActionSheetPicker-3.0 - 为 iOS App 快速制作一个下拉 UIPickerView / ActionSheet 功能。
FlatUIKit - 适用于 iOS 的扁平化 UI 组件集合。
JVFloatLabeledTextField - 附有浮动标签的 UITextField 子类。
SSBouncyButton - 有弹性的 iOS7 样式按钮 UI 组件。
BetweenKit - 一个健壮的 iOS 拖拽框架。
JSQMessagesViewController - 一个优雅的 iOS 聊天消息 UI 库。
AMSmoothAlert - 一个很 cool 的 AlertView。
TSMessages - 在屏幕上方显示通知（比如成功、错误、警告或者消息）视图。
NZAlertView - 简单直观的 AlertView。类似推送通知的效果。
MGSwipeTableCell - 可以显示滑动按钮的 UITableViewCell 的子类，还支持多种过渡动画。
ARAutocompleteTextView - subclass of 实时显示文本提示的 UITextView 的子类。完美支持 e-mail 格式。
TGCameraViewController - 基于 AVFoundation 的自定义相机。样式漂亮，轻量并且可以很容易地集成到 iOS 项目中。
ENSwiftSideMenu - 一个 Swift 写的简洁 iOS7/8 侧滑菜单。★
MDCSwipeToChoose - 滑动卡片来决定 "喜欢" 或者 "不喜欢" 的控件，效果类似 Tinder App。可以用于在几分钟内创建识字卡 app，图片浏览器或者其他类似应用，而不用几小时。
ParallaxTableViewHeader - UITableView header 的视差滚动效果组件。
JLToast - iOS 的 Toast 组件，提供了简单的接口。★
SweetAlert - 为 iOS 应用提供了实时动画效果的 AlertView，Swift 编写而成。★
Form - JSON 驱动的列表控件。
BLKFlexibleHeightBar - 创建一个高度可以自动调整的 NavigationBar，类似 Facebook ，Square Cash，Safari 中的那样。
NMPopUpView - 用于显示浮动窗口的简单 iOS 类。支持 Swift 和 Objective-C。★
SDevIconFonts - 用于 Swift 的 Fontawesome, Iconic, Ionicons, Octicon。★
SDevBootstrapButton - Swift 版的 Twitter Bootstrap 按钮。★
SDevCircleButton - Swift 实现的圆型按钮。★
SDevFlatColors - Swift 实现的扁平化颜色。★
ColorArt - 从图片中取出主要颜色，类似 iTunes 11 的效果。
IQKeyboardManager - 防止键盘滑出来遮挡住 UITextField/UITextView 的框架，非侵入，无需代码。
WCFastCell - 滚动流畅的 Tables/Collections cell (没有动画)。
Motif - 一个基于 JSON 的可定制轻量级样式表框架。
VBFPopFlatButton - 基于 Facebook POP制作的，有9种不同状态动画的扁平化按钮。
HTPressableButton - 扁平化设计的可以按压的按钮。
Cool-iOS-Camera - 一个完全可定制的现代的照相机，使用 AVFoundation 框架实现。
AsyncDisplayKit - AsyncDisplayKit 是一个 iOS 框架，它能够使一个很复杂的用户界面保持平滑和反应灵敏。
AMTagListView - 一个可以添加一系列高度可定制化的标签的 UIScrollView 子类。
MotionBlur - MotionBlur 让你可以在 iOS 动画效果上添加模糊效果。
PBJVision - iOS 相机引擎，支持点击拍摄，慢动作视频和图片捕捉功能。
DynamicColor - 又一个用于操作颜色的 Swift 扩展。★
GaugeKit - 可定制的仪表组件，可以方便地仿制苹果样式的仪表盘。★
SVWebViewController - 一个非侵入式的内置浏览器。
SwiftWebVC - 一个 SVWebViewController 的 Swift 实现。★
MVAutocompletePlaceSearchTextField - 一个类似 Google Places，Uber 等位置搜索的非侵入式自动完成控件。
MVMaterialView - 用来模仿 Material Design 概念波纹（Ripple）效果 UI 控件的子类和 UIButton。
Atlas - 为 Layer 设计的原生 iOS 消息应用 UI 组件。
Swift-Prompts - 用来设计自定义提示的 Swift 库，有很大的范围可供选择。★
IQDropDownTextField - 提供了下拉 UIPickerView 支持的 UITextField。
PJAlertView - 苹果弃用了原来好用的警告视图，让我们失去了很多的定制性，这个库重新将定制性带回来。
CZPicker - iOS 的 Popup 样式的 UIPickerView.
TisprCardStack - 卡片 UI 库。★
YXTPageView - 一个支持 UIView 和 UITableView 之间滚动切换的 PageView。
DatePickerDialog - 在 UIAlertView 上显示 UIDatePicker 的 Swift 库。★
gifu - iOS 上支持动态 GIF 的 Swift 框架。★
SAHistoryNavigationViewController - SAHistoryNavigationViewController 实现了一个在 iOS 上的类似任务管理器的 UI，兼容 UINavigationContoller,3D Touch。★
DOFavoriteButton - 一个可爱的动画按钮。★
LNRSimpleNotifications - 简单的 Swift app 内置通知。LNRSimpleNotifications 是一个 Swift TSMessages 简化版本。 ★
NgKeyboardTracker - iOS 的键盘跟踪 Objective-C 库。
SAInboxViewController - 受到 "Inbox by google" 动画过渡效果启发的 UIViewController 子类。★
TLYShyNavBar - 不像那些 UINavigationBar 那么傲慢。这个 Bar 很谦虚！可以很容易地创建自动滚动的 navigation bar。
BRYXBanner - Swift 的 iOS7+ 样式的下拉通知。 ★
NYAlertViewController - 可以自定义内容视图的 iOS AlertView，可高度自定义。
HDNotificationView - 使用模仿原生的通知横幅 UI，发出任何警告。
MZFormSheetPresentationController - MZFormSheetPresentationController 提供了一个原生 iOS UIModalPresentationFormSheet 的替代品，添加了对 iPhone 的支持，并且可以自定义 controller 的尺寸和表单的外观。
AnimatedTransitionGallery - 使用 UIViewControllerAnimatedTransitioning 协议实现了自定义 iOS 7 过渡动画。
iCarousel - iOS 和 Mac OS 上简单的，高度可定制化的数据驱动 3D 跑马灯。
RESideMenu - 受 Dribble 上的设计启发而制作的 iOS 7/8 样式的视差侧滑菜单。
FontAwesomeKit - iOS 的图标字体库，现在支持 Font-Awesome，Foundation icons，Zocial 和 ionicons。
Cocoa Controls - 开源的 iOS 和 OS X UI 组件.
ActiveLabel.swift - 非侵入的 UILabel 替代品，支持 Hashtags (#), Mentions (@) 和 URL (http:// )。 ★
XLForm - XLForm 是最灵活强大的 iOS 库，用来创建动态的 tableview 表单，完全适用于 Swift 和 Obj-C。
RAReorderableLayout - 可以拖拽放置的 UICollectionView 元素。
ESTabBarController - 一个允许高亮按钮和自定义按钮动作的 Tabbar 控制器。
STPopup - STPopup 为 iPhone 和 iPad 提供了一个 popup 样式的 UINavigationController。
HoneycombView - HoneycombView 是用来显示类似 Honyecomb 布局的 iOS UIView，由 Swift 实现。★
tapkulibrary - tap + haiku = tapku, 一个精心设计的 iOS 开源框架。
NVActivityIndicatorView - 很好的加载动画集合。★
KCJogDial - 提供控制功能的 UIView，类似一个转轮控制器。★
PagingMenuController - 有可定制的菜单的分页视图控制器，Swift 实现。★
RadialMenu - RadialMenu 是一个提供了触控的上下文菜单（类似 iOS8 中 iMessage 的录制按钮）的自定义控件。使用 Swift 和 POP 框架构建。★
VLDContextSheet - 类似 Pinterest iOS app 中的菜单。
cariocamenu - 最快的无点击菜单。★
DAExpandAnimation - 以自定义的模态过渡效果，从 cell 中展开来呈现控制器的库。★
ScrollPager - 类似 Flipboard 的滚动翻页。★
ComponentKit - 受到 React 启发的 iOS 框架，Facebook 出品A React-Inspired View Framework for iOS, by Facebook.
Eureka - 使用纯 Swift 构建优雅的 iOS 表单。★
PMTween - 优雅灵活的 iOS 渐变库。
MZTimerLabel - 让 UILabel 变成 倒计时器或者秒表的便利类，类似苹果的时钟应用。
WobbleView - WobbleView 是一个实现了流行的摇晃效果的视图。你可以在应用中方便的添加动态的用户交互和过渡效果。★
CBZSplashView - Twitter 样式的启动页（Splash Screen）视图，缩放后显示主视图。
RKNotificationHub - 让任何 UIView 变成完善的通知中心。
EatFit - Eat fit 是一个受 Google Fit 启发的用于漂亮地展示数据的组件。
CollapsableTable - 可以自定义 section header 的可折叠 tableview section。★
LiquidFloatingActionButton - 流体状态的 Material Design 的浮动按钮。
LiquidLoader - 液体动画的加载器组件。★
PickerView - Swift 实现的自定义的 UIPickerView 替代品。★
InteractivePlayerView - 自定义的 iOS 音乐播放器视图。★
phone-number-picker - 一个 Swift 实现的简单易用的视图控制器，类似 WhatsApp 那样让你输入带有国家代码电话号码。★
DLWBouncyView - BouncyView 是一个为所有视图都实现了最近流行的弹性效果的框架。
MMPopupView - 基于 Pop-up 的视图(例如，AlertSheet)，支持方便地定制。
EXTView - 使用 IB_DESIGNABLE 和 IBInspectable 为 Interface Builder 提供了 UIView 扩展。
JTMaterialSwitch - 一个受 Google 的 Material Design 启发的可定制的开关 UI，有波纹效果和弹性动画。
PickerView - Swift 写的可定制的 UIPickerView 替代品。
KCSelectionDialog - 简单的选择对话框。★
SFFocusViewLayout - 支持内容聚焦的 UICollectionViewLayout。
UITextField-Shake - 添加了摇晃动画的 UITextField 类别。也有 Swift 版本 ★
JTFadingInfoView - 一个基于 UIButton 的支持淡入淡出动画特性的视图。
KCFloatingActionButton - 简洁的 iOS 浮动操作按钮。★
TTGSnackbar - 在屏幕底部显示简单的消息和操作按钮，支持多种动画效果。★
TTGEmojiRate - iOS 的类似 emoji 的评分视图。★
CardAnimation - 卡片翻页动画效果。★
BEMCheckBox - 优雅的 iOS 复选框。(Check box)
CVCalendar - 支持 iOS 8+ 的自定义可视化日历，Swift（2.0）实现。★
SCLAlertView-Swift - Swift 实现的一个漂亮的动画 Alert View。★
Atlas-iOS - Atlas 是一个原生 iOS 对话 UI Layer 组件。
TKRubberIndicator - Swift 版橡胶 PageControl 指示器。 http://tbxark.github.io ★
HorizontalProgress - 简单的动画水平进度条。
TKSwitcherCollection - 一个动画开关集合。http://tbxark.github.io ★
JDSwiftAvatarProgress - 方便自定义的异步加载展位图进度条动画。★
iOS-CircleProgressView - 这个空间允许用户用代码或者 interface builder 初始化或创建并渲染一个圆形的进度条视图。★
Hamburger-Menu-Button - 一个高度可定制的汉堡包菜单按钮。★
DGElasticPullToRefresh - iOS 弹性下拉刷新控件，Swift 实现。★
HTYTextField - 一个有弹性的站位文字的 UITextField。★
JDStatusBarNotification - 显示在顶部状态栏的通知，使用简单，可以自定义。
GuillotineMenu - 铡刀样式过渡动画的下拉菜单。★
MediumMenu - 一个基于 Medium iOS 应用的菜单。★
YALField - 使用 interface builder 更容易地创建表单 UI。包含带合法性验证的自定义字段。
StarryStars - iOS GUI 库，用于显示和编辑评分。
JRSplitVC - 自适应布局的 UISplitViewController。
SevenSwitch - 非侵入式的 iOS7 样式的开关替代品。★
RadialLayer - 可点击元素的动画。★
MPParallaxView - Swift 实现的 Apple TV 视差效果。★
RPLoadingAnimation - Swift 实现的基于 CALayer 的加载动画。★
Splitflap - Swift 应用的分屏显示框架。★
UIScrollView-InfiniteScroll - 支持无限滚动的 UIScrollView 类别。★
PullToBounce - UIScrollView 的下拉刷新控件。★
TVButton - 重新创造一个非常酷的 Apple TV 视差图标用在 iOS UIButton 上（Swift 实现）。★
SlackTextViewController - 一个非侵入式的 UIViewcontroller 子类，提供了一个可以随文字长度变化的大小的文本框和一些其他有用的消息特性。
EZAlertController - 便捷的 Swift UIAlertController。★
EZSwipeController - 类似 Snapchat/Tinder/iOS 主页的 UIPageViewController。★
SWRevealViewController - 受到 FaceBook 和 Wunderlist 应用启发的 UIViewController 子类，用于显示侧滑的视图控制器。
WebSocket

Socket Rocket - 一个一致的 Objective-C WebSocket 客户端库。
代码质量

KZBootstrap - 一系列的脚本和注释，代码质量很差时，在编译时产生额外的错误和警告。
KZAsserts - 一系列的自定义断言，使用 DSL 来自动生成 NSError，允许在 Debug 时断言和在 Release 时捕获错误。
PSPDFUIKitMainThreadGuard - 简洁的代码片段，当 UIKit 在后台线程被使用时生成断言。
Flex - 一个嵌入 iOS App 的调试和探索工具。
chisel - iOS app 的辅助调试工具，提供了一系列的 LLDB 命令。
OCLint - 静态代码分析工具，用以提高代码质量，减少瑕疵。
ocstyle - Objective-C 代码风格检查器。
SwiftLint - 一个实验性的工具，用于强化 Swift 的代码风格和习惯。★
spacecommander - 像一个团队那样，提交完全格式化的 Objective-C 代码。
DWURecyclingAlert - 优化 UITableViewCell 的滚动流畅性。
DCIntrospect - 小型的 iOS 可视化调试工具库。
Watchdog - 一个用于记录阻塞主线程的过重任务的类。★
Tailor - 跨平台的 Swift 代码静态分析器，它帮助你编写更加清洁的代码，避免 bug。
SwiftCop - SwiftCop 是一个很实用的格式验证库，灵感来自 Ruby On Rails 清晰的活动记录验证。★
分析

Flurry Analytics - 免费的 App 分析 API。
Parse Analytics - 测量 App 的使用情况，跟踪 bug 等等。
Mixpanel - 高级分析平台。
Localytics - 将 app 的营销和数据分析结合起来。
Answers by Fabric - 让你实时的洞悉用户体验。
Liquid Analytics - 通过分析和个性化的实时反馈辨认特定的行为。
GTrack - Google Analytics 对 iOS 的轻量级 Objective-C 封装，并且提供了一些额外的功能。
ARAnalytics - 抽象的分析框架，提供了聪明的 API 来跟踪事件和用户数据。
Segment - 将分析继承进 iOS 应用中的简单方式。
支付

Stripe - 将 Apple Pay 支付继承到你的应用中。很适合那些缺少后台知识的开发者。
Braintree - 提供 5 万美金的免费支付额度，需要后台支持。
Venmo - 在你的应用中支持和接受通过 Venmo 的支付。
Moltin - 使用简单的 SDK 为应用添加 eCommerce，你可以创建一个销售产品的商店，不需要后端支持。
生产力

Import.io - 将网页即时转换为数据。
Tapglue - 是用很少的代码来构建社交产品和活动的 feed。
工具

Underscore.m - 用来操作数据的 DSL。
SBConstants - 生成一个包含了 storyboard 中所有 identifier 的常量文件。
XExtensionItem - 方便地在 iOS 应用和分享扩展至简分享数据。
ReflectableEnum - Objective-C 枚举的反射。
VWWPermissionKit - 可视化的 iOS 权限管理器。
ClusterPrePermissions - 可重用的预授权工具，它可以让开发者在对话中获取系统权限之前询问用户。
DateTools - 简便的 Objective-C 日期和时间工具。
EKAlgorithms - 一些知名的计算机科学算法和数据结构的 Objective-C 实现。
Tactile - 安全并且更加合乎习惯的响应收拾和控件事件的方式。★
Colours - 这是一套与定义的颜色和颜色方法，让你的 iOS／OS X 开发更加方便。
ObjectiveSugar - Ruby 风格的 ObjectiveC 附件。
GroundControl - iOS 远程配置。
OpinionatedC - 让 Objective-C 继承更多 Smalltalk 特性。
GCDKit - GCD 的 Swift 简化版。★
SwiftRandom - 随即数据生成器。★
RandomKit - Swift 随机数据生成器。★
Async - Swift 的 GCD 异步派发语法糖。★
YOLOKit - 让方块透过圆洞。
EZSwiftExtensions - 😏标准类型和类是如何工作的。★
安全

UICKeyChainStore - UICKeyChainStore 是一个对 Keychain 的简洁封装。
cocoapods-keys - 一个用来存储环境和应用键值的键值存储。
Valet - 在 iOS 和 OS X 的 Keychain 中安全地存储数据，然而你无需知道 keychain 的具体工作细节。
libextobjc - 一个用于扩展 Objective-C 编程语言的 Cocoa。
Locksmith - 方便 Keychain 使用的强大的 Swift 面向协议库。★
simple-touch - 非常简单的生物识别认证服务（Touch ID）的 Swift 封装。
项目安装

crafter - 这是一个允许你使用自定义的领域专用语言（DSL）语法来配置你的 iOS 项目模版的命令行工具（CLI），使用简单但性能强大。
liftoff - 另一个用于创建 iOS 项目的 CLI。
KZBootstrap - iOS 项目的 bootstrap，目的是高质量的编码。
amaro - 优秀的 iOS 样板。
chairs - 交换你的 iOS 模拟器文档。
依赖 / 包管理

Cocoa Pods - CocoaPods 是一个 Objective-C 项目的依赖管理工具。它拥有成千上万个库，它们可以使你的项目更加优雅。
Xcode Maven - Xcode Maven 插件，它可以将 Xcode 构建过程嵌入 Maven 的生命周期中。
Gradle - Xcode 的 gradle 插件，可以使用 gradle 来构建 iOS 或者 Mac OS X 项目。
Carthage - 简单的分布式的 Cocoa 依赖管理器。★
SWM (Swift Modules) - 一个类似 npm（node.js的包管理器）或者 bower（Twitter 的浏览器的包管理器） 的 Swift 项目的包／依赖管理器，无需使用 Xcode。★
Alcatraz - Xcode 包管理工具.
CocoaSeeds - Cocoa 的 Git 子模块替代品。
测试

测试驱动开发／行为驱动开发（TDD / BDD）

Kiwi - 一个用于 iOS 开发的 BDD 库。
Specta - 轻量级 TDD / BDD Objective-C & Cocoa 开发框架。
Quick - Swift 和 Objective-C 的 BDD 框架。
XcodeCoverage - Xcode 项目代码覆盖率。
OHHTTPStubs - 方便地为你的网络请求做存根（Stub）! 使用网络假数据测试你的 app ，你也可以自定义响应时间，响应代码和响应头！
Dixie - Dixie 是一个开源的 Objective-C 测试框架。用于改变对象的行为。
gh-unit - Objective-C 的测试框架。
UI 测试

CrashMonkey - iOS 平台的 Monkey 测试工具。
appium - Appium 是一个开源自动化测试框架。用于测试原生或者混合 app。
robotframework-appiumlibrary - AppiumLibrary 是一个用于 RobotFramwork 的 appium 测试框架。
Cucumber - iOS BDD 框架。
Kif - 一个 iOS 的函数式测试框架。
Subliminal - 一个保守的 iOS 集成测试框架。
UIAutomation - 一个使用脚本在连接着的设备上测试你的用户界面元素的 JavaScript 库。
ios-driver - 使用 Selenium / WebDriver 测试任何 iOS 原生，混合或者移动 web 应用。
Zucchini - 可视化的 iOS 测试框架。
Remote - 在 Xcode 内部控制你的 iPhone 来做端到端的测试。
其他测试

NaughtyKeyboard - 一个危险字符串的大列表，当用户输入这些字符串使有很大的可能会造成 bug，这是一个用于在你的 iOS 设备上测试你 app 的键盘。
PonyDebugger - 使用 Chrome 开发者工具对你的 iOS app 进行远程网络和数据调试。
ios-snapshot-test-case - 使用屏幕快照的 iOS 单元测试。
Beta 测试版本发布

Crashlytics - 一个崩溃报告和 beta 测试服务。
TestFlight Beta Testing - iTunes Connect 支持的 beta 测试服务。
HockeyApp - 在 HockeyApp 你可以发布你 app 的 beta 测试版本，收集实时的崩溃报告，获取用户反馈，分析测试覆盖率。
boarding - 即时为 TestFlight beta 测试者创建简单的注册页面。
工具链

RubyMotion - RubyMotion 是一个革命性的工具链。它可以让你快速地开发和测试原生 iOS 和 OS X 应用，全部使用 Ruby 语言。
工具

Shark - 用于将 .xcassets 文件夹转换成一个类型安全枚举的 Swift 脚本。★
R.swift - 在 Swift 项目中，强类型的自动补全资源名称的工具，包括图片，单元格和 segue 的工具。★
SwiftGen - 一个生成 Swift 代码工具的集合（生成资源的枚举，storyboard，本地化字符串和 UIColor）。★
Localize-Swift - Swift 2.0 实现在应用中切换语言的功能，帮助你的 APP 实现友好的本地化和国际化。★
Blade - 为 iOS 和 OS X 应用生成 Xcode 图片目录，全局图片和其他相关的东西。
Retini - 一个超级简单的 Retina（2x，3x）图片转换器。
Provisioning - 一个查看器插件，用于预览 .mobileprovision 文件。
Strsync - 自动翻译并且使 .strings 文件和默认语言同步。
快速开发

KZPlayground - Objective-C 版本的 Playground。
dyci - 代码注入工具。
injectionforxcode - 代码注入，支持 Swift。
MMBarricade - 在运行时为 iOS app 配置本地服务器。
NetworkObjects - 根据你的 Core Data 模型生成 RESTful 服务器。
STV Framework - 开发原生 iOS app 的可视化开发工具。
部署

fastlane 将所有 iOS 部署工具整合到一个工作流中。
deliver 部署截屏，app 元数据和 AppStore app 更新，这一切只需要一个命令就可以搞定。
snapshot 自动地创建全部语言和全部设备的屏幕截图。
App Store

Average App Store Review Times 这个网站可以同时跟踪 AppStore 上 iOS 和 Mac 两个版本的浏览次数，使用了利用 iOS 和 Mac 开发者的众包数据。
Apple's Common App Rejections Styleguide 一些导致 app 被苹果拒绝的重要常见问题。
Free App Store Optimization Tool 在关键字和竞争者的角度上，让你可视化地追踪你的 App Store 数据。
SDK

官方的

Spotify Spotify iOS SDK。
Facebook Facebook iOS SDK。
Google Analytics Google Analytics iOS SDK。
Paypal iOS SDK The PayPal 移动端 SDK，可以简便地在本地应用中集成 PayPal 和 信用卡支付。
Pocket 将东西保存到 Pocket 的 SDK。
Tumblr 集成 Tumblr 数据到 iOS 或 OS X 应用中的库。
Evernote Evernote iOS SDK。
Box Box iOS 和 OS X SDK API。
OneDrive Live iOS SDK。
Stripe iOS and OS X Stripe 绑定框架。
Venmo 在你的 iOS app 通过 Venmo 生成订单并且接受支付。
AWS Amazon Web Services iOS 移动应用 SDK。
Zendesk Zendesk iOS 移动应用 SDK。
Adobe Creative SDK Adobe creative tools 和 Creative Cloud SDK。
Dropbox Drop-ins 和 Dropbox Core API 的 SDK。
Fabric by Twitter iOS 的 Fabric Twitter Kit。
Liquid Analytics 通过分析与实时的个性化的实时响应产生特定的行为。
ResearchKit ResearchKit 是一个开源的软件框架，用它可方便的构建医疗研究应用或者其他的研究项目。
PacketZoom PacketZoom iOS SDK。
Primer - 在可视化编辑器上方便创建定制化的登陆页，注册和登录流程的 SDK，内建了 a/b/n 测试和分析。
非官方

STTwitter 为 Twitter REST API 1.1 制作的稳定，成熟，全面的 Objective-C 库。
FHSTwitterEngine 为 Cocoa 开发者提供的 Twitter API。
Giphy Giphy API 的 Objective-C iOS 客户端。
UberKit - Objective-C 包装的简单易用的 Uber API。
InstagramKit - Instagram iOS SDK。
DribbbleSDK - Dribbble iOS SDK。
objectiveflickr - 对象化的 Flickr， Objective-C 写的 Flickr API。
DropletKit - Objective-C 包装的 DigitalOcean v2 API。
Xcode

插件

FuzzyAutocompletePlugin - 提供了除前缀匹配之外的其他更加灵活的自动补全功能，支持 Xcode 5+。
SCXcodeMiniMap - SCXcodeMiniMap 为 Xcode 添加了代码地图功能
Show in Github - 可以直接打开 Github 上当前正在编辑的行对应的 commit 页面。
BBUFullIssueNavigator - 这个插件让 Xcode 在 issue 导航栏显示所有的 issue 内容。
BBUDebuggerTuckAway - 当你开始编辑的时候帮你隐藏调试器栏的 Xcode 插件。
SCXcodeSwitchExpander - SCXcodeSwitchExpander 是一个可以帮你展开 switch 语句的插件，还会自动帮你插入 case 语句。
VVDocumenter-Xcode - 方便的编写标准注释的 Xcode 插件。
XAlign - 一个 Xcode 代码自动对齐插件，它可以使用自定义的模式来对齐任何东西。
Cocoapods Xcode Plugin - 依赖管理工具 CocoaPods 的 Xcode 插件。
KSImageNamed-Xcode - 提供了图片名称自动补全功能的插件。
ColorSense-for-Xcode - 可视化的颜色选择插件。
Backlight-for-XCode - 高亮当前编辑的行。
UIColor-Hex-Swift - 通过十六进制字符串创建 autorelease 颜色的便利方法。★
KPRunEverywhereXcodePlugin - 只需一次点击，就可以在多个 iOS 设备上构建，运行 App。
RevealPlugin - 将 Reveal App 和你的项目自动合为一体的 Xcode 插件。
RealmPlugin- 生成 Realm 模型的 Xcode 插件。
AdjustFontSize - 使用 ⌘ + / ⌘ - 快捷键调整字体大小。
Lin - 这个插件提供了 NSLocalizedString 的自动补全插件。
Rephrase - Xcode 用于本地化的插件.
XCActionBar - Xcode 的 Alfred。
QuickJump - Xcode 快速代码导航。
CATweaker - 一个用于创建漂亮的 CAMediaTimingFunction 曲线的插件.
XcodeWay - 便捷地导航到多个地方。
GitDiff - 将与 git 仓库中不同的代码高亮。
MCLog - 用于控制台内容筛选的插件。
XToDo - 一个显示项目中 TODO，FIXME，??? 和 !!! 列表的对话框。
CopyIssue - 使复制 Xcode issuse 描述更简单。
RTImageAssets - 自动生成所需的全部 App 图标的插件。
BBUncrustifyPlugin-Xcode - 使用 ClangFormat 或 Uncrustify 格式化代码的插件。
Aviator - 这个插件将 AppCode 的 ⇧⌘T (source/test 切换) 带到 Xcode 中.
JumpMarks - 使用有序的书签为你的代码做导航。
XCSnippetr - 直接上传代码片段到 Slack 和 Gist 的 Xcode 插件。
Peckham - 使用 #import 引用项目中的任何文件，提供代码提示。
MLAutoReplace - 快速编码以及代码格式化插件，提升你的编码速度。
Chameleon - iOS （Obj-C & Swift）的扁平化颜色框架。★
AutoHighlightSymbol - 高亮被选中的符号对应的所有实例。
Reveal-In-GitHub - 用一个快捷键就可以跳转到 GitHub 仓库的 History, Blame, PRs, Issues, Notifications。
CleanHeaders-Xcode - 类似 iSort 的头文件排序和重复消除插件，让你的头文件看起来更加有序。
Luft - 帮助你实现轻量的 View Controller 的 Xcode 插件。
主题

Dracula Theme - 一个 Xcode 的暗色主题（仿 SublimeText）.
Xcode themes list - Xcode 的多彩主题。
Solarized-Dark-for-Xcode - 用于 Xcode5 的 Solarized Dark 主题.
其他 Xcode 插件

Synx - 一个重新组织你的 Xcode 项目的命令行工具，它能够让你的 group 和文件夹对应起来。
dsnip - 可以在本地为所有的 UIKit 协议／代理方法（UITableView,...）生成 Xcode 代码片段的工具。
编码规范

NY Times - Objective C Style Guide - 纽约时报使用的 Objective-C 编码规范。
raywenderlich Style Guide - 一个描述 raywenderlich.com 编码习惯的代码规范。
Github Objective-C Style Guide - Objective-C 项目的编码规范和惯用法。
Objective-C Coding Convention and Best Practices - 一份描述编码习惯的 Gist。
Swift Style Guide by @raywenderlich - raywenderlich.com 官方的 Swift 编码风格规范。★
Spotify Objective-C Coding Style - Spotify 的 iOS 开发指导。
Dropbox Objective-C Style Guide - Dropbox 的 Objective-C 代码风格指南。
Github - Style guide & coding conventions for Swift projects - github 的 Swift 编码风格和习惯指南。★
Futurice iOS Good Practices - @futurice 介绍的 iOS 入门指南和最佳实践。
好网站

中文站点

伯乐在线 iOS 频道：分享 iOS 和 Swift 开发，应用设计和推广，iOS 相关的行业动态。官网
英文站点

### 新闻，播客和其他
BGR
iMore
Lifehacker
iCode Blog
NSHipster
Objc.io
ASCIIwwdc
Natasha The Robot
Apple's Swift Blog ★
iOS Programming Subreddit
iOS Dev Weekly
iOS8-day-by-day ★
iOScreator ★
Mathew Sanders ★
Little Bites of Cocoa ★
iOS Dev Nuggets ★
This Week in Swift ★
iOS Goodies
iOS Developer and Designer interview - 一个用于帮助那些寻找 iOS 开发者或设计师的雇主的小指南。
iOS App Development on Medium - 一些关于 iOS，AppleWatch 开发的小故事和小贴士。
Swift Sandbox - Swift 开发者通讯，Swift 开源新闻，项目和资源。 ★
UIKit 文档

iOS Fonts
UIAppearance list
论坛和讨论列表

iPhone Dev SDK Forum
"iOS" on Stackoverflow
教程和 Keynotes

AppCoda
Tutorials Point
Code with Cris
Cocoa with Love
Cocoa is my Girlfriend
Code School - Try Objective-C
Brian Advent youtube channel - Youtube 上的 Swift 教程频道。 ★
RAYWENDERLICH - 开发者和爱好者的教程。
Ry’s Objective-C Tutorial
Mike Ash
Big Nerd Ranch ★
Tuts+ ★
iOS-Blog ★
Thinkster ★
Swift Education - 一个供教育者分享 Swift 和 app 开发学习材料的社区。★
Cocoa Dev Central
Use Your Loaf
Swift Tutorials by Jameson Quave ★
iOS UI 模版

App Icon Template
iOS 8 GUI PSD Template
iOS UI Design Kit
iOS Design Guidelines
原型

FluidUI
Proto.io
Framer
Pixate
Principle
微博、微信公众号

* iOS大全 微博：[@iOS大全](http://weibo.com/u/5314643524) * iOS大全 微信：分享 iOS 应用开发相关行业动态、技术文章、工具资源、App 设计与推广、热门课程、高薪职位和经典书籍等。 


Twitter

@objcio
@nshipster
@CocoaPods
@CocoaPodsFeed
@RubyMotion
@SwiftSandbox - Swift 开源新闻, 项目和资源。
Facebook 群组

HH iOS
Sketch - Official group
Design-Code
Sketch-Design.io
Origami Community
Framer JS
播客

The Ray Wenderlich Podcast
Debug
iDeveloper
App Story
Mobile Couch
iOS Bytes
书籍

Programming with Objective-C by Apple
Object-Oriented Programming with Objective-C by Apple
The Swift Programming Language by Apple ★
Using Swift with Cocoa and Objective C by Apple ★
iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway
Programming in Objective-C by Stephen G. Kochan
Your First iOS App by Ash Furrow
The Complete Friday Q & A: Volume 1
Core Data for iOS: Developing Data-Driven Applications for the iPad, iPhone, and iPod touch
Cocoa Design Patterns
其他优秀的列表

你可以在下面找到其他十分优秀的列表

awesome-awesomeness 列表。
Open Source apps 开源 iOS app 列表。
优秀的 Swift 列表
@matteocrippa - 一个优秀的 Swift 资源合集列表。
@Wolg - 一个很棒的 Swift 框架，库和软件的策划列表。
awesome watchkit apps watchkit app 例程和教程的列表。▲
iOS Learning Resources 一个高质量，频繁更新并且被很好维护的 iOS 教程网站的完整集合。
awesome-ios-animation - 包括了 Objective-C 和 Swift 实现的 iOS 动画库列表。
awesome-ios-chart - 很棒的 iOS 图表库列表。包括了 Objective-C 和 Swift 两种语言。
awesome-gists - 很棒的 Gist 列表 (iOS 章节).
awesome-ios-ui - 优秀的 iOS UI/UX 库列表。
ios 学习站点

CocoaChina 苹果开发中文站 - 最热的iPhone开发社区 最热的苹果开发社区 最热的iPad开发社区
AppCoda Community - Learn iOS Programming and Build iPhone App
iOS App Development — Medium
Code4App-iOS开发-iOS 开源代码库-iOS代码实例搜索-iOS特效示例-iOS代码例子下载
Custom Controls for iOS and OS X - Cocoa Controls
开源中国 - 找到您想要的开源项目，分享和交流
App开发日报 | app.memect.com | 好东西传送门出品流
NSHipster
objc中国
Ray Wenderlich | Tutorials for iPhone / iOS Developers and Gamers
DevDiv开发者社区，为移动设备、移动互联网、云计算、HTML5等技术人员提供专业技术交流与服务平台
<<码农周刊>>干货精选（Android + iOS 篇） - 孢子社区 : 一起玩，不孤单
博客园 - 开发者的网上家园
CSDN.NET - 全球最大中文IT社区，为IT专业技术人员提供最全面的信息传播和服务平台
Stack Overflow
##中文 iOS/Mac 开发博客列表 博客地址 | 博客地址 | 博客地址 | 博客地址 ----- | ----- | ----- | ----- OneV's Den | 破船之家|技术哥的博客 |Luke's Homepage NSHipster | Limboy 无网不剩| Kenshin Cui's Blog|萧宸宇 Lex Tang | 唐巧的技术博客|Why's blog - 汪海的实验室|摇滚诗人 念茜的博客 | Xcode Dev | Chun Tips | 克伟的博客 Ted's Homepage|txx's blog|里脊串的开发随笔 |Yuan博客 |会写代码的猪 Kevin Blog | 阿毛的蛋疼地 | 煲仔饭 |王中周的技术博客 亚庆的 Blog | Nonomori | 猫·仁波切 | Shining IO 言无不尽 |Wonderffee's Blog|不掏蜂窝的熊 | Travis' Blog I'm TualatriX | Cocoabit|玉令天下的Blog| I'm Allen nixzhu on scriptogr.am | 不会开机的男孩 | 码农人生 | YIFEIYANG--易飞扬的博客 Nico |阿峰的技术窝窝 |hello it works| Lancy's Blog answer_huang |webfrogs | KooFrank's Blog |代码手工艺人

ios 开源项目集合

Github-iOS开源项目集合
常用第三方库
ios 功能模块

网络模块AFNetworking
进度条MBProgressHUD
轻量级iOS开发框架nimbus
仿微信聊天JLWeChat
基于xmpp聊天的开源框架xmppframework
360度全景展示
ios 开发语言

swift学习
Swift学习资源

Swift

最新内容请查看Wiki

苹果公司在WWDC 2014上宣布了他们将会推出一款新的编程语言，面向iOS和OS X系统的开发人员，这个新的语言被命名为Swift。

Swift在iOS 8发布的时候推向市场，用来取代现有的Objective-C语言，对于这个巨大的决定，苹果公司的解释是Swift速度更快，使用起来更加容易。在Swift推出之后，苹果公司应该也不会停止对Objective-C的支持，开发工具会同时支持两种语言。

官方文档及示例

官方文档

目前唯一的完善的文档是官方发布的《The Swift Programming Language》，是名副其实的Swift圣经。目前官方只提供iBooks版本，网友们制作了其它格式的文档可供下载。

《The Swift Programming Language》

苹果官方版本
Kindle/EPUB/PDF版本（百度盘）
Swift介绍 Introducing Swift

WWDC2014 Videos

非官方文档与社区（英文）

初级话题

StackOverflow上的Swift讨论

github上的swift内容 search结果

Swift Cheatsheet

Swift & Cocoapods How to integrate Cocoapods into a vanilla Swift project

Swift Toolbox

Developing iOS Apps Using Swift Tutorial

7 thoughts on “Swift: Not quite there, but too far gone too”

Swift Impressions by Evan Miller

Swift Tutorial – Developing iOS 8 Apps by Jameson Quave 很完整的学习文档

An Absolute Beginner’s Guide to Swift和Understanding Optionals in Swift by Amit Bijlani

Swift Cheat Sheet and Quick Reference by Ray Wenderlich

Generics in Swift

How to use the Swift REPL language shell – Swift programming from the command line

How to write a minimal WebKit browser in 30 lines of Swift

Swift Initializers

Create the Game of Life using Swift and SpriteKit

Composing functions in Swift

Advanced Swift

We ❤ Swift

LEARNABLE PROGRAMMING Designing a programming system for understanding programs

把《The Swift Programming Language》读薄 by Hawstein

深入话题

Swift Operators by Mattt Thompson
Beginning Core Image in Swift
Multiple Animations by David Rönnqvist
The Case for Message Passing in Swift by Michael Buckley
The Core Data stack in Swift by Marcus Zarra
How to Make a Game Like Candy Crush with Swift Tutorial: Part 1 and Part 2 by Matthijs Hollemans
Build custom simulators by Erica Sadun
CloudKit: Moves like Azure by Tom Harrington
about Error handling by Chris Cieslak
Inside Swift
List of implicitly defined variables in Swift 和 Swift Standard Library: Documented and undocumented built-in functions in the Swift standard library – the complete list with all 74 functions by practicalswift
Swift’s Weird Handling of Basic Value Types and AnyObject
Creation of pure Swift module by Alex Denisov. make a logging library and shows us how to document classes in Xcode.
How to write unit tests in Swift with XCTest
gesture recognizer
Swift Language Highlights: An Objective-C Developer’s Perspective
Swift Sequences and lazy evaluation
SPACESHIP OPERATOR IN SWIFT 和 REGULAR EXPRESSIONS IN SWITCH STATEMENTS by Venkat Peri
博客与翻译（中文）

有网友第一时间开始了官方文档的翻译工作，相信近期将由更多文档和教程出现。

社区

https://www.v2ex.com/go/swift
http://swift.sh
http://swift-china.org
CocoaChina的Swift讨论区
QQ群
iOS开发者-开始Swift，群号：32958950，申请时请说明身份。
翻译

《The Swift Programming Language》中文版 （协作翻译)）第一份完整的中文翻译

《Apple Swift编程语言入门教程》比较早期的一篇翻译，最近没有更新

评论

《关于 Swift 的一点初步看法》 by onevcat
《行走于 Swift 的世界中》 by onevcat 更详细的一篇评论
《来自苹果的编程语言——Swift简介》
课程

《SwiftV课堂》 免费Swift学习视频
《Apple Swift语言基础教程》极客学院
官方示例

Apple同时发布了3个示例程序，用于初窥Swift开发的项目。

Lister: A Productivity App Built in Swift apple / github

UICatalog: Creating and Customizing UIKit Controls in Swift apple / github

Adventure: Building a SpriteKit Game Using Swift apple / github

GestureRecognizers: Using standard UIGestureRecognizers in Swift apple / github

非官方代码分享

Swift Trending

FlappySwift 用Swift实现的FlappyBird

swift-2048

PNChart-Swift 可以创建图表的库

Game of Life 一个游戏

swift-alarm 基于地理位置的提醒工具 blog

SwiftNote

翻翻看 游戏翻翻看Swift版

HackerNews HackerNews网站的第三方客户端

SwiftWeather 一个天气客户端

SwiftSingleton

Swift: Spiroswiftograph a cool example of what you can do in the Playground

UIImageView-BetterFace-Swift 展示图片是加入面部识别，改善展示效果

YYHRequest-Swift 异步HTTP请求类

Noah’s Ark, in Swift is a funny example of unicode support

Cartography is an excellent example of what could be achieved with operator overloading. If you don’t like writing Autolayout constraints you should definitely check it out.

Dollar is a Swift library that provides useful functional programming helper methods without extending any built in objects. It is similar to Lo-Dash or Underscore in Javascript.

swifter Tiny http server engine written in Swift programming language.

SwiftyJSON

Agent Minimalistic Swift HTTP request agent for iOS and OS X

开发工具

xcode 6 下载

xcode 6 安装系统要求为MacOSX 10.9.3+

http://pan.baidu.com/s/1dD2AJ3j

xcode_6.0.1.dmg http://pan.baidu.com/s/1sjNQY1B

xcode_6.dmg http://pan.baidu.com/s/1jGoTsWm_

xcode_6_beta_6.dmg http://pan.baidu.com/s/1dD3qeOT

xcode_6_beta_4.dmg http://pan.baidu.com/s/1pJ0nkJx

xcode_6_beta_3.dmg http://pan.baidu.com/s/1nt0WS8T

其它

iOS Developer Library

Chris Lattner Swift设计者

iOS 7.1 to iOS 8.0 API Differences

App Extensions Increase Your Impact

Swift学习资源 新手的Swift学习资料汇总，比较详细总结了常用的资源。

因为重名躺枪的Swift

Swift Lang 一门很专业的并行编程语言，有苹果在Swift页面的链接，肯定带过去很多访问量。

OpenStack Swift OpenStack Object Storage (Swift)。

Swift聊天工具 基于XMPP的聊天工具及服务端SDK。

Taylor Swift 美国乡村音乐女創作歌手、吉他歌手、演员。这位1989年出生的美女获得过数不清的格莱美奖及其它排行榜大奖。2014/05/30刚举办了泰勒•斯威夫特“红”巡演上海演唱会。WWDC2014之后三天，她从Google搜索结果首页被挤出，很受伤，歌迷们也很受伤。去脸盆网关注她，去音悦台听她的歌。

讨论区

【iOS开发者-开始Swift】QQ交流群32958950 申请时请说明身份。

# zebra-sdk-android-origin
[![](https://jitpack.io/v/priscilla-c/zebra-sdk-android-origin.svg)](https://jitpack.io/#priscilla-c/zebra-sdk-android-origin)

| 标题 |  释义 |
| --- | --- |
| [UI](#UI) | 与界面UI相关的代码，某些特殊的 需要重新绘制的 View ，以及一些系统弹窗，如：PopupWindow、AlertDialog、Toast、SnackBar等 |
| [MEDIA](#MEDIA) | 涉及到系统应用的代码，比如：相机、响铃、通知、录音以及音视频编码相关的处理代码比如：H264、I420、Nv21、Nv12、Yv12、AAC、PCM|
| [DATA](#DATA) | 与数据持久化的代码，比如SharedPreferences，MMKV之类的键值对存储，GreenDao、ObjectBox之类的数据库框架  | 
| [RESTS](#RESTS) | 其他功能性的代码，比如图片加载、网络请求、数据转换、格式转换、样式转换、类型转换 |
| [~~FRAMEWORK~~](#~~FRAMEWORK~~) | 模块级的代码，适用于某个小功能块的直接移植 | 
| [~~SECURITY~~](#~~SECURITY~~) | 应用安全相关类的代码 |

## 使用说明
    
## UI
## MEDIA
### 扫码
    功能入口：com.android.origin.media.core.Scan
## DATA
### 对象存储(预初始化)
    一个轻量级的注入框架
    功能入口：com.android.origin.data.kInject.core.Kinit
## RESTS
## ~~FRAMEWORK~~
## ~~SECURITY~~
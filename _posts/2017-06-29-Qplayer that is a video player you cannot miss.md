---
layout: post
title: "QPlayer一款你不容错过的视频播放器"
header-img: "img/post-bg-qplayer.png"
author: "dyf"
date: 2017-06-29
tag: iOS
---

## QPlayer

[QPlayer](https://github.com/dgynfi/QPlayer)是一款你不容错过的视频播放器，支持 `M4V、WMV、MP4、MOV、AVI、MKV、MPEG、MPG、FLV、RM、RMVB、MP3` 等主流媒体格式。输入任何 `HTTP、RTMP、RTSP、HLS` 地址播放网络流或直播。`QPlayer` 使用 `ffmpeg`，支持 `WiFi` 文件传输。聚合了多个直播、视频和短视频平台，可在线观看直播、视频和短视频。(`QPlayer` is a video player that you can't miss, supports `m4v, wmv, 3gp, mp4, mov, avi, mkv, mpeg, mpg, flv, rm, rmvb, mp3` format. Enter any `HTTP, RTSP, RTMP, HLS` address play network streaming or live. QPlayer use ffmpeg，you can transfer files via wifi. It aggregates several live, video and short video platforms, and you can watch live, video and short video online. )

## Disclaimer

部分资源和内容来源于互联网，如涉及版权和法律法规问题，就请给提 issue 或者发送 email 联系本人。

## Usage

在 `App` 设置中打开 `WiFi` 文件传输的开关，即可享用 WiFi 文件传输服务。在电脑浏览器中访问：如 “[http://192.168.6.6:8888](http://192.168.6.6:8888)”，打开网页后，选择文件，点击 `Upload` 上传。在上传媒体文件时，确保电脑和手机在同一 `WiFi` 环境并且不要关闭本应用也不要锁屏。

PS：建议使用PC浏览器（ Safari [Mac], Microsoft Edge [Win10], Google Chrome [Mac Win10] ）

## Group (ID:614799921)

![614799921](https://dgynfi.github.io/img/qrcode/g614799921.jpg)

## Preview

- Local videos

![local_video.png](https://dgynfi.github.io/img/qplayer-preview/local_video.png)

- TV and radio

![tv_radio.png](https://dgynfi.github.io/img/qplayer-preview/tv_radio.png)

- Lives 

![live_web.png](https://dgynfi.github.io/img/qplayer-preview/live_web.png)

- Web videos

![web_video.png](https://dgynfi.github.io/img/qplayer-preview/web_video.png)

## Requirements

iOS 8.0+, iPhone and iPad, Xcode10+.

## Open Source Components

- [AFNetworking](https://github.com/AFNetworking/AFNetworking)

A delightful networking framework for iOS, macOS, watchOS, and tvOS. 

- [SDWebImage](https://github.com/SDWebImage/SDWebImage)

This library provides an async image downloader with cache support. For convenience, we added categories for UI elements like UIImageView, UIButton, MKAnnotationView.

- [ijkplayer](https://github.com/bilibili/ijkplayer) 

Android/iOS video player based on FFmpeg n3.4, with MediaCodec, VideoToolbox support. 

[IJKMediaFramework.framework Download](https://pan.baidu.com/s/1WCZzdCUiaQL3a1yJSD22QQ) - 链接: `https://pan.baidu.com/s/1WCZzdCUiaQL3a1yJSD22QQ` 提取码: mxqq

- [MBProgressHUD](https://github.com/jdg/MBProgressHUD)

MBProgressHUD is an iOS drop-in class that displays a translucent HUD with an indicator and/or labels while work is being done in a background thread. The HUD is meant as a replacement for the undocumented, private UIKit UIProgressHUD with some additional features.

- [MJRefresh](https://github.com/CoderMJLee/MJRefresh)

An easy way to use pull-to-refresh.

- [FDFullscreenPopGesture](https://github.com/forkingdog/FDFullscreenPopGesture)

A UINavigationController's category to enable fullscreen pop gesture with iOS7+ system style.

- [PYSearch](https://github.com/ko1o/PYSearch)

🔍 An elegant search controller which replaces the UISearchController for iOS (iPhone & iPad) .

- [CocoaWebResource](https://github.com/robin/cocoa-web-resource)

A file transfer solution for iPhone and iPod Touch. Support uploading, download and delete files via browser.

- [ZFPlayer](https://github.com/renzifeng/ZFPlayer)

Support customization of any player SDK and control layer(支持定制任何播放器SDK和控制层)

- [KSYMediaPlayer_iOS](ttps://github.com/ksvc/KSYMediaPlayer_iOS)

金山云iOS播放SDK（KSYUN Live Streaming player SDK），支持RTMP HTTP-FLV HLS 协议（supporting RTMP HTTP-FLV HLS protocol）。与系统播放器MPMoviePlayerController接口一致，可以无缝快速切换至KSYMediaPlayer；本地全媒体格式支持, 并对主流的媒体格式(mp4, avi, wmv, flv, mkv, mov, rmvb 等 )进行优化；支持广泛的流式视频格式, HLS, RTMP, HTTP Rseudo-Streaming 等；低延时直播体验，配合金山云推流sdk，可以达到全程直播稳定的4秒内延时；实现快速满屏播放，为用户带来更快捷优质的播放体验；支持画面旋转，音量调节等各种功能。

- [SVBlurView](https://github.com/TransitApp/SVBlurView)

SVBlurView is a simple reimplementation of FXBlurView for iOS 7. It uses Apple's UIImage+ImageEffects category as well as the new drawViewHierarchyInRect: UIView API. It doesn't do dynamic blurs yet.

- [MBProgressHUD-JDragon](https://github.com/lyc59621/MBProgressHUD-JDragon)

封装MBProgressHUD的一个类别。

## Pods for QPlayer

```
# Pods for QPlayer
pod 'AFNetworking'
pod 'SDWebImage'
pod 'MJRefresh', '~> 3.1.12'

pod 'ZFPlayer'
pod 'ZFPlayer/ControlView'
pod 'ZFPlayer/AVPlayer'
#pod 'KSYMediaPlayer_iOS/KSYMediaPlayer_vod' # Conflicts with ijkplayer.

pod 'MBProgressHUD+JDragon', '~> 0.0.3'
pod 'PYSearch', '~> 0.8.8'
pod 'SVBlurView', '~> 0.0.1'
pod 'FDFullscreenPopGesture', '~> 1.1'
```
# show_video_fps

其实，命令行的mediainfo，ffplay,甚至在线播放的都可以看到流的详细的信息，但是那些看多的多是header，metadata，客户端拉到多少FPS是看不到的，所以需要一个播放器把它真正播出来的流的FPS显示出来的播放器，所以我拿ijkplayer改了一下界面，这个app打开直接就是个输入框输入流地址即可，也可以选择本地的视频文件哦！

利用播放端，显示出拉到的流时候的FPS信息，这样子才是最真实的流FPS信息。

	当然，除了FPS，播放界面也可以显示其他信息，设置一下即可显示。

## 1.直接下载APK测试 


![二维码](https://github.com/weizongwei5/show_video_fps/blob/master/otherfile/5d013a9ebe64352c7ab03f380961df11.png?raw=true)

apk打开之后入口里面，有输入流地址的输入框。 或者 ： [直接下载](https://github.com/weizongwei5/show_video_fps/raw/master/otherfile/release1.0.apk)


## 2.使用成熟的推流器对比测试推流问题

在直播项目开发中，难免要遇到我们自己的主播的各种问题，但是又找不到原因，比如慢卡，猜测问题的时候猜测播放器，CDN,WIFI，推流器问题。在我们自己开发推流器的时候，遇到线上问题，也很难定位是不是我们推流器的问题。所以，需要一个第三方的成熟的推流器来定位问题。我们选用 Broadcast me来对比，如果braodcast me 也有问题那么就排除推流器的问题。

所以，这里我上传了一个Broadcast me的APK包，因为，国内的应用宝，豌豆荚都没有下载。

![Broadcast Me 二维码](https://github.com/weizongwei5/show_video_fps/raw/master/otherfile/broadcastme_qrcode.png)
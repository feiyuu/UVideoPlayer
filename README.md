# UVideoPlayer
原生播放器。封装mediaplayer，在UniversalVideoView基础上优化。

问题详见博客：

用原生mediaplayer的一些坑，加载缓冲过程黑屏，有声音没画面
https://blog.csdn.net/m0_38058826/article/details/88350846

视频播放播放，原生mediaplayer和ijkplayer
https://blog.csdn.net/m0_38058826/article/details/88239127

Step1. Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.feiyuu:UVideoPlayer:Tag'
	}

使用代码详见demo

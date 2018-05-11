# ijkPlayerDemo
ijkPlayer编译后的纯净版本

加了几个可用的测试url  
http://live.appwuhan.com/4tzb/playlist.m3u8  
http://live.appwuhan.com/5tzb/playlist.m3u8  
http://live.appwuhan.com/6tzb/playlist.m3u8  
rtmp://live.hkstv.hk.lxdns.com/live/hks

另外编译好后的项目，各cpu的代码都是分开的，官方代码里是把所有的cpu library关联上，我把armv7a,arm64等这些library里编译好的.so文件都放到了ijkplayer-java下，主项目只需要关联这一个library。
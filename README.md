# flowplayer_hls_flash
在线hls  m3u8播放器flash


为了方便修改，就没多写

第41、42的m3u8的地址为直播地址可以修改

第41行的url、第42行的ipadurl
clip: {
	accelerated: true,
	url: "http://125.88.92.166:30001/PLTV/88888956/224/3221227698/1.m3u8",
    ipadUrl: "http://125.88.92.166:30001/PLTV/88888956/224/3221227698/1.m3u8",




更多直播源：https://github.com/sysorem/m3u8-playlist-for-hls




使用：
这个必须以web的形式访问、直接吧index.html用浏览器打开是不行的

windows下可以直接打开netbox.exe, 然后浏览器回自动跳到一个地址

其他系统可以装apache、nginx等搭web服务器

演示地址 http://hls.sysorem.xyz/tv.html
# SSR_MOLAB

手机SSR客户端，ios小火箭，电脑SSR客户端，老毛子改华硕和梅林固件，都可实现SSR订阅，即通过下载一个文档并读出服务器。
 
如何DIY和维护订阅地址。
下载一个订阅样本，txt打开获得一堆乱码。
通过base64解码，可以发现是一条条SSR链接。
base64编码：https://tool.oschina.net/encrypt?type=3
这时候就明白了。
一条条SSR链接排列好每一行，最后通过base64编码，存放为txt。
放到vps上做成直链提供下载，或用github分享即可。

最后让例如手机SSR客户端，subscribe订阅链接URI里输入那条链接，即可实现更新订阅。

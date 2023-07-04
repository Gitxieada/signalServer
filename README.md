
# 参考： 
[WebRTC 从实战到未来！前端如何实现一个最简单的音视频通话？](https://juejin.cn/post/7165539003465531399#)

[基于 WebRTC 的 P2P 文件传输 ](https://juejin.cn/post/7171836076246433799)

[webRTC 局域网点对点文件传输测试](https://github.com/L-orz/webRTC-test)

[信令服务器搭建部署](https://juejin.cn/post/7170767923005358094)

[**webRTC 局域网点对点文件传输测试](https://github.com/L-orz/webRTC-test/)


后端使用express、socket.io提供信令服务

## Install dependencies

```bash
$ npm i
```
# 运行：
 ##　本地运行该信令服务

Start the dev server,

```bash
$ npm run start
```
## pkg将NodeJS项目打包，编译成跨平台的可执行文件

[pkg](https://www.npmjs.com/package/pkg) 是一个可以将nodejs程序打包成exe文件的工具，免去我们的nodejs程序在客户电脑上跑时需要客户下载node环境。不仅可以打包成exe在window上跑，还可以打包成linux/mac下的可执行程序
```bash
$ npm run pkg
```
双击exe文件即可启动服务

 在前端页面：https://gitxieada.github.io/Demo/webrtc/index.html#/signal，
 输入信令服务器的地址signalServer，默认'ws://ip地址:5000'；
 注意在电脑测试时需要填 ws://localhost:5000

 前端代码在https://github.com/Gitxieada/Demo/tree/master/webrtc， 可以下载下来在本地部署
 

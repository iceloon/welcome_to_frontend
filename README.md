# 这是个什么玩意儿？

这是一个演示项目，用于将广大不谙世事的同学忽悠进前端开发这个大火坑

-----

## 准备工作

硬件准备：台式机 * 1，iPad * 1，两者需要在同一个局域网内

把项目 clone 下来之后，进入目录，然后安装相应的 npm 包并启动应用

    $ npm install
    $ node app.js

请自行确保 80 端口没有被占用

## 如何演示

在台式机上，用 Chrome 等高级浏览器打开 http://your.ip.address/index.html ，按下 F11 全屏，并向观众展示它的屏幕

开启 iPad 的旋转锁（锁成垂直方向），打开 http://your.ip.address/ipad.html ，推荐用海豚等能够全屏的浏览器

然后就能在 iPad 上看到一个很囧的葫芦，这时候可以随便说两句，比如：“你们猜猜这个福禄里面有什么？”

最后，最关键的一步，把 iPad 做倾倒状，然后就能看到某个球从 iPad 掉入屏幕了，就像这样

![](http://chaoskeh.com/uploads/attach/thumb_1c9a5daf00c54e0673476c4c52065dab.jpg)

## 说明

此演示的创意完全源自于 @大城小胖 在台湾的一次演讲，当然品质上离原作差了几十万光年

强烈推荐大家翻墙观看原作 http://www.youtube.com/watch?v=yTa-8JwFO30

由于我基本不了解游戏开发，所以源码写的相当差，此项目只为抛砖引玉

## TODO

1. 葫芦很丑，球更丑，原因是作者不是射鸡师
3. iPad 倾倒的判断太简单，导致交互效果很差，原因是作者水平更差
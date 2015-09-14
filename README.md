# SleepHook
定时锁屏工具

## 出发点
以前经常熬夜做事情，到点了也不忍离开实验室，后面想有个定时停止当天工作的工具。定时关机会关闭所有的东西以致于第二天得重新打开电脑和昨天的各种IDE。于是写了这个工具，到了设定的时间段程序会对电脑进行锁屏，不能进行任何操作，只能乖乖回去，第二天会自动解锁。有了这个工具基本早就养成了早回早起的习惯，今天想起来分享给大家。

## 锁屏后效果图
<img src="https://raw.githubusercontent.com/lanbing510/SleepHook/master/screenshots/sleephook.png" width="80%" height="80%">

## 使用说明
release下是可以直接使用的，在.ini文件设定好时间段后，运行SleepHook即可。src下是所有源码，方便感兴趣的进一步开发。

PS: 建议设置SleepHook开机启动, 由于用到了钩子杀毒软件会误报毒(无毒无危害，源码在)，建议加入白名单。

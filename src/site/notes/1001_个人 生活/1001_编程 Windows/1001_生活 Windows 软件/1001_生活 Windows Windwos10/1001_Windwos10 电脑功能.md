---
{"dg-publish":true,"permalink":"/1001/1001-windows/1001-windows/1001-windows-windwos10/1001-windwos10/","dgPassFrontmatter":true}
---

---
---

# 1 Windows 系统版本

![GrayFraserGit](https://grayfraserpic.oss-accelerate.aliyuncs.com/PersonPic/20250101/7a1bcc540b9caf9f7d9a9b8da3af04f1_MD5.png)

```
现在使用的
```

## 1.1 Windows 系统安装 Pe 安装工具

```
复制镜像内容，到新的地方，全部复制即可
然后使用分区工具，将系统盘进行格式化
然后点击左下角，使用winNetSetup进行安装，选择目录为新的分区
抹除以前系统盘分区
然后进入高级设置，调整启动项。
```

# 2 Windwos 设置优化

## 2.1 Windwos 关闭磁盘碎片

```bash
https://zhuanlan.zhihu.com/p/127341400
打开设置->找到隐私->选择后台应用 ，然后关闭不希望后台运行的应用。
关闭磁盘碎片整理计划
选中磁盘C-右键属性–工具–对驱动器进行优化和碎片整理–优化–更改设置–取消选择按计划运行
```

## 2.2 Windwos 修改虚拟内存

```bash
最小值为物理内存的二倍 
最大值为物理内存的三倍
```

## 2.3 Windows 桌面文件位置存放到 D 盘

```bash
配置如下
https://zhuanlan.zhihu.com/p/78243921
```

## 2.4 Windows 关闭弹窗

```bash
https://zhuanlan.zhihu.com/p/97564816
```

## 2.5 Windows 索引

```sql
开启全磁盘 索引 
搜索速度 不亚于EveryThing
https://blog.csdn.net/zhangjiuding/article/details/113400411
相关细则如下
```

## 2.6 Windows 设置独立显卡

```js
电脑怎么设置独立显卡-百度经验
https://jingyan.baidu.com/article/fdbd4277020f8df99e3f48c3.html
```

## 2.7 Windows 安全通知 禁用

第一种方法
禁用“Windows 安全中心”启动项
1、快捷键【Ctrl】+【Shift】+【Esc】打开【任务管理器】。
2、任务管理器页面，点击【启动】，找到【Windows secruity notice】，右键点击【禁用】。
![GrayFraserGit](https://grayfraserpic.oss-accelerate.aliyuncs.com/PersonPic/20250101/c1cb0b64d61b38b71fd072b217e6fee9_MD5.jpg)

## 2.8 Windwos 网络图标【小地球】

![GrayFraserGit](https://grayfraserpic.oss-accelerate.aliyuncs.com/PersonPic/20250101/5226cfb8e5804142b4864ab5c979ccf5_MD5.jpg)

```java
选择“使用下面的DNS服务器地址”，输入8.8.8.8，备用DNS服务器可以填上114.114.114.114等，然后点击确定。
```

## 2.9 Windwos 关闭时间轴

如何在 win10 系统上关闭时间轴 - 百度经验

```cardlink
url: https://jingyan.baidu.com/article/3052f5a1c12e0cd6f31f86dc.html
title: "如何在win10系统上关闭时间轴-百度经验"
description: "如何在win10系统上关闭时间轴,如何在wi10系统上关闭时间轴图文教程"
host: jingyan.baidu.com
favicon: //exp-new.bdstatic.com/static/exp-pc/common-jquery/widget/img-baidu-com/baidu_icon_85beaf5.svg
```

## 2.10 Windows 关闭自动更新

如何关闭 Windows10 的自动更新？ - 知乎

```cardlink
url: https://zhuanlan.zhihu.com/p/38070514
title: "如何关闭Windows10的自动更新？"
description: "相信很多同学在用Windows10系统的时候，经常跳出更新系统的提示。 有时自动更新的时间，恰好是我们需要急用电脑的时候，而且系统更新比较慢，等待的时间长。 甚至经常会更新失败，会影响我们的工作或者平时的使用…"
host: zhuanlan.zhihu.com
image: https://picx.zhimg.com/v2-30eb3d7659a734dd48d0daf46e18793f_720w.jpg?source=172ae18b
```

## 2.11 Windows 关闭特效

![GrayFraserGit](https://grayfraserpic.oss-accelerate.aliyuncs.com/PersonPic/20250101/d338978fd00d01363086f90c60f7f4ab_MD5.png)

## 2.12 Windows 设置文件夹默认直接显示详情

```
https://jingyan.baidu.com/article/0eb457e5276db403f1a9052b.html
```

# 3 Windows 启动功能

## 3.1 Windows 沙盒模式

```shell
如何开启Windows 10中的Windows沙盒功能-腾讯电脑管家官网
https://guanjia.qq.com/web_clinic/s7/2007.html
```

## 3.2 Windwos 电脑开启上次登录时间

```json
windows10 家庭版 安装组策略
http://www.lotpc.com/dngz/8301.html
https://jingyan.baidu.com/article/e75aca85ab5d10552edac6a8.html 
```

## 3.3 Windwos 解除带宽限速

```
https://jingyan.baidu.com/article/3ea514898cd91452e61bba37.html
```

# 4 Windwos 出现异常

## 4.1 Windows 出现快速启动异常 出现了很多次

```sql
Connected User Experiences and Telemetry  服务开启 
Windwos Update  服务关闭 
参照这个 运行服务
https://blog.csdn.net/senbar/article/details/1293216
sfc /scannow 
扫描系统文件
```

## 4.2 Windows 32Bridge 出现问题

```
Windows32Bridge.service 
出现问题 卸载小娜
```

# 5 Windows 小功能

## 5.1 Windwos 使用图片隐藏文件

```json
文件夹和压缩包放在同一个文件中
copy 1.png/b+2.zip=3.png
修改后缀名即可
```

## 5.2 Windwos 删除天翼云盘图标

```js
[坑]删除我的电脑中的各种云盘图标(WPS云、微盘云...)_身披白袍的博客-CSDN博客
https://blog.csdn.net/Shenpibaipao/article/details/82895452
我的电脑里的天翼云盘图标怎么删除？ - 知乎
https://www.zhihu.com/question/484691875/answer/2114329736
```

# 6 Windows 快捷键

## 6.1 Windwos 临时文件 【快捷键】

```js
%temp%
```

![GrayFraserGit](https://grayfraserpic.oss-accelerate.aliyuncs.com/PersonPic/20250101/cb9a801d91edb12dd9caeb7c999826aa_MD5.jpg)

# 7 Windwow 彻底关闭休眠

```cardlink
url: https://jingyan.baidu.com/article/ea24bc395086e69b63b33138.html
title: "win10如何彻底关闭休眠-百度经验"
description: "win10如何彻底关闭休眠,wi10系统彻底关闭休眠方法。"
host: jingyan.baidu.com
favicon: //exp-new.bdstatic.com/static/exp-pc/common-jquery/widget/img-baidu-com/baidu_icon_85beaf5.svg
```

```cardlink
url: https://jingyan.baidu.com/article/5d6edee2fff6f5d8ebdeec3b.html
title: "win11系统怎么关闭自动睡眠-百度经验"
description: "win11系统怎么关闭自动睡眠,wi11系统在无任何操作超过一定时间后就会自动进入睡眠，那如何关闭睡眠设置呢？只需要4个步骤就可以关闭自动睡眠。"
host: jingyan.baidu.com
favicon: //exp-new.bdstatic.com/static/exp-pc/common-jquery/widget/img-baidu-com/baidu_icon_85beaf5.svg
```

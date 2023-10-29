# Microsoft 垃圾产品质量 / BUG 集锦

Microsoft 我操你妈逼

## Windows 开始菜单启动程序后无法自动消失

![Start-Menu.gif](https://s2.loli.net/2023/10/30/aRyh9o5JzjvVi4k.gif)

## [Windows 空间计算错误](https://github.com/JimmyRice/fuck-microsoft/issues/1) by [Arispex](https://github.com/Arispex)

![Detail image](https://user-images.githubusercontent.com/67822718/278647710-f6b4b622-3d49-4ea0-9eb8-e6bc20039bbd.png)

![Detail image](https://user-images.githubusercontent.com/67822718/278647723-04beb9c8-fb6d-4344-b1ac-89a4c31acfc0.png)

## Windows 11 Select an App 的程序选择卡死

![Select-an-app-freezes.gif](https://s2.loli.net/2023/10/23/obFuQl5ZavGkmyn.gif)

啊？这都能卡死...

## Windows 11 从休眠中恢复 Taskbar 图标失踪

![bc3864e55c36d42d70addd8282ea348a.png](https://s2.loli.net/2023/10/14/7LugI6TfnBiptEh.jpg)

随机复现，很他妈烦人。解决方案强制重启 Explorer.exe

## Windows 11 Print Preview 似乎只支持 UWP - (?)

微软亲儿子画图程序 Paint.exe 都必须把 Paint Preview 做成一个独立功能

![image.png](https://s2.loli.net/2023/10/12/TIKwPBcZCUySdHv.png)

![image.png](https://s2.loli.net/2023/10/12/ljuPes15QSmrIDp.png)

目前测试情况: 我能测试的非 WebView / Chromium 的 Windows 窗体程序在新版打印窗口中均没有打印预览

## Azure 前端 Bug

虽然不是太大的问题，但是写出这种玩意也是蛮牛逼的

在 Chrome 和 Edge 都复现成功

![Azure.gif](https://s2.loli.net/2023/10/12/TYq52g9zsED8CAf.gif)

## Bing 前端 Bug

似乎已经修复，有一小段时间了。偶然发现 New Bing 生成的答案，下面的来源框中。href 是这么写的...导致跳转过去是 Bing 404。十分佩服微软

![IMG_5453_20231012-141303_.JPG](https://s2.loli.net/2023/10/12/K25qiSXsaxfIG8e.jpg)

## Windows Theme 保存预览为全黑色，只能按照名字分辨

我很不解为什么微软要这么做。

![image.png](https://s2.loli.net/2023/10/12/1n4THYqmRZS2xAK.png)

## Windows Copilot Preview 临时问题，无法复现宣传功能

未知原因，无法打开程序也无法调整任何设定。但是后面又自己恢复了

![eb04a660070128b49eb29c7dab6fdab0.png](https://s2.loli.net/2023/10/12/rLdWAaGNRgBiJ84.png)

![8016ebc8f6e73f3c6e7de39a02c5047a.png](https://s2.loli.net/2023/10/12/rUpQesx4Pmbf8BL.png)

一样，这个 Windows Copilot 也是 New Bing 做的，WebView 2 套壳 (也许，总之是网页就是)。没有任何诚意的产品。

## Windows Explorer 添加到快速访问 Bug

我只是 Pin 了一个，结果所有都 Pin 上了是？

![Windows Explorer Pin.gif](https://s2.loli.net/2023/10/12/O9JwaHZMkTeriYA.gif)

## Windows Explorer 从快速访问移除 Bug

我移除了一个文件夹，自动把我的 Tom Clancy's Rainbow Six Siege 文件夹 Pin 上干嘛？？

![Windows Explorer Remove List.gif](https://s2.loli.net/2023/10/12/hVosnlC3rbAxOue.gif)

## Windows 11 消息自动聚焦

我的 QQ，微信，Discord 偶尔会复现这个情况。出现这个情况的时候非常烦人，写代码写到一半突然被切出编辑器

![image.png](https://s2.loli.net/2023/10/14/tJ5qIvuM3kHDTmi.png)

刚开始以为是我个人的问题，Google 后发现碰上的人不少

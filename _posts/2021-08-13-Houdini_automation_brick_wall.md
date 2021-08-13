---
layout: post
title: "Houdini自动化砖墙练习"
date: 2021-08-13
tags: [Houdini, 自动化, TA, 练习]
comments: true

Author: Yang Folker
--- 

在houdini中做了一个根据曲线自动生成的砖墙墙面，砖块颜色是一次交替的。

可自动调节高度。

![高度调节](https://raw.githubusercontent.com/YangFolker/YangFolker.github.io/main/images/2021-08-13-Houdini_automation_brick_wall/preview01.gif)

可设置砖块的长短不一程度，设置砖块的侧向参差程度，设置两色砖块的颜色。

![调节砖块长短、参差、包边、颜色](https://raw.githubusercontent.com/YangFolker/YangFolker.github.io/main/images/2021-08-13-Houdini_automation_brick_wall/preview02.gif)

有两种模式，加包边或不加包边（包边即最上一层砖和两侧砖更宽更暗）

还可以选择，是否删除不重要面（即中间砖块被挡住的面，如果删除不重要面，在凸转角处会有一些小瑕疵）

源文件可见：https://github.com/YangFolker/chopSuey/tree/main/Automation_Brick_Wall


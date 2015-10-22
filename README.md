## UniversalCellLayout
simple BrickLayout, with fixed width and height unit , flexible combination style

####Introduction：

参考Launcher桌面布局icon和widget混搭的CellLayout的架构，实现了更为通用的布局方式。


####Feature：

1、长度和宽度为定值的N倍，长方形的混搭布局；

2、可以实现横向、竖向类似metro风格的布局。

3、支持超出屏幕部分scroll的功能

####How to use：

布局中，制定每个长方形的cellX cellY，和x，y，（均为正数）


title:  Unity3D地形系统自定义画笔
date: 2015-09-16 18:46:35
tags:
---

1.在Unity的Assets目录下面创建一个Gizmos目录(Assets\Gizmos\..)


2.创建一个带透明的图形(推荐PNG格式)，分辨率必须是2的幂次方宽高相等(如256*256)。需要突出显示的地方用黑色，反之保持透明。(test.png)


3.将test.png命名为 brush_0.png 下标必须从0开始。不能中断.


4.重启动unity3d,编辑地形和绘制贴图就可以看到新增加的笔刷了。

![](/img/brush/test.png)    
   
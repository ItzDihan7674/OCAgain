# 路径点

![“这边！”“不，那边！”](oredict:opencomputers:waypoint)

路径点重点不在本身，而是如何使用。[导航升级](../item/navigationUpgrade.md)可以探测路径点，因此安装了这种升级的设备就可以通过路径点来导航。这在编写适用于[机器人](robot.md)和[无人机](../item/drone.md)的高度可重用程序时很有用。

注意，导航升级报告的路径点位置其实是路径点方块的正面的方块（会有粒子效果指示）。因此你可以把他放在箱子的边上或者上方，通过将路径点看作“箱子上方”，而不必在你的程序里面旋转路点坐标。

导航升级查询到的路径点有两个属性：当前收到的红石信号强度，以及可编辑的标签。其中，标签是个最长 32 字符的字符串，可通过路径点的 GUI 或对应的组件 API 进行编辑。这些属性可以用来定义一些更具体的行为，比如我们可以将有高电平的路径点视作输入，低电平的路径点则视作输出。

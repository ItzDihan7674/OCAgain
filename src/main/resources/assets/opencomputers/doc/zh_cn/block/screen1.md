# 显示屏

![看见没？](oredict:opencomputers:screen1)

显示屏需要和[显卡](../item/graphicsCard1.md)一起使用，这样电脑才能显示文本。不同型号的屏幕能支持的分辨率和色深不尽相同，从低分单色屏到高分 256 色屏都有。

最终的分辨率和色深取决于最差的配件，举例：当使用 T1 显卡和 T3 屏幕时，只能使用 T1 的分辨率和色深，反之亦然。但是，T3 显卡和 T1 显示器的搭配的运行速度会快些。

多块显示屏若朝向一样，则可组成多方块显示屏；对于朝上或朝下平放的显示屏来说，还要保证旋转方向一致。显示屏的方向可通过手持显示屏并指向其他显示屏时出现的箭头来确定。

只有显示屏等级会影响分辨率，显示屏大小不影响分辨率。可以通过染色控制哪两块屏幕可以连接，手持染料右键即可对显示屏染色，染料不会消耗。拆除显示屏时颜色不会保留。不同颜色的显示屏不会连接。不同等级的显示屏也不会连接。

T2 和 T3 显示屏还支持鼠标。你可以通过屏幕的 GUI（需要键盘来打开）来点击屏幕，或者潜行时空手对屏幕点击；在屏幕没有键盘的时候，不需要蹲下就可以直接点击。注意，潜行与否时使用屏幕的行为是可以通过其组件 API 控制的。T3 屏幕的组件 API 可以启用精确度更高的点击探测，这可以用来判定被点击的字符是上半部分还是下半部分，用于模拟更高分辨率。

各等级显示屏的分辨率和色深如下：
 - T1: 50x16，单色。
 - T2: 80x25，4 位彩色。
 - T3: 160x50，16 位彩色。

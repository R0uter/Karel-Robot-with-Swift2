# Karel Robot with Swift

使用最新的 Swift 5 构建
----
这是我用 Swift 5 实现的一个 Karel 机器人，它能够允许你通过`move()` `putBeeper()` `putBeeper()` `turnLeft()`这四个命令来控制 Karel 解决各种问题。
另外还有`isBlocked()`和`isBeeperHere()`来获得 Karel 的当前状态，，前者是看 Karel 面前是否有墙，后者是看 Karel 脚下是否有 Beeper。

>Karel 其实某种意义上来说就是一个图灵机的模拟器。
总之，来试试吧~


## 使用说明

这个 Karel 机器人是用来给你入门学习编程思想的，你可以直接按照我的课程当中那样使用它；也可以观摩代码来了解它的实现——虽然写的不是很漂亮啦。

在 Run.swift 文件当中写好了算法之后，就可以点击`运行`按钮来跑了，如果撞墙，则程序右下角会有红灯提示——这样程序就会提前结束了。

在 Karel 的世界下方，有一个滑动条，在`重置`之后或者`暂停`的时候，你可以滑动它来调节 Karel 的行动速度，默认是个中间值，滑动到最左边则会瞬间显示结果，滑动到最右边则是最慢的状态啦。

在 `Config.swift` 文件中，你可以配置 Karel 的初始化信息，比如 Karel 的初始位置，朝向，还有世界的初始 Beeper 和 Block 位置，十分的方便。你也可以把其他人写好的世界信息直接粘贴导入，再也不用拷贝整个项目了。也不需要在代码里更改，避免了意外毁掉整个程序：）


## 再说两句

Karel 这个东西在国内好像不是很流行的，在国外我也不知道如今是否还是CS课程里的必修入门课——但我学习编程却真的是从 Karel 走进来的——看着 Java 的 Karel 学习 Swift 。

所以说当我对 Swift 稍微理解之后，边萌生了用 Swift 实现一遍这个机器人的梦想——两个月后，我终于做到了，作为一名野生程序猿，能有这么多学员支持我我很感动。——把这个 Karel 送给你，希望你能像我一样从这个小机器人那里学到更多的东西！


R0uter 
以上

2020-04-13 17:02:42


>Hope enjoy!

## MIT License (MIT)

The MIT License (MIT)

Copyright (c) 2015-2020 R0uter

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Bilibili Drag

这是一款针对B站的浏览器脚本，能够自由调节播放器中的画面。

## 安装

[Greasy Fork](https://greasyfork.org/zh-CN/scripts/549406-b%E7%AB%99%E8%A7%86%E9%A2%91%E7%BC%A9%E6%94%BE-%E7%A7%BB%E5%8A%A8)

## 使用方法

安装后，打开B站视频播放页面，当焦点在播放器上时（无论是否全屏），按下键盘`Shift`键进入画面调整模式，此时滑动`鼠标滚轮`缩放；拖动鼠标`左键`可移动画面。

松开`Shift`键即退出画面调整模式。

当画面调整后，左下角有按钮可以一键还原屏幕。

![效果图](/docs/img/demo.png)

## 反馈

[Github Issues](https://github.com/dbsan2333/bilibili-drag/issues)

[Greasy Fork](https://greasyfork.org/zh-CN/scripts/549406-b%E7%AB%99%E8%A7%86%E9%A2%91%E7%BC%A9%E6%94%BE-%E7%A7%BB%E5%8A%A8/feedback)

## 开发

该目录下[dev.js](./dev.js)为开发开发时用代码。

开发过程中可以将[dev.user.js](./dev.user.js)中的`@require`部分按要求替换后导入到油猴以方便地实时预览。

阶段性开发完成后替换到[user.js](user.js)即可。

> 其实如果开发大型油猴脚本的话，建议使用工程化方式，详见[vite-plugin-monkey
](https://github.com/lisonge/vite-plugin-monkey)

## 使用到的第三方库

异步获取元素的脚本库 [ElementGetter](https://bbs.tampermonkey.net.cn/thread-2726-1-1.html)

xd-no-flash-plz !
======

## 0. Introduction

**学校平台已经增加了对 H5 播放的支持，令人感叹，然而体验依旧不好**

使用 HTML5 播放器 [videojs](https://github.com/videojs/video.js) 替换学在西电课程回放原本的 Flash 播放器

~~1202 年了，学校更新一下有这么难吗？装 Flash 是不可能装的，这辈子不可能装的~~

## 1. Quick start

你需要一个油猴插件 [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) 来运行这个脚本，你可以在 Chrome 网上应用店或者其他什么地方找到它，安装成功后并导入这个脚本

你也可以直接通过 [GreasyFork](https://greasyfork.org/zh-CN/scripts/425163-xd-no-flash-plz) 快速地安装它

## 2. Features

1. 支持的热键： `space` 暂停， `↑` 音量调高， `↓` 音量调低，`←` 后退 5s ， `→` 前进 5s ， `M` 静音 / 取消静音， `ENTER` 全屏
2. 支持的鼠标操作：`左键单击` 暂停 / 播放，`右键单击` 菜单，`左键双击` 全屏，`滚轮` 全屏下调节音量
3. 源地址获取：你可以在右键菜单里快速地复制视频地址 (m3u8) 然后使用其他播放器，下载器
4. 倍速播放：支持多种倍速播放 `[0.5, 1.0, 1.5, 2.0]` 
5. 右键菜单：包含一些功能选项
6. 自动跳过错误切片：最近发现有许多回放切片都无法获取，每个切片为 1~2s ，播放器会跳过这些片段
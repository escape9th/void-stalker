# VOID STALKER · 虚空尾随者

一个 **3D 抽象恐怖小游戏**（browser game）。你被困在一片没有尽头的黑雾里，四周飘着几颗发光的碎片——收集完它们，你才能"醒来"。但雾里有个东西，一直、一直在跟着你。离你越近，低鸣越响，心跳越快。

A tiny **3D abstract horror game** running in the browser. You're trapped in an endless fog, collecting glowing shards to wake up. But something in the fog is following you — the closer it gets, the louder the drone, the faster your heart.

## 怎么玩 / How to play

- 点击画面开始（锁定鼠标），`WASD` 移动，鼠标看方向，`ESC` 暂停。
- 收集全部 **7** 颗碎片通关；被雾里的东西碰到就结束。
- 没有地图、没有提示——你只能靠碎片的微光和越来越近的低鸣判断方向。

## 玩一把 / Play

这是个纯前端的单文件游戏，**不用装任何东西、没有构建步骤**：

```bash
git clone https://github.com/escape9th/void-stalker.git
cd void-stalker
# 直接用浏览器打开 index.html 就能玩（需要联网加载 Three.js）
```

## 技术栈 / Tech

- **Three.js** —— 3D 渲染（雾、几何体、第一人称视角）
- **Web Audio API** —— 全程程序生成的音效（低鸣、心跳、爆音），零外部音频文件
- 原生 **HTML / CSS / JavaScript**，无框架、无 npm 依赖、无构建

## 为什么做这个 / Why

就想试试：不靠贴图、不靠怪物模型，只用"黑雾 + 一个几何体 + 声音"，能不能做出那种"后颈发凉"的感觉。它很小，但该有的都有。

## License

MIT

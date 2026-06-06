# Helldivers2 Stratagems Online Practice Game

一个受《Helldivers 2》启发的网页战备指令练习器。项目以轻量级静态网页形式实现，用于练习方向指令输入，包含中英文战备名称、真实方向代码、分类筛选和来自 wiki 的战备图标。

## 在线试玩

GitHub Pages 地址：

[https://labdogx.github.io/Helldivers2_Stratagems_OnlinePracticeGame/](https://labdogx.github.io/Helldivers2_Stratagems_OnlinePracticeGame/)

## 功能

- 中英文战备指令名称显示。
- 每个战备指令匹配对应方向输入代码。
- 支持按战备类别筛选题库。
- 三档难度，根据指令长度和得分倍率区分。
- 支持 60 秒冲刺和无限练习两种模式。
- 支持键盘方向键和页面方向按钮输入。
- 最近记录展示完成时间和得分增量。
- 单页静态实现，无需构建流程。

## 本地运行

克隆仓库后，直接使用浏览器打开 `index.html`。项目不依赖包管理器、后端服务或构建工具。

```text
index.html
```

## 仓库结构

- `index.html`：完整游戏页面，包含页面结构、样式、数据和交互逻辑。
- `README.md`：英文项目文档。
- `README.zh-CN.md`：中文项目文档。
- `音乐播放器图标/`：保留给本地音乐播放器模块使用的 UI 图标资源。
- `Original Soundtrack/`：可选的本地原声音乐目录，已被 Git 忽略。

## 资产策略

公开仓库不托管《Helldivers 2》原声音乐文件。本地音乐播放器模块仍保留在源码中，便于本地实验和后续开发，但公开页面默认隐藏播放器界面，原声音乐目录也不会进入版本控制。

战备图标和默认训练图标在运行时从 Helldivers Wiki 的公开图片链接加载，未作为本地资源打包进仓库。

## 难度说明

- 轻松：抽取方向长度不超过 4 的战备指令，得分倍率为 1x。
- 标准：抽取方向长度不超过 5 的战备指令，得分倍率为 1.35x。
- 老司机：使用完整战备题库，不限制方向长度，得分倍率为 1.8x。

难度不会改变倒计时速度；它主要影响题库长度范围和完成后的得分倍率。

## 数据来源

- 英文名称、方向代码和战备图标：[Helldivers Wiki - Stratagems](https://helldivers.wiki.gg/wiki/Stratagems)
- 默认训练图标：[Helldivers Wiki - Images - Helldivers 2 - Logo](https://helldivers.wiki.gg/wiki/Category:Images_-_Helldivers_2_-_Logo)
- 中文名称：参考 [Bilibili 译制图](https://www.bilibili.com/opus/919091931569455128)，并补齐后续新增条目

图标通过公开 wiki 图片链接显示，因此浏览器需要联网才能加载图标。跨站使用 wiki 托管文件时，请注明文件获取来源、上传者以及 Helldivers Wiki.gg。

## 说明

这是一个非官方粉丝练习项目。项目不隶属于 Arrowhead Game Studios、Sony Interactive Entertainment 或 PlayStation，也未获得其认可、赞助或授权。*Helldivers* 及相关名称、标志、图片和游戏资产归各自权利人所有。

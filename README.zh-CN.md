# Helldivers2 Stratagems Online Practice Game

一个单文件网页练习小游戏，用来练习类似《Helldivers 2》战备指令输入的反应速度和准确率。

当前版本包含中英文战备指令名、真实方向代码、分类筛选和战备图标显示。

## 在线运行

仓库发布到 GitHub Pages 后，入口文件是：

```text
index.html
```

也可以直接在本地双击 `index.html` 打开游玩。

## 项目文件

- `index.html`：完整游戏页面，包含样式和交互逻辑。
- `Original Soundtrack/Helldivers II Original Soundtrack (2024)`：本地音乐播放器使用的 MP3 文件目录。该目录不会提交到 GitHub；请只在本地或拥有发布授权时提供音频文件。

## 难度说明

- 轻松：只抽取方向长度不超过 4 的战备指令，得分倍率为 1x。
- 标准：只抽取方向长度不超过 5 的战备指令，得分倍率为 1.35x。
- 地狱：不限制方向长度，所有战备指令都可能出现，得分倍率为 1.8x。

难度不会改变倒计时速度；它主要影响题库长度范围和完成后的得分倍率。

## 数据来源

- 英文名称、方向代码和战备图标：[Helldivers Wiki - Stratagems](https://helldivers.wiki.gg/wiki/Stratagems)
- 默认训练图标：[Helldivers Wiki - Images - Helldivers 2 - Logo](https://helldivers.wiki.gg/wiki/Category:Images_-_Helldivers_2_-_Logo)
- 中文名称：参考 [Bilibili 译制图](https://www.bilibili.com/opus/919091931569455128)，并补齐后续新增条目

图标通过公开 wiki 图片链接显示，因此浏览器需要联网才能加载图标。跨站使用 wiki 托管文件时，请注明文件获取来源、上传者以及 Helldivers Wiki.gg。

## 说明

这是一个非官方粉丝练习项目，仅用于学习、练习和个人娱乐。项目不隶属于 Arrowhead Game Studios、Sony Interactive Entertainment 或 PlayStation，也未获得其认可、赞助或授权。

项目不会提交或托管《Helldivers 2》原声音乐文件。本地音乐播放器相关代码保留在源码中，但公开网页默认隐藏播放器界面。

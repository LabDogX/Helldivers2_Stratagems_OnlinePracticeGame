# Helldivers2 Stratagems Online Practice Game

一个单文件网页练习小游戏，用来练习类似《Helldivers 2》战备指令输入的反应速度和准确率。

当前版本包含中英文战备指令名、真实方向代码、分类筛选和战备图标显示。
页面右下角包含本地浮动音乐播放器，可播放 `Original Soundtrack/Helldivers II Original Soundtrack (2024)` 目录中的 MP3，并支持曲目切换、进度拖动、音量调节、列表循环、单曲循环和随机播放。

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

- 英文名称、方向代码和图标：Helldivers Wiki 的 Stratagems 页面
- 中文名称：参考 Bilibili 译制图，并补齐后续新增条目

图标通过公开 wiki 图片链接显示，因此浏览器需要联网才能加载图标。

## 发布到 GitHub Pages

1. 创建名为 `Helldivers2_Stratagems_OnlinePracticeGame` 的 GitHub 仓库。
2. 把本目录内的文件提交并推送到仓库。
3. 在 GitHub 仓库页面进入 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub 生成 Pages 地址。

## 说明

这是一个非官方粉丝练习项目，仅用于学习、练习和个人娱乐。项目不包含官方游戏资源。

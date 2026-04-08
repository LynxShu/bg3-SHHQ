# Baldur's Gate 3 : SHHQ - Chinese Font Replacer (Multi-Weight) 

<div align="center">
  <img src="/assets/logo.png" style="max-width: 100%; height: auto;" />
</div>

<div align="center">

博德之门3 SHHQ - 多字重简中字体替换包

本项目是一个针对《博德之门3》的简中字体美化项目，旨在为中文玩家提供更舒适、沉浸的游玩体验。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Bilibili](https://img.shields.io/badge/Bilibili-LynxShu-006cff?logo=bilibili&logoColor=white)](https://space.bilibili.com/582462)

</div>

---

### ⚙️ 1. 项目简介

本模组将**思源宋体 (Source Han Serif)** 的汉字字符与**原版游戏的英文字符**进行了无缝混排。

* **统一风格：** 解决了原版中文单字重中英文混排时的割裂感。
* **字形修正：** 采用 `思源宋体`  大陆地区专属字符集，融入原版英文字符，并调整了字形与细节。保留了原版英文、数字和半角标点的古典奇幻质感。
* **丰富字重：** 补全了常规体 (Regular)、半粗体 (DemiBold)、粗体 (Bold) 及对应的三种斜体 (Italic)，解决了简中环境下不同字重在游戏中的显示问题。

---
### 📥 2. 安装与卸载

1. 在本仓库的 [Releases](https://github.com/LynxShu/bg3-SHHQ/releases) 页面下载最新的压缩包文件。

2. 将解压后的文件夹放入游戏`根目录`的`Data`文件夹中即可，例如 `\Baldurs Gate 3\Data\`

3. 完整的结构如下所示。

   ```
    📁 Data
    └── Public
        └── Game
            └── GUI
                ├── Assets
                │   └── Fonts
                │       ├── SHHQ-Bold.otf
                │       ├── SHHQ-BoldItalic.otf
                │       ├── SHHQ-Demibold.otf
                │       ├── SHHQ-DemiboldItalic.otf
                │       ├── SHHQ-Italic.otf
                │       └── SHHQ-Regular.otf
                └── Theme
                    ├── DefaultTheme.Fonts.xaml
                    └── Keyboard.Fonts.xaml
   ```

4. 如需卸载，请对照上述模组结构详情，删除 `Public` 文件夹内的相应文件即可。你可以随时安装与卸载，对游戏没有任何影响。

---

### 🖼️ 3. 效果展示

<div align="center">
  <img src="/assets/game01.png" style="max-width: 100%; height: auto;" />
  <br><br>
  <img src="/assets/game02.png" style="max-width: 100%; height: auto;" />
  <br><br>
  <img src="/assets/game03.png" style="max-width: 100%; height: auto;" />
  <br><br>
  <img src="/assets/game04.png" style="max-width: 100%; height: auto;" />
</div>

---

### 😉 4. 一些碎碎念

* 说到游戏的UI字体，其实一直是一个没啥人关心，但却很影响用户体验的问题。尤其是非国产游戏中的默认中文字体，厂商们通常都没有什么动力去定制专属的字体（这里要表扬黑猴一下下），大多数都是一个字重用到底的。我们在游戏中体验一个全新的世界，却要忍受着只有字号变化的中文字，没有粗细，没有层次，极个别的甚至没有艺术美感。我也曾尝试在社区中寻找相应的模组，来改善我的游戏体验，但找到的都只有单字重，就很难绷。（字重：指字体笔画的粗细程度，它是字体设计中的一个重要属性，用不同粗细的样式，增强文本的层次感和可读性。）于是便有了这个项目。
* 当然，`思源宋体` 并非最适合博德3世界观和画风的字体，但却是开源字体中**拥有完整字重**且具有一定艺术美感的字体。隔壁老滚5的社区字体很棒，但因为没有多字重以及缺失一些字符，便没有采用。本模组中所有的中文均采用了 `思源宋体` 简中字符集中的字形，将原英文字体缝合了进去，并进行了一些字形调整，以便更好的适应中英混排的场景。
* 希望你能喜欢这个模组，也希望它能为你带来一些游戏体验的提升。
* SHHQ 取自思源系列的字母简写，最后一个Q，嗯...为了规避一些问题我们还是称它为 SHHQ 吧 :-)

---

### 🙏 5. 鸣谢与免责声明

* **Source Han Serif (思源宋体)**: 由 Adobe 和 Google 联合开发，遵循 SIL Open Font License 1.1。
* **官方英文字体资产**: 版权归 Larian Studios 及原字体厂商所有。
* 本模组包含提取自《博德之门3》本地文件的英文字形资产。本模组完全免费，仅供玩家优化单机游戏体验及技术交流使用，若版权方认为本模组侵犯了您的权益，请联系我，我将第一时间删除相关文件。

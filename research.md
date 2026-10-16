# 研究与工具依据

本轮没有照搬参考图，而是提炼其共同机制：高密度文字场、跨栏、纵横混排、极端字号对比、信息参与构图，以及在大量文字中保持阅读顺序。

## 参考平台与工具

- [typo/graphic posters](https://www.typographicposters.com/)：用于观察文字海报如何让排版成为图像，而不是把文字附着在图像上。
- [100 Beste Plakate](https://100-beste-plakate.de/)：用于核对国际海报评审中对独立视觉系统与版面实验的要求。
- [poster-maker](https://github.com/dabodamjan/poster-maker)：借鉴真实 HTML/CSS 文字、可编辑源文件和 Chromium 高分辨率导出的工作方式。
- [PosterKit](https://github.com/posterkit/posterkit)：借鉴文字自动适配和海报输出逻辑。
- [Any2Poster](https://github.com/Any2Poster/Any2Poster)：借鉴真实文字渲染、溢出检测和逐面板复核的方法。
- [chinese-fonts](https://github.com/yuleshow/chinese-fonts)：用于核对可再分发中文字体与开源许可。

## 本轮采用的方法

1. 先建立 15 套互不复用的布局骨架，再放入同一份经过校订的中英文文单。
2. 用本地开源字体文件保证 GitHub 页面和 PNG 导出稳定一致。
3. 用 1200 × 1800 浏览器画布导出，每张检查 12 位艺术家、8 位团队成员、7 组活动信息、Logo、越界、容器裁切和关键字号。
4. `Highest`、`（）` 与 `Mia` 作为独立校对项。

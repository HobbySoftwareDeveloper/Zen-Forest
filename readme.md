# Zen Forest 

A heavily customized, minimal, and aesthetic visual replacement for Obsidian. Based on the original [Zen Theme](https://github.com/laughmaker/zen) by @Laughmaker.

`Zen Forest` 是一款基于原版 Zen 主题深度魔改的 Obsidian 极简视觉主题。它在保留原版纯净质感的同时，对高阶排版、窄视距对齐以及细节动画进行了像素级的打磨，旨在为你提供一个如同林间清晨般幽静、沉浸的沉浸式写作环境。


![](Screenshot%202026-06-19%20121036.png)
![](Screenshot%202026-06-19%20121048.png)
![](Screenshot%202026-06-19%20121123.png)

---

## Key Features / 核心特性

*   **Unified Narrow Viewport Width / 窄视距排版一体化**
    *   *EN:* Overrode Obsidian's default behavior in readable line width mode. All headings ($H_1$ to $H_6$) and body text are now perfectly constrained to a unified layout width, eliminating horizontal misalignment.
    *   *ZH:* 完美重构了可读行宽（Readable Line Width）模式。所有标题（$H_1$ 至 $H_6$）与正文在窄视距下实现像素级完美对齐，彻底解决原生主题标题两边间距错位的问题。
*   **Stripped Heading Underlines / 极致纯净的无干扰标题**
    *   *EN:* Removed all bottom borders and pseudo-element underlines from all heading levels in both Live Preview and Reading views, delivering an ultra-clean digital canvas.
    *   *ZH:* 彻底清除了实时预览和阅读模式下所有各级标题的下划线及伪元素下划线线索，消灭视觉噪点，让文字专注于文字本身。
*   **Refined Modal Animations / 丝滑转场动画**
    *   *EN:* Replaced rigid transitions with a custom `cubic-bezier(0.2, 0.9, 0.4, 1.1)` entrance animation for modals and dialogs, rendering fluid, cinematic window scaling.
    *   *ZH:* 精心调校了模态弹窗的入场曲线，采用 `cubic-bezier` 缓动动画，让每一次弹窗开启都带有细腻、丝滑且富有弹性（Scale & Translate）的电影级动态质感。

---

## 移动端兼容性说明 / Mobile Compatibility

> [!warning]
> 本主题目前主要针对 **Desktop (Windows / macOS / Linux)** 平台进行深度打磨与日常使用。
> 
> 由于作者日常主力在电脑端编辑，**目前暂未对手机/平板等移动端（iOS / Android）进行全面适配**。移动端可能会出现排版错位或不理想的视觉效果。
> 
> 欢迎移动端用户体验并提交 Bug Report 或 Pull Request，帮助 `Zen Forest` 变得更完美！
> 
> *This theme is primarily tailored for desktop environments. Mobile layout optimization is still a work in progress. Contributions for mobile compatibility are highly welcome!*

---

## Installation & Customization / 安装与微调

### 1. Style Settings Integration / 完美融合配置滑块
本主题兼容 **Style Settings** 插件。

### 2. Manual Installation / 手动安装 (Snippet)
如果你只想作为片段使用：
1. 下载 `theme.css`。
2. 将其放入你的 Obsidian 库文件夹：`.obsidian/snippets/zen-forest.css`。
3. 在 `设置 -> 外观 -> CSS 代码片段` 中启用它。

---

### Theme Color & Style Notice / 主题配色与微调须知

*   **Recommended Accent Color / 推荐主题色**
    *   *ZH:* 为了获得完美的森林视觉沉浸感，建议在安装主题后，进入 `设置 -> 外观 -> 主题色（Accent color）` 中，将颜色自定义为 `#688958`（即 RGB: `104, 137, 88`）。
    *   *EN:* For the best "Zen Forest" immersive experience, it is highly recommended to set your custom Accent Color to `#688958` (RGB: `104, 137, 88`) under `Settings -> Appearance -> Accent color`.

*   **Hardcoded UI & Heading Colors / 核心配色微调说明**
    *   *ZH:* 请注意，本主题的各级标题（$H_1$ - $H_6$）以及大部分 UI 组件的森林系配色是**写死在底层代码中**的，无法通过 Obsidian 的外观设置或 Style Settings 插件直接更改。如果您想要自定义这些颜色，需要直接打开 `theme.css` 文件，搜索 `--h1-color` 至 `--h6-color` 以及 `.theme-dark`/`.theme-light` 块下的变量进行手动修改。
    *   *EN:* Please note that the forest-vibe color palette for headings ($H_1$ - $H_6$) and core UI components is hardcoded. They **cannot** be modified via the native appearance settings or the Style Settings plugin. If you wish to customize them, please open `theme.css` manually and modify the variables like `--h1-color` to `--h6-color` and relevant themed color tokens.

## License & Credits / 版权与协议

*   **Original Theme:** [Zen Theme](https://github.com/laughmaker/zen) by @Laughmaker.
*   **Modifications:** Customized with ❤️ by @Noctivision.

This project is licensed under the **MIT License**. The full license text, including copyrights of both the original author and modifications, can be found directly in the header of `theme.css`.

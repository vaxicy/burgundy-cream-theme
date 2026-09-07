<p align="center">
  <img src="assets/icon.png" width="128" alt="Burgundy Cream Theme logo">
</p>

<h1 align="center">Burgundy Cream Theme · 酒红奶油主题</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=lilinhuang.burgundy-cream-theme">
    <img src="https://img.shields.io/badge/VS%20Code-Theme-810B38?logo=visual-studio-code" alt="VS Code Theme">
  </a>
</p>

温暖复古的 VS Code 配色主题，以「酒红 + 奶油 + 浅驼」为主调，提供 **Burgundy Cream Light** 与 **Burgundy Cream Dark** 两套变体，覆盖编辑器界面与语法高亮。

A warm vintage VS Code theme built around burgundy, cream and camel tones. Ships with a **Burgundy Cream Light** and a **Burgundy Cream Dark** variant, covering both the workbench UI and syntax highlighting.

## 配色 · Color Palette

| 角色 Role | 名称 Name | 色值 Hex |
| --- | --- | --- |
| 主强调 Accent | 莓酒红 Burgundy | `#810B38` |
| 背景（浅色）Light bg | 奶油米白 Cream | `#F1E2D1` |
| 侧栏（浅色）Sidebar | 浅驼 Camel | `#DCC3AA` |
| 正文（浅色）Text | 深红棕 Deep brown | `#541A1A` |
| 主强调（深色）Dark accent | 桃粉 Pink | `#E794B0` |
| 背景（深色）Dark bg | 深褐 Dark brown | `#261719` |

浅色主题以奶油米白作编辑器底色、深红棕作正文，莓酒红贯穿活动栏、状态栏与标题栏；深色主题则翻转为底色 `#261719`、莓酒红活动栏搭配桃粉强调，长时间阅读依旧柔和护眼。

The light variant uses cream as the editor background and deep brown as text, with burgundy running through the activity bar, status bar and title bar. The dark variant flips to a `#261719` base with a burgundy activity bar and pink accents — easy on the eyes during long sessions.

## 特性 · Features

- 两套主题：Burgundy Cream Light（浅色）与 Burgundy Cream Dark（深色），一键切换。
- Two variants: a light and a dark theme, switchable from the Color Theme picker.
- 完整的工作台配色：活动栏、状态栏、侧栏、标签页、列表、输入框、悬浮控件与滚动条。
- Full workbench theming: activity bar, status bar, side bar, tabs, lists, inputs, widgets and scrollbars.
- 语义化语法高亮：关键字、字符串、数字、类型、函数与变量各有独立配色，注释采用柔和低饱和色。
- Semantic syntax highlighting with distinct colors for keywords, strings, numbers, types, functions and variables; comments use a soft, low-saturation tone.

## 安装 · Install

**本地预览（Local preview）**

用 VS Code 打开本项目文件夹，按 `F5` 启动扩展开发宿主（Extension Development Host），在命令面板执行 `Preferences: Color Theme`，选择 **Burgundy Cream Light** 或 **Burgundy Cream Dark** 即可实时预览。

Open this folder in VS Code and press `F5` to launch the Extension Development Host, then run `Preferences: Color Theme` and pick either variant.

**从 Marketplace 安装（From Marketplace）**

在 VS Code 扩展面板搜索 `Burgundy Cream Theme`，或访问：

https://marketplace.visualstudio.com/items?itemName=lilinhuang.burgundy-cream-theme

Search for `Burgundy Cream Theme` in the Extensions view, or open the link above.

## 项目结构 · Files

```
burgundy-cream-theme/
├── package.json                         # 扩展清单
├── README.md
├── assets/
│   └── icon.png                         # 商店图标
└── themes/
    ├── burgundy-cream-light-color-theme.json
    └── burgundy-cream-dark-color-theme.json
```

## License

Non-Commercial License — see `LICENSE.md`.

# 🎨 Markdown/HTML to WeChat Editor 

> 🚀 一个专注于将 Markdown 与 自定义 HTML 完美转换为微信公众号排版的纯前端工具。

[![Version](https://img.shields.io/badge/version-PRO_v5.0-blue.svg)]()
[![License](https://img.shields.io/badge/license-MIT-green.svg)]()

## ✨ 核心特性 / Features

*   **⚡️ 深度 HTML 解析引入**: 独创 `导入 HTML` 解析功能，底座采用 `Turndown.js` 引擎。无论是网页片段还是从其他编辑器导出的源码，均可一键逆向转换回纯正的 Markdown。
*   **📐 微信专属排版引擎 (ConvertEngine)**: 彻底解决微信公众号编辑器吞噬样式的痛点。自动处理行内 CSS (Inline CSS) 注入，将 Flex/绝对定位 等不兼容样式动态转译为适配微信的结构（如 Table/Margin Overlap 等机制），**真正实现 100% 排版还原**。
*   **📦 纯前端零依赖**: 无需后端服务器，即开即用的单 HTML 文件应用，保障所有数据与隐私均在本地浏览器处理。
*   **🎨 专业级多主题矩阵**: 
    *   🌾 **田园暖色 (Warm Earth)**: 暖米色棕色搭配，适合文化/乡土/阅读类。
    *   💎 **经典海洋 (Lapis)**: 科技蓝极简配色，完美匹配 IT 技术分享。
    *   ⬛ **极简黑白 (Minimal BW)**: 纯黑白，最极客的分析/架构文本首选。
    *   🥧 **橙彩小调 (Pie)**: 温暖桔色排版，生活记录最佳搭档。
*   **💻 强悍的开发功能**: 
    *   内建 `CodeMirror` 强大编辑器，支持代码高亮与自动补全。
    *   自动识别并美化代码块，生成 Mac 风格红绿灯窗口边框。
    *   内置 `MathJax 3.0` 支持，完美渲染 LaTeX 复杂数学公式，并以原生 SVG 格式导出至微信。

## 🎯 效果预览 / Showcase

### 直观的模板库与多主题
工具包含精美的 "Gallery" 视图，供创作者快速预览并选择属于自己文字的骨架。

### 简洁清爽的沉浸式编辑区
左侧 `CodeMirror` 源码编辑，右侧模拟真实手机 `Viewport` 的实时渲染预览，让每次修改所见即所得。

## 🚀 快速开始 / Quick Start

无需繁琐的 `npm install`。 

1. 将本项目克隆到本地：
    ```bash
    git clone https://github.com/Luchen-0420/markdown2html.git
    ```
2. 直接在浏览器中双击打开 `html-to-wechat-pro.html` 文件。
3. （可选）点击顶部工具栏的 **[📄 导入 HTML]** 尝试逆向解析外部网页片段。
4. 撰写完毕后，点击右侧的 **[📋 复制到微信]** 按钮。
5. 前往 [微信公众平台草稿箱](https://mp.weixin.qq.com/) 粘贴（Ctrl+V / Cmd+V），发布！

## 📚 扩展语法支持 / Extended Syntax

除标准 Markdown 外，本工具针对微信排版提供了一层拓展块语法糖：

```markdown
> [!intro]
> 导读文本内容

> [!tip] 提示框标题
> 提示框里的重要说明内容...

> [!ending]
> # 结语标题
> 这是一段优美的结束语...
```

## 🛠 技术栈 / Tech Stack

*   [Marked.js](https://marked.js.org/) - 用于高效的 Markdown 解析
*   [Turndown.js](https://github.com/mixmark-io/turndown) - HTML to Markdown 的逆向魔法
*   [CodeMirror 5](https://codemirror.net/5/) - 坚如磐石的文本编辑器组件
*   [MathJax 3](https://www.mathjax.org/) - 极致美观的数学公式排版支撑

## 📄 许可证 / License

本项目采用 [MIT License](LICENSE) 开源。欢迎各类二次开发与改进。

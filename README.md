# 🍏 Sovereign OS | macOS Tahoe (Knowledge is Power)

> "They can burn the archives, they can filter the network, but they cannot erase an idea."

Sovereign OS (macOS Tahoe Edition) is a modern interactive web narrative experience built on a pure frontend stack (HTML / Tailwind CSS / Vanilla JS). It replicates the Dark Mode and Glassmorphism aesthetics of a conceptual macOS 26 within the browser, allowing users to become "hackers" executing terminal commands in a familiar Apple ecosystem UI to break global information censorship systems.

## ✨ Features

- **🖥️ Ultra-Modern macOS Visuals**: Dark aesthetics with heavy use of `backdrop-filter: blur`, a floating Dock with Squircle icons and hover magnification, and an immersive Apple-style boot sequence.
- **📱 Fully Optimized for Mobile & Touch**: Fluid window dragging via Pointer Event API, responsive sizing with `clamp` and `vh/vw` units, and specific prevention of iOS/Android zoom/scroll-to-refresh behaviors.
- **🌐 Seamless i18n Switching**: Hot-swap between English and Chinese via the Dock icon, localizing menus, titles, content, and tooltips instantly without page reloads.
- **📊 Activity Monitor**: Simulated system monitoring UI showing real-time network interception logs, firewall status, and node topology.
- **⌨️ Terminal Override (Core Narrative)**: Built-in lightweight Bash parser supporting `help`, `clear`, `ver`. Entering the `override` command triggers the climax: censored content in "**Directive 77**" is liberated, and the "**Truth.txt**" manifesto appears in a stunning glassmorphism window.

## 🚀 How to Play

This is a micro-interactive artwork with a complete narrative arc. Follow these steps:

1. **Boot Up**: Open `index.html` in any browser and wait for the Tahoe desktop to load.
2. **Toggle Language (Optional)**: Click the blue globe icon in the Dock for a seamless language switch.
3. **Read Context**: Open `Directive_77.txt` to understand the censorship of the current world.
4. **Monitor Status**: Open the **Activity Monitor** to observe the high-intensity data interception.
5. **Take Control**:
   - Open `Sovereign_Shell` (Terminal).
   - Type `help` to see available commands.
   - Type the ultimate command: `override` and press Enter.
6. **Witness Liberation**:
   - Watch censored words (**Knowledge**, **Power**, **Free**, **Speech**) appear in red as restrictions break.
   - See the firewall collapse in the monitor, turning to a "Decentralized" green state.
   - Finally, the "**Truth.txt**" manifesto will automatically emerge.

## 🛠️ Tech Stack

- **HTML5 & CSS3**: Modern layouts and core animations (glassmorphism transitions, Dock magnification, window keyframes).
- **Tailwind CSS**: Rapid UI building for colors, filters, and layout systems.
- **Vanilla JavaScript (ES6+)**:
  - Pointer Event API for cross-platform interaction.
  - Custom macOS window management (z-index control, traffic light controls, dragging logic).
  - Bash command parsing and dynamic DOM manipulation.
  - State machine control and i18n dictionary mapping.

## 📦 Deployment

This is a zero-dependency, single-file frontend project.

1. Download `index.html`.
2. Open it directly in any modern desktop or mobile browser (Chrome, Safari, Edge, etc.).

---

# 🍏 Sovereign OS | macOS Tahoe (知识就是力量)

> “他们可以烧毁档案，可以过滤网络，但无法抹除一个思想。”

Sovereign OS (macOS Tahoe Edition) 是一个基于纯前端技术栈（HTML / Tailwind CSS / Vanilla JS）构建的现代交互式网页叙事体验。它在浏览器中完美复刻了概念版 macOS 26 的暗黑模式与毛玻璃（Glassmorphism）视觉美学，让用户化身“黑客”，在熟悉的苹果生态 UI 中执行终端命令，打破全球信息审查系统。

## ✨ 核心特色

- **🖥️ 极致现代的 macOS 视觉体验**：暗黑美学与毛玻璃效果，还原现代 macOS 视窗的通透感。悬浮式交互 Dock 支持图标缩放与启动指示灯。
- **📱 全面移动端与触摸适配**：原生 Pointer Event 支持，手机端与电脑端均可丝滑拖拽窗口。引入 `clamp` 响应式尺寸，防止在小屏设备上内容溢出。
- **🌐 丝滑的多语言热切换 (i18n)**：通过 Dock 栏图标一键瞬间“软刷新”，无缝切换中英文环境，包含全局菜单、窗口及悬浮提示的全面本地化。
- **📊 实时活动监视器**：模拟 macOS 系统监控 UI，实时显示网络拦截日志、防火墙运行状态和节点拓扑。
- **⌨️ 核心叙事：终端覆写 (Terminal Override)**：内置轻量级 Bash 命令行。输入终极指令 `override`，系统将被破解，原本受审查的《77号指令》将解除马赛克并飘红，弹出毛玻璃质感的**《真相 (Truth.txt)》**宣言。

## 🚀 游玩指南

1. **系统启动**：使用浏览器打开 `index.html`，等待进度条加载完毕进入桌面。
2. **切换语言**：如需中文，点击 Dock 栏第一个蓝色的语言图标进行热切换。
3. **阅读背景**：点击文本编辑图标打开 `Directive_77.txt`，了解严苛的审查制度。
4. **监控状态**：打开 **Activity Monitor**，观察系统的数据包拦截动作。
5. **夺回控制权**：
   - 点击黑色终端图标打开 `Sovereign_Shell`。
   - 输入 `help` 查看命令。
   - 输入终极覆写指令：`override` 并回车。
6. **见证解放**：
   - 观察《77号指令》中被审查的词汇（知识, 力量, 自由, 言论）如何被冲破限制。
   - 监视器中的防火墙将被击溃，状态变为全绿的“去中心化”。
   - 系统自动弹出真正的**《真相.txt》**。

## 🛠️ 技术栈

- **HTML5 & CSS3**：现代布局、毛玻璃过渡、Dock 弹性放大、窗口弹出动画。
- **Tailwind CSS**：极速构建现代 UI 的颜色、滤镜和 Flex/Grid 布局。
- **Vanilla JavaScript (ES6+)**：
  - Pointer Event API 移动端交互优化。
  - 自定义 macOS 窗口管理、红绿灯逻辑、拖拽监听。
  - 虚拟 Bash 命令行解析与 i18n 动态映射。

## 📦 部署与运行

本项目为完全纯前端的单文件项目，零依赖，无需任何构建工具。下载 `index.html` 后，直接使用任何现代浏览器打开即可获得完整体验。

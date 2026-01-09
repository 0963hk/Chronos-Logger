# ⏳ Chronos Logger

> **Capture your day, second by second.**
> <br> 一个极简、无干扰、基于浏览器的每日活动记录工具。

## 📖 简介 (Introduction)

**Chronos Logger** 是一个单文件的 HTML 应用程序，旨在帮助开发者、学生和效率爱好者记录每日的时间流向。

它完全运行在您的浏览器中，利用 `LocalStorage` 保存数据，并在每天的 **23:59** 自动将当天的记录生成为 `.txt` 报告并下载到本地，确保您永远不会忘记这一天做了什么。

## ✨ 功能特性 (Features)

* **🔒 隐私优先**：所有数据仅存储在您的浏览器本地 (LocalStorage)，不上传任何服务器。
* **🌚 沉浸式暗黑模式**：基于 Cyberpunk/Minimalist 风格的 UI 设计，适合长时间开启。
* **⚡ 实时记录**：
    * 支持手动修改时间戳。
    * 支持回车键 (Enter) 快速添加。
    * 支持点击已录入的条目进行二次编辑。
* **🤖 自动化归档**：
    * **倒计时显示**：右上角实时显示距离“每日结算”的剩余时间。
    * **自动下载**：每天 23:59 自动导出当天的 `DailyReport_YYYY-MM-DD.txt` 并清空列表。
* **📂 手动导出**：随时点击下载按钮导出当前进度，不会清空列表。

## 🚀 快速开始 (Getting Started)

### 方法 1：直接使用
1. 下载本仓库中的 `index.html`。
2. 双击在浏览器中打开即可使用。

### 方法 2：部署到 GitHub Pages (推荐)
1. Fork 本仓库。
2. 进入仓库 `Settings` -> `Pages`。
3. 在 `Branch` 选项中选择 `main` (或 `master`) 并保存。
4. 等待几分钟，GitHub 会生成一个专属链接，您可以在任何设备上访问。

## 📝 使用指南 (Usage)

1. **记录任务**：在输入框中输入正在做的事情，按 `Enter` 或点击 `LOG`。
2. **调整时间**：默认记录当前时间。点击左侧的时间输入框可手动指定时间。
3. **编辑记录**：点击列表中的任何时间和文字即可直接修改；点击 `×` 删除条目。
4. **保存报告**：
    * 等待至 23:59 自动保存。
    * 或点击右上角的下载图标 (📥) 手动保存。

## 🛠️ 技术栈 (Tech Stack)

* HTML5
* CSS3 (Flexbox, CSS Variables, Animations)
* Vanilla JavaScript (ES6+)
* No External Dependencies (无第三方库)

## 📄Bug反馈
请联系：jzhongau@connect.ust.hk

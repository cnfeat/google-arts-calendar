# 🎨 Google 艺文日历

[![](https://img.shields.io/github/v/release/cnfeat/google-arts-calendar?style=flat-square)](https://github.com/cnfeat/google-arts-calendar/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Google 艺文日历** 是一款专为 Tampermonkey 设计的用户脚本，旨在为 Google 艺术与文化爱好者提供一个集成且高效的浏览环境。

该脚本通过克服跨域 iframe 安全限制，将 **edui123 日历** 以一个可交互、可拖拽的精简浮动窗口形式，完美叠加在 **Google 艺术与文化** 的页面上。同时，它还会自动化滚动页面，让您第一时间看到每日精选艺术品。

---

## ✨ 核心功能亮点

* **双内容高效整合：** 在一个页面上同时浏览 Google 艺术与文化的主页内容和 edui123 日历。
* **内容净化与适配：** 脚本自动移除日历网站的冗余信息，并精确适配 612x899 的内容比例。
* **自动定位：** 页面加载时瞬间滚动到“今日精选”的标题位置。
* **灵活的浮窗控制：** 浮窗默认贴合左侧边缘，支持**拖拽移动**、**调整大小**和**一键关闭**。

---

## 🛠️ 安装指南 (极简流程)

请确保您已在浏览器中安装了 **Tampermonkey** 扩展程序。

### 步骤一：获取脚本代码

1.  访问本仓库中的脚本文件：`https://raw.githubusercontent.com/cnfeat/google-arts-calendar/main/google-arts-calendar.user.js`
2.  复制该链接内容，或直接点击 Tampermonkey 提供的安装按钮。

### 步骤二：创建并粘贴脚本

1.  点击 Tampermonkey 图标，选择 **【添加新脚本...】**。
2.  清空编辑器中所有的默认内容。
3.  将 **步骤一** 复制的完整代码粘贴到编辑器中。
4.  点击 **【文件】** 菜单，选择 **【保存】**。

### 步骤三：刷新页面

1.  打开或刷新 Google 艺术与文化页面：`https://artsandculture.google.com/`

**验证结果：** 页面将瞬间滚动至“今日精选”，左上角出现可拖拽的 **【edui123 日历】** 浮动窗口。

---

## 📜 许可证

本项目基于 **MIT 许可证** 发布。

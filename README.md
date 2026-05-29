# 📝 期末评语全自动智能生成器 (End-of-Term Report Comment Generator)

![Version](https://img.shields.io/badge/version-1.1.0-blue)
![Platform](https://img.shields.io/badge/platform-GitHub%20Pages-brightgreen)
![LLM](https://img.shields.io/badge/Powered%20by-DeepSeek%20%7C%20Claude-blue)

一个专为**班主任 (Homeroom Teacher)** 与 **ICT 学科老师 (ICT Teacher)** 量身定制的期末全英文评语全自动生成工具。界面采用优雅的**天青石蓝 (Lapis Lazuli)** 色调，支持在网页端一键勾选学生特质，秒级生成符合国际化学校标准的单段落纯英文期末评语。

🌐 **[点击立即访问在线工具](https://gaiasheep.github.io/End_of_Term_Report_Comment_Generator/)**

---

## ✨ 核心亮点 (Key Features)

- **🎭 双角色智能切换**：一键切换“班主任”或“ICT学科老师”模式，动态匹配不同角色的评语侧重点。
- **💻 ICT 学科深度定制**：内置 MS Word, MS Excel, Block Coding, Web Development, Python, MS Access 等高频信息技术模块，评语自带学科含金量。
- **📊 成绩与趋势智能联动**：支持 A+~D 等第及学业走势分析，同时提供 **"无 (N/A)"** 选项（作为默认值，专为不清楚具体分数的班主任或未设置等第的场景设计），不生搬硬套。
- **✍️ 自由度极高的 Others 兜底**：除了高频标签，提供自定义优势与提升点输入框，捕捉每位学生的独特闪光点。
- **📋 完美适配 Excel / Notion 表格**：底层 Prompt 严格限制 AI 仅输出**单一连贯段落**，无换行、无编号、无解释，复制即用，排版绝不崩溃。
- **🔒 安全与持久化记忆**：纯前端架构，API Key 安全地存储在您本地浏览器的 `localStorage` 中，绝不上传任何第三方服务器，且刷新页面无需重复输入。

---

## 🚀 快速上手指南 (Quick Start)

### 第一步：配置大模型 API (仅需一次)
1. 打开网页，展开顶部的 **API 配置区域**。
2. 填入您的 **DeepSeek API Key**（或兼容 OpenAI 格式的中转 Key）。
3. 默认 Base URL 已配置为官方通道，检查无误后折叠该区域（浏览器会自动记住它）。

### 第二步：勾选并一键生成
1. 选择您的教师角色，并输入学生姓名与性别（自动匹配英文代词 He/She）。
2. 根据实际情况勾选成绩等第、学业趋势（若不需要可保持默认的 `N/A`）以及相关的知识技能。
3. 在优势与有待提升区域勾选高频关键词，如有特殊表现可在 `Others` 框中补充。
4. 点击 **✨ 智能生成评语 (Generate Comment)**。

### 第三步：复制带走
在最下方的精美文本框中，点击 **📋 一键复制 (Copy)** 按钮，直接粘贴进您的 Report 系统、Excel 或 Notion 表格中。

---

## 🛠️ 技术栈 (Tech Stack)

本工具由以下硬核科技友情驱动：
- **Frontend**: HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript (纯原生，无第三方依赖)
- **Design & Architecture**: 由 **Claude AI** 协同进行卓越的 UI 设计与前端架构
- **AI Brain**: 后台由 **DeepSeek-v4** 大模型提供高性价比、极具国际范儿的地道英文润色
- **Hosting**: 托管于 **GitHub Pages**，提供 100% 稳定的静态网页服务

---

## 📩 联系与交流 (Get in Touch)

如果您在使用过程中有任何建议、想要新增常用标签，或者想探讨如何升级为 **200人一键全自动 Excel 批量导出大版本**，欢迎随时联系我：

- **Author**: Gaia Yang
- **Email**: [gaiayang.edu@gmail.com](mailto:gaiayang.edu@gmail.com)
- **Workflow Workstation**: Powered and embedded beautifully within **Notion**

---

<p align="center">
  Crafted with 💻 and ❤️ by Gaia Yang | Powered by Claude AI, DeepSeek & GitHub
</p>

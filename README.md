<p align="center">
  <h1 align="center">🎮 GameForge · 游戏企划工坊</h1>
  <p align="center">
    <strong>AI 驱动的游戏设计文档（GDD）生成器</strong><br>
    支持 OpenAI / Claude 及兼容接口 · 单文件 · 零依赖
  </p>
  <p align="center">
    <a href="https://github.com/Baijidot/gameforge/releases"><img src="https://img.shields.io/github/downloads/Baijidot/gameforge/total?style=flat-square&color=blueviolet" alt="Downloads"></a>
    <a href="https://github.com/Baijidot/gameforge/releases/latest"><img src="https://img.shields.io/github/downloads/Baijidot/gameforge/latest/total?style=flat-square&color=green" alt="Latest Downloads"></a>
    <a href="https://github.com/Baijidot/gameforge/releases"><img src="https://img.shields.io/github/v/release/Baijidot/gameforge?style=flat-square&color=orange" alt="Version"></a>
    <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License">
    <img src="https://img.shields.io/badge/HTML-单文件应用-orange?style=flat-square" alt="Single File">
    <img src="https://img.shields.io/badge/支持-中%2F英-blue?style=flat-square" alt="i18n">
  </p>
</p>

---

## ✨ 功能一览

### 🎯 文档生成
| 功能 | 说明 |
|------|------|
| AI 文档生成 | 输入游戏创意，一键生成专业级 GDD |
| SSE 流式输出 | 实时查看生成过程 |
| 19 种游戏类型 | 冒险、解谜、生存、策略、休闲、RPG、动作、模拟、恐怖、沙盒、竞速、体育、陪伴养成、社交、音乐节奏、视觉小说、放置挂机、教育、其他 |
| 批量生成 | 一次输入多个创意，批量生成多份企划 |

### ✏️ 文档编辑
| 功能 | 说明 |
|------|------|
| 文档可编辑 | 点击编辑按钮直接修改内容 |
| AI 润色 | 输入修改要求，AI 对整篇文档润色 |
| 章节单独重生成 | 悬停章节标题，点击按钮仅重写该章节 |
| 文档追问 | 生成完成后继续追问，AI 输出修改后的完整文档 |
| 从已有文档导入 | 粘贴或上传已有 GDD，在此基础上修改/续写 |

### 🔬 分析与工具
| 功能 | 说明 |
|------|------|
| 竞品快速调研 | 输入竞品游戏名称，AI 详细拆解玩法、商业化、美术、核心系统等，可一键插入文档 |
| 美术资源分析 | AI 自动分析文档需要的美术资源，列出清单后可选中，一键生成可用于 Midjourney / SD / DALL·E 的英文 Prompt |
| 多文档对比 | 选择两份历史文档并排 diff，查看差异 |
| 项目数据提取 | 自动从文档提取技术栈、人员需求、里程碑 |

### 🧠 Prompt 系统
| 功能 | 说明 |
|------|------|
| 5 种提示词预设 | 默认 / 详细版 / 投资人版 / 技术侧重 / 叙事侧重 |
| 自定义 Prompt | 自由编辑系统提示词 |
| 企划模板库 | 8 个预设模板（动作RPG、生存建造、叙事解谜、休闲合成、塔防策略、陪伴养成、恐怖探索、音乐节奏） |

### 📤 导出
| 功能 | 说明 |
|------|------|
| 导出 PDF | 通过浏览器打印生成 PDF |
| 导出 Word (.doc) | 生成 Word 兼容格式 |
| 下载 Markdown | 下载 .md 源文件 |
| 复制全部 / 复制 SOLO Prompt | 一键复制 |

### 🎨 界面与体验
| 功能 | 说明 |
|------|------|
| 暗色模式 | 亮色/暗色主题切换，选择持久化 |
| 中英双语 | 中文 / 英文切换，覆盖全部 UI |
| 目录导航 | 右侧 TOC 侧边栏，点击跳转 + 滚动高亮 |
| 历史记录 | 自动保存最近 20 条记录 |
| 响应式设计 | 适配桌面和移动端 |

---

## 🚀 快速开始

1. 下载 [gameforge.html](https://github.com/Baijidot/gameforge/releases)
2. 用浏览器打开
3. 点击右上角 **⚙ 设置**，配置 API
4. 输入游戏创意 → 点击 **生成企划**
5. 使用追问、编辑、润色等功能完善文档
6. 导出为 PDF / Word / Markdown

---

## ⚙️ API 配置

### OpenAI 兼容接口

支持所有 OpenAI 兼容 API（OpenAI、DeepSeek、智谱 GLM、通义千问、硅基流动等）。

| 字段 | 说明 | 示例 |
|------|------|------|
| API 地址 | Base URL | `https://api.openai.com/v1` |
| API Key | 密钥 | `sk-...` |
| 模型 | 模型 ID | `gpt-4o` / `deepseek-chat` / `glm-4-flash` |

### Claude

| 字段 | 说明 | 示例 |
|------|------|------|
| API Key | Anthropic 密钥 | `sk-ant-...` |
| 模型 | 模型 ID | `claude-sonnet-4-20250514` |

> **注意**：部分 API 服务可能不支持浏览器直接调用（CORS 限制）。

---

## ⌨️ 快捷键

| 快捷键 | 功能 |
|--------|------|
| `Ctrl/Cmd + Enter` | 生成文档 |
| `Ctrl/Cmd + S` | 退出编辑模式 |
| `Esc` | 关闭弹窗 |

---

## 🛠️ 技术说明

- **单文件应用** — 纯 HTML + CSS + JavaScript，无需构建工具
- **零外部依赖** — 不依赖任何第三方库或 CDN
- **数据本地存储** — 所有配置和历史记录保存在浏览器 localStorage
- **内置 Markdown 渲染** — 支持标题、表格、列表、引用、代码等
- **SSE 流式传输** — 实时输出，120s 请求超时 + 180s 流超时
- **非流式兼容** — 竞品调研、数据提取、美术分析等功能使用非流式请求，兼容不支持 SSE 的模型（如 Qwen3）

---

## 📋 更新详情

### v1.2.0

**新增功能**
- 🔬 **竞品快速调研** — 输入竞品游戏名称，AI 自动生成详细拆解报告（玩法、商业化、美术风格、核心系统），支持一键插入文档
- 🎨 **美术资源分析** — AI 自动分析 GDD 中需要的美术资源，生成分类清单（角色/场景/UI/图标等），选中后一键生成 Midjourney / Stable Diffusion / DALL·E 可用的英文 Prompt
- 📊 **项目数据提取** — 自动从文档中提取技术栈、人员需求、里程碑等关键数据
- 📝 **企划模板库** — 内置 8 个预设模板（动作RPG、生存建造、叙事解谜、休闲合成、塔防策略、陪伴养成、恐怖探索、音乐节奏）

**优化改进**
- ⚡ 新增非流式请求兼容模式，支持 Qwen3 等不支持 SSE 的模型
- ⚡ 优化 API 响应处理：自动检测 Content-Type，兼容 JSON/SSE 混合响应
- ⚡ 美术资源 Prompt 生成支持动态 max_tokens，按选中资源数量自动调整
- 🌐 完善中英双语翻译覆盖，新增竞品调研、美术分析等模块的英文翻译
- 🐛 修复流式生成后 `currentDocument` 可能为空的问题（新增 DOM 安全网机制）
- 🐛 修复 Qwen3 模型输出 `💭` 思考标签导致内容异常的问题

### v1.1.0

**新增功能**
- ✏️ **文档编辑模式** — 点击编辑按钮直接修改生成内容
- 🤖 **AI 润色** — 输入修改要求，AI 对整篇文档进行润色
- 🔄 **章节单独重生成** — 悬停章节标题，点击按钮仅重写该章节
- 💬 **文档追问** — 生成完成后继续追问，AI 输出修改后的完整文档
- 📂 **文档导入** — 粘贴或上传已有 GDD，在此基础上修改/续写
- 📋 **多文档对比** — 选择两份历史文档并排 diff，查看差异
- 🎯 **5 种提示词预设** — 默认 / 详细版 / 投资人版 / 技术侧重 / 叙事侧重

**优化改进**
- 📑 新增右侧 TOC 目录导航，点击跳转 + 滚动高亮
- 💾 历史记录扩展至 20 条
- 🌐 UI 全面支持中英双语切换

### v1.0.0

- 🎮 **首次发布**
- AI 文档生成（SSE 流式输出）
- 19 种游戏类型支持
- 批量生成（多创意并行）
- 导出 PDF / Word / Markdown
- 暗色模式
- 响应式设计

---

## 📦 下载

前往 [Releases](https://github.com/Baijidot/gameforge/releases) 下载最新版。

只需一个 `gameforge.html` 文件，浏览器打开即用。

---

## 👤 作者

**白芨**

- GitHub: [@Baijidot](https://github.com/Baijidot)
- 哔哩哔哩: [Ourane](https://space.bilibili.com/292001394)
- 📖 介绍文章: [GameForge 游戏企划工坊 - AI 驱动的 GDD 生成器](https://forum.trae.cn/t/topic/8220/)

---

## 📄 License

[MIT](LICENSE)

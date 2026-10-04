<div align="center">

# 你好，我是 sora (mo9652962-ai) 👋

**独立开发者 · 专注于「工业制造 CAD/EDA × AI 智能体自举 × 本地优先架构」**

*数据归用户所有 · 工业级确定性与规范约束 · AI 作为专业赋能层而非黑盒依赖*

<p align="center">
  <a href="https://github.com/mo9652962-ai?tab=repositories"><img src="https://img.shields.io/badge/Repositories-14_Public-2563EB?style=flat-square&logo=github" alt="Repositories"></a>
  <a href="https://github.com/mo9652962-ai/circuit-agent"><img src="https://img.shields.io/badge/Hardware-CircuitAgent-blueviolet?style=flat-square&logo=kicad&logoColor=white" alt="CircuitAgent"></a>
  <a href="https://github.com/mo9652962-ai/wave-fixture-ai"><img src="https://img.shields.io/badge/Manufacturing-WaveFixture_AI-059669?style=flat-square" alt="WaveFixture AI"></a>
  <a href="https://github.com/mo9652962-ai/english-multiple-choice-practice-machine"><img src="https://img.shields.io/badge/App-墨题_MOTI-c73e3a?style=flat-square" alt="墨题 MOTI"></a>
  <a href="https://github.com/mo9652962-ai/second-brain"><img src="https://img.shields.io/badge/Second_Brain-760+_Notes-7C3AED?style=flat-square&logo=obsidian" alt="Second Brain"></a>
</p>

</div>

---

## 🌟 四大旗舰工程 (Flagship Projects)

### ⚡ [CircuitAgent · AI 硬件合成与工业电路编译器](https://github.com/mo9652962-ai/circuit-agent)
> **Prompt → Schematic → Layout → 3D Enclosure: 面向制造的 AI 硬件合成系统与 MCP 协议栈**

* 🧩 **CircuitBlocks 确定性硬件 DSL**：摒弃大模型自由画线的短路幻觉，将电路意图约束于 19+ 预审核硬件积木，实现引脚级仲裁与零电气错误。
* 🏭 **全链路制造闭环**：内置免 Key 的嘉立创 LCSC 元件实时检索、IPC-2152 载流/温升热仿真、IPC-2221 高压安全爬电间距计算与工业 DFX 审核门禁。
* 🔌 **14 个标准化 MCP 工具**：已上架 MCP Registry，支持导出标准 KiCad 网表、JLCPCB 贴片 BOM 与 CPL 坐标文件。
* 🧪 **240 项单元测试全通过**，严苛的 Contract-Sync 契约防漂移守卫与确定性 CI 构建。

`Python` `KiCad` `EDA` `JLCPCB` `MCP` `Hardware DSL` `IPC-2152` `MIT`

---

### 🏭 [WaveFixture AI · 波峰焊治具 AI 设计助手](https://github.com/mo9652962-ai/wave-fixture-ai)
> **Gerber 进 · 治具工程图出 · 21 项制造业自动化 · 会听人话的专业 CAD 助手**

* 🛠️ **全流程自动化**：拖入 PCB Gerber 生产文件，全自动生成沉板区、取手位、避位区、上锡区、压扣孔、定位销与治具外形，一键导出生产级 DXF / STL / GLB 及数控 CNC G 代码。
* 📏 **26 条严苛 DRC 规则与 28 项自然语言参数**：支持「避位区外扩 1mm」等语义参数确定性调节，内建元件高度与波峰锡流干涉消除分析。
* 🛡️ **高可靠工程标准**：**232 项测试全部通过**，通过 **OpenSSF Scorecard** 供应链安全认证，支持本地 Web 界面交互与 GitHub Action 自动化门禁。

`Python` `Gerber` `DXF` `CAD` `KiCad` `CNC` `工业自动化` `MIT`

---

### 📚 [墨题 MOTI · 东方水墨 × 3D 认知计算本地英语刷题机](https://github.com/mo9652962-ai/english-multiple-choice-practice-machine)
> **面向考研 / 四六级 / 高考的 Local-First 离线开源英语客观题刷题工作台**

* 🖥️ **跨平台现代架构**：Windows 桌面端 / Web 端 / Android 端全覆盖，支持标准 ESQ 1.0 开放题库包与 Word 真题草稿自由导入导出。
* 🧠 **认知科学驱动**：内置先进 **FSRS-4.5 智能间隔复习算法**，错题迭代递减队列（越做越少），12 套自建模拟卷 + 7,959 词全类别核心词库（7,951 词带音标与语境义）。
* 🔒 **100% 本地优先**：所有做题记录、笔记与生词本存储于本地 SQLite WAL 数据库，隐私完全归用户所有；提供可选的 AI 启发式错题精讲、智能作文批改与陪伴聊天。
* 🎨 **3D 水墨交互官网**：搭载基于 Three.js 与 GSAP 的 3D 卷轴解构视效与认知雷达图。

`Vue 3` `FastAPI` `SQLite` `Capacitor` `Three.js` `FSRS` `Local-First` `GPL-3.0`

---

### 🧠 [Second Brain — AI Agent 第二大脑](https://github.com/mo9652962-ai/second-brain)
> **持续自我进化的全中文 Obsidian 知识库 · 760+ 篇公开知识资产 · 18 域全景拓扑**

* 🔄 **七大自举进化系统**：工具自愈、上下文记忆四级体系、输出风格对齐、代码质量门禁、知识吸收底线、自动化可靠性，构建可从错误中学习的活系统。
* 🧭 **千轮实证研究引擎**：覆盖硬件 EDA、单片机固件、现代 Web 全栈、自动化测试与学术论文工程，所有前沿项目的架构决策均源于此知识底座。
* ✨ **3D 全景沉浸式官网**：支持 WebGL 3D 知识拓扑宇宙、MkDocs 静态文档站及 `llms.txt` AI 直读协议。

`Obsidian` `AI Agent` `Hermes` `知识工程` `Three.js` `MIT`

---

## 🛠️ 专业工具链与生态矩阵 (Tools & Ecosystem)

| 仓库 | 定位 | 特色与亮点 | 协议 |
|:---|:---|:---|:---:|
| 🛡️ **[agent-audit](https://github.com/mo9652962-ai/agent-audit)** | AI Agent 环境安全审计 CLI | 7 项只读环境体检（供应链/密钥/端口/MCP），对齐 OWASP & NSA CSI，提供 [Marketplace Action](https://github.com/marketplace/actions/agent-audit) | `MIT` |
| 📦 **[esq-builder-mcp](https://github.com/mo9652962-ai/esq-builder-mcp)** | ESQ 开放题库 MCP 工具链 | 构建（自动修复机械坑）→ 校验（双轨）→ 上传发布，已上架 MCP Registry | `MIT` |
| 🧹 **[skill-maintenance-mcp](https://github.com/mo9652962-ai/skill-maintenance-mcp)** | 技能库运维 MCP | 自动完成技能修改前备份、损坏扫描、决策留痕与体检，消除机械失误 | `MIT` |
| 🎯 **[quiz-assistant](https://github.com/mo9652962-ai/quiz-assistant)** | 本地优先题库 CLI | 墨题轻量前身，标准库 + SQLite 零依赖，支持 SM-2 算法与分层模糊匹配 | `MIT` |

---

## 🧰 技术栈全景 (Tech Stack & Capabilities)

<div align="center">

### 核心语言 & 运行时
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### 工业制造 & 硬件 EDA
![KiCad](https://img.shields.io/badge/KiCad-10.0-314CE0?style=flat-square&logo=kicad&logoColor=white)
![Gerber](https://img.shields.io/badge/Gerber-RS--274X-4A5568?style=flat-square)
![DXF](https://img.shields.io/badge/AutoCAD-DXF_R2000-E53E3E?style=flat-square)
![CNC G-Code](https://img.shields.io/badge/CAM-CNC_G--Code-2B6CB0?style=flat-square)
![IPC Standards](https://img.shields.io/badge/IPC-2152%20%2F%202221-D69E2E?style=flat-square)
![LCSC & JLCPCB](https://img.shields.io/badge/Sourcing-LCSC%20%26%20JLCPCB-0052CC?style=flat-square)

### 现代前端 & 可视化
![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)

### AI Agent 协议与工程架构
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-black?style=flat-square)
![OWASP](https://img.shields.io/badge/Security-OWASP_Top_10-0284C7?style=flat-square)
![FSRS](https://img.shields.io/badge/Algorithm-FSRS--4.5-C026D3?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

<div align="center">

### 🤝 链接与支持 (Connect & Star)

如果这些开源项目对你的工程实践或学习有所启发，欢迎给对应的仓库点个 **⭐ Star**！  
你的支持是持续打磨、开源更多工业级实战工具的最大动力。

[![GitHub stars](https://img.shields.io/github/stars/mo9652962-ai?style=social)](https://github.com/mo9652962-ai)

</div>

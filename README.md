# 🛠️ AI Cognitive Disruptor Skill — 让 AI 跳出思维框架

<p align="center">
  <img src="https://img.shields.io/badge/Pattern-Prompt_as_Code-00ADD8?style=for-the-badge&logo=github" alt="Prompt as Code" />
  <img src="https://img.shields.io/badge/Target-Software_Engineering-FF6F00?style=for-the-badge&logo=visualstudio" alt="Software Engineering" />
  <img src="https://img.shields.io/badge/Paradigm-Cognitive_Disruption-8B5CF6?style=for-the-badge&logo=brain" alt="Cognitive Disruption" />
  <img src="https://img.shields.io/badge/Status-Active_Development-22C55E?style=for-the-badge&logo=vercel" alt="Active Development" />
</p>

---

## 📋 目录

- [🌟 核心理念：为什么需要这个项目](#-核心理念为什么需要这个项目)
- [🗂️ 仓库架构](#️-仓库架构)
- [⚙️ 技能总览](#️-技能总览)
- [📖 如何使用这些技能](#-如何使用这些技能)
- [🤖 自动加载规则](#-自动加载规则)
- [🧠 使用场景](#-使用场景)
- [📁 目录结构](#-目录结构)
- [🤝 贡献指南](#-贡献指南)
- [📄 许可证](#-许可证)

---

## 🌟 核心理念：为什么需要这个项目

### AI 的"默认思维陷阱"

AI（大语言模型）的底层工作原理是**预测下一个最可能的词**。这意味着：

- 💬 问一个架构问题 → AI 给你最**常见**的方案
- 💬 问一个 Bug 排障 → AI 给你最**主流**的排查步骤
- 💬 问一个系统设计 → AI 给你最**流行**的技术组合

这不是 AI 的错，这是它的底层逻辑决定的。**但如果你想要的是"好答案"而非"标准答案"，你就需要一些外部的思维干预。**

### 这个项目做了什么

本项目是一个 **Prompt-as-Code** 技能引擎集合。每个技能就是一个**思维框架**，通过精心设计的指令，**强制 AI 跳出默认的思维惯性**：

| 默认思维陷阱 | 对应技能 | 如何打破 |
|-------------|----------|----------|
| "代码能跑就行" | **Arch_Decoupler** | 强制检查依赖方向、边界、接口隔离 |
| "凭经验猜 Bug" | **Debug_Analyzer** | 强制系统化二分法 + 全链路追踪 |
| "AI 给的标准答案" | **Core_Disruptor** | 强制先否定常规方案，从第一性原理推导 |
| "正向排障走不通" | **Inversion_Debugger** | 用逆向思维，"先想怎么制造 Bug" |
| "选什么框架" | **First_Principles_Architect** | 剥离工具名词，回归数据流本质 |

> 🎯 **一句话**：不是让 AI 更快地给出答案，而是让 AI 给出**更好的答案**。

---

## 🗂️ 仓库架构

```
AI-Cognitive-Disruptor-Skill/
├── 🏗️ 软件工程技能包              ← 偏向实操层面的工程技能
│   ├── prompts/                  ← 核心提示词引擎
│   ├── skills/                   ← 技能包
│   └── integrations/             ← 自动加载规则
│
└── 🌌 Universal Cognitive Disruptor  ← 偏向思维层面的认知破局
    ├── skills/                   ← 高维思维技能包
    └── integrations/             ← 自动加载规则
```

---

## ⚙️ 技能总览

### 🏗️ 软件工程技能包

覆盖架构设计、代码质量、调试排障等实操领域。

| 技能 ID | 打破的思维惯性 | 核心规则 |
|---------|--------------|----------|
| **Arch_Decoupler** | "代码能跑就行" → 架构意识 | 🛑 禁止循环依赖 · 🛑 依赖倒置 · 🛑 接口隔离 · 🛑 事件驱动 · 🛑 边界清晰 |
| **Debug_Analyzer** | "凭经验猜 Bug" → 系统化排障 | 🛑 二分法 · 🛑 可复现性优先 · 🛑 日志分层 · 🛑 全链路追踪 · 🛑 区分系统/业务错误 |

### 🌌 通用认知破局引擎

偏向思维层面的认知框架，适用于任何复杂问题。

| 技能 ID | 打破的思维惯性 | 核心方法 |
|---------|--------------|----------|
| **Core_Disruptor** | "AI 只会给标准答案" | 5 阶段 XML 状态机：否定常规 → 第一性原理 → 跨界类比 → 极端约束 → 工程方案 |
| **Inversion_Debugger** | "正向排障"的思维定式 | 逆向思维：先想"如何刻意制造这个 Bug" |
| **First_Principles_Architect** | "选型思维"而非"设计思维" | 剥离工具名词 → 本质定义 → 极限推演 → 现代映射 |

---

## 📖 如何使用这些技能

### 方式一：注入 AI System Prompt（推荐）

将对应技能的 `.md` 文件内容**直接复制到 AI 工具的 System Prompt / 自定义指令中**，然后正常提问即可。

```bash
# 复制技能内容到剪贴板
cat skills/arch_decoupler.md | clip      # Windows
cat skills/arch_decoupler.md | pbcopy    # macOS
```

```bash
# 复制认知破局引擎内容
cat Universal-Cognitive-Disruptor/skills/core_disruptor.md | clip
```

### 方式二：Trae IDE 自动加载

1. 克隆本仓库到本地
2. 在 Trae IDE 中打开项目
3. `integrations/.traerules` 会自动生效，按上下文加载对应技能

### 方式三：手动触发关键词

不想加载整个技能文件？在对话中直接说：
- **Core_Disruptor** → "请用 Core Disruptor 模式分析这个问题"
- **Inversion_Debugger** → "用逆向思维帮我推导这个 Bug 的根因"
- **First_Principles_Architect** → "请用第一性原理重新设计这个系统"
- **Arch_Decoupler** → "请用 Arch_Decoupler 原则审查这个架构"
- **Debug_Analyzer** → "请按系统化排障方法论分析这个问题"

### 方式四：组合使用

多个技能可以叠加使用，效果更佳。例如：
- 系统架构设计 → `Core_Disruptor` + `First_Principles_Architect` + `Arch_Decoupler`
- 复杂 Bug 排障 → `Debug_Analyzer` + `Inversion_Debugger`

---

## 🤖 自动加载规则

### 软件工程技能包 (`integrations/.traerules`)

```json
{
  "rules": [
    { "condition": "architecture design, refactoring, module decoupling",
      "action": "Load [Arch_Decoupler]" },
    { "condition": "bug, crash, performance issue, debugging, root cause analysis",
      "action": "Load [Debug_Analyzer]" }
  ]
}
```

### 通用认知破局引擎 (`Universal-Cognitive-Disruptor/integrations/.traerules`)

```json
{
  "rules": [
    { "condition": "架构设计 / 系统重构 / 算法优化",
      "action": "Load [Core_Disruptor] + [First_Principles_Architect]" },
    { "condition": "Bug / 崩溃 / 超时 / 死锁",
      "action": "Load [Inversion_Debugger]" }
  ]
}
```

---

## 🧠 使用场景

| 场景 | 推荐技能组合 | 效果 |
|------|-------------|------|
| 🏛️ 系统架构设计 | `Arch_Decoupler` + `Core_Disruptor` + `First_Principles_Architect` | 拒绝平庸方案，输出高维架构 |
| 🔧 代码重构/模块拆分 | `Arch_Decoupler` | 依赖倒置、接口隔离、边界清晰化 |
| 🐛 复杂 Bug 排障 | `Debug_Analyzer` + `Inversion_Debugger` | 系统化二分法 + 逆向思维定位根因 |
| 🔄 算法优化 | `Core_Disruptor` + `First_Principles_Architect` | 剥离框架，从数据流本质优化 |
| 💥 偶发崩溃/死锁 | `Inversion_Debugger` + `Debug_Analyzer` | 制造 Bug 的思维推导防御策略 |
| ⚡ 性能问题诊断 | `Debug_Analyzer` | 全链路追踪 + 日志分层分析 |
| 📦 微服务/模块拆分 | `Arch_Decoupler` + `Core_Disruptor` | Bounded Context + 事件驱动解耦 |

---

## 📁 目录结构

```
AI-Cognitive-Disruptor-Skill/
│
├── prompts/                              # 核心提示词
│   ├── core_disruptor.md                 #   Core Disruptor 引擎（XML 状态机）
│   └── domain_modifiers.json             #   领域上下文配置
│
├── skills/                               # 软件工程技能
│   ├── arch_decoupler.md                 #   架构解耦技能
│   └── debug_analyzer.md                 #   调试排障技能
│
├── integrations/                         # 集成配置
│   └── .traerules                        #   Trae IDE 自动规则
│
├── Universal-Cognitive-Disruptor/        # 通用认知破局引擎
│   ├── skills/
│   │   ├── core_disruptor.md             #   核心拦截器
│   │   ├── inversion_debugger.md         #   逆向排障器
│   │   └── first_principles_architect.md #   第一性原理架构师
│   └── integrations/
│       └── .traerules                    #   通用自动规则
│
├── README.md                             # 本文件 😊
└── .gitignore
```

---

## 🤝 贡献指南

欢迎贡献新的技能包！请遵循以下规范：

1. **文件命名**：`snake_case_技能名.md`
2. **文件头格式**：
   ```markdown
   # [Skill_ID]: Your_Skill_Name
   # [Objective]: One-line description of the skill's purpose.
   ```
3. **核心结构**：每个技能文件应包含：
   - `💡 为什么需要这个技能` — 说明它打破的是什么思维惯性
   - `🛑 约束规则` — 具体的约束条件
   - `📖 如何使用` — 使用方法说明
4. **集成规则**：在 `integrations/.traerules` 中添加对应的自动加载规则
5. **语言**：中英文均可，保持一致性即可

---

## 📄 许可证

本项目采用 **MIT License** — 自由使用、修改和分发。

---

<p align="center">
  <sub>Built with ❤️ for engineers who refuse to settle for mediocre AI outputs.</sub>
  <br>
  <sub>Made by <a href="https://github.com/7maxqq">@7maxqq</a></sub>
</p>

<p align="center">
<a href="#-ai-cognitive-disruptor-skill--让-ai-跳出思维框架">⬆️ 回到顶部</a>
</p>

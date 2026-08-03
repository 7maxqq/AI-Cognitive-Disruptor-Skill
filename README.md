# 🛠️ AI Cognitive Disruptor Skill — 工业级 AI 技能引擎包

<p align="center">
  <img src="https://img.shields.io/badge/Pattern-Prompt_as_Code-00ADD8?style=for-the-badge&logo=github" alt="Prompt as Code" />
  <img src="https://img.shields.io/badge/Target-Industrial_Software_Engineering-FF6F00?style=for-the-badge&logo=industrialresearch" alt="Industrial Software Engineering" />
  <img src="https://img.shields.io/badge/Paradigm-Cognitive_Disruption-8B5CF6?style=for-the-badge&logo=brain" alt="Cognitive Disruption" />
  <img src="https://img.shields.io/badge/Status-Active_Development-22C55E?style=for-the-badge&logo=vercel" alt="Active Development" />
</p>

---

## 📋 目录

- [🌟 项目简介](#-项目简介)
- [🗂️ 仓库架构](#️-仓库架构)
- [⚙️ 工业技能包 (Industrial Dev Skills Pack)](#️-工业技能包-industrial-dev-skills-pack)
- [🌌 通用认知破局引擎 (Universal Cognitive Disruptor)](#-通用认知破局引擎-universal-cognitive-disruptor)
- [🤖 自动加载规则 (Auto-Rules)](#-自动加载规则-auto-rules)
- [🚀 快速开始](#-快速开始)
- [📁 目录结构](#-目录结构)
- [🧠 使用场景](#-使用场景)
- [🤝 贡献指南](#-贡献指南)
- [📄 许可证](#-许可证)

---

## 🌟 项目简介

本项目是一个**标准化的 AI 技能引擎集合**，旨在将 LLM（大语言模型）的默认行为约束为**高级软件工程标准**。它通过精心设计的 **Prompt-as-Code** 技能包，引导 AI 从"平庸的默认预测"转向**高维度的工程解法**。

> 🎯 **核心理念**：不是让 AI 更快地给出答案，而是让 AI 给出**更好的答案**。

### 为什么需要这个项目？

| 问题 | 解决方案 |
|------|----------|
| LLM 默认输出"教科书式"的平庸方案 | 通过 **Cache Purge** 机制强制认知破局 |
| 缺乏领域特定约束 | 通过 **Auto-Rules** 按上下文自动加载技能 |
| 架构设计浮于表面 | 通过 **First Principles** 剥离框架外衣 |
| 工业级场景的特殊需求 | 内置 **WPF 解耦**、**Modbus 协议分析**等专项技能 |

---

## 🗂️ 仓库架构

本仓库包含两个核心子系统：

```
AI-Cognitive-Disruptor-Skill/
├── 🏭 Industrial Dev Skills Pack    ← 面向 WPF/C# 工业上位机场景
│   ├── prompts/                     ← 核心提示词引擎
│   ├── skills/                      ← 领域技能包
│   └── integrations/                ← 自动加载规则配置
│
└── 🌌 Universal Cognitive Disruptor ← 通用软件工程认知破局引擎
    ├── skills/                      ← 通用技能包
    └── integrations/                ← 通用自动加载规则
```

---

## ⚙️ 工业技能包 (Industrial Dev Skills Pack)

面向 **C# / WPF 工业上位机开发**场景，专注解决客户端 UI 与工业通信的硬核问题。

### 🔧 技能清单

| 技能 ID | 目标 | 核心约束 |
|---------|------|----------|
| **Arch_WPF_Decoupler** | 强制实施 UI 线程与后台 I/O 的硬解耦 | 🛑 禁止同步阻塞 UI · 🛑 零分配数据绑定 · 🛑 高频数据缓冲背压 |
| **Protocol_Byte_Analyzer** | 专注底层工业通信总线数据帧分析 | 🛑 十六进制表格分析 · 🛑 明确字节序 · 🛑 定位功能码/错误码 |

### 🧩 领域配置

```json
{
  "project_context": {
    "primary_language": "C#",
    "ui_framework": "WPF"
  },
  "industrial_constraints": {
    "communication_protocols": ["Modbus TCP/RTU", "CAN bus"],
    "hardware_specs": {
      "thread_pool_restrictions": "Strict UI Thread isolation required"
    }
  }
}
```

### 🧪 核心引擎 (Core Disruptor)

工业包的核心提示词引擎，定义了 **5 阶段 XML 状态机** 输出规范：

```
<cache_purge>          → 识别并拒绝平庸方案
<first_principles>     → 剥离框架，定义原始物理/逻辑真理
<orthogonal_mapping>   → 跨领域类比（流体力学、生物学等）
<constraint_mutation>  → 施加强约束（内存、线程、时间）
<engineering_blueprint>→ 输出可落地的架构/代码
```

---

## 🌌 通用认知破局引擎 (Universal Cognitive Disruptor)

一个**通用**的 AI 认知破局技能包，适用于任何软件架构、算法设计或复杂排障场景。

### 🔧 技能清单

| 技能 ID | 目标 | 适用场景 |
|---------|------|----------|
| **Core_Disruptor** | 核心拦截器，阻断常识，引入高维约束 | 任何架构/逻辑问题 |
| **Inversion_Debugger** | 逆向排障，通过"刻意制造故障"推导防御策略 | 偶发 Bug、死锁、内存泄漏 |
| **First_Principles_Architect** | 基于信息流与物理极限重构系统 | 系统设计、技术选型、高并发架构 |

### 🧠 Inversion Debugger — 查理·芒格的逆向思维

> 不要问"如何修复它"，而是问"如果要百分之百、极其稳定地触发这个灾难，我该如何设计系统？"

输出规范：
1. **恶意破坏蓝图** — 利用系统缺陷制造 Bug 的伪代码
2. **防御塔映射** — 反推对应的防御代码/断言
3. **根因定位脚本** — 生产环境捕捉"破坏瞬间"的脚本

### 🏛️ First Principles Architect — 第一性原理架构

```
概念剥离 → 本质定义 → 极限推演 → 现代映射
```

剥离"微服务/Redis/Kafka"等工具名词，在 1990 年代单机环境下推演最简数据流，再映射回现代技术栈。

---

## 🤖 自动加载规则 (Auto-Rules)

本项目支持 **Trae IDE** 等 AI 编码工具的自动规则加载，实现技能包的**按需自动激活**。

### 工业包规则 (`integrations/.traerules`)

```json
{
  "rules": [
    { "condition": "*.xaml.cs",          "action": "Load [Arch_WPF_Decoupler]" },
    { "condition": "modbus, CAN",        "action": "Load [Protocol_Byte_Analyzer]" }
  ]
}
```

### 通用包规则 (`Universal-Cognitive-Disruptor/integrations/.traerules`)

```json
{
  "rules": [
    { "condition": "架构设计 / 系统重构 / 算法优化",  "action": "Load [Core_Disruptor] + [First_Principles_Architect]" },
    { "condition": "Bug / 崩溃 / 超时 / 死锁",       "action": "Load [Inversion_Debugger]" }
  ]
}
```

---

## 🚀 快速开始

### 方式一：Trae IDE 用户

1. 克隆本仓库到本地：
   ```bash
   git clone https://github.com/7maxqq/AI-Cognitive-Disruptor-Skill.git
   ```
2. 在 Trae IDE 中打开项目，`integrations/.traerules` 会自动生效
3. 编辑 `.xaml.cs` 文件时，`Arch_WPF_Decoupler` 技能自动加载
4. 输入架构设计相关问题时，`Core_Disruptor` 自动介入

### 方式二：手动提示词注入

将对应技能的 `.md` 文件内容作为 system prompt 注入到你的 AI 对话中：

```bash
# 示例：加载认知破局引擎
cat prompts/core_disruptor.md | pbcopy  # macOS
cat prompts/core_disruptor.md | clip     # Windows
```

### 方式三：ChatGPT / Claude 自定义指令

- 复制 `skills/` 或 `Universal-Cognitive-Disruptor/skills/` 下的技能文件
- 粘贴到 AI 工具的自定义指令 / System Prompt 中
- 根据场景按需加载对应技能

---

## 📁 目录结构

```
AI-Cognitive-Disruptor-Skill/
│
├── prompts/                              # 工业技能包 - 核心提示词
│   ├── core_disruptor.md                 #   Core Disruptor 引擎
│   └── domain_modifiers.json             #   领域上下文配置
│
├── skills/                               # 工业技能包 - 领域技能
│   ├── arch_wpf_decoupler.md             #   WPF 线程解耦技能
│   └── protocol_byte_analyzer.md         #   工业协议分析技能
│
├── integrations/                         # 工业技能包 - 集成配置
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

## 🧠 使用场景

| 场景 | 推荐技能组合 | 效果 |
|------|-------------|------|
| 🏭 WPF 工业上位机开发 | `Arch_WPF_Decoupler` + `Protocol_Byte_Analyzer` | 严格的 UI 线程隔离 + 精确的协议分析 |
| 🏛️ 系统架构设计 | `Core_Disruptor` + `First_Principles_Architect` | 拒绝平庸方案，输出高维架构 |
| 🐛 复杂 Bug 排障 | `Inversion_Debugger` | 逆向思维定位根因 |
| 🔄 算法优化 | `Core_Disruptor` + `First_Principles_Architect` | 剥离框架，从数据流本质优化 |
| 💥 偶发崩溃/死锁 | `Inversion_Debugger` | 制造 Bug 的思维推导防御策略 |

---

## 🤝 贡献指南

欢迎贡献新的技能包！请遵循以下规范：

1. **文件名格式**：`snake_case_技能名.md`
2. **文件头格式**：
   ```markdown
   # [Skill_ID]: Your_Skill_Name
   # [Objective]: One-line description of the skill's purpose.
   ```
3. **约束规则**：以 `## 🛑 约束规则` 开头，列出具体约束
4. **集成规则**：在 `integrations/.traerules` 中添加对应的自动加载规则

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
  <a href="#-ai-cognitive-disruptor-skill--工业级-ai-技能引擎包">⬆️ 回到顶部</a>
</p>
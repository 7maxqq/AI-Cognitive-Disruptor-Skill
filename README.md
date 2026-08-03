# 🛠️ AI Cognitive Disruptor Skill — 通用软件工程 AI 技能引擎包

<p align="center">
  <img src="https://img.shields.io/badge/Pattern-Prompt_as_Code-00ADD8?style=for-the-badge&logo=github" alt="Prompt as Code" />
  <img src="https://img.shields.io/badge/Target-Software_Engineering-FF6F00?style=for-the-badge&logo=visualstudio" alt="Software Engineering" />
  <img src="https://img.shields.io/badge/Paradigm-Cognitive_Disruption-8B5CF6?style=for-the-badge&logo=brain" alt="Cognitive Disruption" />
  <img src="https://img.shields.io/badge/Status-Active_Development-22C55E?style=for-the-badge&logo=vercel" alt="Active Development" />
</p>

---

## 📋 目录

- [🌟 项目简介](#-项目简介)
- [🗂️ 仓库架构](#️-仓库架构)
- [⚙️ 软件工程技能包](#️-软件工程技能包)
- [🌌 通用认知破局引擎](#-通用认知破局引擎)
- [🤖 自动加载规则](#-自动加载规则)
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
| 架构设计缺乏深度 | 通过 **First Principles** 剥离框架外衣，回归本质 |
| 缺乏领域特定约束 | 通过 **Auto-Rules** 按上下文自动加载技能 |
| 排障靠直觉而非方法论 | 通过 **Debug Analyzer** 系统化根因分析 |

---

## 🗂️ 仓库架构

本仓库包含两个核心子系统：

```
AI-Cognitive-Disruptor-Skill/
├── 🏗️ 软件工程技能包              ← 面向通用软件工程场景
│   ├── prompts/                  ← 核心提示词引擎
│   ├── skills/                   ← 通用技能包
│   └── integrations/             ← 自动加载规则配置
│
└── 🌌 Universal Cognitive Disruptor  ← 通用认知破局引擎
    ├── skills/                   ← 高维思维技能包
    └── integrations/             ← 自动加载规则
```

---

## ⚙️ 软件工程技能包

面向**通用软件工程开发**场景，覆盖架构设计、代码质量、调试排障等核心领域。

### 🔧 技能清单

| 技能 ID | 目标 | 核心规则 |
|---------|------|----------|
| **Arch_Decoupler** | 强制实施架构层的关注点分离与模块解耦 | 🛑 禁止循环依赖 · 🛑 依赖倒置 · 🛑 接口隔离 · 🛑 事件驱动 · 🛑 边界清晰 |
| **Debug_Analyzer** | 系统化诊断软件缺陷与性能问题 | 🛑 二分法缩小范围 · 🛑 可复现性优先 · 🛑 日志分层 · 🛑 全链路追踪 · 🛑 区分系统/业务错误 |

### 🧩 核心引擎 (Core Disruptor)

核心提示词引擎，定义了 **5 阶段 XML 状态机** 输出规范，适用于任何技术栈和领域：

```
<cache_purge>          → 识别并拒绝平庸方案
<first_principles>     → 剥离框架，定义原始物理/逻辑真理
<orthogonal_mapping>   → 跨领域类比（流体力学、生物学、经济学等）
<constraint_mutation>  → 施加强约束（内存、线程、时间、网络）
<engineering_blueprint>→ 输出可落地的架构/代码
```

### 🏛️ Arch_Decoupler — 通用架构解耦

适用于任何语言和框架的架构解耦原则：

```
依赖方向：Presentation → Application → Domain → Infrastructure
```

| 规则 | 描述 |
|------|------|
| 🔒 禁止循环依赖 | 依赖方向必须严格单向，Domain 层不引用任何外层 |
| 🔄 依赖倒置 | 抽象定义在 Domain/Application 层，实现注入到 Infrastructure |
| ✂️ 接口隔离 | 每个接口只包含调用方真正需要的方法 |
| 📨 事件驱动 | 跨模块通信通过事件/消息，发布者不感知订阅者 |
| 🧱 边界清晰 | 模块拥有明确的职责边界，通过防腐层（ACL）通信 |

### 🔍 Debug_Analyzer — 通用调试与根因分析

适用于任何语言和平台的系统化排障方法论：

| 阶段 | 方法 | 典型工具 |
|------|------|----------|
| 🔍 问题界定 | 能否稳定复现？影响范围？最近变更？ | Git Blame / Changelog |
| 📊 数据收集 | 日志、监控指标、堆栈、请求/响应样本 | ELK / Prometheus / Dump |
| 🧪 假设验证 | 构造最小复现、A/B 测试、二分回滚 | 单元测试 / Feature Flag |
| 🛠 根因定位 | 代码审查、数据流追踪、压力测试 | Debugger / Profiler / Trace |
| ✅ 修复验证 | 回归测试、灰度发布、监控确认 | CI pipeline / 监控告警 |

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

### 软件工程技能包 (`integrations/.traerules`)

```json
{
  "rules": [
    { "condition": "architecture design, system design, refactoring, module decoupling",
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

## 🚀 快速开始

### 方式一：Trae IDE 用户

1. 克隆本仓库到本地：
   ```bash
   git clone https://github.com/7maxqq/AI-Cognitive-Disruptor-Skill.git
   ```
2. 在 Trae IDE 中打开项目，`integrations/.traerules` 会自动生效
3. 输入架构设计相关问题时，`Arch_Decoupler` 技能自动加载
4. 遇到 Bug 排查时，`Debug_Analyzer` 技能自动介入

### 方式二：手动提示词注入

将对应技能的 `.md` 文件内容作为 system prompt 注入到你的 AI 对话中：

```bash
# 示例：加载架构解耦技能
cat skills/arch_decoupler.md | pbcopy   # macOS
cat skills/arch_decoupler.md | clip      # Windows
```

### 方式三：ChatGPT / Claude / Cursor 自定义指令

- 复制 `skills/` 或 `Universal-Cognitive-Disruptor/skills/` 下的技能文件
- 粘贴到 AI 工具的自定义指令 / System Prompt 中
- 根据场景按需加载对应技能

---

## 📁 目录结构

```
AI-Cognitive-Disruptor-Skill/
│
├── prompts/                              # 核心提示词
│   ├── core_disruptor.md                 #   Core Disruptor 引擎（XML 状态机）
│   └── domain_modifiers.json             #   领域上下文配置
│
├── skills/                               # 通用软件工程技能
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

## 🤝 贡献指南

欢迎贡献新的技能包！请遵循以下规范：

1. **文件命名**：`snake_case_技能名.md`
2. **文件头格式**：
   ```markdown
   # [Skill_ID]: Your_Skill_Name
   # [Objective]: One-line description of the skill's purpose.
   ```
3. **约束规则**：以 `## 🛑 约束规则` 开头，列出具体约束（建议 3-5 条）
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
  <a href="#-ai-cognitive-disruptor-skill--通用软件工程-ai-技能引擎包">⬆️ 回到顶部</a>
</p>
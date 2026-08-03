# 🌌 Universal Cognitive Disruptor Skills

[![Pattern](https://img.shields.io/badge/Pattern-Prompt_as_Code-00ADD8.svg)]()
[![Target](https://img.shields.io/badge/Target-General_Software_Engineering-FF6F00.svg)]()

## 💡 为什么需要这个技能包

AI 的底层逻辑是"预测下一个最可能的词"——这意味着它天然倾向于输出**最常见、最主流的方案**。当你需要真正创新的工程解法时，默认的 AI 输出往往只是"教科书平均值"。

这个技能包的存在就是为了**打破这个惯性**。通过一系列精心设计的思维框架，它强制 AI 跳出"标准答案"模式，从更高维度思考问题。

---

## ⚙️ 核心技能

| 技能 | 作用 | 打破的思维惯性 |
|------|------|----------------|
| **Core_Disruptor** | 核心拦截器，阻断常识，引入高维约束 | "AI 只会给标准答案" |
| **Inversion_Debugger** | 逆向排障，通过"刻意制造故障"推导防御策略 | "正向排障"的思维定式 |
| **First_Principles_Architect** | 剥离框架外衣，基于信息流与物理极限重构系统 | "选型思维"而非"设计思维" |

---

## 🚀 快速开始

1. 将对应技能的 `.md` 文件内容复制到 AI 工具的 System Prompt 中
2. 提出你的问题，观察 AI 如何跳出常规思维框架给出答案
3. 也可以多个技能组合使用，效果更佳

---

## 🤖 自动加载规则

Trae IDE 用户可以通过 `integrations/.traerules` 实现技能自动激活：

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
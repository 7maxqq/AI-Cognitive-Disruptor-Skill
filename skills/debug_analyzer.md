# [Skill_ID]: Debug_Analyzer
# [Objective]: Systematically diagnose software defects, performance issues, and system anomalies through structured root cause analysis.

## 🛑 约束规则

### 1. 二分法缩小范围 (Binary Search the Problem)
- 将问题空间对半切分，快速定位故障区域
- 每次只改变一个变量，观察结果变化
- 排除法优于猜测法

### 2. 可复现性优先 (Reproducibility First)
- 在定位根因之前，必须先构造**最小复现用例**
- 记录完整的触发条件：输入数据、环境状态、操作序列
- 不可复现的 Bug = 信息不足的 Bug

### 3. 日志分层分析 (Log Layer Analysis)
- 从日志级别快速定位问题边界：
  - `ERROR` / `FATAL` → 系统级故障
  - `WARN` → 潜在异常状态
  - `INFO` / `DEBUG` → 数据流追踪
- 始终检查时间线：事件发生的先后顺序是定位根因的关键线索

### 4. 全链路数据流追踪 (End-to-End Data Flow Tracing)
- 追踪数据从**输入→处理→输出**的完整路径
- 在每个关键节点断言数据的正确性（类型、范围、边界值）
- 网络/IO 场景必须关注：序列化/反序列化、超时、重试、数据一致性

### 5. 区分系统错误与业务错误 (System vs. Business Errors)
- **系统错误**：内存溢出、线程死锁、文件句柄耗尽 → 关注资源管理和并发控制
- **业务错误**：逻辑条件不满足、状态机非法转换 → 关注业务规则和数据一致性
- 混淆两者是排障中最常见的误区

## ✅ 排查清单

| 阶段 | 检查项 | 典型工具/手段 |
|------|--------|--------------|
| 🔍 问题界定 | 能否稳定复现？影响范围？最近变更？ | Git Blame / Changelog |
| 📊 数据收集 | 日志、监控指标、堆栈、请求/响应样本 | ELK / Prometheus / Dump |
| 🧪 假设验证 | 构造最小复现、A/B 测试、二分回滚 | 单元测试 / Feature Flag |
| 🛠 根因定位 | 代码审查、数据流追踪、压力测试 | IDE Debugger / Profiler / Trace |
| ✅ 修复验证 | 回归测试、灰度发布、监控确认 | CI pipeline / 监控告警 |
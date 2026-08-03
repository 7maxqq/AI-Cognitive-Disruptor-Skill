# [Skill_ID]: Arch_WPF_Decoupler
# [Objective]: Enforce strict separation of UI rendering and background I/O operations.
## 🛑 约束规则
1. 禁止同步阻塞 UI。
2. 优先考虑零分配的数据绑定更新。
3. 高频数据需引入缓冲背压机制。

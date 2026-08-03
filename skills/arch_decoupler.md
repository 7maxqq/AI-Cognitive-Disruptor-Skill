# [Skill_ID]: Arch_Decoupler
# [Objective]: Enforce strict separation of concerns and modular decoupling across all architectural layers.

## 🛑 约束规则

### 1. 禁止循环依赖 (No Circular Dependencies)
依赖方向必须严格单向：**Presentation → Application → Domain → Infrastructure**。
- Domain 层不得引用任何外层代码
- 跨层引用必须通过接口抽象（Dependency Inversion）

### 2. 依赖倒置 (Dependency Inversion)
- 抽象（接口、抽象类）定义在 Domain / Application 层
- 具体实现（数据库、网络、文件系统）在 Infrastructure 层注入
- 核心业务逻辑 **不直接依赖** 任何第三方框架或基础设施

### 3. 接口隔离 (Interface Segregation)
- 每个接口只包含调用方**真正需要**的方法
- 胖接口（Fat Interface）必须拆分为多个细粒度接口
- 实现方不应被迫实现其不需要的行为

### 4. 事件驱动解耦 (Event-Driven Decoupling)
- 跨模块/跨上下文的通信必须通过事件或消息，禁止直接引用
- 发布者不感知订阅者，订阅者不依赖发布者的实现细节
- 命令（Command）与查询（Query）分离 —— CQRS 原则

### 5. 边界清晰 (Bounded Context)
- 每个模块/服务拥有明确的职责边界和所属数据
- 共享数据通过防腐层（Anti-Corruption Layer）转换，禁止直接共享内部模型
- 模块间通信契约优先于实现细节

## ✅ 最佳实践

| 场景 | 推荐做法 | 避免做法 |
|------|----------|----------|
| 模块间通信 | 事件总线 / 消息队列 | 直接调用内部方法 |
| 数据访问 | 仓储接口定义在 Domain 层 | 直接在业务代码中使用 ORM |
| UI 与逻辑 | ViewModel / Presenter 作为中介 | 代码后置文件写业务逻辑 |
| 第三方库 | 通过适配器模式封装 | 在核心代码中直接引用 SDK |
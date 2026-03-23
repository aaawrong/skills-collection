# Code Skills

本目录包含与编码规范、模式和测试相关的技能说明。每个技能的权威说明在对应的 `SKILL.md`。

| Skill | 作用 | 来源 |
| --- | --- | --- |
| golang-patterns | Go 语言的惯用模式、最佳实践与约定，帮助构建健壮、可维护的应用 | https://github.com/affaan-m/everything-claude-code |
| golang-testing | Go 测试模式：表驱动、子测试、基准、模糊测试与覆盖率，遵循 TDD 思路 | https://github.com/affaan-m/everything-claude-code |
| go-style-core | Go 格式化、行长度、嵌套、裸返回、分号等核心风格原则，未被其他 skill 覆盖时作为兜底 | Google Go Style Guide |
| go-linting | Go 项目的 lint 配置，golangci-lint 设置，CI/CD 中添加 Go 检查 | Google Go Style Guide |
| go-testing | Go 测试代码编写与改进：表驱动测试、子测试、并行测试、测试辅助函数、cmp.Diff 断言 | Google Go Style Guide |
| go-interfaces | Go 接口定义与实现、抽象设计、可 mock 边界、类型嵌入组合 | Google Go Style Guide |
| go-concurrency | Go 并发编程：goroutine、channel、mutex、线程安全、工作并行化与数据竞争修复 | Google Go Style Guide |
| go-generics | Go 泛型使用决策、泛型函数/类型编写、约束选择、类型别名与类型定义 | Google Go Style Guide |
| go-error-handling | Go 错误返回、包装与处理：哨兵错误、自定义类型、fmt.Errorf、错误流组织 | Google Go Style Guide |
| go-logging | Go 日志方案选择、slog 配置、结构化日志编写、日志级别选择 | Google Go Style Guide |
| go-defensive | Go API 边界加固：切片/map 拷贝、接口合规校验、defer 清理、避免可变全局状态 | Google Go Style Guide |
| go-functions | Go 函数组织、签名格式化、返回值设计、Printf 风格命名约定 | Google Go Style Guide |
| go-performance | Go 性能优化、慢代码排查、性能关键段编写、字符串拼接优化与基准测试 | Google Go Style Guide |
| go-code-review | Go 代码审查与社区风格标准检查，提交 PR 前主动执行 | Google Go Style Guide |
| go-context | context.Context 使用：签名中的位置、取消与超时传播、context 存值 | Google Go Style Guide |
| go-functional-options | Go 构造函数/工厂函数的可选配置设计，适用于 3+ 可选参数或可扩展 API | Google Go Style Guide |
| go-documentation | Go 包、类型、函数、方法的文档编写与审查，创建导出类型/函数/包时主动使用 | Google Go Style Guide |
| go-naming | Go 标识符命名：包、类型、函数、方法、变量、常量、接收器，确保命名惯用且清晰 | Google Go Style Guide |
| go-data-structures | Go 切片、map、数组：new vs make、append 使用、空切片声明、map 实现集合 | Google Go Style Guide |
| go-control-flow | Go 条件、循环、switch 语句：if 初始化、提前返回、for 循环形式、range、类型 switch | Google Go Style Guide |
| go-packages | Go 包创建、import 组织、依赖管理、代码包结构设计 | Google Go Style Guide |
| go-declarations | Go 变量/常量/结构体/map 声明与初始化：var vs :=、作用域缩小、复合字面量、iota 枚举 | Google Go Style Guide |

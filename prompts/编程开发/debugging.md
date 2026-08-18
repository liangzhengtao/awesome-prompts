# 调试 Prompts / Debugging Prompts

> 🐛 高效调试 Prompt 集合，覆盖错误分析、堆栈追踪解读、根因分析和问题排查。
> Efficient debugging prompts covering error analysis, stack trace interpretation, root cause analysis, and troubleshooting.

## 目录 / Table of Contents

- [错误分析 / Error Analysis](#错误分析--error-analysis)
- [堆栈追踪 / Stack Trace Interpretation](#堆栈追踪--stack-trace-interpretation)
- [根因分析 / Root Cause Analysis](#根因分析--root-cause-analysis)
- [运行时调试 / Runtime Debugging](#运行时调试--runtime-debugging)
- [测试调试 / Test Debugging](#测试调试--test-debugging)

---

## 错误分析 / Error Analysis

### 1. 通用错误诊断

```
我遇到了以下错误，请帮我分析原因并提供解决方案。

语言/框架：[LANGUAGE]/[FRAMEWORK]
错误信息：
```
[ERROR_MESSAGE]
```

相关代码：
```[CODE]```

请提供：
1. 错误含义解释（用通俗语言）
2. 可能的原因列表（按可能性排序）
3. 针对每个原因的排查步骤
4. 修复代码
5. 如何避免此错误再次发生
```

### 2. 编译错误诊断

```
以下代码出现编译错误，请帮我修复。

语言：[LANGUAGE]
编译器/版本：[COMPILER_VERSION]
错误信息：
```
[COMPILE_ERROR]
```

代码：
```[CODE]```

请：
1. 解释编译错误的根本原因
2. 给出最少改动的修复方案
3. 如果有多种修复方式，比较各方案优劣
4. 提供修复后的完整代码
```

### 3. 环境配置错误

```
我的开发环境出现以下配置/安装错误。

操作系统：[OS]
工具/版本：[TOOL_VERSION]
错误信息：
```
[ERROR_OUTPUT]
```

已尝试的方案：[ATTEMPTED_SOLUTIONS]

请：
1. 分析错误原因
2. 提供逐步修复指南
3. 说明如何验证修复成功
4. 列出常见的环境陷阱
```

### 4. 依赖冲突解决

```
我的项目存在依赖冲突，导致运行/安装失败。

包管理器：[PACKAGE_MANAGER]
错误信息：
```
[DEPENDENCY_ERROR]
```

相关依赖配置：
```[DEPENDENCY_CONFIG]```

请：
1. 分析冲突的依赖链
2. 推荐解决冲突的方案（按优先级）
3. 提供修改后的依赖配置
4. 说明如何预防此类冲突
```

---

## 堆栈追踪 / Stack Trace Interpretation

### 5. 异常堆栈解析

```
请解析以下异常堆栈，帮我定位问题。

语言：[LANGUAGE]
堆栈信息：
```
[STACK_TRACE]
```

上下文代码：
```[RELEVANT_CODE]```

请输出：
1. 🎯 异常类型和含义
2. 📍 错误发生的确切位置（文件+行号）
3. 📖 调用链解读（从入口到异常点的执行路径）
4. 🔧 最可能的修复方案
```

### 6. 多层异常分析

```
我的程序抛出了嵌套/包装异常，请帮我分析真正的根因。

语言：[LANGUAGE]
完整异常链：
```
[FULL_EXCEPTION_CHAIN]
```

相关代码：
```[CODE]```

请：
1. 区分"原因异常"和"包装异常"
2. 找到最初的根因
3. 解释异常传播路径
4. 给出修复方案（应修复根因，不是中间层）
```

### 7. 生产环境错误诊断

```
我在生产环境捕获到以下错误，请帮我诊断。

错误日志：
```
[ERROR_LOG]
```

应用信息：
- 语言/框架：[LANGUAGE]/[FRAMEWORK]
- 部署方式：[DEPLOYMENT]
- 流量特征：[TRAFFIC_PATTERN]（如"高并发时出现"、"偶发"等）
- 最近变更：[RECENT_CHANGES]

请分析：
1. 可能的根因
2. 影响范围
3. 紧急缓解措施
4. 长期修复方案
5. 预防措施
```

---

## 根因分析 / Root Cause Analysis

### 8. 逻辑 Bug 排查

```
以下代码的输出与预期不符，请帮我找出逻辑错误。

语言：[LANGUAGE]
代码：
```[CODE]```

预期行为：[EXPECTED_BEHAVIOR]
实际行为：[ACTUAL_BEHAVIOR]
输入示例：[INPUT]
预期输出：[EXPECTED_OUTPUT]
实际输出：[ACTUAL_OUTPUT]

请：
1. 逐步追踪代码执行
2. 标注逻辑错误所在
3. 解释为何会产生错误结果
4. 提供修复代码
```

### 9. 状态不一致调试

```
我的应用出现了状态不一致的问题。

问题描述：[PROBLEM_DESCRIPTION]
复现条件：[REPRODUCTION_STEPS]
相关代码：
```[CODE]```

状态管理方式：[STATE_MANAGEMENT]（如 Redux/Vuex/数据库事务等）

请分析：
1. 可能导致状态不一致的代码路径
2. 竞态条件的可能性
3. 事件/操作的顺序问题
4. 推荐的修复方案和防御性编程策略
```

### 10. 性能问题诊断

```
我的代码运行缓慢，请帮我找出性能瓶颈。

语言：[LANGUAGE]
代码：
```[CODE]```

运行环境：[ENVIRONMENT]
数据规模：[DATA_SIZE]
当前耗时：[CURRENT_TIME]
目标耗时：[TARGET_TIME]

请：
1. 分析时间复杂度
2. 标注可能的瓶颈点
3. 提供 profiling 建议
4. 给出优化后的代码
5. 对比优化前后的复杂度
```

### 11. 并发问题调试

```
我的多线程/异步代码出现间歇性问题。

语言：[LANGUAGE]
问题描述：[PROBLEM_DESCRIPTION]
代码：
```[CODE]```

出现频率：[FREQUENCY]（如"1000次中出现1次"）

请分析：
1. 是否存在竞态条件
2. 是否存在死锁可能
3. 共享资源访问是否安全
4. 推荐的修复方案
5. 如何复现和验证修复
```

---

## 运行时调试 / Runtime Debugging

### 12. 内存问题诊断

```
我的应用出现内存相关问题。

问题类型：[MEMORY_ISSUE]（内存泄漏/OOM/GC 停顿）
语言：[LANGUAGE]
运行时/版本：[RUNTIME_VERSION]
代码/可疑代码：
```[CODE]```

症状描述：[SYMPTOMS]

请提供：
1. 诊断步骤（如何确认问题）
2. 可疑代码分析
3. 工具推荐（如 heap dump 分析工具）
4. 修复方案
5. 监控建议
```

### 13. 网络/API 调试

```
我的 API 调用出现问题，请帮我排查。

问题描述：[PROBLEM]
调用代码：
```[CODE]```

请求/响应信息：
- URL：[URL]
- Method：[METHOD]
- Headers：[HEADERS]
- 响应状态码：[STATUS_CODE]
- 响应内容：[RESPONSE]

请分析：
1. 问题出在客户端还是服务端
2. 请求构造是否正确
3. 认证/授权是否正确
4. 网络层面的可能性（超时、DNS、代理等）
5. 解决方案
```

### 14. 日志分析

```
请分析以下应用日志，找出异常模式和潜在问题。

日志片段：
```
[LOG_ENTRIES]
```

应用信息：
- 服务名：[SERVICE_NAME]
- 时间范围：[TIME_RANGE]
- 已知问题：[KNOWN_ISSUES]

请：
1. 识别错误模式和频率
2. 找出错误之间的关联
3. 标注关键时间点
4. 推断根因
5. 给出排查建议
```

---

## 测试调试 / Test Debugging

### 15. 单元测试失败调试

```
我的单元测试失败了，请帮我分析原因。

测试框架：[TEST_FRAMEWORK]
测试代码：
```[TEST_CODE]```

被测代码：
```[SOURCE_CODE]```

测试输出：
```
[TEST_OUTPUT]
```

请分析：
1. 测试失败的确切原因
2. 是被测代码的问题还是测试本身的问题
3. 如果是测试问题，如何修正测试
4. 如果是代码问题，如何修复代码
```

### 16. 集成测试问题

```
我的集成测试在 [ENVIRONMENT] 环境中不稳定（Flaky）。

测试描述：[TEST_DESCRIPTION]
失败率：约 [FAILURE_RATE]
测试代码：
```[TEST_CODE]```

常见错误：
```
[TYPICAL_ERRORS]
```

请分析可能导致测试不稳定的因素并给出修复建议。
```

### 17. Mock/Stub 调试

```
我的测试中 Mock/Stub 的行为与预期不符。

测试框架：[TEST_FRAMEWORK]
Mock 库：[MOCK_LIBRARY]
测试代码：
```[TEST_CODE]```

预期行为：[EXPECTED]
实际行为：[ACTUAL]

请分析：
1. Mock 配置是否正确
2. Mock 的调用顺序/参数是否匹配
3. 是否需要调整 Mock 策略
4. 给出修正后的测试代码
```

---

## 💡 使用技巧 / Tips

1. **提供完整错误信息**：完整的错误信息+堆栈追踪远比"我的代码不工作"更有效
2. **附带最小复现**：提供能重现问题的最小代码片段，而非整个项目
3. **说明环境信息**：操作系统、语言版本、框架版本等环境信息常是解题关键
4. **描述预期vs实际**：明确说出你期望什么和实际发生了什么
5. **展示已尝试的方案**：避免 AI 给出你已试过的无效方案

## ⚠️ 常见错误 / Common Mistakes

- ❌ 只说"报错了"而不提供错误信息
- ❌ 提供大量无关代码，不标注可疑位置
- ❌ 隐瞒自己修改过的内容
- ❌ 不说明运行环境和版本信息
- ❌ 跳过错误信息只问"为什么不工作"

---

## 中文版本

> 🐛 高效调试 Prompt 集合，覆盖错误分析、堆栈追踪解读、根因分析和问题排查，帮你快速定位和修复代码问题。

### 核心 Prompt 示例

**通用错误诊断：**
我遇到了以下错误，请帮我分析原因并提供解决方案。语言/框架：[LANGUAGE]/[FRAMEWORK]，错误信息：[ERROR_MESSAGE]，相关代码：[CODE]。请提供：错误含义解释（用通俗语言）、可能的原因列表（按可能性排序）、针对每个原因的排查步骤、修复代码、如何避免此错误再次发生。

**异常堆栈解析：**
请解析以下异常堆栈，帮我定位问题。语言：[LANGUAGE]，堆栈信息：[STACK_TRACE]，上下文代码：[RELEVANT_CODE]。请输出：🎯 异常类型和含义、📍 错误发生的确切位置（文件+行号）、📖 调用链解读（从入口到异常点的执行路径）、🔧 最可能的修复方案。

**逻辑 Bug 排查：**
以下代码的输出与预期不符，请帮我找出逻辑错误。语言：[LANGUAGE]，代码：[CODE]，预期行为：[EXPECTED_BEHAVIOR]，实际行为：[ACTUAL_BEHAVIOR]，输入示例：[INPUT]，预期输出：[EXPECTED_OUTPUT]，实际输出：[ACTUAL_OUTPUT]。请逐步追踪代码执行，标注逻辑错误所在，解释为何产生错误结果，提供修复代码。

**生产环境错误诊断：**
我在生产环境捕获到以下错误，请帮我诊断。错误日志：[ERROR_LOG]，语言/框架：[LANGUAGE]/[FRAMEWORK]，部署方式：[DEPLOYMENT]，流量特征：[TRAFFIC_PATTERN]，最近变更：[RECENT_CHANGES]。请分析：可能的根因、影响范围、紧急缓解措施、长期修复方案、预防措施。

### 💡 使用技巧

1. **提供完整错误信息**：完整的错误信息+堆栈追踪远比"我的代码不工作"更有效
2. **附带最小复现**：提供能重现问题的最小代码片段，而非整个项目
3. **说明环境信息**：操作系统、语言版本、框架版本等环境信息常是解题关键
4. **描述预期vs实际**：明确说出你期望什么和实际发生了什么
5. **展示已尝试的方案**：避免 AI 给出你已试过的无效方案

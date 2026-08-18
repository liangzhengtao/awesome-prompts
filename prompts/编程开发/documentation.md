# 文档编写 Prompts / Documentation Prompts

> 📝 专业文档 Prompt 集合，覆盖 README 生成、API 文档、代码注释和变更日志。
> Professional documentation prompts covering README generation, API docs, code comments, and changelogs.

## 目录 / Table of Contents

- [README 生成 / README Generation](#readme-生成--readme-generation)
- [API 文档 / API Documentation](#api-文档--api-documentation)
- [代码注释 / Code Comments](#代码注释--code-comments)
- [变更日志 / Changelog](#变更日志--changelog)
- [架构文档 / Architecture Documentation](#架构文档--architecture-documentation)

---

## README 生成 / README Generation

### 1. 项目 README 生成

```
为以下项目生成一份完整的 README.md。

项目名称：[PROJECT_NAME]
项目描述：[PROJECT_DESCRIPTION]
技术栈：[TECH_STACK]
编程语言：[LANGUAGE]
包管理器：[PACKAGE_MANAGER]

请包含以下章节：
1. 项目标题 + 一句话描述 + 徽章（构建状态、版本、许可证）
2. ✨ 功能亮点（3-5 个核心特性）
3. 📦 安装指南（含多种安装方式）
4. 🚀 快速开始（最小可用示例）
5. 📖 使用说明（含代码示例）
6. ⚙️ 配置选项（配置文件说明）
7. 🤝 贡献指南（链接到 CONTRIBUTING.md）
8. 📄 许可证
9. 🙏 致谢

使用 [LANGUAGE] 编写内容，代码示例使用 [LANGUAGE]。
```

### 2. 快速开始指南

```
为以下项目/库编写"快速开始"指南。

项目名称：[PROJECT_NAME]
目标用户：[TARGET_AUDIENCE]
前置要求：[PREREQUISITES]
安装方式：[INSTALL_METHOD]

请包含：
1. 环境准备（含版本要求）
2. 安装步骤（含验证安装成功的命令）
3. 最简示例（3-5 行代码即可运行）
4. 运行和查看结果
5. 下一步去哪里（链接到更详细的文档）

要求：新手友好，每个步骤都可验证，预计 5 分钟内完成。
```

### 3. 贡献指南

```
为开源项目 [PROJECT_NAME] 编写 CONTRIBUTING.md。

项目技术栈：[TECH_STACK]
分支策略：[BRANCH_STRATEGY]（如 Git Flow/GitHub Flow）
代码风格：[CODE_STYLE]（如 ESLint + Prettier）

请包含：
1. 开发环境搭建步骤
2. 代码规范和风格要求
3. 分支命名和提交信息规范
4. Pull Request 流程和模板
5. Issue 报告指南
6. Code Review 流程
7. 发布流程说明
```

---

## API 文档 / API Documentation

### 4. REST API 端点文档

```
为以下 REST API 端点生成 OpenAPI/Swagger 文档。

端点信息：
- URL: [ENDPOINT_URL]
- Method: [HTTP_METHOD]
- 功能描述：[DESCRIPTION]
- 认证方式：[AUTH_METHOD]

请求参数：
[REQUEST_PARAMS]

请求体：
[REQUEST_BODY]

响应示例：
[RESPONSE_EXAMPLES]

请生成：
1. 完整的 OpenAPI 3.0 YAML 规范
2. 请求参数说明（含类型、必填、默认值、校验规则）
3. 多种响应示例（成功、客户端错误、服务端错误）
4. 认证说明
```

### 5. GraphQL Schema 文档

```
为以下 GraphQL Schema 生成文档注释。

Schema：
```graphql
[SCHEMA_CODE]
```

业务场景：[BUSINESS_CONTEXT]

请：
1. 为每个 Type、Field 添加描述性注释
2. 标注弃用的字段（使用 @deprecated）
3. 补充查询和变更的使用示例
4. 说明字段之间的关系和约束
```

### 6. SDK/Library API 文档

```
为以下库的公开 API 生成 JSDoc/docstring 文档。

语言：[LANGUAGE]
库代码：
```[LIBRARY_CODE]```

每个公开函数/方法请包含：
1. 功能描述（一句话说清楚做什么）
2. 参数说明（类型、描述、是否可选、默认值）
3. 返回值说明（类型和含义）
4. 异常/错误说明
5. 使用示例
6. 注意事项（如有）

遵循 [LANGUAGE] 的文档注释规范（JSDoc/docstring/Godoc 等）。
```

### 7. WebSocket API 文档

```
为以下 WebSocket API 生成文档。

服务端地址：[WS_URL]
认证方式：[AUTH]

消息类型：
[MESSAGE_TYPES]

请为每种消息类型生成：
1. 消息格式（JSON Schema）
2. 方向（客户端→服务端 / 服务端→客户端 / 双向）
3. 触发条件
4. 响应/确认消息
5. 错误处理
6. 代码示例（连接、发送、接收）
```

---

## 代码注释 / Code Comments

### 8. 函数级注释生成

```
为以下函数/方法添加专业级注释。

语言：[LANGUAGE]
代码：
```[CODE]```

注释要求：
- 遵循 [LANGUAGE] 的标准文档规范（JSDoc/docstring/Javadoc/Godoc）
- 说明"做什么"而非"怎么做"
- 标注参数、返回值、异常
- 对复杂逻辑添加行内注释
- 添加使用示例

输出添加注释后的完整代码。
```

### 9. 复杂算法注释

```
为以下算法代码添加详细的解释注释。

语言：[LANGUAGE]
算法名称：[ALGORITHM_NAME]（如不确定可写"未知"）
代码：
```[CODE]```

请添加：
1. 算法概述（做什么，时间/空间复杂度）
2. 核心思想解释
3. 每个关键步骤的注释
4. 变量含义说明
5. 边界条件处理说明
6. 参考资料链接（如有）
```

### 10. TODO/FIXME 整理

```
扫描以下代码，找出所有 TODO/FIXME/HACK/XXX 注释，并评估优先级。

代码文件：
```[CODE]```

对每条注释：
1. 标注位置（文件:行号）
2. 分类：TODO/FIXME/HACK/XXX
3. 优先级：🔴 紧急 / 🟠 高 / 🟡 中 / 🟢 低
4. 建议：保留/解决/删除（如果是过时的）
5. 如果建议解决，给出解决思路
```

---

## 变更日志 / Changelog

### 11. CHANGELOG 生成

```
基于以下 Git 提交记录生成 CHANGELOG.md。

提交记录：
```
[COMMIT_LOG]
```

版本号：[VERSION]
发布日期：[RELEASE_DATE]

请按 Keep a Changelog 格式组织：
### Added（新增功能）
### Changed（变更）
### Deprecated（废弃）
### Removed（移除）
### Fixed（修复）
### Security（安全）

要求：
- 每条记录用一句话概括，面向最终用户
- 不要包含内部重构等用户不关心的内容
- 链接到相关的 Issue/PR
```

### 12. 迁移指南

```
为版本升级 [OLD_VERSION] → [NEW_VERSION] 编写迁移指南。

变更内容：
[BREAKING_CHANGES]

请包含：
1. 变更摘要
2. 影响范围说明
3. 分步迁移指南（每个破坏性变更一个章节）
4. 每步提供 Before/After 代码对比
5. 自动化迁移工具（如有）
6. 常见问题和解决方案
```

---

## 架构文档 / Architecture Documentation

### 13. 系统架构文档

```
为以下项目编写架构决策记录（ADR）。

项目名称：[PROJECT_NAME]
决策主题：[DECISION_TOPIC]
背景：[CONTEXT]
备选方案：
1. [OPTION_1]
2. [OPTION_2]
3. [OPTION_3]

请按 ADR 格式编写：
1. 标题
2. 状态（提议/接受/废弃/替代）
3. 背景
4. 决策
5. 后果（正面和负面）
6. 合规性
```

### 14. 数据库 Schema 文档

```
为以下数据库 Schema 生成文档。

数据库类型：[DATABASE_TYPE]
DDL/Schema：
```[SQL_SCHEMA]```

请为每个表生成：
1. 表名和用途说明
2. 列名、类型、约束、说明
3. 索引说明
4. 外键关系图（文本形式）
5. 示例查询（常用操作）
6. 注意事项和最佳实践
```

### 15. 部署文档

```
为以下项目编写部署文档。

项目名称：[PROJECT_NAME]
技术栈：[TECH_STACK]
部署目标：[DEPLOYMENT_TARGET]（如 AWS/GCP/K8s/Docker）

请包含：
1. 环境要求和前置条件
2. 配置文件说明和示例
3. 分步部署指南
4. 环境变量说明
5. 健康检查和验证步骤
6. 回滚方案
7. 监控和告警配置
8. 常见问题排查
```

### 16. 国际化/本地化文档

```
为项目 [PROJECT_NAME] 编写国际化（i18n）实施指南。

当前语言：[CURRENT_LANGUAGE]
目标语言：[TARGET_LANGUAGES]
框架：[FRAMEWORK]

请包含：
1. i18n 架构设计
2. 翻译文件结构
3. 字符串提取和管理流程
4. 日期/数字/货币格式化方案
5. RTL 语言支持（如需要）
6. 测试策略
```

---

## 💡 使用技巧 / Tips

1. **指定受众**：告诉 AI 文档面向谁（新手/专家/运维/前端），产出质量会更高
2. **提供代码示例**：给 AI 看到实际代码，生成的文档才准确
3. **指定格式规范**：要求遵循 Google Style/PEP 257/JSDoc 等具体规范
4. **要求版本同步**：文档生成后要求 AI 检查是否与最新代码一致
5. **中英文都可**：根据团队需要选择语言，AI 可以轻松切换

## ⚠️ 常见错误 / Common Mistakes

- ❌ 文档只描述"怎么做"而非"做什么"和"为什么"
- ❌ 代码更新后忘记同步文档
- ❌ README 过于冗长，缺少快速开始指南
- ❌ API 文档缺少错误码说明和示例
- ❌ 注释过多反而降低可读性（好的代码应该自解释）

---

## 中文版本

> 📝 专业文档 Prompt 集合，覆盖 README 生成、API 文档、代码注释、变更日志和架构文档，让文档编写高效且规范。

### 核心 Prompt 示例

**项目 README 生成：**
为以下项目生成一份完整的 README.md。项目名称：[PROJECT_NAME]，项目描述：[PROJECT_DESCRIPTION]，技术栈：[TECH_STACK]，编程语言：[LANGUAGE]，包管理器：[PACKAGE_MANAGER]。请包含：项目标题+一句话描述+徽章、功能亮点（3-5 个核心特性）、安装指南（含多种安装方式）、快速开始（最小可用示例）、使用说明（含代码示例）、配置选项、贡献指南、许可证、致谢。

**REST API 端点文档：**
为以下 REST API 端点生成 OpenAPI/Swagger 文档。端点信息：URL: [ENDPOINT_URL]，Method: [HTTP_METHOD]，功能描述：[DESCRIPTION]，认证方式：[AUTH_METHOD]。请求参数：[REQUEST_PARAMS]，请求体：[REQUEST_BODY]，响应示例：[RESPONSE_EXAMPLES]。请生成完整的 OpenAPI 3.0 YAML 规范、请求参数说明、多种响应示例和认证说明。

**函数级注释生成：**
为以下函数/方法添加专业级注释。语言：[LANGUAGE]，代码：[CODE]。注释要求：遵循 [LANGUAGE] 的标准文档规范（JSDoc/docstring/Javadoc/Godoc），说明"做什么"而非"怎么做"，标注参数、返回值、异常，对复杂逻辑添加行内注释，添加使用示例。输出添加注释后的完整代码。

**CHANGELOG 生成：**
基于以下 Git 提交记录生成 CHANGELOG.md。提交记录：[COMMIT_LOG]，版本号：[VERSION]，发布日期：[RELEASE_DATE]。请按 Keep a Changelog 格式组织：Added（新增功能）、Changed（变更）、Deprecated（废弃）、Removed（移除）、Fixed（修复）、Security（安全）。每条记录用一句话概括面向最终用户。

### 💡 使用技巧

1. **指定受众**：告诉 AI 文档面向谁（新手/专家/运维/前端），产出质量会更高
2. **提供代码示例**：给 AI 看到实际代码，生成的文档才准确
3. **指定格式规范**：要求遵循 Google Style/PEP 257/JSDoc 等具体规范
4. **要求版本同步**：文档生成后要求 AI 检查是否与最新代码一致
5. **中英文都可**：根据团队需要选择语言，AI 可以轻松切换


# Design Document: [标题]

| 字段     | 值                    |
| -------- | --------------------- |
| 作者     |                       |
| 状态     | Draft                 |
| 创建日期 | YYYY-MM-DD            |
| 更新日期 | YYYY-MM-DD            |
| 关联Issue | #编号（如有）         |

---

## Overview

> 一段话说清楚要做什么、为什么做。

## Motivation

> 背景和痛点：现有方案有什么不足？用户遇到什么问题？

## Goals / Non-Goals

**Goals（本次要做的）：**
- [ ] 目标1
- [ ] 目标2

**Non-Goals（本次明确不做的）：**
- 不做 XXX，原因是 ……

## Proposed Design

> 主设计部分，按需包含以下子章节。

### Architecture

> 架构图、模块关系、数据流。（可用 Mermaid 画图）

```mermaid
graph LR
    A[模块A] --> B[模块B]
    B --> C[模块C]
```

### Data Model

> 新增/变更的数据结构、数据库表、Schema。

### API Changes

> 新增/变更/废弃的接口，附请求/响应示例。

### Key Algorithms / Logic

> 核心算法、策略逻辑、关键流程。

## Alternatives Considered

| 方案    | 优点 | 缺点 | 结论 |
| ------- | ---- | ---- | ---- |
| 方案A   |      |      | 采用 |
| 方案B   |      |      | 放弃，因为…… |

## Security & Compliance

> 是否涉及权限变更、密钥/凭证、数据隔离、敏感信息处理？
> - [ ] 无安全影响（如勾选需简要说明理由）
> - [ ] 有安全影响，详见下方：

## Performance Impact

> 预估性能开销：CPU/内存/网络/存储。是否有大查询、高频调用、批量操作？

## Backward Compatibility

> 是否破坏现有接口或行为？
> - [ ] 完全兼容，无破坏性变更
> - [ ] 有破坏性变更，迁移方案如下：

## Testing Plan

| 测试类型 | 覆盖范围              | 备注 |
| -------- | --------------------- | ---- |
| 单元测试 | 核心算法、边界条件    |      |
| 集成测试 | 模块间交互            |      |
| 手动验证 | UI / 端到端流程       |      |

## Rollout Plan

> 上线策略：分几阶段？灰度比例？回滚方案？

- **Phase 1**：……
- **Phase 2**：……
- **回滚方式**：……

## Monitoring & Alerts

> 上线后关键观测指标、告警阈值。

| 指标         | 阈值 / 异常判定 | 告警方式 |
| ------------ | --------------- | -------- |
|              |                 |          |

---

## Open Questions

> 待讨论/未决定的问题。

- [ ] 问题1
- [ ] 问题2

## References

- [相关文档/Issue链接]

---

> **使用方式**：复制此模板到 `docs/design/YYYY-MM-DD-简短标题.md`，填写后随 PR 一起提交评审。

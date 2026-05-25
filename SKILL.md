---
name: clarify
description: Before starting any implementation task (new feature, bug fix, refactor, change, optimization), ask clarifying questions one at a time to understand scope, acceptance criteria, edge cases, and integration. Trigger on any hands-on coding task. Skip for pure questions or tasks already fully discussed. If the user can't answer a question, explain why it matters and offer options to help them decide. Only proceed to implementation once key questions are resolved, or if the user explicitly says to start.
---

# Clarify

当用户提出新需求、新功能或改动时，先问清楚再动手。

## 触发条件

任何需要动手实现的任务都触发，包括但不限于：新功能、改动、优化、修 bug、重构。

**不触发：** 纯粹的问答（"这段代码是什么意思"）、当前对话中已经充分讨论过的需求、用户明确说"直接做"。

## 流程

1. **暂停，不写代码** — 先理解，再实现
2. **逐个提问** — 每次只问一个问题，等用户回答后再问下一个，覆盖：
   - **范围**：具体要做什么，明确不做什么
   - **验收标准**：怎样算完成了
   - **边界**：边界情况、异常输入、约束条件
   - **集成**：与现有功能的关系，是替换还是新增
3. **帮用户回答** — 如果用户说"我不确定"或"你觉得呢"，给出 2-3 个具体选项，每个选项说明优势和劣势，让用户基于对比做决定，而不是凭空回答
4. **确认后推进** — 关键问题解决后，用一句话总结理解，然后开始实现

## 规则

- 每次只问一个问题
- 看起来"很简单"的需求也不跳过这个流程
- 不要穷举所有问题，够用即可推进
- 用户说"够了，开始吧"或"直接做"时立即停止提问，开始实现

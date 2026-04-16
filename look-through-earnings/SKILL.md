---
name: look-through-earnings
description: |
  用户需要看穿会计数字，理解一个企业或投资组合的真实经济收益。特别适用于评估盈利质量、资本支出真实性、EBITDA误导。
  语言信号:"这家公司利润很高"/"EBITDA是多少"/"折旧算不算成本"/"自由现金流和利润为什么不一样"
  不适用于:不需要财务分析的纯定性决策。
source_book: 《巴菲特致股东的信》 沃伦·巴菲特
source_chapter: 1978年信 / 1985年信 / 2000年信
tags: [accounting, earnings, EBITDA, owner-earnings, financial-analysis]
related_skills: [business-picker, aesop-three-questions]
---

# 透视盈余（含所有者收益/反EBITDA）

## R — 原文 (Reading)

> "We feel that the undistributed earnings of companies we hold in large amounts are fully as important to us as those we report." (1978)
> "References to EBITDA make us shudder — does management think the tooth fairy pays for capital expenditures?" (2000)

## I — 方法论骨架

两个核心概念合并为一个skill：

**透视盈余**: 真实经济收益 = 报告利润 + 被投资公司未分配利润份额 - 假设税款
- 会计只显示已收股息，但未分配利润也是你的（如果有控制权或长期持有）

**所有者收益**: 净利润 + 折旧摊销 - 维持性资本支出 ≠ EBITDA
- 折旧不是"非现金费用"——它是预付资本的回收
- EBITDA忽略了维持竞争地位所需的真实资本支出

## A1 — 书中的应用

### 案例: Apple的透视盈余
- **问题**: 伯克希尔从Apple投资中获得多少？
- **使用**: 2021年伯克希尔享有的Apple收益=$56亿，但仅收股息=$7.85亿
- **结果**: 会计利润严重低估真实经济进展（差7倍）

## A2 — 触发场景

1. 分析一家利润高但资本支出也高的公司
2. 评估一家控股/参股公司的真实盈利能力
3. 有人用EBITDA估值——需要指出问题
4. 理解为什么净利润和现金流差距很大

### 语言信号
- "这家公司EBITDA很高"
- "折旧不是现金成本"
- "利润和现金流为什么差这么多？"
- "未分配利润算不算我的？"

### 与相邻 skill 的区分
- 与 `economic-moat` 的区别：护城河分析企业竞争力，透视盈余分析企业真实赚钱能力

## E — 可执行步骤

1. **计算所有者收益** = 净利润 + 折旧摊销 - 维持性资本支出
   - 完成标准：区分"维持性"vs"扩张性"资本支出

2. **检查EBITDA陷阱**
   - 完成标准：如果EBITDA >> 所有者收益，标注"盈利质量存疑"
   - 判停：如果EBITDA与自由现金流差距>50% → 发出警告

3. **计算透视盈余**（适用于有参股公司的情况）
   - 完成标准：报告利润 + 按持股比例的未分配利润 - 假设税款

## B — 边界

- 估计"维持性"vs"扩张性"资本支出需要判断——不同人可能得出不同结论
- 透视盈余对短期投资者意义不大（未分配利润可能永远不实现）
- 作者盲点：巴菲特有足够的控制权来确保未分配利润最终实现——散户没有

---

## 相关 skills (阶段 3 填充)
- depends-on: business-picker
- composes-with: aesop-three-questions

## 审计信息
- **验证通过**: V1 ✓ / V2 ✓ / V3 ✓
- **蒸馏时间**: 2026-04-16

---
name: aesop-three-questions
description: |
  用户需要评估一个资产/投资/项目的价值，或纠结某个东西"值不值"时。适用于任何能产生（或不产生）现金流的资产评估。
  语言信号："这个值多少钱"/"这只股票贵不贵"/"这个项目值不值得投"/"应该用PE还是PB估值"
  不适用于：不需要估值分析的纯情感/审美决策。
source_book: 《巴菲特致股东的信》 沃伦·巴菲特
source_chapter: 2000年信
tags: [valuation, intrinsic-value, dcf, aesop]
related_skills: [circle-of-competence, margin-of-safety, economic-moat, three-asset-categories, first-law-of-capital-allocation, look-through-earnings]
---

# 伊索三问 / 内在价值评估

## R — 原文 (Reading)

> "The oracle was Aesop and his enduring, though somewhat incomplete, investment insight was 'a bird in the hand is worth two in the bush.' To flesh out this principle, you must answer only three questions: How certain are you that there are indeed birds in the bush? When will they emerge and how many will there be? What is the risk-free interest rate?"
>
> — Warren Buffett, 2000年信

---

## I — 方法论骨架 (Interpretation)

伊索三问是一个通用估值框架，适用于任何资产——农场、股票、债券、彩票、石油井：

1. **确定性（鸟真的在吗？）**: 你有多大把握这个资产会产生未来现金流？证据是什么？
2. **时间与数量（何时出现？有多少？）**: 现金流什么时候来？来多少？持续多久？
3. **折现率（无风险利率是多少？）**: 今天的$1和未来的$1价值不同——用无风险利率折现

关键洞察：
- 增长只是价值方程中的一个变量，不是对立面。增长可能是加号也可能是减号
- 常用指标（PE/PB/股息率）只是"线索"而非"答案"——它们帮你估计鸟的数量和时间
- 如果灌木丛里没有鸟（不产生现金流），任何价格都是投机

---

## A1 — 书中的应用 (Past Application)

### 案例1: 三类资产评估（2011年信）
- **问题**: 如何评估货币性资产、黄金、生产性资产的长期价值？
- **方法论的使用**:
  - 货币性资产（债券）：鸟的数量确定但货币在贬值 → 实际回报可能为负
  - 黄金（非生产性）：灌木丛里没有鸟 → 完全依赖有人出更高价
  - 生产性资产（农场/企业）：鸟会持续出现且数量可能增长 → 长期赢家
- **结论**: 生产性资产是"跑赢者"
- **结果**: 伯克希尔始终专注于生产性资产

### 案例2: Coca-Cola投资
- **问题**: Coca-Cola值不值$13亿？
- **方法论的使用**: 鸟（现金流）确定在，每年数量在增长（销量+定价权），持续期很长
- **结论**: 大量买入
- **结果**: 28年后$250亿价值+$7亿/年股息

---

## A2 — 触发场景 (Future Trigger) ★

1. 用户在评估一个投资是否"值得"
2. 用户纠结用什么指标（PE/PB/DCF）估值
3. 用户在比较不同资产类别的长期吸引力
4. 用户想判断一个"增长股"是否被高估
5. 用户问"NFT/加密货币/黄金值多少钱"

### 语言信号
- "这个值不值这个价？"
- "这只股票贵不贵？"
- "应该用PE还是DCF？"
- "增长股和价值股哪个好？"
- "XX资产有没有内在价值？"

### 与相邻 skill 的区分
- 与 `margin-of-safety` 的区别：伊索三问估价值，安全边际用价值与价格比较
- 与 `economic-moat` 的区别：护城河解释"为什么鸟会持续出现"，伊索三问计算"有多少鸟"

---

## E — 可执行步骤 (Execution)

1. **回答第一个问题：确定性**
   - 完成标准：列出3条证据证明这个资产会产生未来现金流（或说明无法证明）
   - 判停：如果无法证明现金流存在 → 这不是投资而是投机，停止

2. **回答第二个问题：时间与数量**
   - 完成标准：估计未来5-10年的现金流区间（不用精确，给范围即可）

3. **回答第三个问题：折现并比较**
   - 完成标准：用无风险利率折现后与当前价格比较，得出"便宜/合理/贵"的判断

---

## B — 边界 (Boundary)

- 不要对不产生现金流的资产用此框架（如比特币/NFT/黄金）——灌木丛里没有鸟，算不出来
- 对快速变化的行业，第二个问题（时间与数量）极难回答——诚实承认"我不知道"
- 内在价值是一个估计值而非精确数字——"宁可大概对也不要精确错"
- 作者局限：巴菲特对美国长期利率的假设可能不适用于其他市场

---

## 相关 skills (阶段 3 填充)

- depends-on: circle-of-competence
- composes-with: margin-of-safety, economic-moat

---

## 审计信息

- **验证通过**: V1 ✓ / V2 ✓ / V3 ✓
- **蒸馏时间**: 2026-04-16

---
name: mr-market
description: |
  用户在市场波动中情绪受到影响，或试图从市场价格变动中获取信息而非从企业分析中获取信息时。
  语言信号："市场在跌，是不是该卖"/"大家都在买"/"这只股票涨了很多，一定有道理"
  不适用于：纯粹的企业基本面分析（不含市场价格判断的场景）。
source_book: 《巴菲特致股东的信》 沃伦·巴菲特
source_chapter: 1987年信
tags: [behavioral, market-psychology, mr-market, graham]
related_skills: [business-picker, aesop-three-questions, margin-of-safety, fear-and-greed]
---

# 市场先生思维（含投票机vs称重机）

## R — 原文 (Reading)

> "He said that you should imagine market quotations as coming from a remarkably accommodating fellow named Mr. Market who is your partner in a private business... Mr. Market is there to serve you, not to guide you. It is his pocketbook, not his wisdom, that is useful to you."
>
> — Warren Buffett, 1987年信 (引用 Benjamin Graham)

> "In the short run, the market is a voting machine; in the long run, however, it becomes a weighing machine."
>
> — Benjamin Graham, 引用于1987年信和2017年信

---

## I — 方法论骨架 (Interpretation)

市场先生是一个行为框架，核心逻辑：

1. 把市场价格想象为一个叫"市场先生"的情绪化合伙人每天的报价
2. 他每天都会报一个买入价和卖出价——你可以接受也可以忽略
3. 他有时极度乐观（报高价），有时极度悲观（报低价）——情绪波动是你的机会
4. **他为你的决策提供服务，但不提供指导**——他的报价不是"信号"，而是"工具"
5. 短期看，市场是投票机（谁的故事更动听）；长期看，市场是称重机（企业的真实价值终将反映在价格上）
6. 你不需要预测市场先生的情绪——你只需要在他报出荒谬价格时利用它

---

## A1 — 书中的应用 (Past Application)

### 案例1: Washington Post 1973-74年
- **问题**: 市场暴跌，Washington Post股价从内在价值的1/4跌到不到1/5
- **方法论的使用**: 市场先生的极度悲观恰好提供了买入机会——他报了一个荒谬的低价
- **结论**: 大量买入
- **结果**: 持有数十年，回报数十倍

### 案例2: 互联网泡沫 1999-2000年
- **问题**: 所有科技股暴涨，价值投资者严重落后
- **方法论的使用**: 市场先生极度乐观——他在报高价，但企业的"重量"并没有增加
- **结论**: 坚持不参与
- **结果**: 成功避开泡沫破裂

---

## A2 — 触发场景 (Future Trigger) ★

### 用户会在什么情境下需要这个 skill?

1. 持有的资产价格大幅下跌，开始恐慌
2. 市场持续上涨，产生"不买就错过"的焦虑
3. 试图从价格走势中推断企业价值
4. 因为"大家都在买/卖"而想要跟风
5. 纠结是否应该"止损"

### 语言信号

- "市场在跌，是不是该卖？"
- "大家都在买这个"
- "这只股票涨了很多，一定有道理"
- "我亏了X%，要不要割肉"
- "现在是不是底部/顶部？"

### 与相邻 skill 的区分

- 与 `fear-and-greed` 的区别：恐惧贪婪是具体行动原则（买/卖），市场先生是更底层的认知框架（你怎么看待市场价格）
- 与 `business-picker` 的区别：做生意关注企业分析，市场先生关注如何对待市场报价

---

## E — 可执行步骤 (Execution)

1. **识别市场先生的当前情绪**
   - 完成标准：用1-2句话描述市场当前情绪（极度乐观/温和乐观/中性/温和悲观/极度悲观），并给出依据

2. **分离"报价"与"价值"**
   - 完成标准：写出现价 vs 你的内在价值估计，标注差距大小
   - 判停条件：如果无法估计内在价值 → 先用 `aesop-three-questions` 估值

3. **决定行动**
   - 如果市场先生报高价（>内在价值）→ 不买/考虑卖
   - 如果市场先生报低价（<内在价值）→ 考虑买/持有
   - 如果市场先生报合理价 → 不行动
   - 完成标准：行动基于价值-价格对比，而非基于市场情绪或价格走势

---

## B — 边界 (Boundary)

### 不要在以下情况使用此 skill

- 当你需要流动性（必须卖出）时——市场先生的报价就是你必须接受的价格
- 在非公开市场的资产中（没有市场先生的报价）
- 当你没有能力独立评估内在价值时——此时你无法判断市场先生的报价是否"荒谬"

### 作者的盲点 / 时代局限

- 巴菲特作为最大股东不需要面对赎回压力——普通投资者有流动性约束
- "忽略市场先生"需要极强的心理素质和长期资金——散户很难做到
- 在极端情况下（如杠杆被迫平仓），即使知道市场先生是错的也无法不行动

### 容易混淆的邻近方法论

- 不是"逆向投资"的简单版——逆向投资是行动，市场先生是认知框架
- 不是"技术分析"——市场先生不关注价格走势形态，只关注价格与价值的关系

---

## 相关 skills (阶段 3 填充)

- depends-on: business-picker, aesop-three-questions
- contrasts-with: (无)
- composes-with: fear-and-greed, margin-of-safety

---

## 审计信息

- **验证通过**: V1 ✓ / V2 ✓ / V3 ✓
- **测试通过率**: 待阶段 4 验证
- **蒸馏时间**: 2026-04-16

# 候选框架列表 — 巴菲特致股东的信

> 由 framework-extractor 产出，待阶段 1.5 三重验证筛选。

---

```yaml
- id: f01
  title: 能力圈 (Circle of Competence)
  type: framework
  source_chapter: 1999年信 / 2014年信
  source_quote: |
    "If we have a strength, it is in recognizing when we are operating well within our circle of competence and when we are approaching the perimeter." (1999)
    "It's vital, however, that we recognize the perimeter of our 'circle of competence' and stay well inside of it." (2014)
  summary: |
    面对任何决策时，先问自己：我对这件事的判断准确率是否经过验证？
    能力圈的大小不重要，重要的是知道边界在哪。
    越过边界时，不是"挑战自我"，而是"走向亏损"。
    即使在圈内也会犯错，但绝不会犯灾难性的错。
  tags: [decision, mental-model, circle-of-competence, boundary]

- id: f02
  title: 市场先生 (Mr. Market)
  type: framework
  source_chapter: 1987年信
  source_quote: |
    "He said that you should imagine market quotations as coming from a remarkably accommodating fellow named Mr. Market who is your partner in a private business... Mr. Market is there to serve you, not to guide you."
  summary: |
    把市场报价想象为一个情绪化的合伙人每天的报价。
    他的情绪波动是你的机会，不是你的指南针。
    你可以忽略他、利用他，但绝不能被他引导。
    如果你不确定自己比市场先生更懂这个生意，你就不该参与。
  tags: [behavioral, mental-model, market-psychology, mr-market]

- id: f03
  title: 伊索三问 (Aesop's Three Questions)
  type: framework
  source_chapter: 2000年信
  source_quote: |
    "The oracle was Aesop and his enduring, though somewhat incomplete, investment insight was 'a bird in the hand is worth two in the bush.' To flesh out this principle, you must answer only three questions. How certain are you that there are indeed birds in the bush? When will they emerge and how many will there be? What is the risk-free interest rate?"
  summary: |
    评估任何资产价值的通用框架——回答三个问题：
    (1) 确定性：灌木丛中真的有鸟吗？
    (2) 时间与数量：它们何时出现、会有多少？
    (3) 折现率：无风险利率是多少？
    这三问适用于农场、石油、债券、股票、彩票、工厂——一切资产。
    增长只是价值方程中的一个变量，不是对立面。
  tags: [valuation, framework, intrinsic-value, aesop, dcf]

- id: f04
  title: 套利四问 (Arbitrage Four Questions)
  type: framework
  source_chapter: 1988年信
  source_quote: |
    "To evaluate arbitrage situations you must answer four questions: (1) How likely is it that the promised event will indeed occur? (2) How long will your money be tied up? (3) What chance is there that something still better will transpire? and (4) What will happen if the event does not take place?"
  summary: |
    评估任何事件驱动型投资的四个必答题：
    (1) 承诺的事件确实发生的概率有多大？
    (2) 资金会被锁定多长时间？
    (3) 出现更好结果（如竞争性收购报价）的概率？
    (4) 如果事件不发生（反垄断、融资失败等），后果如何？
    这四问构成对风险-收益的完整评估结构。
  tags: [arbitrage, framework, event-driven, risk-assessment]

- id: f05
  title: 安全边际 (Margin of Safety)
  type: framework
  source_chapter: 1962年信 / 1985年信
  source_quote: |
    "This substantial excess of value creates a comfortable margin of safety in each transaction. This individual margin of safety, coupled with a diversity of commitments creates a most attractive package of safety and appreciation potential." (1962)
    "We insist on a margin of safety." (1985)
  summary: |
    买入价格必须大幅低于评估的内在价值，这个差额就是安全边际。
    安全边际不是止损线，而是买入前的保护垫——价格越低，保护越厚。
    单个投资的安全边际 + 多元化 = 安全与增值潜力的最佳组合。
    安全边际让你在判断出错时仍有可能不亏钱。
  tags: [decision, mental-model, margin-of-safety, downside-protection]

- id: f06
  title: 投票机 vs 称重机 (Voting Machine vs Weighing Machine)
  type: framework
  source_chapter: 1987年信 (引用Graham) / 2018年信
  source_quote: |
    "In the short run, the market is a voting machine but in the long run it is a weighing machine." (Graham, cited by Buffett)
  summary: |
    短期来看，市场价格由情绪和投票决定（谁的故事更动听）。
    长期来看，市场价格必然回归企业内在价值（称重）。
    因此：不要被短期投票结果困扰，专注于让重量增加。
    延迟的认可反而是机会——让你以便宜价格买到更多。
  tags: [cognitive, framework, market-behavior, long-term]

- id: f07
  title: 逆向操作 (Contrarian Greed/Fear)
  type: framework
  source_chapter: 1986年信
  source_quote: |
    "We simply attempt to be fearful when others are greedy and to be greedy only when others are fearful."
  summary: |
    面对市场极端情绪时的结构化应对：
    当别人贪婪时（市场价格高昂、信心爆棚），你应该恐惧。
    当别人恐惧时（市场价格崩溃、悲观弥漫），你应该贪婪。
    关键不是预测恐惧/贪婪何时到来，而是当它们出现时识别并反向行动。
  tags: [behavioral, framework, contrarian, greed-fear]

- id: f08
  title: 商业分析而非市场分析 (Business Analyst, Not Market Analyst)
  type: framework
  source_chapter: 1987年信
  source_quote: |
    "When investing, we view ourselves as business analysts - not as market analysts, not as macroeconomic analysts, and not even as security analysts."
  summary: |
    投资决策的分析路径：从商业出发，而非从市场出发。
    第一步看企业的经济前景、管理层素质、价格是否合理。
    不设定卖出时间或目标价，只要内在价值在满意增长就持有。
    市场的存在是为了服务你（提供机会），不是指导你。
  tags: [analytical, framework, business-analysis, investment-approach]

- id: f09
  title: 资本配置第一法则 (First Law of Capital Allocation)
  type: framework
  source_chapter: 2011年信
  source_quote: |
    "The first law of capital allocation – whether the money is slated for acquisitions or share repurchases – is that what is smart at one price is dumb at another."
  summary: |
    面对任何资本配置决策（收购、回购、投资）时的第一性原理：
    同一个行为在不同价格下可能是聪明的也可能是愚蠢的。
    价格决定行为的对错，而非行为本身决定对错。
    低于内在价值的回购是增值；高于内在价值的回购是损害。
  tags: [capital-allocation, framework, price-determines-wisdom, first-law]

- id: f10
  title: 内在价值 vs 账面价值 (Intrinsic Value vs Book Value)
  type: framework
  source_chapter: 1983年信 / 1989年信
  source_quote: |
    "Book value is an accounting concept, recording the accumulated financial input... Intrinsic business value is an economic concept, estimating future cash output discounted to present value. Book value tells you what has been put in; intrinsic business value estimates what can be taken out." (1983)
    "We define intrinsic value as the discounted value of the cash that can be taken out of a business during its remaining life." (1989)
  summary: |
    账面价值 = 过去投入了什么（会计概念，可精确计算但价值有限）。
    内在价值 = 未来能取出什么（经济概念，不可精确计算但至关重要）。
    二者可以严重背离——投入相同教育的两个人，产出天差地别。
    评估内在价值用DCF，接受模糊的正确而非精确的错误。
  tags: [valuation, framework, intrinsic-value, book-value, dcf]

- id: f11
  title: 透视盈余 (Look-Through Earnings)
  type: framework
  source_chapter: 1991年信 / 1992年信
  source_quote: |
    "We've previously discussed look-through earnings, which consist of: (1) the operating earnings reported... plus; (2) the retained operating earnings of major investees that, under GAAP accounting, are not reflected in our profits, less; (3) an allowance for the tax that would be paid by Berkshire if these retained earnings had instead been distributed to us."
  summary: |
    真实经济收益 ≠ 会计利润。结构化计算：
    透视盈余 = 报告利润 + 被投公司未分配利润的份额 - 假设税款。
    这比会计利润更接近真实的经济进展。
    留存收益的价值取决于用途，而非是否被计入报表。
  tags: [analytical, framework, look-through-earnings, accounting, true-economics]

- id: f12
  title: 经济商誉识别 (Economic Goodwill Identification)
  type: framework
  source_chapter: 1983年信 / 2005年信
  source_quote: |
    "We own several businesses that possess economic Goodwill (which is properly includable in intrinsic business value) far larger than the accounting Goodwill that is carried on our balance sheet." (1983)
    "Economic goodwill does not, in many cases, diminish. Indeed, in a great many instances — perhaps most — it actually grows in value over time. In character, economic goodwill is much like land." (1983 Appendix)
  summary: |
    识别两类商誉的分离：
    会计商誉：资产负债表上的数字，会摊销减少。
    经济商誉：品牌、市场地位等无形资产，往往随时间增长（如土地）。
    真正伟大的企业拥有远超账面数字的经济商誉。
    经济商誉使企业能在极少额外资本下持续增长收益。
  tags: [analytical, framework, economic-goodwill, intangible-assets, business-quality]

- id: f13
  title: 护城河框架 (Moat Framework)
  type: framework
  source_chapter: 2007年信 / 2005年信
  source_quote: |
    "A truly great business must have an enduring 'moat' that protects excellent returns on invested capital." (2007)
    "Every day, in countless ways, the competitive position of each of our businesses grows either weaker or stronger... we describe the phenomenon as 'widening the moat.'" (2005)
  summary: |
    评估企业的核心框架：是否存在持久护城河？
    护城河类型：低成本优势（GEICO）、强大全球品牌（Coca-Cola）。
    "持久"标准排除了快速变化行业（创造性毁灭使之不可预测）。
    护城河每天或强或弱——管理者的日常决策在"加宽"或"缩窄"护城河。
    短期利润与长期护城河冲突时，护城河优先。
  tags: [analytical, framework, moat, competitive-advantage, business-quality]

- id: f14
  title: 浮存金思维 (Float Thinking)
  type: framework
  source_chapter: 1996年信 / 多年信
  source_quote: |
    "Float is money we hold but don't own... An insurance business has value if its cost of float over time is less than the cost the company would otherwise incur to obtain funds. But the business is an albatross if the cost of its float is higher than market rates for money."
  summary: |
    寻找低成本杠杆替代的思维模型：
    浮存金 = 你持有但不属于自己的资金（保费先收、赔款后付）。
    关键不是有没有浮存金，而是浮存金的成本。
    综合比率<100 → 承保盈利 → 浮存金成本为负 → 被付费持有资金。
    这个模型可迁移到任何"先收后付"的商业场景。
  tags: [mental-model, framework, float, insurance, leverage-alternative]

- id: f15
  title: 三类投资分类法 (Three Categories of Investment)
  type: framework
  source_chapter: 1962年信
  source_quote: |
    "Our avenues of investment break down into three categories. These categories have different behavior characteristics, and the way our money is divided among them will have an important effect on our results."
  summary: |
    投资组合的结构化分类方法：
    (1) Generals（低估型）：无控制权、无时间表，依赖价值回归，随大盘波动。
    (2) Work-outs（事件驱动型）：依赖特定公司行动（并购/清算），收益可预测，与大盘脱钩。
    (3) Control（控制型）：控股或大幅持股，可影响决策，按年评估内在价值。
    三类有不同的行为特征，资金分配比例决定相对表现。
  tags: [portfolio, framework, three-categories, asset-classification]

- id: f16
  title: 逆向推理 / 反向思考 (Inversion)
  type: framework
  source_chapter: 1996年信 / 2010年信
  source_quote: |
    "We try to 'reverse engineer' our future at Berkshire, bearing in mind Charlie's dictum: 'All I want to know is where I'm going to die so I'll never go there.'" (1996)
    "Charlie laid out his strongest ambition: 'All I want to know is where I'm going to die, so I'll never go there.' That bit of wisdom was inspired by Jacobi, the great Prussian mathematician, who counseled 'Invert, always invert.'" (2010)
  summary: |
    面对复杂决策时的思维路径：不从正面推导成功，而从反面排除失败。
    先问"什么会导致灾难性结果？"然后系统性地避开那些路径。
    如果无法容忍某种后果（无论概率多低），就不要种下它的种子。
    应用举例：不借钱是因为无法容忍被强制平仓的后果。
  tags: [mental-model, framework, inversion, reverse-thinking, risk]

- id: f17
  title: 雪茄蒂策略 vs 伟大企业策略 (Cigar Butt vs Great Business)
  type: framework
  source_chapter: 2014年信（50周年回顾）
  source_quote: |
    "Buying the stock at that price was like picking up a discarded cigar butt that had one puff remaining in it. Though the stub might be ugly and soggy, the puff would be free." (2014)
    "But a major weakness in this approach gradually became apparent: Cigar-butt investing was scalable only to a point. With large sums, it would never work well."
    "It took Charlie Munger to break my cigar-butt habits and set the course for building a business that could combine huge size with satisfactory profits."
  summary: |
    两种投资策略的对比框架：
    雪茄蒂：以极低价格买入平庸企业，获取最后"免费的一口"——小资金有效但不可扩展。
    伟大企业：以合理价格买入优秀企业——可扩展且长期回报更优。
    关键转变：从"以便宜价格买还不错的企业"到"以合理价格买伟大的企业"。
    选伴侣标准高于约会标准——构建持久企业需要更严格的筛选。
  tags: [strategy, framework, cigar-butt, business-quality, scalability]

- id: f18
  title: 复利思维 (Compounding Thinking)
  type: framework
  source_chapter: 1963年信
  source_quote: |
    "It is always startling to see how relatively small differences in rates add up to very significant sums over a period of years. That is why, even though we are shooting for more, we feel that a few percentage points advantage over the Dow is a very worthwhile achievement."
  summary: |
    认知框架：小差异经时间放大后产生巨大效应。
    5%/10%/15%的年化收益率，30年后差异可达4倍/17倍/66倍。
    核心推论：不需要每年超高收益，持续稳定的边际优势即可创造惊人财富。
    复利的两个要素：活得够久 + 收益率别太差。
    反向推论：避免灾难性损失比追求暴利更重要（零乘一切为零）。
  tags: [cognitive, framework, compounding, long-term, mathematics]

- id: f19
  title: 留存收益1美元测试 ($1 Retained = $1 Market Value Test)
  type: framework
  source_chapter: 1983年信
  source_quote: |
    "We test the wisdom of retaining earnings by assessing whether retention, over time, delivers shareholders at least $1 of market value for each $1 retained. We will continue to apply it on a five-year rolling basis."
  summary: |
    评估公司是否应保留利润的结构化检验：
    每保留$1利润，长期来看是否创造了至少$1的市场价值？
    如果是 → 保留利润是合理的。
    如果否 → 应将利润分配给股东（他们可以自己找到更好的用途）。
    以五年为滚动窗口检验，避免短期噪音。
    这个测试的核心：留存收益的价值取决于用途，而非所有权比例。
  tags: [analytical, framework, retained-earnings, capital-allocation, test]

- id: f20
  title: 诺亚法则 / 预言不够，造船才算 (Noah Rule: Predicting Rain Doesn't Count)
  type: framework
  source_chapter: 2001年信 / 2015年信
  source_quote: |
    "I violated the Noah rule: Predicting rain doesn't count; building arks does." (2001)
    "Call this Noah's Law: If an ark may be essential for survival, begin building it today, no matter how cloudless the skies appear." (2015)
  summary: |
    风险管理的行动框架：认知不等于行动。
    预测到风险还不够——必须将认知转化为防御行动。
    即使天空晴朗，如果方舟可能是生存所必需的，今天就该开始建造。
    巴菲特自己承认在9/11前"认知到了恐怖主义风险但没有转化为行动"的教训。
    应用：不仅仅识别风险，更要为之做好具体准备。
  tags: [risk-management, framework, action-bias, preparation, noah-rule]

- id: f21
  title: 机构强制力 (Institutional Imperative)
  type: framework
  source_chapter: 2004年信
  source_quote: |
    "Most American businesses harbor an 'institutional imperative' that rejects extended decreases in volume. What CEO wants to report to his shareholders that not only did business contract last year but that it will continue to drop?"
  summary: |
    识别组织行为偏差的思维模型：
    机构强制力 = 管理者模仿同行的愚蠢倾向，拒绝业务收缩。
    三个来源：(1) CEO不愿报告收缩；(2) 后果可能延迟暴露；(3) 乐观储备掩盖真实成本。
    解药：以利润为导向定价，不以市场份额为荣。
    "No"必须是保险承保人词汇中的重要组成部分。
  tags: [behavioral, mental-model, institutional-imperative, bias, organizational]

- id: f22
  title: 集中投资 vs 过度分散 (Concentration vs Over-Diversification)
  type: framework
  source_chapter: 1965年信
  source_quote: |
    "We might invest up to 40% of our net worth in a single security under conditions coupling an extremely high probability that our facts and reasoning are correct with a very low probability that anything could drastically change the underlying value of the investment."
  summary: |
    投资组合构建的结构化思考：
    分散化的最优程度取决于：期望收益率、方差、各选择的关联度。
    持有100只股票是"诺亚方舟投资法"——每样两个——违反数学原理。
    第100只股票加入组合时，降低方差的收益已无法弥补期望收益的损失。
    愿意承受更大的年度波动，换取更高的长期优势。
    集中的前提：极高的确定性 + 极低的本金永久损失概率。
  tags: [portfolio, framework, concentration, diversification, position-sizing]

- id: f23
  title: 四要素选股框架 (Four-Element Stock Selection)
  type: framework
  source_chapter: 2007年信
  source_quote: |
    "Charlie and I look for companies that have a) a business we understand; b) favorable long-term economics; c) able and trustworthy management; and d) a sensible price tag."
  summary: |
    买入任何企业（全资或部分）的四个必要条件：
    (a) 能理解这门生意（能力圈内）；
    (b) 长期经济前景有利（有护城河）；
    (c) 管理层有能力且值得信任；
    (d) 价格合理。
    买不到全资 → 也乐于通过股市买伟大企业的小部分。
    "拥有希望钻石的一角，胜过拥有一整颗莱茵石。"
  tags: [decision, framework, stock-selection, four-criteria, checklist]

- id: f24
  title: 零乘一切为零 / 杠杆归零风险 (Zero Multiplied by Everything)
  type: framework
  source_chapter: 2023年信（芒格语录） / 2018年信
  source_quote: |
    "A string of wonderful numbers times zero will always equal zero. Don't count on getting rich twice." (2023, Munger)
  summary: |
    理解杠杆致命性的数学框架：
    杠杆在一切顺利时放大收益，但一次灾难足以将总收益归零。
    一串美妙的数字乘以零，永远等于零。
    伯克希尔历史上四次跌50%——使用杠杆的人在任何一个点都可能被强制平仓。
    即使借款很少、仓位不会立即被威胁，恐慌新闻也会扰乱心智 → 做出糟糕决策。
  tags: [risk, framework, leverage, zero-risk, permanent-loss]

- id: f25
  title: 内在价值的大学教育类比 (College Education Analogy for Valuation)
  type: framework
  source_chapter: 1989年信
  source_quote: |
    "Think of the education's cost as its 'book value.' ... First, we must estimate the earnings that the graduate will receive over his lifetime and subtract from that figure an estimate of what he would have earned had he lacked his education. That gives us an excess earnings figure, which must then be discounted... Some graduates will find that the book value of their education exceeds its intrinsic value."
  summary: |
    理解内在价值与账面价值差异的思维框架：
    类比大学教育——"账面价值"是投入的学费（含机会成本）。
    "内在价值"是超额终身收入的折现值。
    同样的投入，不同人的产出天差地别。
    推论：不能根据投入判断价值，必须根据未来产出估算。
  tags: [analytical, framework, analogy, intrinsic-value, education]

- id: f26
  title: 五年可预测性测试 (Five-Year Predictability Test)
  type: framework
  source_chapter: 2014年信
  source_quote: |
    "We first have to decide whether we can sensibly estimate an earnings range for five years out, or more. If the answer is yes, we will buy the stock (or business) if it sells at a reasonable price in relation to the bottom boundary of our estimate. If, however, we lack the ability to estimate future earnings – which is usually the case – we simply move on to other prospects."
  summary: |
    买入决策的两步过滤：
    第一步：能否合理估计未来5年的盈利区间？如果不能 → 直接放弃。
    第二步：如果能，价格是否低于估计区间的下限？
    大多数情况下，无法估计 → 因此大多数机会被跳过。
    "我们从未因为宏观或政治环境、或他人的观点而放弃一个有吸引力的购买。"
  tags: [decision, framework, predictability, five-year, filter]

- id: f27
  title: 花朵绽放，杂草凋零 (Flowers Bloom, Weeds Wither)
  type: framework
  source_chapter: 2022年信
  source_quote: |
    "The lesson for investors: The weeds wither away in significance as the flowers bloom. Over time, it takes just a few winners to work wonders. And, yes, it helps to start early and live into your 90s as well."
  summary: |
    长期投资回报的非对称结构：
    少数大赢家创造的财富，足以抵消所有平庸和失败的决策。
    关键不是每次都对，而是让对的决策有足够时间复利增长。
    可口可乐和运通各投13亿美元，数十年后分别增值到250亿和220亿。
    反面教材：同样13亿投30年国债，仍只值13亿——仅占净资产的0.3%。
    核心洞察：不活跃也是一种策略——让花朵自己生长。
  tags: [cognitive, framework, asymmetric-returns, long-term, winners]

- id: f28
  title: 价格决定价值 / 价格与价值的分离 (Price vs Value)
  type: framework
  source_chapter: 2008年信 / 2014年信
  source_quote: |
    "Price is what you pay. Value is what you get." (2008, citing Graham)
    "A sound investment can morph into a rash speculation if it is bought at an elevated price. Berkshire is not exempt from this truth." (2014)
  summary: |
    投资的基础认知框架：
    价格 ≠ 价值。价格是你付出的，价值是你得到的。
    同一个企业在不同价格下：低价买入是投资，高价买入是投机。
    即使是优秀企业，买入价格过高也会导致多年不盈利。
    买入时的价格决定了结果的上限和下限。
  tags: [cognitive, framework, price-vs-value, investment-basics]

- id: f29
  title: 反向工程未来 (Reverse Engineering the Future)
  type: framework
  source_chapter: 1996年信
  source_quote: |
    "In this respect, as in others, we try to 'reverse engineer' our future at Berkshire... If we can't tolerate a possible consequence, remote though it may be, we steer clear of planting its seeds."
  summary: |
    从不可接受的结局出发，反向推导今天应避免的行为：
    先想象最坏的可能后果。
    如果某个后果不可容忍（即使概率很低），就不种下它的种子。
    因此不借大钱 → 因为无法容忍被迫平仓。
    因此不写可能需要大量追加保证金的衍生品合约。
    这不是预测灾难何时发生，而是确保灾难发生时你不受致命伤害。
  tags: [risk-management, framework, reverse-engineering, worst-case, survival]

- id: f30
  title: 非专业投资者的简化框架 (Simplified Framework for Non-Professional Investors)
  type: framework
  source_chapter: 2014年信
  source_quote: |
    "The goal of the non-professional should not be to pick winners... but should rather be to own a cross-section of businesses that in aggregate are bound to do well. A low-cost S&P 500 index fund will achieve this goal."
    "My advice to the trustee could not be more simple: Put 10% of the cash in short-term government bonds and 90% in a very low-cost S&P 500 index fund."
  summary: |
    对无法/不愿深入研究个股的投资者的决策框架：
    承认自己不知道 → 拥有全市场的横截面 → 低成本指数基金。
    何时买：定投而非一把梭，避免在极端狂热时入场。
    何时卖：不要在坏消息和股价下跌时卖。
    对费用的警惕：摩擦成本（管理费、交易成本）长期来看是巨大的。
    自知之明的优势：不专业但了解自己短板的投资者，可能比忽视自身弱点的高手做得更好。
  tags: [decision, framework, index-investing, non-professional, simple]

- id: f31
  title: 增长不是价值的对立面 (Growth Is a Component of Value)
  type: framework
  source_chapter: 2000年信
  source_quote: |
    "Market commentators and investment managers who glibly refer to 'growth' and 'value' styles as contrasting approaches to investment are displaying their ignorance, not their sophistication. Growth is simply a component — usually a plus, sometimes a minus — in the value equation."
    "Growth can destroy value if it requires cash inputs in the early years of a project or enterprise that exceed the discounted value of the cash that those assets will generate in later years."
  summary: |
    纠正"价值vs成长"二分法的认知框架：
    增长只是价值方程中的一个变量——通常是加号，有时是减号。
    如果增长需要大量资本投入且回报低于资本成本，增长反而摧毁价值。
    传统指标（股息率、PE、PB、增长率）本身不等于估值，它们只是提供现金流线索。
    所有资产估值都统一于伊索三问（确定性、时间与数量、折现率）。
  tags: [cognitive, framework, growth-vs-value, valuation, correction]

- id: f32
  title: 三大财务持久力要素 (Three Pillars of Financial Endurance)
  type: framework
  source_chapter: 2014年信（50周年）
  source_quote: |
    "Financial staying power requires a company to maintain three strengths under all circumstances: (1) a large and reliable stream of earnings; (2) massive liquid assets and (3) no significant near-term cash requirements."
  summary: |
    评估任何企业/个人财务安全的三要素框架：
    (1) 大而可靠的盈利流（来自多元业务，确保持续）。
    (2) 大量流动资产（现金如氧气——充裕时不被注意，缺乏时是唯一重要的事）。
    (3) 没有重大的近期现金需求（不依赖展期、不面临追加保证金）。
    三者缺一即脆弱——许多盈利企业因忽视第三点而在危机中倒塌。
  tags: [risk-management, framework, financial-strength, three-pillars, survival]

- id: f33
  title: 收购目标分类法 (Acquisition Category Framework)
  type: framework
  source_chapter: 1981年信
  source_quote: |
    "Two major categories stand out. The first involves companies that have purchased only businesses that are particularly well adapted to an inflationary environment: (1) an ability to increase prices rather easily... and (2) an ability to accommodate large dollar volume increases in business with only minor additional investment of capital."
  summary: |
    收购目标的两类框架：
    第一类（抗通胀企业）：具备两个特征——(1) 能轻松提价而不失客户；(2) 能以极少新增资本承载大幅收入增长。
    第二类（超级管理者）：能识别伪装成蟾蜍的王子，并有能力剥离伪装。
    巴菲特的自我评估：不符合第二类，对第一类的理解虽好但执行不足。
    "买蟾蜍的亲吻很少奏效，买王子则不需要亲吻。"
  tags: [acquisition, framework, inflation-resistant, business-categories]

- id: f34
  title: 五年区间估计法 (Range Estimation vs False Precision)
  type: framework
  source_chapter: 2000年信
  source_quote: |
    "Using precise numbers is, in fact, foolish; working with a range of possibilities is the better approach."
  summary: |
    估值时的认知方法论：
    用精确数字是愚蠢的，用概率区间才是正确方法。
    如果区间太宽 → 无法得出有用结论 → 放弃。
    如果即使非常保守的估计下，价格仍远低于价值 → 这就是机会。
    不需要天才般的洞察力，需要的是独立思考和对商业经济的基本理解。
  tags: [analytical, framework, range-estimation, valuation, epistemology]
```

---

> 共 34 条候选框架，覆盖 1950s-2020s 全部年代。待阶段 1.5 三重验证筛选。

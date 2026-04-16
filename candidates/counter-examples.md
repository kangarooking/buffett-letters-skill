# Counter-Examples: 巴菲特致股东的信 — 失败模式与陷阱

> 本文件是 book2skill 流水线阶段 1 产出, 由反例提取器从原书中提取。
> 每条均包含 failure_mode、mechanism、warning_signs、bound_to 和原文引用。

---

- id: ce01
  title: 蛤蟆变王子的收购幻想
  type: counter-example
  source_chapter: 1981年信 / 1989年信
  source_quote: |
    "Many managements apparently were overexposed in impressionable childhood years to the story in which the imprisoned handsome prince is released from a toad's body by a kiss from a beautiful princess. Consequently, they are certain their managerial kiss will do wonders for the profitability of Company T(arget)."
    "In my early days as a manager I, too, dated a few toads. They were cheap dates - I've never been much of a sport - but my results matched those of acquirers who courted higher-priced toads. I kissed and they croaked."
  failure_mode: |
    以溢价收购平庸企业，期望通过管理改善来创造价值。现实是：平庸企业不会因为换了主人就变优秀。
    管理层深信自己的"管理之吻"能带来奇迹，结果是在越来越多的蛤蟆上浪费资本。
  mechanism: |
    管理层受"机构强制力"驱动——模仿其他管理者的行为，无论多愚蠢。
    收购顾问（投行）永远有理由证明收购合理——"电子表格从不让人失望"。
    自我选择偏差：只有自信能改善目标公司的人才会发起收购，而这份自信往往没有根据。
  warning_signs:
    - 大量使用"协同效应"来证明收购价格
    - 用股票而非现金支付收购对价
    - 目标公司历史表现无法证明其价值
    - 收购后频繁计提"重组费用"
    - CEO将收购规模视为个人成就
  bound_to:
    - "做生意不做股票"
    - "买入价格决定一切"
    - "只与喜欢的人合作"
    - "保守≠传统"
  tags: [counter-example, acquisition, toad-prince, institutional-imperative]

- id: ce02
  title: 机构强制力 — 管理者模仿同行的愚蠢倾向
  type: counter-example
  source_chapter: 1989年信 / 2004年信（保险部分）
  source_quote: |
    "Most American businesses harbor an 'institutional imperative' that rejects extended decreases in volume. What CEO wants to report to his shareholders that not only did business contract last year but that it will continue to drop?"
    "If 'winning,' however, is equated with market share rather than profits, trouble awaits."
  failure_mode: |
    企业管理者不由自主地模仿同行行为，即使这些行为在经济上是非理性的。
    具体表现为：不愿收缩规模、不愿放弃市场份额、不愿承认错误，宁可亏损也要维持表面增长。
  mechanism: |
    CEO的考核标准和自尊心与规模/增长挂钩，而非盈利能力。
    董事会很少真正考核CEO的表现——"老板射出管理绩效之箭，然后在箭落地处匆忙画上靶心"。
    同行都在做的事被视为"安全"——即使错了也不是一个人的错。
  warning_signs:
    - 管理层用市场份额而非盈利能力衡量成功
    - 在明显不赚钱的价位继续承接业务
    - 行业内所有人都在做同样的事，无人愿意收缩
    - CEO不愿在年报中报告业务收缩
  bound_to:
    - "做生意不做股票"
    - "不活跃也是一种策略"
    - "保守≠传统"
  tags: [counter-example, institutional-imperative, management-behavior, psychology]

- id: ce03
  title: 纺织业失败 — 行业选择优于管理努力
  type: counter-example
  source_chapter: 1985年信（纺织业关闭） / 1978年信 / 2010年信
  source_quote: |
    "Our managers were resourceful, energetic and imaginative in attempting to make our textile operation a success. Trying to achieve sustainable profitability, they reworked product lines, machinery configurations and distribution arrangements. We also made a major acquisition, Waumbec Mills, with the expectation of important synergy (a term widely used in business to explain an acquisition that otherwise makes no sense). But in the end nothing worked and I should be faulted for not quitting sooner."
    "I ignored Comte's advice — 'the intellect should be the servant of the heart, but not its slave' — and believed what I preferred to believe."
  failure_mode: |
    在结构性衰败的行业中投入资本和精力，期望通过管理改善扭转乾坤。
    即使每次投资按标准ROI测试看起来都"合算"，但行业内的竞争性投资互相抵消，回报始终微薄。
    管理层的聪明才智和辛勤工作无法对抗行业的结构性劣势。
  mechanism: |
    在商品化行业中，所有竞争者都在做同样的资本投入，成本下降最终转化为价格下降——"每个人看游行时都觉得踮起脚尖能看得更清楚，但当所有人都踮起脚尖时，谁也没有优势"。
    Burlinton Industries在21年间投入30亿美元资本支出，远超所有美国纺织公司，但回报依然惨淡。
    沉没成本谬误：已经投入越多，越难退出。
  warning_signs:
    - 行业存在大量过剩产能
    - 竞争优势来自低成本劳动力或低成本资本
    - 每轮资本投入带来的成本优势都被价格竞争抹平
    - 管理层优秀但行业经济学差
    - "转身"策略反复失败
  bound_to:
    - "经济商誉/护城河识别"
    - "做生意不做股票"
    - "内在价值评估"
    - "能力圈判断"
  tags: [counter-example, textile, industry-selection, commodity-business, sunk-cost]

- id: ce04
  title: Dexter鞋业 — 用股票收购的致命错误
  type: counter-example
  source_chapter: 1993年信 / 2001年信 / 2007年信 / 2010年信 / 2015年信
  source_quote: |
    "I clearly made a mistake in paying what I did for Dexter in 1993. Furthermore, I compounded that mistake in a huge way by using Berkshire shares in payment."
    "What I had assessed as durable competitive advantage vanished within a few years. But that's just the beginning: By using Berkshire stock, I compounded this error hugely. That move made the cost to Berkshire shareholders not $400 million, but rather $3.5 billion. In essence, I gave away 1.6% of a wonderful business — one now valued at $220 billion — to buy a worthless business."
    "As a financial disaster, this one deserves a spot in the Guinness Book of World Records."
  failure_mode: |
    双重错误叠加：(1) 错判了企业的竞争持久性；(2) 用伯克希尔股票而非现金支付，让错误被复利放大。
    用一家优秀企业的股权去换一家平庸企业的所有权，"不可修复地摧毁了价值"。
  mechanism: |
    用股票收购本质上是在用自己1美元的内在价值去换取对方不到1美元的内在价值。
    投资银行家用"市场溢价惯例"和"每股收益增厚"来证明收购合理——这些都是"愚蠢的评估方式"。
    复利的魔力反噬：放弃的1.6%伯克希尔股权随时间增值至35亿美元以上。
  warning_signs:
    - 用自己公司的股票而非现金收购
    - 目标企业处于面临低成本海外竞争的行业
    - "持久竞争优势"的判断基于过去表现而非结构性分析
    - 投行用每股收益增厚来证明收购合理
  bound_to:
    - "不用杠杆"
    - "买入价格决定一切"
    - "做生意不做股票"
    - "复利思维"
  tags: [counter-example, dexter-shoe, stock-for-stock, acquisition, compounding]

- id: ce05
  title: EBITDA是危险指标
  type: counter-example
  source_chapter: 1989年信 / 2000年信 / 2002年信 / 2014年信 / 2016年信
  source_quote: |
    "References to EBITDA make us shudder — does management think the tooth fairy pays for capital expenditures?"
    "Trumpeting EBITDA (earnings before interest, taxes, depreciation and amortization) is a particularly pernicious practice. Doing so implies that depreciation is not truly an expense, given that it is a 'non-cash' charge. That's nonsense. In truth, depreciation is a particularly unattractive expense because the cash outlay it represents is paid up front, before the asset acquired has delivered any benefits to the business."
    "When CEOs tout EBITDA as a valuation guide, button your wallet." / "watch their noses lengthen while they speak."
  failure_mode: |
    用EBITDA估值自欺欺人：将折旧视为"非真实成本"，实际上折旧代表了前期已经支付的现金支出。
    企业需要持续进行资本支出才能维持竞争力，但EBITDA完全忽略这一点。
  mechanism: |
    折旧是"一种特别不吸引人的费用，因为它代表的现金支出是预先支付的，在资产为企业带来任何好处之前就已经付出了"。
    想象一家公司在年初预付了员工未来10年的工资——后9年没有现金支出，但不代表人力成本为零。
    华尔街推广EBITDA是因为它让数字看起来更大、估值更"便宜"。
    BNSF的折旧费用甚至低于维持铁路正常运转所需的资本支出，导致GAAP利润高于真实经济利润。
  warning_signs:
    - 管理层在财报中突出展示EBITDA而非净利润
    - 用EBITDA/利息来衡量偿债能力
    - 资本密集型行业特别热衷EBITDA
    - 分析师不加质疑地引用公司提供的"调整后EBITDA"
  bound_to:
    - "所有者收益"
    - "内在价值评估"
    - "透视盈余"
  tags: [counter-example, EBITDA, accounting, valuation, depreciation]

- id: ce06
  title: 衍生品是大规模杀伤性武器
  type: counter-example
  source_chapter: 2002年信
  source_quote: |
    "Charlie and I are of one mind in how we feel about derivatives and the trading activities that go with them: We view them as time bombs, both for the parties that deal in them and for the economic system."
    "In the reinsurance and derivatives businesses: Like Hell, both are easy to enter and almost impossible to exit."
    "The derivatives genie is now well out of the bottle, and these instruments will almost certainly multiply in variety and number until some event makes their toxicity clear."
    "derivatives are financial weapons of mass destruction, carrying dangers that, while now latent, are potentially lethal."
  failure_mode: |
    衍生品交易的盈利基于mark-to-model而非真实市场报价，造成"mark-to-myth"——双方可以同时显示巨额利润多年。
    衍生品放大了单个机构的风险并创建了链式反应的传导机制。
  mechanism: |
    (1) 估值幻觉：没有真实市场时用模型估值，双方可以同时"盈利"多年，直到崩溃。
    (2) 奖励扭曲：交易员按"盈利"拿奖金，CEO按"盈利"拿期权，但亏损要多年后才暴露。
    (3) 链式风险：一个机构的倒闭可以传染给链条上其他机构——"没有中央银行为保险或衍生品的倒牌效应兜底"。
    (4) 信用降级触发：衍生品合约要求信用降级时立即追加抵押品，形成"降级→追加保证金→流动性危机→进一步降级"的死亡螺旋。
  warning_signs:
    - 企业持有大量长期衍生品合约
    - 盈利严重依赖"mark-to-model"
    - 交易员薪酬与短期"盈利"挂钩
    - 衍生品头寸集中在少数交易商手中
  bound_to:
    - "不用杠杆"
    - "CEO=首席风险官"
    - "保守≠传统"
  tags: [counter-example, derivatives, systemic-risk, mark-to-model, LTCM]

- id: ce07
  title: 杠杆归零 — 一串正数乘以零永远等于零
  type: counter-example
  source_chapter: 2010年信 / 2008年（Berkshire年报） / 2023年信（芒格语录）
  source_quote: |
    "Unquestionably, some people have become very rich through the use of borrowed money. However, that's also been a way to get very poor. When leverage works, it magnifies your gains. Your spouse thinks you're clever, and your neighbors get envious. But leverage is addictive. Once having profited from its wonders, very few people retreat to more conservative practices. And as we all learned in third grade — and some relearned in 2008 — any series of positive numbers, however impressive the numbers may be, evaporates when multiplied by a single zero."
    "Over the years, a number of very smart people have learned the hard way that a long string of impressive numbers multiplied by a single zero always equals zero."
    "Credit is like oxygen. When either is abundant, its presence goes unnoticed. When either is missing, that's all that is noticed."
  failure_mode: |
    杠杆在一切顺利时放大收益、制造"聪明"的幻觉，但一次灾难就足以让一切归零。
    杠杆具有成瘾性——尝到甜头后极少有人主动降杠杆。
    信用就像氧气：充裕时无人注意，缺乏时别无他念。
  mechanism: |
    杠杆创造了对持续可获得的信贷的依赖。但信贷市场可能在最需要的时候消失——2008年9月的隔夜信贷冻结几乎让整个国家瘫痪。
    即使是"非常聪明的人"也会被杠杆摧毁——LTCM的教训。
    "为了完成第一，你必须先完成比赛"——赛车的基本原则同样适用于商业。
  warning_signs:
    - 用借来的钱投资
    - 依赖短期融资支持长期资产
    - 资产负债表有重大到期日集中
    - 有触发追加保证金的衍生品合约
  bound_to:
    - "不用杠杆"
    - "CEO=首席风险官"
    - "安全边际"
  tags: [counter-example, leverage, debt, risk-of-ruin, 2008-crisis]

- id: ce08
  title: 投机与投资的混淆 — 灰姑娘寓言
  type: counter-example
  source_chapter: 1987年信 / 1989年信
  source_quote: |
    "But, like Cinderella at the ball, you must heed one warning or everything will turn into pumpkins and mice: Mr. Market is there to serve you, not to guide you."
    "Consciously paying more for a stock than its calculated value — in the hope that it can soon be sold for a still-higher price — should be labeled speculation (which is neither illegal, immoral nor — in our view — financially fattening)."
  failure_mode: |
    将"投机"包装为"投资"——以高于计算价值的价格买入，期望以更高价格卖出。
    灰姑娘在舞会上忘了时间——投机者在泡沫中忘了估值纪律，一切在午夜（市场崩溃时）变回原形。
  mechanism: |
    投机者不关注企业本身的商业价值，而关注"其他投资者接下来会怎么做"。
    "专业"投资者将股票视为游戏中的棋子（如大富翁中的顶针和熨斗）。
    投机可以持续获利很长时间（让人误以为自己是"投资天才"），但最终价格必然回归价值。
  warning_signs:
    - 买入理由是"还有人会以更高价格接盘"
    - 关注市场走势而非企业基本面
    - 持有期极短，频繁交易
    - 用复杂的金融术语（beta、dynamic hedging）替代商业分析
  bound_to:
    - "做生意不做股票"
    - "内在价值评估"
    - "市场先生思维"
    - "买入价格决定一切"
  tags: [counter-example, speculation, cinderella, bubble, market-mr]

- id: ce09
  title: 投资组合保险 — 1987崩盘的加速器
  type: counter-example
  source_chapter: 1987年信 / 1991年信
  source_quote: |
    "An extreme example of what their attitude leads to is 'portfolio insurance,' a money-management strategy that many leading investment advisors embraced in 1986-1987. This strategy — which is simply an exotically-labeled version of the small speculator's stop-loss order — dictates that ever increasing portions of a stock portfolio, or their index-future equivalents, be sold as prices decline."
    "According to the Brady Report, $60 billion to $90 billion of equities were poised on this hair trigger in mid-October of 1987."
    "whose destructive effects in the 1987 market crash led one wag to observe that it was the computers that should have been jumping out of windows."
  failure_mode: |
    "投资组合保险"本质上就是止损单的复杂版本——价格越低越要卖出。这在逻辑上是荒谬的：如果你拥有一家好企业的部分股权，越便宜应该越想买，而不是卖。
    600-900亿美元的资产被设在这样的"发丝扳机"上，导致1987年崩盘的自动级联卖出。
  mechanism: |
    机构投资者不关注企业价值，只关注"其他基金经理接下来几天会怎么做"。
    价格下跌触发自动卖出，卖出导致进一步下跌，进一步触发更多卖出——自我实现的崩溃螺旋。
    "逻辑"推论：价格大幅反弹后应买回——本质上是"高买低卖"的机械化版本。
  warning_signs:
    - 投资策略依赖价格变动触发自动操作
    - 不考虑企业内在价值的卖出决策
    - 系统性策略可能在同一时间产生同向操作
  bound_to:
    - "恐惧与贪婪逆向"
    - "投票机vs称重机"
    - "做生意不做股票"
  tags: [counter-example, portfolio-insurance, 1987-crash, mechanical-strategy]

- id: ce10
  title: 保险准备金自评考试
  type: counter-example
  source_chapter: 2001年信 / 2017年信 / 2018年信
  source_quote: |
    "insurance accounting is a self-graded exam, in that the insurer gives some figures to its auditing firm and generally doesn't get an argument. A company experiencing financial difficulties — of a kind that, if truly faced, could put it out of business — seldom proves to be a tough grader. Who, after all, wants to prepare his own execution papers?"
    "Ignorance, wishful thinking or, occasionally, downright fraud can deliver inaccurate figures about an insurer's financial condition for a very long time."
  failure_mode: |
    保险公司自行评估损失准备金，审计师通常不会提出异议。结果是：管理层可以多年报告虚高的利润，直到真实的损失最终暴露。
    在再保险和长尾业务中，"不知晓真实成本是炸药"——损失低估可以持续多年而不被发现。
  mechanism: |
    准备金的估算是管理层的主观判断，没有客观市场报价来验证。
    陷入困境的公司几乎不会严格给自己打低分——"谁愿意准备自己的死刑执行文件？"
    General Re就犯了这一错误——准备金严重不足，导致产品定价错误，年复一年地承保亏本业务而不自知。
  warning_signs:
    - 保险公司连续多年报告"意外"的准备金不足
    - 行业综合比率持续高于100%
    - 长尾责任险准备金增长与已赚保费不匹配
    - 管理层频繁使用"损失发展"等中性词汇描述准备金不足
  bound_to:
    - "CEO=首席风险官"
    - "保守≠传统"
    - "透视盈余"
  tags: [counter-example, insurance, reserving, self-deception, accounting]

- id: ce11
  title: General Re文化错配与承保纪律丧失
  type: counter-example
  source_chapter: 2001年信
  source_quote: |
    "In the past I have assured you that General Re was underwriting with discipline — and I have been proven wrong. Though its managers' intentions were good, the company broke each of the three underwriting rules I set forth in the last section and has paid a huge price for doing so."
    "Additionally, General Re was overly-competitive in going after, and retaining, business. While all concerned may intend to underwrite with care, it is nonetheless difficult for able, hard-driving professionals to curb their urge to prevail over competitors."
  failure_mode: |
    收购General Re后，巴菲特错误地信任其原有承保纪律。General Re违反了承保三原则：(1) 只承保能正确评估的风险；(2) 限定在能力圈内；(3) 避免业务集中。
    核心原因是准备金严重不足——"不知道自己的成本就在销售产品"，导致年复一年地严重定价不足。
  mechanism: |
    能干、进取心强的专业人士很难抑制自己战胜竞争对手的冲动——即使初衷是审慎承保。
    在伯克希尔强大资本后盾下，General Re本可以承受更大的波动，但反而因为要"赢得"市场份额而放松了承保标准。
    "不"必须是任何承保商词汇中的重要组成部分。
  warning_signs:
    - 收购后信任被收购方的原有管理系统而不加验证
    - 承保团队将市场份额视为成功指标
    - 准备金估算持续乐观
    - 管理层意图良好但执行偏离
  bound_to:
    - "只与喜欢的人合作"
    - "CEO=首席风险官"
    - "保守≠传统"
  tags: [counter-example, general-re, insurance, underwriting-discipline, culture]

- id: ce12
  title: 增长可能摧毁价值
  type: counter-example
  source_chapter: 1992年信
  source_quote: |
    "Similarly, business growth, per se, tells us little about value. It's true that growth often has a positive impact on value, sometimes one of spectacular proportions. But such an effect is far from certain. For example, investors have regularly poured money into the domestic airline business to finance profitless (or worse) growth. For these investors, it would have been far better if Orville had failed to get off the ground at Kitty Hawk: The more the industry has grown, the worse the disaster for owners."
    "Growth benefits investors only when the business in point can invest at incremental returns that are enticing — in other words, only when each dollar used to finance the growth creates over a dollar of long-term market value. In the case of a low-return business requiring incremental funds, growth hurts the investor."
    "The worst business to own is one that must, or will, do the opposite — that is, consistently employ ever-greater amounts of capital at very low rates of return."
  failure_mode: |
    将"增长"等同于"价值创造"。实际上，如果每投入1美元只能创造不到1美元的市场价值，增长越快，价值摧毁越严重。
    航空业是典型：行业规模越大，股东亏得越多。
  mechanism: |
    增长需要资本投入。如果资本回报率低于资本成本，增长 = 价值摧毁。
    在商品化行业中，竞争性资本投入互相抵消——"看游行时踮起脚尖"的困境。
    低回报企业如果还要留存利润进行再投资，结果比分红更糟。
  warning_signs:
    - 企业收入增长但资本回报率持续低于资本成本
    - 增长需要持续大量的资本投入
    - 行业内所有玩家都在扩张
    - 管理层以收入增长而非盈利能力为目标
  bound_to:
    - "经济商誉/护城河识别"
    - "内在价值评估"
    - "所有者收益"
    - "做生意不做股票"
  tags: [counter-example, growth-destroys-value, airlines, capital-allocation, ROIC]

- id: ce13
  title: 高价回购 — 花一块一买一块钱
  type: counter-example
  source_chapter: 1999年信 / 2011年信 / 2018年信
  source_quote: |
    "The continuing shareholder is penalized by repurchases above intrinsic value. Buying dollar bills for $1.10 is not good business for those who stick around."
    "The first law of capital allocation — whether the money is slated for acquisitions or share repurchases — is that what is smart at one price is dumb at another."
    "It is puzzling, therefore, that corporate repurchase announcements almost never refer to a price above which repurchases will be eschewed."
  failure_mode: |
    管理层在股价高于内在价值时回购股票，以"支撑股价"或"抵消期权稀释"为名，实质上在损害留存股东的利益。
    回购公告几乎从不设定价格上限——如果是买外部企业，价格一定会是考虑因素。
  mechanism: |
    CEO天然对自己的企业持乐观态度——"永远相信自己的股票是便宜的"。
    为了满足期权行权需要而回购，形成"高买低卖"的荒谬循环。
    分析师和董事会很少质疑回购价格——"只有童话里的皇帝才会被告知他没穿衣服"。
  warning_signs:
    - 回购公告不设价格上限
    - 回购动机是"支撑股价"而非"价值投资"
    - 在市盈率远高于历史平均水平时回购
    - 用回购来抵消期权稀释
  bound_to:
    - "买入价格决定一切"
    - "资本配置第一法则"
    - "保守≠传统"
  tags: [counter-example, share-repurchase, capital-allocation, intrinsic-value]

- id: ce14
  title: ConocoPhillips — 在商品价格顶峰买入
  type: counter-example
  source_chapter: 2008年信
  source_quote: |
    "I told you in an earlier part of this report that last year I made a major mistake of commission (and maybe more; this one sticks out). Without urging from Charlie or anyone else, I bought a large amount of ConocoPhillips stock when oil and gas prices were near their peak. I in no way anticipated the dramatic fall in energy prices that occurred in the last half of the year. I still believe the odds are good that oil sells far higher in the future than the current $40-$50 price. But so far I have been dead wrong. Even if prices should rise, moreover, the terrible timing of my purchase has cost Berkshire several billion dollars."
  failure_mode: |
    在石油和天然气价格接近顶峰时大量买入ConocoPhillips股票——典型的"行动偏差"错误（mistake of commission）。
    即使对长期方向的判断可能是对的，买入时机的错误已经造成了数十亿美元的损失。
  mechanism: |
    商品价格的短期波动可以完全压倒长期基本面分析。
    "行动偏差"——不受任何人怂恿就做出大额买入决策——说明即使是最理性的投资者也可能在周期高点被乐观情绪感染。
    时机的代价可以大到让方向正确的判断变得无关紧要。
  warning_signs:
    - 在商品价格接近历史高点时大量买入
    - 买入决策基于"价格还会更高"的预测
    - 大额集中持仓于周期性行业
  bound_to:
    - "不预测市场"
    - "安全边际"
    - "买入价格决定一切"
  tags: [counter-example, conocophillips, timing-error, commodities, oil]

- id: ce15
  title: "协同效应"幻象
  type: counter-example
  source_chapter: 1975年信（Waumbec） / 1985年信 / 2000年信
  source_quote: |
    "We also made a major acquisition, Waumbec Mills, with the expectation of important synergy (a term widely used in business to explain an acquisition that otherwise makes no sense). But in the end nothing worked."
    "In striving to achieve the desired per-share number, a panting CEO and his 'helpers' will often conjure up fanciful 'synergies.' (As a director of 19 companies over the years, I've never heard 'dis-synergies' mentioned, though I've witnessed plenty of these once deals have closed.) Post mortems of acquisitions, in which reality is honestly compared to the original projections, are rare in American boardrooms."
  failure_mode: |
    用"协同效应"为收购定价辩护，但协同效应几乎总是被高估。
    投行和内部顾问总能炮制出"证明"收购合理的预测——"只有童话里的皇帝才会被告知他没穿衣服"。
    收购后的"验尸"（将实际结果与原始预测对比）在美国董事会中极其罕见。
  mechanism: |
    投行按交易规模收费，因此总有动力证明收购合理。
    CEO在收购的狂热中（"气喘吁吁"）容易接受任何正面的预测。
    负面效应（"反协同"）从未被提及，尽管交易完成后比比皆是。
    Paul Andrews（TTI创始人）正是因为知道"战略买家"会以追求"协同效应"之名拆散他辛苦建立的企业，才选择了伯克希尔。
  warning_signs:
    - 收购理由大量引用"协同效应"
    - 没有对过往收购进行"验尸"复盘
    - 投行提供的预测只含正面效应
    - 收购价格需要协同效应才能回本
  bound_to:
    - "买入价格决定一切"
    - "做生意不做股票"
    - "只与喜欢的人合作"
  tags: [counter-example, synergy, acquisition, investment-banking, confirmation-bias]

- id: ce16
  title: Waumbec收购 — "转身"策略几乎不转身
  type: counter-example
  source_chapter: 1978年信 / 1980年信 / 2015年信
  source_quote: |
    "Both our operating and investment experience cause us to conclude that 'turnarounds' seldom turn, and that the same energies and talent are much better employed in a good business purchased at a fair price than in a poor business purchased at a bargain price."
    "Can you believe that in 1975 I bought Waumbec Mills, another New England textile company? Of course, the purchase price was a 'bargain' based on the assets we received and the projected synergies with Berkshire's existing textile business. Nevertheless — surprise, surprise — Waumbec was a disaster."
  failure_mode: |
    以"便宜"的价格买入差企业（雪茄烟蒂策略），期望通过管理改善"转身"。
    但差企业之所以便宜，通常有结构性原因——"转身几乎不会转身"。
    同样的精力和才华花在好企业上，回报远高于花在差企业上。
  mechanism: |
    便宜的价格本身不是价值——"用丝绸做丝线钱包是我们能做到的最好，猪耳朵则无能为力"。
    在衰败行业中，新的问题出现的速度和旧问题被解决的速度一样快。
    资产面值的折扣不应掩盖企业经济学的根本缺陷。
  warning_signs:
    - 买入理由是"资产便宜"而非"生意好"
    - 需要管理改善才能创造价值
    - 行业处于结构性衰退
    - "协同效应"是收购理由的一部分
  bound_to:
    - "经济商誉/护城河识别"
    - "做生意不做股票"
    - "安全边际"
  tags: [counter-example, turnaround, cigar-butt, textile, value-trap]

- id: ce17
  title: CEO不可解雇 — 公司治理的系统性失败
  type: counter-example
  source_chapter: 1988年信
  source_quote: |
    "The supreme irony of business management is that it is far easier for an inadequate CEO to keep his job than it is for an inadequate subordinate."
    "At too many companies, the boss shoots the arrow of managerial performance and then hastily paints the bullseye around the spot where it lands."
    "But the CEO's boss is a Board of Directors that seldom measures itself and is infrequently held to account for substandard corporate performance."
  failure_mode: |
    无能的CEO比无能的下属更容易保住工作。CEO没有直接上级来衡量其表现，董事会很少真正履行监督职责。
    绩效标准模糊、可以被解释、可以豁免。CEO先射出绩效之箭，然后在落点匆忙画上靶心。
  mechanism: |
    董事会成员与CEO关系融洽——批评CEO被视为"社交上相当于在宴会上打嗝"。
    即使因选错CEO而被收购，董事会成员通常也能获得可观利益。
    没有逻辑标准的考核机制，不像打字员必须达到80词/分钟——"达不到就走人"。
  warning_signs:
    - CEO没有清晰的绩效衡量标准
    - 董事会从不公开批评或更换表现不佳的CEO
    - 管理层薪酬与绩效脱钩
    - 公司被收购后原董事会成员反而获利
  bound_to:
    - "吃自己的饭"
    - "只与喜欢的人合作"
    - "保守≠传统"
  tags: [counter-example, corporate-governance, CEO-performance, board-failure]

- id: ce18
  title: ABC企业衰败三因子 — 傲慢、官僚、自满
  type: counter-example
  source_chapter: 2010年信（继任者讨论）
  source_quote: |
    "My successor will need one other particular strength: the ability to fight off the ABCs of business decay, which are arrogance, bureaucracy and complacency. When these corporate cancers metastasize, even the strongest of companies can falter."
    "In their glory days, General Motors, IBM, Sears Roebuck and U.S. Steel sat atop huge industries. Their strengths seemed unassailable. But the destructive behavior I deplored above eventually led each of them to fall to depths that their CEOs and directors had not long before thought impossible."
  failure_mode: |
    即使是最强大的公司，也会被傲慢、官僚主义和自满三大"企业癌症"摧毁。
    通用汽车、IBM、西尔斯百货、美国钢铁——曾经看似不可战胜，最终都跌落到CEO和董事们认为不可能的深度。
  mechanism: |
    成功滋生傲慢——"我们能做到这一步是因为我们厉害"，忽略了运气和顺风。
    规模滋生官僚——层级增多、决策变慢、创新被压制。
    垄断/领先滋生自满——不再关注客户和竞争者。
    这三个因子相互强化，形成恶性循环。
  warning_signs:
    - 管理层开始谈论"我们的规模优势"而非"我们还需要改进什么"
    - 公司内部审批流程越来越长
    - 对竞争者的威胁嗤之以鼻
    - 官僚机构膨胀，总部人员增加
  bound_to:
    - "不活跃也是一种策略"
    - "保守≠传统"
    - "只与喜欢的人合作"
  tags: [counter-example, arrogance, bureaucracy, complacency, corporate-decay, GM, IBM]

- id: ce19
  title: 股票薪酬不是"礼物" — 费用就是费用
  type: counter-example
  source_chapter: 1992年信 / 1998年信 / 2001年信 / 2016年信 / 2018年信
  source_quote: |
    "'Stock-based compensation' is the most egregious example. The very name says it all: 'compensation.' If compensation isn't an expense, what is it? And, if real and recurring expenses don't belong in the calculation of earnings, where in the world do they belong?"
    "Wall Street analysts often play their part in this charade, too, parroting the phony, compensation-ignoring 'earnings' figures fed them by managements."
  failure_mode: |
    管理层声称股票薪酬不是"费用"——"那还能算作什么呢，股东的礼物？"
    华尔街分析师配合这个把戏，不加质疑地引用不含股票薪酬的"盈利"数据。
    结果是投资者看到的利润被系统性地高估了。
  mechanism: |
    股票薪酬稀释了现有股东的权益，本质上是用股东的财富来支付员工的报酬——这当然是费用。
    管理层有强烈的动机将其排除在费用之外：它能显著提高"报告盈利"，从而推高股价和期权价值。
    分析师可能不知情、可能害怕失去"管理层接触机会"、也可能认为"大家都在这么玩"。
  warning_signs:
    - 公司报告"调整后利润"时排除股票薪酬
    - 分析师引用的盈利数据不含股票薪酬
    - 公司大量使用期权而非现金支付薪酬
  bound_to:
    - "透视盈余"
    - "所有者收益"
    - "吃自己的饭"
  tags: [counter-example, stock-compensation, accounting, earnings-manipulation]

- id: ce20
  title: "保守不等于传统" — 投资中的认知误区
  type: counter-example
  source_chapter: 1961年信（基本原则）
  source_quote: |
    "There is nothing at all conservative, in my opinion, about speculating as to just how high a multiplier a greedy and capricious public will put on earnings."
    "You will not be right simply because a large number of people momentarily agree with you. You will not be right simply because important people agree with you."
  failure_mode: |
    将"传统做法"等同于"保守做法"——买入蓝筹股不管估值就是"保守"。
    实际上，在不管价格的情况下买入任何东西都是投机——只不过是用"大众能给出多高市盈率"来下注。
  mechanism: |
    社会认同偏误：人多的路不一定对，权威人士同意也不一定对。
    只有当你的假设正确、事实正确、推理逻辑正确时，你才会在多次交易后是对的。
    真正的保守来自知识和理性，而非从众。
  warning_signs:
    - 以"大家都在买"来证明决策合理
    - 以"蓝筹股"标签来证明估值合理
    - 将高估值归因于"新时代"而非投机
  bound_to:
    - "保守≠传统"
    - "恐惧与贪婪逆向"
    - "能力圈判断"
  tags: [counter-example, conservatism, conventional-wisdom, crowd-behavior]

- id: ce21
  title: 不用股票收购 — 放弃复利力量的零收益交易
  type: counter-example
  source_chapter: 2007年信 / 2015年信
  source_quote: |
    "Several of my subsequent errors also involved the use of Berkshire shares to purchase businesses whose earnings were destined to simply limp along. Mistakes of that kind are deadly. Trading shares of a wonderful business — which Berkshire most certainly is — for ownership of a so-so business irreparably destroys value."
    "I've yet to see an investment banker quantify this all-important math when he is presenting a stock-for-stock deal to the board of a potential acquirer."
    "You can't get rich trading a hundred-dollar bill for eight tens (even if your advisor has handed you an expensive 'fairness' opinion endorsing that swap)."
  failure_mode: |
    用自己的股票去收购 = 用1美元的内在价值换取不到1美元的内在价值。
    这是一种"不可修复地摧毁价值"的行为——被放弃的股权会在未来几十年通过复利持续增值。
  mechanism: |
    投行从不量化这个关键数学——他们关注的是"当前市场惯例溢价"（一种完全愚蠢的评估方式）或"交易是否会增厚每股收益"。
    CEO和他们的"帮手"会炮制出想象的"协同效应"来合理化交易。
    19家公司的董事生涯中从未有人提到"反协同效应"。
    正确的测试是：如果我用现金买是否也愿意？如果不愿意，就不应该用股票买。
  warning_signs:
    - 用股票而非现金进行收购
    - 投行用"市场惯例溢价"来证明价格合理
    - 交易动机是"每股收益增厚"
    - 管理层未计算放弃股权的长期复利成本
  bound_to:
    - "不用杠杆"
    - "复利思维"
    - "买入价格决定一切"
    - "做生意不做股票"
  tags: [counter-example, stock-for-stock, acquisition, compounding, investment-banking]

- id: ce22
  title: USAir投资 — 不懂行业的"便宜"优先股
  type: counter-example
  source_chapter: 1989年信 / 1994年信 / 1996年信 / 1997年信
  source_quote: |
    "We have no ability to forecast the economics of the investment banking business, the airline industry, or the paper industry."
    "In the case of our commitment to USAir, industry economics had soured before the ink dried on our check. As I've previously mentioned, it was I who happily jumped into the pool; no one pushed me."
    "the near-term reward for skill in the airline business is simply survival, not prosperity."
  failure_mode: |
    在没有能力预测行业经济的情况下投资USAir。行业经济在"墨水还没干"时就恶化了。
    航空业的短期回报只是"生存"而非"繁荣"。
  mechanism: |
    航空业是一个竞争者将"持久性自杀式行为"视为常态的行业。
    即使管理层出色（Seth Schofield被高度评价），糟糕的行业经济学也能压倒管理能力。
    好的管理层+差的行业 = 差的结果（差的管理层+好的行业可能还好）。
  warning_signs:
    - 投资于无法预测其经济学的行业
    - 行业内竞争者长期不盈利
    - 投资理由是"管理层优秀"而非"行业好"
    - 以特殊证券（优先股）而非普通股方式介入
  bound_to:
    - "能力圈判断"
    - "经济商誉/护城河识别"
    - "做生意不做股票"
  tags: [counter-example, airline, USAir, industry-economics, circle-of-competence]

- id: ce23
  title: 每股收益幻觉 — "停摆的钟也能看起来像成长股"
  type: counter-example
  source_chapter: 1979年信
  source_quote: |
    "'Earnings per share' will rise constantly on a dormant savings account or on a U.S. Savings Bond bearing a fixed rate of return simply because 'earnings' (the stated interest rate) are continuously plowed back and added to the capital base. Thus, even a 'stopped clock' can look like a growth stock if the dividend payout ratio is low."
    "The primary test of managerial economic performance is the achievement of a high earnings rate on equity capital employed (without undue leverage, accounting gimmickry, etc.) and not the achievement of consistent gains in earnings per share."
  failure_mode: |
    将"每股收益持续增长"等同于"管理绩效优秀"。实际上，只要留存利润、不分红，EPS自然增长——就像银行定期存款一样。
    关键不是EPS是否增长，而是资本回报率是否够高。
  mechanism: |
    只要利润被留存而非分配，EPS必然增长——这不代表资本被有效使用了。
    正确的衡量标准是净资产收益率（ROE），而非EPS增长率。
    如果留存收益的回报率低于市场平均，那么利润应该被分配而非留存——"每保留1美元应至少创造1美元的市场价值"。
  warning_signs:
    - 管理层以EPS增长而非ROE来展示业绩
    - 低分红率、高留存比例但资本回报率低
    - 将会计利润增长等同于经济价值创造
  bound_to:
    - "所有者收益"
    - "透视盈余"
    - "内在价值评估"
  tags: [counter-example, EPS-illusion, ROE, capital-allocation, accounting]

- id: ce24
  title: 伯克希尔纺织/基金合作的历史教训 — 情感战胜理智
  type: counter-example
  source_chapter: 1985年信 / 2015年信
  source_quote: |
    "I should be faulted for not quitting sooner."
    "I ignored Comte's advice — 'the intellect should be the servant of the heart, but not its slave' — and believed what I preferred to believe."
    "The northern textile industry is finally extinct. You need no longer panic if you hear that I've been spotted wandering around New England."
  failure_mode: |
    情感依恋导致理性判断失灵——巴菲特对纺织业有历史渊源（伯克希尔就是纺织公司起家），导致他在明显应该退出时迟迟不做决定。
    "理智应该是心灵的仆人，而不是它的奴隶"——相信了自己想相信的。
  mechanism: |
    沉没成本谬误：已经投入的资本和情感让退出变得困难。
    自我欺骗：每次"新问题"被解决后，乐观地认为转折点已到，但更多的新问题接踵而来。
    正确的决策者（250家已关闭的纺织厂老板）并没有比巴菲特更多的信息——只是更客观地处理了信息。
  warning_signs:
    - 管理层对亏损业务有情感依恋
    - 反复投入资本但看不到转折
    - "下一次一定行"的反复承诺
    - 行业内其他玩家已大规模退出
  bound_to:
    - "不活跃也是一种策略"
    - "安全边际"
    - "能力圈判断"
  tags: [counter-example, emotional-bias, sunk-cost, textile, self-deception]

- id: ce25
  title: 做决策不靠预测 — "新纪元"幻觉的代价
  type: counter-example
  source_chapter: 1959年信 / 1968年信
  source_quote: |
    "I would rather sustain the penalties resulting from over-conservatism than face the consequences of error, perhaps with permanent capital loss, resulting from the adoption of a 'New Era' philosophy where trees really do grow to the sky."
    "What is 'investing' if it is not the act of seeking value at least sufficient to justify the amount paid? Consciously paying more for a stock than its calculated value — in the hope that it can soon be sold for a still-higher price — should be labeled speculation."
  failure_mode: |
    当市场参与者普遍相信"这次不一样"（新纪元哲学），将高估值合理化。
    1959年蓝筹股高估值、1968年科技/ conglomerate泡沫、2000年互联网泡沫——每次都有人声称旧估值标准已过时。
  mechanism: |
    "树木长到天上"的信念使人们不管价格地买入——"以高价买入蓝筹股就是保守"。
    每次泡沫都有看起来合理的理由（新技术、新经济、新模式）。
    但估值的数学法则不会因为"新纪元"而改变。
  warning_signs:
    - "这次不一样"的说法广泛流行
    - 传统估值标准被嘲笑为"过时"
    - 市场参与者以"快速获利"为目标
    - 投资理由是基于"别人会出更高价格"而非企业价值
  bound_to:
    - "不预测市场"
    - "保守≠传统"
    - "内在价值评估"
    - "安全边际"
  tags: [counter-example, new-era, bubble, speculation, valuation]

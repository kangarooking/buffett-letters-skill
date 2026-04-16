# 三重验证通过的方法论单元 — 巴菲特致股东的信

> 共 20 个单元通过全部三重验证（V1跨域 / V2预测力 / V3独特性）。
> 通过率约 50%（40个去重后独立单元中20个通过），符合方法论密集型书籍的预期。

---

- id: v01
  title: 能力圈判断
  original_ids: [f01, p16, f26]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1999年信：明确能力圈定义，承认科技行业在圈外"
      - "1987年信：拒绝投资看不懂的商业模式"
      - "2000年信：互联网泡沫中坚持不投资不理解的领域"
      - "2014年信：再次强调知道边界在哪的重要性"
  V2_predictive_power:
    passed: true
    novel_question: "一个顶级AI工程师是否应该在房地产投资上运用他的自信？"
    derived_answer: "不应。AI领域的判断准确率不能迁移到房地产。能力圈由'历史判断记录'定义，而非主观自信。自信感≠能力圈。"
  V3_exclusivity:
    passed: true
    why_not_common: "常识是'只投你懂的'。巴菲特的独特贡献：(1)能力圈大小不重要，边界意识才重要 (2)用历史判断准确率而非熟悉程度定义边界 (3)公开承认自己的盲区——这不是任何聪明人都会做的事"

- id: v02
  title: 市场先生思维（含投票机vs称重机）
  original_ids: [f02, f06]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1987年信：完整引用Graham的市场先生寓言+投票机vs称重机"
      - "2017年信：再次引用称重机概念"
      - "1973-74年Washington Post投资：利用市场先生的恐慌低价买入"
  V2_predictive_power:
    passed: true
    novel_question: "市场连续上涨3个月，所有新闻都在说还要涨，该怎么做？"
    derived_answer: "市场先生变得极度乐观——这是他提供高价买入服务的时刻。你应该卖出而非买入。短期投票机亢奋，但长期称重机不会因此改变。"
  V3_exclusivity:
    passed: true
    why_not_common: "'市场为你服务而非指导你'是Graham的独特哲学贡献。多数人把市场报价当作信息而非机会。"

- id: v03
  title: 伊索三问 / 内在价值评估
  original_ids: [f03, f10, f31, f34]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "2000年信：明确提出伊索三问框架"
      - "1983年信：内在价值定义（未来现金流折现）"
      - "应用于农场、石油、债券、股票等多种资产"
  V2_predictive_power:
    passed: true
    novel_question: "NFT的内在价值是多少？"
    derived_answer: "灌木丛里没有鸟——NFT不产生任何现金流。三问框架得出内在价值为零。价格完全依赖'更大傻瓜理论'。"
  V3_exclusivity:
    passed: true
    why_not_common: "三问结构化框架≠常识。多数人用PE/PB等倍数而非现金流折现估值。'增长只是价值方程中的一个变量'也纠正了增长vs价值的错误二分法。"

- id: v04
  title: 安全边际
  original_ids: [f05, p02, p17]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1961年信：首次详细阐述安全边际概念"
      - "1962年信：安全边际+多元化=最佳组合"
      - "1985年信：回顾纺织业失败，安全边际不是万能的"
      - "Washington Post 1973年：以1/4内在价值买入——巨大的安全边际"
  V2_predictive_power:
    passed: true
    novel_question: "当估值非常不确定时，如何决定是否投资？"
    derived_answer: "加大安全边际要求。不确定性越高，买入价格必须越低。如果无法建立足够的安全边际，就不投。安全边际的大小应与不确定性成正比。"
  V3_exclusivity:
    passed: true
    why_not_common: "常识是'分散投资降低风险'。安全边际是单笔投资层面的保护——买入价远低于价值。这是Graham/Buffett的独特贡献，多数投资者只做分散而不要求单笔保护。"

- id: v05
  title: 恐惧与贪婪逆向
  original_ids: [f07, p08]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "1986年信：经典表述"
      - "1973-74年Washington Post：别人恐惧时买入"
      - "2000年互联网泡沫：别人贪婪时保持恐惧"
      - "2008年金融危机：向高盛/GE注资"
  V2_predictive_power:
    passed: true
    novel_question: "当所有专家都说某资产是'必买'时该怎么做？"
    derived_answer: "反向检查：如果人人都买，谁是卖家？如果价格已反映所有人的乐观，安全边际为零。这不是买入信号而是卖出信号。"
  V3_exclusivity:
    passed: true
    why_not_common: "这句话广为人知但几乎没人能执行——因为需要独立于群体做判断。巴菲特的独特贡献在于提供了具体的执行框架（基于内在价值而非情绪）。"

- id: v06
  title: 做生意不做股票
  original_ids: [f08, p01, p05, p11]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "1987年信：'我们是商业分析师，不是市场分析师'"
      - "2021年信：'Charlie and I are business-pickers, not stock-pickers'"
      - "1983年Owner-Related Principles：以所有者视角投资"
  V2_predictive_power:
    passed: true
    novel_question: "如何评估一只股票是否值得买？"
    derived_answer: "假设你要买整个公司——你愿意付什么价？用评估私有企业相同的标准（现金流、护城河、管理层）来评估股票。如果不愿意买整个公司，就不该买它的股票。"
  V3_exclusivity:
    passed: true
    why_not_common: "多数投资者用PE倍数和技术分析选股，而非用企业收购的标准。'买股票=买企业'虽已广为人知但实际执行率极低。"

- id: v07
  title: 资本配置第一法则（含留存收益$1测试）
  original_ids: [f09, p09, f19, p06]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "2011年信：第一法则明确表述"
      - "2016年信：回购只在低于内在价值时"
      - "1983年信：留存收益$1测试"
      - "1999年信：批评高价回购='用$1.10买$1'"
  V2_predictive_power:
    passed: true
    novel_question: "公司回购股票总是好的吗？"
    derived_answer: "不。回购只有在低于内在价值时才是好的。高于内在价值的回购='用$1.10买$1'，是对留任股东的损害。同一行为在不同价格下对错不同。"
  V3_exclusivity:
    passed: true
    why_not_common: "多数人认为回购=好。巴菲特指出价格是决定性因素——同一行为在不同价格下可能是聪明或愚蠢的。这不是常识。"

- id: v08
  title: 经济商誉 / 护城河识别
  original_ids: [f12, f13]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1983年信：经济商誉vs会计商誉的完整阐述"
      - "See's Candy：需极少资本即可增长"
      - "GEICO：成本优势作为护城河"
      - "1985年信：纺织业缺乏经济商誉"
  V2_predictive_power:
    passed: true
    novel_question: "软件公司的护城河是什么？"
    derived_answer: "网络效应和切换成本创造经济商誉——用户越多价值越高，切换成本使留存率极高。这些无形资产使软件公司能以极少额外资本增长利润，正是经济商誉的定义。"
  V3_exclusivity:
    passed: true
    why_not_common: "'经济商誉如土地不贬值反而增值'≠常识。多数人关注有形资产和PE倍数，而非无形资产创造价值的能力。"

- id: v09
  title: 透视盈余（含所有者收益/反EBITDA）
  original_ids: [f11, p27, g06, g08]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1978年信：未分配利润同样重要"
      - "1999年信：透视盈余定义"
      - "2021年Apple：享$56亿收益vs仅收$7.85亿股息"
      - "2000年信：EBITDA批评——'牙仙不会为资本支出买单'"
  V2_predictive_power:
    passed: true
    novel_question: "一家公司净利润高但资本支出也高，它真的赚钱吗？"
    derived_answer: "不一定。所有者收益=净利润+折旧摊销-维持性资本支出。如果资本支出持续大于折旧，真实盈利能力被高估。EBITDA正是这个陷阱。"
  V3_exclusivity:
    passed: true
    why_not_common: "华尔街广泛使用EBITDA但巴菲特认为它是危险指标。'折旧是真实成本（资金预付）'≠华尔街共识。透视盈余概念（未分配利润也算你的）也非常识。"

- id: v10
  title: 浮存金思维
  original_ids: [f14]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1986年信：浮存金概念引入"
      - "2000年信：浮存金经济学三要素"
      - "2017年信：浮存金成本为负——'我们因为持有钱而获得报酬'"
      - "2022年信：浮存金是伯克希尔的非凡资产"
  V2_predictive_power:
    passed: true
    novel_question: "有没有非保险行业的浮存金类比？"
    derived_answer: "有。SaaS的年付预付款、律师的retainer fee、租房押金、Amazon的negative working capital——都是'先收钱后提供服务'的模式，本质上是低成本杠杆。"
  V3_exclusivity:
    passed: true
    why_not_common: "'别人付钱让你用他们的钱'≠常识。多数人理解为'借钱投资'，但浮存金的关键在于成本——当承保盈利时成本为负，这在常识框架下是不可想象的。"

- id: v11
  title: 复利思维（含花朵绽放杂草凋零）
  original_ids: [f18, f27]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1962年信：复利表格（$10万在不同利率下的30年增长）"
      - "2022年Coca-Cola：$13亿→$250亿+年股息$7亿"
      - "2022年American Express：$13亿→$220亿"
      - "2023年信：'花朵绽放杂草凋零'——少数赢家的长期绽放"
  V2_predictive_power:
    passed: true
    novel_question: "为什么巴菲特坚持'永久持有'而不是'低买高卖'？"
    derived_answer: "因为卖出优秀企业=放弃了复利引擎。Coca-Cola的例子：持有28年的收益远超任何'高卖'策略。复利的力量需要时间——时间是优秀企业的朋友。"
  V3_exclusivity:
    passed: true
    why_not_common: "复利概念本身不独特但巴菲特的具体洞察独特：(1)高增长率必自毁（基数膨胀后派对结束）(2)'花朵绽放杂草凋零'——不需要所有投资都成功，少数赢家能创造奇迹 (3)历史22%不可持续的真实数学"

- id: v12
  title: 机构强制力
  original_ids: [f21, p23]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1981年信：首次提出机构强制力概念"
      - "1989年信：CEO无能却安然无恙——董事会不作为"
      - "2002年信：公司治理失败——董事会气氛压制异议"
      - "Dexter Shoe/General Re：自己也无法完全避免"
  V2_predictive_power:
    passed: true
    novel_question: "为什么优秀CEO也会做出愚蠢的收购决定？"
    derived_answer: "机构强制力三重驱动：(1)CEO没有直接上司，董事会很少自我衡量 (2)同行都在做似乎'安全' (3)投行有利益动机推动交易。即使理性的人也会在系统性力量下做蠢事。"
  V3_exclusivity:
    passed: true
    why_not_common: "'管理者模仿同行的愚蠢倾向'≠常识。人们通常假设CEO是理性行动的。认识到系统性力量导致非理性行为是巴菲特的独特洞察。"

- id: v13
  title: 不用杠杆 / 财务堡垒
  original_ids: [f24, p07, p14, p25]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "2017年信：伯克希尔4次37%-59%下跌——如果用了杠杆早就出局"
      - "2022年信：Munger——'一串美好的数字乘以零永远等于零'"
      - "1983年信：拒绝过度杠杆，宁可错过机会"
      - "2021年信：永远保持$300亿+现金——'不依赖陌生人的善意'"
  V2_predictive_power:
    passed: true
    novel_question: "如果你90%确定一笔投资会涨，应该加杠杆吗？"
    derived_answer: "不应。10%的失败概率×杠杆=归零。伯克希尔历史上有4次下跌37%-59%——任何一次加杠杆都足以永久出局。90%的确定性在杠杆面前毫无意义。"
  V3_exclusivity:
    passed: true
    why_not_common: "'任何正数乘以零=零'虽简单但执行极难。多数人在高确信度时都会加杠杆。巴菲特用4次实际下跌数据将其从理论警告升级为实证事实。"

- id: v14
  title: 只与喜欢和钦佩的人合作（含吃自己的饭）
  original_ids: [p12, p03]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "1987年信：'宁取100%X配好关系，也不要110%X配差关系'"
      - "1983年信：至少四位董事50%+资产在伯克希尔——吃自己的饭"
      - "1984年信：Mrs. B的收购——基于信任无需审计"
      - "2021年TTI/Paul Andrews：选择伯克希尔因为不会裁人"
  V2_predictive_power:
    passed: true
    novel_question: "两个收购机会，一个回报高但管理层有诚信问题，选哪个？"
    derived_answer: "选管理层好的那个。因为：(1)差管理层会在你最意想不到的时候伤害你 (2)你无法改变别人的品格 (3)短期回报差异远小于长期信任的价值。'吃自己的饭'是验证诚信的终极方法。"
  V3_exclusivity:
    passed: true
    why_not_common: "'宁取100%X而不要110%X'——这在商业决策中是反直觉的。多数人会为额外的10%收益忍受不愉快的关系。巴菲特的独特在于将此作为不可违反的原则。"

- id: v15
  title: 保守≠传统 / 独立思考
  original_ids: [p18, p19]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "1961年信：'你不会因为多数人同意就对，也不会因为重要人同意就对'"
      - "1965年信：'常规≠保守，非常规也不=不保守'"
      - "2017年信：十年赌局——只做一个决定就赢了"
      - "1983年信：不拆股以维持高质量股东群体"
  V2_predictive_power:
    passed: true
    novel_question: "所有专家都推荐某个投资，它是否就是保守的选择？"
    derived_answer: "不。真正的保守来自知识和理性，而非从众。'公开意见调查不能替代思考'。一个投资是否保守取决于你的分析，而非支持它的人数。"
  V3_exclusivity:
    passed: true
    why_not_common: "'常规≠保守'是反常识的。多数人认为从众=安全。巴菲特明确指出：一致性≠正确，多数人同意≠安全。"

- id: v16
  title: CEO = 首席风险官（含诺亚法则）
  original_ids: [p15, f20]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "2009年信：'CEO绝不能委托风险控制'"
      - "2022年信：'CEO将永远是首席风险官'"
      - "2001年信：诺亚法则——'预测下雨不算，造船才算'"
      - "NetJets危机：巴菲特被迫亲自接管"
  V2_predictive_power:
    passed: true
    novel_question: "公司应该设立独立的风险管理委员会吗？"
    derived_answer: "可以设，但CEO本人必须亲自理解和管理风险。委员会不能替代CEO的风险责任。'预测下雨不算，造船才算'——知道风险存在但不采取行动等于没有管理风险。"
  V3_exclusivity:
    passed: true
    why_not_common: "'CEO不可委托风险管理'≠常识。多数大公司将风险管理交给专门部门。巴菲特认为CEO必须亲力亲为。"

- id: v17
  title: 永久持有
  original_ids: [p20]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "1988年信：'我们最喜欢的持有期是永远'"
      - "1987年信：计划永久持有Cap Cities/GEICO/Washington Post"
      - "Coca-Cola 28年、American Express 28年、See's 50年"
      - "2002年信：'我们没有退出策略——我们买就是为了持有'"
  V2_predictive_power:
    passed: true
    novel_question: "什么情况下应该卖出优秀企业？"
    derived_answer: "几乎永远不卖。前提：(1)企业依然优秀 (2)管理层依然值得信任 (3)基本面没有恶化。唯一例外：极度需要资金且无其他来源，或发现更好的机会。但Coca-Cola和Amex的例子说明，持有比切换的回报更高。"
  V3_exclusivity:
    passed: true
    why_not_common: "'最好的持有期是永远'≠常识。多数投资建议强调'低买高卖'。巴菲特认为卖出优秀企业=放弃复利引擎——这个洞察来自60年的实践经验。"

- id: v18
  title: 雪茄蒂 vs 伟大企业
  original_ids: [f17]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "1967年10月信：思维转变——从纯定量到定性分析"
      - "1983年信：'我的想法35年来发生了巨大变化'"
      - "1985年信：纺织业——便宜买差企业的失败"
      - "1987年信：'用丝绸做丝线钱包是我们能做到的最好，猪耳朵则不行'"
  V2_predictive_power:
    passed: true
    novel_question: "便宜买差企业 vs 合理价格买好企业，长期哪个更好？"
    derived_answer: "后者。因为差企业消耗你的时间、注意力和资本。即使买入价格很低，差企业的管理层问题、行业衰退和资本需求会持续侵蚀你的收益。好企业的复利力量远超一次性的价格折扣。"
  V3_exclusivity:
    passed: true
    why_not_common: "虽然'买好企业'现在越来越被接受，但巴菲特从自身错误中总结的转折故事独特：他花了近20年才从格雷厄姆的雪茄蒂方法转向芒格的伟大企业方法。这个心路历程不是常识。"

- id: v19
  title: 三类投资分类法
  original_ids: [f15]
  type: framework
  V1_cross_domain:
    passed: true
    evidence:
      - "2011年信：明确三类分类（货币性/非生产性/生产性资产）"
      - "1986年信：保险投资五类分类（更早期版本）"
      - "1961年信：Generals/Workouts/Controls（合伙基金时期版本）"
  V2_predictive_power:
    passed: true
    novel_question: "黄金和比特币属于哪类？应该如何估值？"
    derived_answer: "第二类（非生产性资产）——它们不产生任何现金流。估值完全依赖'有人出更高价'的预期。按照巴菲特的三类框架，这类资产在长期竞赛中必然输给第三类（生产性资产），因为后者会持续产生更多鸟。"
  V3_exclusivity:
    passed: true
    why_not_common: "将所有投资分为三类并评估其长期竞争力的框架≠常识。多数投资者不区分资产类别的基本经济属性。"

- id: v20
  title: 不用股票收购
  original_ids: [ce08_case, p10]
  type: principle
  V1_cross_domain:
    passed: true
    evidence:
      - "2000年信：Dexter Shoe——$4.34亿股票后来值$60亿+"
      - "2016年信：'我宁愿做结肠镜检查也不愿发行伯克希尔股票'"
      - "1983年信：不发行低估的股票"
      - "General Re：272,200股发行=21.8%稀释"
  V2_predictive_power:
    passed: true
    novel_question: "用自家股票收购另一家公司，如果两家公司质量相当，这笔交易好吗？"
    derived_answer: "不好。你放弃了自家股票的复利力量。Dexter Shoe的例子：用价值$60亿的未来股权换了一个归零的业务。即使两家质量相当，你也失去了集中投资于最了解的企业的优势。"
  V3_exclusivity:
    passed: true
    why_not_common: "'用自己的股票收购=放弃未来复利力量'≠常识。多数CEO认为股票收购是'无现金'交易，不觉得有什么成本。巴菲特用Dexter Shoe的$60亿教训证明这是'保证零收益的行为'。"

# 社交货币指标系统 (SCMS)

问题：根据定性情感，如何衡量社区互动的价值，并准确判定社区的“声誉“？

*注意：这一指标综合了几种可以从跟踪数据中得出的其他指标，以及几种过程导向的指标。 内嵌脚注注解了计划在以后澄清的领域和以后解决的问题。*


## 描述

SCMS 将多渠道[社群聆听](https://blog.hubspot.com/service/social-listening)实践与一组重要分类相结合。 这些策略经过结合，可以形成系统的社区分析并提供社区战略信息，实现可衡量的业务价值。 <sup>1</sup>

**理论与起源**

社交货币或社交资本是一种社会科学理论。 它广泛研究了人类互动如何在社区中建立关系和信任。 社交货币指标系统通过衡量社区信任度、透明度、实用性、一致性和荣誉来表示社区声誉。

人际关系是社区的社会结构。 这可见于 [Levinger 关系模型](https://theadminzone.com/ams/levingers-stage-theory.1272/)和[社会渗透理论](https://psycnet.apa.org/record/1973-28661-000)。 社区成员的个人和群体认同感在互动中不断增强。 成员通过[自我表露](https://en.wikipedia.org/wiki/Self-disclosure)行为建立共同的价值观，积累信任感，鼓励合作并互利互惠。 这些互动建立了一种更强的并且可衡量的联系感。 衡量这些特征的尺度被称为社交货币。 <sup>2</sup>

**结果**

社交货币指标系统是从社区互动梳理“消防水带 (fire hose)”定性数据的方法。 这种方法的中心前提是社区成员互动会对社区产生影响。 社交货币指标系统会持续测量这些互动的情感 <sup>3</sup>。 它说明了社区成员和负责人之间的声誉和信任程度。 <sup>4</sup>


## 目标

分析社区互动中的定性评论。 得出社区的情感概况。 通过各项指标直观显示社区的现状和过去。 从持续测量中使用领先指标主动制定社区策略。 让社区成员相信他们的想法和意见能够得到重视。


## 实现

SCMS 需要收集社区评论（通信踪迹）、定义规范并对通信记录进行持续审查。 <sup>5</sup>

如下“工具”一节所述，设置您所选择的数据收集平台。 确保至少 4 个维度和 3 个通信渠道。 设置完成后，采用以下方法收集、分析和解释结果：

![社交货币指标系统流程环](images/scms-0-circle2.png)

1. **收集通信踪迹** -- 找出您的社区在其上进行交流的在线平台。 设置从主平台到 SCMS 工具的数据漏斗。 系统的关键数据是用户生成的内容。

2. **标准化通信踪迹的评估方式** -- 使用一套规范定义重要概念，作为焦点社区的“跟踪关键词”或“类别”。 在不同人阅读和标记社区情感时，术语统一规范能够确保分析的一致性。 该规范必须定期修订和增补结构。 <sup>5</sup>

3. **分析通信踪迹** -- 在 SCMS 工具中，通过规范术语标记数据分析社区情感。 如果是由团队进行标记，建议所有人定期集合讨论趋势，并确保标记使用的一致性。 如果是由人工智能算法进行标记，则需要人类团队对 AI 进行必要的监督和再训练。 <sup>5</sup>

4. **共享和呈现聚合分析** -- 在仪表板中呈现一定时间内规范术语的定量统计。 定性分析结果在这里生成易于观察的趋势仪表板。 与团队成员共享分析。 <sup>6</sup>

5. **基准、设定目标与预测未来增长** -- 利用足够数据形成基准后，理清您的社区所处的位置。 它有哪些优点和缺点？ 可以采取哪些措施让社区更健康、更稳固？ 然后形成目标明确的社区倡议并执行这些项目，对下周的社交货币指标产生影响。 <sup>6</sup>

6. **重复流程** -- 在定期评估会议上讨论数据集或收集方法的不足之处。 提出在未来弥补这些不足的方法。 将解决方案纳入系统并继续推进。 在趋势中寻求真理，在范式中汲取力量。<sup>7</sup>


### 筛选条件

1. **渠道**：按数据收集处排序。
2. **标记**：根据评论中使用的情感识别规范标记显示数据。
3. **时间**：显示数据随时间变化的趋势，并拉取特定的数据集。
4. **最具影响力评论**：按标志排序和筛选，标志可放置于数据中以突出特定的数据点并说明其重要性。
5. **AI 与人类标记**：根据标记是由程序施加还是由人类施加来进行筛选。
6. **加权货币：**根据任何一个单独选择的标准，对某些评论的“重要性”进行加权。 得出的加权视图仅为信息基于权重的重新排序。


### 可视化效果

**仪表板呈现聚合指标：**

![仪表板呈现聚合指标](images/scms-1-dashboard.png)


**示例 SCMS 工具：**左侧为原始社区评论，标记添加于右侧紧邻的列中。 右侧数据透视表以数字显示标记与其他标记组合出现的频率。

![示例 SCMS 工具](images/scms-2-tool-example.png)


**扩展评论视图：**从字段中移除“定量”，并提供阅读不同评论的最佳方式。

![扩展评论视图](images/scms-3-expanded-comment.png)


### 提供指标的工具

任何 MySQL、smart-sheet、excel 或类似 airtable 的 excel 数据表格程序都可以用于实现指标。 这些数据应足够简化以与其他数据接口交互，确保数据迁移简单、直接并可自动进行（如 Google Data Studio）。 这要求用于实现 SCMS 的系统必须支持 CSV 和其他电子表格文件，我们强烈建议使用开源程序进行实现。

完成后，使用以下数据点创建数据集：<sup>8</sup>

| 数据点           | 描述                                                                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------ |
| 输入日期          | 数据导入 SCMS 工具的日期                                                                                              |
| 评论日期          | 在原平台上发表评论的日期                                                                                                 |
| 评论文本          | 引入的定性数据。 决定您想让这些块按多大移植。 有些可能会移植一整封电子邮件，有些则会每句话断成一行。 它应该只有一种“情感”                                              |
| 数据通道          | 评论的原始数据通道                                                                                                    |
| 标记（创建于下方规范文档） | 根据统一术语规范确定待跟踪标记。 标记可分为两种： 首先，标记可以基于“主题”或人们反复表达的情感（例如，玩家门、口水战或感谢信）； 另外，基于“类别”的标记可以描述成员评论的不同社区方面（例如，事件、发布或治理）。 |
| 社交货币指标        | 在系统中奖励或扣除的社交货币。 这将直接影响数据。                                                                                    |
| 加权分数          | 决定“权重”后，可以分配一个 -3 到 +3 的系统，提供人类标记指标的加权视图（由于多种原因，AI 不会分配权重）。 这将启用“最具影响力评论”筛选条件。                               |

为术语统一规范创建第二张表，对术语进行定义。 如下所示：<sup>8</sup>

| 类别术语              | 定义                            | 何时使用                               | 何时不使用                                           |
| ----------------- | ----------------------------- | ---------------------------------- | ----------------------------------------------- |
| [自定义标记 - 主题和类别]   |                               |                                    |                                                 |
| [社区专用术语]          |                               |                                    |                                                 |
| 社交货币维度：           |                               |                                    |                                                 |
| 透明度               | 人们是否察觉和感知到和您社区的联系？            | 当他们有“话语”来指出他们为什么认为您是真实的或有个性的。      | 这和良好的客户服务或表现无关。  那是实用性。  这关系到他们是否了解您的企业形象及其认同感。 |
| 实用性               | 您的社区是否在做有用的事情或者在贡献价值？         | 提供使用术语时进行排除的参数，让人们知道什么时候不应该实现类别标记。 | 这和良好的客户服务或表现无关。  那是实用性。  这关系到他们是否了解您的企业形象及其认同感。 |
| 一致性               | 您是否具有值得信赖的历史？                 | 当他们表示使用过您的品牌，或与您有过多次互动             | 如果他们提供的评论仅仅表示您曾经有所帮助，则以实用性代替。                   |
| 荣誉                | 您的成就是否获得社区的尊重和注意？             | 从客户获得的社交货币似乎会持续一段时间，并会影响其他人的意见。    | 当他们表示以后将再次采用您时，以信任度代替，因为这是对品牌的个人信任。 荣誉表现于外部。    |
| 信任度               | 人们能否相信您的社区在未来会继续提供价值和发展？      | 当他们对您表示信任，可以在未来继续与您对话              | 当没有足够的实质性证据表明他们会作为忠实客户或社区成员继续与您合作并对您表示信任。       |
| 内部声誉 <sup>9</sup> | 人们是否强烈地相信这些事情，以至于需要对话或行动？     |                                    |                                                 |
| 外部声誉 <sup>9</sup> | 您在社区里的声誉有多少可以传递给社区外的陌生人（冷受众）？ |                                    |                                                 |

该规范由利益相关方特定社区定期填写，构成数据分析的基础。 这是最重要的部分。 没有这一部分，定性数据的主观性就不符合普遍规则：<sup>9</sup>

> “A 概念仅在 C 限制下适用于 B 人群。”


### 数据收集策略

社区成员的评论可从跟踪数据中获得。 理想情况下，SCMS 将评论文本自动导入标记工具。 跟踪数据可以从社区成员编写评论的协作平台收集，这些平台包括票证系统、代码审查、电子邮件列表、即时消息、社交媒体和论坛。

**法律和监管考量**

_销毁点_：_xx_ 月后，详细数据将被销毁。 根据 GDPR 规定，定量计算最长可保存 250 周。 超过 250 周的数据将成为无法处理但可以查看的归档数据。 用户可以协商主要统计。


## 参考资料

- [在 airtable 上的示例实现](https://airtable.com/invite/l?inviteId=inv8u49VVMtQTrfFU&inviteToken=c49b1ed3759c5cd736901fd81c9f460f86e8e9f462703c4f85a3bdd7250ca5a7)
- [在 Data Studio 中的示例实现](https://datastudio.google.com/open/1X9UdQz8FtHHmjMBpjba3pFqE55lNpwg5)（报告）
- [在 Data Studio 中的示例实现](https://datastudio.google.com/open/1Z4EJ03898lZxm2NZVULaEoLS0bYqL79A)（数据源）
- [Google 表格中的示例实现](https://drive.google.com/open?id=1zi3JE0bwfEdRdc-wQEZn8GaB7sE8IvxeSeqvVywKnXw)
- [实现文档](https://docs.google.com/document/d/1RlAedRBQbhq0oYMCB3VqdawOCZE2XT5R3teydjBZODM/edit#heading=h.8hyunaadfriq)（始于第 33 页）


## 带注解的脚注

<sup>1</sup> CHAOSS 指标一直以来用于建立标准定义，这些定义可在项目之间良好应用以支持比较。 该指标可能会在未来演变为一个项目。

<sup>2</sup> 从此描述中得出什么指标？ 可能包括：1. 社区信任，2. 透明度，3. 实用性，4. 一致性，以及 5. 荣誉

<sup>3</sup> 情感分析表明，指标 (6) 很可能是“通信情感”，定义可能需要引用常见情感分析工具，有时被称为“词袋”。

<sup>4</sup> 衡量如何向社区成员灌输信任，使他们的思想和意见得到重视，这种可能的指标 (7) 将定义一项进程，也许无法通过跟踪数据衡量。

<sup>5</sup> 开源软件的任意规范中都有相当一部分是各项目之间共有的，每个项目都可能有一套特定兴趣属于规范的一个子集。 在某些情况下，其主要兴趣可能不会出现在既定的规范组成部分中。 通常，规范和 CHAOSS 项目本身一样作为共享元数据开源，确保跨开源社区的共享理解。

<sup>6</sup> 这描述了标准规范的演变及其通过 CHAOSS 工作组和项目进程的要素，特征如上一个脚注所述。 这可能为进程指标 (8)。

<sup>7</sup> 候选进程导向指标 (9)。

<sup>8</sup> 使用开源规范编码的数据示例经过发展，将成为通过 SCMS 推进开源软件的核心组成部分。 实现将需要这些示例，作为 CHAOSS 项目的开源资产提供，并将以共享数据返回价值。

<sup>9</sup> 内部和外部声誉可能是 SCMS 产生的指标 (10) 和 (11)。 

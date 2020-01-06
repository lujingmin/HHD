# 分析世界孕产妇死亡率变换情况与原因

### 项目目的：
* 通过数据挖掘分析世界孕产妇死亡率变换情况与原因，给相关慈善关怀机构及有关部门提供相应的目标引导建议。
### 背景和意义：
* 孕妇作为社会的弱势群体，同时承担着人类传承的重任，需要得到全社会的关爱。改善孕产妇健康是国际社会于2000年通过的八个千年发展目标中的一个，孕产妇死亡率作为人群医疗健康水平的敏感指标, 其变化状况不仅反映了全民医疗健康水平, 更在一定程度上反映当地妇女儿童权益的保障情况。
* 每年约有100万儿童因为妊娠或分娩有关的并发症而失去母亲。这些儿童在其母亲死亡之后一两年内死亡的可能性更高。
* 此项研究工作有助于解决孕产妇卫生保健服务获取和质量方面的不平等问题，降低孕产妇死亡率。

### 数据来源：
* World bank
* API获取
### 项目分析
* 收集世界各国有关项目数据
* 挖掘数据故事、优化数据交互
* 利用flask实现PYTHON的数据传输
### 项目目标
* 成最小可行的交互式数据可视化产品设计，做出PRD及至少有2份成功交互且交互意义相关连（以超连结或交互达成）的交互式界面（其中至少1份含地图）的产品原型或完整产品，包括使用相关Pyecharts及/或Plotly模块等等的整合外观样式及数据科学代码实践，以及外观样式的前端CSS及Javascript库调用实践（如Bootstrap）
### 项目数据
- [在熟练医护人员护理下的分娩（占总数的百分比）](https://data.worldbank.org.cn/indicator/SH.STA.BRTC.ZS)
- [孕妇贫血患病率(%)](https://data.worldbank.org.cn/indicator/SH.PRG.ANEM)
- [接受产前护理的孕妇（百分比）](https://data.worldbank.org.cn/indicator/SH.STA.ANVC.ZS)
    - 接受产前护理的孕妇是在妊娠期因妊娠相关原因而至少经熟练的医务人员护理过一次的孕妇的百分比。
- [避孕普及率（占 15–49 岁女性的百分比）](https://data.worldbank.org.cn/indicator/SP.DYN.CONU.ZS) 
- [孕产妇死亡率（模型估计值，每10万例活产中所占比例）](https://data.worldbank.org.cn/indicator/SH.STA.MMRT)
### 结论
* 孕产妇死亡率高的国家/地区大部分属于发展中国家。据联合国数据统计，发展中国家的孕产妇死亡占全球的99%，其中超过50%的孕产妇死亡发生在非洲撒哈拉沙漠以南地区，1/3发生在南亚。在发展中地区孕产妇死亡率是每10万活产450例，而在发达国家是每10万活产9例。其中反映出各国孕产妇在获得医疗服务的机会不平等。
* 妇女在分娩前、分娩期间和分娩后没有获得所需要的照护的原因是多种多样的。在一些偏远的地区，可能是妇女无法获得专业保健，或者是妇女可获得保健服务，但保健服务的质量不高。其它的情况是妇女不能到达卫生机构。因为没有交通工具，或者是她们不能支付交通费用或医疗服务费用。同时，文化信仰或妇女社会地位低下也可阻碍孕妇获取所需的保健服务。为了改善孕产妇健康，应该在社区水平发现卫生系统的能力和质量的差距以及妨碍孕妇获取卫生服务的因素，并且扭转这一局面。
* 尽管近十年来孕妇死亡率整体呈现下降趋势,但各国各地区之间的差异也在逐渐扩大，甚至还体现在贫富人口的差异和农村、城市人口的差异。这些差异意味着孕产妇权益在受到“隐形”侵害。
### 建议
#### 政府：
* 提供全方位孕期保健服务，普及产前检查，开设孕前咨询门诊，提供生育力评估和备孕指导。
* 产后保健服务，开展产妇产后保健指导和健康检查，进行母乳喂养和产后避孕指导，建立系统规范的孕产妇管理制度和服务模式。


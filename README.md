---
Title: WFA词库说明
Version: 2.1
Update: 2018.12.28
---

# WFA词库说明
> 感谢你的使用，希望我没有做好的事，能在你手里做得更好
———— Richasy.云之幻

> 由于词库的特殊性，未来会随着游戏的更新持续更新，如果其中未包含你需要的词条，请在Github上issue一下哟~也请持续关注我的Github主页，及时更新新版本

#### 当前词库版本：V2.1
#### 最后更新时间：2018-12-28

### 简要说明
词库包含四份文件：
1. `WF_Dict` 词典表，一份相对齐全的WF中英对照表(有id,type,zh,en四个字段)
2. `WF_Sale` 交易物品表，内含绝大部分可交易物品(其中的search字段为WM专属查询码)
3. `WF_Alert` 警报奖励物品表(囊括警报中可能出现的奖励，相比词典，多了一些头盔等特殊奖励)
4. `WF_Invasion` 入侵奖励物品表(囊括入侵中可能出现的奖励，相比词典，多了亡魂、破坏者等武器部件)
5. `WF_Relic` 遗物表(其中的`reward`字段按空格区分各个奖励，下划线代表该物品的空格。奖励列表按稀有度从低到高排序)
6. `WF_Riven` 裂罅倾向表（其中的`level`表示武器的倾向性星数，而`ratio`则是其倾向系数）
7. `WF_Modifier` 由[Sduby22](https://github.com/Sduby22)提交的PR，表示突击强化类型的翻译，字段与词典表一致
___
这七份表都已被转化为json格式，当然，你要是觉得查询性能太差，也可以自行转化为Sqlite等数据库文件，只要你用的方便，查的爽，怎么做都可以，到了你手上就随便你折腾。

这六份数据表字段都很精简，只要你打开，相信不用我多介绍你也知道该怎么用了，如果你真的学过编程的话。

虽然我是免费公开这部分情报，不过我还是有一点小小的期望，如果你在构建自己的应用时用到了我的这份词库(当然，这是我的荣幸)能顺便在About里稍微提一下我的存在，我就更感到荣幸咯~

### 更新日志

* 2019-1-1: 合并来自[Sduby22](https://github.com/Sduby22)的PR，将突击类型单独提取出来做了张表，并修复`Mesa的华尔兹`的查询码
* 2018-12-28：修复塔克桑皮肤的翻译错误，新增棱晶-库狛护甲的条目
* 2018-12-27: 修正关于TITANIA的词条重复问题
* 2018-12-19: 添加了包括女枪P在内的新更新物品，遗物列表也进行了更新
* 2018-12-3: 修复词典表翻译错误(猬刺->豪猪)，交易物品表新增本次金星平原的鱼类，已分好类别
* 2018-12-1: 新增遗物表（WF_Relic）和裂罅倾向表（WF_Riven），此外，加入了金星平原这次更新的大多数物品翻译
* 2018-10-24: 日常更新，包括万圣节噩梦在内的字段更新
* 2018-10-16: 包括`谨慎射击`、`献出力量`等在内的MOD及武器更新
* 2018-10-7: 包括手枪驱逐P卡在内的奸商物品更新
* 2018-9-26: 包括龙甲P、格拉姆P、绝路P在内的累积性更新
* 2018-9-11: 包括新出的集团卡在内的累积性更新，修复一些翻译问题
* 2018-8-02: 累积性更新，增加了许多新的条目，以及对各个特殊战术警报内容的翻译、属性的字段翻译等
* 2018-5-21: 修正Nezha-金吒头盔词条、角斗士-钳制词条，新增BOSS翻译，新增相关属性词条如霰弹枪、敌人元素强化等
* 2018-5-18: 更新奥堤克光子枪-镀铜外观、XIPHOS-棱晶外观
* 2018-5-18: 适应游戏22.20的变化，新增EQUINOX晨昏头盔词条、MOD-再启动、MOD-抵消






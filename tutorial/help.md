# 常用命令速查表

!> **查询前请注意**

- 本表格仅包含对喵窝 Minecraft 服务器常见命令的介绍，具体的命令说明、操作方法等请查阅[插件帮助](space/plugins)。
- 本页大多数命令与“毛玉线圈物语”服务器共通；  
  **以下含 :smile_cat: 标记的，为喵窝特有。**
- 如无特殊说明，如果需要手持物品，均为**主手持有**。
- 部分命令收费或征税，备注为 **“收费”**。收费明细请参考 [经济规则](nyaa/economic.md)和[HEH 插件指南](space/plugins/hamsterecohelper)<sup>（经济类）</sup>。
- 对于某些命名类命令，如果名称中含有空格，需要使用反引号 ``` ` ``` 将全部内容包围。  
示例：```/nu suffix `&f宝 生 永 梦` ```

## 传送类

| 命令| 说明| 备注 |
| - | - | - |
| `/espawn`:smile_cat: | 返回喵窝默认出生点 | 当前为大神殿 |
| `/spawn`<br>`/town tp`:smile_cat: | 返回玩家设定的出生点 | |
| `/mvtp [维度代号]`:smile_cat:<br />`/goto [维度代号]`:smile_cat: |前往指定[维度](nyaa/worlds.md "也称世界")的默认出生点 ||
| `/back`:smile_cat:  | 返回上一次传送前所在位置 | 收费 |
| `/home`:smile_cat:  | 传送回家 | 收费 |
| `/home [家的名称]`:smile_cat:  | 传送回指定名称的家 | 收费 |
| `/home bed`:smile_cat: | 传送回你上一次使用过的床的位置 | 收费 |
| `/sethome`:smile_cat:  | 设置家 | 收费 |
| `/sethome [家的名称]`:smile_cat:  | 设置一个家 | 收费 |
| `/delhome [家的名称]`:smile_cat:  | 删除一个家 ||
| `/town select` | 变更出生点，村落间传送 | 初次免费，此后每次均收费 |
| `/server [服务器代号]` |前往指定的[服务器](wiki/server-network.md "查看服务器列表") | |


## 经济 / 市场类

<details>
<summary>:notebook_with_decorative_cover: 交易相关命令的多种用法</summary>

HEH 相关命令具有多种拼写方法，功能完全一致。以访问天喵商城为例：
- `/hamsterecohelper market`
- `/heh market`
- `/h m`
- `/hm`

**以下如无特殊说明，均采用最简短的用法。**

</details>
<br />

| 命令 | 说明 | 备注 |
| - | - | - |
| `/balance`<br>`/bal` | 查看现金余额 | |
| `/nb my`:smile_cat: | 查看银行存款及贷款总额 | |
| `/pay [玩家 ID] [金额]` | 转账给指定玩家 | 执行后**立即转账**，请慎用 |
| `/ptt ac` | 领取刚刚提示的PTT奖励 | |
| `/hm` | 访问天喵商城 | |
| `/hm [单价]` | 将手中物品上架到天喵商城 | 收费 |
| `/hreq [数量] [单价]` | 发起征购（手上的物品） | |
| `/hsell [数量（可选）]` | 手持征购中物品，响应征购 | |
| `/hauc [起步价] [步进价] [保留价]` | 发起拍卖，拍卖手中的物品 | “保留价”可选 |
| `/hbid [价格]` | 在拍卖中出价 | 价格**留空**或为“min”时，跟进可允许的最低价格 |
| `/hstorage` | 查看/取回暂存于系统的物品 | |
| `/hshop create sell [备注1] [备注2]` | 开设自己的出售木牌 | 执行前，对准一块空告示牌<br />“备注 1”可选，写入木牌第 3 行<br />“备注 2”可选，写入木牌第 4 行 |
| `/hshop create buy [备注1] [备注2]` | 开设收购木牌 | 同上 |
| `/hshop create lotto [单价] [备注]` | 开设抽奖木牌 | 也要对准一块空告示牌<br />“备注”可选，写入木牌第 4 行 |
| `/hshop sell [单价]` | 上架商品到你的木牌商店 | 执行前，对准自己的“出售”木牌 |
| `/hchest req` | 设置收购存储箱 | |
| `/hshop buy [单价]` | 将手中的物品添加到收购列表 | 执行前，对准自己的“收购”木牌 |
| `/hchest lotto` | 设置抽奖奖池存储箱 | |
| `/hframe set` | 设置展示框商店 | |
| `/hframe remove` | 移除展示框商店 | |
| `/hsearch [关键词] [选项:值]` | 搜索世界木牌商店中的商品 | 高级选项暂不可用 |
| `/hsearch page [页码]` | 搜索结果页翻页 | |
| `/hsellto [玩家 ID] [总价]` | 向指定玩家出售手中物品，并发送账单 | |
| `/hpay [账单 ID]` | 支付指定账单，并收货 | 收费 |
| `/hcancel [账单 ID]` | 取消指定账单 | |
| `/npc hehshop` | 创建一个NPC，替代自己售货 | 与自己样貌相同 |
| `/npc hehshop remove` | 移除自己创建的NPC | 执行前须对准自己的NPC |

<details>
<summary>木牌商店搜索选项（暂不可用）</summary>

* `i` 或 `item`：物品名称或 ID，仅搜索指定物品
* `p` 或 `player`：玩家 ID，仅搜索指定玩家
* `r` 或 `range`：搜索范围，仅搜索指定距离内有木牌的商店
* `a` 或 `advanced`：高级搜索选项：
  * `ench`：搜索包括附魔
    * `enchonly`：仅搜索附魔
    * `lore`：搜索包括描述
    * `loreonly`：仅包括描述 选项间用 `|` 并列，如 `ench|lore`

?> :heavy_check_mark: **以上参数组合范例**  
在所有木牌商店中，查找带有『经验修补』附魔的附魔书：  
`/hsearch SILK_TOUCH i:enchanted_book a:ench`

</details>


## 物品类

| 命令| 说明| 备注 |
|-|-|-|
|`/nu rename [名称]`	|重命名物品	|可使用样式代码<br />收费|
|`/hat` | 将主手中的物品作为头盔穿戴 | 可突破原版限制<br />置换头盔栏的物品（若有） |

!> 据多人报告，修复及附魔命令不再工作，因此暂时移除。

## 辅助类

**主条目：[NyaaUtils 插件指南](space/plugins/nyaautils.md)**

| 命令| 说明| 备注 |
|-|-|-|
|`/nu lp`	|切换战利品保护开关	|| 
|`/nu lp ignorevanilla`<br />`/nu lp ig` |开启战利品保护|忽略原版物品|
|`/nu lp rejectvanilla`<br />`/nu lp re` |开启战利品保护|拒绝原版物品，但按住 Shift 键仍可捡起|
|`/nu lp includevanilla`<br />`/nu lp ac`|开启战利品保护|包括原版物品|
|`/nu el`	|切换飞行动力开关	| |
|`/nu mailbox create`		|创建邮箱|执行后，右键点击要用作收件箱的箱子|
|`/nu mailbox remove`	|删除自己的邮箱	 ||
|`/nu mailbox info`	|查看自己的邮箱信息	 ||
|`/nu mailbox send [玩家 ID]` |发送手中的物品	|收费|
|`/nu mailbox sendchest [玩家 ID]`	|发送一箱物品	|执行后，右键点击此箱子；收费|
|`/nu prefix [前缀]`	|设置名称前缀	|可使用样式代码；收费|
|`/nu resetprefix`|删除名称前缀	|| 
|`/nu suffix [后缀]`	|设置名称后缀	|可使用样式代码；收费|
|`/nu resetsuffix`	|删除名称后缀	 ||
|`/nu format`	|查看可用的样式代码	 ||
|`/nu show`	|展示手中的物品	 ||
|`/nu exhibition set`	|设置物品展示框保护	 ||
|`/nu exhibition unset`	|取消物品展示框保护	 ||
| `/nu expcap store` | 查询当前自己拥有的经验值的具体数值 ||
|`/nu expcap store [经验值]`	|将指定数量的经验存储到附魔瓶里	|经验值为“all”时，存储身上所有经验|
|`/nu expcap restore [经验值]`	|从附魔瓶提取指定数量的经验	|经验值为“all”时，提取所有经验|
|`/nu sit`	|开启或关闭“席地而坐”	|仅支持台阶、楼梯、毛毯、床（在白天）|
|`/nu se sign [行数] [内容]` | 预编辑手中的告示牌 |编辑后放置，直接点击“完成”|
| `/nu realm info`:smile_cat: | 显示当前自己所在区域信息 | 包括区域名称和坐标范围 |
| `/msg [玩家 ID] [正文]` | 与指定玩家私聊 | 只有目标玩家在线时，其才会有机会看到 |
|`/mail send [玩家 ID] [正文]`	|向指定玩家发送私信 |正文加玩家ID字数限制**244字**|
|`/mail read`	|阅读新私信	 ||
|`/mail clear`	|清空私信箱	 ||
|`/nick [昵称]`:smile_cat: | 修改在主服务器的昵称 | 优先于游戏ID显示，但不影响之<br />昵称为“off”时，移除昵称 |
| `/ptt` | 查询游戏时长 | |


## 服务器状态查询

| 命令| 说明 | 备注 |
| - | - | - |
| `/list`<br>`/plist` | 列出当前在主服务器的玩家 | 昵称可覆盖游戏 ID 显示 |
| P 键 | 列出在当前服务器的玩家，并可屏蔽某人的消息 | 仅显示游戏 ID |
| `/tps` | 显示服务器近 10 秒经过的游戏刻 | 每秒 20 刻为正常 |
| `/ping` | 显示连接到服务器的延迟 | 统计近 10 秒数据 |
| `/yasui status`| 列出各维度已加载区块、实体数量 ||
| `/co i` | 进入方块变更查询模式，左键点方块、右键点箱子以查询<br>再执行一次以退出该模式 | 仅在怀疑有失窃、破坏等情况时使用 |

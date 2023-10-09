# Changelog

喵窝及毛线的更新记录。

!> **此页尚需完善。**因原 Wiki 记录遗失，且维护者精力有限，本页或未记录所有事件。

!> 除管理组公告、服务器重大变动之外，其余内容会逐步迁移至[民间事件](changelogs/unofficial-events.md)。

## 2023

### 2023-8-11 Minecraft 1.20.1

- 主服务器升级至 *Minecraft* 1.20.1。
- 毛线主世界边界拓展至半径 5800 米范围。
- 资源维度（喵窝 `EpicWorld`、毛线 `vx`）被重置。
- Ukit 已对新版两面告示牌适配。
- 经济系统变动：
  + 现在个人商店可以通过 `/hm my` 统一管理了，无需进入店面补货。但截至 10 月 8 日，玩家在喵窝仍无权使用该指令。
  + 商店界面加入“刷子”，供手动刷新。

### 2023-6-23 Minecraft 1.20.1 先行体验

服务器 `pre` 即日起开放新版本 `1.20.1` 测试。  
目前已有升级规划，现正等待现有插件完成跟进。升级将另行通告。

### 2023-6-14 nyaa.cat 域名和主页不可达

据报告，受注册局影响，`nyaa.cat` 域名被标记为 Serverhold 且不可解析。七月已恢复解析，但受近期网络攻击影响，主页、Wiki 以及游戏服务器等仍可能难以连接。\
有热心伙伴启用了临时域名 `nyaa.id` 作为备份。

### 2023-1-2 新版本，但是是小游戏

经*奈诺 `Aqua_nano`* [引荐](https://community.craft.moe/d/3501)，小游戏“[Dungeon of the Arbalist](https://www.planetminecraft.com/project/dungeon-of-the-arbalist-dungeon-crawler-zombies-game-1-50-players-realms-map-1-17-1-by-command-realm/)”现已登陆社区。可用 `1.19.3` 客户端登录 `hana.nyaacat.com` 以体验。  
<span class="nw-spoiler">这也意味着 hana 代号的用途出现了变更</span>

## 2022

### 2022 秋季

**主世界：**

- 现在幻翼被完全逐出喵窝及毛线主世界了。
- 现在灾厄巡逻队再度出没于喵窝各处。*（毛线待确认）*
- 恢复了木牌商店，目前仅支持出售，且用法有变动。

**服务器变动：**

- 10 月 18 日，玩家数据统计站点（[喵窝](https://i.nyaa.cat) \| [毛线](https://stats.craft.moe)）进行了更新，并加入实验功能“**排行榜**”（[喵窝](https://i.nyaa.cat/experiments/ranking/) \| [毛线](https://stats.craft.moe/experiments/ranking/)）。
- “[无尽地狱](legacy/inf.md)”服务器于 11 月 2 日再度开放，可经 1.16.5 客户端直接登录。

### 2022-8-11 喵、毛社区合并

- **修订了对社区的定义。**现在“NyaaCat 社区”同时囊括原喵窝、毛玉线圈物语玩家社区，而且内容不仅限于 *Minecraft*。
- 原毛玉线圈物语社区论坛（地址 `forum.craft.moe`）改名为“NyaaCat 社区论坛”，调整了版块。现在重定向至 `community.craft.moe`。
- 喵窝论坛（原地址 `bbs.nyaa.cat`）关闭。现在重定向至“NyaaCat 社区论坛”。
- 原喵窝 Wiki （地址 `wiki.nyaa.cat`）现在起接受原毛玉线圈物语社区的内容投稿，亦可从 `wiki.craft.moe` 访问了。
- 现在所有 *Minecraft* 服务器入口的标语（MOTD）统一为同时显示喵窝与毛玉线圈物语。
- 其余现有的运营策略维持不变。

--------

?> :information_source: :cat2: **以下更新仅限于喵窝。**

### 2022-5-31 “宝蓝总算摸到鱼好起来了”更新

- “天喵商城”恢复营业，但清退了所有商品。
- 现在又可自由选择出生点了，出生点选项未作变动。费用为 45 卷/次，事实上涨价了。
- 现在可以对准告示牌编辑内容了（包括既有的），而且支持多彩文字。

### 2022-3-7 Minecraft 1.18.2 升级测试

- 主服务器升级至 *Minecraft* 1.18.2。
- ~~移除了 `/back` 命令。~~
- 关闭了 `/tps` 命令对玩家的权限。
- 添加了 Ukit 插件及 `/u` 系列命令，以取代 NyaaUtils。
- 经济系统变动：
  + PTT 在线奖励恢复了 `eco`（日常档），以及新人累计在线奖励（共五档）~~（但似乎视为日常奖励分发了）~~ 。
  + 新人累计在线奖励可被**所有**玩家领取一次。
  + 现在 `/home` 等传送指令恢复了收费。
  + `/sethome` 指令收费标准微调。
  + 其余仍维持升级 1.18.1 后的状态。

### 2022-2-20 Minecraft 1.18.1 升级测试

- 主服务器已升级至 *Minecraft* 1.18.1。
  + 主世界地下已拓展；外围人迹罕至之区块被重置。
- 三个资源维度被再次重置。
- 目前除基本经济功能、PTT、牌子锁之外，所有辅助插件（命令）及NPC下线。
- 经济系统被完全重置：
  + 存量货币作废；
  + 货币单位改用“卷”；
  + `/pay` 现在收取 1% 服务费，微调了命令格式，（重新）加入了两步验证；
  + `/home` 等指令暂时免费了。
  + PTT 在线奖励仅保留了 `daily`（日常档），额度缩至 45 卷。
  + 牌子商店、天喵商城与银行关闭。


- 所有玩家的 `/spawn` 目的地重置为大神殿。
- 除大神殿以外，关闭了所有出生点。
- 现在终末之池传送门又不能回家了（改向大神殿）。
- 人工存放经验的瓶子皆已作废。

### 2022-2-19 小变动

- 移除了玩家使用 `/goto [玩家 ID]` 传送的权限。  
  作为替代，现可通过 `/tpa [玩家 ID]` 与 `/tpahere [玩家 ID]` 发出传送要约；经对方同意即可传送。
- 大神殿被打扫干净了。
- 清理了多余的月饼礼盒。
- 增设一名 NPC 以便获取空气光源。

### 2022-2-5 模组服务器第十期开放

服务器 `hana` 例行更新，仍基于 *Minecraft* 1.18.1；相比上期仅保留了“现代工业”模组。

<details>
<summary>:notebook_with_decorative_cover: 本期所需模组（点击展开）</summary>

?> :newspaper: **内容类**

| 模组 | 功能简述 | 前置模组 |
|-|-|-|
| [Applied Energistics 2](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2) | **“应用能源”**，更科学、智能地存储与运输物品，以及更多 ||
| _插件：[Wireless Terminals](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2-wireless-terminals)_ | 整合并添加无线合成、流体、接口终端等多种终端机 | “应用能源” |
| [Botania](https://botaniamod.net/) | **“植物魔法”**，蕴含大自然魔力的科技模组 ||
| [Hookshot](https://www.curseforge.com/minecraft/mc-mods/cammies-combat-tweaks) | 加入一种立体机动装置 ||
| [Modern Industrialization](https://www.curseforge.com/minecraft/mc-mods/modern-industrialization) | 引入现代工业设备 | [Indium](https://www.curseforge.com/minecraft/mc-mods/indium)<br /><sup>*为兼容Sodium所需</sup> |
| [Promenade](https://www.curseforge.com/minecraft/mc-mods/promenade) | 加入鸭子及全新生物群系 | [Dawn](https://www.curseforge.com/minecraft/mc-mods/dawn) |
| [Sky Villages](https://www.curseforge.com/minecraft/mc-mods/sky-villages-fabric) | 随机生成浮空村庄 | [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config)<br />[Cloth API](https://www.curseforge.com/minecraft/mc-mods/cloth-api) |
| The [Wild Mod](https://www.curseforge.com/minecraft/mc-mods/the-wild-mod)| 抢先体验 *Minecraft* 1.19 新内容——青蛙和循声守卫等 | |
| [Trinkets](https://www.curseforge.com/minecraft/mc-mods/the-wild-mod)| 可佩戴饰品 | |
| [When Dungeons Arise](https://www.curseforge.com/minecraft/mc-mods/when-dungeons-arise-fabric) | 随机生成神庙、宫殿、要塞、城镇，以及帆船、飞船、树屋等结构 | |


?> :wrench: **辅助类**  
此分类下的模组可独立于 Mod 服务器使用。


| 模组 | 功能简述 | 前置模组 |
|-|-|-|
| Fabric API | | |
| [Iris](https://irisshaders.net/) | 替代Optifine | [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) |
| [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) | 优化客户端的网络性能 | |
| [Lamb Dynamic Lights](https://www.curseforge.com/minecraft/mc-mods/neat) | 加入动态光源 | [ModMenu](https://www.curseforge.com/minecraft/mc-mods/modmenu) |
| [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) | 优化客户端性能 ||
| [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) | 优化光照性能 | |
| [Roughly Enough Items](https://irisshaders.net/) | 物品管理器 | [Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-forge) |


</details>

- - -

## 更早年份的更新

* [2021](changelogs/2021.md) :balloon:
* [2020](changelogs/2020.md) :butterfly:
* [2019](changelogs/2019.md) :sparkles:
* [2018](changelogs/2018.md) :sweat_drops:
* [2017](changelogs/2017.md) :rainbow:
* [2016](changelogs/2016.md) :cat:
* [2015](changelogs/2015.md) :heart:
* [2014](changelogs/2014.md) :cyclone:

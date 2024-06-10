# Changelog

喵窝及毛线的更新记录。

!> **此页尚需完善。**因原 Wiki 记录遗失，且维护者精力有限，本页或未记录所有事件。

!> 除管理组公告、服务器重大变动之外，其余内容会逐步迁移至[民间事件](changelogs/unofficial-events.md)。

## 2024

### 2024-04-22 CoreProtect 日志溢出故障

由于硬盘空间耗尽，4 月 17 日起，方块变动监听插件 CoreProtect 发生日志溢出故障，随后宕机；17～22 日的方块变动日志丢失。已对服务器进行紧急升级，现恢复监听。详见[论坛](https://community.craft.moe/d/5008)。

### 2024-04-08 Ukit 更新及其它

- Ukit 插件功能获得更新。
  + `/u mail` 邮箱功能上线，弥补了 1.18 更新以来邮箱功能的缺位。
  + `/u lock` 功能增强，主要补全了对锁定展示框内物品的展示功能。
  + 详情请参考 [Ukit 插件页面](tutorial/plugins/ukit.md)。
- Discord bot 转发项目获得更新。
  + 现在游戏内使用 `/u show` 展示物品的信息会被转发到 Discord 了。

### 2024-04-04 加入插件 FreedomChat 等

- 自服务器升级以来，有部分玩家因安装 No Chat Reports 模组，遭遇被主服务器踢出、归来后不断报告“聊天信息验证失败”错误等情况，严重影响游戏体验。管理组遂引入插件 FreedomChat，以图修复。<span class="nw-spoiler">Blame M$</span>
- 加入了 [收纳袋](https://zh.minecraft.wiki/w/%E6%94%B6%E7%BA%B3%E8%A2%8B) 的合成配方。
- 现在可通过 `/tpauto` 自动接受其他玩家的传送请求了。

### 2024-04-01 EpicWorld 重置

由于新道具试验造成较大破坏，当日资源世界（EpicWorld）被重置。资源下界、末地未受影响。

### 2024-03-10 新镶嵌机制上线

当日，喵窝启用镶嵌系统数据包。不同于 2015 年前所用插件，该数据包仅引入原版附魔和装备栏增益（但强度远超原版），所需材料皆取自自然；主要操作地点位于魔法之源·海星城。截至目前，该数据包[仍在调整之中](https://github.com/Acappellia/NyaaGems/)；已有玩家分享[先行体验报告](https://community.craft.moe/d/4837)。  
此后，陆续有一批上古装备道具被重制，可通过镶嵌废弃资材兑换而得。

### 2024-03-03 Minecraft 1.20.4

- 主服务器升级至 1.20.4。
- 此前，test（ubw）服务器已先行升级到 1.20.4。
- 此前，archive 服务器已恢复上线。
- 增加自动飞行功能，类似以前的樱花动力燃料机制，以**刷子**作为媒介，自动使用背包中的烟花火箭为飞行加速，并在手持刷子时、在物品名称处显示当前的飞行速度，且可按住 Shift 键暂停自动加速功能。

## 2023

### 2023-10-25 小游戏 Packour limbo 登陆

现在活动服务器 `act` 托管跑酷小游戏 [Packour limbo](https://www.planetminecraft.com/project/parkour-limbo-1-19-2/)，版本和主服务器现行的通用。开放时间至 11 月 19 日前后止，此后改为“无尽地狱”体验服务器。

### 2023-8-11 Minecraft 1.20.1

- 主服务器升级至 *Minecraft* 1.20.1。
- 毛线主世界边界拓展至半径 5800 米范围。
- 资源维度（喵窝 `EpicWorld`、毛线 `vx`）被重置。
- Ukit 已对新版两面告示牌适配。
- 经济系统变动：
  + 现在个人商店可以通过 `/hm my` 统一管理了，无需进入店面补货。~~但截至 10 月 8 日，玩家在喵窝仍无权使用该指令。~~（现已修复）
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


- - -

## 更早年份的更新

* [2022](changelogs/2021.md) :blossom:
* [2021](changelogs/2021.md) :balloon:
* [2020](changelogs/2020.md) :butterfly:
* [2019](changelogs/2019.md) :sparkles:
* [2018](changelogs/2018.md) :sweat_drops:
* [2017](changelogs/2017.md) :rainbow:
* [2016](changelogs/2016.md) :cat:
* [2015](changelogs/2015.md) :heart:
* [2014](changelogs/2014.md) :cyclone:

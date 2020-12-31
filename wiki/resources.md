# 推荐资源

这里是推荐使用的各类游戏资源。  
请注意这里仅仅是推荐，我们的服务器对客户端**除了版本对应，没有任何要求**。相比于原版，使用这些整合包/资源包可以让您获得更好的游戏体验。但如果您有自己的选择，请尽管按照自己的喜好来游戏。

这里提供的版本可能不是最新的，最新版本请参考各资源官网。

如果因为一些原因需要适用于旧版的资源，戳 [这里](wiki/resources/old)。

## 整合包（客户端）

### Minecraft 1.16.4

?> :green_heart: 【2020.11.30更新】**Fabric 不完全整合/Auth Me/optifine/锂钠磷/投影mod教程**

由 *Kinomotomoyo* 整理，需解压后手动添加到游戏。  
[原帖与下载地址](https://bbs.craft.moe/d/1923-20201130minecraft-1164-fabric-auth-meoptifinemod)

<details>
<summary>默认包含模组</summary>

- Antighost ——反幽灵方块【快捷键G或者输入指令/ghost】
- AppleSkin ——饥饿显示
- Auth Me ——游戏内重登账号(不用退游戏和启动器，然后再开启动器进游戏那么麻烦了  
<span class="nw-spoiler">其实电脑足够快的话，稍微等等也无妨</span>
-  AutoReconnector-Fabric ——自动断线重连  
_感谢派兹，辛苦更新_
- BlockMeterFabric ——距离度量
- Color Unchained ——将彩色/特殊字体输入书(编写彩色书籍
- Controlling ——键位设置
- Giselbaer's Durability Viewer ——耐久显示
- [Easiervillagertrading](#easier-trading) ——批量与村民交易
- **Fabric API**
- Hwyla ——方块信息显示
- Inventory Profiles ——R键整理【修改配置界面快捷键R+C】
- Item Scroller ——【修改配置界面快捷键I+C】超级好用的物品批量移动！！！（交易必备）
- Litematica ——投影【修改配置界面快捷键M+C】
- **MaLiLib** ——<span class="nw-explain" title="Item Scroller、Litematica、MiniHUD、Tweakeroo">部分模组</span>的基础API
- MiniHUD ——信息显示【修改配置界面快捷键H+C】
- Mod Menu ——模组信息列表
- **Optifabric**
  + OptiFine ——高清修复
  + **此二者必须同时安装！**和 Lithium、Sodium 互不兼容！
- Orderly ——生命值显示
- Phosphor(磷) ——计算优化
- Roughly Enough Items (REI) ——方块信息
- ShulkerBoxTooltip ——潜影盒内容快捷显示
- Tooltipfix ——信息大小自适应调整
- Tweakeroo ——万能工具箱【修改配置界面快捷键X+C】
- VoxelMap ——小地图

</details>
<br />

<details>
<summary>可选模组</summary>

- BBOR ——特殊建筑区块范围显示
- EnchantedToolTips ——附魔描述
- Lithium(锂) ——照明优化
- Mouse Wheelie ——鼠标功能扩展(貌似和Item Scroller有冲突？看你习惯用哪个吧)
- NBT Tooltip ——物品 NBT 标签信息显示
- Replay ——录像重放
- [Sodium(钠)](#sodium) ——渲染优化
- WorldEdit
- WorldEdit CUI

</details>
<br />

?> :blue_heart: 【2020.11.04更新】**Fabric 简单整合**

由 *Atom202SLL* 整理，可直接被 MultiMC 导入。  
[原帖与下载地址](https://bbs.craft.moe/d/1923-20201130minecraft-1164-fabric-auth-meoptifinemod)

<details>
<summary>Mod 一览</summary>

- Appleskin
- Carpet
- Carpet-extra
- Durability Viewer
- **Fabric API**
- Hwyla
- Inventory Profiles
- MASA 五件套，包含：
  + Item Scroller
  + Litematica
  + **MaLiLib**
  + MiniHUD
  + Tweakeroo
- Mod Menu
- Optifabric
  + Optifine
- Replaymod
- Roughly Enough Items
- Shulker Box Tooltip
- Voxelmap
- WorldEdit
- WorldEdit CUI

</details>

!> **已知问题**

当前，如果启用 Optifine 并尝试进入喵窝服务器，**会出现客户端崩溃的情况。**  
目前可用的临时解决方案（选择其一）：

- 禁用 Optifine。
- 关闭服务器资源包，并使用[离线资源包](wiki/faq#服务器资源包加载缓慢，怎么办？)。

!> 关于官方启动器使用 MultiMC 整合包

如果你正在、且只能使用官方启动器，你必须先安装 Fabric 框架，并配合 **Fabric API** 模组使用（以上整合包均已包含 Fabric API）。

1. 首先[下载](https://fabricmc.net/use/) Fabric 框架安装器，之后双击安装。
1. 从整合包内的`.minecraft/mods`目录，提取所有文件，放到官方启动器所存储的<span class="nw-explain" title="对于Windows，其位于 C:\Users\<用户名>\AppData\Roaming\.minecraft">游戏目录</span>下的`mods`目录中。
1. 整合包可能禁用了 Optifine / OptiFabric，如需使用它们，重命名将`.disabled`后缀删除。如果需要 [Sodium](#sodium)，请勿重命名。
1. （可选）从 [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-api) 下载最新版 Fabric API。
  <!-- - **注意：1.15.2 整合包**内的 Fabric API 不要更新。 -->
1. 开始游戏吧:-P

## 模组（Mod）

模组能提供许多好用的功能甚至改变整个游戏。

### [Fabric] AutoReconnector

如果在挂机时中途掉线，借助这个 Mod，就可以自动重连了。

支持 1.14.4 / 1.15.\* / 1.16.\* 。

[论坛讨论 / 下载](https://bbs.craft.moe/d/1316)

### [Fabric] EasierVillagerTrading :id=easier-trading

可以大幅提升与村民等 NPC 交易的效率，对于喵窝等重度依赖交易 NPC 的服务器非常有帮助。

* 单击一种交易内容即可立即交易一次
* 按住 Shift 键单击一种交易内容即可将背包中的物品全部用于交易
* 按住 Ctrl 键单击一种交易内容即可只准备交易（就像原版一样）

[CurseForge 介绍 / 下载](https://www.curseforge.com/minecraft/mc-mods/easiervillagertrading)

### [Fabric] Sodium :id=sodium

可以大幅提升游玩时的**帧率**，尤其在核芯（集成）显卡、入门独显平台上。<br />
当前仅支持 1.16.1 及以上版本，以及 Fabric 框架。

- MCBBS 上的[介绍](https://www.mcbbs.net/thread-1079347-1-1.html)
- [GitHub 下载地址](https://github.com/jellysquid3/sodium-fabric/releases)
- [CurseForge 下载地址](https://www.curseforge.com/minecraft/mc-mods/sodium/files)
  + [Gitee镜像](https://gitee.com/mirrors_trending/sodium-fabric/tree/1.16.x%2Fstable/)，可供自行编译（选择 `1.16.x/Stable` 分支，编译后即适配 1.16.4）

!> **Optifine 和 Sodium 不兼容。** 使用本插件前，须先移除/禁用 OptiFabric 和 Optifine，反之亦然。  
除提高性能以外，其并不能取代 Optifine（包括光影、披风、资源包的额外特性等）。

### [Forge] JourneyMap

VoxelMap 的替代品，其优势是：
1. 界面简洁美观
1. 界面风格（皮肤）可更改
1. 白天/黑夜地图可随时选择
1. 可测绘地形，生成地形图（Topographic Map）
1. 可生成 PNG 格式的世界地图
1. 拥有更多选项

当前支持最高至 1.15.2 的游戏版本，仅支持 Forge 框架。

- [CurseForge 下载地址](https://minecraft.curseforge.com/projects/journeymap/files)
- MCBBS 上的[介绍](https://www.mcbbs.net/forum.php?mod=viewthread&tid=612917)

## 资源包（材质）

-   [Sphax PureBDCraft](https://bdcraft.net/purebdcraft-minecraft) —— 俗称“五边形”
-   [ShortBread](http://www.planetminecraft.com/texture_pack/shortbread--/)
-   [ChromaHills](http://www.chromahills.com/)
-   [Soartex Fanver](http://soartex.net/downloads/)
-   [R3D Realism](http://www.minecraftforum.net/topic/1182714-)
- [Faithful](https://faithful.team) —— 原版材质高清重制
- [ZigZag](https://zigzagpack.com/) —— 敲可爱，Mojang还进行过[采访](https://www.mcbbs.net/thread-1075295-1-1.html)

## 光影包

- [BSL Shaders](https://bitslablab.com/bslshaders/)
- [SEUS (Sonic Ether’s Unbelievable Shaders)](https://www.sonicether.com/seus/)
- [Chocapic13' Shaders](https://www.curseforge.com/minecraft/customization/chocapic13-shaders)

## 皮肤

-   [幻想乡人物皮肤](http://pan.baidu.com/s/1mgyq8mW)  by setomu@yuly
-   [Love Live! 皮肤合集](https://www.mcbbs.net/thread-315887-1-1.html)  by Arasd_Yu
- 还有其它的吗？[在这里挑选！](https://www.minecraftskins.com/)

<!--
## Minecraft 正版许可

由于在升级成为正版服务器的时候仍有一些玩家还没有购买正版，因此我们决定向没有收入能力的学生玩家免费提供正版许可。

您必须是本服的玩家，能够证明自己是学生并且还没有购买正版，请邮件或在社群 / QQ 群联系管理组获得正版许可。

依据 MinecraftEdu 的协议， 您如果希望获得一份由喵窝提供的 GiftCode，您需要同意以下协议：

-   您保证您目前是一名在读学生。
-   您保证您使用由此 GiftCode 激活的 Minecraft 账号是以学习为目的。
-   您保证您不会以任何方式再次出售（或者赠送）此 GiftCode 和此 GiftCode 激活的账号。
-->
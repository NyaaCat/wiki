# 推荐资源

这里是推荐使用的各类游戏资源。

请注意这里仅仅是推荐，我们的服务器对客户端**除了版本对应，没有任何要求**。使用这些整合包/资源包可以让您获得更好的游戏体验。但如果您有自己的选择，请尽管按照自己的喜好来游戏。

这里提供的版本可能不是最新的，最新版本请参考各资源官网。

如果因为一些原因需要适用于旧版的资源，戳 [这里](wiki/resources/old)。

## 整合包（客户端）

### Minecraft 1.16.4

**1.16.4 Fabric 简单整合** *by Atom202SLL* （适用于 MultiMC）  
体验上基本与 1.15.2 整合包无异，并加回了 OptiFine。

详情请见 [相关帖子](https://bbs.craft.moe/d/2079-multimcminecraft-116-fabric/5)。

<details>
<summary>Mod 一览</summary>
<img alt=1-16-4 src=https://i.loli.net/2020/09/17/6oyE5LACUXFiT4t.png>
</details>

#### 已知问题

如果进入喵窝服务器并启用服务器资源包，**会出现客户端崩溃的情况。**  
目前可用的临时解决方案（选择其一）：

- 禁用 Optifine。
- 关闭服务器资源包，并使用[离线资源包](wiki/faq#服务器资源包加载缓慢，怎么办？)。

#### 关于官方启动器使用整合包

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
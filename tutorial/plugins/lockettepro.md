# LockettePro 插件指南

LockettePro 是一个帮助玩家在多人服务器保护自己财产的插件。

挖到钻石 / 绿宝石怎么办？辛苦撸死只黑化掉了魔矿怎么办？当然您可以~~给卷卷交 450~~ 挖一个很秘密的洞放上箱子储存您的财产，但这并不是正确地保存财产的方法。如果有地精玩家挖到了您的箱子，财产仍然会有丢失之虞。正确的方法是，使用 LockettePro 插件。

目前，LockettePro 支持传统的木牌锁和 PDC 锁（限容器）两种模式。

?> :information_source: 原版的 Lockette 与 LockettePro（前者的衍生版本）均已年久失修，因此目前喵窝使用的是自己维护的版本。如果希望查看源代码、反馈技术问题、参与贡献等，请戳 [这里](https://github.com/NyaaCat/LockettePro)。

# 木牌锁模式（传统模式）

## 快速入门

用告示牌右键单击没有人声明主权的箱子，然后就可以将木箱设置为私有，**其它人无法以任何方式打开箱子或者提取箱子内的物品**，如下图所示。

![基本的锁箱](../../assets/images/plugins/lockettepro/basic.jpg)  
<small>一个被玩家 `tcdw` 声明拥有主权的箱子。</small>

如果**不希望**上锁，可以按住 Shift 键放置木牌，然后编写其它东西。

如果告示牌使用的位置**有水**，则无法自动锁定。这时，需要按住 Shift 键放置木牌，然后手动编辑告示牌方可上锁：

* 告示牌第一行：`[Private]`

### 我想把这个箱子分享给更多的玩家

您可以将箱子设置为多人有权限使用，但需要注意的是仍然**只有您可以破坏这个箱子**：

* 右键需要分享的箱子的锁箱木牌
* 执行命令 `/lock [行号] [内容]`。行号的有效范围介于 3 - 4 之间，内容可以是：
  * 玩家 ID
  * `[Everyone]`（共享给所有人）
  * 自定义文本（支持格式符号，但不支持空格）

如下图所示。

![共享给一位玩家的箱子](../../assets/images/plugins/lockettepro/multi_user.jpg)  
<small>一个被玩家 `tcdw` 声明拥有主权、`Leon_Xu` 可以打开的箱子。</small>

### 但是我觉得分享给两名玩家不够，怎么办？

用告示牌右键单击由您声明占有的箱子外面的其它位置，即可添加「更多用户」木牌。然后，用 `/lock` 命令向「更多用户」木牌添加要共享的玩家 ID；在这里，行号的有效范围介于 2 - 4 之间。

![共享给多位玩家的箱子](../../assets/images/plugins/lockettepro/many_user.jpg)  
<small>一个被玩家 `tcdw` 声明拥有主权、4 名指定玩家可以打开的箱子。</small>

**「更多用户」木牌的粘贴数量没有上限，只要确保他们贴在箱子上面即可。** 这意味着通过适当的摆放，您最多可以给一个箱子设置 17 个共享的玩家 ID。

### 我能锁其它的东西么？

您可以利用这个插件锁住门、贵重的方块和其它一切包含存储空间的方块（**潜影盒**、**发射器**和**投掷器**除外）。

用告示牌右键单击可以了。


![目前可以被上锁的方块](../../assets/images/plugins/lockettepro/blocks.jpg)  
<small>目前可以被上锁的方块。</small>

对于门来说，您还可以设置开启时间。通过 `/lock` 命令在木牌上添加一行：

```none
[timer:时长]
```

即可。其中，时长的单位是秒，您可以自行指定数值。

例如，`[timer:2]` 将会导致在门被开启 2 秒后自己关闭。

## 技巧

#### 一种隐藏锁门木牌的方法

在门下方的方块旁，挂牌锁定，然后以墙壁和地板遮蔽之。如下图：
 
![步骤 2](../../assets/images/plugins/lockettepro/hide_step2.jpg)  
![步骤 3](../../assets/images/plugins/lockettepro/hide_step3.jpg)  


### 其它

* 该插件还可以间接实现：
  * 点击一次，即可完整打开两个门扇的门。
  * 徒手打开铁门。

### 嗯，我想保护展示框里的东西，怎么办呢？

[这个功能 Ukit 做了。](tutorial/plugins/ukit.md#lock)

# PDC 锁模式

PDC 锁是一种利用 PaperMC PersistentDataContainer API 对容器方块进行隐形上锁的模式，可以实现对容器权限的高级管理。

PDC 锁仅适用于容器，对于各类门和普通方块的上锁，仍适用上文的普通木牌锁模式。

目前适用 PDC 锁的容器包括：熔炉、烟熏炉、高炉、炼药台、箱子、木桶、潜影盒、发射器、投掷器、合成器、漏斗、陷阱箱。

!>由于服务端版本的问题，截至本文撰写时，暂时无法测试铜箱子是否支持 PDC 锁。

注意：**任何对 PDC 锁的操作均需要将准星对准容器。**

|指令|说明|
|--|--|
|/lock on|为当前容器配置 PDC 锁，并将自己设置为所有者（owner）|
|/lock off|撤销当前容器的 PDC 锁|
|/lock permission|配置当前容器的 PDC 锁权限|
|/lock rename|配置当前 PDC 锁容器的名称|
|/lock clone|获取批量复制当前容器 PDC 锁配置的道具|
|/lock info|查看当前容器的 PDC 锁信息|

## 启用/停用 PDC 锁

### 启用 PDC 锁： `/lock on`

该指令为所指的容器配置 PDC 锁，并将命令发起者配置为所有者（owner）。

配置完成后，即使容器所有者也不能直接打掉这个容器，必须首先停用 PDC 锁。

### 停用 PDC 锁： `/lock off`

停用 PDC 锁的同时将丢弃已有的所有配置。

## 配置 PDC 锁权限：`/lock permission <mode>:<subject>`

编辑容器 PDC 锁的权限，你必须是容器的所有者才能使用该指令。

权限（mode）列表如下：

|权限|说明|
|--|--|
|ro|只读，只能查看、而不能拿取容器中的内容|
|rw|读写，可以查看，也可以拿取容器中的内容|
|xx|所有者，拥有容器的所有权限，包括编辑权限和停用 PDC 锁|
|--|用于移除指定对象的权限|

当玩家不在权限列表中时，**不能对容器进行任何操作**，包括打开容器进行查看。

当为同一玩家多次指定权限时，仅级别最高的权限生效，如：玩家原有 ro 权限，为其配置 xx 权限，则在赋予 xx 权限的同时自动撤销 ro 权限。

?> :information_source: 为防止丢失容器的所有权，拥有容器所有者权限的玩家不能通过本命令移除（--）或降级（ro、rw）自己的权限。

!> 所有者权限（xx）可以撤销其他用户的权限，并可取消箱子的 PDC 锁，赋予其他玩家前请慎重考虑。

对象（subject）列表如下：

|对象|说明|
|--|--|
|玩家ID|指定的玩家 ID，大小写不敏感，如当前玩家在线，自动匹配为 ID#UUID 的格式|
|玩家UUID|指定的玩家 UUID，需注意应使用长 UUID 格式，如：069a79f4-44e9-4726-a5be-fca90e38aaf5|
|tag|标签对象，如 [everyone] 代指任意玩家，也可以是权限组标签、计分板队伍标签等|
|#entity|实体 ID，如：#hopper 表示漏斗可以对容器进行操作|
|[g:权限组名称]|预定义的一组玩家，具体见后|

!> 不能将所有者（xx）权限赋予权限组。

将权限（mode）与对象（subject）进行组合，即可对容器权限进行灵活配置，例如：

|示例指令|说明|
|--|--|
|/lock permission ro:Notch|为 ID 为 Notch 的玩家赋予容器的只读权限|
|/lock permission rw:f9a159cb-9ab0-46b5-b7e0-7e07997c1b68|为 UUID 为 069a79f4-44e9-4726-a5be-fca90e38aaf5 的玩家赋予容器的读写权限|
|/lock permission ro:[everyone]|允许任意玩家只读查看当前容器|
|/lock permission rw:#hopper|允许漏斗放入、取出容器中的物品|
|/lock permission rw:[g:myteam]|为 myteam 权限组赋予容器的读写权限|
|/lock permission xx:Notch|将 ID 为 Notch 的玩家配置为容器的所有者|
|/lock permission --:Notch|将 ID 为 Notch 的玩家从权限列表中移除|

## PDC 权限组：`/lock group`

权限组用于管理一个玩家列表，可减少多个容器批量配置权限时的工作量，并方便按组对权限进行分配。

用法示例：将聚落成员加入权限组，然后为聚落中的容器分配该权限组，聚落成员即可对特定容器进行指定权限的存取操作，而不必重复撰写大量的 PDC 条目或木牌锁来达到相同的目的。

目前，每位玩家最多可以创建 1 个权限组，且其名称在整个服务器中具有唯一性，只有权限组的创建者可以对其进行修改、删除等操作。

相关指令如下：

|指令|说明|
|--|--|
|/lock group create <groupname>|创建名称为 groupname 的权限组|
|/lock group delete <groupname>|删除名称为 groupname 的权限组|
|/lock group add <groupname> <subject>|将对象 subject 添加到权限组 groupname 中|
|/lock group remove <groupname> <subject>|将对象 subject 从权限组 groupname 中移除|
|/lock group info <groupname>|显示权限组 groupname 的详细信息|
|/lock group list|显示由当前玩家创建的权限组列表|

?> :information_source: 有关对象（subject）的说明，请参考上一章节《配置 PDC 锁权限》中的相关内容。

配合 `/lock permission` 指令，对按组赋权的操作进行举例说明：

|示例指令|说明|
|--|--|
|/lock group create ourteam|创建一个名为 ourteam 的权限组|
|/lock group add ourteam Notch|将玩家 Notch 加入到权限组 ourteam 中|
|/lock group add ourteam 069a79f4-44e9-4726-a5be-fca90e38aaf5|将 UUID 为 069a79f4-44e9-4726-a5be-fca90e38aaf5 的玩家加入到权限组 ourteam 中|
|/lock group remove ourteam Notch|将玩家 Notch 从权限组 ourtime 中移除|
|/lock permission rw:[g:ourteam]|指定权限组 ourteam 中的玩家等拥有当前所指向容器的读写权限|

### PDC 权限复制工具：`/lock clone`

指向启用 PDC 锁的容器使用本指令，可获得一个权限复制工具（物品样式为羽毛），可快速为其他容器套用本容器的 PDC 锁配置。

使用复制工具时，容器不需要事先启用 PDC 锁。

使用复制工具时，使用者必须与复制工具的创建者一致（只能对自己的容器使用自己的复制工具）。

### PDC 锁容器改名：`/lock rename`

指向启用 PDC 锁的容器使用本指令，可修改该容器的名称。

修改后的容器名称不会因 PDC 锁撤销而复原。

?> :information_source: 要改回默认名称，可以取消 PDC 锁后，拿着物品形式的容器去铁砧上改名为“ ”（一个英文空格），开销为 1 级经验。

### PDC 锁容器信息：`/lock info`

查看目前指向的容器的 PDC 锁信息，包括名称、持有 xx、rw、ro 权限的用户列表等。
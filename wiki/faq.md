# FAQ

*最后更新：{docsify-updated}*

此页面是对《[新人指南](nyaa/beginners-guide)》的补充——关于新人的所有问题，应该皆已解答；如果还有旁的，为了保持《指南》整洁，统一在此答复。  
没有找到所需的答案？先对自己的问题分类——它是属于[Minecraft 本身](https://wiki.biligame.com/mc)的，还是喵窝里各种新奇玩意的？不妨先在本页和整个 Wiki 内尝试搜索；如果 Wiki 上也没有，那就试着在社群里询问吧。

总之，抽出一定时间仔细阅读 Wiki，后面只会节省更多时间！

## 初来者相关 :id=newcomers

一些常用问题已汇总到以下表格了。  
更多方面的问题：
- [插件和命令](tutorial/help.md)
- 这个世界的[神奇物品](#items)
- 这个世界的[奇特现象](#nyaa-world)
- 服务器[资源包](#server-resourcepack-dl)
- 服务器[连接问题](#connection)
- [其它问题](#other-newcomers)

| 常见疑问 | 直达传送门 |
|-|-|
| 喵窝服务器对客户端有特别的要求吗？ | :point_right:[准备好客户端](nyaa/beginners-guide#prepare-client) |
| 第一次加入服务器如何注册？以后如何登录？ | :point_right:[申请白名单](wiki/whitelist-application.md)，并准备好客户端 |
| 我是新玩家，我应该去哪生存？ | :point_right:[白手起家](nyaa/beginners-guide#start-from-scratch) |
| 我该怎么赚钱？ | :point_right:[每个节操都要精打细算](nyaa/beginners-guide#earning) |
| 如何去其它维度（世界）？ | :point_right:[维度列表](nyaa/worlds)<br />要摆传送门请往下翻\~ |
| 如何在游戏聊天内分享一条命令？ | 命令前面加上`&f`。 |
| 如何使用锁箱插件？ | :point_right:[牌子锁指南](space/plugins/lockettepro.md) |
| 如何设置名称前/后缀？ | :point_right:[NyaaUtils帮助](space/plugins/nyaautils.md#prefix-suffix) |
| 如何创建邮箱？ | :point_right:[NyaaUtils帮助](space/plugins/nyaautils.md#mailbox) |

### 关于物品 :id=items

?> :drooling_face: **我看商店里，那些装备道具似乎很厉害，值得买吗？**

视情况而定。对于超出原版的道具，请注意：**目前只有以下道具尚具备价值。**
1. 在描述中，明确写明**使用方法**，以及以**阿拉伯数字**表示伤害、或消耗数值的装备道具（即新版 RPGItem）。
   + 凡符合 [“无尽地狱”世界道具](inf/items.md) 之定义的，皆为有效道具。
   + 某些道具未写能量值，仅写明了**使用方法（具体到用哪个键）以及效果**。这种是可用的一次性 RPGItem，也具备价值。
1. 包含若干原版附魔的装备道具（等级越高越好）。
   + **不满足** [“无尽地狱”世界附魔书](inf/items.md#附魔与消魔) 定义的附魔书除外。
1. 描述最后包含**“Unbreakable（无法破坏）”**的道具。
   + 含有此的盔甲不包含在内：受伤时，其只能以附魔吸收伤害，使保护效果打折扣。
1. 新版活动限定代币，不早于 2020 年劳动节活动。
1. 新版活动限定道具，不早于 2019 年国庆节活动。
1. 服务器[周年纪念道具](space/items/anniversary-gifts.md)。

原版可得者，一般较少见诸市场（因为不及上述装备强力/好玩）。当然，都可以买。


?> :dizzy_face: **我已经买了坏掉的旧道具，怎么办？**

部分道具已有翻新版本，可以**找我们辛勤可耐的，** ***卷老师*** **换货！**  
没有的，可以找店主协商退货。


?> :blue_book: **为什么有一些非工具的物品有附魔？它们可以给其它工具附魔吗？**

这些附魔往往**仅用于装饰**，不能给其它工具附魔。

一些东西可能具有其他的加成属性，比如增加你的攻击、速度等，这时你可以选择把它们戴在头上（`/hat`），或者放在副手上。

一些附魔可能会间接工作，但并不靠谱，请不要依赖这个技巧。


?> :orange_book: **我看到这装备有陌生的附魔，红色字的，它厉害吗？**

现在**无用**，也不厉害。你就当它不存在。


?> :green_book: **一些在原版 Minecraft 里只有 1 级的附魔（精确采集、经验修补等），为什么在喵窝会存在 2 级以上的？这类附魔等级高会有特别的 buff 吗？**

这些附魔等级**仅用于装饰**，并不会带来特别的 buff；由此可见，经验修补 1 与经验修补 10 的效力一致。  
除非你是在新版武器装备上发现它们——这种确实提升了装备的强度，可以询问“肝黑”专家了解。

?> :drooling_face: **那么原来最高 3~5 级（如效率、时运）的呢？我看它们都去到 10 级了。**

恭喜你，你捡到宝了。它们真的有用。



### 关于这个世界 :id=nyaa-world

?> :sheep: **主世界的动物怎么不动了？**

一般而言，**离人 16 格以外**的动物，行动会大幅放缓。如果希望动物跟随你，最好牵绳子，没牵的不要跑太快，以免其掉队。  
如果**在线人数太多**，服务器要优先保证玩家与怪物行动无阻，动物会愈加“懒惰”。做养殖做红石什么的，等人少了再做。


?> :ice_cube: **我能不能自己摆个下界传送门？**

一般在野外，下界传送门可自行设置；但在聚落内则不建议私自设置，应首先和聚落内其他邻居共同决定。  
若你新摆设的传送门与既有的门发生“串门”，应**以既有者为先，不得私自破坏或更改其目的地。**


?> :evergreen_tree: **为什么「资源世界」在这里叫 EpicWorld？**

一句话：历史遗留的叫法。

喵窝曾使用 [EpicWorld 生成器](https://www.spigotmc.org/resources/epicworldgenerator-1-15-1-16-1.8067/)生成资源兼黑化世界，当时它也叫做 EpicWorld；但自 1.13.2 版本起，该世界每次重置，均生成原版地形。尽管如此，玩家仍习惯以 EpicWorld 相称。


?> :classical_building: **那些美观的建筑，都是在生存模式下建造的吗？**

有些是，也有些在 2019 年以前通过创造模式下建造——不过现在不再开放创造权限了。  
2019 年过后，也时而有在专门设置的[建筑服务器](wiki/server-network#ubw)内建造之后“搬运”到主世界的楼宇——包括无尽地狱世界和活动地图等。建筑服务器的背包、权限等与主服务器隔离，不会影响游戏平衡。


?> :world_map: **喵窝主世界地图是什么时候生成的？期间有更换过吗？**

是 2014 年初（即喵窝开服时）基于 1.6.x 版本生成的，自开服以来从未更换。  
而对于距离世界中心 15360 格以外的地区，2020 年 2 月起才开放并生成。详见下图：

![borders](../assets/images/history/overworld-borders.png)


?> :fish: **嗯，但是为什么海底有着 1.13 以后才有的地形？**

喵窝使用自行开发的 [插件](https://github.com/NyaaCat/update-aquatic)，实现了向在旧版生成的游戏地图移植 1.13 新增的海底地形。  
原理：使用与主世界相同的种子在新版 Minecraft 生成参考世界，并将主世界高度 ≦ 63 的水方块替换成参考世界中对应的方块。

但是，主世界**半径 15360 范围内**：

* 不包含 1.11 以后的其它新增内容：新版村庄、林地府邸等。
* 能够在沉船、水下废墟中找到的藏宝图都是错误的。

尽管后期可能会进一步开放世界边界，但如果需要探索相关地形、获取资源，最佳选择是移步至 [EpicWorld](nyaa/worlds#epicworld)。


<!-- 在服务端升级到最新版本以后，将下面的内容直接注释掉即可。 -->
<!--
?> :arrow_up: **喵窝服务端什么时候升级到最新 Minecraft 版本？**

将服务端升级到最新的 Minecraft 版本不是件非常容易的事情。在喵窝升级到下一个版本以前，需要等待插件跟进、性能评估、游戏策略的调整等。

不过，喵窝对于跟进官方最新版本是积极的，相信不久之后就可以在喵窝享受最新版本（1.16.X）的特性了。
-->


### 关于服务器资源包 :id=server-resourcepack-dl

?> :file_folder: **为什么喵窝服务器需要服务器资源包？**

喵窝的服务器资源包并不会改变游戏整体的材质，但是可以给喵窝服务器的**非原版物品**应用自定义 [模型](https://minecraft-zh.gamepedia.com/%E6%A8%A1%E5%9E%8B)，达到媲美 Mod 物品的效果。

喵窝服务器不使用 Mod，各种自定义物品均通过插件实现。这种操作固然可行，但必须基于某一种原版物品为原型，且其**原版物品特性难以被覆盖**（例如某些箭外形的 RPGitem 物品可以当成普通的箭射出去）。

不过，自 Minecraft 1.14 起，任意物品均可以通过增加 NBT 标签并配合特定资源包来实现自定义模型。这使得使用没有过多功能的原版物品（例如铁粒）作为原型成为可能，同时还极大提升了物品的观感和辨识度。

<!--
如何确保服务器资源包正常工作？

确保喵窝服务器的「使用服务器资源包」为打开状态即可。在登入服务器时，客户端会自动下载最新的服务器资源包并应用。
-->

?> :dizzy_face: **服务器资源包加载缓慢/启用后不断崩溃，怎么办？**

通常「加载缓慢」和客户端崩溃，可能发生于以下情况：

1. 资源包的下载。不过，目前资源包分发已改用中国大陆节点，国内加载速度正常情况下应该可以接受。
2. 资源包的应用。以笔者~~拉胯~~的电脑为例，该过程需要至少 20 秒；如果从其它子服务器跳转到主服务器，资源包还会加载两遍，极大影响体验。  
——以上皆可尝试离线资源包以改善体验。
3. 如果**在 Fabric 框架上同时加载 Optifine 与 VoxelMap 插件**，读取资源包时，客户端将发生崩溃<sup>（注：首次登录时不会崩溃）</sup>。<br />
——这种情况下，可尝试以下其中一种办法：
   - 额外安装 [SomeCrashFixes](https://bbs.nyaa.cat/d/1801-1164-somecrashfixes) 插件以避免崩溃<sup>（实名感谢一下宝蓝）</sup>。
   - 移除 Fabric、Optifine、VoxelMap 当中的一个。如电脑性能欠佳，可选配 [Sodium](wiki/resources#sodium)。
   - 使用离线资源包。

离线资源包下载地址：

```
https://ci.nyaacat.com/job/resourcepacks/job/master/lastSuccessfulBuild/artifact/nyaacat-resourcepack-latest.zip
```

你可将该地址加入到收藏夹、或者迅雷。建议每隔数日重复下载，以确保物品材质显示正常。  
下载后，在进入喵窝前加载之，并关闭「使用服务器资源包」选项即可。


?> :hammer_and_wrench: **这些物品模型该如何制作？**

它们是使用专门的 3D 建模工具（如 [Blockbench](https://blockbench.net/)、[Cubik Studio](https://cubik.studio/) 和 [Magicvoxel](https://www.voxelmade.com/magicavoxel)）制作而成的。如果希望入门，不妨参考一下 [这篇教程](https://bbs.craft.moe/d/2078)。

目前喵窝仍有相当一部分非原版物品没有自己的模型。如果希望为模型制作贡献一份自己的力量，参见 [创造激励计划 - Infinite Infernal 模型制作](nyaa/creation?id=infinite-infernal-模型制作)。



### 关于服务器连接问题 :id=connection

?> :computer: **修改密码后无法登陆？**

在 Mojang 官网修改密码后，新密码将会在 24h 内生效。在新密码生效前，**使用新旧密码均无法登陆 Minecraft**。

总之甩锅给 Mojang 就是了


?> :dizzy_face: **我上次玩完活动就走了，这次登录怎么登不上？**

**你上次是不是没回到主世界？**如果这时[活动服务器](wiki/server-network#act)未处于活动时间，在其再次开放前，你是无法回归的。不过，你可以：

- 等待相关服务器彻底关闭<sup>（事实上可能性极低）</sup>，在下次上线时，会自动切换到其它可用服务器。
- 联系管理组协助解决。

下次参加完活动，千万记得，先回到主世界（`/server nyaa`）再下线。


?> :woozy_face: **为什么我感觉服务器突然好卡啊？**

首先尝试 `/ping` 命令检查你与服务器的延迟。如果延迟过大，应考虑排查你的网络问题，或更换其它游戏线路。

如果延迟正常但游戏卡顿，尝试 `/tps` 命令检查服务器的 [TPS](https://www.zhihu.com/question/269769734/answer/349795953) 值（正常应为 20）。  
如果数值过低，请联系管理组反馈以协助解决问题。



### 其它初来者问题 :id=other-newcomers

?> :clock3: **我就离开了一小会儿，怎么就错过了签到奖励？**

你离开后 5 分钟内，服务器仍认为你在活动，并照常将 5 分钟内到期的签到奖励推送给你。  
害怕错过任何奖励的话，最稳妥的方案，是在离开之前手工输入 `/afk` 命令。


?> :congratulations: **我可以自行举办活动吗？**

当然可以。  
请事先计划好整个活动的各方面细节，包括主办方(一名或多名玩家或服内玩家组织)、活动名称、活动主题、时间、地点、可以参与的玩家、活动流程细节、需要管理组做何种支持等。制作成一份活动规划发送至管理组邮件列表：`owo@nyaa.cat`。管理组审核后会予以回复。

<!--
#### 救命啊！我在 Mojang 官网改完 Minecraft 游戏用户名以后，锁住的箱子打不开了！

这种情况一般在较早加入喵窝的玩家身上发生，由于较早版本的 Lockette 插件**不支持 UUID**，加上喵窝早期没有使用正版验证。

遇到这种情况，请联系管理组成员移除 Lockette 木牌，然后重新锁箱即可。

新版 LockettePro 插件已经加入对 UUID 的支持，如果锁箱时间较晚，你可以安心修改 Minecraft 游戏用户名而不用作出额外举措。
-->


---------

## 论坛相关 :id=bbs

?> :x: **别人发的论坛链接都是 HTTP 404，怎么办？**

~~先在浏览器中登录论坛（没有帐户的话请先注册），再打开链接。~~

这意味着 [帖子位于自宅板块，且你没有获得 Verified 权限](https://bbs.nyaa.cat/d/4)。如果你确认获得了相关权限，那才是别人真的手滑打错地址了。


?> :wrench: **我该如何分辨管理组成员和站长？**

管理组成员的头像上有着“深蓝色的闪电”徽章，而“红色的小扳手”徽章则代表站长。

将鼠标移动到徽章上可看到这些徽章的具体含义。


?> :six_pointed_star: **头像上粉红色的徽章是什么？我能获取吗？**

该徽章意为「Verified」（已认证），当在 NyaaBBS **累计发帖、回复 50 次以上** 时，即有资格获取之。  
需要获取时，联系管理组处理。


?> :-( **我在论坛发言中输入了一个颜文字，然后样式崩坏了！**

这是因为你输入的颜文字中，恰好包含了会被认为是 Markdown 样式语法的符号，如：
- 下划线 `_` 和星号 `*`，表示斜体或加粗（成对使用，下同）；
- 指数符号 `^`，表示上标；
- 波浪号 `~`，表示下标或删除线；
- 加减号 `+` `-` 和星号，表示无序列表；
- 反引号 ``` ` ```，表示代码块；
- 反斜杠 `\`，表示对上述符号转义。

正确的解决方法是在上述符号前面加上反斜杠 `\`，转义后其按原样显示。例如，当输入颜文字 \_(:з」∠)\_ 时，可以这样输入：

```markdown
\_(:з」∠)\_
```

---------

## 社区相关 :id=community

?> :people_holding_hands: **我可以带我的对象/同学/朋友…… 来玩吗？**

当然可以，但是：

- 你的伙伴需要自行在 [minecraft.net](https://www.minecraft.net) 注册、激活国际版账号，并**自行申请**喵窝[白名单](wiki/whitelist-application)，使用**自己的账号**登录游戏。
- **不要与你的伙伴互相共享账号**（即使你们在一起）。这是违反规则的！

<!--
#### 为什么喵窝需要正版？我能申请正版 giftcode 吗？

*   使用正版，即承认您尊重商品的著作权，并能正确地使用产品。喵窝服务器使用正版验证是希望您能够：
    +   了解正版版权的重要性
    +   有足够的自制能力，能够在游戏里做到主动遵守规则
    +   能够在游戏中主动承担起相应的玩家责任，在发生问题或冲突时，主动承担自己方面的责任并协助管理组解决问题
*   **您必须确认您满足以下要求方可申请 Minecraft 的正版 giftcode**
    +   您有较好的作品，包括但不限于 Minecraft 相关
    +   您是喵窝服务器的老玩家，但尚未申请正版
*   申请须发送邮件到 `owo@nyaa.cat` (由于一些问题，请不要使用 163 / 126 / yeah.net 等网易邮箱服务)，**包含以下内容**：
    +   玩家游戏 ID
    +   邀请玩家 ID
    +   希望获取正版 giftcode 的原因
    +   接触 Minecraft 历史
    +   优秀作品，包括但不限于 Minecraft 建筑作品，附有图或作品地址
-->

?> :construction_worker: **我不从事 IT 相关行业 / 我对 IT 相关领域没有兴趣，可以加入这个社区吗？**

相信很多人有这种误解的一个理由是 NyaaCat 社区中有相当一部分成员来自 [ArchLinuxCN](https://www.archlinuxcn.org) 社区，加上 NyaaCat 社区在 [V2EX](https://www.v2ex.com) 上进行过较多的宣传。

尽管 NyaaCat 社区有很多成员在现实生活中从事 IT 相关行业，但我们也拥有很多从事其它行业的成员。而且，我们欢迎来自任何行业 / 正在学习任何专业的小伙伴们，只要你热爱 NyaaCat 社区。


?> :family_man_woman_girl_boy: **我并不是很熟悉，或者喜欢二次元相关，也可以加入么？或者，加入后如何融入大家？**

喵窝是定位「宅文化」的社区，关于「宅」的定义—— **宅，不是 neet，不是脱离社会，也不是指团员，而是对喜欢的事情狂热。**  
喵窝社区提倡「**兼容并包**」的思想，社区成员**对于一切合理的存在都应当尽可能以包容的心态对待**。所以，不管是不是熟悉或者喜欢二次元，只要自己能够接受自己不熟悉，或者没有兴趣的东西的存在，而不是不熟悉或不感兴趣就坚决反对，都是可以加入进来的。反之，社区成员并不只是会卖萌、只是讨论二次元相关的东西，如果有其他方面的想法，或者问题，通过正确的方式提出，也会得到响应甚至引发热烈的讨论。

最后，可参考此文章[《哪些起源或流行于宅圈的文化已完全不代表宅文化.AFTER》](http://miz.audio/posts/otaku-for-the-past-3)。



--------

## 技术性问题 :id=technical

?> :red_circle: **服务器地址无法解析？显示 Unknown host?**

请更新您的 DNS。[戳这里](http://tools.cloudxns.net/Index/Diag)。


?> :orange_circle: **GNU/Linux 下 Minecraft 如何输入中文（或其他 CJK 字符）？**

GNU/Linux 下 Minecraft 输入中文/日文等解决方案：(无需 Mod，无需修改客户端，支持任何输入法)
- [方案一](#linux-typing-1)
- [方案二](#linux-typing-2)

##### 方案一 :id=linux-typing-1

> 此方案拥有比 bash 脚本更好的鲁棒性，适应多种情形，并绕过了一些坑。但是需要 Ruby。（[Gist](https://gist.github.com/FiveYellowMice/86b73e35298467e2d89b5d0cc3db1f0d)）

```ruby
#!/usr/bin/env ruby
# encoding: utf-8
# frozen_string_literal: true

# mc-im.rb
# ========
#
# 在 Linux 下的 Minecraft 中输入中文。拥有比 bash 脚本更好的鲁棒性，适应多种情形，并绕过了一些坑。
#
# 使用方法
# -------
#
# 1. 将此脚本下载，保存在任意位置。（如 `/home/user/.bin/mc-im.rb` ）
# 2. 将此文件赋予执行权限。（如 `chmod +x /home/user/.bin/mc-im.rb` ）
# 3. 在你使用的桌面环境中，添加一个快捷键（如 Meta - c ），将执行的命令设置为脚本的路径。
# 4. （可选）再添加一个另外快捷键，将执行的命令设置为脚本的路径，并在后面加上一个空格和 `--direct` 。
#
# 使用 `--direct` 选项来直接输入文字，而不去按 Esc 、 t 和 Enter ，在输入告示牌等情形下有用。
#
# 要求
# ---
# 
# 需要 Ruby 1.9 或更高版本。（除非你用的是比 Debian 7, Ubuntu 14.04, CentOS 7 还要老的发行版，这一般没有问题，不过还是确认一下你装了 Ruby 啊！）
# 需要 `xdotool` ，所以也只能在 X11 下工作。（不一定自带，请用包管理器装）
# 在 KDE 和 LXQt 中需要 `kdialog` ，而在其他桌面环境中需要 `zenity` 。（一般来说都是自带的）
#
# 版权
# ---
#
# 此脚本以公有领域授权。

TITLE_TEXT = "输入"
LABEL_TEXT = "在此输入文字："

def press(*keystrokes)
  system 'xdotool', 'key', '--delay', '100', *keystrokes
end

def type(str)
  system 'xdotool', 'type', '--delay', '100', '--', str
end

input =
if %w(KDE LXQt).include? ENV['XDG_CURRENT_DESKTOP']
  `kdialog --title '#{TITLE_TEXT}' --inputbox '#{LABEL_TEXT}'`
else
  `zenity --entry --title '#{TITLE_TEXT}' --text '#{LABEL_TEXT}'`
end.chomp

sleep 0.1

if ARGV.include? '--direct'
  type ' '
  press 'BackSpace'
  type input
elsif !input.empty?
  press 'Escape', 't'
  sleep 0.2
  type input
  press 'Return'
else
  press 'Escape'
end
```

##### 方案二 :id=linux-typing-2
> 此方案也可写入告示牌。需要 zenity 和 xdotool，如果用 `apt-get` 的话可以用 `sudo apt-get install zenity xdotool` 来安装：<sup>[（来源）](https://blog.lilydjwg.me/2015/5/17/input-chinese-to-minecraft-in-linux.93167.html)</sup>

```bash
#!/bin/bash -e
chars=$(zenity --title 中文输入 --text 中文输入 --width 500 --entry 2>/dev/null)
sleep 0.1
xdotool key --delay 150 Escape t
sleep 0.2
xdotool type --delay 150 "$chars"
xdotool key Return
```

如果不想自动按 t 和回车的话（如写入告示牌的情形），可以去掉不需要的行：

```bash
#!/bin/bash
chars=$(zenity --title 中文输入 --text 中文输入 --width 500 --entry 2>/dev/null)
xdotool type --delay 150 "$chars"
```

如果不想使用 zenity 的话，请根据你所使用的工具来修改第二行。如 Ubuntu 下用 gdialog ，就将第二行修改为：

```bash
chars=$(gdialog --inputbox ' ' 2>&1)
```


?> :yellow_circle: **macOS 下 Minecraft 如何在聊天框输入中文（或其他 CJK 字符）？**

喵窝目前使用的游戏版本在 macOS Catalina (10.15) 和 Big Sur (11.0) 可以正常通过输入法输入中文。

根据笔者测试，目前直接输入中文时存在以下问题：

- 输入拼音时，如果试图删除已经输入的拼音，则会同时删除已经输入的汉字。

尽管如此，目前还是基本可以使用的。对于比较重要的文本，建议先在其它文本编辑器中输入，然后粘贴到游戏中。


?> :green_circle: **macOS 下鼠标滚轮速度鬼畜**

这是由于 macOS Sierra 及以上版本的鼠标滚轮加速功能导致的；该功能对 Minecraft 并不是非常友好，从而会导致滚动速度鬼畜的问题。

如果需要禁用滚轮加速功能，可以尝试安装 [DiscreteScroll](https://github.com/emreyolcu/discrete-scroll)。

?> :large_blue_circle: **下载文件失败/无法登录正版服务器**

因为 Mojang 的服务器基本托管在 Amazon AWS，所以部分地区的用户经常会遇到下载失败、无法登录等等问题。解决方案之一是让启动器通过 [SOCKS5](https://en.wikipedia.org/wiki/SOCKS#SOCKS5) 代理启动。

但是，由于新版启动器没有提供代理设置，通过 Proxifier 等第三方工具配置步骤繁杂、稳定性不确定，我们建议直接更换第三方启动器（如 [MultiMC](https://multimc.org/)），然后在启动器中配置代理。

通常情况下，给启动器配置代理**不会影响**游戏的网络连接，但还请仔细阅读启动器的相关说明。

![](../assets/images/faq/multimc_proxy_config.png)  
<small>MultiMC 的代理设置页面。正如界面中的说明，该代理设置<b>仅适用于启动器</b>，不适用于游戏本体。</small>


?> :purple_circle: **如何设置游戏的内存大小**

在 JVM Arguments 中填写 `-Xmx` 参数。
例如：`-Xmx2G` 表示为最多占用 2G 内存。

32 位 Java 最大只能设置为 1G。


?> :coffee: **那么，我该如何下载到 64 位 Java 呢？**

如正在以官方启动器登录，这个问题无需操心。  
如使用其它启动器，建议下载[Amazon Corretto](https://corretto.aws/downloads/latest/amazon-corretto-8-x64-windows-jdk.msi)——点击即获取 Windows 64位版本。[没有在用Windows？](https://docs.aws.amazon.com/corretto/latest/corretto-8-ug/downloads-list.html)

安装完成以后，不要忘记在你的启动器中设置好 Java 运行时（javaw.exe）目录。


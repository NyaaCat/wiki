# FAQ

问题没有得到解决？

首先要多看看 NyaaWiki 与 [Minecraft Wiki](https://minecraft-zh.gamepedia.com/Minecraft_Wiki) 的其它页面，因为那是众喵们逐字逐句写出来的；本 FAQ 仅仅提供了常见问题的解决方案，一些内容可能还没有覆盖。如果 Wiki 上也没有，那就试着在社群里询问吧。

总之你抽出一定时间仔细阅读 Wiki，后面只会节省更多时间！

### Nyaa BBS 相关

#### 别人发的论坛链接都是 HTTP 404，怎么办？
~~先在浏览器中登录论坛（没有帐户的话请先注册），再打开链接。~~

这意味着 [帖子位于自宅板块，且你没有获得 Verified 权限](https://bbs.nyaa.cat/d/4)。如果你确认获得了相关权限，那才是别人真的手滑打错地址了。

以及喵窝的梯子在自宅板块。

#### 我该如何分辨管理员和站长？

管理员的头像上有着深蓝色的闪电徽章，站长（特指_凤凰卷_ ）的头像上有着红色的小扳手徽章。

将鼠标移动到徽章上可看到这些徽章的具体含义。

### Nyaa Wiki 相关

#### 如何获得 Wiki 的帐号？

发送邮件到 &lt;owo#nyaa.cat&gt; (记得把“#“换成”@”)，注明请求 Wiki 帐号就可以了喵~

请求通过后管理员会将用户名和密码以邮件的方式发送给你，登录之后可以通过右上角的「编辑资料」修改密码。

#### 那个，Wiki 的语法是？

现在的 NyaaWiki 使用可视化编辑器。如要练手，可前往 【[Playground](misc/playground.md)】体验 。

#### 没有那个啥啥页面，咋办？

去创建它呗~在相应的图书页面，点击右上角的+新页面即可。

#### 原来侧边栏的（页面名称）不见了

尝试进行搜索。但如果还是找不到，说明页面确实被删除了。

### 社区相关

#### 你们说的星球是什么东西啊，不是很懂

是 NyaaCat Planet，[这里有它的介绍](wiki/planet-nyaacat.md)。

#### 我不从事 IT 相关行业 / 我对 IT 相关领域没有兴趣，可以加入这个社区吗？

相信很多人有这种误解的一个理由是 NyaaCat 社区中有相当一部分成员来自 [ArchLinuxCN](https://www.archlinuxcn.org) 社区，加上 NyaaCat 社区在 [V2EX](https://www.v2ex.com) 上进行过较多的宣传。

尽管 NyaaCat 社区有很多成员在现实生活中从事 IT 相关行业，但我们也拥有很多从事其它行业的成员。而且，我们欢迎来自任何行业 / 正在学习任何专业的小伙伴们，只要你热爱 NyaaCat 社区。

#### 我并不是很熟悉，或者喜欢二次元相关，也可以加入么？或者，加入后如何融入大家？

喵窝是定位「宅文化」的社区，关于「宅」的定义—— **宅，不是 neet，不是脱离社会，也不是指团员，而是对喜欢的事情狂热。**[1)](#fn__1)喵窝社区提倡「**兼容并包**」的思想，社区成员**对于一切合理的存在都应当尽可能以包容的心态对待**。所以，不管是不是熟悉或者喜欢二次元，只要自己能够接受自己不熟悉，或者没有兴趣的东西的存在，而不是不熟悉或不感兴趣就坚决反对，都是可以加入进来的。反之，社区成员并不只是会卖萌、只是讨论二次元相关的东西，如果有其他方面的想法，或者问题，通过正确的方式提出，也会得到响应甚至引发热烈的讨论。

[1)](#fnt__1)
[哪些起源或流行于宅圈的文化已完全不代表宅文化.AFTER](http://miz.audio/posts/otaku-for-the-past-3)


### 技术问题

#### 服务器地址无法解析？显示 Unknown host?

请更新您的 DNS。[戳这里](http://tools.cloudxns.net/Index/Diag)。


#### GNU/Linux 下 Minecraft 如何输入中文（或其他 CJK 字符）？

GNU/Linux 下 Minecraft 输入中文/日文等解决方案：(无需 Mod，无需修改客户端，支持任何输入法)

##### 方案一

此方案拥有比 bash 脚本更好的鲁棒性，适应多种情形，并绕过了一些坑。但是需要 Ruby 。（[Gist](https://gist.github.com/FiveYellowMice/86b73e35298467e2d89b5d0cc3db1f0d)）

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
    end`

##### 方案二
此方案也可写入告示牌。需要 zenity 和 xdotool，如果用 `apt-get` 的话可以用 `sudo apt-get install zenity xdotool` 来安装：[1)](#fn__1)

   
	#!/bin/bash -e
    chars=$(zenity --title 中文输入 --text 中文输入 --width 500 --entry 2&gt;/dev/null)
    sleep 0.1
    xdotool key --delay 150 Escape t
    sleep 0.2
    xdotool type --delay 150 "$chars"
    xdotool key Return`
如果不想自动按 t 和回车的话（如写入告示牌的情形），可以去掉不需要的行：

    #!/bin/bash
    chars=$(zenity --title 中文输入 --text 中文输入 --width 500 --entry 2&gt;/dev/null)
    xdotool type --delay 150 "$chars"`

如果不想使用 zenity 的话，请根据你所使用的工具来修改第二行。如 Ubuntu 下用 gdialog ，就将第二行修改为：

	chars=$(gdialog --inputbox ' ' 2>&1)
    

#### macOS 下 Minecraft 如何在聊天框输入中文（或其他 CJK 字符）？

(无需 Mod，无需修改客户端，支持任何输入法)

注：仅在 10.9 测试通过，据玩家报告 10.10 下使用异常。 以下提供[经 @OrcaXS 修改的 mc-chat-helper](https://github.com/OrcaXS/minecraft-chat-helper)。 使用 Github for Mac 可以将其直接克隆到本地。也可以使用 git clone 指令克隆此脚本到任意目录，具体终端操作如下：

    git clone https://github.com/OrcaXS/minecraft-chat-helper:/Users/XXX/AppleScript`

请将 XXX 设定为您的用户名，脚本所在目录也可以设定为任意位置）
之后的具体设定方法请参见 [@OrcaXS 的GIST](https://gist.github.com/OrcaXS/312e80a899ad425a98e5)。

游戏时，请直接按下设定的快捷键（比如：Cmd + T），屏幕内将会弹出对话框，即可输入任意文字，回车后自动发送。

如果使用 Forge 的话，可以使用 [CocoaInput](https://minecraft.curseforge.com/projects/cocoainput)

#### 下载文件失败/无法登录正版服务器

提醒：目前 Mojang 似乎在 [封杀使用代理服务器的中国大陆玩家](https://www.reddit.com/r/Minecraft/comments/5vwve1/mojang_now_ban_accounts_for_vpn_usage/)，因此请尽量不使用代理登录。

##### 使用 SOCKS5 代理

因为 Mojang 的服务器基本托管在 Amazon AWS，所以部分地区的用户经常会遇到下载失败、无法登录等等问题。解决方案之一是让启动器通过 [SOCKS5](https://en.wikipedia.org/wiki/SOCKS#SOCKS5) 代理启动。

下面的示例用于启动启动器，并不是启动器内填写的 Profile JVM Arguments。

启动器启动命令示例[2)](#fn__2):

`java -DsocksProxyHost=127.0.0.1 -DsocksProxyPort=1080 -jar Minecraft.jar`

可以看出这里的 `127.0.0.1:1080` 是一个 SOCKS5 代理地址。

这个参数**不会影响**游戏的网络连接。

不过有时会遇到进入游戏后又出现验证服务器报错的情况<span style="text-decoration: line-through;">（因为脸太黑了，解决方案洗脸）</span>，这个时候不妨用下面的方案试试看，不仅修改启动器启动命令，还需要修改启动器内填写的 Profile JVM Arguments。

启动器启动命令示例同上。

启动器内填写的 Profile JVM Arguments 示例：

`-Xmx1G -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:-UseAdaptiveSizePolicy -Xmn128M -DsocksProxyHost=127.0.0.1 -DsocksProxyPort=1080`

这个参数同样**不会影响**游戏的网络连接。

##### 使用 hosts

将下面的代码添加到 hosts 文件中，即可通过专用的 SNI 加密代理登录 Minecraft 服务器（客户端/服务端均适用）_<sup><span style="color: #ff0000;">[待验证]</span></sup>_

(请注意此代理仅适用于登录 Minecraft 服务器，其他网域访问将直接报错）

    # minecraft sniproxy IPv4
    106.187.38.30 api.mojang.com
    106.187.38.30 account.mojang.com
    106.187.38.30 auth.mojang.com
    106.187.38.30 authserver.mojang.com      
    106.187.38.30 login.minecraft.net
    106.187.38.30 session.minecraft.net
    106.187.38.30 sessionserver.mojang.com
    106.187.38.30 skins.minecraft.net
    106.187.38.30 minecraft.net

    # minecraft sniproxy IPv6
    2600:3c01::f03c:91ff:fe61:81ae api.mojang.com
    2600:3c01::f03c:91ff:fe61:81ae account.mojang.com
    2600:3c01::f03c:91ff:fe61:81ae auth.mojang.com
    2600:3c01::f03c:91ff:fe61:81ae authserver.mojang.com      
    2600:3c01::f03c:91ff:fe61:81ae login.minecraft.net
    2600:3c01::f03c:91ff:fe61:81ae session.minecraft.net
    2600:3c01::f03c:91ff:fe61:81ae sessionserver.mojang.com
    2600:3c01::f03c:91ff:fe61:81ae skins.minecraft.net
    2600:3c01::f03c:91ff:fe61:81ae minecraft.net

##### 使用喵窝梯子无法登陆 Mojang 官网

关掉梯子即可。

#### 如何设置游戏的内存大小

在 JVM Arguments 中填写 `-Xmx` 参数。
例如：`-Xmx2G` 表示为最多占用 2G 内存。

32 位 Java 最大只能设置为 1G。


[1)](#fnt__1)
来源：[Linux 下在 Minecraft 里输入中文 - 依云's Blog](https://blog.lilydjwg.me/2015/5/17/input-chinese-to-minecraft-in-linux.93167.html)

[2)](#fnt__2)
[Java Networking and Proxies](https://docs.oracle.com/javase/8/docs/technotes/guides/net/proxies.htm)







### 插件相关

#### 如何使用锁箱插件？

放置一个箱子(或其他可以存放物品的容器)，向其上放置一块木牌，不需要写任何内容，即可锁住该容器。只有木牌上有名字的玩家才可以打开。如果有些容器无法直接右键放置，请按住 `Shift` 再右键放置。

在上锁的箱子上右键牌子输入 `/lockette 3 playername` 即可实现与好友的共享而非所有玩家的共享。

#### 如何创建快递箱？如何向其他玩家发送快递？

[这里](tutorial/nyaautils) 有详细说明。

#### 救命啊！我在 Mojang 官网改完 Minecraft 游戏用户名以后，锁住的箱子打不开了！

这种情况一般在较早加入喵窝的玩家身上发生，由于较早版本的 lockette 插件**不支持 UUID。**

遇到这种情况，请联系管理组成员移除 lockette 木牌，然后重新锁箱即可。 [1)](#fn__1)

新版 lockette 插件已经加入对 UUID 的支持，如果锁箱时间较晚，你可以安心修改 Minecraft 游戏用户名而不用作出额外举措。

[1)](#fnt__1)
lockette [官方说明](https://dev.bukkit.org/bukkit-plugins/lockette/) 指出了插件会通过用户名历史来重新确认以前的箱子锁的所有权，但由于喵窝以前未开启正版验证等一系列历史原因，贸然改回可能会导致更大的麻烦。

### 游戏相关

##### 为什么喵窝需要正版？我能申请正版 giftcode 吗？


*   使用正版，即承认您尊重商品的著作权，并能正确地使用产品。喵窝服务器使用正版验证是希望您能够：

    *   了解正版版权的重要性

        *   有足够的自制能力，能够在游戏里做到主动遵守规则

        *   能够在游戏中主动承担起相应的玩家责任，在发生问题或冲突时，主动承担自己方面的责任并协助管理员解决问题

*   **您必须确认您满足以下要求方可申请 Minecraft 的正版 giftcode**

    *   您有较好的作品，包括但不限于 Minecraft 相关

        *   您是喵窝服务器的老玩家，但尚未申请正版

*   申请须发送邮件到 `owo@nyaa.cat` (由于一些问题，请不要使用 163 / 126 / yeah.net 等网易邮箱服务)，**包含以下内容**：

    *   玩家游戏 ID

        *   邀请玩家 ID

        *   希望获取正版 giftcode 的原因

        *   接触 Minecraft 历史

        *   优秀作品，包括但不限于 Minecraft 建筑作品，附有图或作品地址

#### 喵窝服务器对客户端有特别的要求吗？

喵窝服务器不需要专用客户端，使用原版 Minecraft 客户端即可登录。

不过，如果你懒得自行配置带有辅助性 mod 的客户端，可以直接使用喵窝玩家提供的 [整合包](wiki/resources.md)。

#### 第一次加入服务器如何注册？以后如何登录？

喵窝已经开启正版验证，不需要 `/login` 命令。只需确认已经使用正版方式启动游戏，并且位于服务器白名单之中，即可直接加入游戏。

#### 我使用的是 1.14.x 客户端，为什么却给我 Outdated Server 的提示？

喵窝服务器**目前没有**使用官方最新版本，请使用 <span style="color: #ff0000;">**1.13.2 版本**</span>的客户端进入服务器。

#### 如何去其它维度（世界）？

命令 `/mvtp [维度代号]` 可达。
但该命令仅可前往指定维度的总出生点。若需抵达出生点以外的任意位置，请使用[传送牌](tutorial/teleport-capcat.md)。

如果是下界或末地，可前往主世界对应的传送门前往。

#### 我通过 ''/ptt ac'' 命令领取了一个名称为「樱花辦」的粉色染料外形物品，它可以做什么？

这是用于启动 [月常环游任务](https://wiki.nyaa.cat/books/%E7%8E%A9%E6%B3%95%E6%95%99%E7%A8%8B/page/%E6%9C%88%E5%B8%B8%E7%8E%AF%E6%B8%B8%E4%BB%BB%E5%8A%A1) 的中间兑换物。

##### 这名字好像有什么不对？

不错，“辦”应作“瓣”。然而，其乃万物之源，此生已不可能改正……

#### 如何设置名称前/后缀？

目前支持通过命令自助设置前后缀。请参阅 [本页面](tutorial/nyaautils.md) 中 前缀/后缀 一节了解详情。

#### 维修点在哪里？该如何使用？

目前已废弃维修点，请移步 [这里](tutorial/Item-repair.md) 参看新版维修方法。

#### 为什么有一些非工具的物品有附魔？它们可以给其它工具附魔吗？

这些附魔往往**仅用于装饰**，不能给其它工具附魔。

一些东西可能具有其他的加成属性，比如增加你的攻击、速度等，这时你可以选择把它们戴在头上（`/hat`），或者放在副手上。

一些附魔可能会间接工作（比如使用带有时运附魔的非工具物品收割作物可以增加产量），但并不靠谱，请不要依赖这个技巧。

#### 一些在原版 Minecraft 里只有 1 级的附魔（精确采集、经验修补等），为什么在喵窝会存在 2 级以上的？这类附魔等级高会有特别的 buff 吗？

这些附魔等级**仅用于装饰**，并不会带来特别的 buff；由此可见，经验修补 1 与经验修补 10 的效力一致。

#### 为什么我感觉服务器突然好卡啊？

首先你可以尝试使用 `/ping` 命令检查你与服务器的延迟。如果延迟不正常，请尝试检查你自身的网络状况，或更换其它游戏线路。

如果延迟正常但游戏卡顿，意味着游戏服务器可能出现 [TPS 过低](https://www.spigotmc.org/threads/what-is-tps.4277/) 等异常状况，请联系管理组反馈以协助解决问题。

#### 如何申请举办活动？

请事先计划好整个活动的各方面细节，包括主办方(一名或多名玩家或服内玩家组织)、活动名称、活动主题、时间、地点、可以参与的玩家、活动流程细节、需要管理组做何种支持等。制作成一份活动规划发送至管理组邮件列表：`owo@nyaa.cat`。管理组审核后会予以回复。

#### 修改密码后无法登陆？

在 Mojang 官网修改密码后，新密码将会在 24h 内生效。在新密码生效前，**使用新旧密码均无法登陆 Minecraft**。

总之甩锅给 Mojang 就是了

#### 如何在游戏聊天内分享一条命令？

在命令前面输入一个样式代码，比如

	&f/nu rename 好喝的水

那么你就可以**以聊天文本的形式**发出

	/nu rename 好喝的水

了。

### 参与贡献

#### 如何成为高级玩家？

普通玩家**在线游戏时间（不包含 afk 时间）**达到 128 小时后，PlayTimeTracker 会在聊天屏幕提示你可以领取 `advanced` 奖励，输入 `/ptt ac` 即可自助升级高级玩家，升级机会只有 1 次。

高级玩家 30 天不活跃后会自动降级为普通玩家。如果错过了高级玩家的领取，或长时间不上线被降级为普通玩家，可以联系管理组重新申请积累，积累到足够的时间后即可再次获取奖励。

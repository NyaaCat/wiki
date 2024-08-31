# 推荐资源

这里是推荐使用的各类游戏资源。  
请注意这里仅仅是推荐，我们的服务器对客户端**除了版本对应外，没有任何要求**。相比于原版，使用这些整合包/资源包可以让您获得更好的游戏体验。但如果您有自己的选择，请尽管按照自己的喜好来游戏。

这里提供的版本可能不是最新的，最新版本请参考各资源官网。

如果因为一些原因需要适用于旧版的资源，戳 [这里](wiki/resources/old)。

<details>
<summary>:information_source: 关于官方启动器使用 MultiMC 整合包</summary>

如果你正在、且只能使用官方启动器，你必须先安装 Fabric 框架，并配合 **Fabric API** 模组使用（以上整合包均已包含 Fabric API）。

1. 首先[下载](https://fabricmc.net/use/) Fabric 框架安装器，之后双击安装。
2. 从整合包内的 `.minecraft/mods` 目录，提取所有文件，放到官方启动器所存储的<span class="nw-explain" title="对于Windows，其位于 C:\Users\<用户名>\AppData\Roaming\.minecraft">游戏目录</span>下的 `mods` 目录中。
3. 整合包可能禁用了 Optifine / OptiFabric，如需使用它们，重命名将 `.disabled` 后缀删除。如果需要 [Sodium](#sodium)，请勿重命名。
4. （可选）从 [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-api) 下载最新版 Fabric API。
  <!-- - **注意：1.15.2 整合包**内的 Fabric API 不要更新。 -->
1. 开始游戏吧:-P

</details>

--------

## 原版整合包（客户端）

——以下整合包可正常登录喵窝世界，以及除 `hana` 以外的所有[子服务器](wiki/server-network)。

### Minecraft 1.21.1

?> :heart: 【2024.08.31 更新】**Minecraft 1.21.1 简单整合** *by BlingWang*

提供可被 MultiMC 导入的 Mod 包。

[原帖与下载地址](https://community.craft.moe/d/5182)

<details>
<summary>默认包含模组</summary>

[Moddermore 列表](https://moddermore.net/list/ClMMrGvIbcXH)

- [Animatica](https://modrinth.com/mod/animatica) - A mod implementing the OptiFine/MCPatcher animated texture format
- [AppleSkin](https://modrinth.com/mod/appleskin) - Food/hunger-related HUD improvements
- [Architectury API](https://modrinth.com/mod/architectury-api) - An intermediary api aimed to ease developing multiplatform mods.
- [Auth Me](https://modrinth.com/mod/auth-me) - Authenticate yourself and re-validate your session
- [Better Mount HUD](https://modrinth.com/mod/better-mount-hud) - Improves the ingame HUD while riding a mount
- [Better Ping Display [Fabric]](https://modrinth.com/mod/better-ping-display-fabric) - Adds a configurable numerical ping display to the player list
- [BetterF3](https://modrinth.com/mod/betterf3) - BetterF3 is a mod that replaces Minecraft's original debug HUD with a highly customizable, more human-readable HUD.
- [Capes](https://modrinth.com/mod/capes) - Lets you use capes from OptiFine, LabyMod and other cape mods
- [Cloth Config API](https://modrinth.com/mod/cloth-config) - Configuration Library for Minecraft Mods
- [Concurrent Chunk Management Engine (Fabric)](https://modrinth.com/mod/c2me-fabric) - A Fabric mod designed to improve the chunk performance of Minecraft.
- [Continuity](https://modrinth.com/mod/continuity) - A Fabric mod that allows for efficient connected textures
- [Controlling](https://modrinth.com/mod/controlling) - Adds a search bar to the Key-Bindings menu
- [Cubes Without Borders](https://modrinth.com/mod/cubes-without-borders) - A mod that allows you to play Minecraft in a borderless fullscreen window.
- [Dark Loading Screen](https://modrinth.com/mod/dark-loading-screen) - Makes the loading screen darker.
- [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) - Reduce resource usage while Minecraft is in the background or idle.
- [Enhanced Block Entities](https://modrinth.com/mod/ebe) - Reduce block entity FPS lag with almost no compromises, and improve their visuals
- [Entity Culling](https://modrinth.com/mod/entityculling) - Using async path-tracing to hide Block-/Entities that are not visible
- [Fabric API](https://modrinth.com/mod/fabric-api) - Lightweight and modular API providing common hooks and intercompatibility measures utilized by mods using the Fabric toolchain.
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) - This is a mod that enables usage of the Kotlin programming language for Fabric mods.
- [FabricSkyBoxes Interop](https://modrinth.com/mod/fabricskyboxes-interop) - FabricSkyBoxes Interoperability for MCPatcher/OptiFine Skies
- [FabricSkyboxes](https://modrinth.com/mod/fabricskyboxes) - Allows resource packs to define custom skyboxes.
- [Fabrishot](https://modrinth.com/mod/fabrishot) - Take insanely large screenshots because why not
- [FastQuit](https://modrinth.com/mod/fastquit) - Lets you return to the Title Screen early while your world is still saving in the background!
- [FerriteCore](https://modrinth.com/mod/ferrite-core) - Memory usage optimizations
- [Gamma Utils (Fullbright)](https://modrinth.com/mod/gamma-utils) - Gamma / Brightness / Night Vision mod, making it easy to see in the dark. Basically Fullbright for Fabric.
- [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) - Speed up immediate mode rendering in Minecraft
- [Indium](https://modrinth.com/mod/indium) - Sodium addon providing support for the Fabric Rendering API, based on Indigo
- [Inventory Profiles Next](https://modrinth.com/mod/inventory-profiles-next) - Take control over you inventory. Sort. Move matching Items. Throw all. Locked slots. Gear sets! And much more.
- [Iris Shaders](https://modrinth.com/mod/iris) - A modern shader pack loader for Minecraft intended to be compatible with existing OptiFine shader packs
- [Language Reload](https://modrinth.com/mod/language-reload) - Reduces load times and adds fallbacks for languages
- [Lithium](https://modrinth.com/mod/lithium) - No-compromises game logic/server optimization mod
- [MixinTrace](https://modrinth.com/mod/mixintrace) - Adds a list of mixins in the stack trace to crash reports 
- [Mod Menu](https://modrinth.com/mod/modmenu) - Adds a mod menu to view the list of mods you have installed.
- [Model Gap Fix](https://modrinth.com/mod/modelfix) - Fixes gaps in Block Models and Item Models
- [ModernFix](https://modrinth.com/mod/modernfix) - All-in-one mod that improves performance, reduces memory usage, and fixes many bugs. Compatible with all your favorite performance mods!
- [More Chat History](https://modrinth.com/mod/morechathistory) - Increases the maximum length of chat history.
- [More Culling](https://modrinth.com/mod/moreculling) - A mod that changes how multiple types of culling are handled in order to improve performance
- [No Chat Reports](https://modrinth.com/mod/no-chat-reports) - Makes chat unreportable (where possible)
- [OptiGUI](https://modrinth.com/mod/optigui) - Blazing fast custom GUI textures on Fabric and Quilt with built-in OptiFine custom GUI resource pack support
- [Paginated Advancements & Custom Frames](https://modrinth.com/mod/paginatedadvancements) - Better advancements screen
- [Polytone](https://modrinth.com/mod/polytone) - Customize Map Color, Block Colors, Colormaps and Block Sounds, Biome Colors, Dye Colors. Supports Optifine format. For Resource Packs
- [Puzzle](https://modrinth.com/mod/puzzle) - Adds resourcepack features and a GUI to more conveniently configure OptiFine alternatives.
- [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options) - Alternative Options Menu for Sodium
- [Remove Reloading Screen](https://modrinth.com/mod/rrls) - Makes resource packs load in the background, allowing you to do other things while waiting!
- [Searchables](https://modrinth.com/mod/searchables) - Searchables is a library mod that adds helper methods that allow for searching and filtering elements based on components, as well as offering built in auto-complete functionality.
- [Sodium](https://modrinth.com/mod/sodium) - The fastest and most compatible rendering optimization mod for Minecraft. Now available for both NeoForge and Fabric!
- [Sodium Extra](https://modrinth.com/mod/sodium-extra) - A Sodium addon that adds features that shouldn't be in Sodium.
- [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap) - Displays a map of the nearby world terrain, players, mobs, entities in the corner of your screen. Lets you create waypoints which help you find the locations you've marked.
- [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map) - Adds a full screen world map which shows you what you have explored in the world. Works great together with Xaero's Minimap.
- [YetAnotherConfigLib](https://modrinth.com/mod/yacl) - A builder-based configuration library for Minecraft.
- [Your Options Shall Be Respected (YOSBR)](https://modrinth.com/mod/yosbr) - Your options shall be respected.
- [Zoomify](https://modrinth.com/mod/zoomify) - A zoom mod with infinite customizability.
- [[EMF] Entity Model Features](https://modrinth.com/mod/entity-model-features) - EMF is an, OptiFine format, Custom Entity Model replacement mod available for Fabric and Forge.
- [[ETF] Entity Texture Features](https://modrinth.com/mod/entitytexturefeatures) - Emissive, Random & Custom texture support for entities in resourcepacks just like Optifine but for Fabric
- [e4mc](https://modrinth.com/mod/e4mc) - Open a LAN server to anyone, anywhere, anytime.
- [libIPN](https://modrinth.com/mod/libipn) - Inventory Profiles Next GUI/Config library

</details>

?> :blue_heart: 【2024.08.03 更新】**Minecraft 1.21.x 简单实用整合包** *by Big_WhiteDragon*

提供可被 MultiMC 导入的 Mod 包。

[原帖与下载地址](https://community.craft.moe/d/5121)

<details>
<summary>默认包含模组</summary>

[Moddermore 列表](https://moddermore.net/list/xvXCQ87YMmgt)

- [Animatica](https://modrinth.com/mod/animatica) - A mod implementing the OptiFine/MCPatcher animated texture format
- [AppleSkin](https://modrinth.com/mod/appleskin) - Food/hunger-related HUD improvements
- [Auth Me](https://modrinth.com/mod/auth-me) - Authenticate yourself and re-validate your session
- [Better Ping Display [Fabric]](https://modrinth.com/mod/better-ping-display-fabric) - Adds a configurable numerical ping display to the player list
- [BetterF3](https://modrinth.com/mod/betterf3) - BetterF3 is a mod that replaces Minecraft's original debug HUD with a highly customizable, more human-readable HUD.
- [Bobby](https://modrinth.com/mod/bobby) - Allows for render distances greater than the server's view-distance
- [Capes](https://modrinth.com/mod/capes) - Lets you use capes from OptiFine, LabyMod and other cape mods
- [Chat Heads](https://modrinth.com/mod/chat-heads) - See who you're chatting with!
- [Concurrent Chunk Management Engine (Fabric)](https://modrinth.com/mod/c2me-fabric) - A Fabric mod designed to improve the chunk performance of Minecraft.
- [Continuity](https://modrinth.com/mod/continuity) - A Fabric mod that allows for efficient connected textures
- [Controlify](https://modrinth.com/mod/controlify) - Adds the best controller support to Minecraft Java edition!
- [Debugify](https://modrinth.com/mod/debugify) - Fixes Minecraft bugs found on the bug tracker
- [Entity Culling](https://modrinth.com/mod/entityculling) - Using async path-tracing to hide Block-/Entities that are not visible
- [Fabric API](https://modrinth.com/mod/fabric-api) - Lightweight and modular API providing common hooks and intercompatibility measures utilized by mods using the Fabric toolchain.
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) - This is a mod that enables usage of the Kotlin programming language for Fabric mods.
- [FerriteCore](https://modrinth.com/mod/ferrite-core) - Memory usage optimizations
- [Forge Config API Port](https://modrinth.com/mod/forge-config-api-port) - NeoForge's & Forge's config systems provided to other modding ecosystems. Designed for a multiloader architecture.
- [Freecam (Modrinth Edition)](https://modrinth.com/mod/freecam) - A highly customizable freecam mod.
- [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) - Speed up immediate mode rendering in Minecraft
- [Indium](https://modrinth.com/mod/indium) - Sodium addon providing support for the Fabric Rendering API, based on Indigo
- [Iris Shaders](https://modrinth.com/mod/iris) - A modern shader pack loader for Minecraft intended to be compatible with existing OptiFine shader packs
- [LAN World Plug-n-Play (mcwifipnp)](https://modrinth.com/mod/mcwifipnp) - LAN World Plug-n-Play (mcwifipnp)
- [Lithium](https://modrinth.com/mod/lithium) - No-compromises game logic/server optimization mod
- [MixinTrace](https://modrinth.com/mod/mixintrace) - Adds a list of mixins in the stack trace to crash reports 
- [Mod Menu](https://modrinth.com/mod/modmenu) - Adds a mod menu to view the list of mods you have installed.
- [More Chat History](https://modrinth.com/mod/morechathistory) - Increases the maximum length of chat history.
- [More Culling](https://modrinth.com/mod/moreculling) - A mod that changes how multiple types of culling are handled in order to improve performance
- [OptiGUI](https://modrinth.com/mod/optigui) - Blazing fast custom GUI textures on Fabric and Quilt with built-in OptiFine custom GUI resource pack support
- [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options) - Alternative Options Menu for Sodium
- [Restore Chat Links](https://modrinth.com/mod/restore-chat-links) - Clickable player chat links
- [Screenshot to Clipboard](https://modrinth.com/mod/screenshot-to-clipboard) - Screenshots taken are copied to the clipboard.
- [Sodium](https://modrinth.com/mod/sodium) - The fastest and most compatible rendering optimization mod for Minecraft. Now available for both NeoForge and Fabric!
- [Sodium Extra](https://modrinth.com/mod/sodium-extra) - A Sodium addon that adds features that shouldn't be in Sodium.
- [Status Effect Bars](https://modrinth.com/mod/status-effect-bars) - Adds customizable bars to the status effects overlay to show the remaining duration of effects.
- [WTHIT](https://modrinth.com/mod/wthit) - What the hell is that?
- [WorldEdit](https://modrinth.com/mod/worldedit) - A Minecraft Map Editor... that runs in-game!
With selections, schematics, copy and paste, brushes, and scripting.
Use it in creative, or use it temporarily in survival.
- [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap) - Displays a map of the nearby world terrain, players, mobs, entities in the corner of your screen. Lets you create waypoints which help you find the locations you've marked.
- [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map) - Adds a full screen world map which shows you what you have explored in the world. Works great together with Xaero's Minimap.
- [YetAnotherConfigLib](https://modrinth.com/mod/yacl) - A builder-based configuration library for Minecraft.
- [bad packets](https://modrinth.com/mod/badpackets) - Bad Packets allows packet messaging between different modding platforms.
- [lazy-language-loader](https://modrinth.com/mod/lazy-language-loader) - lazy-language-loader improves loading times when changing your language by only reloading the language instead of all the game resources!

</details>

## 模组服务器整合包

——以下整合包可登录模组服务器 `hana`。

### NyaaCat: Flourish Moment 2024.6

由 *凤凰卷 `phoenixlzx`* 整理，提供可被 MultiMC 导入的 Mod 包。

[原帖与下载地址](https://community.craft.moe/d/5122)

<details>
<summary>默认包含模组</summary>

[Moddermore 列表](https://moddermore.net/list/Ni5DCRustDdX)

- [3D Skin Layers](https://modrinth.com/mod/3dskinlayers) - Render the player skin layer in 3d!
- [Ad Astra](https://modrinth.com/mod/ad-astra) - Live long and prosper, Ad Astra!
- [AppleSkin](https://modrinth.com/mod/appleskin) - Food/hunger-related HUD improvements
- [Applied Botanics](https://modrinth.com/mod/applied-botanics) - mana through ae2, what could go wrong
- [Applied Energistics 2](https://modrinth.com/mod/ae2) - AE2: A popular automation and storage mod
- [Applied Energistics 2 Wireless Terminals](https://modrinth.com/mod/applied-energistics-2-wireless-terminals) - An addon for Applied Energistics 2 that adds wireless versions of several Terminals
- [Aquamirae](https://modrinth.com/mod/aquamirae) - Ship graveyard with terrible deep sea creatures!
- [Balm](https://modrinth.com/mod/balm) - Abstraction Layer (but not really)™ for Blay's multiplatform mods
- [Botania](https://modrinth.com/mod/botania) - An innovative natural magic themed tech mod
- [Botarium](https://modrinth.com/mod/botarium) - A crossplatform API for devs that makes transfer and storage of items, fluids and energy easier, as well as some other helpful things
- [Cloth Config API](https://modrinth.com/mod/cloth-config) - Configuration Library for Minecraft Mods
- [Cooking for Blockheads](https://modrinth.com/mod/cooking-for-blockheads) - Adds a cooking book and multiblock kitchens that only shows recipes you can make with what you currently have in your inventory.
- [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) - Reduce resource usage while Minecraft is in the background or idle.
- [Enhanced Block Entities](https://modrinth.com/mod/ebe) - Reduce block entity FPS lag with almost no compromises, and improve their visuals
- [Fabric API](https://modrinth.com/mod/fabric-api) - Lightweight and modular API providing common hooks and intercompatibility measures utilized by mods using the Fabric toolchain.
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) - This is a mod that enables usage of the Kotlin programming language for Fabric mods.
- [Forge Config API Port](https://modrinth.com/mod/forge-config-api-port) - NeoForge's & Forge's config systems provided to other modding ecosystems. Designed for a multiloader architecture.
- [Friends&Foes (Fabric/Quilt)](https://modrinth.com/mod/friends-and-foes) - Adds outvoted and forgotten mobs from the mob votes in a believable vanilla plus style. (Copper Golem, Glare, Moobloom, Iceologer, Barnacle, Wildfire, Illusioner, Rascal, Tuff Golem)
- [Friends&Foes - Flowery Mooblooms (Fabric/Quilt)](https://modrinth.com/mod/friends-and-foes-flowery-mooblooms-fabric) - An addon for the Friends&Foes mod, adding one moobloom variant for each flower.
- [Geckolib](https://modrinth.com/mod/geckolib) - A 3D animation library for entities, blocks, items, armor, and more!
- [Inventory Profiles Next](https://modrinth.com/mod/inventory-profiles-next) - Take control over you inventory. Sort. Move matching Items. Throw all. Locked slots. Gear sets! And much more.
- [Iris Shaders](https://modrinth.com/mod/iris) - A modern shaders mod for Minecraft intended to be compatible with existing OptiFine shader packs
- [Just Enough Items](https://modrinth.com/mod/jei) - JEI - View Items and Recipes
- [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights) - A dynamic lights mod for Fabric.
- [Lithium](https://modrinth.com/mod/lithium) - No-compromises game logic/server optimization mod
- [Mod Menu](https://modrinth.com/mod/modmenu) - Adds a mod menu to view the list of mods you have installed.
- [Mythic Mounts](https://modrinth.com/mod/mythic-mounts) - Befriend legendary creatures to accompany you across the world!
- [Naturalist](https://modrinth.com/mod/naturalist) - Adds new immersive wildlife with realistic behavior!
- [No Chat Reports](https://modrinth.com/mod/no-chat-reports) - Makes chat unreportable (where possible)
- [Obscure API](https://modrinth.com/mod/obscure-api) - Auxiliary Library
- [Patchouli](https://modrinth.com/mod/patchouli) - Accessible, Data-Driven, Dependency-Free Documentation for Minecraft Modders and Pack Makers
- [Physics Mod](https://modrinth.com/mod/physicsmod) - Welcome to a more destructive Minecraft than you've ever seen before!
- [Resourceful Config](https://modrinth.com/mod/resourceful-config) - Resourceful Config is a mod that allows for developers to make cross-platform configs
- [Resourceful Lib](https://modrinth.com/mod/resourceful-lib) - Resourceful Lib
- [Shulker Box Tooltip](https://modrinth.com/mod/shulkerboxtooltip) - View the contents of shulker boxes from your inventory
- [Sodium](https://modrinth.com/mod/sodium) - A modern rendering engine for Minecraft which greatly improves performance
- [Stellarity](https://modrinth.com/mod/stellarity) - Extreme rehaul and expansion of The End! 'We have End Update at home.'
- [Trinkets](https://modrinth.com/mod/trinkets) - A data-driven accessory mod
- [Waystones](https://modrinth.com/mod/waystones) - Teleport back to activated waystones. For Survival, Adventure or Servers.
- [Wilder Wild](https://modrinth.com/mod/wilder-wild) - This mod aims to upgrade the Wild Update!
- [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap) - Displays a map of the nearby world terrain, players, mobs, entities in the corner of your screen. Lets you create waypoints which help you find the locations you've marked.
- [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map) - Adds a full screen world map which shows you what you have explored in the world. Works great together with Xaero's Minimap.
- [libIPN](https://modrinth.com/mod/libipn) - Inventory Profiles Next GUI/Config library

</details>

## 辅助模组（Mod）

模组能提供许多好用的功能甚至改变整个游戏。

### [Fabric] AutoReconnector

如果在挂机时中途掉线，借助这个 Mod，就可以自动重连了。

支持 1.14.4 / 1.15.\* / 1.16.\* / 1.17.\* / 1.18.\* / 1.20.\* / 1.21.\* 。

- [论坛讨论 / 下载](https://community.craft.moe/d/1316)
- [Modrinth 下载地址](https://modrinth.com/mod/autoreconnector-fabric/versions)

### [Fabric] Iris :id=iris

兼容 OptiFine 光影包的开源光影模组，需与 Sodium 一同使用。当前支持 1.16.5 及以上版本。

- [官方网页](https://irisshaders.dev)
- FAQ、光影包兼容列表和 Iris 之限制可在[GitHub 页面](https://github.com/IrisShaders/Iris)查阅
- [Modrinth 下载地址](https://modrinth.com/mod/iris/versions)
- MC 百科上的[介绍](https://www.mcmod.cn/class/3697.html)

### [Fabric] Sodium :id=sodium

可以大幅提升游玩时的**帧率**，尤其在核芯（集成）显卡、入门独显平台上。当前支持 1.16.3 及以上版本。

- [GitHub 下载地址](https://github.com/jellysquid3/sodium-fabric/releases)
- [Modrinth 下载地址](https://modrinth.com/mod/sodium/versions)
- MC 百科上的[介绍](https://www.mcmod.cn/class/198.html)

!> **Optifine 和 Sodium 不兼容。** 使用本插件前，须先移除/禁用 OptiFabric 和 Optifine，反之亦然。  
除提高性能以外，其并不能取代 Optifine（包括光影、披风、资源包的额外特性等）。

### [Forge / Fabric / Quilt] Xaero's Minimap

原版外观的小地图，与 Xaero's World Map 一起使用，效果更佳。当前支持 1.7.10 及以上版本。

- [Modrinth 下载地址](https://modrinth.com/mod/xaeros-minimap/versions)
- MC 百科上的[介绍](https://www.mcmod.cn/class/1701.html)

## 资源包（材质）

- [Sphax PureBDCraft](https://bdcraft.net/purebdcraft-minecraft) —— 俗称“五边形”（需要付费获取最新版本）
- [Faithful](https://www.faithfulpack.net) —— 原版材质高清重制

## 光影包

- [BSL Shaders](https://bitslablab.com/bslshaders/)

## 皮肤

- [幻想乡人物皮肤](https://pan.baidu.com/s/1mgyq8mW)  by setomu@yuly
- 还有其它的吗？[在这里挑选！](https://www.minecraftskins.com/)

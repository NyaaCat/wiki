# NyaaUtils 粒子效果指南

[论坛讨论<sup>（存档截图）</sup>](/assets/images/legacy/nyaabbs/1165-20171113-nyaautils.webp ':ignore')

## 基本知识

### 粒子特效的类型

不同的粒子特效可以应用在不同的实体或状态，不能混用。已有的类型包括

- `PLAYER` - 玩家粒子特效，玩家飞行状态以外的状态下会持续产生此效果
- `ELYTRA` - 玩家飞行粒子特效，也就是之前的 ep 鞘翅轨迹
- `OTHER` - 其他弹射物的粒子特效，例如玩家射出的箭

### 偏移量

粒子是在玩家脚下生成的，设置偏移量可以让粒子生成范围更广。例如偏移量 `offsetY` 设置到 2 粒子会在玩家头顶生成（站立情况下

一般建议偏移量除 Y 以外，不要设置超过 1。

### 粒子效果列表

!> **此列表需要订正。**  
并不是所有的粒子效果都是在喵窝服务器被允许使用的，因此需要对其逐一进行测试。

（摘自 https://hub.spigotmc.org/javadocs/spigot/org/bukkit/Particle.html ）

```
BARRIER
BLOCK_CRACK
BLOCK_DUST
BUBBLE_COLUMN_UP
BUBBLE_POP
CAMPFIRE_COSY_SMOKE
CAMPFIRE_SIGNAL_SMOKE
CLOUD
COMPOSTER
CRIT
CRIT_MAGIC
CURRENT_DOWN
DAMAGE_INDICATOR
DOLPHIN
DRAGON_BREATH
DRIP_LAVA
DRIP_WATER
DRIPPING_HONEY
ENCHANTMENT_TABLE
END_ROD
EXPLOSION_HUGE
EXPLOSION_LARGE
EXPLOSION_NORMAL
FALLING_DUST
FALLING_HONEY
FALLING_LAVA
FALLING_NECTAR
FALLING_WATER
FIREWORKS_SPARK
FLAME
FLASH
HEART
ITEM_CRACK
LANDING_HONEY
LANDING_LAVA
LAVA
LEGACY_BLOCK_CRACK
LEGACY_BLOCK_DUST
LEGACY_FALLING_DUST
MOB_APPEARANCE
NAUTILUS
NOTE
PORTAL
REDSTONE
SLIME
SMOKE_LARGE
SMOKE_NORMAL
SNEEZE
SNOW_SHOVEL
SNOWBALL
SPELL
SPELL_INSTANT
SPELL_MOB
SPELL_MOB_AMBIENT
SPELL_WITCH
SPIT
SQUID_INK
SUSPENDED
SUSPENDED_DEPTH
SWEEP_ATTACK
TOTEM
TOWN_AURA
VILLAGER_ANGRY
VILLAGER_HAPPY
WATER_BUBBLE
WATER_DROP
WATER_SPLASH
WATER_WAKE
```

如果需要了解它们的效果，请戳 [这里](https://wiki.biligame.com/mc/%E7%B2%92%E5%AD%90)。

## 如何使用？

作为玩家——

### 查看已有的粒子效果组

```
/nu particle list [TYPE]
```

`TYPE` 即为上面的效果类型。例如查看鞘翅轨迹的列表，使用 `/nu particle list ELYTRA`

这会列出一堆玩家设置的粒子效果组，前面带有 ID。之后的操作，都需要这个 ID。

### 设置粒子效果

命令

```
/nu particle set [TYPE] [ID]
```

例如设置飞行轨迹的粒子效果为 ID 3 的效果，则

```
/nu particle set ELYTRA 3
```

### 如何清除

使用 `/nu particle set [TYPE] clear` 即可。

## 创建与删除

### 创建一个粒子效果组

```
/nu particle create [TYPE] [name]
```

例如设置为玩家应用的粒子效果组 `lover`

```
/nu particle create PLAYER lover
```

创建成功后会返回一个 Particle set ID 供之后的编辑使用

### 为粒子效果组添加粒子

```
/nu particle add [Particle set ID] [particle name] [amount] [frequency] [offsetX] [offsetY] [offsetZ] [extra]
```

ummm 难懂。那么一个个来解释。例如，为粒子效果组 `lover` （Particle set ID 为 2）添加粒子效果 `HEART`，即玩家会不停在身边生成爱心的形状。为了让粒子效果分散在玩家身边，需要以玩家脚底为中心设置偏移量。

该粒子将在每 20 tick (1s) 生成 5 个粒子，散布在玩家平面 0.6x0.6 的范围，高度 2.0 的范围，且不需要额外的选项。

```
/nu particle add 2 HEART 5 20 0.6 2.0 0.6 0
```

执行成功后，`lover` 效果组中会有一条粒子记录，其 index 为 0。

### 删除

emmm 添加错了，怎么办？

——删掉咯。

```
/nu particle remove [ID] [index]
```

即可删除特定 ID 中 `index` 的效果。如果不加 `index` 的值，则删除整个粒子效果组。

## 电脑性能差怎么办

```
/nu particle toggle
```

便不会再看到粒子特效。

**注意** 这只是对你不发送粒子特效，他人依然可以看到你的粒子特效。请不要使用过分影响视觉效果或令他人反感的粒子特效！

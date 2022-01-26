# 为 Wiki 定制的样式

由于 Docsify 原生样式尚存不足，本 Wiki 在其基础上，定制了若干文字样式，以丰富阅读体验。本页将重点介绍它们的用法。  
它们均存放于根目录下 `assets/css/common.css` 文件中。

Wiki 同时也对 Docsify 提供的“深色主题”样式进行了深度改良，并挂载于 `assets/css/dark.css`。“浅色”主题未有变动。

## 定制样式

!> **使用原则**

* **尽量优先使用 Markdown 和 HTML 的默认样式。**如果确实无法满足，再考虑使用这里的样式。
* 可供引用的样式数量应保持精简。
* 所有定制样式的类名，应以 `nw-` 开头，以免与 Docsify 内置的样式发生冲突。

下面列举出所有通用样式的示例使用方法。

### 常用样式

| 样式 | 在源文件中编辑 | 效果 |
| - | - | - |
| 隐藏的文本<br>当鼠标移动到 / 在触摸屏上点击该文本时，内容就会重现。 | `<span class="nw-spoiler">我藏起来啦</span>` | <span class="nw-spoiler">我藏起来啦</span> |
| 有着注释的文本 | `<span class="nw-explain" title="对于该词的解释内容">Chrome</span>` | <span class="nw-explain" title="包括其它基于 Chromium，且内核版本 ≧32 的浏览器">Chrome</span> |
| 重要的文本 | `<span class="nw-important">重要的文本</span>` | <span class="nw-important">重要的文本</span> |

### 不常用样式

| 样式 | 在源文件中编辑 | 效果 |
| - | - | - |
| 红色标注；<br />旧式近战武器 | `<span class="nw-mark-red">红色标注</span>` | <span class="nw-mark-red">红色标注</span> |
| 绿色标注；<br />旧式远程武器 | `<span class="nw-mark-green">绿色标注</span>` | <span class="nw-mark-green">绿色标注</span> |
| 蓝色标注；<br />旧式魔法武器 | `<span class="nw-mark-blue">蓝色标注</span>` | <span class="nw-mark-blue">蓝色标注</span> |
| 黄色标注；<br />旧式召唤武器 | `<span class="nw-mark-yellow">黄色标注</span>` | <span class="nw-mark-yellow">黄色标注</span> |
| 紫色标注；<br />原 T4 怪物及武器 | `<span class="nw-mark-purple">紫色标注</span>` | <span class="nw-mark-purple">紫色标注</span> |

> 注：<span class="nw-important">重要的文本</span>是<span class="nw-mark-red">红色标注</span>的加粗型。

## 深色主题样式

<details>
<summary>关于深色模式，以及为何改良</summary>

我们的愿望很简单：**当不希望有灯光闪瞎眼的时候，Wiki 最好也跟着调暗**。然而，现行的 Docsify 4.x 版本，并无自动切换主题的功能。所幸一行“魔术”代码，勉强解决了燃眉之急。

受此局限，「深色模式」只会在**浏览器已处于「深色」主题模式**时自动、强制启用。浏览器版本须不早于：
- Chrome 76
- Firefox 67
- 新版、也即蓝绿配色的 Microsoft Edge
- iOS 13、Android 10 的内置浏览器

我们相信 Docsify 提供的深色主题样式是 100% 能用的，但怎奈其表现过于[拉跨](https://docsify.js.org/#/themes "可在此自行体验")……据开发者透露，Docsify 5.x 推出后会正式整合深色模式；但在此之前<sup>（目前仍使用 4.x 版本）</sup>，只能自力更生丰衣足食了。

</details>

定制工作主要集中在**配色**上。为便于维护，已改动的样式被移至 `dark.css` 文件前列。感兴趣者可在本地环境下尝试修改。  
有任何改进意见的，欢迎在[论坛帖子](https://bbs.nyaa.cat/d/1700)中提出。
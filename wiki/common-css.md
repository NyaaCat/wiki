# 通用样式

Wiki 根目录下 `assets/css/common.css` 文件中，保存着各种在 NyaaWiki 常用的部分 CSS 样式。

## 原则

* **尽量优先使用 Markdown 和 HTML 的默认样式。**如果确实无法满足，再考虑使用这里的样式。
* 可供引用的样式数量应保持精简。
* 所有类名应该以 `nw-` 开头，以免与 Docsify 的某些样式发生冲突。

## 通用样式

下面列举出所有通用样式的示例使用方法：

| 样式 | HTML 代码 | 效果 |
| - | - | - |
| 隐藏的文本<br>当鼠标移动到 / 在触摸屏上点击该文本时，内容就会重现。 | `<span class="nw-spoiler">我藏起来啦</span>` | <span class="nw-spoiler">我藏起来啦</span> |
| 有着注释的文本 | `<span class="nw-explain" title="对于该词的解释内容">Chrome</span>` | <span class="nw-explain" title="包括其它基于 Chromium，且内核版本 ≧32 的浏览器">Chrome</span> |
| 重要的文本 | `<span class="nw-important">重要的文本</span>` | <span class="nw-important">重要的文本</span> |

### 不常用样式

| 样式 | HTML 代码 | 效果 |
| - | - | - |
| 【Inf】T1 怪物或武器 | `<span class="nw-inf-t1">T1</span>` | <span class="nw-inf-t1">T1</span> |
| 【Inf】T2 怪物或武器 | `<span class="nw-inf-t2">T2</span>` | <span class="nw-inf-t2">T2</span> |
| 【Inf】T3 怪物或武器 | `<span class="nw-inf-t3">T3</span>` | <span class="nw-inf-t3">T3</span> |
| 【Inf】T4 怪物或武器 | `<span class="nw-inf-t4">T4</span>` | <span class="nw-inf-t4">T4</span> |
| 【Inf】T5 怪物或武器 | `<span class="nw-inf-t5">T5</span>` | <span class="nw-inf-t5">T5</span> |
| 【Inf】T5+ 怪物或武器 | `<span class="nw-inf-t5p">T5+</span>` | <span class="nw-inf-t5p">T5+</span> |
| 【Inf】近战武器 | `<span class="nw-inf-red">近战武器</span>` | <span class="nw-inf-red">近战武器</span> |
| 【Inf】远程武器 | `<span class="nw-inf-green">远程武器</span>` | <span class="nw-inf-green">远程武器</span> |
| 【Inf】魔法武器 | `<span class="nw-inf-blue">魔法武器</span>` | <span class="nw-inf-blue">魔法武器</span> |
| 【Inf】召唤武器 | `<span class="nw-inf-gold">召唤武器</span>` | <span class="nw-inf-gold">召唤武器</span> |

# 参与贡献 Wiki

NyaaWiki 采用 [Docsify](https://docsify.js.org) 构建，源文件存放于 [GitHub](https://github.com/NyaaCat/wiki)。

### 参与要求

- 了解 Markdown、CommonMark 和 Github Flavored Markdown 语法。
- 了解 Git 的基本用法，能够解决简单的文件冲突。
- 有较好的文字表达能力。
- 了解 NyaaCat 社区和喵窝服务器的内容。

### 文件结构

- `index.html` - 用于设置 Docsify 的各项参数，如无必要请勿修改。
- `README.md` - Wiki 主页内容。
- `_navbar.md` - 导航栏，如无必要请勿修改。
- `_sidebar.md` - 侧边栏，如果新增较重要的页面可在这里做相应的修改。
- `_404.md` - 404 页面，如无必要无需修改。
- `changelog.md` - 近期的改动记录。
- `assets` - 各种静态文件目录。图片等文件请放在这里再引用。
- 分类目录说明
  - `wiki` - 各类基础信息，规则、说明性文本等。
  - `nyaa` - 喵窝世界的各项设定、村落、经济、工程等等。
  - `space` - 玩家贡献的各类内容。
  - `tutorial` - 玩家贡献的各种教程。
  - `misc` - 各类杂项信息页面。
  - `inf` - "Infinite Infernal" 子服务器相关内容。
  - `nfs` - "Need For Speed" 子服务器相关内容。
  - `pvp` - "PVP" 子服务器相关内容。
  - `miu` - "美羽实验室" 子服务器相关内容。
- 如果有额外的详细信息页面，例如[城镇村落](nyaa/realms.md)上的村落详细信息，还可以在以上对应目录中新建目录来整理。例如[琥珀川](nyaa/realm/kohakukawa.md)的独立页面。

### 编辑说明

0. **所有文本都必须使用 UTF-8 编码**
1. 编辑或新建页面时，应保持文件结构正确、整洁。
2. 文件和目录命名保持简洁，文件名应只包含英文、数字、短线（`-`）。
3. Wiki 内的链接应使用相对路径，并注意检查引用路径是否正确。
4. 请勿滥用 heading 语法。
  - 页首标题使用一级 heading
  - 大段 section 使用二级或三级 heading
  - 小节使用四级以下 heading
4. 并不是所有的页面都要列如侧边栏。一些详细内容的页面也可以存放在相应目录下并通过其他页面访问。

(WIP)

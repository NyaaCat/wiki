# 参与贡献 Wiki

NyaaWiki 采用 [Docsify](https://docsify.js.org) 构建，源文件存放于 [GitHub](https://github.com/NyaaCat/wiki)。

### 参与要求

- 了解 Markdown、CommonMark 和 Github Flavored Markdown 语法。
- 了解 Git 的基本用法，能够解决简单的文件冲突。
- 有较好的文字表达能力。
- 了解 NyaaCat 社区和喵窝服务器的内容。

### 参与方式

##### 加入 Collaborators

如果你能够熟练使用 Git 和 Markdown 语法，并且能灵活处理各种路径和文件问题，即可以申请加入 Collaborators 获得直接写权限。

向 NyaaCat 管理组或开发组申请加入本 repo 的 Collaborators，确认邀请后即可直接编辑 repo 内的文件。

##### 提交 PR

如果你尚不熟悉 Git 操作或 Markdown 语法，但是希望参与贡献，可以 fork 本 repo 或直接在相应页面上方点击 "Edit on Github" 来编辑。

完成后，访问本 repo 并提交 Pull Request (PR)。协作者将 review 所有变更，如无问题，即可合并进本 repo。

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
  - `space` - 玩家贡献的各类内容。玩法、心得、各类整理的信息可以放在这里。
  - `tutorial` - 玩家贡献的各种教程。这里指的是手把手式、非常 case specific 的教程，而非一般的通用教学和知识整理。
  - `misc` - 各类杂项信息页面。
  - `inf` - "Infinite Infernal" 子服务器相关内容。
  - `nfs` - "Need For Speed" 子服务器相关内容。
  - `pvp` - "PVP" 子服务器相关内容。
  - `miu` - "美羽实验室" 子服务器相关内容。
- 如果有额外的详细信息页面，例如[城镇村落](nyaa/realms.md)上的村落详细信息，还可以在以上对应目录中新建目录来整理。例如[琥珀川](nyaa/realms/kohakukawa.md)的独立页面。

### 编辑说明

1. **所有文本都必须使用 UTF-8 编码** 推荐使用 [VS Code](https://code.visualstudio.com/) 编辑器。
2. 编辑或新建页面时，应保持文件结构正确、整洁。
3. 文件和目录命名保持简洁，文件名应只包含英文、数字、短线（`-`）。
4. Wiki 内的链接应使用相对路径，并注意检查引用路径是否正确。
5. 文本排版保持简洁、美观。中文和西文、数字之间要有空格。
5. 请勿滥用 heading 语法。
  - 页首标题使用一级 heading
  - 章节/section 使用三级 heading（如希望侧边栏自动展开 table of contents，则需要使用二级 heading）
  - 小节使用五级以下 heading
6. 并不是所有的页面都要列如侧边栏。一些详细内容的页面也可以存放在相应目录下并通过其他页面访问。
7. 由于托管在 GitHub 的特殊性，请尽量不要上传大文件。图片如无必要，请使用 JPG 而非 PNG 并使用 mozjpeg 进行压缩。其他大文件、静态文件请使用稳定可靠的文件托管外链服务。

(WIP)

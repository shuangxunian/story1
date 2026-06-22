# 项目地图

这个项目同时保留两套层级：

- `pages/`：当前正文的页级写作区。每章按 `chXX/NNN.md` 拆成小节，便于增补、重排和局部修订。
- `story.md`：全书主索引，记录题材、视角、章节状态和主线拆纲。
- `docs/`：作者可直接阅读的辅助文档，包括总纲、章节纲、人物、连续性、时间线和修订记录。
- `settings/`：awesome-novel 标准设定区，包括世界观、题材、文风、角色设定。
- `chapters/`：awesome-novel 标准章纲区，目前第三章已有标准章纲文件。
- `volumes/`：awesome-novel 标准卷纲区，用于沉淀卷级主线和节奏。
- `prompts/`：awesome-novel 标准提示词区，用于保存正式写作前的提示词包。
- `archives/`：awesome-novel 标准归档区，用于保存整章草稿、定稿或归档版本。
- `.agent/`：工作流状态区，记录当前 phase、章节和下一步任务。
- `.claude/`：工作流隐藏目录，包含 agents、skills、knowledge、memory。因为目录名以点开头，在 Finder 或部分文件树里默认隐藏。

## 当前正文状态

- 第一章：`pages/ch01/001.md`-`063.md`
- 第二章：`pages/ch02/001.md`-`065.md`
- 第三章：`pages/ch03/001.md`-`150.md`

第三章已补齐 150 节，下一步是反 AI 通读、衔接检查与读者评审。

## 为什么之前看不到部分辅助目录

Git 不会追踪空目录。`volumes/`、`prompts/`、`archives/` 在本地存在，但如果没有文件，提交到 GitHub 后不会显示。现在这些目录会放入 README 或正式文档，后续在仓库里就能看见。

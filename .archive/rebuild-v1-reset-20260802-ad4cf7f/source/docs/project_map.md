# 项目地图

这个项目按 awesome-novel 标准结构组织：

- `archives/`：正文 canonical 归档区。每章以 `vol-{N}-ch-{M}-{slug}.md` 或 `.draft.md` 保存整章版本，writer/updater 流程以这里为准。
- `story.md`：全书主索引，记录题材、视角、章节状态和主线拆纲。
- `docs/`：作者可直接阅读的辅助文档，包括总纲、章节纲、人物、连续性、时间线和修订记录。
- `settings/`：awesome-novel 标准设定区，包括世界观、题材、文风、角色设定。
- `chapters/`：awesome-novel 标准章纲区，目前第三章已有标准章纲文件。
- `volumes/`：awesome-novel 标准卷纲区，用于沉淀卷级主线和节奏。
- `prompts/`：awesome-novel 标准提示词区，用于保存正式写作前的提示词包。
- `.agent/`：工作流状态区，记录当前 phase、章节和下一步任务。
- `.claude/`：工作流隐藏目录，包含 agents、skills、knowledge、memory。因为目录名以点开头，在 Finder 或部分文件树里默认隐藏。

## 当前正文状态

- 第一章：`archives/vol-1-ch-1-jing.md`
- 第二章：`archives/vol-1-ch-2-xinhao.md`（120节修订版，当前真相源）
- 第三章：`archives/vol-1-ch-3-huisheng.md`（旧稿待按新版第二章返修）
- 第四章：`archives/vol-1-ch-4-huise.md`（待第三章重接后复核）
- 第五章：`archives/vol-1-ch-5-lihen.md`（待第三章重接后复核）
- 第六章：`archives/vol-1-ch-6-shenyuan.md`（待第三章重接后复核）
- 第七章：`archives/vol-1-ch-7-huixiang.md`（待第三章重接后复核）

第2章修订版已收口到 `archives/`。当前状态见 `.agent/status.md`，下一步是按新版第二章章末钩子返修第三章《回声》。

## 为什么之前看不到部分辅助目录

Git 不会追踪空目录。`volumes/`、`prompts/`、`archives/` 在本地存在，但如果没有文件，提交到 GitHub 后不会显示。现在这些目录会放入 README 或正式文档，后续在仓库里就能看见。

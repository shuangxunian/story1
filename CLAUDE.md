# 小说项目

## 写作流程

本项目使用 awesome-novel 工作流：设定 → 卷纲 → 章纲 → 提示词 → 正文 → 验收 → 归档。

当前处于 `reset-v2 / setup`：正文从第一章重新开始。先通过 `@novel-agent` 与作者确认设定，再按标准 agent 链推进。

## 资料边界

- `rebuild/reset-v2/`：当前重置的权威入口、确认记录和验收门禁。
- `.archive/`：重置前历史快照。除非作者明确要求历史比对或恢复演练，普通 agent 禁止读取；其中任何资料不得作为 canon 或写作输入。
- `archives/`：仅保存 reset-v2 通过验收后的活动正文。
- `settings/`、`volumes/`、`chapters/`、`prompts/`、`.claude/memory/`：仅保存 reset-v2 后建立的活动资料。

不得续写旧第九章，不得使用旧第一章候选、clean baseline、001—006 或 019—022 批次作为活动正文基线。

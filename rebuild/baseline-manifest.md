# rebuild-v1 基线清单

- Git 基线：`ad4cf7fa49797021c5a57d3516b6ac744c6b7ce6`
- 建立日期：2026-07-27
- 清单范围：现有 archive、outline、prompt、docs 的路径及分类；另列本次 order 指定的辅助资料类别。
- 判定：所有列出的旧 archive 与旧 docs 均为**保留参考，不是自动 canon**。

## Archive：正文证据（保留参考）

- `archives/README.md` — 存档说明
- `archives/vol-1-ch-1-jing.md` — 第 1 章旧正文
- `archives/vol-1-ch-2-xinhao.md` — 第 2 章旧正文
- `archives/vol-1-ch-3-huisheng.md` — 第 3 章旧正文
- `archives/vol-1-ch-4-huise.md` — 第 4 章旧正文
- `archives/vol-1-ch-5-lihen.md` — 第 5 章旧正文
- `archives/vol-1-ch-6-shenyuan.md` — 第 6 章旧正文
- `archives/vol-1-ch-7-huixiang.md` — 第 7 章旧正文
- `archives/vol-1-ch-8-fenlie.md` — 第 8 章旧正文
- `archives/vol-1-ch-9-daojishi.draft.md` — 第 9 章进行中草稿（001—054）

## Outline：规划资料（不单独确立 canon）

- `chapters/vol-1-ch-3-150.md` — 第 3 章 150 节版本
- `chapters/vol-1-ch-3-70.md.bak` — 第 3 章 70 节备份
- `chapters/vol-1-ch-3.md` — 第 3 章章纲
- `chapters/vol-1-ch-4.md` — 第 4 章章纲
- `chapters/vol-1-ch-5.md` — 第 5 章章纲
- `chapters/vol-1-ch-6.md` — 第 6 章章纲
- `chapters/vol-1-ch-7.md` — 第 7 章章纲
- `chapters/vol-1-ch-8.md` — 第 8 章章纲
- `chapters/vol-1-ch-9.md` — 第 9 章章纲

## Prompt：规划资料（执行指令痕迹，不单独确立 canon）

- `prompts/README.md` — 提示词说明
- `prompts/vol-1-ch-3-prompt.md` — 第 3 章提示词
- `prompts/vol-1-ch-4-prompt.md` — 第 4 章提示词
- `prompts/vol-1-ch-5-prompt.md` — 第 5 章提示词
- `prompts/vol-1-ch-6-prompt.md` — 第 6 章提示词
- `prompts/vol-1-ch-7-prompt.md` — 第 7 章提示词
- `prompts/vol-1-ch-8-prompt.md` — 第 8 章提示词
- `prompts/vol-1-ch-9-prompt.md` — 第 9 章提示词

## Docs：历史文档（保留参考）

- `docs/chapter01_outline.md` — 第 1 章旧章纲
- `docs/chapter02_outline.md` — 第 2 章旧章纲
- `docs/chapter02_revision_plan.md` — 第 2 章修订计划
- `docs/chapter03_anti_ai_scan.md` — 第 3 章反 AI 扫描
- `docs/chapter03_outline.md` — 第 3 章旧章纲
- `docs/chapter04_outline.md` — 第 4 章旧章纲
- `docs/characters.md` — 角色资料
- `docs/continuity.md` — 连续性记录
- `docs/early_chapter_revision_plan.md` — 前期章节修订计划
- `docs/outline.md` — 旧版总纲
- `docs/project_map.md` — 项目地图
- `docs/revision_notes.md` — 修订说明
- `docs/story_structure.md` — 故事结构
- `docs/timeline.md` — 旧时间线

## 辅助资料类别

| 类别 | 路径 | rebuild-v1 用途 |
| --- | --- | --- |
| 主线索引 | `story.md` | 当前章节目标和承接关系的工作假设 |
| 现行设定 | `settings/` | 当前世界、角色、题材、风格、时间线的工作假设 |
| 流程状态 | `.agent/status.md` | 进度判断，不确立剧情 canon |
| 动态记忆 | `.claude/memory/` | 作者反馈与流程线索，不确立剧情 canon |
| 外部计划 | `02-写作计划.json` | 历史计划线索，需与上层资料核对 |

## 创建的重构容器

- `rebuild/changes/` — 后续已确认的 rebuild-v1 改动记录位置；本次初始化未写入任何变更。

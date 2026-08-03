# rebuild-v1 矛盾台账

## 使用规则

本文件只登记已识别的资料冲突或需作者裁决的权威性问题；不在此文件中擅自裁决。每条应说明来源、冲突内容、影响范围和作者决定。

## 初始条目

| ID | 状态 | 问题 | 涉及资料 | 所需裁决 |
| --- | --- | --- | --- | --- |
| RBLD-001 | 待裁决 | 旧 archive 与旧 docs 的资料地位均为保留参考，不能因既有内容而自动视为 rebuild-v1 canon。 | `archives/`、`docs/` | 后续按议题明确确认、替换或废弃。 |
| RBLD-002 | 已解决 | 当前主线索引将第 8—10 章标注为“待规划”，而状态文件记录第 9 章已有 001—054 草稿。 | `story.md`、`.agent/status.md`、`archives/vol-1-ch-9-daojishi.draft.md` | [作者已确认；来源：`.agent/task/setting-update-order.md`] 第 9 章草稿与章纲定性为 `legacy-reference / rewrite-input`：保留倒计时、分片、“回应不能由一个人完成”核心价值与群像日常锚点，以新版第 1—8 章和第 10 章终局为准整体重写；不可直接续写或视为 canon。 |

## 解决记录

| ID | 作者决定 | 影响文件 | 保留未决细节 |
| --- | --- | --- | --- |
| RBLD-002 | 第 9 章草稿与章纲是 `legacy-reference / rewrite-input`，不可自动采纳或直接续写；只保留倒计时、分片、“回应不能由一个人完成”及群像日常锚点，并依新版第 1—8 章和第 10 章终局整体重写。 | `rebuild/canon-event-matrix.md`、`rebuild/chapter-spec-matrix.md`、`settings/foreshadowing.md` | 倒计时机制与归零后果、六小时读数、最终回应规则及第 10 章接口。 |
| RBLD-003 | 第 1 章按约 70 节重构；第 2—10 章均按 120 节重构。 | `rebuild/canon-event-matrix.md`、`rebuild/chapter-spec-matrix.md` | 终章标题与具体终局结构。 |
| RBLD-004 | P-21 是独立旧实验受害者／对象；苏晚为另一条平行受害者线。终章必须分别回应，任一线不得吞并、替代或简化另一线。 | `rebuild/canon-event-matrix.md`、`rebuild/world-rule-ledger.md`、`settings/foreshadowing.md` | P-21 的实体性质、苏晚完整经历、两线各自的回应方式与结局状态。 |
| RBLD-005 | 倒计时归零会将人、记忆和关系压缩为可调用的“稳定记录”；终局使 P-21 与苏晚不再被系统作为记录处理。第 10 章标题定为《未命名》。苏晚仍活着但被隔离／隐匿，并在终局获得不被系统命名和利用的选择；保留重逢余地，不强行团圆。 | `rebuild/canon-event-matrix.md`、`rebuild/world-rule-ledger.md`、`rebuild/character-state-matrix.md`、`rebuild/chapter-spec-matrix.md`、`settings/foreshadowing.md` | 稳定记录的具体机制；P-21 与苏晚各自被机制卷入的具体过程；终局执行、两线具体回应和场景安排。 |
| RBLD-006 | rebuild-v1 第一章的已有章纲、提示词及正文 001—006 可作为重构工作线的受控续写基线；旧第一章归档、旧 `story.md` 概述和 `.agent/raw/` 快照只作冲突检查或历史参考，不得自动回填新正文。 | `chapters/vol-1-ch-1.md`、`prompts/vol-1-ch-1-prompt.md`、`archives/vol-1-ch-1-jing.rebuild-v1.draft.md`、`.agent/raw/vol-1-ch-1-jing.rebuild-v1.draft.md`、`story.md`、旧 `archives/` | 第一章完整草稿完成后的读者验收与归档裁决。 |

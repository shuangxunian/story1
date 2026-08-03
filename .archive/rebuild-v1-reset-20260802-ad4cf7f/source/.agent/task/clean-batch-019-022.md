# 第一章干净基线批次019—022 order

- **mode:** clean-batch-draft-only
- **source:** `rebuild/vol-1-ch-1-jing.clean-baseline.draft.md`
- **write_target:** 只能写入 `rebuild/batches/ch1-019-022.draft.md`，不得直接修改任何 `archives/` 文件。
- **canonical_inputs:** `chapters/vol-1-ch-1.md`、`prompts/vol-1-ch-1-prompt.md`、`settings/writing-style.md`、`settings/genre-setting.md`、`volumes/volume-1.md` 第一章内容。
- **locked_context:** 001—018作为前情只读；019—022从零重写；023以后不读取、不改动。
- **required_sections:** 标题必须严格为 `019｜体温`、`020｜白纸`、`021｜电话`、`022｜限制`，正文中禁止把节标题覆盖成散文段落。
- **linear_canon:**
  - 019：林时仍在昨夜临时据点，体温/灰纹/耳鸣未退；顾铮只给已确认事实，林时追问夜巷。
  - 020：许岚到场，给有限选项：受监护回出租屋取物后观察，或接受记忆处理/回原生活；保护和控制并置，不讲后期机制。
  - 021：林时在受限条件下给母亲打电话/回消息，不能说明地点和真相；不提前回出租屋。
  - 022：次日上午真正从据点出发，受监护抵达出租屋楼下/巷口；许岚和顾铮在外等待，林时准备上楼取物，结尾接023收拾。
- **canonical_characters:** 林时（运维实习生，男性）；母亲（电话/消息）；许岚；顾铮。不得出现林诗、林识、何明、顾峥、徐岚、学生/高二/十七岁、地下车库/旧物流楼、其他项目场景。
- **length:** 每节1800—2300汉字，最多16个非空段落，自然正文，不占位、不编号填充、不重复。
- **output_validation:** 生成后只报告文件路径、逐节字数、标题、角色/禁名扫描；未经主流程复核不得写入archive。

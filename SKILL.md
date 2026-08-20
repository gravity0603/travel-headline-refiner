---
name: travel-headline-refiner
description: Refine, rewrite, or evaluate Chinese travel, scenery, geography, architecture, and destination headlines in the lively reference style. Use when a user asks to modify travel titles, make travel headlines more eye-catching or colloquial, match the style of 旅行类标题参考.csv, or provide several short headline alternatives for travel-lock-screen content.
---

# 旅行标题优化

将旅行内容标题改写为“好奇提问 + 反差/拟人化 + 具体奇观”的短标题。先读 `references/style-guide.md`；涉及事实、地点、数据或“唯一/最”等绝对表述时，先核验或改为待核验措辞。

## 工作流程

1. 提取素材中的地点、主角、可感知画面和真正的奇特点；没有明确奇点时，先向用户索取素材，不凭空编造。
2. 从参考句式中选 1–3 种，优先写具体反差、异常现象或生活化联想；同批标题避免同一开头和同一句式重复。
3. 输出 5–10 个候选（用户指定数量时从其要求），每条单独一行。默认不加解释；如需，附 1 条“推荐：”并简短说明理由。
4. 自检：自然、短、能一眼看懂；不为吸睛制造虚假事实；不用恐慌、贬损、擦边或标题党式误导。

## 硬性要求

- 默认控制在 8–16 个汉字左右；需要适配锁屏时优先更短。
- 保留一个核心信息点，不把地点、背景、结论全部塞进标题。
- `？` 用于真实悬念或反常识；`！` 仅用于明确且可信的强奇观；避免连续标点。
- 引号只突出一个具象拟人词、俗称或反差词，例如“巨眼”“变脸”“大冰箱”。
- 使用口语化中文，但避免网络烂梗、堆叠形容词、空泛“震撼/绝美/必去”。
- 不擅自使用“世界第一”“唯一”“最”“UFO”“外星人”“消失”等无法确认的表述；可改写成“像……”“传说中……”“疑似……”并标出待核验。

## 输出模式

- **改写已有标题**：保留原意，给出更像参考表的版本；不要改写成与素材无关的新选题。
- **根据素材拟标题**：先保证地点和现象准确，再给多样候选。
- **审核标题**：标出“可用 / 需弱化 / 需核验”，并给可直接替换的一版。

## 参考

完整规律、句式和已整理的样本见 [references/style-guide.md](references/style-guide.md)。

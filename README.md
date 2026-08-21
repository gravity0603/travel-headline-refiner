# travel-headline-refiner

一个用于优化中文旅行、风光、地理、建筑和目的地标题的 Skill。

## 内容

- `SKILL.md`：Skill 入口、任务类型判断、事实核验和输出流程
- `references/style-guide.md`：旅行类标题风格指南
- `agents/openai.yaml`：界面显示配置

## 主要行为

- 纯改写已有标题时，只优化表达，不新增事实或启动新选题流程。
- 根据素材拟题或批量生成候选时，先核验事实，并区分 `[已验证]` 与 `[待验证]`。
- 含疑问或悬念结构的标题必须使用中文问号 `？`。
- 找不到可核验来源时如实说明，不伪造链接或核验结果。

将整个 `travel-headline-refiner` 目录放入 Agent 的 skills 目录即可使用。

# AI Practice Kit

用真实任务积累 AI 使用经验，把反复奏效的方法整理成可复制的提示词和可复用的 Skills。

| 目录 | 适用场景 | 首批内容 |
| --- | --- | --- |
| `experience/` | 查阅实践方法、适用条件和验证步骤 | [AI 协作调试：先判断失败能否复现](experience/verify-before-fixing.md) |
| `skills/` | 给支持 `SKILL.md` 的智能体加载完整工作流程 | [高质量 PDF 制作](skills/high-quality-pdf/SKILL.md) · [逐页验收细则](skills/high-quality-pdf/references/pdf-review.md) |
| `prompts/` | 复制提示词完成一次具体任务 | [中文教学 PDF](prompts/chinese-pdf.md) |

## 实践索引

- [先查根因，再决定改哪里](experience/trace-root-causes.md) · 用构建产物异常变大演示如何定位问题。
- [用验收结果衡量长任务执行力](experience/long-running-delivery.md) · 定义完成条件、诊断失败、恢复执行、交付可验证成果。
- [先核对工具规则，再解释现象](experience/evidence-first.md) · 区分观察、推断和不确定之处。
- [AI 协作系统提示词](prompts/system-prompt.md) · 汇总长期适用的判断、执行、学习和交付规则。
- [让 AI 排查根因并交付验证结果](prompts/ai-debug-and-deliver.md) · 可直接填入项目背景和验收条件。

## 更多实践

- [按阶段分配模型与工具](experience/model-routing-and-handoff.md)
- [独立探索与多智能体汇总](experience/independent-exploration.md)
- [研发立项、实验与产品形态](experience/research-and-project-scope.md)
- [游戏中的贴图、教程与界面空间](experience/game-ui-and-art.md)
- [用 AI 提示、诊断和复测](experience/ai-assisted-learning.md)

## 开始使用

- 用提示词时，复制正文并替换方括号内的字段。
- 用 Skill 时，将包含 `SKILL.md` 和 `references/` 的完整目录导入支持 Agent Skills 的工具，或按该工具的技能目录约定放置。使用时可明确指定 `high-quality-pdf`。
- 新增经验时，注明场景、条件、结果和复验方法。新增提示词时，写清输入和输出。新增 Skill 时，保留必要的步骤和验收标准。

## 许可证

[MIT](LICENSE)


## 前端设计能力训练

通过真实题目训练产品理解、视觉审美、交互设计和前端工程能力，严格执行“先生成效果图 → 用户审查 → 前端实现 → 浏览器验收 → 截图交付 → 用户批评 → 提示词进化”的闭环。

- [训练总览与目录](frontend-training/README.md)
- [前端设计原则](frontend-training/DESIGN_PRINCIPLES.md)
- [主训练提示词 V1.0](frontend-training/PROMPT_V1.md)
- [统一评分标准](frontend-training/evaluation-rubric.md)
- [训练总台账](frontend-training/training-log.md)

每轮必须保留原始题目、效果图、真实运行截图、测试证据、用户原始批评、根因分析和提示词版本差异。

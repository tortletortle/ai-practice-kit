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
- [让 AI 排查根因并交付验证结果](prompts/ai-debug-and-deliver.md) · 可直接填入项目背景和验收条件。

## 开始使用

- 用提示词时，复制正文并替换方括号内的字段。
- 用 Skill 时，将包含 `SKILL.md` 和 `references/` 的完整目录导入支持 Agent Skills 的工具，或按该工具的技能目录约定放置。使用时可明确指定 `high-quality-pdf`。
- 新增经验时，注明场景、条件、结果和复验方法。新增提示词时，写清输入和输出。新增 Skill 时，保留必要的步骤和验收标准。

## 许可证

[MIT](LICENSE)

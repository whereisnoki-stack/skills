# Ambition Upshift｜AI 野心升级器

**一个让 AI 不止完成任务，还能重新定义问题、发现新机会、验证大胆假设的中文 Skill。**

适合创业者、投资人、研究者、产品经理和希望把 AI 用得更深入的普通读者。无需任何脚本或 API Key；如有可用的研究工具、文件或数据连接，效果更好。

## 一分钟上手

**方式 A｜任何聊天 AI（包括普通 ChatGPT 对话）**

打开 [`PROMPT.md`](PROMPT.md)，复制其中的完整启动提示词，粘贴给 AI，再附上自己正在做的事情。这是“复制提示词使用”，不是在 ChatGPT 中自动安装本地 Skill。

你可以这样开始：

> 我正在做一份 AI 创业公司的投资分析。请按照 Ambition Upshift 的 Altitude、Depth、Range 方法重新设计这项任务。不要只让我得到一份更长的报告，而要提高投资判断的质量；提出大胆但可验证的方案，并立刻做一项力所能及的工作。

**方式 B｜Claude Code**

把整个 `ambition-upshift` 文件夹放到 `~/.claude/skills/ambition-upshift/`（个人）或项目的 `.claude/skills/ambition-upshift/`。随后在 Claude Code 中输入：

`/ambition-upshift 帮我重新思考这件事：……`

**方式 C｜Codex / 支持 Agent Skills 的环境**

把文件夹放在项目的 `.agents/skills/ambition-upshift/`，并在对话中明确要求使用 `ambition-upshift`。不同应用支持的安装位置和调用方法可能有差异，按该应用的当前文档调整。

**方式 D｜Claude.ai 自定义 Skills**

支持自定义 Skills 的帐号可按应用设置上传本 ZIP 包。具体入口、可用性和权限以产品当前帮助文档为准。

## 五条可以反复使用的指令

- **升维**：“别先完成这个交付物。问问我究竟要改变什么现实，再升维一层。”
- **深挖**：“更深，不要更大。用顶尖专家的方法、最原始的材料重新做。”
- **跨界**：“把名词换成动词。还有哪些行业的哪些方法可以帮我们解决？”
- **证伪**：“什么证据最可能证明我们的想法是错的？设计最低成本的测试。”
- **开干**：“从你现在有权限的工具和信息出发，做第一轮可验证的工作，而不是继续 brainstorm。”

## 这个 Skill 的 3 个约束

**不空谈**：每一种升级必须对应具体方法、材料与行动。

**不自证**：AI 的判断不能替代现实世界的独立证据。

**不越权**：没有材料就说明缺口；涉及真实对外操作，先获得适当授权。

## 文件清单

- [`SKILL.md`](SKILL.md)：标准 Agent Skill 说明，直接可安装。
- [`PROMPT.md`](PROMPT.md)：方便文章读者复制到任何 AI 对话的中文版本。
- [`references/EXAMPLES.md`](references/EXAMPLES.md)：复盘、投资研究和创业产品的示例。

## 原始灵感

Felix Rieseberg, [*How to be more ambitious: A tutorial for humans with models*](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/)（2026 年 10 月 13 日）。

原文强调 Speed、Altitude、Depth、Range 四个维度；本 Skill 重点落实后三项，并增加工作流、执行、外部验证、权限及示例。这里是独立整理的可复用改编，并非原作者发布的官方 Skill。

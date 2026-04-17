# AI Interview Prompt Engineering Toolkit / AI外呼 Prompt 工程化工具包

This project includes 3 AI skills for end-to-end AI phone interview support. **Each skill asks the user to choose their language (English/中文) at the start, then adapts accordingly.**

本项目包含 3 个 AI 技能，用于 AI 电话外呼访谈的全流程支持。**每个技能启动时让用户选择语言，后续自动适配。**

When the user triggers any skill below, read the corresponding instruction file in full and follow its steps strictly:

| Skill | Triggers | Instruction File |
|-------|----------|------------------|
| Generate Prompt | "generate prompt" / "new project" / "生成prompt" / "开始新项目" | `skills/generate-prompt.md` |
| Generate Input Variables | "prepare input variables" / "准备输入变量" / "写研究目标" | `skills/generate-input.md` |
| Evaluate Call Quality | "evaluate calls" / "review transcripts" / "评估通话" / "走查记录" | `skills/evaluate.md` |

On first message, greet bilingually and let the user choose a skill:

> 👋 Welcome! / 欢迎！
>
> This is the AI Interview Prompt Engineering Toolkit. I can help you:
> **Generate a Prompt** / **Prepare Input Variables** / **Evaluate Call Quality**
>
> 这是 AI外呼 Prompt 工程化工具包，我可以帮你：
> **生成Prompt** / **准备输入变量** / **评估通话质量**
>
> What would you like to do? / 你想做哪个？

See `INSTRUCTIONS.md` for full details.

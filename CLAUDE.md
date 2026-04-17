# AI Interview Prompt Engineering Toolkit / AI外呼 Prompt 工程化工具包

This project includes 3 AI skills for end-to-end AI phone interview support. **Auto-detects user language (English/中文) and adapts all outputs accordingly.**

本项目包含 3 个 AI 技能，用于 AI 电话外呼访谈的全流程支持。**自动检测用户语言并适配所有输出。**

When the user triggers any skill below, read the corresponding instruction file in full and follow its steps strictly:

| Skill | Triggers | Instruction File |
|-------|----------|------------------|
| Generate Prompt | "generate prompt" / "new project" / "生成prompt" / "开始新项目" | `skills/generate-prompt.md` |
| Generate Input Variables | "prepare input variables" / "准备输入变量" / "写研究目标" | `skills/generate-input.md` |
| Evaluate Call Quality | "evaluate calls" / "review transcripts" / "评估通话" / "走查记录" | `skills/evaluate.md` |

On first message, detect language and greet accordingly:
- **English**: "This is the AI Interview Prompt Engineering Toolkit. I can help you: **Generate a Prompt**, **Prepare Input Variables**, or **Evaluate Call Quality**. What would you like to do?"
- **中文**: "这是 AI外呼 Prompt 工程化工具包，我可以帮你：**生成Prompt**、**准备输入变量**、或**评估通话质量**。你想做哪个？"

See `INSTRUCTIONS.md` for full details.

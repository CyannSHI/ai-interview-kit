# AI Interview Prompt Engineering Toolkit / AI外呼 Prompt 工程化工具包

This project includes 3 AI skills for end-to-end AI phone interview support. It automatically detects the user's language and adapts all interactions and outputs accordingly.

本项目包含 3 个 AI 技能，用于 AI 电话外呼访谈场景的全流程支持。系统会自动检测用户语言并适配所有交互和输出。

## Language / 语言

Detect the user's language from their first message and use it throughout the session:
- **English** → respond in English, use `framework/base_en.md` and `methodologies/en/`
- **中文** → 使用中文交互，使用 `framework/base.md` 和 `methodologies/`

## Available Skills / 可用技能

### 1. generate-prompt — Generate a complete interview prompt / 生成完整的AI外呼Prompt
- **Trigger**: "generate prompt" / "new project" / "生成prompt" / "开始新项目"
- **Instruction file**: `skills/generate-prompt.md`
- **Function**: Guided info collection → methodology recommendation → auto-assembled prompt

### 2. generate-input — Generate structured input variables / 生成结构化输入变量
- **Trigger**: "prepare input variables" / "write research goals" / "准备输入变量" / "写研究目标"
- **Instruction file**: `skills/generate-input.md`
- **Function**: Step-by-step guidance to convert natural language into standardized agent-parsable templates

### 3. evaluate — Evaluate call quality / 评估通话质量
- **Trigger**: "evaluate calls" / "review transcripts" / "评估通话" / "走查记录"
- **Instruction file**: `skills/evaluate.md`
- **Function**: Batch review of AI call transcripts, Bad Case detection, and information collection audit

## Usage / 使用方式

When the user triggers any skill above, you must first read the corresponding instruction file (`skills/*.md`) in full, then strictly follow its steps.

当用户触发上述任一技能时，你必须先读取对应的指令文件（`skills/*.md`）的完整内容，然后严格按照其中的步骤执行。

## Welcome / 开场引导

When the user opens a conversation without a clear instruction, briefly introduce the toolkit and ask what they'd like to do — in their language:

- **English**: "This is the AI Interview Prompt Engineering Toolkit. I can help you: **Generate a Prompt**, **Prepare Input Variables**, or **Evaluate Call Quality**. What would you like to do?"
- **中文**: "这是 AI外呼 Prompt 工程化工具包，我可以帮你：**生成Prompt**、**准备输入变量**、或**评估通话质量**。你想做哪个？"

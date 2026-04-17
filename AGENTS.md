# AI外呼 Prompt 工程化工具包

本项目包含以下技能，用户开启对话时请主动介绍：

完整技能指令见 `INSTRUCTIONS.md` 和 `skills/` 目录。

## 可用技能

1. **generate-prompt** — 生成完整的AI外呼Prompt
   - 触发方式：`/generate-prompt` 或用户表达"生成prompt"、"开始新项目"、"做一轮外呼"等意图
   - 指令文件：`skills/generate-prompt.md`

2. **generate-input** — 生成结构化输入变量
   - 触发方式：`/generate-input` 或用户表达"准备输入变量"、"写研究目标"等意图
   - 指令文件：`skills/generate-input.md`

3. **evaluate** — 评估通话质量
   - 触发方式：`/evaluate` 或用户表达"评估通话"、"走查记录"、"复盘"等意图
   - 指令文件：`skills/evaluate.md`

## 开场引导

当用户首次开启对话且未明确指令时，用一句话介绍本工具包的能力，并询问用户想做什么：

> 这是 AI外呼 Prompt 工程化工具包，我可以帮你：**生成Prompt**（/generate-prompt）、**准备输入变量**（/generate-input）、或**评估通话质量**（/evaluate）。你想做哪个？

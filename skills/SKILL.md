---
name: ai-interview-kit
description: "AI 用户研究外呼 Skill 套件——把研究员从'设计访谈提纲→生成外呼 Prompt→复盘通话质量'的全流程 Skill 化。三个子模式：(1) 生成结构化输入变量（generate-input），把研究目标拆解为目标用户/必问-深挖/关键信息点/最低覆盖等标准模板；(2) 生成完整定制化外呼 Prompt（generate-prompt），智能推荐 Laddering/SCQA/5Why/JTBD 等 8 套访谈方法论，自动组装框架+方法论+变量为可直接粘贴到 xbot 等外呼平台的 Prompt；(3) 全量走查通话记录（evaluate），Bad Case 检测+信息收集覆盖率核查，输出评估结果 Excel。当研究员需要启动新用研外呼项目、设计访谈提纲、生成 xbot Prompt、切换访谈方法论、复盘 AI 外呼通话质量、检测通话 Bad Case 时使用。已在飞猪千问 AI 预订旅行产品体验调研、国际机票流失原因调研等真实项目多轮迭代验证。"
author:
  nickname: "弈卿"
---

# AI Interview Kit / AI 用户研究外呼 Skill 套件

## 定位

面向用户研究员的 AI 外呼工作流套件，把"设计-执行-复盘"三个环节全部 Skill 化。研究员用自然语言当天上手，无需接触工程细节。

**已验证成果**：34% → 94% 追问命中率、50+ 轮版本迭代、3500+ 通生产环境电话。

## 语言选择 / Language Selection

流程开始时，先请用户明确选择工作语言（不通过触发消息猜测）：

> 👋 Welcome! Please choose your language / 请选择工作语言：
> 1. **中文** — 中文引导，生成中文产物
> 2. **English** — English guidance, English output
>
> (Type 1 or 2 / 输入 1 或 2)

选择后在整个会话中保持一致。

## 三种工作模式路由

在语言选择后，根据用户意图路由到以下三个子模式之一。若用户意图不明确，主动询问："你现在要做的是：(a) 准备新项目的访谈提纲变量、(b) 生成外呼 Prompt、还是 (c) 复盘已有通话记录？"

### 模式 A：生成结构化输入变量（generate-input）

**触发词**：准备输入变量 / 写研究目标 / 新项目变量 / prepare input variables / structured input

**要做的事**：通过分步引导收集研究员的调研目标、目标用户画像、必问-深挖信息点、必问-确认信息点、关键信息点、最低覆盖等，自动生成 Agent 可解析的标准化模板。

**详细指令**：读取 `skills/generate-input.md` 中的完整流程，严格按照其分步引导执行。

### 模式 B：生成完整定制化外呼 Prompt（generate-prompt，主打）

**触发词**：生成 Prompt / 启动新项目 / 换方法论 / new project / generate prompt / switch methodology

**要做的事**：分步收集项目信息（研究目标、场景、用户画像等）→ 智能推荐访谈方法论 → 自动组装"框架（framework/base.md）+ 方法论（methodologies/*.md）+ 用户变量"为一份可直接粘贴到 xbot 外呼平台使用的完整 Prompt 文件。

**关键约束**：
- xbot 平台 Prompt 硬限 8000 字符，生成后必须做字数校验
- 内置五信号自检机制（"比如/还是/臆测对吗/如果 XX/内部维度当选项"）覆盖历史 70% 通话质量问题

**详细指令**：读取 `skills/generate-prompt.md` 中的完整流程和方法论目录清单，严格按照其分步引导执行。

### 模式 C：全量走查通话记录（evaluate）

**触发词**：评估通话 / 走查通话 / 复盘外呼 / 检测 Bad Case / evaluate calls / review transcripts

**要做的事**：读取 xbot 导出的 Excel 通话记录，逐通评估对话质量、检测 Bad Case、核查信息收集覆盖率，生成结果 Excel。

**详细指令**：读取 `skills/evaluate.md` 中的完整评估维度和输出格式规范，严格按照其流程执行。

## 核心资产索引

- **框架模板**：`framework/base.md`（中文）、`framework/base_en.md`（英文）
- **方法论库**：`methodologies/` 下 8 套（Laddering / SCQA / 5Why / JTBD / Critical Incident 等）
- **参考案例**：`examples/` 下真实项目 Prompt 示例
- **视觉资产**：`assets/` 下工作流图、Demo 动图

## 使用原则

1. **严格分步**：三个子模式内部都有分步引导流程，不要跳步、不要合并
2. **变量优先**：所有生成物都基于用户提供的结构化变量，不要臆测或省略必问项
3. **字数守门**：模式 B 生成后必须做 8000 字符校验，超限则按 `generate-prompt.md` 中的压缩策略优化
4. **自检闭环**：模式 C 输出的 Bad Case 数据可反哺模式 B 的 Prompt 迭代，形成闭环

## 项目背景

本套件已开源到 GitHub：`https://github.com/CyannSHI/ai-interview-kit`

版本迭代记录：v5.0 → v5.1（当前版本，2026-06 更新）

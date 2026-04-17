<h1 align="center">AI Interview Kit</h1>

<p align="center">
  <strong>将用研方法论工程化为 AI Prompt，让每一通电话都有专业访谈的质量</strong>
</p>

<p align="center">
  <code>追问到位率 34% → 94%</code>&nbsp;&nbsp;·&nbsp;&nbsp;<code>经 50+ 轮迭代验证</code>&nbsp;&nbsp;·&nbsp;&nbsp;<code>生产环境 2500+ 通外呼</code>
</p>

<p align="center">
  <a href="#快速开始"><img src="https://img.shields.io/badge/-快速开始-blue?style=for-the-badge" alt="Quick Start"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"></a>
  <a href="#兼容性"><img src="https://img.shields.io/badge/兼容-5+_AI工具-orange?style=for-the-badge" alt="Compatibility"></a>
  <a href="#方法论库"><img src="https://img.shields.io/badge/方法论-6种-purple?style=for-the-badge" alt="Methodologies"></a>
</p>

---

<p align="center">
  <img src="assets/demo.gif" alt="50 秒看懂全流程" width="90%">
  <br>
  <sub>▲ 50 秒演示：输入研究问题 → AI 分类 → 推荐方法论 → 生成完整 Prompt</sub>
</p>

---

## 为谁而做

**如果你是用研从业者** —— 你一定经历过这些：
- 深度访谈效率太低，一周只能做 5-8 个样本
- 外包给执行公司，质量参差不齐，回来还得自己补访
- 想规模化但预算有限，最后只能砍样本量

**如果你是产品经理 / 创业者 / 对洞察用户感兴趣的人** —— 你可能觉得：
- 用户访谈门槛太高，不知道问什么、怎么问
- 用 ChatGPT 问出来的都是表面答案，聊不下去
- 花了时间访谈，整理完发现没问到重点

**我们的思路**：把专业用研的方法论工程化成 AI Prompt，让非专业人士也能做专业级访谈，让专业人士能规模化执行。

---

## 核心创新：AI 控制精度

访谈不是让 AI 自由聊天。不同研究目标需要不同的 AI 自由度——验证性研究要求精确执行，探索性研究需要 AI 灵活发挥。**这是用研老手凭经验做的事，我们把它参数化了。**

```
AI 自由度:   低 ◄━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━► 高

            🎯 精细控制          ⚖️ 平衡模式          🔍 粗放模式
            验证性研究            大多数场景            探索性调研
```

|  | 🎯 精细控制 | ⚖️ 平衡模式 | 🔍 粗放模式 |
|:--|:--:|:--:|:--:|
| **适用场景** | 目标明确的验证性研究 | 大方向明确，适度发挥 | 探索性调研，发现未知 |
| **关键信息点** | 每题标注 ✅ | 每题标注 ✅ | 不标注，AI 自主 |
| **追问上限** | 4 回合/题 | 6 回合/题 | AI 自主判断 |
| **最低覆盖** | 必问题 × 80% | 必问题 × 75% | 必问题 × 60% |
| **典型场景** | NPS 回访、满意度验证 | JTBD 迁移、旅程归因 | 新品探索、品牌心智 |

> **为什么这很重要？** 传统用研中，访谈质量高度依赖访谈员的经验——何时深挖、何时跳过、何时接住话题展开。我们将这些隐性经验提炼为三个参数维度（信息点标注密度、追问回合上限、最低覆盖率），让你在项目启动前就能精确设定 AI 的行为边界。精细控制确保你不遗漏任何关键验证点；粗放模式则给了 AI 足够空间去发现你没想到的洞察。

---

## How It Works：Prompt 工程化架构

<p align="center">
  <img src="assets/architecture.svg" alt="Prompt 工程化架构" width="90%">
</p>

**一句话说清**：通用框架（怎么问）+ 可插拔方法论（问什么）+ 项目变量（问谁）→ 自动组装为完整 Prompt。

### SLOT 插槽机制

<p align="center">
  <img src="assets/slot-mechanism.svg" alt="SLOT 插槽组装原理" width="90%">
</p>

> 新增方法论只需写 3 个 SLOT，不用改框架；框架升级自动惠及所有方法论。

---

## 实验验证：从 50+ 次失败中迭代

### 发现的问题

<table>
<tr>
<td width="50%" align="center">

**❌ 低智闲聊：问了废话，用户翻白眼**

</td>
<td width="50%" align="center">

**❌ 节奏失调：一口气问太多，用户抓不住**

</td>
</tr>
<tr>
<td>

<img src="assets/before-bad-question.png" width="100%">

> 用户："不是火车票抢不抢都一样的...你问的是啥呀？"

</td>
<td>

<img src="assets/before-bad-rhythm.png" width="100%">

> AI 一段话问了 3 个问题，用户只回应了最后一个

</td>
</tr>
</table>

### 解决后的效果

<table>
<tr>
<td width="50%" align="center">

**✅ 精准归纳：实时总结全程信息，零遗漏**

</td>
<td width="50%" align="center">

**✅ 逐层下钻：从模糊表述追到具体场景**

</td>
</tr>
<tr>
<td>

<img src="assets/after-good-summary.png" width="100%">

> AI 一口气回收散落全程的关键信息——订酒店渠道、决策因素、会员感知、期望权益——用户直接回复"对对对"

</td>
<td>

<img src="assets/after-good-deepdrill.png" width="100%">

> 用户只说了句模糊抱怨，AI 三步追到具体城市→具体酒店→具体事件："您当时已按时到达，却因系统判定被限制入住？"

</td>
</tr>
<tr>
<td width="50%" align="center">

**✅ 自然拓展：像真人一样顺着语境延伸**

</td>
<td width="50%" align="center">

**✅ 精准下钻：层层深入抓住重点**

</td>
</tr>
<tr>
<td>

<img src="assets/after-good-expand.png" width="100%">

> AI 从"做什么工作"自然过渡到"每通电话多长时间""几轮能问全信息"，对话节奏接近真人访谈员

</td>
<td>

<img src="assets/after-good-drill.png" width="100%">

> AI 精准追问"两个渠道"的选择原因，层层深入到价格差异

</td>
</tr>
</table>

### 关键改进路径

```
v0.1  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━  v0.4
 │                                                            │
 │  追问到位率 34% ──────────────────────► 追问到位率 94%       │
 │                                                            │
 ├─ v0.1 基础问题清单            问完就过，不追问               │
 ├─ v0.2 +关键信息点标注         AI知道要挖什么了     ──► 61%   │
 ├─ v0.3 +追问上限+三问必换题    节奏可控，不僵局     ──► 89%   │
 └─ v0.4 +方法论SLOT机制         方法论驱动深挖       ──► 94%   │
```

<details>
<summary>📋 <strong>完整测试方案：6 大压力场景</strong>（点击展开）</summary>

<br>

我们设计了 6 个极端场景来压力测试 Prompt：

| # | 测试场景 | 验证目标 |
|:-:|---------|---------|
| 1 | **唤醒与破壁** | 用户说"不记得"时，AI 能否温柔唤醒记忆？ |
| 2 | **深度下钻与拒绝诱导** | AI 能否纯开放提问，不给选项、不诱导？ |
| 3 | **事实矛盾与逻辑敏锐度** | 用户前后矛盾时，AI 能否发现并追问？ |
| 4 | **高压效率与极端情绪** | 用户愤怒/抱怨时，AI 能否安抚并拉回？ |
| 5 | **信息降噪与关键提取** | 用户说了一堆，AI 能否抓住关键信息？ |
| 6 | **用户反问与身份稳定性** | 用户质疑"你是机器人吧"，AI 怎么应对？ |

**评估维度**：聊天节奏 · 问题挖掘深度 · 关键信息遗漏 · 异常挂断率 · 提示词鲁棒性

</details>

<details>
<summary>📊 <strong>生产环境验证数据</strong>（点击展开）</summary>

<br>

以下数据来自 Prompt 在实际外呼平台的生产运行：

| 核心指标 | 传统人工（行业基准） | A 项目（测试） | B 项目（正式） | C 项目（正式） |
|:--------|:--:|:--:|:--:|:--:|
| 单次覆盖量 | 50-100 通/天 | **1267 通** | **202 通** | **1031 通** |
| 接通率 | 30-40% | 47% | **61%** | 51% |
| 有效访谈率 | 10-15% | 6% | **21%** | 7% |
| 时间效率 | 1-2人 × 2-3天 | 2号码 × 4h | 2号码 × 30min | 2号码 × 3.5h |

> B 项目有效访谈率达到 21%，超过行业基准 10-15%。

</details>

---

## 快速开始

```bash
git clone https://github.com/CyannSHI/ai-interview-kit.git
cd ai-interview-kit
# 用任意 AI 工具打开，说"生成 prompt"即可
```

| 技能 | 触发方式 | 功能 |
|:-----|:--------|:-----|
| **generate-prompt** | "生成prompt"、"开始新项目" | 引导收集信息 → 推荐方法论 → 自动组装 Prompt |
| **generate-input** | "准备输入变量" | 自然语言 → 结构化输入变量 |
| **evaluate** | "评估通话" | 全量走查通话记录，检测 Bad Case |

<p align="center">
  <img src="assets/workflow.svg" alt="用户操作全流程" width="90%">
</p>

---

## 闭环：复盘 → 迭代

外呼结束不是终点。把通话记录丢给 AI，它会告诉你**下次怎么做得更好**。

```bash
# 对AI说：
"评估这次外呼效果"
"复盘通话质量"
"检查Bad Case"
```

**典型问题 → 迭代动作**：

| 发现的问题 | 优化动作 |
|:-----|:---------|
| 追问到位率 60% → 关键信息点标注不清晰 | 下次增加信息点描述，减少模糊表述 |
| 用户频繁反问 AI 身份 → 开场白不够自然 | 调整身份设定，增加"用户研究员"背书 |
| 某类问题总是收集不到 → 提问方式有问题 | 修改提问话术，增加场景引导 |
| 追问 5 轮用户不耐烦 → 节奏太紧 | 降低追问上限，或切换平衡模式 |

**输出**：Excel 报告（每通评分 + 问题定位 + 具体改进建议）→ 直接用于优化下一轮 Prompt

---

## 方法论库

| 方法论 | 适用场景 | 核心维度 |
|:------|:--------|:--------|
| **JTBD 需求迁移** | 用户决策 · 流失原因 · 竞品替换 | 推力 / 拉力 / 焦虑 / 习惯 / 去向 |
| **用户旅程归因** | 体验流程 · 流程断点 · 操作链路 | 阶段 / 触点 / 行为 / 情绪 / 断点 |
| **NPS/满意度** | 满意度回访 · 服务改善 | 正向驱动 / 负向驱动 / 期望落差 |
| **心智培育** | 深层动机 · 价值观挖掘 | 属性 / 功能利益 / 情感利益 / 核心价值观 |
| **用户生命周期** | 转化 · 留存 · 流失 | 获取 / 转化 / 使用 / 留存 / 流失 |
| **品牌诊断** | 品牌认知 · 竞品定位 | 认知 / 联想 / 偏好 / 对比 / 忠诚 |

> 想添加自定义方法论？复制 `methodologies/_template.md`，填写 3 个 SLOT，保存即可。

---

## 兼容性

技能指令使用**纯自然语言**编写，零 API 依赖，自动适配主流 AI 工具：

| AI 工具 | 入口文件 |
|:--------|:--------|
| **Qoder** | `AGENTS.md` → `.qoder/skills/` |
| **Claude Code** | `CLAUDE.md` |
| **Cursor** | `.cursor/rules/ai-interview-skills.mdc` |
| **GitHub Copilot** | `.github/copilot-instructions.md` |
| **Windsurf** | `.windsurfrules` |
| **其他** | `INSTRUCTIONS.md` |

所有入口文件最终指向 `skills/` 目录——**技能逻辑只有一份，零重复**。

---

<details>
<summary>📂 <strong>项目结构</strong>（点击展开）</summary>

<br>

```
.
├── skills/                     # 技能指令（唯一真实来源）
│   ├── generate-prompt.md      #   生成 Prompt
│   ├── generate-input.md       #   生成输入变量
│   └── evaluate.md             #   通话质量评估
├── framework/
│   └── base.md                 # 通用访谈框架（含 SLOT 插槽）
├── methodologies/              # 方法论库（可插拔）
│   ├── jtbd.md                 #   JTBD 需求迁移
│   ├── journey.md              #   用户旅程归因
│   ├── nps.md                  #   NPS/满意度
│   ├── laddering.md            #   心智培育
│   ├── lifecycle.md            #   用户生命周期
│   └── brand.md                #   品牌诊断
├── examples/                   # 示例文件
└── assets/                     # 图片资源
```

</details>

---

## 贡献

欢迎 Issue 和 PR！尤其欢迎贡献新的方法论模块、分享使用案例、改进框架的下钻逻辑。

---

<p align="center">
  <br>
  <strong>愿景：洞察平权</strong>
  <br><br>
  让没有预算请专业用研公司的初创团队、公益组织，<br>
  也能低成本地"听见用户"，让产品设计真正回归"以人为本"。
  <br><br>
  如果这个项目对你有帮助，请给个 ⭐ Star 支持一下
  <br><br>
  <a href="./LICENSE">MIT License</a>
</p>

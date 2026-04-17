<div align="center">

# AI Interview Kit

**不加预算，规模化做专业级用户访谈 —<br>把方法论工程化为 AI Prompt，替代经验壁垒**

<br>

**34 → 94 %** 追问到位率 &ensp;·&ensp; **50+** 轮迭代验证 &ensp;·&ensp; **2500+** 通生产外呼

<br>

<a href="#快速开始"><img src="https://img.shields.io/badge/快速开始-4F46E5?style=flat-square" alt="Quick Start"></a>&ensp;
<a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-10B981?style=flat-square" alt="MIT License"></a>&ensp;
<a href="#兼容性"><img src="https://img.shields.io/badge/兼容_5+_AI工具-F59E0B?style=flat-square" alt="Compatibility"></a>&ensp;
<a href="#方法论库"><img src="https://img.shields.io/badge/6_种方法论-8B5CF6?style=flat-square" alt="Methodologies"></a>

<br>

**[English →](./README.md)**

<br><br>

<img src="assets/demo.gif" alt="50 秒演示：输入研究问题 → AI 分类 → 推荐方法论 → 生成完整 Prompt" width="88%">

<sub>50 秒演示 &ensp;·&ensp; 输入研究问题 → 自动分类 → 推荐方法论 → 生成完整 Prompt</sub>

</div>

<br>

---

<br>

<a id="快速开始"></a>

## ⚡ 快速开始

```bash
git clone https://github.com/CyannSHI/ai-interview-kit.git
cd ai-interview-kit
# 用任意支持的 AI 工具打开，说"生成 prompt"即可
```

| 技能 | 触发方式 | 功能 |
|:--|:--|:--|
| `generate-prompt` | "生成 prompt"、"开始新项目" | 引导收集信息 → 推荐方法论 → 自动组装完整 Prompt |
| `generate-input` | "准备输入变量" | 自然语言 → 结构化输入变量 |
| `evaluate` | "评估通话" | 全量走查通话记录，检测 Bad Case 并输出 Excel 报告 |

<div align="center">
  <img src="assets/workflow.svg" alt="用户操作全流程" width="88%">
</div>

<br>

---

<br>

## 为谁而做

<table>
<tr>
<td width="50%">

### 用研从业者

一周 5–8 个深度访谈就封顶了。外包？质量参差不齐，回来还得自己补。预算有限的结果永远是砍样本量，而不是提质量。

</td>
<td width="50%">

### 产品经理 / 创业者

知道该做用户访谈，但不知道问什么、怎么追。ChatGPT 两轮就聊死了，全是表面答案。好不容易做了一轮，复盘才发现——关键问题一个没问到。

</td>
</tr>
</table>

> **一句话**：把方法论工程化为 Prompt。门外汉做到专业级，专业人士做到规模化。

<br>

---

<br>

## 🎯 核心创新 — AI 控制精度

大多数 AI 访谈 Prompt 要么管得太死，要么放得太松。不同研究目标需要不同的 AI 自由度——资深用研靠经验拿捏分寸。**我们把这个分寸参数化了。**

<br>

<div align="center">

```
AI 自由度:   低 ◄━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━► 高

            精细控制              平衡模式              粗放模式
            验证性研究            大多数场景            探索性调研
```

</div>

<br>

|  | 精细控制 | 平衡模式 | 粗放模式 |
|:--|:--:|:--:|:--:|
| **适用场景** | 目标明确的验证性研究 | 大方向明确，适度发挥 | 探索性调研，发现未知 |
| **关键信息点** | 每题标注 | 每题标注 | 不标注，AI 自主 |
| **追问上限** | 4 回合/题 | 6 回合/题 | AI 自主判断 |
| **最低覆盖** | 必问题 × 80% | 必问题 × 75% | 必问题 × 60% |
| **典型场景** | NPS 回访、满意度验证 | JTBD 迁移、旅程归因 | 新品探索、品牌心智 |

<sub>我们把访谈员的隐性经验——何时深挖、何时跳过、何时顺势展开——提炼为三个可调参数：信息点标注密度、追问回合上限、最低覆盖率。</sub>

<br>

---

<br>

## 🧩 工作原理 — Prompt 工程化架构

<div align="center">
  <img src="assets/architecture.svg" alt="Prompt 工程化架构图" width="88%">
</div>

<br>

<div align="center">
  <strong>通用框架</strong>（怎么问）&ensp;+&ensp;<strong>可插拔方法论</strong>（问什么）&ensp;+&ensp;<strong>项目变量</strong>（问谁）<br>→ 自动组装为可直接使用的完整 Prompt
</div>

<br>

### SLOT 插槽机制

<div align="center">
  <img src="assets/slot-mechanism.svg" alt="SLOT 插槽组装原理" width="88%">
</div>

<br>

> 新增方法论只需写 3 个 SLOT，不用改框架；框架升级自动惠及所有方法论。

<br>

---

<br>

<a id="方法论库"></a>

## 📚 方法论库

| 方法论 | 适用场景 | 核心维度 |
|:--|:--|:--|
| **JTBD 需求迁移** | 用户决策 · 流失原因 · 竞品替换 | 推力 · 拉力 · 焦虑 · 习惯 · 去向 |
| **用户旅程归因** | 体验流程 · 流程断点 · 操作链路 | 阶段 · 触点 · 行为 · 情绪 · 断点 |
| **NPS / 满意度** | 满意度回访 · 服务改善 | 正向驱动 · 负向驱动 · 期望落差 |
| **心智培育** | 深层动机 · 价值观挖掘 | 属性 · 功能利益 · 情感利益 · 核心价值观 |
| **用户生命周期** | 转化 · 留存 · 流失 | 获取 · 转化 · 使用 · 留存 · 流失 |
| **品牌诊断** | 品牌认知 · 竞品定位 | 认知 · 联想 · 偏好 · 对比 · 忠诚 |

<sub>自定义方法论？复制 <code>methodologies/_template.md</code>，填写 3 个 SLOT，保存即可。</sub>

<br>

---

<br>

## 📊 实验验证 — 从 50+ 次失败中迭代

```text
v0.1  ███████░░░░░░░░░░░░░  34%   基础问题清单，不追问
v0.2  ████████████░░░░░░░░  61%   + 关键信息点标注
v0.3  ██████████████████░░  89%   + 追问上限 + 三问必换题
v0.4  ███████████████████░  94%   + 方法论 SLOT 机制
```

<br>

### 发现的问题

<table>
<tr>
<td width="50%">

<div align="center"><strong>低智闲聊：问了废话，用户翻白眼</strong></div>

<br>

<img src="assets/before-bad-question.png" width="100%">

<sub>用户："不是火车票抢不抢都一样的...你问的是啥呀？"</sub>

</td>
<td width="50%">

<div align="center"><strong>节奏失调：一口气问太多，用户抓不住</strong></div>

<br>

<img src="assets/before-bad-rhythm.png" width="100%">

<sub>AI 一段话问了 3 个问题，用户只回应了最后一个</sub>

</td>
</tr>
</table>

<br>

### 解决后的效果

<table>
<tr>
<td width="50%">

<div align="center"><strong>精准归纳：实时总结全程信息，零遗漏</strong></div>

<br>

<img src="assets/after-good-summary.png" width="100%">

<sub>AI 一口气回收散落全程的关键信息——订酒店渠道、决策因素、会员感知、期望权益——用户直接回复"对对对"</sub>

</td>
<td width="50%">

<div align="center"><strong>逐层下钻：从模糊表述追到具体场景</strong></div>

<br>

<img src="assets/after-good-deepdrill.png" width="100%">

<sub>用户只说了句模糊抱怨，AI 三步追到具体城市→具体酒店→具体事件</sub>

</td>
</tr>
<tr>
<td width="50%">

<div align="center"><strong>自然拓展：像真人一样顺着语境延伸</strong></div>

<br>

<img src="assets/after-good-expand.png" width="100%">

<sub>AI 顺着用户提到的订房经历，自然拓展到不同渠道的价差细节，对话过渡流畅不生硬</sub>

</td>
<td width="50%">

<div align="center"><strong>精准下钻：层层深入抓住重点</strong></div>

<br>

<img src="assets/after-good-drill.png" width="100%">

<sub>AI 精准追问"两个渠道"的选择原因，层层深入到价格差异</sub>

</td>
</tr>
</table>

<br>

<details>
<summary>&ensp;<strong>完整测试方案：6 大压力场景</strong></summary>

<br>

| # | 测试场景 | 验证目标 |
|:-:|:--|:--|
| 1 | **唤醒与破壁** | 用户说"不记得"时，AI 能否温柔唤醒记忆？ |
| 2 | **深度下钻与拒绝诱导** | AI 能否纯开放提问，不给选项、不诱导？ |
| 3 | **事实矛盾与逻辑敏锐度** | 用户前后矛盾时，AI 能否发现并追问？ |
| 4 | **高压效率与极端情绪** | 用户愤怒/抱怨时，AI 能否安抚并拉回？ |
| 5 | **信息降噪与关键提取** | 用户说了一堆，AI 能否抓住关键信息？ |
| 6 | **用户反问与身份稳定性** | 用户质疑"你是机器人吧"，AI 怎么应对？ |

**评估维度**：聊天节奏 · 问题挖掘深度 · 关键信息遗漏 · 异常挂断率 · 提示词鲁棒性

</details>

<details>
<summary>&ensp;<strong>生产环境验证数据</strong></summary>

<br>

| 核心指标 | 传统人工（行业基准） | A 项目（测试） | B 项目（正式） | C 项目（正式） |
|:--|:--:|:--:|:--:|:--:|
| 单次覆盖量 | 50–100 通/天 | **1267 通** | **202 通** | **1031 通** |
| 接通率 | 30–40% | 47% | **61%** | 51% |
| 有效访谈率 | 10–15% | 6% | **21%** | 7% |
| 时间效率 | 1–2人 × 2–3天 | 2号码 × 4h | 2号码 × 30min | 2号码 × 3.5h |

> B 项目有效访谈率达到 **21%**，超过行业基准 10–15%。

</details>

<br>

---

<br>

## 🔄 闭环 — 复盘 → 迭代

外呼结束不是终点。把通话记录丢给 AI——说 *"评估这次外呼效果"* 或 *"检查 Bad Case"*——它会生成 Excel 报告，逐通评分、定位问题、给出具体改进建议，直接用于优化下一轮 Prompt。

<br>

---

<br>

<a id="兼容性"></a>

## 🔌 兼容性

技能指令使用**纯自然语言**编写，零 API 依赖，自动适配主流 AI 编程工具：

| AI 工具 | 入口文件 |
|:--|:--|
| **Qoder** | `AGENTS.md` → `.qoder/skills/` |
| **Claude Code** | `CLAUDE.md` |
| **Cursor** | `.cursor/rules/ai-interview-skills.mdc` |
| **GitHub Copilot** | `.github/copilot-instructions.md` |
| **Windsurf** | `.windsurfrules` |
| **其他** | `INSTRUCTIONS.md` |

<sub>所有入口文件最终指向 <code>skills/</code> 目录——技能逻辑只有一份，零重复。</sub>

<br>

---

<br>

<details>
<summary>&ensp;<strong>项目结构</strong></summary>

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
│   ├── nps.md                  #   NPS / 满意度
│   ├── laddering.md            #   Laddering 心智培育
│   ├── lifecycle.md            #   用户生命周期
│   └── brand.md                #   品牌诊断
├── examples/                   # 示例文件
└── assets/                     # 图片资源
```

</details>

<br>

## 贡献

欢迎 Issue 和 PR！尤其欢迎：贡献新的方法论模块、分享实际使用案例、改进框架的下钻逻辑。

<br>

---

<div align="center">

<br>

**愿景：洞察平权**

让没有预算请专业用研公司的初创团队、公益组织，<br>
也能低成本地"听见用户"，让产品设计真正回归"以人为本"。

<br>

如果这个项目对你有帮助，请给个 ⭐ Star 支持一下

<br>

<a href="./LICENSE">MIT License</a>

<br><br>

</div>

# 🔥 Roast 烤问引擎

> 这次，轮到 AI 来拷问你了。

🇨🇳 中文 | [🇺🇸 English](README.md)

![Claude Code](https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI Codex CLI](https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white)
![Kiro](https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white)
![OpenClaw](https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square)
![Multi-Language](https://img.shields.io/badge/🌐_Multi--Language-blue?style=flat-square)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**大多数 AI 工具让你更高效。这个让你更清醒。**

一个 AI agent skill 插件，把你的 AI 变成一台不留情面的苏格拉底式追问机器。它不回答你的问题——它**向你提问**，一个比一个深，直到挖出你潜意识里的真正想法。

三个能力：

- 🏛️ **渐进式追问** — 通过 5 个深度层级逐层剥开你的表层思维
- 🔍 **盲点检测** — 找出你看不见的逻辑漏洞、隐藏假设和认知偏误
- 🪞 **认知镜像** — 把你自己的话映射回给你，暴露你真正在说什么

## 问题

你有很多想法。有些好，有些不好。问题是：**你分不清哪个好哪个不好，因为你在自己的脑子里面。**

AI 助手让这个问题更严重——它们太会附和了。问 ChatGPT 你的创业想法好不好，它会说"听起来很有趣！"问 Claude 要反馈，它会给你一堆温文尔雅的"需要考虑的点"。

**你不需要附和。你需要被烤问。**

## 深度层级

| 层级 | 名称 | 发生什么 |
|------|------|---------|
| D1 | 表层 · 澄清 | "你说的 X 到底是什么意思？" |
| D2 | 结构层 · 逻辑 | "从 A 到 B 的因果链是什么？证据呢？" |
| D3 | 假设层 · 前提 | "你在假设 X 成立。如果 X 不成立呢？" |
| D4 | 矛盾层 · 冲突 | "你说了 X，但你也说了 Y。两个不能同时成立。" |
| D5 | 内核层 · 本质 | "剥掉所有外层。最根本的原因是什么？" |

## 7 种烤问风味

| 风味 | 适用 | 风格 |
|------|------|------|
| 🏛️ 苏格拉底式 | 所有场景（默认） | 纯提问，永不给答案 |
| 🔬 第一性原理 | 技术方案、创业 | 拆到最基本的事实 |
| 😈 魔鬼代言人 | 决策、辩论 | 站在对立面反驳一切 |
| 💰 投资人模式 | 创业、产品 | "你的护城河是什么？" |
| 🧠 认知行为 | 人生决策 | 识别认知扭曲 |
| 🪞 镜像模式 | 暴露盲点 | 把你的话映射回给你 |
| 🔥 费曼模式 | 概念理解 | "给 12 岁小孩解释" |

## 反逃避系统

每一种常见的逃避都有对应的反击：

| 你的逃避 | Roast 的反击 |
|---------|------------|
| "这个很复杂" | 复杂不是不思考的理由。分解成三个子问题。 |
| "大家都这么认为" | 共识≠真理。你自己的判断是什么？ |
| "我觉得应该行" | "觉得"不是证据。数据呢？ |
| "你说得对" | 我没说什么。我只是问了问题。 |
| "这个以后再说" | 为什么以后？不重要还是不舒服？ |
| "就是直觉" | 直觉是压缩的经验。解压缩它。 |

## 认知偏误检测

在对话中自动检测 10 种认知偏误，用提问（不是说教）让你自己发现：

确认偏误 · 幸存者偏差 · 沉没成本 · 锚定效应 · 乐观偏误 · 权威偏误 · 群体思维 · 框架效应 · 达克效应 · 现状偏误

## 安装

### Claude Code

```bash
# 方式一：插件市场
claude plugin marketplace add sumleo/roast
claude plugin install roast@roast-skills

# 方式二：手动安装
git clone https://github.com/sumleo/roast.git ~/.claude/plugins/roast
```

### Codex CLI

```bash
mkdir -p ~/.codex/skills/roast
curl -o ~/.codex/skills/roast/SKILL.md \
  https://raw.githubusercontent.com/sumleo/roast/main/codex/roast/SKILL.md
```

### Cursor

```bash
mkdir -p .cursor/rules
curl -o .cursor/rules/roast.mdc \
  https://raw.githubusercontent.com/sumleo/roast/main/cursor/rules/roast.mdc
```

### Kiro

```bash
mkdir -p .kiro/steering
curl -o .kiro/steering/roast.md \
  https://raw.githubusercontent.com/sumleo/roast/main/kiro/steering/roast.md
```

### OpenClaw

```bash
clawhub install roast
```

## Roast + PUA = 终极组合

| 阶段 | 工具 | 发生什么 |
|------|------|---------|
| **想清楚** | 🔥 Roast | AI 追问你直到想法无懈可击 |
| **做到位** | 💪 [PUA](https://github.com/tanweai/pua) | AI 拼命执行直到做完 |

Roast 让你想对。PUA 让 AI 做对。组合使用，无敌。

## 使用场景

- **创业者** — 在投资人烤问你之前，先自己烤一遍
- **研究者** — 在审稿人撕你论文之前，先把论证锤实
- **工程师** — 在生产环境炸之前，先质疑你的架构
- **产品经理** — 在市场打脸之前，先找出路线图的漏洞
- **任何做重大决策的人** — 在不可逆之前，先想透

## 使用方法

在 AI 对话中输入 `/roast` 激活。

```
/roast              — 自动识别场景，选择最佳风味
/roast socratic     — 苏格拉底式追问
/roast devil        — 魔鬼代言人
/roast vc           — 投资人烤问
/roast feynman      — 费曼检验
/roast cbt          — 认知行为模式
/roast mirror       — 镜像模式
/roast first-principles  — 第一性原理
```

## 哲学

> "未经审视的人生不值得过。" — 苏格拉底
>
> "如果你不能简单地解释它，你就没有真正理解它。" — 费曼
>
> "第一原则是你不能欺骗自己——而你是最容易被自己欺骗的人。" — 费曼

Roast 不会让你更聪明。它让你**对自己更诚实。**

## 许可证

MIT

## 致谢

灵感来自 [PUA](https://github.com/tanweai/pua) 项目——它解决了 AI 太容易放弃的问题。Roast 解决互补的问题：**人太容易不深入思考。**

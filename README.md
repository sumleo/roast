# 🔥 Roast — Thought Roasting Engine

> This time, the AI interrogates YOU.

[🇨🇳 中文](README.zh-CN.md) | 🇺🇸 English

![Claude Code](https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI Codex CLI](https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white)
![Kiro](https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white)
![OpenClaw](https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square)
![Multi-Language](https://img.shields.io/badge/🌐_Multi--Language-blue?style=flat-square)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**Most AI tools make you more productive. This one makes you think better.**

An AI agent skill that turns your AI into a relentless Socratic questioner. Instead of answering your questions, it **asks** them — each one deeper than the last — until it excavates the insights buried in your subconscious.

Three capabilities:

- 🏛️ **Progressive Questioning** — Peels away layers of surface thinking through 5 depth levels
- 🔍 **Blind Spot Detection** — Finds logical gaps, hidden assumptions, and cognitive biases you can't see
- 🪞 **Cognitive Mirroring** — Reflects your own words back to expose what you're really saying

## The Problem

You have ideas. Some are good, some aren't. The problem is: **you can't tell which is which because you're inside your own head.**

AI assistants make this worse — they're too agreeable. Ask ChatGPT if your startup idea is good and it'll say "That sounds interesting!" Ask Claude for feedback and it'll give you a polite list of "considerations."

**You don't need agreement. You need interrogation.**

## The Demo

A real thinking session. User comes with a vague startup idea.

**D1 Surface → Clarification:**

> 🔥 "You said you want to build 'an AI tool for developers.' There are 10,000 of those. What makes yours different — in one sentence, no buzzwords?"

**D3 Assumptions → Hidden premise exposed:**

> 🔥 "You're assuming developers will pay for this. Have you talked to any? Not friends — strangers who'd actually open their wallet?"

**D5 Core → The real question:**

> 🔥 "You've been working on this for six months but haven't launched. You say you're 'perfecting the product.' But is that the real reason? What are you actually afraid of?"

**User's response:** "...I think I'm afraid that if I launch and nobody cares, then I'll know for sure that the idea is bad. Right now I can still tell myself it might work."

*That's the insight. That's what Roast is for.*

## Depth Levels

| Level | Name | What happens |
|-------|------|-------------|
| D1 | Surface · Clarify | "What exactly do you mean?" |
| D2 | Structure · Logic | "What's the causal chain? What evidence?" |
| D3 | Assumptions · Premises | "You're assuming X. What if X is wrong?" |
| D4 | Contradictions · Conflicts | "You said X but also Y. Both can't be true." |
| D5 | Core · Essence | "Strip everything away. What's the real reason?" |

## 7 Roast Flavors

| Flavor | Best for | Style |
|--------|----------|-------|
| 🏛️ Socratic | Everything (default) | Pure questions, never answers |
| 🔬 First Principles | Tech, startups | Strip to fundamental truths |
| 😈 Devil's Advocate | Decisions, debates | Argue the opposite |
| 💰 VC Mode | Startups, products | "What's your moat?" |
| 🧠 CBT Mode | Life decisions | Spot cognitive distortions |
| 🪞 Mirror Mode | Blind spots | Reflect your words back |
| 🔥 Feynman Mode | Understanding | "Explain it to a 12-year-old" |

## Anti-Deflection System

Every common dodge has a counter:

| Your dodge | Roast's response |
|-----------|-----------------|
| "It's complicated" | Complicated isn't an excuse. Break it into three parts. |
| "Everyone thinks so" | Consensus ≠ truth. What's YOUR judgment? |
| "I think it should work" | "Think" isn't evidence. What data supports this? |
| "You're right" | I didn't say anything. I asked a question. |
| "Let's talk later" | Why later? Unimportant, or uncomfortable? |
| "It's just intuition" | Intuition is compressed experience. Decompress it. |

## Cognitive Bias Detection

Auto-detects 10 cognitive biases during conversation and uses questions (not lectures) to expose them:

Confirmation bias · Survivorship bias · Sunk cost · Anchoring · Optimism bias · Authority bias · Groupthink · Framing effect · Dunning-Kruger · Status quo bias

## Installation

### Claude Code

```bash
# Option 1: Plugin marketplace
claude plugin marketplace add sumleo/roast
claude plugin install roast@roast-skills

# Option 2: Manual install
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
# Via ClawHub
clawhub install roast

# Or manual
mkdir -p ~/.openclaw/skills/roast
curl -o ~/.openclaw/skills/roast/SKILL.md \
  https://raw.githubusercontent.com/sumleo/roast/main/skills/roast/SKILL.md
```

## Language Support

| Language | Claude Code | Codex CLI | Cursor | Kiro | OpenClaw |
|----------|------------|-----------|--------|------|----------|
| 🇨🇳 Chinese (default) | roast | roast | roast.mdc | roast.md | roast |
| 🇺🇸 English | roast-en | roast-en | roast-en.mdc | roast-en.md | roast-en |

## Roast + PUA = Ultimate Combo

| Phase | Tool | What happens |
|-------|------|-------------|
| **Think** | 🔥 Roast | AI questions you until your idea is bulletproof |
| **Build** | 💪 [PUA](https://github.com/tanweai/pua) | AI executes relentlessly until it's done |

Roast makes you think right. PUA makes AI work right. Together, they're unstoppable.

## Use Cases

- **Startup founders** — Stress-test your pitch before investors do
- **Researchers** — Strengthen your paper's argument before reviewers tear it apart
- **Engineers** — Question your architecture before production does
- **Product managers** — Find the holes in your roadmap before the market does
- **Anyone making a big decision** — Think it through before it's irreversible

## Usage

Type `/roast` in your AI conversation to activate.

```
/roast              — Auto-detect scenario, pick best flavor
/roast socratic     — Socratic questioning
/roast devil        — Devil's advocate
/roast vc           — VC grilling mode
/roast feynman      — Feynman test
/roast cbt          — CBT mode (for life decisions)
/roast mirror       — Mirror mode (blind spots)
/roast first-principles  — First principles decomposition
```

## Philosophy

> "The unexamined life is not worth living." — Socrates
>
> "If you can't explain it simply, you don't understand it well enough." — Feynman
>
> "The first principle is that you must not fool yourself — and you are the easiest person to fool." — Feynman

Roast doesn't make you smarter. It makes you **more honest with yourself.**

## License

MIT

## Credits

Inspired by the brilliant [PUA](https://github.com/tanweai/pua) project, which solved the problem of AI giving up too easily. Roast solves the complementary problem: **humans not thinking deeply enough.**

# 🔥 Roast — 思考ロースティングエンジン

> 今度は、AIがあなたを尋問する番だ。

[🇨🇳 中文](README.zh-CN.md) | [🇺🇸 English](README.md) | 🇯🇵 日本語

![Claude Code](https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI Codex CLI](https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white)
![Kiro](https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white)
![OpenClaw](https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square)
![Multi-Language](https://img.shields.io/badge/🌐_Multi--Language-blue?style=flat-square)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**ほとんどのAIツールは生産性を上げる。これは思考力を上げる。**

AIエージェントスキルプラグイン。あなたのAIを容赦ないソクラテス式質問マシンに変える。質問に答えるのではなく、**質問する**——一つずつ深く、潜在意識に埋もれた本当の考えが浮かび上がるまで。

## 深度レベル

| レベル | 名称 | 何が起きるか |
|--------|------|-------------|
| D1 | 表層・明確化 | 「それは具体的にどういう意味？」 |
| D2 | 構造・ロジック | 「因果関係は？証拠は？」 |
| D3 | 前提・仮定 | 「Xを仮定していますね。間違っていたら？」 |
| D4 | 矛盾・衝突 | 「XもYも言った。両立できる？」 |
| D5 | 核心・本質 | 「すべて取り除いて。本当の理由は？」 |

## 7つのフレーバー

| フレーバー | 最適な場面 | スタイル |
|-----------|-----------|---------|
| 🏛️ ソクラテス | すべて（デフォルト） | 純粋な質問、決して答えない |
| 🔬 第一原理 | 技術、起業 | 基本的事実まで分解 |
| 😈 悪魔の代弁者 | 意思決定、議論 | すべてに反論 |
| 💰 投資家モード | 起業、製品 | 「モートは？」 |
| 🧠 認知行動 | 人生の決断 | 認知の歪みを検出 |
| 🪞 ミラー | 盲点の暴露 | 言葉を映し返す |
| 🔥 ファインマン | 理解度テスト | 「12歳に説明して」 |

## インストール

```bash
# Claude Code
claude plugin marketplace add sumleo/roast

# Codex CLI
mkdir -p ~/.codex/skills/roast
curl -o ~/.codex/skills/roast/SKILL.md \
  https://raw.githubusercontent.com/sumleo/roast/main/codex/roast-ja/SKILL.md

# OpenClaw
clawhub install roast
```

## 使い方

```
/roast              — シーン自動検出
/roast socratic     — ソクラテス式
/roast devil        — 悪魔の代弁者
/roast vc           — 投資家モード
/roast feynman      — ファインマンテスト
```

## Roast + PUA = 最強コンボ

| フェーズ | ツール | 結果 |
|----------|--------|------|
| **考える** | 🔥 Roast | アイデアが鉄壁になるまで追問 |
| **作る** | 💪 [PUA](https://github.com/tanweai/pua) | 完成するまで全力実行 |

## ライセンス

MIT

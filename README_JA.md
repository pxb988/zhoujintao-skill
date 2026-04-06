# pxb-zhoujintao

> 中国語文脈での景気循環の位置判断に向けた、周金涛視点の skill。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude%20Code-Skill](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![skills.sh-Compatible](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

**Other Languages:** [简体中文](README.md) · [English](README_EN.md) · [한국어](README_KO.md) · [Español](README_ES.md)

---

## 概要

`pxb-zhoujintao` は、周金涛の循環分析フレームワークを再利用可能な Claude Code skill として整理したものです。

これは人格模倣のための skill ではありません。公開資料から再利用可能な要素を抽出し、主に次の内容を扱います。

- 循環の位置判断
- ドライバーと伝導チェーンの分析
- 位相とタイムラグの判断
- 資産 / 業種へのマッピング
- リスク境界の整理

したがって、この skill は「いまどの局面にいるのか」「なぜ一部データの改善が全面回復を意味しないのか」といった問いに向いており、人物伝記、強いロールプレイ、短期的な相場総括には向きません。

---

## 効果例

### 例 1

**ユーザー：** 今の中国経済はどの段階にありますか？

**Skill：** まず「もう回復した」と結論づけるべきではありません。重要なのは先に循環上の位置を定めることです。見えているのが短期循環の修復なのか、それとも中期循環での新しい拡張なのか。もし不動産、信用、設備投資がまだリレーを形成していないなら、それは新しい周期の確認というより修復局面に近いです。

### 例 2

**ユーザー：** データは少し改善しているのに、なぜ市場はまだ本格的に上がらないのですか？

**Skill：** 一部の改善はシステム全体の回復とは違うからです。このフレームワークは、各ドライバーが順番に受け渡されているか、先行指標が遅行指標へ伝導しているか、いまの改善が始まり・途中・終盤のどこにあるのかを見ます。

### 例 3

**ユーザー：** 周金涛の枠組みで今は何を観察すべきですか？

**Skill：** 先に位置を定め、その次にドライバーを見ます。単独の指標を見るのではなく、不動産、貨幣/信用、在庫、設備投資が明確な伝導順序を作っているかを見るべきです。そうでなければ、全面回復と呼ぶにはまだ早いです。

---

## インストール

```bash
npx skills add pxb988/zhoujintao-skill
```

---

## 利用シーン

- 中国の現在の循環局面を判断する
- 弱い修復、偽の底、先走り回復、新しい拡張を区別する
- ドライバー、伝導チェーン、先行 / 遅行関係を分析する
- マクロ局面を業種や資産クラスに対応づける
- 結論が成り立つためのリスク境界を整理する

---

## 方法について

この skill の蒸留方法は `huashu-nuwa` が提供し、現在の内容は整理済みの公開資料にもとづいて完成されています。

目的は分析の骨格、意思決定ヒューリスティクス、表現上の制約を再現することであり、人物そのものを完全に模倣することではありません。

---

## リポジトリ構成

```text
zhoujintao-skill/
├── SKILL.md
├── README.md
├── README_EN.md
├── README_JA.md
├── README_KO.md
├── README_ES.md
├── LICENSE
└── references/
    └── research/
```

---

## 研究範囲

公開リポジトリに含まれるのは次のみです。

- `SKILL.md`
- 多言語 README
- `LICENSE`
- `references/research/`

含まれないもの：

- `references/sources/`
- `evals/`
- workspace や内部補助ディレクトリ

---

## ライセンス

MIT

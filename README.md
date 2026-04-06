# pxb-zhoujintao

> 一个面向中国语境的周金涛周期分析视角 skill。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude%20Code-Skill](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![skills.sh-Compatible](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

**Other Languages:** [English](README_EN.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

---

## Skill 简介

`pxb-zhoujintao` 是一个把周金涛周期分析框架整理为可直接调用的 Claude Code skill。

它关注的不是人格模仿，而是把公开资料中可复用的部分提炼出来，包括：

- 周期定位
- 驱动力与传导链条拆解
- 相位与时滞判断
- 资产 / 行业映射
- 风险边界收束

因此，这个 skill 更适合回答“现在处在什么位置”“为什么局部修复不等于全面复苏”这一类问题，而不是做人物传记、强拟人扮演或短线盘后复盘。

---

## 效果示例

### 示例 1

**用户：** 现在中国经济大概处于什么阶段？

**Skill：** 先不要急着下“已经复苏”这个结论。更关键的是先做周期定位：当前看到的到底是短周期修复，还是中周期意义上的新扩张。如果只是局部变量改善，而地产、信用、资本开支之间还没有形成接力，那么它更像修复中的一段，而不是新周期的确认。

### 示例 2

**用户：** 为什么数据有些修复了，市场还是没起来？

**Skill：** 因为局部修复不等于系统复苏。周金涛式的框架看的是驱动力有没有接力、领先变量有没有向滞后变量传导，以及当前改善究竟是起点、途中还是尾声。单个数据改善，可能只是情绪修复，还不足以支持更大的周期切换。

### 示例 3

**用户：** 如果按周金涛的框架，现在应该重点观察什么？

**Skill：** 先看定位，再看动力。重点不是孤立看一个指标，而是看地产、货币/信用、库存、资本开支这些变量之间有没有形成顺序清晰的传导链条；如果没有，就要对“全面复苏”保持克制。

---

## 安装

```bash
npx skills add pxb988/zhoujintao-skill
```

安装后即可在 Claude Code 中直接调用或按场景触发。

---

## 适用场景

- 判断中国语境下的周期位置
- 区分弱修复、假底、抢跑复苏与新扩张
- 分析驱动力、传导链条与领先/滞后关系
- 讨论行业轮动与大类资产映射
- 梳理结论成立所依赖的风险边界

---

## 方法说明

本 skill 的蒸馏方法由 `huashu-nuwa` 提供，当前内容结合已整理的公开资料完成。

这意味着它优先还原的是分析框架、决策启发式与表达约束，而不是追求对人物本人的完整模仿。

---

## 仓库结构

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

## 研究说明

公开仓库仅包含：

- skill 本体 `SKILL.md`
- 中英日韩西五份 README
- `LICENSE`
- `references/research/` 研究沉淀

不公开的内容包括：

- `references/sources/`
- `evals/`
- workspace 与内部辅助目录

---

## 许可证

MIT

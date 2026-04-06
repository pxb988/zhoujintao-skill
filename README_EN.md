<div align="center">

# 周金涛.skill

> *"Position first, drivers second; sequence first, conclusions second."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**A Zhou Jintao-inspired cycle analysis skill for China-specific macro positioning.**

<br>

It does not imitate the person. It distills Zhou Jintao's cycle framework,
decision heuristics, and expression constraints into a reusable skill.<br>
It is best for questions like “where are we in the cycle?” or “why doesn't
partial repair mean full recovery?”

[Examples](#example-outputs) · [Installation](#installation) · [Use Cases](#use-cases) · [Methodology](#methodology)

<br>

**Other Languages:**

[简体中文](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

---

## Overview

`pxb-zhoujintao` turns Zhou Jintao's cycle-analysis framework into a reusable Claude Code skill.

It is not for persona imitation. It distills reusable parts from public materials, including:

- cycle positioning
- driver and transmission-chain analysis
- phase and time-lag judgment
- asset / sector mapping
- risk boundary framing

So this skill is best for questions like “where are we in the cycle?” or “why does partial data repair not mean full recovery?”, rather than biography, hard roleplay, or short-term market recap.

---

## Example Outputs

```
User               ❯ What stage is China in right now?

周金涛.skill        ❯ Don't jump straight to “recovery” first. The key is cycle
                     positioning: are we seeing a short-cycle repair, or a genuine
                     new expansion in the medium cycle? If property, credit, and
                     capex have not yet formed a relay, this looks more like a
                     repair phase than a confirmed new cycle.
```

```
User               ❯ Why has some data improved, but markets still haven't really moved?

周金涛.skill        ❯ Because partial improvement is not the same as system-wide
                     recovery. This framework asks whether the drivers are handing
                     off properly, whether leading indicators are transmitting into
                     lagging ones, and whether the current improvement is the
                     beginning, middle, or end of a process.
```

```
User               ❯ What should we watch now under Zhou Jintao's framework?

周金涛.skill        ❯ Position first, drivers second. The point is not to isolate
                     one indicator, but to see whether property, money/credit,
                     inventory, and capex are forming a clear transmission
                     sequence. If not, it is too early to call full recovery.
```

---

## Installation

```bash
npx skills add pxb988/zhoujintao-skill
```

---

## Use Cases

- Positioning China's current cycle stage
- Distinguishing weak repair, false bottom, front-run recovery, and new expansion
- Analyzing drivers, transmission chains, and lead-lag relationships
- Mapping macro phases to sectors and asset classes
- Defining the risk boundaries behind a conclusion

---

## Methodology

The distillation methodology for this skill is provided by `huashu-nuwa`, and the current content is completed using organized public materials.

The goal is to recover analytical structure, decision heuristics, and expression constraints — not to imitate the full persona.

---

## Repository Structure

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

## License

MIT

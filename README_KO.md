<div align="center">

# 周金涛.skill

> *"먼저 위치를 보고, 다음에 동인을 본다. 먼저 순서를 보고, 그다음 결론을 내린다."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude%20Code-Skill](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![skills.sh-Compatible](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**중국 맥락에서의 경기 순환 위치 판단을 위한 주금도 관점 skill.**

<br>

**Other Languages:**

[简体中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [Español](README_ES.md)

</div>

---

## 소개

`pxb-zhoujintao` 는 주금도의 경기 순환 분석 프레임워크를 재사용 가능한 Claude Code skill 로 정리한 것입니다.

이 skill 은 인물 모방을 위한 것이 아닙니다. 공개 자료에서 재사용 가능한 부분을 추려 다음과 같은 내용을 다룹니다.

- 순환 위치 판단
- 동인과 전달 체인 분석
- 국면과 시차 판단
- 자산 / 업종 매핑
- 리스크 경계 정리

따라서 이 skill 은 “지금 어느 위치에 있는가”, “왜 일부 지표의 회복이 전면적 회복을 뜻하지 않는가” 같은 질문에 더 적합하며, 인물 전기, 강한 롤플레잉, 단기 장 마감 해설용은 아닙니다.

---

## 예시

### 예시 1

**사용자:** 지금 중국 경제는 어느 단계에 있나요?

**Skill:** 먼저 “이미 회복됐다”는 결론부터 내리면 안 됩니다. 핵심은 먼저 순환상 위치를 정하는 것입니다. 지금 보이는 것이 단기 순환의 회복인지, 아니면 중기 순환의 새로운 확장인지 봐야 합니다. 부동산, 신용, 설비투자가 아직 릴레이를 이루지 못했다면, 그것은 새로운 사이클의 확인이라기보다 회복 구간에 가깝습니다.

### 예시 2

**사용자:** 일부 데이터는 좋아졌는데 왜 시장은 아직 크게 움직이지 않나요?

**Skill:** 부분적 개선은 시스템 전체의 회복과 같지 않기 때문입니다. 이 프레임워크는 동인들이 순서대로 이어지고 있는지, 선행 지표가 후행 지표로 전달되고 있는지, 현재의 개선이 시작·중간·말기 중 어디에 있는지를 봅니다.

### 예시 3

**사용자:** 주금도 프레임워크로 보면 지금 무엇을 봐야 하나요?

**Skill:** 먼저 위치를 보고, 그다음 동인을 봐야 합니다. 하나의 지표를 따로 떼어 보기보다, 부동산, 통화/신용, 재고, 설비투자가 명확한 전달 순서를 만들고 있는지를 보는 것이 중요합니다. 그렇지 않다면 전면적 회복이라고 부르기에는 아직 이릅니다.

---

## 설치

```bash
npx skills add pxb988/zhoujintao-skill
```

---

## 사용 장면

- 중국의 현재 경기 순환 위치 판단
- 약한 회복, 가짜 바닥, 선행 회복, 새로운 확장을 구분
- 동인, 전달 체인, 선행 / 후행 관계 분석
- 거시 국면을 업종과 자산군에 매핑
- 결론이 성립하는 리스크 경계 정리

---

## 방법론

이 skill 의 증류 방법론은 `huashu-nuwa` 가 제공하며, 현재 내용은 정리된 공개 자료를 바탕으로 완성되었습니다.

목표는 분석 구조, 의사결정 휴리스틱, 표현상의 제약을 복원하는 것이지, 인물 자체를 완전히 모방하는 것이 아닙니다.

---

## 저장소 구조

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

## 라이선스

MIT

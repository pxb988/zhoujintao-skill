<div align="center">

# 周金涛.skill

> *"Primero ubicar la posición; después, analizar los impulsores. Primero ver la secuencia; después, sacar conclusiones."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Un skill de perspectiva de Zhou Jintao para ubicar ciclos en el contexto de China.**

<br>

No imita a la persona. Destila el marco de ciclo de Zhou Jintao, sus
heurísticas de decisión y sus restricciones expresivas en un skill reutilizable.<br>
Sirve mejor para preguntas como “¿en qué punto del ciclo estamos?” o
“¿por qué una reparación parcial no significa una recuperación total?”.

[Efectos](#ejemplos) · [Instalación](#instalación) · [Casos de uso](#casos-de-uso) · [Metodología](#metodología)

<br>

**Other Languages:**

[简体中文](README.md) · [English](README_EN.md) · [日本語](README_JA.md) · [한국어](README_KO.md)

</div>

---

## Descripción general

`pxb-zhoujintao` convierte el marco de análisis de ciclos de Zhou Jintao en un skill reutilizable para Claude Code.

No es un skill de imitación de personalidad. Destila las partes reutilizables de materiales públicos, entre ellas:

- ubicación del ciclo
- análisis de impulsores y cadena de transmisión
- juicio de fase y desfases temporales
- mapeo hacia activos / sectores
- delimitación de riesgos

Por eso, este skill sirve mejor para preguntas como “¿en qué punto del ciclo estamos?” o “¿por qué una mejora parcial de datos no significa una recuperación total?”, y no para biografía, roleplay fuerte o resúmenes de mercado de muy corto plazo.

---

## Ejemplos

```
Usuario            ❯ ¿En qué etapa está ahora la economía china?

周金涛.skill       ❯ No conviene saltar de inmediato a la conclusión de “ya se
                  recuperó”. Lo primero es ubicar el ciclo: ¿estamos viendo una
                  reparación de corto ciclo o una nueva expansión real en el
                  ciclo medio? Si inmobiliario, crédito y capex todavía no forman
                  un relevo, esto se parece más a una fase de reparación que a un
                  nuevo ciclo confirmado.
```

```
Usuario            ❯ ¿Por qué algunos datos mejoraron, pero el mercado aún no arranca?

周金涛.skill       ❯ Porque una mejora parcial no equivale a una recuperación
                  sistémica. Este marco pregunta si los impulsores se están
                  relevando correctamente, si los indicadores adelantados se
                  transmiten a los rezagados y si la mejora actual está al
                  comienzo, en medio o al final del proceso.
```

```
Usuario            ❯ Según el marco de Zhou Jintao, ¿qué deberíamos vigilar ahora?

周金涛.skill       ❯ Primero la ubicación, después los impulsores. El punto no
                  es aislar un solo indicador, sino ver si inmobiliario,
                  dinero/crédito, inventarios y capex están formando una
                  secuencia clara de transmisión. Si no, aún es pronto para
                  hablar de recuperación total.
```

---

## Instalación

```bash
npx skills add pxb988/zhoujintao-skill
```

---

## Casos de uso

- Ubicar la etapa actual del ciclo en China
- Distinguir entre reparación débil, falso fondo, recuperación adelantada y nueva expansión
- Analizar impulsores, cadenas de transmisión y relaciones líder-rezagado
- Mapear fases macro a sectores y clases de activos
- Definir los límites de riesgo detrás de una conclusión

---

## Metodología

La metodología de destilación de este skill es provista por `huashu-nuwa`, y el contenido actual se completó a partir de materiales públicos ya organizados.

El objetivo es recuperar la estructura analítica, las heurísticas de decisión y las restricciones expresivas, no imitar por completo a la persona.

---

## Estructura del repositorio

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

## Licencia

MIT

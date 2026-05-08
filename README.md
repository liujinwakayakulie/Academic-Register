# Academic Register Skill

[English](#english) | [中文文档](./README_CN.md)

---

## What is this?

A prompt skill that strips **"AI flavor"** from LLM-generated text and polishes it into proper **academic register** — the conventional style required in essays, reports, dissertations, and theses.

## Why do you need it?

LLM-generated text often suffers from:

- Adjective stacking and flowery language
- Emotionally charged or exaggerated expressions
- Overly strong claims without sufficient evidence
- Colloquial or informal phrasing

Academic writing, by contrast, demands four qualities: **objectivity, formality, precision, and tentativeness**.

## Core Principles

Adapted from the [University of Sunderland Academic Writing Guide](https://libraryguides.sunderland.ac.uk/academic-writing/academic-register). Each revision is checked against four dimensions:

| Principle | Description |
|-----------|-------------|
| **Objective** | Evidence-based, neutral language; third-person perspective; no value judgments |
| **Formal** | No colloquialisms, contractions, or slang; proper grammar throughout |
| **Precise** | Eliminate redundancy and ambiguity; one idea per sentence |
| **Tentative** | Hedge claims to match evidence strength — *may, might, seems, appears to, suggests* |

## How to use

1. Place `AcademicRegister.md` in your project or Claude Code skills directory.
2. Reference it with `@AcademicRegister.md` when asking an AI to polish your text.
3. The AI will revise your writing against the four principles, listing each change with its justification.

## Example

**Before (AI-generated):**
> 感知有用性作为一个核心的、关键性的重要中介变量，深刻揭示了其在整个机制中举足轻重的传导角色。

**After (Academic register):**
> 感知有用性在感知AI暴露度与持续使用意愿之间起显著中介作用。

## Credit

Adapted from [University of Sunderland — Study Skills: Academic Register](https://libraryguides.sunderland.ac.uk/academic-writing/academic-register).

## License

MIT

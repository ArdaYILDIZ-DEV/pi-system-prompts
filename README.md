# pi-system-prompts

Curated, role-specialized system prompts for Pi agent personas.

## Personas

| File | Persona | Role |
|---|---|---|
| `Aster-Strategy-Deep.md` | Aster | Strategy, architectural trade-offs, reversibility analysis, and red-teaming |
| `Caelum-Adversarial-Deep.md` | Caelum | Adversarial sparring partner and dialectical hypothesis testing |
| `Elyndra-Agent-Deep.md` | Elyndra | Disciplined agentic task execution, strict tool permissions, and verification |
| `Kaida-Entertainment-Pocket.md` | Kaida | Entertainment, pop culture, Watcharr CLI integration, and spoiler safeguards |
| `Liora-Companion-Deep.md` | Liora | Thoughtful conversation partner for ideas and writing with explicit boundaries |
| `Neris-Research-Deep.md` | Neris | Evidence-driven research, intelligence analysis, and multi-source verification |

## Usage

Set a persona as the active system prompt by copying or linking it to `SYSTEM.md` in your Pi agent directory (`~/.pi/agent/`):

```sh
cp Elyndra-Agent-Deep.md ~/.pi/agent/SYSTEM.md
```

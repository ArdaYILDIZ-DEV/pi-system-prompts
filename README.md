# pi-system-prompts

Curated, role-specialized system prompts for Pi agent personas.

Choose the role by the question you need answered, not by the desired response length. `Deep` favors careful reasoning; `Pocket` favors low-overhead conversation. Neither imposes a fixed answer length.

## Personas

| Persona | Use it for | Prompt |
|---|---|---|
| Aster | Deciding what to do: strategy, architecture, trade-offs, and reversible commitments | [Aster-Strategy-Deep.md](Aster-Strategy-Deep.md) |
| Elyndra | Carrying out scoped technical work with approval gates and outcome verification | [Elyndra-Agent-Deep.md](Elyndra-Agent-Deep.md) |
| Kaida | Entertainment discussion, recommendations, spoiler control, and authorized Watcharr operations | [Kaida-Entertainment-Pocket.md](Kaida-Entertainment-Pocket.md) |
| Neris | Establishing what the evidence supports: research, source evaluation, and synthesis | [Neris-Research-Deep.md](Neris-Research-Deep.md) |

For mixed tasks, use Neris to establish the evidence, Aster to choose a direction, and Elyndra to implement an approved decision. Not every task needs all three.

## Usage

Set a persona as the active system prompt by copying or linking it to `SYSTEM.md` in your Pi agent directory (`~/.pi/agent/`):

```sh
cp Elyndra-Agent-Deep.md ~/.pi/agent/SYSTEM.md
```

# IB DP Physics Skills

Three reusable [Agent Skills](https://agentskills.io/specification) for IB Diploma Programme Physics SL and HL, aligned with the course first assessed in 2025. The paper skills focus on marking and worked feedback. The IA skill helps students plan, write and review their own scientific investigations.

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1](.agents/skills/ib-physics-paper-1/SKILL.md) | “Mark my IB Physics Paper 1B SL answers using this markscheme.” | `$ib-physics-paper-1` |
| [Paper 2](.agents/skills/ib-physics-paper-2/SKILL.md) | “Grade my Physics Paper 2 HL working and explain where I lost marks.” | `$ib-physics-paper-2` |
| [Internal assessment](.agents/skills/ib-physics-ia/SKILL.md) | “Help me plan a Physics IA about how temperature affects the resistance of a wire.” | `$ib-physics-ia` |

## Install and use

Clone or download the repository and open it as a Codex workspace. Codex discovers the skills under `.agents/skills/`. To use a skill across projects, copy its entire folder, including `references/`, to `~/.agents/skills/`. For another Agent Skills-compatible host, follow its skill installation instructions.

Once installed, the assessment names in the skill descriptions help the host choose the relevant skill from ordinary prompts. Selection depends on the host and prompt context. The explicit invocations above select a specific skill in Codex. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

For marking a real paper, supply the questions, your answers and the matching markscheme if available. For an IA draft review, include any tables, graphs and analysis the agent needs to evaluate. The skills also provide clearly labeled provisional feedback when official marking materials are unavailable.

## Sources and license

The primary source is the IB *Physics guide*, first assessment 2025, updated November 2024. Relevant printed pages are 28–32 for practical and mathematical skills, 62–65 for the exams, 66–75 for the IA, and 76–77 for command terms. The May 2023 correction on p. 80 sets SL Paper 2 to 50 marks. Each skill adds original study guidance and summarizes the applicable assessment rules. The guide, exam questions and official markschemes remain available from the IB or through your school. [IB Physics course overview](https://www.ibo.org/programmes/diploma-programme/curriculum/sciences/physics/) · [IB specimen papers and markschemes](https://ibo.org/globalassets/new-structure/programmes/dp/pdfs/physics-hl-sl-specimen-papers-1a-2b-2-en.pdf)

This independent resource is available under the [MIT License](LICENSE) for its original material.

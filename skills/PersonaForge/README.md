# PersonaGAN-Distill

`PersonaGAN-Distill` is a persona distillation workflow built on top of `nuwa-skill`, with an added GAN-style adversarial validation layer for improving distilled personality frameworks.

Instead of stopping at "collect materials -> summarize traits -> write a skill", this project introduces a `Generator / Discriminator` loop:

- `Generator`: distills mental models, decision heuristics, expression DNA, and value tensions from source material.
- `Discriminator`: challenges those distilled outputs for accuracy, distinctiveness, evidence strength, and compactness.
- Iteration: the distilled persona is refined until it better matches the target subject's real cognitive style.

## What This Project Contains

- A base `SKILL.md` workflow inherited from the `nuwa-skill` idea of building runnable persona skills from public information.
- A GAN-enhanced distillation framework in [references/GAN-distill-framework.md](/F:/nuwa-skill/references/GAN-distill-framework.md).
- A general extraction methodology in [references/extraction-framework.md](/F:/nuwa-skill/references/extraction-framework.md).
- Supporting scripts for subtitle cleanup, research merging, and quality checks in [scripts](/F:/nuwa-skill/scripts).

## Core Idea

Traditional persona distillation usually has one weak point: the extracted "personality" is easy to become generic, over-compressed, or loosely grounded in evidence.

PersonaGAN-Distill addresses that by adding adversarial review during the extraction stage:

1. Collect multi-source research data.
2. Generate candidate mental models and style patterns.
3. Use a discriminator to attack weak claims, vague wording, and non-distinctive abstractions.
4. Iterate until the persona description is more faithful and more usable.

The goal is not role-play for its own sake, but a more robust way to distill:

- how a person thinks
- how they make decisions
- how they express ideas
- where their framework breaks down

## Usage

PersonaGAN-Distill is designed to be used with AI coding agents (such as opencode or codex) that can follow multi-step workflow instructions.

### Workflow Overview

1. **Setup**: Clone this repository and ensure your AI agent has access to the `SKILL.md` workflow instructions and `references/` framework files.
2. **Load the Skill**: Instruct your AI agent to load the persona-building skill (the `SKILL.md` file at the repository root defines the complete "Nuwa Skill Creation" workflow).
3. **Provide a Target**: Give the agent a person's name (e.g., "distill Sam Altman"). The agent will follow the 6-phase pipeline described in `SKILL.md`.
4. **Review Checkpoints**: The workflow includes built-in checkpoints (Phase 1.5, Phase 2.6, Phase 4) where you can review intermediate results and provide feedback.
5. **Optional GAN Mode**: For important subjects with 50+ public sources, enable GAN adversarial validation for higher fidelity distillation.

### Quick Start Example

```text
User: Distill Sam Altman using the PersonaGAN-Distill workflow.

Agent: (Executes Phase 0.5 → Phase 1 with 6 parallel research agents → 
        Phase 1.5 checkpoint → Phase 2 synthesis → 
        Phase 2.5 GAN discriminator → Phase 3 build → 
        Phase 4 quality verification)
```

The output is a complete persona skill under `.claude/skills/[person-name]-perspective/` containing the SKILL.md and all research files.

### Requirements

- An AI agent capable of multi-step task execution, web search, and file writing.
- For the GAN discriminator phase, the agent must be able to spawn sub-agents for adversarial evaluation.
- Python 3.x for the utility scripts in `scripts/` (subtitle processing, quality checks, research merging).

### Current Limitations

- **Testing scope**: This workflow has only been tested with **opencode** and **codex** as the execution agents. Compatibility with other AI coding tools is unverified.
- **Project maturity**: This is a research/workflow project, not a packaged software product. Expect rough edges and missing automation.
- **Optimization needed**: The pipeline works end-to-end but could benefit from better error handling, agent timeout management, and source validation automation.

## Repository Structure

```text
PersonaGAN-Distill/
├── README.md
├── SKILL.md
├── references/
│   ├── GAN-distill-framework.md
│   ├── extraction-framework.md
│   └── skill-template.md
├── scripts/
│   ├── download_subtitles.sh
│   ├── merge_research.py
│   ├── quality_check.py
│   └── srt_to_transcript.py
└── docs/
    └── archive/
```

## Notes

- This repository is currently organized as a research/workflow project rather than a packaged software product.
- Some original upstream presentation materials have been preserved under [docs/archive](/F:/nuwa-skill/docs/archive).
- The current project name is temporarily `PersonaGAN-Distill`.

## Acknowledgement

This project is derived from the workflow ideas of `nuwa-skill`, and extends them with adversarial validation for persona distillation.

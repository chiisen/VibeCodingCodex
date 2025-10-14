# Agent Playbook

## Quick Summary
- Repository hosts a futuristic-themed one-page introduction to OpenAI Codex for Traditional Chinese readers.
- Core deliverable lives at `docs/index.html`; supporting assets in `images/`, process docs in `openspec/`.
- Follow instructions in this file and `openspec/project.md` before modifying content.

## Primary Artifacts
- `docs/index.html`: Single-page microsite. Preserve structure (hero, core value, quickstart, capability map, resource navigation) and neon dark-mode styling.
- `STYLE.md`: Design cue — maintain "未來科技風" palette, typography, and layout tone when expanding visuals.
- `openspec/project.md`: Canonical context for scope, constraints, and workflow.

## Style Guardrails
- Keep HTML semantic; prefer sections with descriptive headings and consistent Orbitron/Inter typography usage.
- Use CSS custom properties (`--accent`, `--bg-primary`, etc.) when adding colors to maintain theme cohesion.
- Limit animations; subtle hover/transition effects only. Avoid heavy scripts or frameworks.
- Content language stays zh-Hant; technical keywords may remain in English when common in developer discourse.

## Workflow Expectations
- Before implementation, confirm no outstanding change proposals in `openspec/changes/`.
- For new capabilities or multi-page expansions, draft an OpenSpec change (`openspec AGENTS.md` for guidance) and wait for approval.
- Run link validation or manual checks after edits; document verification steps in summaries.
- Never remove the OpenSpec managed block below.

## Quality Checklist
- [ ] Sections remain responsive down to 360px width (check flex/grid fallbacks).
- [ ] External links point to current OpenAI Codex resources.
- [ ] Typography loads gracefully with/without Google Fonts (ensure sensible fallbacks).
- [ ] Adhere to repository constraints: no build steps, no third-party scripts, under 100KB HTML/CSS.

## Communication Notes
- Summaries to maintainers should highlight content changes, design impacts, and any follow-up verification done.
- Flag deviations from project constraints early (e.g., need for additional assets or scripts).

<!-- OPENSPEC:START -->
# OpenSpec Instructions

These instructions are for AI assistants working in this project.

Always open `@/openspec/AGENTS.md` when the request:
- Mentions planning or proposals (words like proposal, spec, change, plan)
- Introduces new capabilities, breaking changes, architecture shifts, or big performance/security work
- Sounds ambiguous and you need the authoritative spec before coding

Use `@/openspec/AGENTS.md` to learn:
- How to create and apply change proposals
- Spec format and conventions
- Project structure and guidelines

Keep this managed block so 'openspec update' can refresh the instructions.

<!-- OPENSPEC:END -->

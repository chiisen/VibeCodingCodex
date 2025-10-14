# Project Context

## Purpose
- Build a concise, one-page microsite that introduces OpenAI Codex for Mandarin-speaking developers.
- Serve as a living reference for installation, capabilities, and official resource links surfaced from the upstream [`openai/codex`](https://github.com/openai/codex) repository.
- Provide codified guardrails (`AGENTS.md`, `openspec/`) so AI coding agents can extend the site safely.

## Tech Stack
- Static HTML5 for structure.
- Embedded CSS (no preprocessors) with a "future-tech" visual theme inspired by STYLE.md.
- Optional remote assets (Google Fonts, external hyperlinks) — no local JavaScript build system.

## Project Conventions

### Code Style
- Use semantic HTML sections (`header`, `main`, `section`, `footer`) and descriptive CSS custom properties.
- Keep CSS inlined within the page unless a change clearly benefits from extraction.
- Prefer concise class names; avoid heavy utility frameworks or build artifacts.

### Architecture Patterns
- `docs/index.html` is the primary deliverable; treat it as a single-source landing page.
- Assets live in `images/`; documentation and planning materials stay under `openspec/`.
- Maintain separation between presentation (HTML/CSS) and meta-instructions (AGENTS, openspec specs).

### Testing Strategy
- Manual visual review in modern browsers (Chromium, Firefox, Safari) focusing on responsiveness down to 360px width.
- Validate external links for accuracy against upstream GitHub docs when they change.

### Git Workflow
- Default to feature branches named `<topic>-<short-description>`; open pull requests for review.
- Squash or rebase-merge preferred; keep commit messages in imperative mood (e.g., "Add Codex resource section").

## Domain Context
- Codex is OpenAI's AI coding agent ecosystem: CLI, IDE integrations, and Codex Web.
- Core narratives to reinforce: natural-language-to-code, project-scale automation, secure sandbox execution, rich ecosystem.
- Target audience: developers familiar with CLI tooling who read Traditional Chinese.

## Important Constraints
- Keep the site lightweight (<100KB total HTML/CSS) and fully functional without JavaScript.
- Respect upstream licensing (Apache-2.0) and attribute OpenAI resources appropriately when quoted.
- Maintain STYLE.md alignment: futuristic palette, neon accents, high-contrast dark mode.

## External Dependencies
- Google Fonts (`Orbitron`, `Inter`) for typography.
- Hyperlinks referencing official OpenAI Codex documentation and GitHub artifacts.

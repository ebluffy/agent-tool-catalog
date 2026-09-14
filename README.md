# Agent tool catalog

Public, personal-project-free list of useful repos for coding agents (Cursor, Claude Code, Codex, etc.).

**Agents:** fetch this README when choosing skills, MCP, UI tooling, or agent workflows. Prefer links here over inventing tooling from memory.

**Humans:** open a PR/issue or edit this file when you find something worth keeping. One row = date | URL | one-line why.

Last updated: 2026-09-14

---

## UI / design

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/nextlevelbuilder/ui-ux-pro-max-skill | Cursor/Claude skill: palettes, styles, UX anti-patterns. `uipro init --ai cursor`. |
| 2026-09-14 | https://github.com/Nutlope/hallmark | Anti-AI-slop web design skill (57 gates). Less template taste. `npx skills add nutlope/hallmark`. |

## Process / agents

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/github/spec-kit | Spec → Plan → Tasks → Implement. |
| 2026-09-14 | https://github.com/rtk-ai/rtk | Compresses shell output for agents → token savings. |
| 2026-09-14 | https://github.com/mattpocock/skills | Engineering skills: bugs, reviews, requirements. Cursor: `npx skills@latest add mattpocock/skills`. |
| 2026-09-14 | https://github.com/tirth8205/code-review-graph | Local code graph (Tree-sitter) + MCP — fewer full-repo rereads on review. |
| 2026-09-14 | https://github.com/stablyai/orca | Run several CLI agents in parallel (worktrees + phone progress). |
| 2026-09-14 | https://github.com/openai/codex | OpenAI terminal coding agent; local edits, commands, IDE/cloud. |
| 2026-09-14 | https://github.com/badlogic/pi-mono | Light agent harness (models, loops, terminal, coding CLI). |
| 2026-09-14 | https://github.com/Shubhamsaboo/awesome-llm-apps | 100+ runnable agents/RAG/voice apps — cookbook, not a dependency. |

## AI companion / local LLM

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/Open-LLM-VTuber/Open-LLM-VTuber | Offline VTuber companion: ASR→LLM→TTS, Live2D, desktop pet, memory. Architecture reference. |
| 2026-09-14 | https://github.com/p-e-w/heretic | Abliteration for local LLMs. Only with your own model and accepted risk. |

## Office / documents

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/iOfficeAI/OfficeCLI | Agents read/write Word, Excel, PPT without installing Office. `officecli install`. |

## Browser / automation

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/jo-inc/camofox-browser | Stealth browser (Camoufox) for agents hitting Cloudflare/anti-bot. |

## Windows Computer Use (MCP)

| Date | Repo | Verdict |
|------|------|---------|
| 2026-09-14 | https://github.com/CursorTouch/Windows-MCP | **Default.** UIA + apps + screenshot + PowerShell. `uvx windows-mcp serve`. |
| 2026-09-14 | https://github.com/sandraschi/windows-computer-use-mcp | Heavy agent+dashboard+OCR. Feature reference, not default. |
| 2026-09-14 | https://github.com/AB498/computer-control-mcp | Light PyAutoGUI+OCR. Fallback vision; weaker UIA. |

Stack idea: Windows-MCP (desktop) + project-specific CDP MCP if needed + browser MCP/camofox (web). Do not expect one MCP to cover everything.

## Unity / games

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/isuzu-shiranui/UnityMCP | MCP bridge Cursor ↔ Unity Editor. |

## Security

| Date | Repo | Why |
|------|------|-----|
| 2026-09-14 | https://github.com/KeygraphHQ/shannon | AI web/API pentester. Only against **your own** staging. |

## Lower priority (kept for awareness)

| Repo | Why not top |
|------|-------------|
| https://github.com/HKUDS/Vibe-Trading | Trading / backtest — niche. Verify before real money. |
| https://github.com/HKUDS/DeepTutor | Custom tutor / Q&A over materials — personal learning, not core product. |

---

## Suggested defaults

1. UI → ui-ux-pro-max + hallmark  
2. Review / tokens → code-review-graph (+ rtk)  
3. Engineering process → mattpocock/skills + spec-kit  
4. Companion / RAG recipes → Open-LLM-VTuber + awesome-llm-apps  
5. Office → OfficeCLI when needed  
6. Agent fleets → Orca / Codex / pi later  
7. Unity → UnityMCP when in Editor  
8. Pre-prod web → shannon on your own stand  

---

## How to add an entry

Ask an agent:

> Add to https://github.com/ebluffy/agent-tool-catalog — `<url>` — `<one-line why>`

Or edit this README directly. Keep rows short. No secrets, no private repo paths, no personal project names.
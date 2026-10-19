# Hi, I'm Ajey

I build data science projects, and lately the tools that help AI coding agents do work you can actually trust.

## Agent Skills

[![skills](https://raw.githubusercontent.com/AjeyDS/skills/main/assets/hero.jpg)](https://github.com/AjeyDS/skills)

A skill is a folder of instructions an agent loads when a task calls for it. Mine carry the knowledge a model is missing and leave the thinking to the model. They work in Claude Code, Codex, Cursor and Gemini CLI.

| Skill | What it does |
|---|---|
| [ai-slop-detector](https://github.com/AjeyDS/skills/tree/main/skills/engineering/ai-slop-detector) | Audits a codebase for AI-generated quality decay: duplication, dead code, over-engineering, hallucinated packages. |
| [bootstrap-system-md](https://github.com/AjeyDS/skills/tree/main/skills/engineering/bootstrap-system-md) | Writes a `SYSTEM.md` that every coding agent reads before touching the repo. |
| [external-agent-delegation](https://github.com/AjeyDS/skills/tree/main/skills/engineering/external-agent-delegation) | Hands work to parallel coding agents, matches review depth to the model that did it, and refreshes model knowledge from the web. |
| [frankenstein-code](https://github.com/AjeyDS/skills/tree/main/skills/engineering/frankenstein-code) | Finds open-source code that already solves part of a goal and stitches in only the pieces needed. |
| [freshness-check](https://github.com/AjeyDS/skills/tree/main/skills/engineering/freshness-check) | Sends cheap scout models to check a plan's assumptions against what is current. |
| [goal-anchored-delegation](https://github.com/AjeyDS/skills/tree/main/skills/engineering/goal-anchored-delegation) | Carries the goal, not just the plan, into every handoff between agents. |
| [ui-ux-audit](https://github.com/AjeyDS/skills/tree/main/skills/engineering/ui-ux-audit) | Audits a frontend against UI/UX basics and reports fixes with file and line. |
| [causal-root-cause-analyst](https://github.com/AjeyDS/skills/tree/main/skills/research/causal-root-cause-analyst) | Finds what is really behind a claim, headline, metric move or incident. |
| [saving-raw-sources](https://github.com/AjeyDS/skills/tree/main/skills/research/saving-raw-sources) | Saves research sources one file each, with the original wording intact. |
| [synthesize-research-insights](https://github.com/AjeyDS/skills/tree/main/skills/research/synthesize-research-insights) | Turns a folder of raw sources into plain-language insights. |
| [study-notes-pdf](https://github.com/AjeyDS/skills/tree/main/skills/learning/study-notes-pdf) | Builds a big-picture-first study guide as a polished PDF. |

```bash
npx skills add AjeyDS/skills
```

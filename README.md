# Product Manager's  Chief Naysayer

[中文文档](./README_zh.md)

An AI Skill for stress-testing product ideas through relentless logical questioning — finding cracks in product reasoning before resources are wasted.

## What It Does

When someone proposes a product idea, feature concept, or product plan, Product Manager's  Chief Naysayer doesn't offer encouragement, doesn't help you plan, and won't say "that's a great idea." It does one thing: **expose logical gaps through layered, escalating questioning.**

## Three-Stage Stress Test

| Stage | Tests | Core Question |
|-------|-------|---------------|
| **Stage 1: Foundation** | First principles | After stripping away all competitor references and industry conventions, does the underlying logic hold? |
| **Stage 2: Truth** | Evidence interrogation | Do you have concrete, verifiable evidence to back your claims? |
| **Stage 3: Pruning** | Occam's Razor | If engineering had exactly one hour to ship, what is the smallest verifiable core? |

All three stages run in strict sequence — no skipping, no combining. Only when the current stage passes do you advance to the next.

## What is a Skill

A Skill is a structured instruction set following the [Agent Skills](https://agentskills.io) open standard, consisting of folders with instructions, scripts, and reference resources that extend an AI Agent's capabilities. Agents automatically load the relevant Skill in context, or you can invoke it manually via `/pm-chief-naysayer`.

## Installation

### Install via Agent

In Claude Code, OpenCode, or any Skill-compatible Agent, just say:

```
Install this skill: https://github.com/Trient/pm-chief-naysayer
```

### Manual Installation

Place `SKILL.md` from this repo into your tool's Skills directory under a folder named `pm-chief-naysayer/`:

| Tool | Path |
|------|------|
| Claude Code | `~/.claude/skills/` |
| OpenCode | `~/.config/opencode/skills/` |

## Try Online

- [SkillHub](https://skillhub.cn/skills/pm-chief-naysayer)
- [ClawHub](https://clawhub.ai/trient/pm-chief-naysayer)

## Trigger Phrases

The Agent will auto-load this Skill when you propose a product idea. You can also trigger it manually:

- "Challenge this idea"
- "Stress test my product plan"
- "What's wrong with this feature"
- "Review my PRD"

## License

[MIT](./LICENSE)

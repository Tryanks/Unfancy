# Unfancy

Unfancy is a Codex skill for writing plain, exact, product-native UI copy.

It is designed to catch and prevent wording that sounds polished but semantically wrong, especially in product surfaces like labels, buttons, statuses, empty states, confirmations, settings, dashboards, and internal tools.

## What It Does

Unfancy pushes copy toward:

- real object names
- direct action labels
- factual status text
- concrete warnings
- short helper text
- scan-friendly structure

It pushes copy away from:

- inflated nouns
- vague capability language
- ornamental section labels
- marketing leakage
- technical leakage
- AI-sounding filler

## When To Use It

Use `unfancy` when writing or reviewing:

- buttons and CTAs
- status labels
- empty states
- helper text
- confirmation dialogs
- settings pages
- dashboards
- admin tools
- operational product copy

## Core Principle

Preserve meaning. Remove performance.

The goal is not to make copy feel more impressive. The goal is to make it more correct.

## Files

- [`SKILL.md`](./SKILL.md): the skill definition and working rules
- [`agents/openai.yaml`](./agents/openai.yaml): UI metadata for the skill

## Usage

Example prompt:

```text
Use $unfancy to review and rewrite this settings page copy.
```

## Notes For Updates

When updating the skill, keep `SKILL.md` and `agents/openai.yaml` aligned so the skill behavior and displayed metadata describe the same thing.

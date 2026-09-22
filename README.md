# Z Graphic Production Skill

An evergreen ZedBiz workflow for creating, editing, exporting, saving, and delivering marketing graphics across supported agent runtimes and chat channels.

The skill keeps three responsibilities separate:

- `z-creative-asset-analysis` develops and assesses the direction when needed.
- `z-graphic-production` makes, corrects, exports, stores, and delivers the asset.
- [`z-creative-asset-critique`](https://github.com/ZedBiz44/z-creative-asset-critique-Skill) reviews visible quality and returns the verdict.

GitHub is the technical source of truth. The ZedBiz Notion SOP is the operating guide for agents and team members.

This repository owns the graphic production skill; `SKILL.md` is the authoritative runtime instruction.

## When to Use

Use for creating, editing, exporting, saving and delivering still marketing graphics. When an attention-focused brief lacks a hook or direction, use `z-creative-asset-analysis` before the draft.

## Do Not Use

Do not use production alone for an independent execution verdict or marketing-performance claim. Analysis develops the direction; critique reviews the exact draft against it.

## Safety and Approval

Keep secrets out of this repository. Existing approval governs provider, cost and destination; do not treat analysis or critique as authority for new spend, client delivery or publication.

## Contents

- `SKILL.md` — core portable workflow
- `references/` — brief, handoff, export, runtime, delivery, and evidence guidance
- `tests/` — trigger and workflow acceptance cases

## Design Rules

- Use the runtime's native handoff for a newly generated image in the current chat.
- Use an approved media path and require a channel-specific receipt for a resend or separate file delivery.
- Inspect the exact final export.
- Use the critique companion for newly created or meaningfully edited graphics.
- Keep provider and channel differences in small runtime adapters, not in the core workflow.

## Validation

Validate with the current `z-ai-skill-developer` package before release, then test discovery and the complete workflow in one real agent runtime before expanding deployment.

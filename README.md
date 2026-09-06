# Z Graphic Production Skill

An evergreen ZedBiz workflow for creating, editing, exporting, saving, and delivering marketing graphics across supported agent runtimes and chat channels.

The skill keeps two responsibilities separate:

- `z-graphic-production` makes, corrects, exports, stores, and delivers the asset.
- [`z-creative-asset-critique`](https://github.com/ZedBiz44/z-creative-asset-critique-Skill) reviews visible quality and returns the verdict.

GitHub is the technical source of truth. The ZedBiz Notion SOP is the operating guide for agents and team members.

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


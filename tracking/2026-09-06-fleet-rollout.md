# Fleet Rollout

Date: 2026-09-06  
Owner: Cody  
Status: Passed

## Scope

Deploy the validated `z-graphic-production` package to every active ZedBiz OpenClaw agent and to Ruby's Hermes runtime. Preserve each platform's own tools and delivery rules.

## Deployed Agents

- VPS1 OpenClaw: Amanda, Edith, GohZed, Grogar, Inga, Maggie, Marsha, Terry, Victor, Vivian, and Wilma.
- VPS2 OpenClaw: Harry, Suzy, and Frank.
- VPS4 OpenClaw: Rocky.
- VPS3 Hermes: Ruby.

## Verification

- Every deployed `SKILL.md` matched SHA-256 `af85f22f2ff03a3192f33169b6d29a6cf8073681be787a0ae66a70c36d603a72`.
- All fifteen OpenClaw agents reported the skill as eligible and model-visible after a managed gateway refresh where needed.
- All affected VPS1 containers were healthy after the refresh. VPS2 services and Rocky's user service were active.
- Ruby reported the local skill enabled under Hermes and had both image generation and vision available.
- Ruby completed the Hermes create, critique, export, save, and Telegram delivery path. Telegram media message ID: `2925`.
- Inga completed a fresh-session OpenClaw test without the skill name in the request. She automatically loaded `z-graphic-production` and `z-creative-asset-critique`, produced a Ready 1254 by 1254 PNG, saved the reusable final, and delivered the photo to Telegram. Telegram media message ID: `159`.
- Terry and Harry had already passed the representative OpenClaw production and confirmed Discord delivery tests recorded in the pilot report.

## Live Finding

Some long-running OpenClaw gateways retained their pre-install skill inventory. The files were correct but the new skill was not model-visible until those gateways received a normal managed restart. Deployment verification therefore includes both the file hash and a live eligible/model-visible check.

## Change Boundary

- Installed only the new skill package.
- Used the existing platform-specific runtime and delivery tools.
- Did not alter agent prompts, channel configuration, credentials, or unrelated skills.

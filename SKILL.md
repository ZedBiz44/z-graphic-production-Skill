---
name: z-graphic-production
description: Create, edit, export, save, and deliver reusable marketing graphics with a brief, quality check, and confirmed handoff.
---

# Z Graphic Production

Use this skill to create or edit marketing graphics, social images, ad creative, avatars, illustrations, simple promotional visuals, and photo-based assets. It owns production, export, storage, and delivery. It does not replace `z-creative-asset-critique`, which owns the quality verdict.

## Start With the Operation

- **Create or edit:** capture the brief, produce the asset, use the critique companion, correct material problems, export, inspect, save, and deliver.
- **Resize or compress:** preserve the approved design and check only what the transformation could damage: crop, safe areas, readability, colour, transparency, and file quality.
- **Resend unchanged:** confirm the correct approved file and destination, then deliver it. Do not reopen design critique.

Read [creative brief](references/creative-brief.md) before meaningful creation or editing. Read only the other reference files needed for the requested operation.

## Produce the Graphic

- Use the image provider and tools available in the active runtime. Follow their current operating restrictions.
- Reuse approved copy, brand assets, references, and prior decisions. Do not invent logos, testimonials, prices, offers, legal claims, or brand rules.
- Keep text out of generated image pixels when an available layout tool can add it more reliably.
- Preserve editability when practical. Save reusable work outside temporary generation folders.
- Existing approval for the provider, cost, and destination carries through the approved job. Ask again only when the scope, cost, account, or destination materially changes.

ZedBiz owns this portable workflow. Each runtime's tool requirements and operating restrictions still apply. Read [runtime adapters](references/runtime-adapters.md) when the available generation or editing tool is unclear.

## Use the Critique Companion

For every newly created or meaningfully edited graphic, apply the relevant guidance from `z-creative-asset-critique` before production and request its Quick Look after the first draft. Use [critique handoff](references/critique-handoff.md) so production and critique use the same facts.

- Make one initial production pass and no more than two targeted correction passes by default.
- Stop sooner when the asset is **Ready** and all done-when checks pass.
- Never label an unresolved asset **Ready** because the revision limit was reached.
- If a material issue remains, state the issue and the decision needed.

If the companion skill is unavailable, perform a basic visible review using the known brief. Ordinary work may proceed only with: **Basic review completed; ZedBiz critique companion unavailable.** Work that explicitly requires a full review, or is costly or high-risk to publish, remains unfinished until the companion review occurs.

## Export and Inspect

Export for the stated use and inspect the exact final file, not only the working draft. Recheck what export could affect: dimensions, crop, clipped edges, text readability, colour, transparency, compression, and file opening. Follow [production output checks](references/production-output-checks.md).

Save the reusable master, final export, brief, and essential references in the approved project location when future reuse is likely. A successful chat delivery is not durable storage.

## Deliver the Graphic

Choose the correct lane in [channel delivery](references/channel-delivery.md):

- **Current-chat generated image:** use the runtime's built-in image completion or native handoff. Do not manually attach a temporary generation path.
- **Resend or separate file delivery:** stage the exact final file in the runtime's approved media folder, use the supported structured media send, and require a channel-confirmed media receipt.

A generic success flag, `delivery_ambiguous`, or missing message ID is not confirmed delivery. Make one safe retry after correcting a known path or format problem. If still unconfirmed, tell the requester plainly and preserve the approved file for recovery.

## Finish the Work

Report the asset version, saved location when applicable, review status, delivery destination, and confirmed receipt. Never claim delivery from the absence of an error.

Save only compact, verified lessons after a real recovery or durable decision. Do not put raw chats, logs, images, or temporary paths into memory. Follow [memory and evidence](references/memory-and-evidence.md).


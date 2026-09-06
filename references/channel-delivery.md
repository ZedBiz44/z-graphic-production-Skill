# Channel Delivery

## Current-Chat Generated Image

Use the runtime's native image completion or built-in handoff to the conversation that requested the image. The runtime should carry the generated media from its temporary workspace to the active channel.

Do not manually attach the temporary generation path. Do not copy a temporary file merely to imitate the native handoff.

## Resend or Separate File Delivery

- Select the exact approved final export.
- Copy or stage it in the runtime's approved media folder when local-file sending requires that boundary.
- Use the channel's supported structured media-send format.
- Confirm the receipt identifies the delivered media message. Require the channel's media message ID when the tool exposes one, including Telegram and Discord.

Treat `success: false`, `delivery_ambiguous`, a missing message ID, or a text-only receipt for an intended image as unconfirmed. A wrapper-level `sent` result does not prove image delivery when its returned payload contains no media and channel read-back cannot find the attachment.

After a correctable path or format error, make one safe retry. If delivery remains unconfirmed, say so plainly, retain the approved file, and report the recovery location or next required action.

Channel transport rules may differ across Telegram, Discord, and future channels. Do not change the production and critique standards to solve a transport-specific problem.

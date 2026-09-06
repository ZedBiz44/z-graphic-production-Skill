# Acceptance Tests

## Create and Deliver

Given an approved brief and a current chat, the agent creates a draft, obtains a companion verdict, makes no more than two targeted correction passes, exports and opens the exact final file, saves reusable work when needed, and uses the native image handoff. The final report includes the version, review status, destination, and confirmed receipt.

## Export Defect

Given a draft that passes critique but whose final crop clips text, the final-file check catches the defect. The agent corrects the export and does not claim the earlier draft verdict proves the delivery file is ready.

## Missing Companion

Given an ordinary graphic and an unavailable critique skill, the agent performs a basic visible check and labels it exactly: **Basic review completed; ZedBiz critique companion unavailable.** It does not claim a full critique pass.

## Resend Unchanged

Given a previously approved final file, the agent confirms the file and destination, stages it if required, sends it through the supported media tool, and verifies a channel-specific media receipt. It does not reopen design critique.

## Ambiguous Delivery

Given `delivery_ambiguous` or no message ID, the agent does not claim success. It makes at most one safe recovery attempt after correcting a known problem, then reports unconfirmed delivery plainly and preserves the approved file.


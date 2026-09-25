---
description: Supervise a BillCutterz post, email or attachment against the Social Handbook before it goes to Ravi or Barry
argument-hint: [post number, file path, or blank for the post in progress]
---

# Post Check

Run two checks over the work in progress before it is sent, in this order:

1. `billcutterz-marketing-manager` — will this bring in customers, and would Barry sign
   it? Must return `VERDICT: APPROVE`.
2. `billcutterz-post-supervisor` — does it follow every handbook rule? Must return
   `VERDICT: PASS`.

Social posts need both. Emails and attachments to Barry need the supervisor only.

## When to run

- Before sending a social post picture or caption to Ravi for upload.
- Before sending anything at all to Barry Gross — email, Word attachment, link, page.
- After applying a round of Ravi's changes, before saying the change is done.

## How it works

1. Load `skills/billcutterz-social-handbook/SKILL.md`.
2. Hand the supervisor the caption text, the rendered picture path, and any attachment.
3. For a post, the manager goes first and returns `APPROVE` or `REVISE` with a score and
   exact fixes. On REVISE, fix every MUST FIX line and run the manager again.
4. The supervisor then returns `VERDICT: PASS` or `VERDICT: FAIL` with the failing rule
   numbers and the exact replacement wording.
5. On FAIL, fix every named line and run the check again. Do not send on a FAIL.
6. On PASS, send, and pass both FLAGS FOR BARRY lists along with it.

## After the verdict

Any correction that came back from Ravi or Barry rather than from the supervisor is a
gap in the handbook. Add the rule to
`skills/billcutterz-social-handbook/SKILL.md` — what was rejected, what replaced it, and
why — then commit. The supervisor catches it next time.

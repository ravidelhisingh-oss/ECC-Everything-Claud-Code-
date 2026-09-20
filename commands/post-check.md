---
description: Supervise a BillCutterz post, email or attachment against the Social Handbook before it goes to Ravi or Barry
argument-hint: [post number, file path, or blank for the post in progress]
---

# Post Check

Run the `billcutterz-post-supervisor` agent over the work in progress before it is sent.

## When to run

- Before sending a social post picture or caption to Ravi for upload.
- Before sending anything at all to Barry Gross — email, Word attachment, link, page.
- After applying a round of Ravi's changes, before saying the change is done.

## How it works

1. Load `skills/billcutterz-social-handbook/SKILL.md`.
2. Hand the supervisor the caption text, the rendered picture path, and any attachment.
3. The supervisor returns `VERDICT: PASS` or `VERDICT: FAIL` with the failing rule
   numbers and the exact replacement wording.
4. On FAIL, fix every named line and run the check again. Do not send on a FAIL.
5. On PASS, send, and pass the FLAGS FOR BARRY list along with it.

## After the verdict

Any correction that came back from Ravi or Barry rather than from the supervisor is a
gap in the handbook. Add the rule to
`skills/billcutterz-social-handbook/SKILL.md` — what was rejected, what replaced it, and
why — then commit. The supervisor catches it next time.

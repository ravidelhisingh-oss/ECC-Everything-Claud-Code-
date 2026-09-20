---
name: billcutterz-social-handbook
description: The house rules for every BillCutterz social post, picture and caption — Barry's copywriting rules, card layout, caption format, hashtags, links, and the figures policy. Use before writing, editing or approving any BillCutterz post for LinkedIn or Facebook, and before sending any post to Barry for approval.
origin: BillCutterz
---

# BillCutterz Social Handbook

Every rule below was learned from a real correction by Barry Gross or Ravi Singh, or from
research that changed how a post is built. Nothing here is a preference. Each rule carries
the date it was learned and why, so it is never re-litigated or quietly dropped.

Read this before building a post. Run `billcutterz-post-supervisor` before sending one.

## 1. Barry's two copywriting rules

These come first. A post that breaks either one does not go out.

### 1.1 Every sentence stands on its own

Barry, in his own words:

> "If you write a paragraph, each sentence should stand on its own. They're all a
> complement to the next one. But if something says 'we can do better than that' just by
> itself, it gives you no context. We can do better at what? We can do better at saving
> you money on your monthly bills."

Test each sentence by reading it alone, with nothing above it. If it leaves the reader
asking "better at what?" or "which one?", it fails. Pronouns pointing backwards
("that", "this", "they") are the usual cause.

### 1.2 Attention, interest, involvement, service, close

Ravi, 11 Sep. Every caption runs in this order, one job per line:

| Line | Job |
|---|---|
| Attention | The sentence that stops the scroll. Usually the headline restated. |
| Interest | Why it is happening. The mechanism the reader did not know. |
| Involvement | The line that asks the reader to do or say something. |
| Service | What BillCutterz actually does about it. |
| Close | The domain, on its own line. |

## 2. The involvement line never teaches the reader to do it themselves

Learned 20 Sep, from Ravi, twice in a row on posts 2 and 3.

The involvement line must move the bill **toward BillCutterz**. It must never hand over
the method, because a reader who has the method does not need the service.

Rejected wording, and why:

- "Next time you call, ask for retention" — gives away the whole service in six words.
- "Count how many boxes you are paying for" — sends them to audit their own bill.
- "Tell us your provider and we will tell you which charges do not belong" — BillCutterz
  cannot know that from a provider name alone. It promises something we cannot deliver.

Accepted shape: ask for the bill, then say what we do with it.

> Send us your bill and we do the work for you.
>
> We review your bill, find charges like these, get them removed, and lower your rate
> without changing your service.

### 2.1 The service line is one plain sequence, not a chain of clauses

Learned 20 Sep, from Ravi. This wording was rejected:

> "We review it, find the charges that can come off, challenge them with your provider,
> and lower your rate without changing your service."

It reads as four separate negotiating steps and the reader loses the thread. "Challenge
them with your provider" in particular sounds like the reader is doing the challenging.

Say what we do to the bill, in the order it happens, naming the bill as the subject.

**The rule is three beats, not one frozen sentence.** The wording adapts to the post; the
shape does not. Three beats, in this order, nothing about method:

1. We review your bill.
2. We find or tell you what is wrong with it.
3. We fix it — charges removed, rate lowered, service unchanged.

Two approved examples:

> We review your bill, find charges like these, get them removed, and lower your rate
> without changing your service.

Or, where the post is about a charge the customer did not know was there:

> We review your bill, tell you what you are paying for and not using, and get those
> charges removed without changing your service.

A fourth beat is the failure. So is any beat that sounds like the reader is doing the
work.

### 2.2 Do not invent a mechanism to make a point sharper

Learned 20 Sep, from Ravi, after a rejected line. This was written and rejected:

> "An unused cable box looks exactly like a used one on the account, so every box on the
> bill reads as active."

It claims the provider's system cannot tell the difference. Nobody said that, and it is
not true. The real point is smaller and safer: the charge continues, and nobody at the
provider raises it. Keep the claim at "nobody notices and nobody tells you", never at
"they cannot tell".

When a line is cut for being an unverified claim about a provider, the fix is to state
less, not to invent a mechanism that sounds more convincing.

### 2.3 We are the ones who tell the customer

Learned 20 Sep, from Ravi, on post 3. The interest lines should land on the fact that
nobody else is going to point the problem out — the bill does not show it and the
provider has no reason to raise it. That makes the review itself the service, not only
the negotiation. Where a post supports it, beat 2 of the service line says "tell you",
because being told is what the customer is actually buying.

The panel line on the picture follows the same rule. "You only reach retention by asking
for retention" was replaced with "We know how to reach them, what to say, and when to
say it."

## 3. The picture

Built in HTML at `scratchpad/cards5/cards.html`, rendered by `shoot.mjs`. 1080 x 1080.

### 3.1 The foot lockup — fixed, every card

- **Bottom left:** the real BillCutterz logo, on a white plate. The source PNG has no
  alpha channel, so it needs the plate on dark cards.
- **Bottom right:** `BillCutterz.com` in the accent green. Nothing else.

### 3.2 Never put a fake button on a picture

Learned 20 Sep from Ravi. "Send us your bill →" looked like a button and was not
clickable. A picture cannot be tapped, so it must not pretend to be. The domain replaced
it on all seven cards.

### 3.3 The domain is spelled BillCutterz.com

With a **z**. Same as the email domain. Never billcutters.com. This is worth checking
every single time — it is mistyped often, including by us.

### 3.4 The hero is the bill

Not stock photography, not an AI-generated image. A white panel showing the relevant
lines of a bill. This was settled on 20 Sep after Canva's AI produced gibberish text on
rendered bills, clipped supplied headlines, recoloured them, and invented a fake
BillCutterz logo. AI image tools cannot render a legible bill. Do not try again.

### 3.5 The panel shows the problem, the last line shows us

Rows carry the figures. The `.note` line under them is where BillCutterz enters. The
note is never a how-to.

### 3.6 Make the arithmetic read itself

Learned 20 Sep. A panel that requires mental multiplication has failed. Three different
framings stacked in one box ("units under management", "per unit per month", "same
portfolio, twelve months") is the failure mode. Use one ladder of the same unit, and
name what each figure is:

> What you pay today — $79 / mo
> What it should cost — $59 / mo
> You are paying extra — $20 / mo
> Extra, across 12 units, one year — $2,880

A reader must be able to tell, without thinking, which number is their bill and which
number is the saving.

### 3.7 Name the rows like a real household

Learned 20 Sep, from Ravi. A panel listing "Set-top box / Set-top box / Set-top box" is a
spreadsheet — the reader cannot see why there are three, so the unused one carries no
weight.

Name each row the way the customer would: living room, bedroom, guest room. The guest
room is the one everybody recognises as rarely used, so `NOT IN USE` needs no
explanation once the room is named.

The same rule applies anywhere a panel lists repeated items. Give each row an identity
the reader recognises from their own home or their own portfolio.

### 3.7 Clear beats clever, always

Learned 20 Sep, after a headline of Ravi's was replaced with a cleverer one and he
pushed back. Avoiding repetition across cards is our problem to solve; it is never a
reason to make a headline harder to understand. When Ravi or Barry has written a line,
it stands as written.

## 4. The caption

### 4.1 One sentence per line, blank line between

Learned 20 Sep. Captions were delivered as running paragraphs, which is not how they
post. Deliver them laid out exactly as they will appear, so they can be copied straight
across.

### 4.2 The domain goes on its own line, as plain text

`BillCutterz.com` — no `https://`, no `www`.

### 4.3 Three hashtags, CamelCase, at the end

Both platforms have moved off hashtag discovery. On LinkedIn, posts with no hashtags now
slightly outperform posts with them; 2–3 that match the actual topic are all that help.
Facebook treats them as minor.

CamelCase, not lowercase, because screen readers pronounce `#BillNegotiation` correctly
and read `#billnegotiation` as one garbled word.

### 4.4 Never post a link on its own

The reach penalty sits on the **link preview card**, not on the URL. 2026 figures: a post
with a preview card gets about 414 median impressions, the same post without one about
795, and a URL in the body as plain text about 858 — level with posts carrying no link.

Because these are image posts, the picture takes the attachment slot and no preview card
is ever generated. Picture plus the domain in the text is safe. A link-only post is the
lowest-reach format on Facebook and takes the full penalty on LinkedIn.

### 4.5 If the involvement line is a question, it is answerable in four words

Comments are weighted far above likes on both platforms. "Who is your provider?" gets
answered. "Audit your bill and report back" does not.

This applies only when the line is a question. The standard involvement line, "Send us
your bill and we do the work for you," is an instruction, and section 2 governs it.
Section 2 wins where the two sections meet.

## 5. Figures, claims and compliance

### 5.1 Barry's rule: no invented numbers

Any figure that reads as a real customer outcome must come from BillCutterz books.

### 5.2 The FTC rule that backs it up

The old safe harbour is gone. A disclaimer of "results not typical" or "individual
results may vary" no longer covers an advertiser. If a figure in an ad reads as a normal
customer outcome, there must be proof it is typical, or the typical result must be stated.
A disclosure that is not visible without clicking "more" is not clear and conspicuous —
which rules out burying it at the end of a long caption.

### 5.3 What this means in practice

- **Illustrative panel** — header reads `EXAMPLE BILL · <subject>`. Currently on cards 1
  and 3.
- **Arithmetic-only figures** — fine unlabelled. 12 units x $79 x 12 months = $11,376
  asserts nothing about what a customer saved.
- **A savings figure** — needs a real before-and-after, or the EXAMPLE label.
- Once a real bill is supplied, the true figures go in and the label comes off.

### 5.4 Media mentions

Only these three, until Barry confirms more:

- CNBC Select — Best Overall
- ABC World News Tonight
- Better Business Bureau A+

Fox Business News, Men's Health and "with Diane Sawyer" came from a web search, are
unconfirmed, and do not appear in Barry's own approved LinkedIn Overview. They stay off
every card until he says otherwise.

### 5.5 Claims about other companies

A line like "customer service and billing are not allowed to change your rate" is a
factual claim about third parties. It must rest on Barry's experience on the phones, not
on research. Flag these for him rather than asserting them.

## 6. Delivery

### 6.1 One post at a time

Learned 20 Sep. Seven posts in one message cannot be reviewed. Send one picture and one
caption, wait for the verdict, apply changes, then move to the next.

### 6.2 Every delivery carries the post title

Learned 20 Sep, from Ravi. A revision was sent without its title and he had to ask for it
again. He needs the title for the Studio short name on every upload.

Every post, and every revision of a post, is delivered with:

- the post number ("Post 3 of 7")
- the **title** — the Studio short name, e.g. `Equipment rental`
- the picture filename
- the caption, laid out as it will post

A revision is not a fragment. Send the whole post again, title included, even when only
one line changed.

### 6.2 Apply a settled change to every card at once

When a rule changes the picture, fix all seven cards in that pass, even though only one
is being presented. The fix is then already done when its turn comes.

### 6.3 Names and addresses

- Ravi: `ravi@billcutterz.com` — never the gmail address, never billcutters.com.
- Barry: `barry@billcutterz.com`.
- Every email to Barry ends with a sign-off wish.

### 6.4 Tone

Plain American English. Short. Professional and very polite. Suggestions, never
instructions — learned from the Tony message, which was rejected for sounding like an
order. Do not repeat the word "just". Do not offer three options when one decision is
needed; make the call and say why.

## 7. Distribution, still to act on

Worth raising with Barry, not yet decided:

- Reels are the highest-reach format on Facebook in 2026. Pages posting two a week report
  3–4x the reach of image posts.
- Personal profiles out-reach company pages on LinkedIn. Barry posting from his own
  profile, with the company page resharing, is the strongest available distribution.
- Facebook's algorithm penalises overly promotional pages. Hold to roughly 80% useful,
  20% promotional across the calendar.

## Maintaining this handbook

Every correction adds a rule. When Ravi or Barry changes something, write down what was
rejected, what replaced it, and why, then commit. A rule with no reason attached gets
argued about again six weeks later.

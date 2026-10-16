# The 12-Point AI Ops Audit

_Score the operating system of your one-person business - v1.0_

Most solo operators do not have an AI problem. They have an operations problem that AI happens to be good at fixing. This audit finds which of your 12 recurring business jobs are still living entirely in your head. Score each one honestly, 0 to 3. Twelve minutes, pen or spreadsheet. Then work only on the lowest two in the Money and Intake groups first - they pay back fastest.

## How to run this

1. Score each point 0-3 for how your business runs TODAY, not how it will run once you're disciplined.
2. Be harsh. A system you have to remember to use is a 1, not a 3.
3. Add up the 12 scores. Compare against the four bands on page 2.
4. Pick the lowest-scoring point in Intake or Money and run its 45-minute quick win this week.

## What your score means

| Score | Read | What it means |
|---|---|---|
| 0-9 | **You are the system** | Everything routes through your memory and your mood. One bad week and revenue stalls. Fix points 1, 9 and 4 before buying anything else. |
| 10-18 | **Fragile** | You have documents, but no triggers. Work happens when you remember. Fix points 6, 7 and 12. |
| 19-27 | **Systemised** | Jobs repeat predictably and AI does first drafts. Your bottleneck is review, not production. Fix points 8, 10 and 11. |
| 28-36 | **Runs like a team of five** | You approve, the system executes. Your next gain is capacity pricing, not more automation. |

## The 12 points

### 01 · INTAKE — Qualification before reply

**Symptom:** You answer every enquiry like a maybe-client, then discover the budget in week two.

**Score:**

- **[ 0 ]** Every enquiry gets the same enthusiastic reply
- **[ 1 ]** You ask budget and timeline, but by memory, in chat, inconsistently
- **[ 2 ]** One form or scripted 5 questions every enquiry must answer before you quote
- **[ 3 ]** Form scores fit automatically; anything under the cut-off gets a polite no or a referral, written by AI, approved by you

**Quick win (≤45 min):** Write the 5 non-negotiable questions (scope, budget band, start date, decision-maker, what happens if we both say yes). Paste them into your enquiry auto-reply. Nothing else today.

**Starter prompt:**

```text
Act as a filter-first sales operator. From my service description below, write 5 qualifying questions a prospect must answer before I quote. Rules: max 12 words per question, no jargon, one question must isolate budget band without a number field, one must expose urgency. Then write the polite 40-word decline template for anyone who fails two or more. Service: [describe in 3 lines]
```

*Where AI helps:* Draft the questions, the auto-reply and the decline script. You edit tone once.  
*Watch out:* Never let AI decide who is a good client. It optimises for politeness, not for your calendar.

### 02 · INTAKE — Speed and shape of first reply

**Symptom:** Slow or unstructured replies. The prospect's second choice becomes their first.

**Score:**

- **[ 0 ]** Reply when you find the email, often 24-72 hours
- **[ 1 ]** You reply same-day when you're free
- **[ 2 ]** A reply template exists: outcome, next step, two time slots, price band
- **[ 3 ]** Template plus calendar link; enquiry answered same day even on a bad day; a weekly note tells you how many you sat on

**Quick win (≤45 min):** Build the 5-line reply skeleton once and save it where you actually type (email signature, snippet tool, Notion button): acknowledgement, one clarifying question, price band, two slots, next step.

**Starter prompt:**

```text
Write a 5-line reply template for new enquiries into my business: [service], [typical project size], [lead time]. Line 1 acknowledges the specific project. Line 2 asks the single most useful clarifying question. Line 3 states my price band plainly. Line 4 offers exactly two call slots. Line 5 says what happens if they don't reply in 5 days. No exclamation marks.
```

*Where AI helps:* Structure and wording. You supply the numbers.  
*Watch out:* Do not automate the yes. Automate the response, keep the decision.

### 03 · SCOPE — Proposal that pre-answers the argument

**Symptom:** Proposals turn into three weeks of 'can you just also...' negotiation.

**Score:**

- **[ 0 ]** A quote with a number and a paragraph
- **[ 1 ]** A template with deliverables and timeline
- **[ 2 ]** Template lists out-of-scope items, assumptions, revision count, what voids the price
- **[ 3 ]** The template is filled from the intake answers, reads itself back to the client in plain English, and every sent version is archived

**Quick win (≤45 min):** Add an 'Not included' block with 6 bullets to your current proposal. Six bullets, twenty minutes, most scope creep dies there.

**Starter prompt:**

```text
I run a one-person [service] business. Here is my proposal draft: [paste]. Rewrite the scope section so a non-expert client cannot misunderstand it. Split into: included, explicitly not included, assumptions that must hold, what triggers re-quoting. Keep my price. Flag any sentence where I have promised an outcome I cannot control.
```

*Where AI helps:* Rewrites, clarity flags, the not-included list.  
*Watch out:* Never let AI invent delivery dates or warranties. You own the promises.

### 04 · SCOPE — Agreement and deposit enforced before work

**Symptom:** You start before paper is signed, then invoice into a silence.

**Score:**

- **[ 0 ]** No contract, or a contract sent after work starts
- **[ 1 ]** A contract exists, sent and chased manually
- **[ 2 ]** Contract plus deposit is a gate: no kickoff until both land
- **[ 3 ]** Gate automated with a signed copy and deposit status visible in one place, and renewal terms stated up front

**Quick win (≤45 min):** Make the deposit a hard line in your proposal's last section: 'Work starts when the signed agreement and the [X]% deposit land.' Then say it out loud once, on your next call.

**Starter prompt:**

```text
Review this payment and start-work clause for a solo [service] business: [paste]. Make it firm but not aggressive: deposit percentage before kickoff, milestone payment trigger, what happens at 7 and 14 days late, kill fee if the client stalls 30+ days, and a line that protects me if they ghost mid-project. Plain English, no Latin.
```

*Where AI helps:* Drafting and tightening. Use a lawyer for the final read if a project exceeds a value you set.  
*Watch out:* Do not claim legal advice or jurisdiction-specific enforceability in client-facing copy.

### 05 · DELIVERY — Kickoff packet and one source of truth

**Symptom:** Week one is chaos; the project lives across email, chat and three folders.

**Score:**

- **[ 0 ]** We just start
- **[ 1 ]** A welcome email with a couple of links
- **[ 2 ]** A fixed kickoff packet: what we do in week 1, what I need from you, where truth lives, when updates come
- **[ 3 ]** Packet sent automatically, client completes their half through a form, and the project has one folder and one doc of record

**Quick win (≤45 min):** Write the 10-line kickoff note you wish every client got on day one: access list, decision-maker, response expectation, where files live, when the first update arrives.

**Starter prompt:**

```text
Create a kickoff packet for clients of my [service] business. Include: the 3 things I need from them in week 1, what they get and when, who the single decision-maker must be, my response window, where files and decisions are stored, and 3 ways a project like this usually goes sideways plus what we do if it does. Max 350 words, second person.
```

*Where AI helps:* Whole first draft, plus the 'how projects go sideways' framing.  
*Watch out:* Keep credentials out of emailed packets. Use a password manager share.

### 06 · DELIVERY — Update cadence the client never has to ask for

**Symptom:** Clients chase you. Chasing clients make them anxious and anxious clients add scope.

**Score:**

- **[ 0 ]** Updates when asked
- **[ 1 ]** Ad-hoc Friday notes
- **[ 2 ]** Fixed weekly digest: done, next, blocked, decision needed
- **[ 3 ]** Digest auto-drafted from your week's notes or tasks; sent on schedule even when you're underwater

**Quick win (≤45 min):** Set a recurring 15-minute calendar block named 'client digests' and send this Friday's digest to every active client, thin version counts.

**Starter prompt:**

```text
Turn these raw notes into a client update email: [paste bullets, timestamps, anything messy]. Format: Done (3 bullets max), In progress, Blocked, Decision I need from you by [date]. Tone: calm professional, no apology unless I actually slipped, no filler opening. Under 130 words.
```

*Where AI helps:* The whole drafting step - it takes it 8 seconds and you 20 minutes.  
*Watch out:* Do not send AI-written status on anything you have not personally verified.

### 07 · DELIVERY — Change and revision control with a price

**Symptom:** 'One small tweak' six times, unbilled, invisible.

**Score:**

- **[ 0 ]** Revisions happen by goodwill
- **[ 1 ]** You say the revision count out loud
- **[ 2 ]** Change log exists: every request, in or out of scope, and its cost
- **[ 3 ]** Changes logged, priced and approved in writing before work; out-of-scope handled by a rate card, not a mood

**Quick win (≤45 min):** Add a 'Change request' line to your tracker with 3 statuses: included, billable, discussed. From tomorrow, no change happens without one of those three words against it.

**Starter prompt:**

```text
Write a change-request procedure for a one-person studio: how a request arrives, how I classify included vs billable against the signed scope, a 60-word message that prices the change without sounding punitive, a rate card layout with 4 columns, and the exact sentence that pauses work if they dispute the charge.
```

*Where AI helps:* Procedure, message wording, rate card columns.  
*Watch out:* Never retro-bill silently. A surprise invoice is a lost client and a bad review.

### 08 · DELIVERY — Triage: interruptions do not own the day

**Symptom:** You work in the client's order of urgency, not yours, and ship nothing deep.

**Score:**

- **[ 0 ]** Everything is answered on arrival
- **[ 1 ]** Two fixed windows a day for messages
- **[ 2 ]** A triage rule: every inbound becomes do-now, schedule, delegate-to-AI, or archive
- **[ 3 ]** Inbox is a queue with an owner (the system, not you), AI drafts the routine 70%, you approve in one pass

**Quick win (≤45 min):** Define the three labels you'll use for any inbound today (Now / Scheduled / Waiting-on-client) and apply them for one day. That is the whole quick win.

**Starter prompt:**

```text
Here are today's inbound messages for my [service] business: [paste]. Sort each into: must-do-now (with why), can-schedule (propose a slot), can-delegate-to-AI-draft (write the draft), or archive (write the 1-line reply). Flag anything where a client is waiting on me and it affects their deadline. Be blunt about what is genuinely urgent.
```

*Where AI helps:* Classification and drafts. You keep the judgement call.  
*Watch out:* Do not let AI send anything with a number, a date or an apology in it without your read.

### 09 · MONEY — Invoice, receipt and the 3-touch chase

**Symptom:** You invoice when you remember and chase when it's already awkward.

**Score:**

- **[ 0 ]** Invoices from a docs template, sent whenever
- **[ 1 ]** Numbered, dated, sent on completion
- **[ 2 ]** Trigger-based: milestone or Friday, with terms and payment link in the body
- **[ 3 ]** Auto-scheduled with a 3-touch sequence at day 1, 7, 14, escalation rule and a late-fee line that actually exists

**Quick win (≤45 min):** Write the three chase emails now and save them as snippets: day 1 gentle ('sending this back to the top'), day 7 direct ('payment is 7 days late, here's what happens next'), day 14 formal ('work pauses on [date] until settled').

**Starter prompt:**

```text
Write a 3-touch overdue invoice sequence for a freelance [service] business. Email 1 (day 1 after due): friendly, assume oversight, restate amount, link, one line. Email 2 (day 7): direct, no apology, state consequence, offer a payment plan option in one sentence. Email 3 (day 14): formal, work paused from [date], late fee of [X] applies, keeps the relationship. Under 90 words each. Zero passive aggression.
```

*Where AI helps:* All three drafts.  
*Watch out:* Do not threaten legal action you will not take.

### 10 · MONEY — Cash and margin visibility (not revenue)

**Symptom:** Revenue looks fine, the account is tight, and no project has a real margin number.

**Score:**

- **[ 0 ]** No view beyond the bank balance
- **[ 1 ]** A monthly income figure
- **[ 2 ]** A 13-week cash view plus hours-per-project so you can see margin
- **[ 3 ]** Both maintained weekly, plus a per-client profitability habit that changes what you quote next

**Quick win (≤45 min):** Open a sheet. One row per active project: quoted, deposit in, hours spent, hourly floor. The hour column is the one people skip and the one that fixes pricing.

**Starter prompt:**

```text
Act as a fractional finance analyst for a solo [service] business. Numbers: [monthly fixed costs, average project value, typical hours per project, current cash, receivables, expected deposits next 8 weeks]. Tell me: my true hourly rate, the week I run out of buffer if nothing new signs, my minimum viable quote, and which two habits would move cash the most in 60 days. Show the arithmetic. Say plainly if my pricing is below my floor.
```

*Where AI helps:* Structure, arithmetic check, the honest sentence about pricing.  
*Watch out:* Do not treat AI output as tax or accounting advice; keep your own records and ask a professional once a year.

### 11 · KNOWLEDGE — A place that remembers so you don't have to

**Symptom:** You solve the same problem four times a year and re-solve it from scratch each time.

**Score:**

- **[ 0 ]** It's in my head
- **[ 1 ]** Notes exist, scattered
- **[ 2 ]** One searchable store: decisions made, snippets, boilerplates, lessons
- **[ 3 ]** New decisions land there automatically at end of week, and AI is allowed to read it as context before it drafts anything for you

**Quick win (≤45 min):** Create one file per client called 'decisions'. Start it now with the three decisions from this month and one line each: what, why, date.

**Starter prompt:**

```text
Turn this messy project note into a reusable record. Output exactly four headings: Decision made / Why / When it must be revisited / Boilerplate I can reuse next time. Note: [paste]. No summary paragraph.
```

*Where AI helps:* Converts your week's mess into a library that compounds.  
*Watch out:* Keep client-confidential data out of AI context unless your plan and their agreement allow it.

### 12 · GROWTH — Offboarding that harvests the proof

**Symptom:** Projects end with a handshake. No testimonial, no case study, no referral ask.

**Score:**

- **[ 0 ]** Nothing happens at the end
- **[ 1 ]** You ask for a review sometimes
- **[ 2 ]** A fixed offboarding message: outcome recap, testimonial ask with a 3-question prompt, referral line
- **[ 3 ]** Every closed project produces a case study paragraph and a dated testimonial, filed next to the project

**Quick win (≤45 min):** Draft the one message you'll send at every project end: recap of their outcome in numbers, three questions that make a testimonial easy to write, and a permission line to publish it.

**Starter prompt:**

```text
Write an offboarding message for a completed [service] project. Include: a two-line recap of what we delivered framed as their outcome, three questions that make writing a testimonial effortless (before/after, what surprised you, what you'd tell someone considering me), one sentence asking for a referral with a specific target profile, and a plain permission line to publish their words. Under 150 words, warm, no marketing speak.
```

*Where AI helps:* Drafts the ask and formats the case study from their reply.  
*Watch out:* Never write or plant a testimonial. Publish what they actually said, with permission.

## Guardrails

- **AI may draft** — Client comms first drafts, change classification, research briefs, meeting summaries, invoice chase wording, my own weekly review
- **AI may decide** — Nothing about money, dates, scope or who becomes a client
- **AI must never touch** — Bank logins, contracts without your read, health or legal conclusions, client credentials, anything you haven't verified against your own record
- **Before every launch** — Read the AI output once out loud. If you would not sign it, do not send it.

## Then: seven days

- Day 1 - Point 1: five qualifying questions into your enquiry reply.
- Day 2 - Point 3: the six-bullet 'not included' block in your proposal.
- Day 3 - Point 9: three chase emails saved as snippets.
- Day 4 - Point 6: send a weekly digest to every active client, thin version fine.
- Day 5 - Point 10: project sheet with the hours column, numbers ugly is fine.
- Day 6 - Point 12: offboarding message drafted and sent to last week's finished client.
- Day 7 - Re-score all 12 points. Two points moved, you have a system. None moved, the problem was time, not tooling - cut two client-facing hours a week before adding anything new.

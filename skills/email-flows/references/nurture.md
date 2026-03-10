# Nurture Email Flow

*Ongoing value sequences that build trust, demonstrate expertise, and prime for offers — from 7-day mini-sequences to 30-day daily flows.*

Sources: Larsen (FAQ-driven content method), Kennedy (Ultimate Sales Letter — write to one person, PAS, internal dialogue), Clemens (Persuasion Story Code — epiphany bridge, villain, two futures), Collier (enter the conversation, dominant desire), Brunson (Hook/Story/Offer), Cialdini (reciprocity, commitment/consistency)

---

## Nurture Intake

Before writing, gather these details from the user. Use `AskUserQuestion` or conversational follow-up — don't dump all questions at once.

**Required:**
- How many emails? (default: 30)
- Send interval? (default: daily. Options: daily, every other day, 2x/week, weekly)
- Do you have a FAQ document? If so, where? (file path)
- What's the product/service being nurtured toward?
- What's the primary offer? (or is this pure nurture with no pitch?)
- What percentage of emails should include a soft CTA? (default: ~20-30%)
- Who is the audience? (cold leads, warm leads, existing customers, mixed)

**If available:**
- BRIEF.md or existing audience research
- Known objections specific to the offer
- Voice/tone samples (previous emails, social posts, anything that sounds like the sender)
- Whether there's a hard deadline or evergreen

If the user doesn't have all of this, draft with placeholders marked `[PLACEHOLDER: ...]` and note what's missing.

---

## FAQ-Driven Content Architecture (Larsen Method)

This is the engine of the entire sequence. Instead of staring at a blank page thinking "what should email #14 be about?", you work from a pre-built content pool that ensures every email has substantive subject matter.

### How It Works

1. **Define 8-10 categories of operation** within your domain. These are the major topic areas your audience cares about. For a video editing agency: cameras, lighting, scripting, editing software, color grading, sound design, client management, pricing. For a SaaS: onboarding, integrations, reporting, team workflows, pricing, security, migration, support.
2. **For each category, generate 30-50 FAQs** — questions your audience actually asks, objections they have, things they get wrong, misconceptions they hold, fears they won't say out loud.
3. **This produces a pool of 240-500 potential email topics.**
4. **Pare down to your email count** by scoring and selecting the strongest FAQs.

### The FAQ Document

The FAQ document is created in a separate process. When running this playbook, check if a FAQ document exists. If it does, read it and use it as the content source. If it doesn't, tell the user to create one first — the nurture flow is only as good as its source material.

**Expected FAQ document format:**
```markdown
# FAQ Document: [Product/Service]

## [Category 1: e.g., Cameras]
1. What camera should beginners start with?
2. Does camera quality actually matter for social media?
3. Why do my videos look amateur even with a good camera?
...

## [Category 2: e.g., Lighting]
1. Can you get professional lighting on a budget?
2. Why does natural light make such a difference?
...
```

### Paring Down from FAQ Pool to Email Sequence

Score each FAQ on three dimensions:

| Dimension | What it measures | High score means |
|-----------|-----------------|------------------|
| **Objection strength** | Does this FAQ represent a belief that blocks the sale? | Must include — removing this objection clears the path to purchase |
| **Value density** | Can you teach something genuinely useful answering this? | Builds trust through reciprocity — reader feels they got something real |
| **Story potential** | Can this become a narrative with an epiphany bridge? | More engaging email — Clemens techniques apply naturally |

**Selection rules:**
- **Category rotation:** No more than 2 emails in a row from the same category
- **Mix:** Balance objection-handling FAQs and value-giving FAQs
- **Early sequence:** Favor curiosity and value FAQs (build trust first)
- **Later sequence:** Shift toward objection-handling FAQs that prime for the offer
- Each selected FAQ becomes the email's **subject matter** — NOT the subject line. The subject line uses A-pile principles from the parent skill.

---

## Email Type Mix

A 30-day nurture isn't 30 identical value emails. It's a deliberate mix of email types, each doing a different job.

| Email type | Frequency | Job | Structure |
|------------|-----------|-----|-----------|
| **Value** | 40-50% | Teach WHAT and WHY, hold back HOW | FAQ answer → insight → open loop to next email |
| **Story** | 15-20% | Build connection, break beliefs | Epiphany bridge: "I used to think [FAQ assumption]. Then I discovered..." |
| **Proof** | 10-15% | Build credibility through specific results | Case study told as narrative (Clemens), not stat dump |
| **Belief-break** | 10-15% | Reframe a false belief | Contrarian take on a FAQ — "What most people get wrong about X" |
| **Soft pitch** | 10-20% | Periodic CTA without hard sell | Value first, insight, then "if you want help with this..." at the end |

### Assigning Types to FAQs

Match the FAQ's nature to the email type it fits best:
- FAQ is a common misconception → **belief-break** email
- FAQ has a great story behind it → **story** email
- FAQ has clear proof/results → **proof** email
- FAQ is a genuine how-to question → **value** email
- FAQ touches the core offer directly → **soft pitch** email

---

## Sequencing Principles

**Open sequences by naming what prospect is doing now (Dunford).** The first 1-3 emails should establish context by naming the status quo or alternative the subscriber is currently using — before introducing your solution. "You're probably managing this in spreadsheets," or "Most teams use Slack for this, which is why coordination breaks down around 10 people." This competitive-alternatives framing proves you understand their world and sets up the natural question: "why does that fail?" Most nurture sequences jump straight to value without acknowledging what the reader is already doing. When you name the current approach first, the reader recognizes themselves and the insights that follow land as direct alternatives to something concrete, not abstract improvements.

| Phase | Emails | Mix | CTA frequency | Emotional register |
|-------|--------|-----|---------------|-------------------|
| **Trust-building** | 1-5 | Pure value + 1 story | None | Generous, warm, establishing voice |
| **Deepening** | 6-15 | Value/story/proof rotation | 1 in 4 (~25%) | Confident, authority-building |
| **Belief-shifting** | 16-25 | More proof + belief-breaks | 1 in 3 (~33%) | Challenging, reframing |
| **Conversion** | 26-30 | Proof + pitch emphasis | Every email has CTA | Direct, urgent (if offer exists) |

If this is pure nurture with no end offer, maintain the Trust-building → Deepening pattern indefinitely. Skip the Conversion phase.

### Adapting for Shorter Sequences

Not every nurture is 30 emails. Scale the phases proportionally:

| Sequence length | Trust-building | Deepening | Belief-shifting | Conversion |
|----------------|---------------|-----------|-----------------|------------|
| **7 emails** | 1-2 | 3-5 | 5-6 | 7 |
| **14 emails** | 1-3 | 4-9 | 10-12 | 13-14 |
| **21 emails** | 1-4 | 5-12 | 13-18 | 19-21 |
| **30 emails** | 1-5 | 6-15 | 16-25 | 26-30 |

The ratio stays roughly the same: ~15% trust, ~35% deepening, ~35% belief-shifting, ~15% conversion. The trust-building phase is the one section you never compress below 2 emails — you need at least 2 pure value sends before anything else.

### Sequence Iteration for Long Flows (Fenton & Waltz)

For flows longer than 14 emails, don't design all 30 emails upfront as a finished sequence. Build the first 7 as deliberate angle tests — vary the email type, category, register, and style across those 7 to discover what the audience responds to. Track opens, clicks, replies, and unsubscribes per email.

**The first 7 emails are an experiment. Emails 8+ are informed by data.**

What to vary in the test batch:
- **Type:** Mix value, story, proof, and belief-break across all 7 — don't cluster types
- **Category:** Draw from at least 4-5 different FAQ categories
- **Register:** Test formal vs. conversational, long vs. short, direct vs. narrative
- **Style:** One email might be a single-question hook. Another might be a 400-word story. Another might be a list of 5 contrarian takes

After the first 7 send, examine the data:
- Which email types had the highest engagement? Double down on those in emails 8-14.
- Which categories fell flat? Deprioritize them or reframe the angle.
- Which register resonated? Let it become the baseline voice for the rest of the sequence.
- Which style got replies? That's the format the audience wants more of.

This prevents the most common long-sequence failure: designing 30 emails from theory, then discovering at email 12 that the audience doesn't care about half the categories you chose. Volume reveals what converts — not planning alone.

### Intelligence-Gathering Emails (Belfort)

Place 1-2 intelligence-gathering emails early in the trust-building phase (emails 2-4). Their job is to identify which certainty each subscriber needs most so the rest of the sequence can target the gap.

**Formats that work:**

- **"Which describes you best?"** — Give 2-3 options that map to certainty gaps. "Reply with A, B, or C" where A = "I'm not sure this approach works" (low product certainty), B = "I don't know enough about you/your company" (low personal/company trust), C = "I know I need this but can't pull the trigger" (high action threshold).
- **Click-to-segment links** — Each link goes to the same page but is tagged differently. "What's your biggest challenge right now? [Link 1: Getting results] [Link 2: Finding someone I trust] [Link 3: Making the leap]." The click tells you which certainty to prioritize.
- **Single-question reply** — "Hit reply and tell me: what's the ONE thing holding you back from [desired outcome]?" Open-ended, but the answers cluster into certainty categories.

If the ESP supports segmentation, tag subscribers by their response and branch the sequence. If it doesn't, the intelligence still shapes the overall mix — if 70% of replies indicate low product certainty, weight the sequence toward proof and results.

These emails also build trust through the act of asking. Subscribers who reply or click feel heard, which raises personal trust as a side effect. The intelligence-gathering email pulls double duty: it segments AND it nurtures.

### Category Rotation System

- Track which category the last 2 emails drew from
- Never send 3+ emails from the same category consecutively
- With 8 categories and 30 emails: roughly 3-4 emails per category, evenly distributed
- Exception: if a story or proof email naturally follows a value email on the same topic, that's a deliberate 2-email arc (acceptable)

---

## Story Techniques for Nurture (Clemens)

Apply these to Story and Belief-break emails:

**Epiphany bridge:** "I used to think [FAQ assumption]. Then I discovered [insight]. Here's what changed..." — recreate the moment of realization so the reader has the same aha. The bridge has five beats: before state, tension, the moment, the realization, the after. Don't skip the tension — it's what makes the realization land.

**The villain:** Name the force causing the problem. Not a competitor — a system, a conventional wisdom, an industry norm. "The reason most people fail at X isn't laziness — it's that every YouTube tutorial teaches the wrong approach." The villain gives the reader an enemy that isn't themselves. That's critical — most people already blame themselves for failing.

**Two futures:** End emails with a contrast. Life without this insight (honest trajectory, specific, sensory) vs. life with it (specific, achievable, real). Don't exaggerate either side. The "no action" future isn't doom — it's the honest extension of their current path. The "action" future isn't fantasy — it's a specific Tuesday morning when something is different.

**Proof through narrative:** When citing results, tell it as a story: who the person was, where they started, what they tried, what changed, specific result, how they felt. Not: "Client got 300% ROI." Stories bypass the critical filter; stats activate it. Structure: relatable person → same starting point as the reader → same failed attempts → the change → specific measurable result → what the result meant to them emotionally.

---

## Hook, Story, Offer Applied to Nurture (Brunson)

Even in non-pitch emails, this structure works:

**Hook:** The subject line + first sentence. Enter their conversation (Collier). Start where they are, not where you want them to be. The reader was thinking something before they opened this email — join that thought.

**Story:** The body. Narrative, insight, teaching — but always through a lens, not a lecture. Sugarman's slippery slide applies: every line's job is to get them to read the next line. No exit ramps.

**Offer:** Not always a product pitch. Sometimes the "offer" is: "Try this one thing today." Or: "Reply and tell me what happened." Or an open loop to tomorrow's email. The offer is the next action, whatever it is.

---

## Internal Dialogue (Kennedy)

Every line of the email triggers a thought in the reader's mind. The next line should answer that thought. Read each email imagining the reader saying "So what?" or "Why should I care?" or "Is that true?" after every sentence. The sentence that follows should address that reaction.

| You write | They think | Your next line should |
|-----------|-----------|----------------------|
| "Most creators get lighting wrong." | "Do I get it wrong?" | Make it personal — describe the specific mistake they recognize |
| "I tested this on 40 projects last year." | "Prove it." | Give one specific result with a number, a client, a before/after |
| "Here's what actually matters about color grading." | "This better be good." | Deliver a genuine insight immediately — no throat-clearing |
| "If you want help implementing this..." | "Here comes the pitch." | Lead with what they get, not what it costs. Or better: make the CTA feel like a natural next step, not a gear shift |

This is the line-by-line test that separates emails people read from emails people delete at paragraph two. Every email should pass this test before it ships.

---

## Write to One Person

Nurture emails should read like messages from a specific person to a specific person. Not broadcasts. Not newsletters. Use "you" (singular), reference specific situations ("You know that moment when you're editing at 2am and the timeline just won't cooperate?"), write in the voice of a real human with opinions.

Collier's "you" ratio applies: count the "you/your" words vs "we/our/I" words. The ratio should heavily favor "you." Kennedy's principle: if the email doesn't feel like it was written to one person sitting across the table, it's too broad.

| Broadcast voice (weak) | One-person voice (strong) |
|------------------------|--------------------------|
| "Many video editors struggle with color grading." | "You've stared at that timeline for 20 minutes wondering why it looks off." |
| "Our clients often report improved results." | "Last week, a creator sent me her before/after. Same camera. Same room. Completely different footage." |
| "In the video editing industry, lighting is important." | "Your footage looks amateur and you can't figure out why. It's not the camera." |

---

## Before/After Examples

### Value Email — Generic Tip vs. FAQ-Driven with Personality

**Before (generic):**
> Subject: Tip #14: Use natural light
>
> Natural light is great for video because it creates a soft, flattering look. Try filming near a window during golden hour for best results. You can also use a white sheet as a diffuser. Good lighting doesn't have to be expensive!

**After (FAQ-driven):**
> Subject: Your $3,000 lighting kit is making things worse
>
> I get this question constantly: "What lighting setup do you recommend?"
>
> Here's what nobody tells you.
>
> The most expensive lighting mistake isn't buying cheap gear. It's buying too much gear and creating a look that screams "I'm trying too hard."
>
> I've color-graded footage from creators with $5,000 setups that looked worse than an iPhone propped against a window at 4pm.
>
> The difference wasn't the equipment. It was understanding one thing about how light falls on a face — something a $3,000 kit can't teach you and a window can.
>
> Tomorrow I'll break down exactly what that one thing is. If you've ever stared at your footage and thought "why doesn't this look professional?" — that email is for you.

### Soft Pitch Email — Hard Sell vs. Value-First with Natural CTA

**Before (hard sell):**
> Subject: Are you tired of bad video quality?
>
> Our course can help! You'll learn professional techniques used by top creators. Sign up now for 50% off! This deal won't last forever. Click here to transform your videos today!

**After (value-first):**
> Subject: The color grading trick that takes 90 seconds
>
> Most creators skip color grading because it feels like a rabbit hole. Hours of tutorials. Confusing software. Curves and scopes and LUTs.
>
> Here's one thing you can do in 90 seconds that fixes 80% of the "why does my video look off?" problem:
>
> Drop the highlights by 10%. Lift the shadows by 5%. Add a single point of warmth to the midtones.
>
> That's it. Takes 90 seconds. Works in Premiere, DaVinci, even CapCut.
>
> Your footage will look like a different camera shot it.
>
> This is one of 12 techniques we break down step-by-step in [Program] — with side-by-side before/afters for each one. If you want the full system: [link]. Either way, the principle above works on its own. Try it on your next edit.

---

## The Output

When writing a nurture flow, output:

1. **Content map** — a table showing all [N] emails:

| # | Category | FAQ Source | Type | Subject Line | Angle |
|---|----------|-----------|------|-------------|-------|
| 1 | Cameras | "What camera should beginners start with?" | Value | "The camera doesn't matter (yet)" | Reframe the gear obsession — show what actually matters in first 30 days |
| 2 | Lighting | "Can you get professional lighting on a budget?" | Story | "The $12 lamp that changed everything" | Epiphany bridge — discovery that expensive ≠ professional |
| 3 | Scripting | "Why do my videos feel awkward?" | Belief-break | "Stop writing scripts" | Contrarian take — scripts cause the problem they're meant to solve |
| ... | ... | ... | ... | ... | ... |

2. **Full email copy** for each email in sequence, following the parent SKILL.md output format

---

## Anti-Patterns

- **30 identical "value" emails with no type variety.** Monotone flow — reader tunes out by email 5. Vary the email types deliberately.
- **Teaching the HOW in value emails.** Give away the full solution and there's no reason to buy. Teach WHAT and WHY. Hold back the complete HOW.
- **No personality.** Reads like a textbook, not a person talking. Kennedy: write to one person. Collier: the letter is a conversation. If it sounds institutional, rewrite it.
- **Pitching in every email.** Burns trust, trains readers to ignore you. Emails 1-5 should have zero pitch.
- **Never pitching.** You built a list and never make an offer — the trust was pointless. Reciprocity (Cialdini) creates goodwill, but goodwill without a next step is a dead end.
- **No category rotation.** 5 emails about lighting in a row bores people who don't care about lighting. Rotate categories to keep the sequence fresh.
- **Generic subject lines.** "Tip #14," "Quick tip," "Did you know?" — violates A-pile principle from parent skill. Subject lines should enter the conversation, not label the content.
- **No open loops between emails.** Each email stands completely alone, no forward momentum through the sequence. Plant seeds (Sugarman) that pull the reader into tomorrow's email.
- **Starting with pitches before trust is built.** Emails 1-5 should be pure value. You haven't earned the right to ask yet.
- **Ignoring the FAQ document.** Writing emails from scratch when curated content already exists is wasting the most valuable input you have.
- **Belief-break emails without story.** Just stating "you're wrong about X" without the epiphany bridge feels preachy. Show the journey from wrong belief to right belief — don't lecture.
- **Same length for every email.** Vary based on email type — story emails run longer (300-500 words), soft pitch emails run shorter (150-250 words), value emails sit in between.

# Guide

How to use these skills together. The workflow, not just the tools.

## The Foundation: Brief and Voice

Every project starts here. Skip this and everything downstream will be generic.

### 1. Run `/brief`

```
/brief
```

Claude will ask about your product, audience, problem, and proof. Answer with specifics. Vague inputs produce vague outputs.

The skill creates `.claude/BRIEF.md`. This document captures:

- Who you're talking to (and who you're not)
- What problem you solve and why it matters
- How you're different from alternatives
- The exact language your audience uses
- Proof that backs up your claims

Every other skill reads this file automatically.

### 2. Run `/voice`

```
/voice
```

This creates `.claude/VOICE.md`: your brand's tone, style rules, vocabulary, and anti-voice (what you never sound like).

The voice skill reads your brief first. It proposes a voice that fits your positioning and audience.

**Now you have the foundation.** Brief defines what you say. Voice defines how you say it.

---

## Building a Sales Page

With brief and voice in place:

```
/sales-pages
```

The skill asks what type of page you need (landing page, opt-in, long-form sales page, etc.) and builds the full structure:

- Hero section
- Problem agitation
- Mechanism (how it works)
- Proof stack
- Offer
- CTA

The output references your brief for positioning, your voice for tone, and your proof points for credibility. It's not generic copy. It's your copy.

### What to expect

The skill produces a complete page structure with copy. You'll likely want to:

1. Review the hero. Does it grab attention and match your positioning?
2. Check the proof section. Is it specific enough?
3. Adjust the CTA. Does the action match your funnel?

Run `/copy` on any section that needs sharpening.

---

## Writing an Email Sequence

```
/email-flows
```

The skill asks what type of sequence:

- **Welcome/onboarding**: new subscriber or customer
- **Launch**: product or feature release
- **Nurture**: ongoing value delivery
- **Webinar**: registration, reminder, replay, pitch

Each flow type has its own structure. A launch sequence builds anticipation differently than a nurture sequence builds trust.

### How it connects

The email flow skill reads your brief for:

- Audience pain points (what problems to address)
- Objections (what to preempt)
- Proof (what to reference)
- Voice (how to sound)

A 5-email welcome sequence might look like:

1. Delivery + quick win
2. Story + credibility
3. Problem agitation
4. Mechanism + proof
5. Soft CTA

Each email has a job. The skill knows the structure. You provide the specifics.

---

## Creating Ad Hooks

```
/ad-hooks
```

The skill generates hooks using 18 proven architectures:

- Pattern interrupt
- Contrarian
- Specific result
- Curiosity gap
- And 14 more

It reads your brief for:

- Dominant desire (what they want most)
- Pain points (what to agitate)
- Proof points (what makes claims credible)

### Output format

You get multiple hooks per architecture. Test them. The skill generates volume. Your job is selection.

Hooks work for:

- Ad creative (Facebook, YouTube, TikTok)
- Email subject lines
- Landing page headlines
- Content hooks

Run `/copy` to develop any hook into full copy.

---

## The Copy Skill

```
/copy
```

This is the sharpening tool. Use it on:

- Headlines that aren't punchy enough
- Body copy that's too long
- Bullets that don't land
- CTAs that feel weak

The skill applies direct-response principles: specificity, curiosity, benefit-forward, proof-backed.

### When to use it

After any other skill, when specific sections need work. It's a scalpel, not a chainsaw.

---

## Building a Content System

```
/content-engine
```

This skill designs your ongoing content strategy:

- Content pillars (3-5 themes)
- Platform strategy (where to post, format per platform)
- Repurposing workflow (one piece → many formats)
- Posting cadence (realistic, sustainable)

It reads your brief for audience and positioning, then builds a system you can actually execute.

---

## Cold Outreach Sequences

```
/cold-outreach
```

For prospecting: email or DM sequences to cold leads.

The skill builds:

- Opening hook (pattern interrupt, not "Hope this finds you well")
- Value prop (why they should care)
- Proof (why they should believe you)
- CTA (low-friction ask)
- Follow-up sequence (2-4 additional touches)

Cold outreach is different from marketing copy. It's one-to-one, interrupting someone's day. The skill knows the difference.

---

## Workflow Summary

For a new product or project:

1. `/brief`: Define positioning, audience, problem, proof
2. `/voice`: Define tone and style
3. `/sales-pages`: Build the landing page
4. `/email-flows`: Create the welcome or launch sequence
5. `/ad-hooks`: Generate hooks for ads and content
6. `/copy`: Sharpen any section that needs it

For ongoing marketing:

- `/content-engine`: Design your content system
- `/cold-outreach`: Build prospecting sequences
- `/ad-hooks`: Generate fresh hooks
- `/copy`: Sharpen as needed

The brief and voice persist. Every skill reads them. Update them when your positioning evolves.

---

## The Full Library

These 8 skills are the open-source marketing subset. The full library is 34 skills covering product design, mobile/web development, pricing strategy, UX architecture, onboarding, paywalls, and more.

The full library is available to mentees of the [Spec Coding Mentorship](https://jwallaceparker.com/mentorship).

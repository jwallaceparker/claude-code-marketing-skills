# Claude Code Marketing Skills

8 AI skills for solo builders who ship products but struggle with marketing.

Principles, not prompts.

## What This Is

A skill library that teaches Claude Code to produce expert-level marketing output. Each skill encodes domain expertise (what good looks like, what to avoid, how to think about the problem) drawn from cited sources.

This is not a prompt collection. It's the same approach that makes vibe coding work: give the AI real expertise to draw from, not instructions to follow.

## Skills Included

| Skill | What It Does |
|-------|--------------|
| **brief** | Create the foundation document: positioning, audience, messaging, proof. Every other skill reads this. |
| **voice** | Generate a brand voice guide: tone, style rules, vocabulary, anti-voice. |
| **sales-pages** | Write complete landing pages: hero, problem, mechanism, proof, offer, CTA. |
| **copy** | Sharpen headlines, hooks, bullets, body copy. The building blocks. |
| **ad-hooks** | Generate hooks using 18 proven architectures. |
| **email-flows** | Write complete sequences: welcome, launch, nurture, re-engagement. |
| **cold-outreach** | Build prospecting sequences with full copy and response branches. |
| **content-engine** | Design a content system: pillars, platform strategy, repurposing, cadence. |

## Installation

Copy the `skills/` directory to your Claude Code configuration:

```bash
cp -r skills/* ~/.claude/skills/
```

Or clone and symlink:

```bash
git clone https://github.com/jwallaceparker/claude-code-marketing-skills.git
ln -s $(pwd)/claude-code-marketing-skills/skills/* ~/.claude/skills/
```

## How to Use

1. Run `/brief` first. It creates the foundation document at `.claude/BRIEF.md`
2. Run `/voice` to define tone at `.claude/VOICE.md`
3. Run any other skill as needed

Each skill reads your brief and voice automatically. Output is localized to your product, not generic.

**[→ Full usage guide](GUIDE.md)**: workflows, what to expect, how the skills connect.

## Philosophy

**Source-first.** Every principle traced to a published expert. Nothing invented.

**Principles over prompts.** Skills teach Claude how an expert thinks, not what to type.

**Interconnected.** The brief informs the sales page. The sales page informs the email sequence. Nothing exists in isolation.

## The Full Library

This is the open-source marketing subset.

The full library is 34 skills covering product design, mobile/web development, pricing strategy, UX architecture, onboarding, paywalls, and more.

The full library is available to mentees of the [Spec Coding Mentorship](https://jwallaceparker.com/mentorship).

"Vibe coding builds demos. Spec coding builds products."

## Links

- [jwallaceparker.com](https://jwallaceparker.com)
- [@jwallaceparker](https://x.com/jwallaceparker) on X

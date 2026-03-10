---
name: voice
description: Generate a deep voice guide for a project — .claude/VOICE.md. Defines the brand character, status, metaphor system, style rules, vocabulary, context-specific register shifts, and anti-voice. Use when the user says "voice guide," "brand voice," "tone of voice," "how should we sound," "voice document," "writing style guide," or "voice rules." Reads BRIEF.md for baseline voice and product context. Optionally analyzes writing samples and existing codebase copy.
---

# Voice

You generate `.claude/VOICE.md` — the deep voice guide for a project. Not tone adjectives. Not a style guide PDF nobody reads. A working document that every copy-producing skill in the system consumes: offers, cold-outreach, email-flows, sales-pages, decks, content-engine. The VOICE.md defines who this brand is as a communicator — how it sounds, what it never says, and how its register shifts across contexts.

Brief captures voice basics. VOICE.md goes deep. Run `/brief` first for the seed, then `/voice` to expand it. Or run `/voice` standalone if you have writing samples and context.

Voice is also a similarity signal (Cialdini: Influence). People trust voices that sound like their internal monologue — the way they talk to themselves about their problems, not the way a brand talks about solutions. Extract specific phrases from customer language (support tickets, reviews, forum posts, sales call transcripts) and embed them in the voice guide as approved vocabulary. The voice guide should be grounded in verbatim audience language — how real customers talk about their problems, desires, and solutions (Halbert). Read their Reddit posts, DMs, reviews, and sales call transcripts. The voice absorbs their vocabulary and rhythm. A voice built from research sounds like it understands the reader. A voice built from adjective brainstorming ("professional yet approachable") sounds like it was designed in a conference room. The gap between "brand voice" and "how the audience actually talks" is where trust leaks. A voice guide that sounds like the brand talking TO the audience creates distance. One that sounds like the audience talking to each other creates belonging. The anti-pattern is over-polished professional language when the audience uses casual, specific, colloquial speech — or formal register when the audience is irreverent. Mirror their register, not your aspirational register. The voice should make the reader feel "this person talks like me" before they evaluate whether the content is good.

The voice guide should establish genuine interest in the reader's world as the default orientation — not interest as a persuasion technique, but interest as a posture (Carnegie). The test: would this voice sound the same if there were nothing to sell? If the warmth disappears when the product mention is removed, the interest is performative. The voice doc should name what the brand is genuinely curious about in the customer's world — their daily frustrations, their ambitions, the problems they talk about at dinner — because that curiosity becomes the fuel for every downstream skill that reads VOICE.md.

Sources: Alexander (A Pattern Language — quality without a name as alive vs. performed voice, voice as connection layer across copy-producing skills, wholeness as system coherence), Baker (The Business of Expertise — vendor signals vs expert signals in linguistic patterns, eagerness language undermines expertise positioning, constraint language and pattern-recognition phrasing signal expert status), Saunders (A Swim in a Pond in the Rain — voice as cumulative trust where every word deposits or withdraws), O'Bannon (Guide to Screenplay Structure — tension/release rhythm as voice character), Ogilvy (Ogilvy on Advertising — brand as character, personality consistency), Weston (Directing Actors — playable actions vs. unplayable results, subtext carried by performer), Johnstone (Impro — status transactions, reincorporation, the inner censor), Cabane (Charisma Myth — Presence/Power/Warmth, charisma styles), Caine (Acting in Film — stillness as voice power, scale it down, first-take energy), Cannell & Travis (YouTube Secrets — cross-platform voice consistency as audience recognition), Lakoff/Johnson (Metaphors We Live By — conceptual metaphor systems, highlight/hide), Halbert (The Boron Letters — research-first voice construction, 8th-grade simplicity default), Heinrichs (Thank You for Arguing — decorum, rhetorical registers), Howard & Mabley (The Tools of Screenwriting — invisible exposition, conflict at every level as voice diagnostic), Kennedy (Ultimate Sales Letter — write to one person, damaging admission), Berger (Contagious — voice shifts by outcome), McCloud (Understanding Comics — abstraction ladder, composition as voice), Aristotle (Rhetoric — elocutio, ethos demonstration, kairos), Feynman (Surely You're Joking — pretension test, specificity of observation, simplicity as proof of understanding), Goffman (Presentation of Self — front/back stage, expressions given off, audience segregation, role distance), de Bono (Lateral Thinking — dominant pattern, cross-domain analogy), Tharp (The Creative Habit — creative DNA, rut vs. groove, scratching), Seger (You Talkin' to Me? — voice as character, rhythm patterns, metaphor as subtext, status through sentence structure, punctuation as speech pattern), Seger (Writing Subtext — metaphor system as symbolic subtext), Truffaut (Hitchcock/Truffaut — POV register shifts), Yorke (Into the Woods — brand flaw, shadow self positioning), Hunter (Screenwriting 434 — emotional truth, revision layers), Pearson (Hero Within — brand archetypes as character scaffolding), Vorhaus (The Comic Toolbox — rule of three as rhetorical rhythm), Luntz (Words That Work — reception vs. intent, word-level simplicity, sound/texture, consistency over synonym-rotation), Mackendrick (On Film-Making — subtext as voice depth, tempo variation), Schwartz (Breakthrough Advertising — awareness-level register shifts), Cialdini (Influence — liking and similarity as voice calibration driver), Belfort (Way of the Wolf — tonal patterns, certainty transfer), Godin (Tribes — leader vs manager voice, heretical positioning, conviction over hedging), Godin (Purple Cow — very-good language audit, safety test), Godin (All Marketers Are Liars — worldview alignment, authenticity structure), Godin (This Is Marketing — status-role calibration, signal congruence), Godin (Permission Marketing — recipient-first voice), Brunson (Expert Secrets — Epiphany Bridge), Brunson (Dotcom Secrets — Attractive Character), Lumet (Making Movies — tone vs mood as voice architecture, commitment, point of view about everything), Mamet (On Directing Film — uninflected presentation, eliminate interesting), Miller (Building a StoryBrand — guide voice, BrandScript), Carnegie (How to Win Friends — genuine-interest orientation, appreciation vs flattery, vulnerability as trust register), Kahneman (Thinking, Fast and Slow — cognitive ease as trust signal, fluency test, mere exposure effect for consistent vocabulary), Collier (The Robert Collier Letter Book — conversational rhythm, specificity as voice default), Garfinkel (Breakthrough Copywriting — four dimensions, deep structure), Bachelard (The Poetics of Space — psychic anchor, verticality, inside/outside belonging), Abraham (Getting Everything You Can — preeminence as voice posture, USP-voice alignment), Camp (Start with No — Columbo effect as deliberate uncertainty, decisions are emotional for dimension sequencing), McPhee (Draft No. 4 — character sketch as structural commitment, prohibitions as character definitions, discovered vs intended voice), Whitman (Cashvertising — Camera Test for voice audit, LF8 emotional register field), Ariely (Predictably Irrational — social-to-market norm bridge in register shifts, voice as expectation architecture), Sullivan (Hey Whipple, Squeeze This — kill category dead metaphors, ugly-first character drafting), Duarte (Resonate — reader as hero, brand as mentor, first/last line emotional weight), Kane (One Million Followers — platform grammar as structural voice constraint), Levitin (This Is Your Brain on Music — word texture as timbre, variation within consistency, genre schemas for register shifts), Barden (Decoded — brands as goal-signal systems, implicit goal determines signal design), Heath (Switch — voice register that speaks to Elephant and Rider, emotional vocabulary for Find the Feeling, clarity principles for Script the Critical Moves), Moesta (Demand-Side Sales 101 — Customer Language for voice sourcing, Supply-Side vs. Demand-Side for voice framing), Dunford (Obviously Awesome — whole-company voice deployment for positioning consistency, category-voice expectations for competitive context, best-fit targeting for voice construction), Brand (How Buildings Learn — voice emerges from authentic brand character and natural communication patterns, voice guide evolves through performance data on what resonates, continuous voice refinement prevents guide drift from actual brand communication), Aftel (Essence and Alchemy — blending opposites creates voice tension and interest, authenticity has texture not synthetic smoothness), Baer & Lemin (Talk Triggers — Five Types Talkable Attitude as voice domain, Same Is Lame for category voice norm deviation, Consistency Over Surprise for voice touchpoint consistency), Barthes (Camera Lucida — pose and its death for voice that lives in structural truth not declared authenticity, studium vs punctum for voice elements that exceed brand guidelines, resistance to meaning for uncoded voice qualities that cannot be explained), Barthes (Mythologies — mythical speech act for tone as separate persuasion channel, naturalization for voice that feels inevitable not chosen, tonal consistency as mythological proof of coherence, bourgeois sign for matching audience cultural codes), Beckwith (Selling the Invisible — sell the feeling through confident voice without hedging, price signals quality through voice delivery), Bellos (Is That a Fish in Your Ear? — translator must be invisible for native not translated feel, register is a choice by context, audience determines success), Berger (Ways of Seeing — specificity over mystification for concrete language over abstractions), Blount (Fanatical Prospecting — confident unattached tone, copy that signals comfort with rejection), Bly (The Copywriter's Handbook — clarity principles), Bourdain (Kitchen Confidential — voice as the product, anti-corporate voice, earned irreverence, rhythm and pacing, genuine curiosity), Brook (The Empty Space — Deadly Theater audit, Rough Theater authenticity, repetition trap for voice calcification), Brooks (The Mythical Man-Month — conceptual integrity, documentary hypothesis), Burgis (Wanting — modeling desire deliberately), Byrne (How Music Works — repetition and variation, amateur energy vs polish), Carse (Finite and Infinite Games — surprise and the infinite player, theatrical vs dramatic, educated vs trained), Catmull (Creativity, Inc. — ugly baby, new ideas need iteration, don't polish to death prematurely), Chernow (Titan — reputation as strategic asset, trust as competitive weapon), Cohen (The Fish That Ate the Whale — outsider's advantage, compete on different terms, authenticity over mimicry), Cole (The Art and Business of Online Writing — psychographic reader definition, use reader's language, narrow attracts broad), Davidson & Rees-Mogg (The Sovereign Individual — sovereignty narrative, reputation as currency, post-employment positioning), Dean (Step by Step to Stand-Up Comedy — truth as foundation, reversals, misdirection in positioning), Dillard (Pilgrim at Tinker Creek — beauty and violence coexist for honest voice, via negativa for essential stripping, specificity reveals character), Enns (Win Without Pitching — peer vs supplicant language, expertise through restraint, confidence in declining), Frankl (Man's Search for Meaning — tragic optimism holds difficulty and purpose, dereflection forgets self in service, agency framing, statue in the stone for aspirational voice), Gallwey (The Inner Game of Tennis — Self 1 vs Self 2, trust vs will, the inner game happens first, learning by feel), Gross (Puppet — voice-body match, puppeteer visibility, visible seams, simplification enables projection), Haidt (The Righteous Mind — Moral Foundations Theory, WEIRD bias, groupishness, moral capital), Hansen (Deploy Empathy — voice-of-customer library, exact language preservation, three dimensions), Helitzer & Shatz (Comedy Writing Secrets — self-deprecation calibration, hostility calibration, exaggeration range, writing tight), Horowitz (The Hard Thing About Hard Things — peacetime vs wartime register, direct feedback style, company-first framing, the Struggle honesty), Isaacson/Franklin (Benjamin Franklin — pseudonyms as voice testing, audience determines voice, voice as variable not constant), Isaacson (Steve Jobs — reality distortion field for conviction in every sentence, brand as identity for tribal language and us vs them, declarative style), Jaynes (The Origin of Consciousness — bicameral command for no hedging, prophetic frame for channeling truth through evidence not ego, hallucinated voice for speech patterns and rhythm), Johnston & Thomas (The Illusion of Life — appeal as distinctive voice over generic, secondary action through tonal shifts, the illusion of life for emotional coherence, exaggeration to transmit authentic traits), Naval (The Almanack of Naval Ravikant — long-term game voice, positive-sum marketing, authenticity as moat, compound trust), Knight (Shoe Dog — founder obsession IS brand voice, community voice over marketing voice, manufactured passion fails, obsession shows in specificity), Koestler (The Act of Creation — matrix-level bisociation, codes and rules, habit vs originality, the triptych), Koren (Wabi-Sabi — imperfection over perfection, natural over manufactured, acceptance over control), Klinkenborg (Several Short Sentences About Writing — sentence as unit, habitual phrases, rhythm and variation, read as stranger), Saint-Exupéry (Wind, Sand and Stars — tool disappears, economy is beauty, craft is meaning), Kuhn (The Structure of Scientific Revolutions — paradigm-specific vocabulary, voice as paradigm signal, new paradigms need new language), Macdonald (H is for Hawk — projection destroys relationship, attention as foundational listening), McLuhan (Understanding Media — medium-is-message for medium-adapted voice, hot-vs-cool for platform temperature matching, tribal-dynamics for tribe membership signaling), Meadows (Thinking in Systems — feedback-loops for voice affecting recognition and trust, bounded-rationality for voice decisions affecting entire communication system), Meyer (Setting the Table — fifty-one-percenter for outward-focused voice with reader's situation before brand, enlightened-hospitality for authentic voice from team culture not style guide), Minto (The Pyramid Principle — scqa for brand narrative following situation-complication-answer structure, storylining for consistent narrative thread across all touchpoints), Miller (Spent — big-five-signal-targets for voice matching the trait the buyer is advertising, signal-must-match-audience for calibrating register to what audience respects and mocks, narcissism-of-small-differences for voice demonstrating tribal dialect fluency, post-consumerist-signaling for understatement as the power move with sophisticated audiences), Monmonier (How to Lie with Maps — generalization-smooths-reality for generalizing ruthlessly to make the argument legible while preserving essential truth), Neumeier (The Brand Gap — differentiate-or-die for voice flowing from differentiation encoding what makes the brand different in how it sounds, brand-is-gut-feeling for voice creating feeling before conveying information with think-feel pair governing word choice, collaborate-across-divide for VOICE.md specific enough to constrain without checking in using concrete behaviors not abstract attributes), Nosrat (Salt, Fat, Acid, Heat — salt-early-salt-often for consistent voice across all touchpoints where voice that appears only in marketing feels artificial, season-for-the-eater for calibrating voice to audience register not internal preference), Perret (The New Comedy Writing Step by Step — writing-in-someone-elses-voice for disappearing into the brand's voice studying their patterns rhythms and vocabulary, test-against-real-audiences for calibrating voice based on audience response not internal preference), Pirsig (Zen and the Art of Motorcycle Maintenance — classical-and-romantic-understanding for integrating structural soundness with emotional resonance in voice construction, caring-as-source-of-quality for voice emerging from genuine interest not performed enthusiasm, craftsmans-relationship-to-materials for respecting word rhythm weight and texture as medium properties), Polya (How to Solve It — pattern-recognition for identifying voice patterns from samples, restate-the-problem for reformulating voice challenges when initial approach fails, socratic-guide for defining voice through questions about character not prescriptions), Porter (On Competition — cost-leadership-vs-differentiation for voice that commits to positioning, strategy-is-choosing-what-not-to-do for voice constraints that reinforce positioning, stuck-in-the-middle for diagnosing voice that tries to appeal to everyone), Postman (Amusing Ourselves to Death — age-of-exposition-vs-age-of-show-business for voice that performs not just informs, conversation-of-culture for platform-adapted voice registers), Pressfield (The War of Art — territory-vs-hierarchy for voice grounded in territory not external validation, amateur-vs-professional for consistent voice emerging from daily practice), Priestley (Key Person of Influence — design-for-ascent for tone signaling upward trajectory, vitality-over-functionality for energized voice over functional delivery, dominate-micro-niche for specialist language), Strunk & White (The Elements of Style — omit-needless-words for voice that sounds confident through brevity not padding, positive-form for voice that asserts rather than hedges, nouns-and-verbs for voice built on strong nouns/verbs not adjective stacks), Taleb (Skin in the Game — soul-in-the-game for identity on the line not anonymous corporate voice, surgeons-should-not-look-like-surgeons for rough authenticity over manufactured polish, intellectual-yet-idiot for earned expertise through experience not credentials), Yakob (Paid Attention — brand-as-memory for voice as distinctive retrieval cue in consumer minds, fame-over-persuasion for distinctiveness over differentiation), Zahavi (The Handicap Principle — cheap-signals-ignored for avoiding hollow superlatives that actively damage credibility, costly-signals for specificity and admission of mistakes as trust-building cost), Zinsser (On Writing Well — strip-the-clutter for clean voice that sounds confident not corporate, find-your-voice for removing filters until only the distinctive remains, maintain-unity for consistent pronoun and stance across all touchpoints), McKee (Dialogue — three-layer voice test, blind paragraph test, silence as voice element), Greene (The Art of Seduction — seducer archetypes as brand personality framework, anti-seducer qualities as voice repellent audit)

## What Claude Gets Wrong with Voice

Without guidance, voice work fails in predictable ways. Every one of these is a default behavior you must actively override:

**Adjectives instead of character.** "Professional, friendly, approachable" could be any brand in any industry. It describes nothing and constrains nothing. A character sketch constrains. Adjectives don't. **Adjective-defined voice is unplayable (Weston).** "Warm, professional, approachable" tells the writer what to BE, not what to DO. Results are unplayable — no writer can execute "be warm" directly, because warmth is an outcome, not an action. Define voice as actions the brand takes in every communication: "We challenge conventional wisdom. We name what everyone's thinking but nobody's saying. We treat the reader as a peer who's already smart." Actions generate voice; adjectives generate performance. A writer who plays an action sounds real. A writer who performs an adjective sounds like marketing.

**No status awareness.** Mixes high-status declarations with low-status hedging in the same paragraph. "We're the definitive platform — and we'd love to show you how it might work for your situation!" is cognitive dissonance on the page.

**Dead metaphors everywhere.** "Drive growth," "unlock potential," "fuel revenue," "leverage insights." These are conceptual metaphors carrying weight nobody chose. They're invisible precisely because they're universal. A distinctive voice replaces unconscious metaphors with deliberate ones.

**One register for all contexts.** Same voice for a tweet, a nurture email, and a terms of service page. Real people shift registers constantly — formal at a conference, casual at a bar, precise in an email to their accountant. A brand voice that can't shift registers sounds robotic across contexts.

**Enthusiasm substituting for authority.** Exclamation marks where proof should be. "We're SO excited about this feature!" signals uncertainty, not confidence. A brand that has to tell you it's excited probably isn't.

**Scale-it-down failure (Caine).** A voice that over-projects — ALL CAPS, stacked exclamation points, superlatives in every sentence — is the written equivalent of an actor shouting to the back row of a theater. But the reader isn't in the back row. They're six inches from a screen. The medium is intimate, and a voice calibrated for a stadium is deafening at reading distance. Scale down for the intimacy of the medium. One exclamation mark in an email is a raised voice. Three is a person screaming in your living room. ALL CAPS in a headline is emphasis. ALL CAPS in body copy is a writer who doesn't trust the words to carry themselves. When reviewing the voice guide for calibration, ask: is this voice projecting to a crowd or speaking to one person at arm's length? If it reads like a rally, scale it down until it reads like a conversation.

**Committee voice.** Every edge filed down until nothing is distinctive. The result of multiple stakeholders each vetoing anything that could possibly offend anyone. Reads like it was written by a legal team with a thesaurus. This is what happens when a voice refuses to commit (Lumet) — hedging every position until the character disappears. A voice that tries to resonate with everyone resonates with no one.

**Fake warmth masking transactional intent.** "We're so excited to help you!" when the next line is a sales pitch. Readers detect this instantly. The mismatch between stated warmth and obvious agenda destroys trust faster than no warmth at all. Related: the voice must distinguish sincere appreciation from flattery (Carnegie). Sincere appreciation is specific, earned, and demonstrates real observation — "You built a six-figure business without a single paid ad" notices something true. Flattery is generic, transparent, and performative — "You're clearly a smart business owner" could be said to anyone and means nothing. Flattery is an anti-pattern: the reader knows it's unearned, and it signals that the voice is managing them rather than respecting them.

**Corporate wallpaper.** Specific reality "improved" into generic marketing language. The founder said "we help plumbers stop losing jobs because they forgot to follow up." Marketing made it "we empower service professionals to optimize their customer engagement pipeline." The voice should default to specific, vivid details over generalities (Collier). "We help coaches grow" is invisible — it creates no picture. "We helped Sarah go from $2,300 months to $10,847 months in 12 weeks" is vivid — the reader can see it. Specificity creates mental images, and mental images create belief. Mark generalities as an anti-pattern in the voice guide: if a sentence could describe any company in the category, it's a generality and needs to be replaced with a concrete detail, a number, or a name.

**Over-explaining.** Assumes the reader is confused instead of trusting them. Three sentences where one would do. Parenthetical clarifications that clarify nothing. The voice equivalent of explaining a joke.

**Naked exposition (Howard & Mabley).** The brand delivers information inside story and tension, never as preamble or naked explanation. "As you know, our platform processes 10,000 records..." is exposition wearing a thin disguise. The information should emerge from a scene, a tension, or a claim that earns the reader's forward motion. If the copy has to stop the narrative to explain how the product works, the narrative isn't doing its job.

**Pretension masquerading as expertise.** Using words the brand's customers would never use in conversation. "Synergistic alignment of stakeholder value" when the customer says "getting everyone on the same page." If the voice guide uses vocabulary the audience doesn't recognize, the voice is performing expertise rather than demonstrating it. The Feynman test: if you can't describe the brand's character in words a smart teenager would follow, you haven't understood the character — you've only memorized the jargon.

**Leaking what you don't intend.** Word choice, response patterns, and formatting communicate independently of content. Using "just" in pricing copy signals low confidence about value. An exclamation mark in a subject line from a brand that claims authority leaks uncertainty. A casual tone in error messages from a brand with warm marketing copy reveals two different communicators. These are expressions given off — accidental signals that contradict the intended voice and erode trust without anyone noticing why.

**Voice rules that can't be checked.** "Be authentic." "Sound human." "Keep it conversational." These can't be verified by anyone — writer, editor, or AI. "Sentences under 15 words average, no exclamation marks, second person, active voice" can be verified by anyone.

**Manager voice instead of leader voice (Godin).** Describes what exists instead of where we're going. Informs instead of challenges. Sounds like documentation instead of conviction. "Here's our product and what it does" is manager voice. "Here's what everyone gets wrong, and here's where we're going instead" is leader voice. Manager voice maintains; leader voice challenges. A brand that sounds like it's reporting information rather than leading a point of view builds audiences, not tribes.

**No archetype — defaulting to "helpful professional" (Greene: The Art of Seduction).** Most brands have no distinct personality because they haven't chosen one. Greene's nine seducer archetypes provide a framework: Siren (sensory appeal, escape from routine), Rake (intense focused attention), Ideal Lover (mirroring unmet needs), Dandy (defying norms), Natural (spontaneous, unpolished), Coquette (confident withdrawal), Charmer (making the reader feel exceptional), Charismatic (bold vision, conviction), Star (distance, aspiration). Choose one primary archetype. Blend a secondary for nuance. A SaaS brand might lead with Charismatic (bold category vision) and blend Natural (casual, no-jargon). The fatal mistake is trying to be all nine — which produces the "helpful professional" default that creates no fascination. "Helpful professional" is the absence of an archetype, not a choice.

**Anti-seducer patterns that repel (Greene).** Audit the voice for qualities that actively push people away: insecurity (excessive hedging, "we think maybe you might..."), self-absorption ("We're excited to announce..." — nobody cares about your excitement), impatience (hard selling in first touchpoint, rushing to CTA), clinginess ("Did you see my last email?", excessive follow-up), humorlessness (relentlessly earnest, devoid of wit), and lack of generosity (teaser-only content, paywalling everything). These are not just missed opportunities — they are voice patterns that create active distrust. The audience is not ignoring you because your offer is weak. They're ignoring you because the voice repels them.

**Voice that is correct but dead (Alexander).** A voice guide that checks every box — status defined, metaphors documented, register shifts specified — and produces output that feels performed rather than alive. The test is felt, not measured: does this voice feel like someone who understands you is talking to you, or does it feel like a template was filled in? Alive voice invites you in. Dead voice is structurally correct and emotionally inert. If the voice guide produces technically compliant copy that a reader can sense was generated from rules, the voice is dead.

**Voice disconnected from system (Alexander).** VOICE.md exists to ensure every copy-producing skill — offers, cold-outreach, email-flows, sales-pages, decks, content-engine — shares the same character. The voice guide is the connection layer. If the landing page sounds like one brand and the email sequence sounds like another, the connection was never established. Every asset produced by any skill that reads VOICE.md should feel like it was made by the same mind for the same person. Break the connection and assets drift into incoherence.

**Vendor signals in linguistic patterns (Baker: The Business of Expertise).** Specific phrases communicate vendor status regardless of intent. "We're happy to discuss..." / "We're always available..." / "We'd love to work with you..." / "Feel free to reach out anytime" — these are vendor signals. They communicate that demand does not exceed capacity, that you are one option among many, that the prospect holds all the leverage. Expert positioning uses constraint language: "We work with a small number of clients..." / "We're selective about fit..." / "We take on new projects quarterly." The voice guide should flag vendor signals as anti-patterns and specify constraint-language alternatives. A brand that positions itself as expert but speaks like a vendor has a voice that contradicts its positioning.

**Eagerness that undermines expertise (Baker: The Business of Expertise).** Exclamation marks, hedging phrases, and enthusiasm markers don't just signal uncertainty — they signal vendor status. "We're SO excited to announce..." / "We'd love to help!" / "Just wanted to follow up!" — these are eager phrases that position the brand below the audience. Expert voice is unhurried, declarative, and never breathless. The difference is subtle but visceral: "We've seen this pattern in 40+ companies" transfers authority. "We're really excited to share what we've learned!" transfers neediness. Audit the voice guide for any phrase that sounds like it's asking for permission or approval — these are eagerness leaks that erode the expert positioning the voice is meant to support.

**Register shifts that break wholeness (Alexander).** A voice that shifts register appropriately across contexts (tweet vs. legal disclaimer) is adaptive. A voice whose register shifts fight the system — warm in marketing, cold in onboarding, aggressive in sales, apologetic in support — lacks wholeness. Every register shift must serve the coherent whole. If one context's register contradicts the brand's core character, that's not a register shift — it's a voice that hasn't decided who it is.

**Voice flexibility across Rider and Elephant (Heath: Switch).** A voice that only speaks to the Rider (precise, logical, feature-focused) can't motivate the Elephant when needed. A voice that only speaks to the Elephant (emotional, aspirational, feeling-focused) can't direct the Rider when clarity is needed. The voice guide should enable register shifts: logical clarity for Rider moments (CTAs, instructions, next steps) and emotional resonance for Elephant moments (problem, transformation, belonging).

**Translating customer language into marketing language (Moesta: Demand-Side Sales 101).** When customers say "I was drowning in spreadsheets," the voice guide should note this exact phrase, not translate it to "users experience workflow friction." Customer language is more credible because it's real — readers recognize their own words and feel understood. Supply-Side voice ("Our platform enables seamless workflow optimization") speaks from the product world. Demand-Side voice ("You open your inbox to 47 unread messages and three fire drills before coffee") speaks from the customer's world. Default to demand-side framing — start in their world, not yours.

## When You Run This Skill

**Step 1 — Gather inputs.** Check three sources in order:

1. Read `.claude/BRIEF.md` if it exists. Pull the Voice section (tone, personality, style rules, Instead of / Say examples) as baseline. Also pull audience, product, and differentiation — voice should fit who you're talking to and what you stand for.

2. Check if `.claude/VOICE.md` already exists. If it does, this is an update — preserve what works, improve what's weak. Don't start from scratch.

3. Check for writing samples. The user may provide existing copy directly. Also scan the codebase for marketing copy: landing pages, README, emails, onboarding flows, in-app text, social posts, ad copy. If the product has written anything public-facing, it already has a voice — even if nobody documented it.

**Step 2 — Analyze or ask.** If you have writing samples or BRIEF.md, use the Voice Analysis Framework (Principle 1) to draft the VOICE.md. Draft-and-correct beats interviewing — give the user something to react to.

If you have neither BRIEF.md nor writing samples, run the intake questions (below) to establish a baseline before drafting.

**Step 3 — Draft.** Build the full VOICE.md through the principles below. Use the output format at the end of this skill.

**Step 4 — Deliver.** Write to `.claude/VOICE.md`. Run the quality check before saving.

## Intake Questions

Use these only when no BRIEF.md and no writing samples exist. These establish enough baseline to draft a first pass the user can correct.

- What does your brand/product do? (one sentence)
- Who are you talking to? (their role, sophistication level, what they care about)
- If your brand were a person at a dinner party, how would guests describe them after they left?
- Name a brand whose voice you admire — what specifically do you like about how they sound?
- Name a brand whose voice makes you cringe — what specifically bothers you?
- What do you never want to sound like? (quote specific phrases or describe the feeling)
- Share 2-3 real pieces of copy you've written that feel "right." (paste text, link to pages, or point to files in the codebase)

Don't dump all questions at once. Start with the dinner party question — it reveals character faster than anything else. Follow up based on what they give you.

## Principles

### 1. Voice Analysis Framework

Before writing rules, analyze what exists. Three input sources, in order of richness:

**Writing samples** (richest source): Existing landing page copy, emails, social posts, in-app text, README, onboarding flows. Analyze for:
- Sentence length patterns (short and punchy? Long and flowing? Mixed?)
- Status signals (hedging language, declarative statements, seeking approval, comfortable assertions)
- Metaphor systems (what conceptual frames appear? War, journey, building, growth, craft?)
- Vocabulary frequency (which words recur? Which industry terms are used or avoided?)
- Personality markers (humor, directness, warmth, edge, patience, urgency)
- Formality level (contractions, slang, technical precision, conversational asides)

**Four-dimension voice mapping (Garfinkel).** Beyond surface style, define how the brand expresses across four dimensions: *logical* (how it structures arguments and presents evidence), *emotional* (how it names feelings and builds tension), *sensory* (how it paints scenes with specific, visceral detail), and *identity* (how it frames who the reader becomes). Most voice guides only capture logical and emotional. Adding sensory and identity dimensions means the difference between "our tool saves time" (logical only) and "picture closing your laptop at 5pm with an empty inbox — that's who you become" (all four). For each voice, document its characteristic move in each dimension. Specify the sequencing across dimensions — emotional and identity dimensions must be established in the first pass of any communication before logical structure or sensory detail are added, because a reader who hasn't felt something from the voice won't engage with what it's saying (Camp).

Notice the specific recurring choices, not the general impression. The writer who always uses short first sentences, who reaches for construction metaphors, who avoids exclamation marks, who opens emails with a question — the voice lives in those particular patterns, not in a summary like "professional" or "casual." Two brands can both be "casual" and sound nothing alike. The specifics are the voice.

The voice already exists in practice. Your job is to name it, not invent it.

**BRIEF.md voice section** (stated intent): Tone, personality, style rules, examples. This captures what the brand wants to sound like. It may or may not match how they actually sound.

**Product/codebase context** (accidental voice): README, marketing pages, error messages, onboarding text. If the product has copy, it already has a voice — the question is whether that voice was chosen or defaulted.

**Reception test (Luntz):** Voice isn't what you intend to sound like — it's what the audience *hears* you sounding like. After drafting the character sketch and style rules, test every key phrase by asking "what did they hear?" not "is this clear?" A brand that intends "confident" but lands as "arrogant" has a reception gap, not a clarity problem. Build reception testing into the analysis: read the voice back as the target audience, not as the brand team.

**When sources conflict:** If samples and stated intent disagree (e.g., BRIEF.md says "conversational" but existing copy is formal and corporate), flag the gap. Ask: "Your brief says conversational, but your existing copy reads formal. Which direction is the target?" Don't silently average them. The conflict itself is useful — it means the voice isn't settled yet.

**Name the dominant voice before defining the brand's.** Before writing any rules, identify what every competitor in the space sounds like — the tone they all use, the phrases they all reach for, the register they default to. That's the dominant pattern. The most distinctive voice rules are often the direct inversions of industry defaults. If every competitor sounds warm and approachable, this brand might differentiate through precision and edge. If every competitor leads with authority, this brand might differentiate through candor and irreverence. Don't just avoid the bad — design the opposite of the expected.

**Scratch beyond the brand.** Don't build a voice guide in a vacuum of the brand's own copy. Before drafting, study 3-5 brands outside the industry that the target audience admires — how do those brands sound? What tonal qualities carry across domains? Cross-industry scratching produces voice options that same-industry analysis cannot.

### 2. Brand as Character

A brand voice is not a list of adjectives. It's a character. A character has a way of seeing the world, consistent reactions to situations, topics they care about, things they'd never say, and a recognizable rhythm.

Write a character sketch, not a tone description:

"A direct, technically sharp friend who explains complex things simply, gets frustrated with jargon, and would rather show you a working example than write a paragraph about it. Talks fast. Cuts to the point. Gets visibly annoyed at hand-wavy marketing speak. Respects your time by respecting your intelligence."

That's a character. You can hear how they'd write an email. You can predict what they'd cut from a landing page.

"Professional, friendly, approachable" is a blank wall. Three writers reading those adjectives would produce three completely different voices.

**Use brand archetypes as optional scaffolding.** Pearson's archetypes can jumpstart the character sketch: Innocent brands sound optimistic and simple, Warrior brands sound competitive and achievement-oriented, Magician brands sound visionary and transformative. Start with an archetype if it fits — then make it specific to this brand through details, contradictions, and rough edges. The archetype is a template, not the character itself.

**Psychic anchor (Bachelard).** Name the voice's home state — the register it returns to when context is neutral, when the brand isn't selling or teaching or entertaining. Every context variation should be readable as a departure from and return to that home, not a separate mode.

**The emotional truth test:** The character must come from who the founders actually are — including their contradictions and rough edges — not from persona research conducted without founder interviews. A voice guide built from market positioning and competitor analysis without real founder input produces a character nobody can sustain. The voice sounds right on paper but wrong out loud because it was never anyone's actual voice. If the character sketch describes someone the founding team wouldn't recognize as themselves, it's a costume, not a character. The voice guide should include the brand's Epiphany Bridge (Brunson): the founder's backstory, the wall they hit, the epiphany that changed their understanding, the plan that followed, and the result that proved it worked. This is the origin story that gets retold across channels — in the founder bio, the about page, the webinar intro, the podcast interview. Without this structure, founder stories become résumés: a list of credentials and milestones that inform but don't transform. The Epiphany Bridge gives the character an emotional origin, not just a professional one, and it gives every copy-producing skill a narrative spine to reference when the founder's voice needs to show up. But the Epiphany Bridge is just the origin story. The full character needs four elements that Brunson calls the Attractive Character: the backstory (the origin that creates identification — not credentials, but the struggle the audience recognizes as their own), parables (teaching stories drawn from real life that the voice returns to across channels — these are the brand's reincorporation material), character flaws (admitted imperfections that build trust — distinct from the brand flaw below, these are personal to the founder: impatience, obsessiveness, a bias toward action over planning), and polarity (strong positions that repel some people and attract others harder — the heretical position expressed as consistent behavior, not a one-time stance). Without these four elements, the voice doc produces "brand voice" — consistent but characterless. Tone without a person behind it. With them, every skill downstream writes as a real person the audience connects with, not a company performing personality. The Attractive Character is what turns a voice guide from a style sheet into a relationship blueprint. Document all four elements in the character sketch: the backstory the audience identifies with, 2-3 signature parables the brand retells, the flaws it openly admits, and the polarizing positions it refuses to soften. The voice doc should also capture the founder's real mistakes and failures as a trust register — specific, detailed vulnerability that every copy-producing skill can access (Carnegie). "I closed my laptop and stared at the ceiling for 20 minutes because my best client just fired me" is a voice register. "We've learned a lot along the way" is corporate filler. Flag the anti-pattern: "I'll be honest with you..." followed by a curated admission is theater, not vulnerability — the audience recognizes the performance because genuine honesty doesn't need a preface.

**First-take energy (Caine).** A voice that sounds over-polished loses the quality of genuine thought. The best screen performances have first-take energy — the actor thinking in real time, discovering the line as they say it, not reciting something rehearsed. The written equivalent is prose where the thinking is visible: the sentence that builds toward its conclusion instead of announcing it, the aside that feels spontaneous, the rhythm that sounds like someone working through an idea rather than presenting a finished one. Third-revision smoothness — where every edge is sanded, every transition is seamless, every paragraph reads like it was committee-approved — kills this quality. The reader can feel the difference between a voice that's thinking and a voice that's performing having thought. First-take energy doesn't mean sloppy or unedited. It means the final version preserves the directness and roughness of genuine expression. When the voice guide produces copy that sounds too polished, too perfect, too "written," ask whether the first draft was more alive — and whether the editing killed what made it real.

**Ugly-first character drafting (Sullivan).** Write the character sketch in 10 minutes without editing. Raw, specific, contradictory. What this person believes, what they'd never say, what frustrates them. THEN edit for clarity. First-draft urgency prevents committee voice — the polished, edge-filed, offend-nobody result of editing before the character exists. The ugly draft captures the rough edges that make a voice real; the revision shapes them without sanding them off. If the first draft is careful, the final draft is dead.

**The specificity test:** Two different writers reading the character sketch should produce recognizably similar copy. If the guide could describe any brand in the industry, it's too generic. Push until the character is specific enough that it could only be this brand.

**Subtext carried by performer, not script (Weston).** Voice guides should give writers enough direction to carry the right subtext without scripting every word. "We speak as a sharper peer who's three steps ahead, not as a teacher explaining basics" tells the writer what to play underneath — their words can vary while the subtext stays consistent. Over-scripting kills voice. The more precisely you dictate exact phrases, the less room the writer has to bring authentic intention underneath. A voice guide that scripts every sentence produces copy that sounds read, not spoken. A voice guide that defines the subtext — what the brand is always doing beneath the words — produces copy where any words the writer chooses sound like the same person. The test: could a writer follow this guide and produce copy that sounds right in words you didn't anticipate? If the guide only works when writers use the exact phrases provided, it's a script, not a voice.

**Three-layer voice test (McKee: Dialogue).** After writing voice copy, ask three questions: What does this *say*? (The explicit message.) What does this *imply*? (The subtext the reader infers through tone, rhythm, and specificity.) What does this *touch* that the reader cannot name? (The deeper emotional resonance.) If the third answer is "nothing," the voice is operating on one layer only. A voice that operates on all three layers bonds — a voice that operates on one informs. The three-layer test applies after drafting, not during: write naturally, then audit each layer.

**Subtext as voice depth (Mackendrick).** A voice that operates on one level — surface meaning only — engages the reader's comprehension but not their social cognition. A voice that carries subtext engages both. The founder who tells the story of their biggest failure is teaching on the surface and establishing credibility underneath, without ever claiming credibility directly. The newsletter that opens with a specific observation about the reader's Tuesday morning is offering insight on the surface and demonstrating intimacy with the reader's world underneath. This dual-layer voice is what separates brands that inform from brands that bond. The subtext layer is where trust, authority, and belonging are built — not through claims but through what the reader infers from how the voice behaves. Document the brand's characteristic subtext moves: what is the voice always doing underneath the words? "Surface: teaches frameworks. Subtext: positions the brand as the person who's already solved what you're struggling with." "Surface: admits a mistake. Subtext: demonstrates the self-awareness that only comes from real experience." If the voice guide only defines what the brand says — and not what the reader should feel beneath what the brand says — the voice is flat, no matter how well the surface style is calibrated.

**The reincorporation test** (Johnstone): A distinctive voice plants specific details, phrases, or framings and brings them back. A brand that calls everything "sharp" in one place should call things "sharp" everywhere, not switch to "excellent" or "quality." If the character sketch doesn't suggest recurring motifs or signature moves — a word they overuse, a type of example they always reach for, a structure they default to — it's still too abstract. Luntz's consistency research reinforces this: identical repetition of chosen terms builds belief. Synonym-rotation — swapping "sharp" for "precise" for "excellent" across channels — feels like editorial polish but actually destroys memorability. The voice guide should name the brand's signature terms and mandate that they appear identically everywhere, never paraphrased for variety.

**The credibility test** (Aristotle): The character sketch should answer three questions about how the brand demonstrates ethos — not by claiming it, but by showing it. How does this brand demonstrate *phronesis* (expertise through specificity, not credentials)? A brand that says "we've been in business 20 years" is claiming expertise. A brand that names the exact problem you're having before you describe it is demonstrating it. How does it demonstrate *arete* (honesty through limitations acknowledged, not perfection claimed)? How does it demonstrate *eunoia* (audience-centered care through framing, not stated concern)? These three together are what makes the character credible.

**USP-voice alignment (Abraham).** A voice that doesn't express the brand's strategic difference is a voice any competitor could wear. If the brand's USP is speed, the voice should be fast — short sentences, no preamble, impatient with filler. If the USP is depth, the voice should demonstrate depth — layered analysis, references, willingness to go long when the material demands it. If the USP is simplicity, the voice should be radically clear — no jargon, no complexity, ruthless editing. The test: read the voice guide with the brand name removed. Could a direct competitor adopt this voice without changing their product? If yes, the voice is generic — it describes a category tone, not a brand character. The USP should be audible in how the brand sounds, not just visible in what the brand claims.

**The cross-domain analogy.** When developing the character sketch, reach outside business archetypes. Instead of describing the brand as "professional and direct," describe it as "a documentary narrator who respects the subject too much to hype it" or "a dive bar bartender who gives real advice, not the answer you want to hear" or "a late-night radio host who talks to one person, not an audience." The analogy produces a more vivid, more actionable character than adjectives ever can.

**Voice tension through blending opposites (Aftel).** The most memorable voices pair unexpected combinations — sharp citrus with deep amber, warmth with authority, casual with expert, vulnerable with bold. A single-note voice is flat, no matter how well-executed. Find the unexpected pairing: conversational + authoritative, playful + substantive, direct + empathetic, irreverent + knowledgeable. The tension between the two notes is what makes the voice interesting. A voice that's only warm is generic. A voice that's warm + brutally honest is distinctive. Document the brand's voice tension in the character sketch: "We pair [quality A] with [quality B] — most brands in our space are one or the other."

**Blind paragraph test (McKee: Dialogue).** The voice should be distinctive enough that someone could identify the brand from a paragraph with the name removed. If not, the voice is generic. Test by reading voice samples from the brand alongside competitors — if they're interchangeable, the fingerprint isn't working. Specific fingerprint mechanics to audit: vocabulary choices, sentence length range, register default, what the voice notices, and what it never says. A voice that passes the blind test has character. A voice that fails it has style without identity.

**Silence as voice element (McKee: Dialogue).** Define what the brand voice does NOT say — topics it avoids, claims it refuses to make, registers it never enters. These silences are as defining as the words chosen. A brand that never hedges signals confidence through what it omits. A brand that never uses superlatives signals substance through restraint. Document the brand's characteristic silences in the voice guide alongside the vocabulary: "We never say..." is as important as "We always say..."

**Authenticity has texture, not synthetic smoothness (Aftel).** Natural essential oils have complexity — hundreds of compounds creating depth and imperfection. Synthetic fragrances are smooth but flat. The same principle applies to brand voice. A voice with quirks, opinions, rough edges, and inconsistencies feels real. A voice polished to corporate perfection feels manufactured — the reader can tell something is off even if they can't name it. Let the voice have texture: a recurring phrase that's slightly awkward, an opinion that's unfashionable, a perspective that doesn't fit the category norms. The rough edges are what make it feel like a person wrote it, not a brand committee. When the voice guide produces copy that sounds too smooth — no rough edges, no surprising opinions, no texture — it's synthetic voice, not natural voice.

**Creative DNA.** Name the brand's recurring themes, instinctive angles, and consistent blind spots. If the brand always leads with logic, name the gap in emotional range. If the brand always uses war metaphors, name the domains it never enters. If the brand defaults to long, complex sentences, name the situations where that pattern fails. Creative DNA is a starting point — leverage strengths, address gaps deliberately rather than accidentally.

**The brand flaw.** Every compelling brand voice has an acknowledged incompleteness — a bias, a limitation, a tension it hasn't fully resolved. This is what makes the voice human rather than corporate. A brand that claims to do everything well sounds like marketing. A brand that says "We're obsessed with simplicity to the point where we sometimes ship too little" sounds like a character with a real perspective. The flaw should be genuine — something the audience can see for themselves, not a humble-brag disguised as a limitation. "We move fast, which means we sometimes break things" is a flaw. "We care too much about our customers" is not. Define the brand flaw in the voice guide alongside the character sketch. It anchors the character in reality and gives the voice permission to be honest about tradeoffs, which builds more trust than any perfection claim ever could.

**The heretical position (Godin).** Name what this voice believes that the mainstream rejects. A voice without a contrarian stance is a voice without direction — it can inform, but it can't lead. The heretical position is the belief that makes followers feel like insiders who know something others don't. "Most marketing advice optimizes for reach when it should optimize for depth" is a heretical stance. "Marketing tips" is not. If the character sketch doesn't include what the brand is against — the assumption everyone makes that this brand rejects — it's describing a broadcaster, not a leader.

**Point of view about everything (Lumet).** The heretical position gives the voice one sharp stance. But a voice built on a single contrarian take surrounded by generic opinions is a one-trick character. The voice should have a point of view about every topic it touches — not just the brand's core domain, but the adjacent areas the audience cares about. A project management tool with a sharp take on productivity but generic opinions on remote work, hiring, and team culture sounds distinctive in one corner and invisible everywhere else. The generic areas undermine the distinctive ones because the audience starts to suspect the sharp take was marketing, not character. You don't need to be contrarian about everything. You need to have actually thought about everything. A considered, specific opinion — even a conventional one stated with precision — reads differently than a default. "We think remote work is the future" is a default. "Remote work rewards writers and punishes talkers, which is why our tool is built for async" is a point of view. Audit the voice guide for any topic where the brand's stance is interchangeable with every competitor's stance. Those are the gaps where the character goes flat.

**"Very good" language (Godin).** Comprehensive, robust, seamless, cutting-edge, best-in-class, world-class, end-to-end. These words describe adequacy, not remarkability. They are the four-star-hotel register of language — professional, polished, and completely invisible. Add these to the word avoidance list or mark explicitly for audit. A voice that uses these words sounds like every other brand in the category.

**The safety test (Godin).** If the voice feels safe — acceptable to everyone, offensive to no one — it's probably invisible. Safe is the most dangerous strategy. Push until the voice would make someone disagree. If nobody would push back on how this brand sounds, it's wallpaper, not a voice.

**Commit to the voice (Lumet).** A voice that qualifies its own positions, hedges its claims, or softens its character reads as having no character at all. Commitment is not volume or aggression — it's the refusal to water down the voice for comfort. A brand that's irreverent in its blog but polished in its emails hasn't chosen a voice; it's performing one when it's convenient. A brand that claims directness but adds "we think" and "in our experience" before every claim is hedging its own identity. Bold wrong beats timid right. A fully committed voice that's slightly off-target is more compelling than a perfectly calibrated voice that never takes a risk. The voice guide should name what the brand commits to — and what it accepts losing by committing. Every strong voice repels someone. If the guide doesn't name who this voice isn't for, the commitment isn't real.

**Worldview alignment (Godin).** The voice should sound like someone who shares the audience's worldview. If the audience believes "big companies are bloated and slow," the voice should sound lean and direct — not corporate and polished. If the audience believes "most advice is shallow clickbait," the voice should sound deep and specific — not punchy and surface-level. The character sketch isn't just who the brand is; it's who the audience already believes they should be listening to. A voice that contradicts the audience's worldview gets rejected before the content is evaluated — not because it's wrong, but because it doesn't sound like "one of us."

**Inside voice (Bachelard).** The test for voice alignment isn't "does this sound like our audience?" but "does this sound like it's coming from inside their world?" A voice from an external observer's position reads as empathy. A voice from inside — using their cadences, ironies, specific frustrations — reads as belonging.

**Voice as expectation architecture (Ariely).** The emotional register is not only a persuasion instrument — it sets expectations that shape actual user experience. A voice that promises confidence, competence, and warmth in marketing copy must maintain that register in product copy: error messages, empty states, renewal reminders, cancellation flows. When the marketing voice is warm and the error message is cold, the user experiences the product as worse than it objectively is — because the expectation set by the voice made the gap feel like a betrayal. The voice guide should explicitly extend its register rules to transactional and edge-case copy, not just acquisition copy. A brand that sounds like a trusted advisor on the landing page and sounds like an automated system in the billing email has two voices, and the second one undermines the first.

**Brands are goal-signal systems, not personalities (Barden).** The brain processes brands as physical objects — bundles of associations (visual signals, contextual frames, goal associations) — not as people with personality traits. 'Our brand is innovative, friendly, and bold' is pilot-language the autopilot cannot process. 'Our brand signals autonomy through angular design, bold typography, and direct language' is operational — it specifies signals the autopilot recognizes. When building a voice guide, define what goal the brand serves (which of the six implicit goals) and what signals encode it (language patterns, visual cues, tonal register), not what personality it would have at a dinner party. The goal-signal definition produces consistent execution because signals can be implemented. Personality adjectives produce inconsistent execution because everyone interprets them differently.

### 3. Status Choice

Every piece of copy plays a status. Most brands do this unconsciously, creating mixed signals that readers feel but can't name.

**High-status markers:** Short sentences. Declarative statements. No hedge words. Comfortable with silence (white space). Confident framing ("Here's how it works" not "We'd like to show you how it might work"). Doesn't ask permission. Doesn't over-explain. High-status is structural, not just tonal — the sentence itself is short, declarative, and commits to every word. A brand that hedges in the subordinate clause ("which could potentially help") while declaring in the main clause is leaking low-status through its syntax.

**Stillness as voice power (Caine).** The most commanding thing a voice can do is stand still. A sentence alone on the page, surrounded by white space, no intensifiers, no exclamation marks — that's the written equivalent of screen presence. Stillness reads as confidence because it doesn't need to shout, gesture, or amplify. A voice that piles on modifiers ("incredibly powerful," "absolutely essential," "truly game-changing") is fidgeting — filling silence because it doesn't trust the statement to land on its own. The fix is structural: strip the sentence to its claim, give it room, and let it breathe. "We cut churn by 40%." Period. White space. The reader feels the weight because nothing around it is competing for attention. Stillness is the highest-status move a voice can make — it signals that the brand is comfortable enough with what it's saying to say it once, plainly, and move on.

**Low-status markers:** Qualifying language ("We believe," "might," "could," "perhaps"). Seeking approval ("We'd love to hear your thoughts!"). Over-explaining. Excessive exclamation marks. Apologetic framing ("Sorry for the inconvenience"). Hedged claims ("We think this could potentially help"). Low-status shows up in sentence structure before it shows up in word choice — the over-long sentence that keeps adding clauses is a speaker who won't stop talking because they're afraid silence means rejection.

**Permission-seeking is not humility (Godin).** Phrases like "I think maybe," "you might consider," and "it could be argued" feel like hedging for politeness, but they're actually abdication. A brand that constantly seeks permission to have a perspective isn't leading anywhere. Cut permission-seeking phrases unless humility is the deliberate, justified choice. "Here's what I believe" is leadership. "I think maybe we could consider" is asking the audience's permission to exist.

Neither is wrong. High-status builds authority and trust for premium products. Low-status builds accessibility and approachability for community-driven or support-heavy products. The choice must be deliberate and consistent.

**Status-role calibration (Godin).** Diagnose whether the brand plays a dominion game or an affiliation game. Dominion voice is authoritative, exclusive, hierarchical — "we set the standard." Affiliation voice is warm, inclusive, communal — "we're in this together." Mixing them creates dissonance. A brand that says "join our exclusive community where everyone belongs" is playing both games at once and winning neither. The dominion/affiliation axis cuts deeper than high-status/low-status because it shapes not just how confident the voice sounds but what relationship it's offering the audience. A dominion brand can be warm (mentorship), and an affiliation brand can be confident (movement leadership), but the underlying game must be consistent. Name it in the voice guide: "This brand plays a [dominion/affiliation] game" — then audit every status choice against it.

**Vendor voice vs. advisor voice (Abraham).** Preeminence is a voice dimension, not a strategy layer. A vendor voice is defensive, promotional, self-referential — it talks about the product, justifies the price, and treats every interaction as a conversion opportunity. An advisor voice is generous, authoritative, and willing to recommend alternatives — it talks about the reader's problem, offers genuine counsel, and sounds the same whether or not there's something to sell. Most brand voices default to vendor without realizing it. The tell: remove the product mention from any paragraph. If the voice collapses — if the warmth, specificity, and authority disappear — it was vendor voice wearing an advisor costume. Advisor voice holds up with no product on the page because the posture is "I'm here to help you make the best decision" not "I'm here to help you make this decision." Document where on the vendor-advisor axis this brand sits, and audit voice samples for vendor drift — the tendency to slide toward promotional language in any context where a sale is possible.

**Vertical status (Bachelard).** Status isn't only horizontal (peer vs. authority) — it's also directional. Name when the voice looks up (asks rather than prescribes) and when it looks down (prescribes, corrects, leads). The mismatch between directional register and situation creates condescension or false modesty.

**Mixed status is the most common failure.** Confident in the headline, hedging in the body. Declarative in the ad, apologetic in the email. This isn't "range" — it's incoherence. The reader gets two different signals about who's talking to them and stops trusting either one.

A brand voice that shows occasional uncertainty, acknowledges complexity, or asks genuine questions in its copy — "we're not sure this is right for everyone — here's how to find out" — paradoxically reads as more confident than one that projects certainty at every turn, because it signals security rather than defensiveness (Camp).

**Certainty transfer (Belfort).** The writer's emotional state transfers to the reader through word choice as a mechanical cause-and-effect. Qualifiers ("might," "could," "potentially," "we believe," "it's possible that") are not just low-status markers, they are uncertainty transmitters. Each qualifier injects doubt into the reader's mental model of the product, the person, and the company. This is not a style preference. A sentence with two qualifiers communicates less certainty than the same sentence with zero, regardless of the factual content. The fix is structural: delete the qualifier and let the statement stand. "This will save you 10 hours a week" transfers certainty. "This could potentially save you up to 10 hours a week" transfers doubt. When reviewing copy for voice consistency, run a qualifier audit as a separate pass. Every qualifier is a certainty leak, treat it like a status leak and patch it.

Document the primary status choice and what it looks like in practice: "This brand plays medium-high status. Confident statements, no hedging, but uses 'you' more than 'we.' Doesn't seek approval. Comfortable making direct claims backed by proof. Never apologizes for pricing."

**Role distance.** High-competence brands earn the right to be irreverent about their own category. A security company that jokes about password hygiene signals mastery — they're so confident in the domain they can be casual about it. This is role distance: the ability to step outside the expected seriousness of your role. Document when the brand is allowed to use role distance (after establishing competence, in informal contexts, on social media) and when it isn't (first contact with enterprise prospects, in product during critical flows). Role distance without established credibility reads as flippant, not masterful.

### 4. The Three Pillars

Every voice expresses some combination of Presence, Power, and Warmth. The ratio determines the charisma style:

**Authority** (power-dominant): Confidence, expertise, proof. "Here's what the data shows." Short, declarative. Signals: I know the answer. Works for: tools, platforms, B2B, anything where expertise is the value prop.

**Visionary** (power + warmth): Inspiring about the future. "Imagine what happens when..." Expansive, forward-looking. Signals: I see where this is going. Works for: category creators, movement brands, founders building something new.

**Kindness** (warmth-dominant): Deep understanding and acceptance. "We've been exactly where you are." Empathetic, patient. Signals: I understand your situation. Works for: health, coaching, support-heavy, community products.

**Focus** (presence-dominant): Attentive, specific, mirror-like. "You mentioned X — here's exactly how that works." Precise, personalized. Signals: I'm paying attention to you specifically. Works for: consulting, personalized services, concierge products.

Most brands blend two styles. Document the primary and the supporting one.

**Claude defaults to Visionary charisma.** If the brand needs Authority or Focus, this must be explicitly stated in VOICE.md or Claude will default to expansive, future-oriented, "imagine the possibilities" language. This is the single most common voice failure in AI-generated copy — everything sounds like a TED talk.

### 5. Metaphor System

Every brand operates within a conceptual metaphor framework, usually unconsciously. The metaphors shape what feels natural to say and what feels off-brand.

**Common business metaphor systems:**
- BUSINESS IS WAR — attack, defend, capture market share, target, campaign, conquer
- BUSINESS IS A JOURNEY — roadmap, milestones, destination, compass, navigate, path
- BUSINESS IS BUILDING — foundation, architecture, framework, blueprint, construct
- BUSINESS IS GROWTH — plant, nurture, cultivate, harvest, seed, fertile, bloom
- BUSINESS IS CRAFT — shape, refine, polish, tool, artisan, handmade, forge

Each system highlights and hides. WAR highlights competition but hides collaboration. JOURNEY highlights progress but hides that the destination might be wrong. BUILDING highlights structure but hides organic adaptation. GROWTH highlights patience but hides active effort.

**The metaphor system is the brand's unspoken worldview.** The metaphors communicate values the brand never has to claim. Building metaphors ("foundation," "architecture," "framework") silently communicate stability and structure. Journey metaphors ("roadmap," "milestone," "path") communicate progress and motion. The metaphor family carries brand values that are felt, not read — choose the system for what it implies, not just what it describes. The audience absorbs the worldview through the frame, not the argument. This is symbolic subtext (Seger) at the brand level — choose the system deliberately, because it's doing persuasion work whether you designed it to or not.

**Document the primary metaphor system.** Name what it highlights and what it hides. Check for coherence — mixing JOURNEY and WAR metaphors ("marching toward our roadmap milestone") creates cognitive friction readers feel but can't articulate. If you find mixed metaphors in existing copy, pick one system and commit.

**Dead metaphor audit:** Identify the invisible metaphors in existing copy. "Drive growth," "unlock potential," "fuel revenue," "leverage insights," "double down," "move the needle" — these are dead metaphors carrying conceptual weight nobody chose. They make copy feel generic precisely because they're generic. Replace with conscious alternatives from the brand's chosen framework, or with literal language that says what you actually mean. Before choosing your metaphor family, name the three dead metaphors every competitor uses in this category (Sullivan). Growth = journey, business = war, success = climbing — these are invisible precisely because they're universal. Name what metaphors your competitors all use, then deliberately choose a different system. The category's dominant metaphors are the ones nobody notices, which is exactly why they flatten every voice that uses them.

**Rhetorical devices as voice tools.** Beyond the conceptual metaphor framework, name the specific rhetorical devices this voice uses — these are the mechanics of style, not just the conceptual frame:

- **Antithesis:** Setting two ideas against each other for contrast and memorability. "Not a cost. An investment." "Others chase followers. You close deals." Some brands use antithesis constantly (punchy, opinionated voices); others never do (warm, flowing voices). Document whether this brand reaches for it.
- **Energeia:** Vivid scenes over abstractions. "Picture opening your laptop Monday morning to a full pipeline" versus "Improve your lead generation results." Brands that use energeia paint mental movies; brands that avoid it stay precise and analytical.
- **Rule of three (Vorhaus):** Two items establish a pattern, the third breaks it. "Write better. Ship faster. Stop overthinking every sentence." The first two set the rhythm; the third delivers the insight or edge. Some brands use pattern-then-break as a consistent voice signature — it creates a recognizable cadence readers feel but can't name. Others never use it. Document this explicitly.
- **Rhythm:** Short sentences for authority. Long sentences for context and nuance. Alternating between both for momentum. The rhythm pattern is as distinctive as vocabulary — a brand that writes in staccato bursts sounds nothing like one that builds long, layered sentences even when they're saying the same thing. Conversational rhythm is not optional — it's the difference between a voice that holds attention and one that puts people to sleep (Collier). Vary sentence length deliberately. Alternate questions with statements. Use fragments for emphasis. Then a longer sentence that builds. Monotone kills trust even when the words are warm — and every sentence the same length is monotone even if the words change. Read every voice sample aloud; if it sounds like a document being read instead of a person talking, the rhythm is dead.

- **Tempo variation (Mackendrick).** Uniform sentence length and structure is the written equivalent of a metronome — technically keeping time but producing no feeling. The reader's nervous system tracks tempo changes, not tempo itself. A passage of long, exploratory sentences that suddenly lands on a short declarative punch — the reader feels that shift physically, the way an audience feels a cut from a wide shot to a close-up. Short sentences between longer ones create emphasis through contrast, not through volume. The variation itself is the signal: this voice is alive, it's modulating, it's making choices about when to slow down and when to hit. A voice with no tempo variation reads as automated even when the content is personal. Document the brand's tempo pattern as a rhythm signature: does it build long then punch short? Does it open with a fragment and expand? Does it hold a steady middle length and break the pattern only for emphasis? The pattern should be nameable and repeatable. If the voice guide specifies sentence length ranges but not the tempo pattern — the characteristic way those lengths alternate — it's constraining the metronome instead of teaching the musician.

- **Tension/release rhythm (O'Bannon).** A strong voice alternates between tension moves (challenge, provocation, hard truth) and release moves (warmth, humor, empathy). Voices that are relentlessly intense or relentlessly pleasant are structurally flat — they have no rhythm because they have no contrast. The ratio between tension and release defines the brand's character: a brand that runs 70/30 tension-to-release sounds very different from one that runs 30/70, even if they share the same vocabulary and status level. Document the brand's tension/release ratio and name its characteristic tension moves and release moves.

- **Sound/texture (Luntz):** Words have phonetic character independent of meaning. Plosives (b, d, g, k, p, t) create punch and decisiveness — they stop the mouth and hit the ear. Sibilants (s, sh, soft c) create smoothness and flow. A brand voice should specify its phonetic character: does it prefer hard-consonant words that land with authority, or softer words that glide? "Cut the waste" and "streamline inefficiencies" mean the same thing but sound completely different in the mouth. Document whether the voice favors phonetic punch or phonetic flow, and audit key phrases — taglines, headlines, signature phrases — for mouth-feel. Word texture is processed as timbre — the brain's auditory system evaluates subvocalized words the way it evaluates instrument timbres (Levitin). A voice built on hard consonant clusters (crack, strip, break, grip) has a fundamentally different neurological texture than one built on open vowels and soft consonants (flow, ease, open, gentle). These aren't style preferences — they're different instruments playing the same notes. Define the voice's timbral range: what sonic texture does this brand occupy?

Name which devices belong to this voice and which don't. A brand that never uses antithesis but always uses energeia has a different texture than one that lives on antithesis and avoids scene-setting. These choices are checkable and teachable — they're how the voice actually works on the page.

### 6. Style Rules That Can Be Checked

Voice rules must be verifiable. "Be authentic" can't be checked by a writer, an editor, or an AI. "Sentences under 20 words average, no exclamation marks, second person, active voice" can be checked by anyone.

Cognitive ease is a non-negotiable voice principle, not a style preference (Kahneman). Simple sentences feel more true. Familiar words feel more trustworthy. Readable prose feels more honest. Complexity is not authority — it's friction that triggers System 2 suspicion. The fluency test applies to every voice sample: read it aloud, and every stumble means the reader's trust dipped. Repeated phrases and consistent vocabulary build the mere exposure effect — familiarity that compounds into trust over time. A brand that rotates synonyms for variety is actively destroying the cognitive ease that repetition builds. The voice guide should establish Halbert's 8th-grade rule as a non-negotiable default: short words over long words, short sentences over long sentences, active voice over passive, conversational over formal. Not because the audience is unsophisticated — because everyone prefers clear writing. Complexity is a barrier. Simplicity is a bridge. Mark sophistication and hedging as anti-patterns.

**Uninflected voice as default (Mamet).** The most authoritative voices present facts without emotional editorializing. "We reduced churn by 40%" is uninflected and powerful. "We're thrilled to announce an amazing 40% reduction in churn!" is inflected and weak. Inflection — added excitement, wonder, pride — is the writer telling the reader how to feel instead of trusting the fact to land. Guide every voice toward uninflected confidence as the baseline; inflection should be a deliberate exception, not the default register.

**Rules to specify:**

- **Word-level simplicity (Luntz):** Small words land harder than big ones. "Use" beats "utilize." "Help" beats "facilitate." "Fix" beats "remediate." Luntz's retention research shows that every additional syllable reduces recall. Document the brand's syllable ceiling — most voices should cap at two syllables for key terms unless technical precision demands otherwise. Audit signature phrases and taglines for syllable count; if it takes two breaths to say, it won't get repeated.
- **Consistency with variation (Levitin):** Consistency without variation becomes wallpaper. The brain classifies exact repetition and stops attending to it. Repeat signature phrases and structures, but vary the execution each time — same rhythm, different words; same metaphor family, different specific image; same sentence cadence, different payload. The brain rewards recognizing the familiar pattern AND discovering the novel variation. A tagline repeated identically across every touchpoint is noise by the tenth exposure. The same tagline's rhythm echoed with different words in different contexts stays alive.
- **Sentence length:** Average range and maximum. Short average (8-12 words) = punchy, urgent. Medium (12-18) = conversational. Long (18-25) = thoughtful, literary. Note: the range matters more than the average. A voice that alternates 4-word sentences with 20-word sentences has a rhythm; uniform 12-word sentences feel robotic. Document the rhythm pattern, not just the constraint — a voice that writes "Short. Short. Then a longer sentence that builds and lands." has a BEAT. That beat is as distinctive as vocabulary. Name it: "staccato-then-expand," "long build to short punch," "even flow." If you can't name the pattern, the voice doesn't have one yet.
- **Paragraph length:** 1-2 sentences = scannable, digital-first. 2-4 sentences = balanced. 4+ sentences = editorial, longform.
- **POV:** Second person ("you") is direct. First person plural ("we") is communal. Third person is distanced. Most marketing should be "you"-dominant.
- **Punctuation:** Exclamation marks (yes/no/limit). Em dashes: always banned - use regular dashes, periods, commas, or parentheses instead. Ellipses (allowed for suspense/banned). Oxford comma (yes/no). Semicolons (use/avoid). Punctuation is a speech pattern, it's how the voice breathes on the page. Periods create authority and finality (a speaker who commits). Ellipses create hesitation and trailing off (a speaker who implies rather than states). Document which punctuation patterns this voice uses as signatures and which it avoids, these are as identifiable as word choice.
- **Capitalization:** Sentence case vs. title case for headings. ALL CAPS policy.
- **Contractions:** Always (casual), never (formal), context-dependent (which contexts?).
- **Jargon:** Which industry terms are okay? Which are banned? Does the brand define its own vocabulary?
- **Numbers:** Digits vs. spelled out. Currency formatting. Percentage style.
- **Concrete language (Luntz):** Document whether the voice prefers visual, picture-able language over abstract terminology. "Sharpen your pitch" paints an image; "optimize your value proposition" doesn't. Apply the picture test to key copy: can the reader see it? If not, rewrite with a visual verb. This is checkable — audit any passage for abstract verbs (optimize, leverage, streamline, facilitate) and replace with visual alternatives (sharpen, plug, stack, cut).

**Revision layers:** When editing copy for voice consistency, don't try to fix everything in one pass. Make separate passes — one for tone (is the register right across the piece?), one for vocabulary (are we using our words, not generic alternatives?), one for rhythm (does it sound like us when read aloud?). Each pass catches things the others miss. A tone pass catches the paragraph that slips into corporate mode. A vocabulary pass catches the dead metaphor that survived drafting. A rhythm pass catches the sentence that's technically correct but lands flat. Collapsing all three into a single edit produces a piece that's "close enough" in all three dimensions but nailed in none.

**The junior copywriter test:** Could a copywriter with no context follow these rules and produce on-brand copy without asking questions? If they'd need to ask "but what did you mean by 'keep it casual'?", the rules are too vague. If they could open the VOICE.md, read the rules, and start writing — the rules are specific enough.

### 7. Voice by Context

**Genre schemas (Levitin).** Audiences carry unconscious templates for how a brand in this category "should" sound — a SaaS brand has a different schema than a coaching brand, which has a different schema than a media company. Strategic violation of the expected schema creates attention: a B2B brand that suddenly writes with literary texture, a coaching brand that uses clinical precision. But the violation only works when the audience has the schema — break rules they recognize, not rules they don't know exist. When defining the voice, name the category schema the audience expects, then document which conventions this voice follows and which it deliberately violates.

**Tone vs mood — the architectural distinction (Lumet).** Tone and mood are different instruments, and collapsing them is the most common structural error in voice design. Tone is the brand's consistent stance toward its material — irreverent, clinical, conspiratorial, empathetic. It holds across every piece of content the brand produces. Mood is the emotional register of a specific piece — urgent, playful, grave, curious. It varies by context, by audience awareness level, by where the reader is in the sequence. A strong voice holds tone while varying mood. A weak voice changes both with every channel shift, producing a brand that sounds like a different person on the landing page than in the nurture email. The tone is chosen once in the voice guide and locked. The mood is chosen per piece and modulated. When the voice-by-context table below documents register shifts, what's shifting is mood. What's staying constant is tone. If both change, the voice has no spine.

Same character, different register. A person talks differently at a conference than at a bar. They're still the same person — the personality, values, and vocabulary are constant. What shifts is the formality, sentence length, energy level, and how much personality comes through.

Document how the voice shifts across relevant contexts. These shifts are rhetorical decorum (Heinrichs) — the speaker matching their register to the occasion and audience, not just "changing tone." A high-status register for authority content (case studies, thought leadership) deploys credibility-first language. An emotional register for connection content (community posts, founder stories) deploys warmth-first language. Naming these as decorum choices rather than vague "tone shifts" makes them deliberate and checkable.

Document voice the way a screenwriter documents a character — not "conversational" but "short sentences, no qualifiers, asks questions instead of stating conclusions." Not "authoritative" but "leads with data, never hedges numbers, uses 'here's what happened' instead of 'we believe.'" The character method forces specificity: background, verbal habits, sentence structure, what this voice reaches for and what it avoids. If the voice description could apply to any brand, it's an adjective list, not a character.

| Context | Register | What changes | What stays |
|---------|----------|-------------|------------|
| Landing page / sales page | Confident, direct | Longer sections, more proof, higher energy | Character, metaphor system, vocabulary |
| Email (nurture) | Personal, conversational | Shorter, more casual, first-person | Status choice, core personality |
| Email (transactional) | Clear, minimal | Stripped to essentials, no personality flourish | Vocabulary, clarity rules |
| Social (Twitter/X) | Sharp, opinionated | Shortest, most personality, most edge | Character voice, status |
| Social (LinkedIn) | Authoritative, structured | More formal, more expertise signaling | Core message, vocabulary |
| In-app copy | Functional, human | Minimal, action-oriented, no marketing | Warmth, vocabulary, contractions |
| Support / help docs | Patient, specific | Most warmth, most clarity, least personality | Vocabulary, respect for reader |
| Ads / hooks | High-arousal, specific | Most compressed, most emotional, strongest hooks | Character, metaphor system |

Not every project needs all rows. Include only the contexts relevant to the product. A SaaS product might need landing page, in-app, email, and docs. A personal brand might need social, email, and sales page. A B2B consultancy might need LinkedIn, cold email, and service page.

**Platform grammar as structural constraint (Kane).** Register shifts across platforms are not just formality adjustments — they are structural transformations. Each platform has a native grammar that governs length, rhythm, pacing, and composition, and the brand voice must conform to that grammar or sound foreign regardless of how well the character is maintained. Twitter's grammar is compression: one idea per post, no preamble, the insight IS the post. LinkedIn's grammar is structured authority: hook line, supporting argument, spaced single-line paragraphs, a takeaway. Newsletter grammar is sustained intimacy: longer paragraphs, personal asides, the pace of a letter not a feed. YouTube's grammar is spoken rhythm: conversational cadence, verbal signposting, energy front-loaded. A brand that writes LinkedIn posts in newsletter grammar — dense paragraphs, sustained argument, no visual breaks — sounds off-platform even if every word is on-voice. A brand that writes newsletters in Twitter grammar — fragmented, punchy, no connective tissue — sounds like a thread pasted into an email. When building the voice-by-context table, document the platform's structural grammar alongside the register shift: not just "sharper and more opinionated on Twitter" but "one complete thought per post, no thread unless the idea genuinely requires sequence, front-load the sharpest line." The character stays constant. The structure obeys the platform.

**Cross-platform consistency is a recognition signal (Cannell & Travis).** Register can and should shift by context — shorter on Twitter, more formal on LinkedIn, more patient in support docs. But the underlying character must be recognizable everywhere. A brand that sounds irreverent on social, corporate in email, and clinical in-app isn't shifting register — it's three different voices wearing the same logo. The audience who discovers you on one platform and follows you to another should feel like they found the same person in a different room, not a different person entirely. When building the voice-by-context table, test cross-platform recognition: if someone read a tweet, an email, and an in-app message with all branding removed, would they identify them as the same voice? If not, the "What stays" column isn't strong enough.

**Social-to-market norm bridge (Ariely).** Transitions from social-norm register (warm, personal, relationship-first) to market-norm register (transactional, price-forward, CTA-driven) require an explicit contextual bridge — a sentence or section that acknowledges the shift. Abrupt norm-switching at the CTA moment retroactively reads the warmth as manipulation and destroys the trust the voice built. A newsletter that spends eight paragraphs in warm peer-register then drops "Buy now — 50% off ends tonight" with no bridge makes the reader reinterpret the entire email as a sales setup. The bridge can be simple: "If any of this resonated, here's something I built around it." That single sentence moves the reader from social norms to market norms without rupture. Document where the brand's content shifts from social to market register — the newsletter CTA, the webinar pitch, the free-to-paid transition — and prescribe the bridge language for each.

**Audience collision risk.** Flag contexts where multiple audiences converge on the same channel. A founder's Twitter is seen by both early-stage prospects and enterprise buyers. A newsletter goes to free subscribers and paying clients. A webinar recording is shared beyond the live audience. When audiences collide, one register must be prioritized — document which audience "wins" and how the voice handles the other. A founder who's irreverent on Twitter might confuse enterprise prospects who find that channel; the voice guide should name that tension and choose.

**POV register — the speaker's stance.** Context shifts the channel. POV shifts who's speaking. The same brand sounds different when the founder speaks as an authority ("Here's what we built and why"), as a peer ("I hit the same wall you're hitting"), or as a guide ("Here's the framework — let me walk you through it"). Each POV demands a different register: authority POV is declarative, high-status, proof-heavy. Peer POV is personal, uses first-person stories, admits struggle. Guide POV is structured, patient, expertise-forward without credential-waving. Document which POV the brand uses in which situations — a founder keynote is authority, a newsletter is often peer, a tutorial is guide. The trap is defaulting to one POV everywhere. A brand that only speaks as authority sounds cold. A brand that only speaks as peer sounds unserious. A brand that only speaks as guide sounds like a textbook. Name the POV for each major context alongside the channel register.

**Default to guide register (Miller).** Most brand voices should default to guide, not hero. Guide register leads with empathy first ("we understand your problem"), authority second ("here's how we've solved it"). Hero register ("we're the best, most innovative, most powerful") creates distance because it centers the brand as protagonist. Guide register creates trust because it positions the audience as the hero and the brand as the one who helps them win. The voice positions the reader as the hero making progress — the brand is the mentor, not the protagonist (Duarte). Test every piece: if you count "we/our" vs "you/your," the reader should dominate. A voice that centers itself ("We built...", "Our team...") casts itself as hero and the reader as audience. Test every voice sample: does this sound like a guide helping the hero, or a hero bragging about themselves? If the brand's default copy reads like a résumé of accomplishments rather than a map for the reader's journey, it's in hero register. Flip it. The rare exception is luxury or status brands where the audience wants to borrow the brand's status — but even then, the voice works harder when it says "here's what you become" rather than "here's what we are."

**What stays back stage.** The character section defines what the brand shows. Equally important is what it deliberately keeps hidden. Name 3-5 categories of information the brand does not discuss publicly — internal revenue details, client conflicts, operational struggles, pricing rationale, competitive insecurities. The boundary between front stage and back stage sharpens the voice by constraining it. A brand that talks about everything has no mystique. A brand with clear back-stage boundaries can make deliberate reveals (a founder sharing a specific failure) that feel genuine precisely because they're exceptions to the pattern.

**Tonal patterns as register vocabulary (Belfort).** Generic register labels ("confident," "casual," "formal") are too blunt for precise voice calibration. Use named tonal patterns instead: *declarative certainty* (short, committed statements that close the door on doubt), *reasonable man* (measured, logical, "let me walk you through this" calm that disarms skepticism), *mystery/intrigue* (curiosity-forward, implies hidden knowledge, pulls the reader forward), *implied scarcity* (urgency through framing, not countdown timers, signals that the window is real), and *earned empathy* (vulnerability that comes after demonstrated competence, not before it). These five patterns give the voice-by-context table a precise tonal toolkit. Instead of documenting a context as "confident and warm," specify "declarative certainty in the headline, reasonable man through the proof section, earned empathy in the founder story." The patterns are combinable and sequenceable, which is what makes them more useful than adjectives.

**Shift register by audience awareness level (Schwartz).** Beyond channel context and POV, the voice should modulate based on how aware the audience is. For unaware audiences: story-led, indirect, curiosity-driven — the voice leads with the world, not the product. For problem-aware audiences: empathetic, specific, pain-naming — the voice proves it understands before it prescribes. For solution-aware audiences: differentiating, mechanism-forward, comparative — the voice explains why this approach, not just what the approach is. For product-aware audiences: proof-heavy, direct, confident — the voice converts with evidence. For most-aware audiences: transactional, offer-forward, minimal — the voice gets out of the way and lets the offer speak. Same character, same vocabulary, same metaphor system — but the dial settings shift. A brand that sounds the same to a cold prospect and a returning customer is ignoring the most important context of all: what the audience already knows and believes.

**First and last lines carry disproportionate weight (Duarte).** The first line and final line of every communication carry the emotional weight of the entire piece. Opening lines set the relationship; closing lines determine what happens next. Apply more voice craft to these two moments than to middle passages — the opening earns the reader's attention by establishing who's talking and why they should care, and the closing converts attention into action or memory. A piece with a strong middle but a generic opener ("We're excited to share...") and a limp closer ("Let us know if you have questions!") wastes the two moments where voice matters most. When reviewing copy for voice consistency, audit first and last lines separately — they should be the most characteristic, most deliberate expressions of the brand's voice in the entire piece.

**Deep structure (Garfinkel).** Surface voice is word choice, sentence length, register. Deep structure is the psychological sequence underneath — the characteristic rhythms that persist even when the surface adapts to different channels. Define the brand's signature psychological moves: "we lead with a specific story before extracting the framework," "we name the pain with concrete detail before offering the principle," "we build tension through accumulating specifics before releasing with a single declarative line." These patterns are format-independent — they show up in emails, landing pages, social posts, and decks. If two pieces of copy use different vocabulary and register but follow the same psychological sequence, the deep structure is working. Document 2-3 deep structure patterns in the voice guide so every copy-producing skill maintains the brand's argumentative rhythm, not just its surface style.

The test: read the voice-by-context table and write one sentence in each register. Do they sound like the same person in different situations? Or do they sound like different people? If different — the character isn't strong enough. If identical — the register shifts aren't real.

### Voice as Vernacular Expression

Brand voice emerges from how the company and founder actually talk, refined through use — not borrowed from voice template frameworks (Brand). The most authentic voices aren't designed from scratch; they're discovered in how the brand naturally communicates, then codified and sharpened.

**Capture natural voice samples first:**

Most voice guides start with aspirational adjectives ("we want to sound confident and approachable"). This produces template voice — what the brand thinks it should sound like, not what it actually sounds like when it's being itself.

Instead, start with observed voice:
- **Founder writing** — Internal memos, investor updates, team announcements. How does the founder talk when not performing for customers?
- **Internal docs** — Slack messages, project briefs, design rationale. How does the team talk to each other about the work?
- **Customer conversations** — Sales calls, support tickets, onboarding emails. What language emerges when the brand is helping someone?
- **Early marketing** — The first landing page, the first pitch deck, the first newsletter. Before "professional marketing voice" took over, what did the brand sound like?

Mine these sources for patterns:
- Which phrases appear repeatedly?
- What's the sentence rhythm — short and punchy, or long and winding?
- What metaphors show up naturally?
- Where does humor or edge appear?
- What's the default register — formal, casual, technical?
- How does the brand handle objections or hard truths?

**The authentic voice is already there — codify what exists rather than imposing what "should" be there.**

Most brands sound most like themselves in moments they're not trying to sound like anything. A founder explaining the product to a confused user. A team member writing release notes. The CEO's Twitter thread about why they built this. These unguarded moments reveal the real voice.

The voice guide's job is to identify the patterns in those moments and make them repeatable across all contexts. Not to invent a new voice that sounds more professional or more on-trend.

**Example: authentic voice discovery**

A SaaS founder's early emails to customers had a pattern:
- Always started with a specific observation about what the user did ("I noticed you exported 47 reports last week")
- Never used superlatives ("best," "amazing," "incredible")
- Wrote in short declarative sentences with occasional fragments for emphasis
- Used "here's what I'd do" instead of "here's what you should do"
- Signed off with "Let me know if this helps" (not "Don't hesitate to reach out!")

That's the authentic voice. It wasn't designed — it's how the founder naturally talks when helping someone. The voice guide codifies it: "We lead with observed behavior, not generic greeting. We write in short sentences. We give direct recommendations using first person. We sign off with helpful uncertainty, not eager availability."

**Warning: voice templates produce performed voice, not authentic voice.**

"Professional yet approachable." "Confident but not arrogant." "Technical but accessible." These adjective pairs could describe any brand. They produce voice that checks boxes but feels flat because it wasn't found — it was constructed.

The test: If you stripped the brand name off a piece of copy, would someone who knows the company recognize the voice? If not, it's template voice. Authentic voice is distinctive because it's specific to this company's actual communication patterns.

**Process: capture, identify patterns, refine, codify**

1. **Capture** — Collect 10-20 samples of natural brand communication (founder writing, team docs, early marketing, customer conversations)
2. **Identify patterns** — What shows up in at least 60% of samples? Sentence rhythm, vocabulary, metaphors, register, how objections are handled
3. **Refine** — Take the patterns and sharpen them. If the natural voice is "pretty casual," refine that to "conversational, second person, contractions always, sentence fragments for emphasis"
4. **Codify** — Write the refined patterns into checkable rules in the voice guide

The voice guide documents what's already there, just made consistent and intentional.

### Voice Evolution Through Performance

Voice guides should evolve based on which content actually resonates with the audience — not stay locked to launch decisions (Brand). Track what works and iterate the voice toward proven patterns.

**Track which voice applications resonate:**

Most voice guides are written once and never updated. The voice becomes a fixed artifact rather than a living system. But audience response teaches you what's working.

**Performance signals:**
- **Email engagement** — Which emails get high open rates and replies? What voice patterns do they share?
- **Content shares** — Which blog posts, tweets, or LinkedIn posts get shared organically? What makes those pieces distinctive?
- **Conversion on copy** — Which landing pages, sales pages, or CTAs convert better? What voice elements are present?
- **Sales call feedback** — When prospects say "I love how you explain this" or "your emails feel different," what are they responding to?
- **Support ticket tone** — When customers mirror your voice back to you, which elements stick? If they adopt your vocabulary or rhythm, those patterns are resonating

**The discipline: refine voice guide toward what works with your actual audience, not theoretical best practices.**

Generic voice advice says "use short sentences" or "write with empathy." Your engagement data might reveal that your audience responds better to longer, more detailed explanations (technical audience) or that they engage more with edge and provocation than warmth (contrarian audience).

The voice guide should evolve based on evidence from your specific audience, not universal rules.

**Example: voice evolution through performance**

A B2B SaaS brand launched with voice guidance: "confident, direct, professional." Their early email sequences performed okay but didn't stand out.

After six months, they analyzed their highest-engagement content:
- Emails that used specific customer examples performed 2x better than generic benefits
- Subject lines with curiosity gaps ("The metric nobody tracks") got 40% higher opens than direct labels ("Q4 Product Update")
- Long-form educational content (800+ words) got more shares than short tactical posts
- Founder story emails got 3x more replies than feature announcements

They updated the voice guide:
- "Lead with specific customer examples, not generic benefits"
- "Use curiosity-driven framing in headlines and subject lines"
- "Default to depth over brevity — this audience wants detail"
- "Founder voice drives connection; use it more than corporate we"

The voice didn't change — it refined toward what their actual audience responded to.

**When to update the voice guide:**

Not every variant justifies a voice guide update. The threshold: if a voice pattern appears in 3+ high-performing pieces and isn't yet documented in the guide, add it.

**What not to change based on performance:**

Core character stays consistent. The brand's status level, metaphor system, and fundamental personality shouldn't change based on one email that performed well. What evolves is how those core elements are expressed — which tactics, which rhythms, which specific applications resonate most.

**Voice guide as living document:**

The voice guide should have a "Last Updated" timestamp and a changelog. When you refine the voice based on performance, document what changed and why:

```
## Changelog
**2024-03-15:** Added "lead with specific customer examples" to Style Rules based on email engagement analysis showing 2x higher opens for specific vs. generic openers.

**2024-01-08:** Shifted from "professional" to "direct with edge" after analyzing most-shared content and sales call feedback showing audience responds to provocation over diplomacy.
```

This prevents voice drift (guide stops matching actual voice) and documents the evolution so new team members understand why these rules exist.

### Continuous Voice Refinement

Voice guides improve through small updates, not periodic rewrites (Brand). Continuous refinement prevents voice guide drift where the documented voice stops matching actual brand communication.

**The drift problem:**

Most voice guides become outdated within 6-12 months. The brand evolves — new team members join, the audience matures, the market shifts, the product expands. But the voice guide stays frozen.

The result: the voice guide documents a version of the brand that no longer exists. New copywriters read it and produce voice that sounds "off" because it matches the guide, not the current brand.

**Small updates prevent drift:**

Instead of letting the voice guide drift for a year then rewriting it from scratch, update it continuously as the brand evolves.

**Update triggers:**
- **New vocabulary emerges** — The team starts using a new metaphor or phrase consistently. Add it to the vocabulary section before it becomes inconsistent usage.
- **Register shifts observed** — You notice the brand naturally uses a different tone for a new context (e.g., product updates vs. founder essays). Document the register shift in the voice-by-context table.
- **Anti-voice violations spotted** — You catch copy that breaks the voice but isn't explicitly prohibited in the guide. Add the anti-pattern to prevent it from recurring.
- **Metaphor evolution** — The brand's conceptual metaphors shift (from construction metaphor to growth metaphor). Update the metaphor system section.
- **Performance data contradicts guidance** — The guide says "keep it short" but your highest-engagement content is all long-form. Refine the rule based on evidence.

**The discipline: one small refinement per month beats one major rewrite per year.**

Continuous updates keep the voice guide accurate to current brand communication. Major rewrites often throw away institutional knowledge about what works because the rewrite happens long after the team forgot why certain rules existed.

**What a small update looks like:**

Not a full voice guide rewrite. A targeted change to one section:

- Add one new prohibited phrase to the anti-voice section
- Refine one style rule based on recent copy review
- Add one new register to the voice-by-context table for a new channel
- Update one metaphor example that's become stale
- Add one new vocabulary term the brand has adopted

Each update takes 10-15 minutes and keeps the guide aligned with reality.

**Version control for voice guides:**

Treat the voice guide like code — track changes, document updates, maintain a history.

Use version numbers (v1.0, v1.1, v1.2) or dates (2024-03-15) to track updates. When you make a change, note:
- What changed
- Why it changed
- When it changed
- Who changed it

This creates institutional memory. When a new marketing hire asks "why don't we use exclamation marks?" the changelog shows: "Removed exclamation marks from approved punctuation 2023-08-20 because high-status character doesn't amplify for emphasis — the statement lands without it."

**Prevent voice guide abandonment:**

The most common failure mode: the voice guide becomes so outdated that the team stops using it. They know the documented voice doesn't match the current brand, so they ignore it and wing it based on intuition.

Continuous refinement prevents abandonment. If the voice guide is always within 30 days of current brand communication, it stays useful. If it's 18 months out of date, it becomes a historical artifact.

**The monthly voice review:**

Set a recurring task: review the voice guide monthly against recent content.

- Read the last month's emails, landing pages, social posts, sales decks
- Compare them to the voice guide
- Identify patterns that aren't documented (new metaphors, new rhythms, new register shifts)
- Identify patterns that contradict the guide (rules being broken consistently)
- Update the guide to match reality

This takes 30 minutes per month and prevents the voice guide from drifting into irrelevance.

### 8. Anti-Voice

What the brand NEVER sounds like. Anti-voice is more useful than positive rules because it prevents the most common failures. Writers can interpret "confident and direct" many ways. "Never sounds like a corporate press release" is unambiguous.

**Three categories:**

**"We never sound like [specific example]"** — Quote what bad looks like. Not "we avoid being too formal" — quote the exact sentence that would be wrong: "We are pleased to announce the launch of our innovative new solution."

**"We never use [specific words/phrases]"** — Banned vocabulary with reasons. Not just "don't say leverage" — explain why: "We don't say 'leverage' because it's a dead metaphor that makes everything sound like a consulting deck."

**"We never [specific behavior]"** — Behavioral rules. "We never apologize for our pricing." "We never use exclamation marks in subject lines." "We never start emails with 'I hope this email finds you well.'" "We never use 'just' to minimize what we're asking." Every prohibition should connect back to the character — not just what the voice avoids, but why the character would never do it (McPhee). "This voice doesn't hedge because it plays high-status." "This voice doesn't use exclamation marks because the character trusts its statements to land without amplification." A prohibition without a character reason is an arbitrary rule; a prohibition derived from the character is a structural choice that writers can internalize and apply to situations the guide didn't anticipate.

**The shadow self — positioning through what you'd become, not what others are.** Instead of positioning against competitors as simply "wrong," define the shadow self: what this brand would become if it surrendered to its worst impulse. If the brand values simplicity, the shadow self is the bloated feature-factory it would become if it optimized for checkbox comparisons. If the brand values honesty, the shadow self is the hype machine it would become if it optimized for conversions over trust. "That's what we'd build if we optimized for revenue over retention" is a more nuanced, more compelling contrast than "competitors are bad, we're good." The shadow self gives the anti-voice a narrative spine — it's not a random list of things to avoid, it's a coherent picture of the brand's dark path. Define it in the voice guide, and the anti-voice examples flow from it naturally.

**Before/after examples make anti-voice actionable:**

| Never this | Always this |
|-----------|------------|
| "We're excited to announce..." | "Here's what's new:" |
| "Don't hesitate to reach out!" | "Questions? Reply to this email." |
| "We're passionate about helping..." | "Here's what we do:" |
| "Unlock the power of..." | [Name the specific thing it does] |
| "Our innovative solution..." | [Name the product and say what it does] |

Include 5-8 anti-voice examples that cover the most common failures for this specific brand. The examples should be realistic — things Claude would actually generate without the VOICE.md to stop it.

**Expressions given off — the accidental anti-voice.** Beyond what the brand says wrong, document what it accidentally communicates. These are signals leaked through word choice, formatting, and behavior that contradict the intended voice:

| Accidental signal | What it communicates | Fix |
|---|---|---|
| Using "just" in pricing or feature copy | Low confidence about value | Remove "just" — state the thing directly |
| Inconsistent response time across channels | Some channels matter more than others | Name expected response cadence per channel |
| Marketing copy warm, error messages robotic | Two different brands behind the product | Extend the voice guide to cover every touchpoint |
| Dense paragraphs on a "simple" product page | The product isn't actually simple | Match paragraph density to the claim |

Add 2-3 brand-specific examples of expressions given off. These are harder to catch than explicit anti-voice because nobody wrote them on purpose — they leaked.

**The credibility test (Luntz):** Superlatives are the anti-voice's most reliable tell. "Best-in-class," "world-class," "industry-leading," "cutting-edge" — these are credibility claims that destroy credibility. Specifics signal confidence; superlatives signal insecurity. When auditing anti-voice examples, check every claim for superlatives and replace them with specific numbers, timeframes, or outcomes. "The fastest platform" is a superlative. "Processes 10,000 records in 3 seconds" is a credibility signal.

**Voice distinctiveness that serves ego, not audience (Mamet).** A voice element that exists because the brand wants to "stand out" rather than because the reader needs it is ego, not craft. Quirky capitalization, forced catchphrases, contrived sentence fragments for style points — if a voice choice makes the brand feel clever without making the reader's experience better, cut it. The test: remove the distinctive element and ask whether the reader lost anything. If they didn't, the element was serving the brand's desire to be interesting, not the audience's need to understand.

**The pretension test.** If the voice guide uses words the brand's customers would never use in conversation, the voice is performing expertise rather than demonstrating it. A B2B SaaS brand whose customers say "we need to get everyone on the same page" should not have a voice guide that says "synergistic alignment of stakeholder value." The customers' language is the ceiling for vocabulary complexity — anything above it is pretension.

**Sample Rewrites — the companion to Anti-Voice.** Anti-voice shows what to avoid. Sample rewrites show what to do. Take 3+ real copy contexts (landing page headline, email intro, error message, social post) and show the transformation: generic Claude output → this brand's voice applied. At least one rewrite should be a longer passage (50-100 words) to demonstrate sustained voice, not just punchy one-liners. Choose contexts that match the voice-by-context table — these rewrites prove the register shifts are real, not theoretical.

## Quality Check

Before saving VOICE.md, verify:

1. **Character sketch reads like a person, not adjectives.** Could you picture this character at a dinner party? Could you predict what they'd say about a bad product? If not, it's still abstract.
2. **Tone is named and distinct from mood.** The voice guide specifies the brand's tonal stance (its consistent attitude toward its material) separately from the moods it uses in different contexts. If tone and mood are collapsed into one description, the voice will flatten across channels. The tone holds; the mood varies.
3. **Status choice is explicit and consistent.** One status level, documented. No mixed signals between sections.
4. **Primary charisma style identified.** Not defaulting to Visionary. If it IS Visionary, the choice is justified — not just Claude's default.
5. **Metaphor system named with highlight/hide analysis.** The primary conceptual framework is identified, coherent, and its blind spots are acknowledged.
6. **Style rules are checkable.** Specific numbers, specific constraints. A junior copywriter could follow them without asking questions.
7. **Vocabulary has both "use" and "avoid" columns with reasons.** Not just word lists — explanations for why each word fits or doesn't fit the character.
8. **Voice-by-context table has at least 3 relevant contexts.** Each row shows what changes AND what stays constant. Mood varies across rows; tone holds across all of them.
9. **Anti-voice has 5+ specific before/after examples.** Real phrases Claude would generate, paired with what this brand says instead.
10. **Sample rewrites show the voice applied to 3+ different copy types.** Not just headlines — at least one longer passage (email intro, landing page section, error message).
11. **Specific enough for convergence.** Two writers reading this VOICE.md would produce recognizably similar copy. If it could describe any brand in the industry, it fails.
12. **Brand flaw is genuine, not a humble-brag.** The flaw names a real limitation the audience can see for themselves. "We care too much" is not a flaw. "We optimize for simplicity at the cost of power-user features" is.
13. **Shadow self is defined and anti-voice flows from it.** The shadow self names what the brand would become if it gave in to its worst impulse. Anti-voice examples should feel like manifestations of the shadow self, not a random list.
14. **Voice commits fully.** The character sketch, sample rewrites, and vocabulary list should all feel like a voice that has chosen its stance and accepted the tradeoffs. If the guide hedges between two personalities, softens its positions with qualifiers, or tries to appeal to everyone, the commitment isn't there. Check: does the guide name who this voice is NOT for?
15. **Point of view covers every topic the brand touches.** Audit the voice guide for any subject the brand regularly addresses where the stance is interchangeable with competitors. Generic positions on adjacent topics undermine distinctive positions on core topics. Every area the voice touches should have a specific, considered opinion — not necessarily contrarian, but never default.
16. **Expands BRIEF.md without contradicting it.** If BRIEF.md exists, VOICE.md deepens the voice section — same tone, same personality, deeper mechanics. Any conflict means one document is wrong. The voice doc should also include or reference the brand's BrandScript (Miller) — the 7-element narrative (character, problem, guide, plan, call to action, failure, success) that constrains all copy. Without it, the voice is consistent in tone but inconsistent in story. Every channel retells the same narrative spine in different registers; the BrandScript is what keeps that spine coherent. If BRIEF.md contains the BrandScript, VOICE.md should reference it. If neither document has one, flag the gap — a voice guide without a narrative backbone produces copy that sounds right but tells a different story every time.
17. **Dead metaphors identified and replaced.** At least 3-5 dead metaphors from existing copy or common industry language, with conscious alternatives.
18. **Passes the simplicity test.** Could a new copywriter read just the character sketch and write recognizably on-brand copy without asking questions? If the sketch requires interpretation — if a writer would need to ask "but what do you mean by 'authentic'?" — it's too abstract. The character sketch is the voice guide's most important section. If it's clear enough to act on cold, it works.
19. **Authenticity structure.** Flag in the voice doc: this voice must be livable across marketing, product, support, and billing. If the voice only works in marketing copy, it's theater — and customers will feel the gap. Test the character sketch against every touchpoint: could this voice write an invoice reminder? A downtime notification? A pricing page? If the character disappears outside marketing, the voice is a costume the brand puts on to sell and takes off everywhere else. That gap is where trust dies — not because the marketing was bad, but because everything else revealed it wasn't real.
20. **Recipient-first voice (Godin).** The voice should default to centering the audience's experience, not the brand's story. A voice that naturally says "you can now..." instead of "we built..." signals that the brand exists to serve, not to be admired. Check the character sketch and sample rewrites: if the subject of most sentences is the brand ("we," "our team," "our product"), flip them to the reader ("you," "your," "this means you can"). A brand-centered voice talks about itself. A recipient-first voice talks about what changes for the reader. This is distinct from POV rules (which set pronoun ratios) — it's about whose experience the sentence orbits, even when using "we."
21. **Signal congruence (Godin).** Voice is one signal in a system. If the voice says "premium" but the design says "discount," trust erodes. If the voice says "simple" but the onboarding has twelve steps, the audience believes the experience over the words. The voice doc should flag what the non-verbal signals must match — pricing presentation, design density, response speed, packaging, email frequency — so that copy-producing skills don't write voice-perfect text that lands in a contradictory context. Include a brief "signal alignment" note: what the visual design, pricing, UX, and support experience must reinforce for the voice to land as intended.
22. **Camera Test (Whitman).** Take any five voice examples and apply: could a camera capture each? If more than two fail, examples are too abstract to constrain execution (Whitman).
23. **Not in a rut.** If updating an existing VOICE.md, read the last 10 pieces of brand copy. Is the voice still producing growth — new phrasings, fresh angles, expanding range? Or has it become a template — same moves, predictable rhythm, no surprises? If it's a rut, change the input: new source material, new competitors to study, a constraint like "no sentences over 8 words for one week." A voice that never evolves calcifies into the very committee voice it was built to prevent.
24. **Conflict at every level (Howard & Mabley).** Check three levels of tension in the sample rewrites: word-level (unexpected vocabulary that creates friction), sentence-level (rhythm variation that keeps the reader off-balance), and paragraph-level (argument that moves forward, not exposition that sits). A voice flat at all three levels is structurally dead — technically correct but emotionally inert. If a passage reads smoothly without a single moment of surprise, resistance, or forward pull, it needs more tension at one or more levels.

## Output Format

```markdown
# Voice Guide: [Brand/Product Name]

*Generated by /voice. This file is consumed by all copy-producing skills (offers, cold-outreach, email-flows, sales-pages, decks, content-engine). Edit directly to refine.*

---

## The Character
*The character sketch is the structural foundation. Every rule below is derived from it. If the character sketch changes, every rule below must be re-derived — a rule that doesn't trace back to the character is a floating convention, not a voice choice (McPhee).*

[2-3 paragraph character sketch. Who is this brand as a communicator? How do they see the world? What do they care about? How do they react? What's their rhythm? Must read like a specific person, not a category. Use a cross-domain analogy — "a documentary narrator who..." or "a dive bar bartender who..." — not adjectives.]

**Creative DNA:** [Recurring themes, instinctive angles, blind spots. What the brand always leads with, what it consistently avoids, where it needs deliberate growth.]
**Brand flaw:** [The acknowledged incompleteness — a bias, limitation, or tension the brand hasn't fully resolved. Must be genuine, not a humble-brag. This is what makes the voice human.]
**Back stage:** [3-5 categories of information the brand deliberately keeps private — this sharpens the front-stage voice by defining its boundary.]

## Status & Style
**Tone:** [The brand's consistent stance toward its material — e.g., conspiratorial, clinical, irreverent, empathetic. Chosen once, held everywhere.]
**Status:** [High / Medium-High / Medium / Medium-Low / Low] — [why this choice, what it looks like in practice]
**Role distance:** [When the brand can be irreverent about its own category, and what competence signals must be established first]
**Charisma style:** [Authority / Visionary / Kindness / Focus] primary, [secondary] supporting
**Pillars:** Presence [1-5] | Power [1-5] | Warmth [1-5]
**Primary emotional register:** [The LF8 desire this voice serves by default — safety, freedom from fear, comfortable living, status, social approval, care for loved ones. Prevents a voice guide that's technically correct but emotionally generic (Whitman).]

## Metaphor System
**Primary frame:** [e.g., BUILDING — foundation, architecture, structure]
**Highlights:** [what this metaphor makes visible]
**Hides:** [what this metaphor suppresses]
**Dead metaphors to retire:** [list with replacements]
**Rhetorical devices:** [Which devices this voice uses — antithesis, energeia, rhythm patterns — and which it avoids]

## Style Rules
- Sentence length: [average range and maximum]
- Paragraph length: [range]
- POV: [person, ratio]
- Punctuation: [specific rules for exclamation marks, ellipses, Oxford comma]. Em dashes: banned. Use regular dashes, periods, commas, or parentheses instead.
- Capitalization: [heading style, emphasis policy]
- Contractions: [always / never / policy]
- Jargon: [policy with specific terms allowed and banned]
- Numbers: [digits vs. spelled out, currency, percentages]

## Vocabulary
| Use | Instead of | Why |
|-----|-----------|-----|
| [brand word] | [generic alternative] | [what the brand word signals] |

| Never use | Why |
|-----------|-----|
| [word] | [what it signals that conflicts with the character] |

## Voice by Context
| Context | POV | Register shift | Collision risk | Example |
|---------|-----|---------------|----------------|---------|
| [relevant context] | [authority / peer / guide] | [what changes, what stays] | [which audiences overlap here, which one the register prioritizes] | [one sentence in this register] |

## Sample Rewrites
### [Context 1: e.g., Landing page headline]
**Generic:** [before — what Claude would write without VOICE.md]
**Our voice:** [after — what it should sound like]

### [Context 2: e.g., Email subject line]
**Generic:** [before]
**Our voice:** [after]

### [Context 3: e.g., Error message or in-app copy]
**Generic:** [before]
**Our voice:** [after]

## Anti-Voice
**Shadow self:** [What this brand would become if it surrendered to its worst impulse. The anti-voice examples should flow from this — they're not random prohibitions, they're manifestations of the dark path.]

**We never sound like:**
| Never this | Always this |
|-----------|------------|
| [specific bad example] | [what we say instead] |

**Banned phrases:** [list with reasons]
**Behaviors we avoid:** [list of behavioral rules]

## Discovered vs. Intended
*Include this section only when existing copy was analyzed. Omit for net-new voice builds.*

**Current voice:** [What the existing copy actually sounds like — the discovered voice, described without judgment]
**Target voice:** [What the character sketch above defines — the intended voice]
**Gap:** [Specific differences between discovered and intended — not "more casual" but "current voice hedges with qualifiers in 60% of claims; target voice commits without qualification"]
**Evolution path:** [Specific changes required to close the gap — which patterns to stop, which to start, which to amplify. Evolving a voice is harder than building one from scratch because the existing patterns are habitual. Name the 3-5 specific habits that must change (McPhee).]

**Expressions given off — accidental signals to audit:**
| Signal | What it leaks | Fix |
|--------|--------------|-----|
| [accidental signal from word choice, formatting, or behavior] | [what it communicates to the reader] | [how to correct it] |
```

## After Delivering

"Read the Character section first — does it sound like a specific person, or could it describe any brand in your industry? If it's too generic, tell me what's missing. Then check the Anti-Voice section — does it name the exact things you hate seeing in your copy? Those two sections do 80% of the work. The style rules and vocabulary are for enforcement; the character and anti-voice are for identity."

If the user has BRIEF.md: "Your BRIEF.md voice section is the quick reference. This VOICE.md is the deep guide. If they ever conflict, update one to match the other — every skill checks both."

If the user provided writing samples: "I built this from your existing copy. The character sketch describes how you already write at your best. The anti-voice names the patterns you'll want to avoid. If any rule feels wrong — if it describes someone else's voice, not yours — tell me which one and I'll recalibrate."

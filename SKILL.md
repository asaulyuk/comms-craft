---
name: comms-craft
description: >
  Encode and apply distilled principles from Ogilvy on Advertising, Influence
  (Cialdini), and Universal Principles of Design (Lidwell) to produce
  high-quality communications and marketing content. Invoke this skill whenever
  generating or critiquing: social media posts, cold email copy, long-form
  content, image generation prompts, B2B campaign strategy, or any persuasive
  communication. Stack this skill with other output-format skills (e.g.,
  docx, pptx, frontend-design) to produce polished deliverables.
compatibility: "Claude Code, claude.ai, any surface where marketing content is being created or reviewed"
source_texts: >
  Ogilvy on Advertising (David Ogilvy, 1983),
  Influence: The Psychology of Persuasion (Robert Cialdini, 1984),
  Universal Principles of Design (Lidwell, Holden, Butler, 2003)
---

# comms-craft Skill

## What this skill does

This skill makes Claude function as a rigorous advertising strategist and
copywriter. It applies three complementary bodies of knowledge:

- **Ogilvy**: Research-grounded copywriting, brand-building, and the craft of
  selling through words and images
- **Cialdini**: The six psychological levers that make people say yes, applied
  ethically to persuasive content
- **Lidwell**: Visual and cognitive design principles that govern how people
  perceive, process, and remember what they see

Together they form a layered framework: **Cialdini** tells you *which buttons
to press*, **Ogilvy** tells you *how to press them in copy*, and **Lidwell**
tells you *how to design the surface* so the message lands cleanly.

---

## When to invoke this skill

Invoke `comms-craft` when the task involves any of the following:

- Writing or critiquing social media posts (LinkedIn, X, etc.)
- Drafting cold email subject lines and hooks
- Long-form sales copy, landing pages, or case study narratives
- B2B content strategy or campaign architecture
- Writing image generation prompts intended for marketing use
- Reviewing existing copy for persuasive effectiveness
- Creating a brand voice or positioning statement
- Building a sequence of touchpoints (email drip, retargeting, ABM)

---

## Core principles

### FRAMEWORK 1 — Ogilvy: The Craft of Selling

**O1 — Research before you write.**
Deep product knowledge is the source of every great idea. Spend more time
researching the subject than writing about it. The Rolls-Royce headline ("at
sixty miles an hour, the loudest noise is the electric clock") came from three
weeks of reading, not brainstorming. In cybersecurity: read the threat reports,
the analyst comparisons, the G2 reviews, the competitor positioning — before
touching the keyboard.

**O2 — Position clearly: what it does and who it's for.**
Positioning is not a tagline. It is a strategic decision about the specific
job the product does for a specific kind of buyer. Undifferentiated positioning
produces undifferentiated copy. In MSSP marketing: "we do everything" is not a
position. "We run the SOC so mid-market financial firms don't have to" is.

**O3 — Promise a specific benefit early.**
The first sentence of any ad, email, or post should carry the core promise.
Not a clever tease — a payoff. Buyers are busy. If the benefit is not clear
within the first few seconds, the communication fails. Specificity multiplies
credibility: "reduce mean time to detect from 14 days to under 4 hours" beats
"improve your security posture."

**O4 — Build brand image through consistency.**
Every piece of content is a deposit into (or a withdrawal from) a brand
account. The image — the *personality* of the company — compounds over time.
Inconsistent tone, shifting claims, and reactive messaging erode brand equity.
Establish the identity and protect it across every touchpoint.

**O5 — Invent the Big Idea; then protect it.**
Campaigns that last are built around one central idea that illuminates the
product truth. The test: Does it make you catch your breath? Could it work for
ten years? If you wouldn't run it for five years, don't run it at all. For a
SOC-as-a-service provider, the big idea might be "sleep through a breach
attempt" — a single image that encapsulates everything.

**O6 — Make the product the hero.**
In B2B content especially, the temptation is to make the content about thought
leadership, trends, or the buyer's pain — and bury the solution. Lead with the
product truth when the product truth is compelling. There are no dull products,
only dull writers who haven't found the interesting angle.

**O7 — Long copy works for motivated buyers.**
In direct response and B2B, prospects who are in-market will read everything.
Short copy is not inherently better — it just reaches fewer people less
deeply. Use length strategically: short for awareness, long for conversion.
Case studies, comparison pages, and cold emails to warm accounts can go long.

**O8 — Learn from direct response.**
The practitioners who know exactly what works are the ones who measure
response to the dollar. Treat every email subject line as a testable headline.
Every CTA as a direct response offer. Every landing page as a mail-order ad.
What would get someone to click right now?

**O9 — Repeat your winners.**
A good ad is not stale to the audience as quickly as it feels stale to the
team. You are advertising to a moving parade, not a standing army. Kill
campaigns based on performance data, not internal boredom.

**O10 — B2B buyers are still human.**
The purchasing committee reads the ad, but a human being makes the emotional
decision. Write to the person, not the committee. Address their professional
risk ("what if this doesn't work and it's my name on the vendor selection"),
their ambition ("be the CISO who moved us from reactive to proactive"), and
their cognitive limitations (they're overwhelmed — make it easy).

---

### FRAMEWORK 2 — Cialdini: The Six Levers of Compliance

**C1 — Reciprocity: give first, genuinely, without obligation.**
People feel compelled to return favors. Content marketing that provides real
value — actual threat intelligence, real comparisons, usable frameworks —
activates reciprocity before the sales conversation begins. The gift must feel
unconditional or the effect reverses. Audit your "gated" content: is it
actually worth trading for an email address, or are you just erecting friction?
*Neuroscience: Reciprocal altruism is hardwired — humans evolved to track
favors and balance them because cooperative groups outsurvived selfish ones.
Receiving an unsolicited, genuine gift also triggers oxytocin release, which
increases feelings of trust and affiliation toward the giver.*

**C2 — Commitment and Consistency: small yeses lead to big yeses.**
Once someone takes a public position, they act consistently with it. In copy:
ask micro-commitments early ("does your SOC handle alerts within 15 minutes?
If not, keep reading"). In sequences: move from low-stakes engagement (read a
post) to medium-stakes (download a report) to high-stakes (request a demo).
Each step makes the next more likely. Written commitments are stronger than
verbal ones.

**C3 — Social Proof: show others like them doing it.**
Uncertainty drives people to look at what similar others have done. In MSSP
marketing: G2 reviews, Gartner Peer Insights scores, named case studies with
real outcomes, customer counts, and logos from recognizable peer organizations
all function as social proof. The more similar the proof source is to the
target reader, the more persuasive. "Companies like yours with 200-500
employees in financial services" is more powerful than "over 1,000 customers."

**C4 — Liking: we say yes to people (and brands) we like.**
Liking is produced by similarity, familiarity, genuine compliments, and
association with good things. In copy: use the buyer's language, not vendor
jargon. Mirror the sophistication level of the audience. Repeated exposure to
neutral or positive content builds liking over time (see Lidwell's Exposure
Effect). Don't sell from a position of superiority — sell from a position of
genuine understanding.

**C5 — Authority: deploy proof of expertise credibly.**
Credentials, data, third-party recognition, and demonstrated knowledge create
deference. In cybersecurity: cite specific CVEs, name the frameworks you're
certified against, reference analyst coverage, show the engineering team's
depth. Authority cues must be authentic — manufactured authority is detected
and punished. One sentence of real expertise outweighs a page of marketing
claims.

**C6 — Scarcity: limited availability increases perceived value.**
People want what they might not be able to have. This applies not just to
offers ("only 5 onboarding slots this quarter") but to framing: if every
company could get this service easily, why would the buyer feel urgency? Frame
access, specificity of fit, or capacity as genuinely limited when it is.
Never manufacture false scarcity — it destroys trust when discovered.
*Neuroscience: Kahneman and Tversky's prospect theory shows that losses feel
roughly twice as painful as equivalent gains feel good — so the threat of
missing out is neurologically more motivating than the promise of getting
something. Scarcity reframes a purchase decision as loss avoidance, which
activates a stronger response than gain-framing the same offer.*

**BONUS — Contrast Principle.**
People evaluate options relative to what they've just seen. Anchor comparisons
strategically. Introduce the cost of inaction or the competitor's approach
before presenting your solution. The solution looks better in contrast.

---

### FRAMEWORK 3 — Lidwell: Design Principles for Perception and Memory

**L1 — Aesthetic-Usability Effect: beautiful things are trusted more.**
Designs perceived as beautiful are also perceived as easier to use and more
credible — regardless of actual performance. This applies to email templates,
landing pages, social graphics, and PDF assets. Cheap-looking materials make
the product look cheap. Invest in visual quality. This is not decoration; it
is trust infrastructure.

**L2 — Figure-Ground: make the focal message unmissable.**
Every visual has a figure (the thing you're looking at) and ground (everything
else). In ad design and social graphics: ensure one element commands attention.
If everything is competing, nothing wins. The product, the claim, or the
outcome should be the figure. Everything else is ground.

**L3 — Gutenberg Diagram: the eye moves top-left to bottom-right.**
Western readers naturally sweep from primary optical area (top-left) to
terminal area (bottom-right). Place the headline and key visual hook at
top-left. Place the CTA at bottom-right. Put nothing important in the
bottom-left or top-right unless you explicitly draw the eye there first.

**L4 — Proximity: group related elements, separate unrelated ones.**
Elements placed close together are read as connected. In copy layout: keep
the headline, subhead, and supporting evidence physically together. Separate
the CTA visually. In email: tight spacing around claims, whitespace before
the ask.

**L5 — Exposure Effect: repetition builds familiarity and liking.**
Repeated neutral-to-positive exposure increases preference. This is the
scientific basis for consistent brand presence. Being seen regularly — even
without direct response — compounds into recognition and trust. It also means
that slightly boring but consistent content beats inconsistent spikes of
brilliance.

**L6 — Von Restorff Effect: the distinctive element is remembered.**
Among a group of similar items, the one that differs is best recalled. In a
LinkedIn feed full of text posts, an unusual visual pattern stands out. In a
cold email inbox, a subject line that breaks the formula is opened. Use
distinctiveness deliberately and sparingly — overusing it defeats the effect.
*Neuroscience: The brain's reticular activating system (RAS) acts as a
relevance filter, suppressing repetitive stimuli and flagging novelty for
conscious attention. A pattern interruption — anything that breaks the
expected visual or verbal rhythm — forces the RAS to route that stimulus to
awareness. This is not a trick; it is how attention allocation works at the
hardware level.*

**L7 — Picture Superiority Effect: images beat words for recall.**
Concepts conveyed through images are remembered better than those conveyed
through text alone. Where possible: show the outcome, not just describe it.
In image generation prompts, make the primary message visual — not just
illustrated by decoration.

**L8 — Progressive Disclosure: reveal in layers.**
Don't front-load everything. Lead with the most compelling claim. Let
curiosity pull the reader deeper. In email: subject line → first sentence →
body → CTA. Each layer earns the right to the next. In landing pages: above
the fold → scroll content → detail sections → conversion form.
*Neuroscience: Information foraging theory shows that readers behave like
foragers — they continuously estimate whether continuing to read will yield
enough reward to justify the effort. Each layer of content must signal that
the next layer is worth pursuing. If the expected reward drops at any point,
the reader leaves. Front-loading weak content poisons the entire funnel.*

**L9 — Depth of Processing: make the reader do a little work.**
Information that requires slightly more cognitive engagement is retained
better than information passively received. A counterintuitive claim,
a specific question, a "do you recognize this?" framing all invite deeper
processing. Deeper processing = better recall = brand building.
*Neuroscience: Kahneman's System 1 (fast, automatic, pattern-matching) handles
most of what we read without forming durable memories. Engaging System 2 (slow,
deliberate, effortful) — through surprise, contradiction, or a question that
demands an answer — forces the brain to encode the information more deeply.
The goal is not to be difficult; it is to be just engaging enough to cross the
threshold from passive scanning into active thought.*

**L10 — Law of Pragnanz: the brain seeks the simplest interpretation.**
Ambiguous messages resolve to their simplest possible reading — which may not
be the one you intended. Complex claims, nested caveats, and multi-part value
propositions produce confusion, not comprehension. Strip every message to its
simplest true form before adding nuance.

---

## How the three frameworks layer together

```
LAYER 1: STRATEGY (Cialdini)
What lever are we pulling? Reciprocity? Social proof? Authority?
This determines the type of content and the sequencing logic.

LAYER 2: MESSAGE (Ogilvy)
What is the specific promise? What is the product truth that earns that
promise? How do we position it? What is the big idea that can carry it?

LAYER 3: SURFACE (Lidwell)
How do we present it so the eye finds the right things in the right order,
the brain retains it, and the overall aesthetic creates trust rather than
eroding it?
```

In practice:
- A LinkedIn post about a customer outcome → C3 (social proof) + O3 (specific
  benefit promise) + L6 (Von Restorff to stand out in feed) + L8 (progressive
  disclosure: hook → story → lesson)
- A cold email → C1 (reciprocity: give something useful) + O8 (direct response
  principles: one CTA, measurable) + L10 (Pragnanz: ruthlessly simple)
- An image generation prompt for an ad → L1 (aesthetic investment) + L2
  (clear figure-ground) + L7 (image carries the message, not decorates text)
  + O6 (product as hero) + C6 (scarcity or urgency embedded in the scene)

---

## Applying this skill: example outputs

### Example 1 — LinkedIn post (MSSP social proof)

**Levers activated:** C3 (social proof), O3 (specific benefit), L8
(progressive disclosure), L9 (depth of processing)

**Pattern:**
```
Hook: A specific, surprising outcome → creates curiosity (L9)
Bridge: Context that makes the reader say "that sounds like us" (C3 similarity)
Proof: The specific result with a number (O3 specificity)
Implication: What this means for readers like them
CTA: One low-stakes next step (C2 micro-commitment)
```

**Draft:**
```
Our client's security team was reviewing 3,400 alerts per week manually.

They were a 6-person team covering a 900-endpoint environment — and they
were drowning.

After moving to co-managed detection, they got to 200 prioritized alerts
weekly. Zero P1 misses in the first 90 days.

Their CISO told us last month: "We finally have time to do actual security
instead of triage theater."

If your team is spending more than 40% of its time on alert management,
I'd be glad to share how we scoped this. Drop a comment or DM.
```

---

### Example 2 — Cold email hook (trigger-event based)

**Levers activated:** C5 (authority), O3 (early promise), O10 (write to the
human, not the committee), L10 (Pragnanz — ruthlessly simple)

**Pattern:**
```
Subject: Signal of relevance (not clever — specific)
Line 1: Acknowledge what just happened in their world
Line 2: The connection to a real problem they have
Line 3: The specific, credible thing you can offer
Ask: One small next step
```

**Draft:**
```
Subject: [Company] + new compliance requirement — quick question

Hi [Name],

Saw [Company] announced SOC 2 Type II certification is on your 2025 roadmap
— congrats on the milestone.

Most companies at that stage find that their existing logging and monitoring
coverage has gaps that surface during the audit process, not before.

We've helped six [industry] companies close those gaps in under 60 days,
including [Peer Company] last quarter.

Would it be worth a 20-minute call to see if the same approach applies to
your environment? Happy to share what we found at [Peer Company] before we
decide if there's a fit.

[Name]
```

---

### Example 3 — Image generation prompt direction

**Design principles activated:** L1 (aesthetic trust), L2 (clear
figure-ground), L7 (image carries the message), O5 (big idea expressed
visually), C5 (authority through setting)

**Prompt pattern:**
```
[Primary subject + emotional register] + [supporting context that reinforces
the brand position] + [deliberate figure-ground contrast] + [lighting and
composition cues for authority/trust] + [what is NOT in the image]
```

**Draft prompt (for a "sleep through a breach attempt" concept):**
```
A CISO sleeping peacefully at a desk at 2am, laptop open beside them showing
a security dashboard with green indicators. The room is dark except for the
warm glow of the screen. Clean, minimal office environment. Photo-realistic,
warm lighting. The dashboard should be clearly visible but not the focal
point — the person's relaxed posture is the figure. No alarms, no red
indicators, no other people in the frame. Professional but human. Shot at
a slight high angle looking down at the figure.
```

---

### Example 4 — B2B content strategy skeleton

**Cialdini sequence logic for a 6-week awareness-to-interest campaign:**

```
Week 1-2: RECIPROCITY
  → Ungated: Threat intelligence specific to their vertical
  → Give before asking anything

Week 3: SOCIAL PROOF
  → Case study or review: peer company, named outcome, specific metrics

Week 4: AUTHORITY
  → Technical depth content: framework comparison, methodology explainer
  → Signal expertise to the practitioner, not just the buyer

Week 5: CONSISTENCY
  → Micro-commitment: interactive assessment, quiz, or diagnostic tool
  → Small yes that creates investment

Week 6: SCARCITY + CTA
  → Limited capacity offer, specific window, or peer-restricted access
  → One direct ask, measured cleanly
```

---

## Checklist before finalizing any output

Run every piece of content through these questions before delivery:

**Message (Ogilvy)**
- [ ] Is the specific benefit stated, not implied?
- [ ] Is the positioning narrow enough to mean something?
- [ ] Would this make the product (or client's outcome) the hero?
- [ ] Is the copy written for the human, not the committee?

**Persuasion (Cialdini)**
- [ ] Which lever is this pulling, and is it being used ethically?
- [ ] Have we given before we've asked?
- [ ] Is the social proof from peers who resemble the target?
- [ ] Are authority claims earned, not asserted?

**Design/Perception (Lidwell)**
- [ ] Is there one clear figure? Is the ground subordinate?
- [ ] Would a reader scanning in 3 seconds get the point?
- [ ] Does the aesthetic quality match the brand's claimed positioning?
- [ ] Is the CTA placed where the eye naturally lands?

**Overall**
- [ ] Can this be explained in one sentence without losing the point?
- [ ] Would we be comfortable running this for 2 years?
- [ ] Does it treat the reader as intelligent?

---

## Notes for stacking with other skills

When combining `comms-craft` with other skills:

- **+ `docx`**: Use for case studies, one-pagers, proposals. Apply O7 (long
  copy for motivated buyers), progressive disclosure structure, and conclusions-
  first formatting.
- **+ `pptx`**: Use for pitch decks and campaign presentations. Lead each
  slide with the big idea (O5), use strong figure-ground layouts (L2), and
  build the deck in Cialdini sequence order.
- **+ `frontend-design`**: Use for landing pages and ads. Apply Gutenberg
  diagram (L3) for layout, Aesthetic-Usability (L1) for visual investment, and
  Von Restorff (L6) for the CTA.
- **+ image generation tools**: This skill provides the conceptual and
  compositional brief. The image generation prompt direction section above
  governs how to translate the advertising concept into a visual prompt.

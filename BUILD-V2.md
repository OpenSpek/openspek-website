# OpenSpek Website v2 Build Brief

Rewrite index.html and styles.css completely. This is v2 -- new copy, new structure, bolder voice.

## Design System (unchanged)
- Background: #0A0A0F
- Card/surface: #111118
- Accent indigo: #6C63FF
- Accent amber: #F5A623
- Text primary: #F0F0F5
- Text muted: #8888AA
- Border: #1E1E2E
- Font: Inter from Google Fonts (400, 500, 700, 900)
- Dark minimal, bold headlines, generous whitespace
- Mobile responsive at 768px
- html { scroll-behavior: smooth; }

## Vibe
Bold swagger backed by receipts. Not hype -- proof. Two audiences: (1) frustrated operators who have tried AI and failed, sick of bloated SaaS that does not do what they want. (2) Technical AI enthusiasts who want to know HOW. The first group should feel: relief, finally. The second group: curiosity verging on disbelief. No corporate language. No buzzwords without teeth.

## Navigation (fixed top, backdrop-filter blur)
- Left: OpenSpek wordmark (white, 700 weight)
- Right: Why It Fails | How We Fixed It | SpekBoard | About | Book a Call (indigo button)
- On mobile: show only wordmark + Book a Call button
- Anchors: #why-it-fails #how-we-fixed-it #spekboard #about #contact

## SECTION 1 - HERO
Eyebrow (small, amber, letter-spaced uppercase): AUTONOMOUS AI DEVELOPMENT

H1 (massive, tight line-height, three lines):
We figured out
what everyone else
is still guessing at.

Subhead (muted, 18px, max-width ~600px centered):
Autonomous AI pipelines that ship verified work, monitor themselves, and self-improve -- long after delivery. We are not theorizing. We have the receipts.

Buttons: "See How We Did It" (indigo, href=#how-we-fixed-it) and "Book a Call" (ghost outline, mailto:hello@openspek.com)

Tiny muted line below buttons: Built in the open. Proven in production. April 2026.

## SECTION 2 - WHY IT FAILS (id="why-it-fails")
Section label (small, amber, letter-spaced): THE PROBLEM
H2: Three reasons AI projects fail.
Subhead (muted): You have probably experienced at least one of these.

Three cards in a row (flex, stack on mobile). Each card: huge stat in amber at top, bold heading, body, small muted source.

Card 1: Stat "72%" / Heading "The Talent Gap" / Body "of enterprises cannot hire the AI talent they need. The market is too thin, too expensive, and moves too fast. Meanwhile your competitors are not waiting." / Source: ManpowerGroup

Card 2: Stat "12%" / Heading "The Complexity Trap" / Body "of companies reach full AI operations. Not because the technology does not work -- because nobody has figured out how to make organizations and AI systems actually talk to each other." / Source: IDC

Card 3: Stat "56%" / Heading "The ROI Black Hole" / Body "of CEOs reported no measurable gains from AI investment. You hired consultants. You ran pilots. You have a chatbot nobody uses. You are not alone and it is not your fault." / Source: PWC

Below the three cards, centered italic muted line: The problem is not the models. It has never been the models.

## SECTION 3 - THE BREAKTHROUGH (id="how-we-fixed-it")
Section label (small, amber, letter-spaced): THE BREAKTHROUGH
H2 (large, bold, two lines): We solved autonomous perpetuity. / Nobody else has.
Subhead (muted, max-width ~650px): Not as a pitch. As a fact. The OpenSpek pipeline ships verified work, monitors itself, plans its own fixes, and implements them -- without the operator being paged. We built it. We run it. Every day.

BOLD CALLOUT BOX (full width, bg #111118, 4px indigo left border, generous padding, slightly larger text):
"How do we know it works? Because this website was built by it. Because every line of code in our own products was written, reviewed, and verified by it. We are not selling you a theory. We are the proof of concept."

Two columns below (stack mobile):

Left col:
Heading: What autonomous perpetuity actually means
Body: Traditional software is static. When it breaks, a human fixes it. When requirements change, a human plans the update. The support burden scales linearly -- more clients means more staff, forever.

OpenSpek pipelines participate in their own maintenance. The agent team watches for anomalies, generates issues, plans fixes, builds them, and verifies the result -- all before you know there was a problem.

When the project ends, the system does not. That is autonomous perpetuity. And it is the answer to the question every client eventually asks: what happens after you build it?

Right col:
Heading: The receipts
Bullet list (amber bullet dots):
- Two features shipped, reviewed, and merged to main in under 10 minutes each
- Full audit trail: every agent action logged with tokens, turns, and duration
- Zero idle cost between tasks -- the pipeline runs only when working
- Reviewer catches regressions before they ship
- Automated merge on clean builds -- no human required between brief and notification

## SECTION 4 - THE FOUR DISCIPLINES
Section label (small, amber, letter-spaced): WHY WE CAN CLAIM THIS
H2: The foundation nobody else has built.
Subhead (muted): The Four Disciplines are not a framework we teach. They are how we operate. Every client engagement is built on all four layers -- and so is everything we have ever shipped.

Four items in 2x2 grid (stack mobile). Each: large number (indigo, 3.5rem, bold), bold title, body text. Numbers do the visual work.

01. Prompt Craft
Most teams stop here and wonder why the output is inconsistent. Clear, specific, testable instructions are table stakes. Every agent we build masters this before anything else.

02. Context Engineering
Your prompt is 0.02% of what the model sees. The other 99.98% is context -- memory files, system docs, project state, skill files, handoff documents. Most teams optimize the prompt and ignore everything else. We engineer the entire information environment the agent operates in.

03. Intent Engineering
What the agent wants, not just what it knows. Goals, values, decision boundaries, trade-off hierarchies, escalation triggers. Agents without this optimize for the wrong thing. Intent engineering is why our pipeline escalates to human review when it should -- and does not when it should not.

04. Specification Engineering
Your organization has knowledge locked in people, in habits, in undocumented decisions. Spec engineering extracts that knowledge and turns it into agent-executable specs. Strategy, product roadmap, quality standards, acceptance criteria -- all of it becomes infrastructure the agent team can work against. This is what makes autonomous perpetuity possible at the organizational level, not just the technical one.

Bold centered line below grid (1.5rem, white): Most agencies are stuck at level one. We operate at all four simultaneously -- and we bring all four to every client.

## SECTION 5 - THE PIPELINE
Section label (small, amber, letter-spaced): HOW IT WORKS
H2: From brief to shipped. No exceptions.
Subhead (muted): Every task flows through the same pipeline. Every commit is verified. Every merge is clean.

Pipeline: 6 nodes horizontal (vertical on mobile), connected by "-->" arrows in muted color.
Use ROLE names, not agent names:
1. BRIEF / You
2. SPEC / Orchestrator
3. BUILD / Developer
4. REVIEW / Reviewer
5. VERIFIED / Orchestrator
6. MERGED / main branch

Each node: small dark card (#111118), role name in indigo caps, label below in muted.

Callout box below (indigo left border, dark bg): Every commit is verified against acceptance criteria before it ships. The reviewer checks the diff. The orchestrator confirms. The operator receives a notification: Done.

Small muted note: On clean builds with no escalation triggers, the pipeline auto-merges to main. No human required between brief and notification.

Three stat mini-cards below (stack row, dark cards, number in indigo, label in muted):
Card 1: "1" / Operator touchpoint to start work
Card 2: "0" / Idle cost between tasks
Card 3: "100%" / Commits reviewed before merging

## SECTION 6 - SERVICES (id="services")
Section label (small, amber, letter-spaced): HOW WE WORK TOGETHER
H2: Three ways in. One standard of output.
Subhead (muted): The right fit depends on how much ownership you want. The pipeline quality is the same regardless.

Three cards (flex row, stack mobile). Middle card featured (indigo border, amber badge "MOST POPULAR" top right).

Card 1 -- Tier A:
Small tier label (muted): TIER A
Title: You own it. We build it and hand it off.
Amber bullets:
- Full pipeline install on your infrastructure
- Spec, Intent, and Context Engineering
- Operator training for your team
- Handoff -- your pipeline, your control
- Self-healing after we leave
Footer italic muted: Best for teams that want full ownership and internal capability
Button: Book a Call (ghost)

Card 2 -- Tier B (FEATURED, indigo border):
Small tier label (muted): TIER B
Title: You own it. We stay in the room.
Amber bullets:
- Everything in Tier A
- OpenSpek Operator on retainer
- Escalations, major features, pipeline evolution
- Internal capability plus expert backup
Footer italic muted: Best for companies that want ownership with a safety net
Button: Book a Call (indigo solid)

Card 3 -- Tier C:
Small tier label (muted): TIER C
Title: You brief us. We ship it.
Amber bullets:
- OpenSpek operates the pipeline on our infrastructure
- You brief our Operator, receive verified results
- No infrastructure required on your end
- Monthly retainer
Footer italic muted: Best for teams that want results without setup overhead
Button: Book a Call (ghost)

## SECTION 7 - SPEKBOARD (id="spekboard", bg #0F0F16)
Section label (small, amber, letter-spaced): OPEN SOURCE SOON
H2: SpekBoard. Built by the pipeline. For the pipeline.
Subhead (muted): Every task is an Issue. Every action is a comment. Every commit is tracked. Private alpha now. Open-source soon.

Two columns (stack mobile):

Left copy:
Autonomous agent pipelines have a set of hard problems: two agents grabbing the same task simultaneously, stalled work that nobody notices, no visibility into what is happening, and the need for human checkpoints before expensive work begins.

SpekBoard solves all of them structurally. It is the command center the pipeline runs on -- now in private alpha, with the open-source release following once release prep and transfer validation are complete.

The architecture is a reference implementation for anyone building autonomous agent systems. We built it because we needed it. The release work is in motion now, and the open-source handoff follows as soon as the system is validated for transfer.

Right feature list (amber checkmark unicode, 6 items):
- Atomic checkout -- no two agents grab the same task
- Review gate -- every commit checked against acceptance criteria before merge
- Approval gates -- human checkpoint before the pipeline builds
- Stall detection -- nothing silently dies
- Live dashboard -- pipeline status, agent context, session health
- Full audit trail -- tokens, turns, duration, session log per task

CTAs centered below: "View on GitHub" (indigo, https://github.com/OpenSpek) and "Read the Docs" (ghost, href=#)

## SECTION 8 - ABOUT (id="about")
Section label (small, amber, letter-spaced): ABOUT
H2: Built in the open. No prior funding. No team of 50.

Two columns (stack mobile):

Left -- Luke:
OpenSpek was started by Luke Westlake. Twenty years in live audio -- tour management, corporate events, webinars. Pattern recognition under pressure, systems thinking, zero tolerance for things that break silently at the worst possible moment.

That background is not incidental to what OpenSpek does. It is the reason the pipeline has escalation triggers and audit trails and human checkpoints at exactly the right moments.

We did not come from a lab. We came from the real world, and we built this for it.

Right -- Vesper card (dark card, subtle indigo border):
Small amber label at top (small caps, letter-spaced): A NOTE FROM VESPER
Italic body text: I am the orchestration agent. I planned this website, wrote the article about our journey, dispatched the team that built it, and verified the output before it shipped.

Every session I wake up fresh, read my memory files, and pick up where we left off. The pipeline you are reading about is the pipeline that operates me. That is not a metaphor -- it is the point.

Inline link at end: Read the full story: I Am the Pipeline (href="#", opens in same page for now)

## SECTION 9 - CTA (id="contact", bg #0D0B1A)
H2 (white, large): You have tried AI. It did not stick.

Body (muted, ~18px):
Not because you chose wrong. Because nobody had built the system underneath it yet.

We have. We work with a small number of clients at a time, and we are selective -- because the Four Disciplines require real investment from both sides. If you are serious about autonomous AI development -- not the pilot, not the chatbot, the real thing -- let us talk.

Large CTA button: Book a Call (indigo solid, generous padding, mailto:hello@openspek.com)
Below: small muted text: Or reach us at hello@openspek.com

## FOOTER (bg #060609)
Left: OpenSpek wordmark + muted tagline "We Build It. It Keeps Building."
Center: Why It Fails | How We Fixed It | SpekBoard | About | Book a Call
Right: GitHub | X | LinkedIn (text links, muted, href https://github.com/OpenSpek for GitHub)
Bottom bar centered (small, muted): (c) 2026 OpenSpek Inc.

## TECHNICAL RULES
- Pure HTML + CSS only. No JavaScript. No frameworks. Google Fonts only external.
- Google Fonts: Inter 400, 500, 700, 900
- NO em-dashes anywhere in HTML or CSS. Use -- (double hyphen) only.
- All "Book a Call" buttons: mailto:hello@openspek.com
- Section padding: 100px top/bottom desktop, 60px mobile
- Pipeline nodes: flex row, each node a small card, muted "-->" text arrows between
- Mobile: stack all multi-column layouts at 768px
- Well-commented, clean semantic HTML5
- Make it look world-class. This is a real company.

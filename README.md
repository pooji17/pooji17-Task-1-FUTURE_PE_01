AI Website Copy Generator — Prompt Engineering Task

Business chosen: Brewed Horizons Cafe, Banjara Hills, Hyderabad
Business type: Specialty coffee café & all-day brunch spot
Tool used: Claude (claude.ai)
Task: Future Interns — Prompt Engineering Task 1 (2026)


About This Project

Most local cafés lose customers not because their coffee is bad, but because their website reads like every other café website. This project demonstrates how a structured prompt framework can generate high-quality, conversion-focused website copy that feels specific to a real business — not generic AI output.

Brewed Horizons Cafe was chosen as the client business. All copy was generated using structured prompts and then refined for tone, specificity, and conversion focus.


Repository Structure

brewed-horizons-copy/
├── README.md                        ← This file
├── prompts/
│   ├── 01-homepage-hero.md          ← Homepage headline & intro prompt
│   ├── 02-service-descriptions.md   ← Service page copy prompt
│   ├── 03-cta-sections.md           ← Call-to-action prompt (3 variants)
│   └── 04-tone-adaptation.md        ← Reusable tone-switching prompt
└── outputs/
    ├── homepage-copy.md             ← Generated homepage content
    ├── services-copy.md             ← Generated services page content
    └── cta-copy.md                  ← Generated CTA sections


Prompt Logic

Each prompt follows a consistent architecture:

1. Role assignment

Every prompt opens by defining the AI's role:


"You are a professional website copywriter specialising in local businesses."



This anchors the model's output register and prevents generic responses.

2. Parameterised variables

Key variables are marked with [BRACKETS] so the same prompt can be reused for any client:


[BUSINESS_NAME] — the trading name
[BUSINESS_TYPE] — what the business actually does
[LOCATION] — city or neighbourhood
[TONE] — friendly / professional / bold
[UNIQUE FACTORS] — 2–3 real differentiators


3. Structured output format

Each prompt specifies exactly what to output — headline, sub-headline, paragraph, bullet list — so the result is ready to drop into a web builder without editing.

4. Negative constraints

Each prompt includes an "Avoid:" line to prevent the most common AI copy problems:


"world-class", "passionate team", "one-stop-shop"
Generic location references
Unsubstantiated superlatives


5. Tone guide

Prompt 4 includes an explicit tone guide that maps business types to language styles, making the system adaptable:


Friendly (café, salon) → warm, contractions, conversational
Professional (clinic, agency) → authoritative, clear, no slang
Bold (gym, fast food) → punchy, short, action-oriented



How to Reuse for Another Client


Open any prompt file in /prompts/
Replace all [BRACKET] variables with your client's details
Paste into Claude, ChatGPT, or Gemini
Copy the output into your web builder (Framer, Lovable, Webflow, etc.)


The system is designed to produce publishable copy in under 5 minutes per section.


Tools Used

PurposeToolCopy generationClaude (claude.ai)Prompt designManual framework (this repo)Web deploymentCompatible with Framer AI, LovableVersion controlGitHub


What Good Copy Does Differently

Generic AI copyThis framework's output"We are passionate about coffee""Your mornings deserve something real.""Best café in Hyderabad""Not a chain. Not a clone.""Contact us today!""Reserve your table — or just walk in.""We offer a wide range of services"Specific service descriptions with inclusions

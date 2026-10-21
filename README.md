# ToolGenX: Agent Skill Packs for Claude Code

[![Website](https://img.shields.io/badge/website-agentskillpacks.com-ff90e8?style=flat-square)](https://www.agentskillpacks.com)
[![Products](https://img.shields.io/badge/products-21-ffc900?style=flat-square)](https://www.agentskillpacks.com/products)
[![Free tools](https://img.shields.io/badge/free%20tools-13-0a0a0a?style=flat-square)](https://www.agentskillpacks.com/tools)
[![Google Site](https://img.shields.io/badge/Google%20Sites-ToolGenX-4285F4?style=flat-square)](https://sites.google.com/view/toolgenx-pages/ana-sayfa)

> **ToolGenX** is an independent shop for Claude Code skill packs, templates and toolkits at **[agentskillpacks.com](https://www.agentskillpacks.com)**. It sells 21 digital products for developers, founders and marketers, from $9 to $149, each a one-time payment with an instant download. No subscription.

This repository powers the brand's public link hub on GitHub Pages: **[ismailgunaydn.github.io/ToolgenX.github.io](https://ismailgunaydn.github.io/ToolgenX.github.io/)**. It lists every product, free tool, book, blog post and official profile, and links each one to its page on agentskillpacks.com.

## Contents

- [What is a Claude Code skill pack?](#what-is-a-claude-code-skill-pack)
- [Install a pack in 4 steps](#install-a-pack-in-4-steps)
- [Catalog](#catalog)
- [Free tools](#free-tools)
- [Platform fees on a $29 sale](#platform-fees-on-a-29-sale)
- [Books](#books)
- [Problem guides](#problem-guides)
- [Blog](#blog)
- [Documents and mirrors](#documents-and-mirrors)
- [Official links](#official-links)
- [FAQ](#faq)
- [Company](#company)

## What is a Claude Code skill pack?

A Claude Code skill pack is a set of folders, each with a `SKILL.md` file, that teach an AI coding agent repeatable jobs: auditing a page, writing a cold email sequence, planning a feature. Claude loads a skill only when the task matches it. Since December 2025 the format is an open standard ([agentskills.io](https://agentskills.io)), so Cursor, Codex, Gemini CLI and GitHub Copilot can read the same folders.

```text
~/.claude/skills/
├── seo-audit/
│   ├── SKILL.md
│   └── checklist.md
└── cold-email/
    ├── SKILL.md
    └── templates/
```

## Install a pack in 4 steps

1. Buy a pack on [agentskillpacks.com](https://www.agentskillpacks.com/products) and unzip the download.
2. Copy the skill folders into `~/.claude/skills/` (all projects) or `<repo>/.claude/skills/` (one project).
3. Restart Claude Code and type `/` to list the new skills, or just describe the task.
4. Edit the examples in each `SKILL.md` to match your stack, voice and clients.

## Catalog

21 products in 7 categories. Prices in USD, one-time payment.

### [AI Tools](https://www.agentskillpacks.com/categories/ai-tools)

| Product | Price | What it is |
|---|---:|---|
| **[Idea to App OS](https://www.agentskillpacks.com/products/idea-to-app-os)** | $149 | A seven-guide playbook written for people who have never written code, bundled with the CodeForge workflow plugin that makes Claude Code behave like a disciplined developer, a security and launch kit for the part where AI-built apps fail, and seven templates. Pro adds a written Idea Review by email; Founder adds a Pre-Launch Review and 30 days of email. |
| **[Visa Document Translator](https://www.agentskillpacks.com/products/visa-document-translator)** | $9 | A Claude Code skill that reads a photo of a visa document, birth certificate or other official paper with OCR on your computer, then has Claude translate it into a bilingual PDF: the original image first, then the translation. |

<details><summary><b>Idea to App OS</b>: key features</summary>

- Your idea on one page: seven questions that turn "an app for my clients" into a spec an AI can build from, with the exact first prompt
- Set up your AI developer: Node, Git, Claude Code, CodeForge and four accounts, step by step on Mac and Windows, with a monthly cost table
- Directing the build: the 60-minute session, one feature per session, what to say and what never to say, what "done" means
- When it breaks: fifteen stuck situations with the exact message to send, the 45-minute budget rule, the two prompts that roll back to the last working version
- The last 20 percent: login without custom code, users only seeing their own data, secrets out of the code, backups, Stripe in test mode, deploy, the pre-launch self-test
- Launch: ten people first, the three feedback questions, bugs before features, a landing page from one prompt, the one number to watch
- Run it without a developer: the monthly 30-minute health check, cost of ownership, the four cases where you hire a human and the brief that gets you a good one

**For:** Business owners, consultants and professionals with a budget who want a specific tool built and would rather direct it than learn to code  
**Ships with:** Seven guides that tell you what to say to Claude Code at every step, the CodeForge plugin (14 skills: questions before code, a plan you approve, tested steps, review, verification), three rule files, a CLAUDE.md project template, seven templates, and in Pro and Founder, written reviews of your spec and your app by email.  
**Page:** https://www.agentskillpacks.com/products/idea-to-app-os

</details>

<details><summary><b>Visa Document Translator</b>: key features</summary>

- OCR on your computer with macOS Vision, EasyOCR or Tesseract
- A bilingual PDF: the original image on page 1, the translation on page 2
- A review note format for marking unclear lines, when you ask for it
- 22 source languages, with English, Turkish, German or French as the target
- A Claude Code skill: OCR runs on your computer, the text is translated by Claude

**For:** Immigrants, expats, travelers, and international workers who need documents translated fast  
**Ships with:** A Claude Code skill with local OCR, 22 source languages, a bilingual PDF with the original image and the translation, and a guide with translator notes and a review note format.  
**Page:** https://www.agentskillpacks.com/products/visa-document-translator

</details>

### [Automation](https://www.agentskillpacks.com/categories/automation)

| Product | Price | What it is |
|---|---:|---|
| **[AutoEarnaAI](https://www.agentskillpacks.com/products/autoearnaai)** | $27 | A Python app with four automation modules: a YouTube Shorts maker, an X posting bot, an Amazon affiliate poster and a local-business outreach drafter. The text is written by a local model through Ollama; the Shorts images come from the Gemini API with your own key. |
| **[MarketFlow AI](https://www.agentskillpacks.com/products/marketflow-ai)** | $29 | A marketing automation stack of 11 systems and 42 Python scripts that connect HubSpot, GA4, Apollo, Gong and Ahrefs, covering A/B testing, content ops, lead scoring, outbound and revenue attribution. |
| **[ShortFactory AI](https://www.agentskillpacks.com/products/shortfactory-ai)** | $29 | A Python pipeline that makes YouTube Shorts: Claude writes the script, Gemini generates the images, ElevenLabs reads the voiceover, Whisper adds synced captions, and the YouTube Data API uploads each video as private. Budget about $0.25 to $0.30 per Short in API fees at October 2026 prices. |

<details><summary><b>AutoEarnaAI</b>: key features</summary>

- YouTube Shorts module: Ollama writes the script, Gemini makes the images, then voice, subtitles and upload
- An X bot that writes and posts on a schedule, one to three times a day
- An Amazon affiliate module that reads a product page, writes a pitch with your link and posts it to X
- A local-business outreach drafter that emails your own template
- A setup wizard that creates config.json, plus a preflight check that marks each part OK, WARN or FAIL
- Text drafting runs on Ollama locally, so the writing has no per-call API bill

**For:** Side hustlers, affiliate marketers and solo creators who do repetitive posting work by hand and want it automated without a subscription  
**Ships with:** One Python app with 4 automation modules, a setup wizard that creates config.json, a preflight check and the full source code. One payment, no subscription.  
**Page:** https://www.agentskillpacks.com/products/autoearnaai

</details>

<details><summary><b>MarketFlow AI</b>: key features</summary>

- 42 Python automation scripts covering the full marketing stack
- API integrations: HubSpot, GA4, Apollo, Gong and Ahrefs, each with your own keys
- Lead scoring automation: know who to call and when
- A/B testing engine, cold email sequencer, and SEO ops tools
- revenue_attribution.py: credits closed HubSpot deals to GA4 pages, with four attribution models

**For:** Marketing teams and growth leads at B2B companies using HubSpot and GA4  
**Ships with:** 11 marketing systems, 42 ready-to-run Python scripts with Claude Code skill files, platform integrations, and attribution reports that print in the terminal or save as JSON or Markdown.  
**Page:** https://www.agentskillpacks.com/products/marketflow-ai

</details>

<details><summary><b>ShortFactory AI</b>: key features</summary>

- Full pipeline: script → visuals → voiceover → captions → upload
- Claude for the script, Gemini for the images, ElevenLabs for the voice
- Word-by-word captions from Whisper that sync with the audio
- Upload through the YouTube Data API, private by default so you review first
- About $0.25 to $0.30 per Short in API fees at October 2026 list prices

**For:** Content creators and faceless channel operators who want to post daily without the grind  
**Ships with:** A complete Python pipeline with Claude scripts, Gemini images, ElevenLabs voice, Whisper captions and YouTube upload, plus a setup guide and a cost table per service.  
**Page:** https://www.agentskillpacks.com/products/shortfactory-ai

</details>

### [Business & Growth](https://www.agentskillpacks.com/categories/business-and-growth)

| Product | Price | What it is |
|---|---:|---|
| **[AI Agency Launch Kit](https://www.agentskillpacks.com/products/ai-agency-launch-kit)** | $119 | A 37-skill system that walks through every stage of starting an AI agency, finding clients, delivering work, and getting paid on retainer. |
| **[AI CFO Toolkit](https://www.agentskillpacks.com/products/ai-cfo-toolkit)** | $29 | A founder toolkit of three Claude Code skills and two Python scripts: cfo-analyzer.py reads your QuickBooks CSV or XLSX exports and prints a CFO briefing on burn, runway and margins, and scenario-modeler.py projects base, bull and bear cases saved as JSON. |
| **[B2B Growth Machine](https://www.agentskillpacks.com/products/b2b-growth-machine)** | $49 | A B2B growth pack with 7 systems and 4 skills: an outbound engine with an ICP template, sending rules and cold sequences, plus visitor routing, content, revenue attribution, A/B tests and a deal sizing playbook. Most systems are Python scripts. |
| **[Conversion Rate Domination](https://www.agentskillpacks.com/products/conversion-rate-domination)** | $29 | An 8-skill CRO suite that audits landing pages, optimizes forms and popups, sets up A/B tests, and applies marketing psychology to turn visitors into buyers. |
| **[Startup Launch Arsenal](https://www.agentskillpacks.com/products/startup-launch-arsenal)** | $39 | A 10-skill founder toolkit for Claude Code that covers pre-launch and fundraising: a skill that drafts the pitch deck in investor order, pricing strategy with the Van Westendorp questions, and a launch plan built on owned, rented and borrowed channels. |

<details><summary><b>AI Agency Launch Kit</b>: key features</summary>

- 37 Claude Code skills covering the full agency workflow
- 6-phase system: prospect, pitch, deliver, retain, upsell, scale
- Done-for-you cold email, proposal, and onboarding templates
- GEO/SEO service packages priced and ready to sell
- Lead research and outreach automation included

**For:** Freelancers and consultants building an AI-powered agency  
**Ships with:** 37 battle-tested skills, a 6-phase workflow, pricing templates, cold email sequences, and a full client delivery system.  
**Page:** https://www.agentskillpacks.com/products/ai-agency-launch-kit

</details>

<details><summary><b>AI CFO Toolkit</b>: key features</summary>

- cfo-analyzer.py: reads QuickBooks exports (CSV or XLSX) and prints a briefing on revenue, margins, costs and burn
- scenario-modeler.py: base, bull and bear projections 12 months ahead, saved as JSON
- Unit economics check (LTV, LTV to CAC, payback) in the analytics-tracking skill
- Value metrics, three tiers and the Van Westendorp questions in the pricing-strategy skill
- A green, yellow or red status per metric against thresholds you can edit

**For:** Founders and operators who need financial clarity without hiring a CFO  
**Ships with:** Three Claude Code skills (finance-ops, pricing-strategy, analytics-tracking) and two Python scripts that read your QuickBooks exports and print a CFO briefing and scenario projections. There is no spreadsheet.  
**Page:** https://www.agentskillpacks.com/products/ai-cfo-toolkit

</details>

<details><summary><b>B2B Growth Machine</b>: key features</summary>

- An ICP template with primary, secondary and excluded titles and industries
- A five-email cold sequence plan over 21 days, with written deliverability rules
- A lead pipeline script that searches Apollo, verifies emails and uploads to Instantly
- Deal scaling playbook from $1K to $100K contracts
- Revenue intelligence scripts that credit closed HubSpot deals to the pages buyers read

**For:** B2B founders, sales teams, and growth leads who need a repeatable pipeline system  
**Ships with:** 7 growth systems (mostly Python scripts), 4 skills, an ICP template, a cold sequence plan, a deal scaling playbook and revenue attribution scripts.  
**Page:** https://www.agentskillpacks.com/products/b2b-growth-machine

</details>

<details><summary><b>Conversion Rate Domination</b>: key features</summary>

- 8 CRO skills covering landing pages, forms, popups, and onboarding
- Landing page audit tool that finds where people drop off
- A/B test setup for any element, no developer needed
- Marketing psychology principles baked into every optimization
- Funnel analysis from first click to checkout

**For:** E-commerce owners, SaaS founders, and marketers with traffic but weak conversion rates  
**Ships with:** 8 CRO skills, landing page audit templates, A/B testing workflows, and a marketing psychology playbook.  
**Page:** https://www.agentskillpacks.com/products/conversion-rate-domination

</details>

<details><summary><b>Startup Launch Arsenal</b>: key features</summary>

- 10 founder skills covering pitch, pricing, and launch strategy
- investor-materials: drafts a 10-slide deck from problem to ask, from your own facts
- pricing-strategy: value metrics, three tiers and the four Van Westendorp questions
- A five-phase launch plan using owned, rented and borrowed channels, plus a pre-launch checklist
- From napkin idea to investor-ready in one structured system

**For:** Early-stage founders who need to pitch investors, price their product, and execute a launch  
**Ships with:** 10 Claude Code founder skills: pitch deck and investor materials, investor outreach, market research, pricing with the Van Westendorp questions, and a launch plan and checklist.  
**Page:** https://www.agentskillpacks.com/products/startup-launch-arsenal

</details>

### [Content & Writing](https://www.agentskillpacks.com/categories/content-and-writing)

| Product | Price | What it is |
|---|---:|---|
| **[AI Content Blueprint](https://www.agentskillpacks.com/products/ai-content-blueprint)** | $29 | A 14-section article framework built for AI search. Covers structure, quick-answer boxes, FAQ schema, and how to write content that gets pulled into AI answers. |
| **[AI Content Empire Builder](https://www.agentskillpacks.com/products/ai-content-empire-builder)** | $29 | An 8-skill content multiplication system that turns one piece of content into social posts, threads, newsletters, and more, without writing everything separately. |
| **[Humanizer Pro](https://www.agentskillpacks.com/products/humanizer-pro)** | $19 | A 3-skill writing pack for Claude Code: a humanizer that strips AI writing patterns and banned phrases and can match your voice, plus a copy editor and a copywriter. It makes the writing better; it does not promise any AI detector score. |
| **[Podcast to Empire Kit](https://www.agentskillpacks.com/products/podcast-to-empire-kit)** | $29 | A 5-skill content multiplication system that turns one podcast episode into 12 content pieces, Twitter threads, LinkedIn posts, newsletters, blog posts, and short clips, automatically. |

<details><summary><b>AI Content Blueprint</b>: key features</summary>

- 14-section article framework for Google and AI search
- Quick answer box formula that gets picked up by ChatGPT and Perplexity
- FAQ schema setup that triggers rich results
- Blog writer skill for Claude Code, fully automated
- Step-by-step guide to writing content AI engines actually cite

**For:** Bloggers, content marketers, and SEO writers who want both Google and AI search traffic  
**Ships with:** 14-section content framework, quick-answer box templates, FAQ schema blueprints, and a blog writer skill for Claude Code.  
**Page:** https://www.agentskillpacks.com/products/ai-content-blueprint

</details>

<details><summary><b>AI Content Empire Builder</b>: key features</summary>

- 8 production-ready skills for content creation and repurposing
- Content calendar system: one piece becomes a week of posts
- AI humanizer that removes robotic tone from AI writing
- Twitter/X algorithm optimizer for more reach with less effort
- Works with Claude Code, no extra subscriptions needed

**For:** Content creators and solo founders who need to show up consistently but are running out of time  
**Ships with:** 8 Claude Code skills, a content repurposing calendar, AI humanizer, and platform-specific optimizers.  
**Page:** https://www.agentskillpacks.com/products/ai-content-empire-builder

</details>

<details><summary><b>Humanizer Pro</b>: key features</summary>

- A written list of banned AI phrases plus structural patterns, such as lists of three
- Voice matching from a sample of 200 or more words of your own writing
- A report of detected issues, then the rewrite with every change highlighted
- Works on blog posts, emails, LinkedIn, sales copy, and more
- 3 skills: humanizer, copy editor, and copywriter in one pack

**For:** Writers, agency owners, and content marketers who draft with AI and need it to read like a person wrote it  
**Ships with:** 3 writing skills (humanizer, copy editor, copywriter), a banned phrase and pattern list, voice matching, and a rewrite with the changes highlighted.  
**Page:** https://www.agentskillpacks.com/products/humanizer-pro

</details>

<details><summary><b>Podcast to Empire Kit</b>: key features</summary>

- One episode becomes 12 content pieces across 6 platforms
- Weekly content calendar fully mapped from one recording
- Guest workflow with co-promotion and cross-distribution
- Twitter threads, LinkedIn posts, newsletter, blog post, auto-generated
- 5 skills covering every part of podcast content operations

**For:** Podcasters who want more reach without recording more episodes  
**Ships with:** 5 content production skills, a 12-format content system, a weekly calendar template, and a guest episode workflow.  
**Page:** https://www.agentskillpacks.com/products/podcast-to-empire-kit

</details>

### [Design & UI](https://www.agentskillpacks.com/categories/design-and-ui)

| Product | Price | What it is |
|---|---:|---|
| **[iOS Liquid Glass UI Kit](https://www.agentskillpacks.com/products/ios-liquid-glass-ui-kit)** | $29 | A 5-skill Claude Code kit for the iOS 26 Liquid Glass look: SwiftUI, UIKit and WidgetKit glass patterns, morphing and container examples, an accessibility checklist, and a CSS backdrop-filter version for the web. The code ships as samples inside the skill files and README. |

<details><summary><b>iOS Liquid Glass UI Kit</b>: key features</summary>

- The liquid-glass-design skill: SwiftUI, UIKit and WidgetKit glass patterns
- SwiftUI samples for glassEffect, glass button styles and GlassEffectContainer
- UIKit samples for UIGlassEffect and UIGlassContainerEffect
- A CSS backdrop-filter web version, plus Tailwind and shadcn patterns
- A Reduce Transparency fallback and a contrast checklist
- Four more skills: UI rules, styling, design tokens and brand design

**For:** iOS developers, web developers, and UI designers who need to adopt the new iOS 26 design language  
**Ships with:** 5 Claude Code skills with SwiftUI, UIKit and WidgetKit Liquid Glass code samples, plus a README with a CSS web version, an accessibility checklist and performance notes. No Figma files or separate Swift files.  
**Page:** https://www.agentskillpacks.com/products/ios-liquid-glass-ui-kit

</details>

### [Developer Tools](https://www.agentskillpacks.com/categories/developer-tools)

| Product | Price | What it is |
|---|---:|---|
| **[CodeForge](https://www.agentskillpacks.com/products/codeforge)** | $19 | A 14-skill Claude Code plugin for planning, TDD, code review, debugging, verification and git worktrees, with adapter files for Cursor, Codex, OpenCode and Gemini CLI. |
| **[Indie Game Studio Kit](https://www.agentskillpacks.com/products/indie-game-studio-kit)** | $39 | A 27-agent Claude Code kit that gives solo indie devs specialist helpers for design, programming, narrative, audio and game economy, with separate engine specialists for Godot 4, Unity 6 and Unreal 5. |

<details><summary><b>CodeForge</b>: key features</summary>

- 14 dev workflow skills for Claude Code
- TDD workflow: red-green-refactor with subagent support
- Planning and brainstorming system before you write a single line
- Git worktrees integration for parallel development branches
- A Claude Code plugin, with adapter files for Cursor, Codex, OpenCode and Gemini CLI

**For:** Developers who use AI coding tools but feel they are not getting the most out of them  
**Ships with:** A Claude Code plugin with 14 skills, one review agent and session-start hooks: planning, a TDD workflow, code review, verification and a git worktree skill.  
**Page:** https://www.agentskillpacks.com/products/codeforge

</details>

<details><summary><b>Indie Game Studio Kit</b>: key features</summary>

- 27 specialist AI agents covering every game dev discipline
- Godot, Unity, and Unreal Engine specialist agents included
- Narrative director, economy designer, and audio director agents
- A README with example prompts and a step-by-step order for running several agents on one feature
- Built for solo devs who want studio-quality output without a studio

**For:** Solo indie game developers who want to build bigger games without hiring a team  
**Ships with:** 27 specialist agent files for Claude Code, including 14 engine specialists for Godot 4, Unity 6 and Unreal 5, a model already set in each file, and a README with example prompts.  
**Page:** https://www.agentskillpacks.com/products/indie-game-studio-kit

</details>

### [SEO & Visibility](https://www.agentskillpacks.com/categories/seo-and-visibility)

| Product | Price | What it is |
|---|---:|---|
| **[AI SEO Agency OS](https://www.agentskillpacks.com/products/ai-seo-agency-os)** | $149 | A 41-skill AI SEO toolkit for Claude Code bundled with the operating layer that turns it into paying clients: a 7-day plan, three priced packages, outreach scripts, a 20-minute sales conversation, a 48-hour delivery SOP and six templates. The Pro edition adds a written review of your first paid audit and 30 days of email. |
| **[AI SEO Command Suite](https://www.agentskillpacks.com/products/ai-seo-command-suite)** | $69 | A 30-skill SEO command system for Claude Code covering keyword research, competitor analysis, content gaps, schema generation, and GEO optimization in one toolkit. |
| **[AI Search Visibility Toolkit](https://www.agentskillpacks.com/products/ai-search-visibility-toolkit)** | $49 | An 11-skill GEO (Generative Engine Optimization) system that audits, scores, and fixes your site so AI search engines find, trust, and cite your content. |
| **[Structured Data Pro Pack](https://www.agentskillpacks.com/products/structured-data-pro-pack)** | $19 | A pack of six JSON-LD templates (Article with author, LocalBusiness, Organization, Product, SaaS and WebSite), two Claude Code skills, schema-markup and geo-schema, and a schema_validator.py script that scores each block on required and recommended fields. |

<details><summary><b>AI SEO Agency OS</b>: key features</summary>

- Day 1 to 7: pick a niche, audit your own site, build a list of 20 prospects with one checkable fact each, send, handle replies, deliver
- Three packages written out with price bands: AI Visibility Diagnostic, Complete AI Search Audit, GEO + SEO retainer
- Outreach scripts built around one line: "I asked ChatGPT for the best [category] in [city]. It named your competitors. It did not name you."
- The 20-minute sales conversation minute by minute, a written-only variant for prospects who never take calls, and an objection table
- Delivery SOP from payment to PDF in 48 hours: command sequence, the prompt that ranks the 10 fixes, a QA gate
- Templates: proposal, scope of work, kickoff questionnaire, report cover email, monthly report, audit QA checklist
- From the first audit to a retainer: the one question that opens it, the 90-day plan, when to raise prices

**For:** Freelancers, SEO consultants and small agencies who can run an AI visibility audit and have not sold one yet  
**Ships with:** 41 Claude Code skills (11 GEO, 20 SEO, 3 content, 7 agency), 5 agents, 6 JSON-LD templates, and the seven-part playbook that takes a cold prospect to a delivered audit and a monthly retainer.  
**Page:** https://www.agentskillpacks.com/products/ai-seo-agency-os

</details>

<details><summary><b>AI SEO Command Suite</b>: key features</summary>

- 30 Claude Code skills covering the full SEO workflow
- Keyword research, SERP analysis, and content gap finder
- Competitor audit showing what they rank for that you do not
- Schema markup templates for rich results and AI citation
- GEO and traditional SEO combined into one command system

**For:** SEO professionals, agency owners, and developers who want to automate SEO work  
**Ships with:** 30 production-ready SEO skills, keyword research templates, competitor analysis workflows, and a full schema library.  
**Page:** https://www.agentskillpacks.com/products/ai-seo-command-suite

</details>

<details><summary><b>AI Search Visibility Toolkit</b>: key features</summary>

- Full GEO audit scoring your site across 11 AI visibility factors
- llms.txt setup so AI crawlers can read your site
- Client-ready PDF report generator for agencies
- Citation audit, see where AI engines stand on your content
- Works with ChatGPT, Perplexity, Google AI Overviews, and Gemini

**For:** SEO professionals, agency owners, and business owners who want AI search traffic  
**Ships with:** 11 GEO audit skills, an llms.txt template, citation scoring system, and a client-ready PDF report generator.  
**Page:** https://www.agentskillpacks.com/products/ai-search-visibility-toolkit

</details>

<details><summary><b>Structured Data Pro Pack</b>: key features</summary>

- 6 JSON-LD templates: Article with author, LocalBusiness, Organization, Product, SaaS and WebSite
- 2 Claude Code skills: schema-markup to audit and draft, geo-schema for entity markup aimed at AI search
- schema_validator.py: pulls each JSON-LD block from a saved page and scores it from 0 to 100
- SpeakableSpecification in the Article template
- A field guide that lists the required and recommended fields for each type
- Plain JSON-LD you paste into any page head or CMS custom code field

**For:** SEO practitioners, developers, and site owners who want valid schema markup without guessing at the syntax  
**Ships with:** Six JSON-LD templates, two Claude Code skills (schema-markup and geo-schema), the schema_validator.py script, and two reference guides: when to use which type, and implementation patterns.  
**Page:** https://www.agentskillpacks.com/products/structured-data-pro-pack

</details>

## Free tools

Free, in the browser, no signup and no email.

| Tool | What it does |
|---|---|
| [Gumroad Fee Calculator](https://www.agentskillpacks.com/gumroad-fee-calculator) | Itemizes Gumroad transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [Stripe Fee Calculator](https://www.agentskillpacks.com/stripe-fee-calculator) | Itemizes Stripe transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [PayPal Fee Calculator](https://www.agentskillpacks.com/paypal-fee-calculator) | Itemizes PayPal transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [Lemon Squeezy Fee Calculator](https://www.agentskillpacks.com/lemon-squeezy-fee-calculator) | Itemizes Lemon Squeezy transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [Payhip Fee Calculator](https://www.agentskillpacks.com/payhip-fee-calculator) | Itemizes Payhip transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [Etsy (digital downloads) Fee Calculator](https://www.agentskillpacks.com/etsy-fee-calculator) | Itemizes Etsy (digital downloads) transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [Ko-fi Fee Calculator](https://www.agentskillpacks.com/ko-fi-fee-calculator) | Itemizes Ko-fi transaction fees, card processing cuts, merchant-of-record costs, and net payouts. |
| [Refund Policy Generator](https://www.agentskillpacks.com/refund-policy-generator) | Writes a digital-products refund and withdrawal policy with EU CRD Art 16(m) dual-consent wording, the withdrawal button required by Directive (EU) 2023/2673 from 19 June 2026, and UK and Türkiye addenda. Runs in the browser. |
| [AI Crawler Checker](https://www.agentskillpacks.com/ai-crawler-checker) | Tests any domain's robots.txt against 12 AI crawlers (GPTBot, OAI-SearchBot, ChatGPT-User, ClaudeBot, Claude-User, PerplexityBot, Perplexity-User, Google-Extended, CCBot, Bytespider, meta-externalagent, Applebot-Extended) and shows the rule that matched. |
| [llms.txt Generator](https://www.agentskillpacks.com/llms-txt-generator) | Builds an llms.txt file in the llmstxt.org format with live structural validation, fully client-side. |
| [AI Writing Checker](https://www.agentskillpacks.com/ai-writing-checker) | Flags 5 measurable AI writing tells with exact positions: em-dash density over 4 per 1,000 words, 26 stock phrases, rule-of-three padding, sentence-length variation under 35%, and missing first-person voice. A style checker, not an AI detector. |
| [Digital Product Pricing Calculator](https://www.agentskillpacks.com/digital-product-pricing-calculator) | Suggests a floor / anchor / premium price band from product type, audience and depth, then models monthly revenue at 0.5%, 1% and 2% conversion after platform fees. |
| [Platform Fee Comparison](https://www.agentskillpacks.com/platform-fee-comparison) | One sale price across 7 platforms and 13 fee variants, sorted by net payout. |

## Platform fees on a $29 sale

On a $29 digital download the seller keeps $20.30 to $27.86. Stripe leaves the most but you file VAT and sales tax yourself; merchant-of-record platforms (Gumroad, Lemon Squeezy, Payhip) cost more and handle tax.

| Platform | You keep | Lost to fees |
|---|---:|---:|
| Stripe | $27.86 | $1.14 (4%) |
| Lemon Squeezy | $27.05 | $1.95 (7%) |
| Payhip (free plan) | $26.41 | $2.59 (9%) |
| Etsy | $25.79 | $3.21 (11%) |
| Gumroad (direct) | $24.46 | $4.54 (16%) |
| Gumroad (Discover) | $20.30 | $8.70 (30%) |

| Platform | Base fee | Extra | Notes |
|---|---|---|---|
| [Gumroad (direct sale)](https://www.agentskillpacks.com/gumroad-fee-calculator) | 10% + $0.50 | + 2.9% + $0.30 card processing | Merchant of record; Discover marketplace sales pay a flat 30% |
| [Stripe](https://www.agentskillpacks.com/stripe-fee-calculator) | 2.9% + $0.30 | +1.5% international cards, +1% currency conversion | Not a merchant of record: you handle VAT/sales tax |
| [PayPal](https://www.agentskillpacks.com/paypal-fee-calculator) | 3.49% + $0.49 | +1.5% cross-border | Micropayments rate 4.99% + $0.09 wins under ~$26 |
| [Lemon Squeezy](https://www.agentskillpacks.com/lemon-squeezy-fee-calculator) | 5% + $0.50 | All-inclusive | Merchant of record; the ~2 point premium over Stripe buys VAT compliance |
| [Payhip](https://www.agentskillpacks.com/payhip-fee-calculator) | 5% / 2% / 0% by plan | + payment processing | Plus pays for itself at $967/month, Pro at $3,500/month over Plus |
| [Etsy (digital downloads)](https://www.agentskillpacks.com/etsy-fee-calculator) | $0.20 listing + 6.5% transaction | + 3% + $0.25 processing | Offsite Ads add 12-15%; a $3.99 printable loses ~21% to fees |
| [Ko-fi](https://www.agentskillpacks.com/ko-fi-fee-calculator) | 5% shop fee (free tier) | 0% on donations | Ko-fi Gold is $12/month for new members, breaks even at $240/month in shop sales |

Source: calculator pages on agentskillpacks.com, verified September 2026. Live numbers: [platform fee comparison](https://www.agentskillpacks.com/platform-fee-comparison).

## Books

18 books by İsmail Günaydın. The Solo Operator Series:

1. **[The Leverage Stack](https://www.amazon.com/dp/B0H6MP1WG9)**: How One Person Runs What Used to Take a Team. [Book page](https://www.agentskillpacks.com/books/the-leverage-stack)
2. **[Found by AI](https://www.amazon.com/dp/B0H6MZH5WJ)**: How Small Businesses Get Recommended by ChatGPT, Claude, Perplexity, and Google AI. [Book page](https://www.agentskillpacks.com/books/found-by-ai)
3. **[The One-Person Million](https://www.amazon.com/dp/B0H6N47FZ8)**: Build a Real Business With AI Doing the Work. [Book page](https://www.agentskillpacks.com/books/the-one-person-million)
4. **[The Unfair Solopreneur](https://www.amazon.com/dp/B0H6MJJ93J)**: Compete With Companies 100x Your Size Using AI. [Book page](https://www.agentskillpacks.com/books/the-unfair-solopreneur)
5. **[AI Won’t Run Your Business. You Will.](https://www.amazon.com/dp/B0H6NGWHP7)**: Judgment and Doubt in the AI Age. [Book page](https://www.agentskillpacks.com/books/ai-wont-run-your-business)

More books:

- [Claude Code for Non-Programmers](https://www.amazon.com/dp/B0HN6WSTMG): A Business Owner's Guide to Building Your Own AI Operating System (2027 Edition) ([book page](https://www.agentskillpacks.com/books/claude-code-for-non-programmers))
- [From Zero to Sustainable Startup](https://a.co/d/0ejzri2t): Building a business that survives its first year
- [Businesses Are Positive-Sum Games](https://a.co/d/01TpQiVn): Scaling through coopetition instead of war
- [Startup Spells: Loopholes & Leverage](https://a.co/d/01yslc6y): Growth tactics for founders without budgets
- [The Startup Exploit](https://a.co/d/08v5oO0O): Traction and speed for early-stage products
- [The Million Dollar Launch Manual](https://a.co/d/06Ut7UEz): Launch mechanics, step by step
- [SEO Content, Rebuilt](https://a.co/d/0d459Dzm): Data-driven SEO content in the AI era
- [The Bottom-of-Funnel SEO + LLM Cost Hacker's Guide](https://a.co/d/0aDjd1UD): Enterprise SEO meets AI cost optimization
- [Reverse-Engineered Newsletters: The $10K/Month Blueprint](https://a.co/d/02SMC5NQ): Newsletter business models, taken apart
- [Wealth Rewired: Escape the System. Build Real Freedom](https://a.co/d/08zjZxvS): Rethinking money as a freedom budget
- [No Borders, No Boss: How to Design a Life of Freedom](https://a.co/d/0006aBga): Remote work and location independence
- [Break Then Build](https://a.co/d/03JjoaHy): Rebuilding after a failed project or career reset
- [Don't Click That!](https://a.co/d/0gser3n7): Recognizing online scams before they cost you

**Recommended reads.** We earn from these sales.

- [Mental Models That Actually Work](https://www.agentskillpacks.com/books/mental-models-that-actually-work): 40 Thinking Tools from Munger, Bezos, Feynman, and Kahneman, Tested Against the Evidence, for Clearer Thinking and Better Decisions ([Amazon](https://www.amazon.com/dp/B0HKYJRWMN))
- [The Genius Lab](https://www.agentskillpacks.com/books/the-genius-lab): 50 Thought Experiments and Mind Drills from Einstein, Feynman, Darwin, and Da Vinci, With What the Science Actually Says ([Amazon](https://www.amazon.com/dp/B0HM1VL1BD))
- [The Manipulator's Phrasebook](https://www.agentskillpacks.com/books/the-manipulators-phrasebook): What They Say, What It Really Means, and What to Say Back at Work, With Friends, and in Love ([Amazon](https://www.amazon.com/dp/B0HLGZ6XHL))
- [The 20-Minute Couples Workbook](https://www.agentskillpacks.com/books/the-20-minute-couples-workbook): Talk, Listen, and Reconnect Without a Therapist, Even If Your Partner Is Skeptical ([Amazon](https://www.amazon.com/dp/B0HMNVHF9W))
- [The Year You Turn 65](https://www.agentskillpacks.com/books/the-year-you-turn-65): The Medicare and Social Security Calendar, Month by Month ([Amazon](https://www.amazon.com/dp/B0HLB95HY6))
- [The Year You Retire](https://www.agentskillpacks.com/books/the-year-you-retire): A Woman's Guide to the Retirement Dates, Rules, and Benefits Nobody Hands You ([Amazon](https://www.amazon.com/dp/B0HKN1ZQJZ))
- [The Year You Arrived](https://www.agentskillpacks.com/books/the-year-you-arrived-1957): 1957: A 70th Birthday Book of Real Prices, Headlines and Everyday Life, From the World You Were Born Into to the One You Grew Up In ([Amazon](https://www.amazon.com/dp/B0HKKKKP1R))
- [Classic Chair Tai Chi for Seniors](https://www.agentskillpacks.com/books/classic-chair-tai-chi-for-seniors): 30 Gentle Chair Moves From the Traditional Tai Chi Form and the Eight Brocades, in Large Print With Clear Step-by-Step Pictures, and What the Research Really Says ([Amazon](https://www.amazon.com/dp/B0HMNT43W5))

## Problem guides

117 free guides at agentskillpacks.com/guides. Each answers one real question in its first paragraph, then points to the book chapter that covers it.

### [The Leverage Stack](https://www.agentskillpacks.com/books/the-leverage-stack) (10)

- [Should I automate this task, delegate it to AI, or just stop doing it?](https://www.agentskillpacks.com/guides/automate-or-delegate-a-task)
- [My business stops when I take a day off. What can I set up before I go?](https://www.agentskillpacks.com/guides/business-stops-when-i-take-a-day-off)
- [Why do ChatGPT emails sound generic? A one-line prompt vs a real brief](https://www.agentskillpacks.com/guides/chatgpt-emails-sound-generic)
- [I'm a freelancer drowning in client emails. What do I do this morning?](https://www.agentskillpacks.com/guides/freelancer-drowning-in-client-emails)
- [I automated my admin, but I keep checking if it actually ran. Is that normal?](https://www.agentskillpacks.com/guides/keep-checking-if-my-automations-ran)
- [You run a one-person business and you can't keep up. Here is what is actually broken.](https://www.agentskillpacks.com/guides/one-person-business-cant-keep-up)
- [How to stop checking everything AI writes: what to check, what to skip](https://www.agentskillpacks.com/guides/stop-checking-everything-ai-writes)
- [Too much admin as a one-person business: where to start, and in what order](https://www.agentskillpacks.com/guides/too-much-admin-where-to-start)
- [How do I turn ChatGPT into a daily routine instead of something I use now and then?](https://www.agentskillpacks.com/guides/turn-chatgpt-into-a-daily-routine)
- [If AI does most of my work, what is left of me? What should I never hand to AI?](https://www.agentskillpacks.com/guides/what-work-should-i-never-hand-to-ai)

### [Found by AI](https://www.agentskillpacks.com/books/found-by-ai) (9)

- [ChatGPT describes my business wrong, or can't say what I do. Is it me?](https://www.agentskillpacks.com/guides/chatgpt-describes-my-business-wrong)
- [ChatGPT doesn't recommend my business. It names three others instead. Why?](https://www.agentskillpacks.com/guides/chatgpt-doesnt-recommend-my-business)
- [GEO vs SEO: what is the difference, and which one does a small business need?](https://www.agentskillpacks.com/guides/geo-vs-seo-whats-the-difference)
- [How does ChatGPT decide which business to recommend? The five checks, in order](https://www.agentskillpacks.com/guides/how-ai-decides-which-business-to-recommend)
- [How to get your website quoted in ChatGPT, Perplexity and Google AI answers](https://www.agentskillpacks.com/guides/how-to-get-quoted-in-ai-answers)
- [Is SEO dead now that people ask ChatGPT instead of Google?](https://www.agentskillpacks.com/guides/is-seo-dead-because-of-ai)
- [Why isn't my local business showing up when people ask AI for someone near them?](https://www.agentskillpacks.com/guides/local-business-not-showing-in-ai-answers)
- [My robots.txt is blocking GPTBot and other AI crawlers. How do I fix it fast?](https://www.agentskillpacks.com/guides/robots-txt-blocking-ai-crawlers)
- [My website traffic dropped after Google AI Overviews started. What do I do this week?](https://www.agentskillpacks.com/guides/website-traffic-dropped-after-ai-overviews)

### [The One-Person Million](https://www.agentskillpacks.com/books/the-one-person-million) (8)

- [A client said your quote is too low. How do you raise your price on the next one?](https://www.agentskillpacks.com/guides/client-said-my-quote-is-too-low)
- [You bill by the hour, you are fully booked, and your freelance income stopped growing](https://www.agentskillpacks.com/guides/hourly-freelance-income-stopped-growing)
- [How to productize a service when you are the only one doing the work](https://www.agentskillpacks.com/guides/how-to-productize-a-service)
- [Is a one-person million-dollar business realistic, or is it just a story people sell?](https://www.agentskillpacks.com/guides/is-a-one-person-million-dollar-business-realistic)
- [Too many orders to deliver alone? Before you hire help, do this](https://www.agentskillpacks.com/guides/too-many-orders-to-deliver-alone)
- [Value-based pricing vs hourly: which one should a freelancer use?](https://www.agentskillpacks.com/guides/value-based-pricing-vs-hourly)
- [Which parts of client work can AI deliver, and which parts must stay yours?](https://www.agentskillpacks.com/guides/what-ai-should-deliver-in-client-work)
- [What to sell after your first digital product, so the second one sells the first](https://www.agentskillpacks.com/guides/what-to-sell-after-your-first-digital-product)

### [The Unfair Solopreneur](https://www.agentskillpacks.com/books/the-unfair-solopreneur) (8)

- [Can a small business compete with big companies? Here is where to start.](https://www.agentskillpacks.com/guides/can-a-small-business-compete-with-big-companies)
- [You keep losing clients to bigger companies. Is it really their budget?](https://www.agentskillpacks.com/guides/keep-losing-clients-to-bigger-companies)
- [You just lost a client to a bigger agency. Here is what to do this week.](https://www.agentskillpacks.com/guides/lost-a-client-to-a-bigger-agency)
- [Can one person really do a marketing department's work alone with AI?](https://www.agentskillpacks.com/guides/marketing-department-work-alone-with-ai)
- [How to pick a niche too small for big companies but big enough for you](https://www.agentskillpacks.com/guides/niche-too-small-for-big-companies)
- [Should a small business sound bigger, or say it's just you?](https://www.agentskillpacks.com/guides/should-a-small-business-sound-bigger)
- [Small business vs big company: who has the advantage, and where?](https://www.agentskillpacks.com/guides/small-business-vs-big-company-advantages)
- [How a small business can use speed to beat bigger competitors](https://www.agentskillpacks.com/guides/use-speed-to-beat-bigger-competitors)

### [AI Won't Run Your Business. You Will.](https://www.agentskillpacks.com/books) (8)

- [AI gave a confidently wrong answer and it went to a client. Here is what to do now.](https://www.agentskillpacks.com/guides/ai-wrong-answer-went-to-client)
- [Automation bias explained simply: why you go along with the AI even when you know better](https://www.agentskillpacks.com/guides/automation-bias-explained-simply)
- [Can I trust ChatGPT for business decisions, or only for advice?](https://www.agentskillpacks.com/guides/can-i-trust-chatgpt-for-business-decisions)
- [The client deliverable is due in an hour and AI wrote most of it. How do you check it fast?](https://www.agentskillpacks.com/guides/check-ai-work-before-sending-to-client)
- [You feel dumber, or less sure of yourself, since you started relying on AI. You are not imagining it.](https://www.agentskillpacks.com/guides/feel-dumber-after-relying-on-ai)
- [You keep asking ChatGPT if a business decision is right, just to make the doubt stop](https://www.agentskillpacks.com/guides/using-chatgpt-to-calm-business-doubt)
- [What not to hand to AI in your business, and what you can give it freely](https://www.agentskillpacks.com/guides/what-not-to-hand-to-ai)
- [When to overrule AI: the signs its confident answer is wrong for your business](https://www.agentskillpacks.com/guides/when-to-overrule-ai)

### [Claude Code for Non-Programmers](https://www.agentskillpacks.com/books/claude-code-for-non-programmers) (10)

- [The AI agent's report looks perfect. Should you trust it before you act?](https://www.agentskillpacks.com/guides/check-ai-agent-report-before-acting)
- [Claude Code changed files it shouldn't have. What to do right now](https://www.agentskillpacks.com/guides/claude-code-changed-files-it-shouldnt-have)
- [Claude Code forgets everything each session. How do you make it remember?](https://www.agentskillpacks.com/guides/claude-code-forgets-everything-each-session)
- [Claude Code vs the Claude chat window: which one should you use for your business?](https://www.agentskillpacks.com/guides/claude-code-vs-claude-chat)
- [How to write a CLAUDE.md file for a small business, even if you don't code](https://www.agentskillpacks.com/guides/claude-md-for-a-small-business)
- [Can you paste an API key or client data into Claude Code? Where secrets go instead](https://www.agentskillpacks.com/guides/keep-api-keys-and-client-data-out-of-ai)
- [How to make Claude Code ask before it changes your files](https://www.agentskillpacks.com/guides/make-claude-code-ask-before-changing-files)
- [How to run Claude Code on a schedule, and know the job actually ran](https://www.agentskillpacks.com/guides/run-claude-code-on-a-schedule)
- [Scared of the terminal? Here is why one wrong key won't break your computer](https://www.agentskillpacks.com/guides/scared-of-the-terminal)
- [What is Claude Code, and can you use it if you don't write code?](https://www.agentskillpacks.com/guides/what-is-claude-code-for-non-coders)

### [Mental Models That Actually Work](https://www.agentskillpacks.com/books/mental-models-that-actually-work) (8)

- [First principles thinking explained simply, with a way to try it today](https://www.agentskillpacks.com/guides/first-principles-thinking-explained-simply)
- [How to keep a decision journal: what to write, and when to look back](https://www.agentskillpacks.com/guides/how-to-keep-a-decision-journal)
- [How to make better decisions when you keep making the same kind of bad call](https://www.agentskillpacks.com/guides/how-to-make-better-decisions)
- [The plan launches soon. Here is how to run a pre-mortem in 20 minutes](https://www.agentskillpacks.com/guides/how-to-run-a-pre-mortem)
- [One-way vs two-way door decisions: which kind is the choice in front of you?](https://www.agentskillpacks.com/guides/one-way-vs-two-way-door-decisions)
- [You keep overthinking a big decision. Is something wrong with you?](https://www.agentskillpacks.com/guides/overthinking-a-big-decision)
- [Should you quit after investing so much? The sunk cost question, asked plainly](https://www.agentskillpacks.com/guides/should-i-quit-after-investing-so-much)
- [Which mental models actually work, and which are just famous quotes?](https://www.agentskillpacks.com/guides/which-mental-models-actually-work)

### [The Genius Lab](https://www.agentskillpacks.com/books/the-genius-lab) (8)

- [Do brain supplements work? Thirteen popular ones checked against the human evidence](https://www.agentskillpacks.com/guides/do-brain-supplements-work)
- [Do brain training games work, or do you just get better at the game?](https://www.agentskillpacks.com/guides/do-brain-training-games-work)
- [The Edison nap: how to catch ideas at the edge of sleep, and when to stop](https://www.agentskillpacks.com/guides/edison-nap-ideas-at-the-edge-of-sleep)
- [You read it three times and still can't explain it. The Feynman technique, done properly.](https://www.agentskillpacks.com/guides/feynman-technique-explain-it-simply)
- [How to build a memory palace when you have never tried one before](https://www.agentskillpacks.com/guides/how-to-build-a-memory-palace)
- [How to think like Einstein: what he really did, and the parts the internet made up](https://www.agentskillpacks.com/guides/how-to-think-like-einstein)
- [Stuck on a problem and your brain has stopped working? Do this in the next hour.](https://www.agentskillpacks.com/guides/stuck-on-a-problem-cant-think)
- [Thought experiments for adults: how to start using them on real problems](https://www.agentskillpacks.com/guides/thought-experiments-for-adults)

### [The Manipulator's Phrasebook](https://www.agentskillpacks.com/books/the-manipulators-phrasebook) (8)

- [A client uses urgency and guilt to get free work. Here are the rules and the words.](https://www.agentskillpacks.com/guides/client-uses-urgency-and-guilt-for-free-work)
- [A coworker keeps taking credit for my work. Is it petty to say something?](https://www.agentskillpacks.com/guides/coworker-taking-credit-for-my-work)
- [DARVO explained simply: why you raise a problem and end up apologizing](https://www.agentskillpacks.com/guides/darvo-explained-simply)
- [Guilt-tripping family at the holidays: what they say, what it does, and what to say back](https://www.agentskillpacks.com/guides/guilt-tripping-family-at-holidays)
- ["I'm only saying this because I care": what that phrase and others like it really mean](https://www.agentskillpacks.com/guides/im-only-saying-this-because-i-care)
- [Is my boss manipulating me, or am I reading too much into it?](https://www.agentskillpacks.com/guides/is-my-boss-manipulating-me)
- [Love bombing or real interest? How to tell the difference in the first few weeks](https://www.agentskillpacks.com/guides/love-bombing-or-real-interest)
- [What to say when someone gaslights you, right now, in the middle of it](https://www.agentskillpacks.com/guides/what-to-say-when-someone-gaslights-you)

### [The 20-Minute Couples Workbook](https://www.agentskillpacks.com/books/the-20-minute-couples-workbook) (8)

- [You bought something to work on your relationship. How to ask a skeptical partner to try it.](https://www.agentskillpacks.com/guides/ask-skeptical-partner-to-work-on-relationship)
- [Couples workbook or couples therapy: which one fits where you are right now?](https://www.agentskillpacks.com/guides/couples-workbook-vs-couples-therapy)
- [The fight is getting too heated right now. How to take a break that actually helps.](https://www.agentskillpacks.com/guides/fight-too-heated-how-to-take-a-break)
- [Your partner won't go to couples therapy. What you can do instead.](https://www.agentskillpacks.com/guides/partner-wont-go-to-couples-therapy)
- [Questions to ask your partner to reconnect, and how to ask them so they work](https://www.agentskillpacks.com/guides/questions-to-ask-your-partner-to-reconnect)
- [How to bring up a hard conversation with your partner without starting a fight](https://www.agentskillpacks.com/guides/start-hard-conversation-without-a-fight)
- [You and your partner don't really talk anymore. Is that normal, and how do you start again?](https://www.agentskillpacks.com/guides/we-dont-talk-anymore)
- [You keep having the same fight with your partner. Here is why it never ends.](https://www.agentskillpacks.com/guides/we-keep-having-the-same-fight)

### [The Year You Turn 65](https://www.agentskillpacks.com/books/the-year-you-turn-65) (8)

- [When to stop HSA contributions before Medicare: the six months that reach backward](https://www.agentskillpacks.com/guides/hsa-contributions-before-medicare)
- [Your Medicare premium letter says you owe more because of income you no longer have](https://www.agentskillpacks.com/guides/irmaa-letter-medicare-premium-too-high)
- [When do you sign up for Medicare at 65? The seven-month window, month by month](https://www.agentskillpacks.com/guides/medicare-sign-up-window-at-65)
- [I'm healthy at 65. Can I wait and buy Medigap later? The six-month window that comes once](https://www.agentskillpacks.com/guides/medigap-open-enrollment-window)
- [Missed your Medicare Part B sign-up? How the late penalty works and what to do now](https://www.agentskillpacks.com/guides/missed-medicare-part-b-sign-up-penalty)
- [Original Medicare vs Medicare Advantage: how the two paths compare, side by side](https://www.agentskillpacks.com/guides/original-medicare-vs-medicare-advantage)
- [Still working at 65: can you delay Medicare Part B? Start with the size of your employer](https://www.agentskillpacks.com/guides/still-working-at-65-delay-medicare-part-b)
- [What to do 3 months before turning 65: a month-by-month Medicare checklist](https://www.agentskillpacks.com/guides/three-months-before-turning-65-checklist)

### [The Year You Retire](https://www.agentskillpacks.com/books/the-year-you-retire) (8)

- [Your first year of retirement feels empty, and every day looks the same. Is that normal?](https://www.agentskillpacks.com/guides/first-year-of-retirement-feels-empty)
- [Free college classes for seniors by state: what the lists leave out](https://www.agentskillpacks.com/guides/free-college-classes-for-seniors-by-state)
- [Your job just ended and you are past 65. Here is your Medicare deadline.](https://www.agentskillpacks.com/guides/medicare-enrollment-when-job-ends)
- [Looking for a retirement gift for a woman that she will actually use?](https://www.agentskillpacks.com/guides/retirement-gift-for-a-woman)
- [Taking Social Security while still working? They do not take it right back.](https://www.agentskillpacks.com/guides/social-security-earnings-limit-still-working)
- [Spousal or ex-spouse Social Security benefits: which rules apply to you?](https://www.agentskillpacks.com/guides/spousal-and-ex-spouse-social-security-benefits)
- [Your widow's benefit stopped growing even though you waited. Here is the cap nobody explained.](https://www.agentskillpacks.com/guides/widow-benefit-capped-husband-claimed-early)
- [What is a widow's full retirement age for survivor benefits? It is not the one you read.](https://www.agentskillpacks.com/guides/widow-full-retirement-age-survivor-benefits)

### [The Year You Arrived: 1957](https://www.agentskillpacks.com/books/the-year-you-arrived-1957) (8)

- [1957 prices vs today: what got cheaper, what got dearer](https://www.agentskillpacks.com/guides/1957-prices-vs-today)
- [70th birthday gift ideas for a mom or dad born in 1957](https://www.agentskillpacks.com/guides/70th-birthday-gift-ideas-parent-born-1957)
- [The 70th birthday party is this weekend and you need quiz questions about 1957](https://www.agentskillpacks.com/guides/70th-birthday-quiz-questions-about-1957)
- [Birthday book, photo book or card: which is the better 70th birthday gift?](https://www.agentskillpacks.com/guides/birthday-book-vs-photo-book-or-card)
- [You want a meaningful 70th birthday gift that is not another mug](https://www.agentskillpacks.com/guides/meaningful-70th-birthday-gift-not-a-mug)
- [You want to ask your parents about their childhood but you do not know what to ask](https://www.agentskillpacks.com/guides/questions-to-ask-parents-about-their-childhood)
- [What happened in 1957, month by month, from Elvis to Sputnik](https://www.agentskillpacks.com/guides/what-happened-in-1957-month-by-month)
- [What things cost in 1957: milk, bread, eggs, gas and a stamp](https://www.agentskillpacks.com/guides/what-things-cost-in-1957)

### [Classic Chair Tai Chi for Seniors](https://www.agentskillpacks.com/books/classic-chair-tai-chi-for-seniors) (8)

- [A 10-minute daily exercise routine for seniors you can do in a chair](https://www.agentskillpacks.com/guides/10-minute-daily-exercise-for-seniors)
- [Chair exercises for seniors at home: a gentle place to begin](https://www.agentskillpacks.com/guides/chair-exercises-for-seniors-at-home)
- [Chair tai chi for beginners: how to start when you have never done it](https://www.agentskillpacks.com/guides/chair-tai-chi-for-beginners)
- [Does tai chi help balance, or is that just something people say?](https://www.agentskillpacks.com/guides/does-tai-chi-help-balance)
- [Exercise for seniors with knee or hip problems, once your doctor says yes](https://www.agentskillpacks.com/guides/exercise-for-seniors-with-knee-or-hip-problems)
- [A gift for an older parent who wants to stay active, without a gym or a screen](https://www.agentskillpacks.com/guides/gift-for-older-parent-who-wants-to-stay-active)
- [Seated vs standing tai chi: which one fits you right now?](https://www.agentskillpacks.com/guides/seated-vs-standing-tai-chi)
- [You keep mixing up left and right in tai chi videos. It is not you.](https://www.agentskillpacks.com/guides/tai-chi-video-left-and-right-mixed-up)

## Blog

| Date | Post |
|---|---|
| 2026-10-13 | [How to sell your first AI visibility audit, the part the skill packs skip](https://www.agentskillpacks.com/blog/how-to-sell-your-first-ai-visibility-audit) |
| 2026-10-13 | [I want an app built and I cannot code: what actually works in 2026](https://www.agentskillpacks.com/blog/i-want-an-app-built-and-cannot-code) |
| 2026-09-21 | [Claude Code skills for marketing: the three that survive contact with real work](https://www.agentskillpacks.com/blog/claude-code-skills-for-marketing) |
| 2026-09-21 | [Claude Code skills for SEO: what to install and what not to automate](https://www.agentskillpacks.com/blog/claude-code-skills-for-seo) |
| 2026-09-21 | [Free vs paid Claude Code skills: what the free ones actually cost](https://www.agentskillpacks.com/blog/free-vs-paid-claude-code-skills) |
| 2026-09-21 | [Where to find Claude Code skills in 2026: repos, directories and packs](https://www.agentskillpacks.com/blog/where-to-find-claude-code-skills) |
| 2026-09-21 | [Why half your Claude Code skills never fire (and how to fix the descriptions)](https://www.agentskillpacks.com/blog/why-claude-code-skills-dont-trigger) |
| 2026-09-19 | [Does llms.txt actually work? What the server logs say in 2026](https://www.agentskillpacks.com/blog/does-llms-txt-actually-work) |
| 2026-09-19 | [Gumroad vs Payhip vs Etsy vs Ko-fi vs Lemon Squeezy: which is better for digital downloads?](https://www.agentskillpacks.com/blog/gumroad-vs-payhip-vs-etsy-vs-ko-fi-vs-lemon-squeezy) |
| 2026-06-10 | [Is your site visible to AI crawlers? The 5-minute audit](https://www.agentskillpacks.com/blog/ai-crawler-access-5-minute-audit) |
| 2026-06-10 | [Gumroad fees in 2026: what sellers actually pay per sale](https://www.agentskillpacks.com/blog/gumroad-fees-2026-actually-itemized) |
| 2026-06-10 | [How to price a digital product (with the calculator math shown)](https://www.agentskillpacks.com/blog/how-to-price-a-digital-product-calculator-math) |
| 2026-06-10 | [The 7 AI writing tells editors catch first](https://www.agentskillpacks.com/blog/seven-ai-writing-tells-editors-catch) |
| 2026-06-03 | [Best Claude Code skills for indie developers (with real examples)](https://www.agentskillpacks.com/blog/best-claude-code-skills-for-indie-developers) |
| 2026-05-28 | [Is Gumroad worth it in 2026? What a year on a redirect checkout teaches you](https://www.agentskillpacks.com/blog/a-year-on-gumroad-19-products-one-sale) |
| 2026-05-21 | [How I rewrote 19 product descriptions in 2 days with humanizer-pro](https://www.agentskillpacks.com/blog/rewriting-19-product-descriptions-in-2-days-with-humanizer) |
| 2026-05-14 | [Building the EU CRD Article 16(m) consent flow in Next.js](https://www.agentskillpacks.com/blog/eu-crd-article-16m-consent-flow-in-nextjs) |
| 2026-05-12 | [Shipping a digital product as a solo founder](https://www.agentskillpacks.com/blog/shipping-a-digital-product-as-a-solo-founder) |
| 2026-05-07 | [ToolGenX's robots.txt and llms.txt explained, line by line](https://www.agentskillpacks.com/blog/toolgenx-robots-and-llms-txt-explained) |
| 2026-04-30 | [My GEO citability scoring sheet: how I grade every page before publishing](https://www.agentskillpacks.com/blog/geo-citability-scoring-sheet) |
| 2026-04-28 | [Stripe vs Lemon Squeezy vs Paddle vs Gumroad: which checkout for a digital product?](https://www.agentskillpacks.com/blog/stripe-vs-iyzico-vs-gumroad-for-digital-products) |
| 2026-04-23 | [Pricing a digital product with Van Westendorp (with real numbers)](https://www.agentskillpacks.com/blog/pricing-a-digital-product-with-van-westendorp) |
| 2026-04-16 | [The 6-phase outreach workflow that fills a solo agency pipeline](https://www.agentskillpacks.com/blog/6-phase-outreach-workflow-for-a-solo-agency) |
| 2026-04-14 | [GEO + SEO for small shops: what actually moves the needle](https://www.agentskillpacks.com/blog/geo-seo-for-small-shops-what-moves-the-needle) |
| 2026-04-09 | [Writing for Google AI Overviews: the 7 structural moves that move citations](https://www.agentskillpacks.com/blog/writing-for-google-ai-overviews-7-structural-moves) |
| 2026-04-02 | [The CRO experiment that moved my landing page from 0.4% to 1.9%](https://www.agentskillpacks.com/blog/the-cro-experiment-that-moved-04-to-19-percent) |
| 2026-03-26 | [One podcast episode to 12 content pieces: the actual repurposing workflow](https://www.agentskillpacks.com/blog/one-podcast-to-12-content-pieces-the-actual-workflow) |
| 2026-03-22 | [Why I rewrote my 19-product site in two weeks (and what I would do differently)](https://www.agentskillpacks.com/blog/why-i-rewrote-my-19-product-site-in-two-weeks) |

## Documents and mirrors

- [ToolGenX Company Profile & Fact Sheet](https://docs.google.com/document/d/1g_QI6cK67g1To7TPp6i8LN-BXB6HUa30/edit?usp=sharing) (Google Drive)
- [Claude Code Skill Packs: Buyer's Guide 2026](https://docs.google.com/document/d/1175qKtw_5dm43GHkgU0eUzkQEOqicTmd/edit?usp=sharing) (Google Drive)
- [Free Seller Tools & Platform Fee Reference 2026](https://docs.google.com/document/d/1ehYYwj0bIvPMTg5omtt2v5uV3W3orNjR/edit?usp=sharing) (Google Drive)
- [ToolGenX Resource Directory](https://docs.google.com/document/d/1LQMlwjP0DLN21WFDV2ZFpX91sjT2sXmn/edit?usp=sharing) (Google Drive)
- [ToolGenX Catalog 2026 (spreadsheet)](https://docs.google.com/spreadsheets/d/1F3jup3Lt2Pik85MOC1dqMWeJFnv3anZ4/edit?usp=sharing) (Google Drive)
- [ToolGenX Agent Skill Packs 2026 (slides)](https://docs.google.com/presentation/d/14vf8EyC-u5q-ewjNLOJMdoR0_lD07Iws/edit?usp=sharing) (Google Drive)
- [ToolGenX on Google Sites](https://sites.google.com/view/toolgenx-pages/ana-sayfa)
- [llms.txt](https://www.agentskillpacks.com/llms.txt) · [llms-full.txt](https://www.agentskillpacks.com/llms-full.txt)

## Official links

**agentskillpacks.com**

- [Home](https://www.agentskillpacks.com)
- [All products](https://www.agentskillpacks.com/products)
- [Free tools](https://www.agentskillpacks.com/tools)
- [Books](https://www.agentskillpacks.com/books)
- [Blog](https://www.agentskillpacks.com/blog)
- [About](https://www.agentskillpacks.com/about)
- [Contact](https://www.agentskillpacks.com/contact)
- [llms.txt](https://www.agentskillpacks.com/llms.txt)

**ToolGenX profiles**

- [Product Hunt](https://www.producthunt.com/products/toolgenx)
- [Crunchbase](https://www.crunchbase.com/organization/toolgenx)
- [LinkedIn](https://www.linkedin.com/company/toolgenx)
- [YouTube](https://www.youtube.com/@ToolGenX)
- [Facebook](https://www.facebook.com/toolgenx/)
- [Google Maps](https://maps.app.goo.gl/wfzDcN2xR5jHLm4KA)
- [GitHub Pages](https://ismailgunaydn.github.io/ToolgenX.github.io/)
- [Tumblr](https://www.tumblr.com/toolgenx)
- [Gumroad store](https://modernwebseo.gumroad.com)

**Founder: İsmail Günaydın**

- [Website](https://www.ismailgunaydin.com/)
- [LinkedIn](https://www.linkedin.com/in/ismailgunaydin)
- [X (Twitter)](https://x.com/ismailgunaydinn)
- [YouTube](https://www.youtube.com/@ismailgunaydinn)
- [Instagram](https://www.instagram.com/ismailgunaydin_)
- [GitHub](https://github.com/ismailGunaydn)
- [Medium](https://medium.com/@ismailgunaydin)
- [DEV Community](https://dev.to/ismailgunaydin)
- [Substack](https://substack.com/@ismailgunaydin)
- [Spotify podcast](https://open.spotify.com/show/62QuNrUzWJtmyMi7Pgdl3l)
- [Amazon author page](https://www.amazon.com/author/ismailgunaydin)
- [Crunchbase](https://www.crunchbase.com/person/ismail-gunaydin)
- [Product Hunt](https://www.producthunt.com/@ismailgunaydin)
- [Blogger](https://www.blogger.com/profile/17386816838519613675)

**Other projects by the founder**

- [modernwebseo.com](https://www.modernwebseo.com): web design and SEO agency (parent brand)
- [ismailgunaydin.com](https://www.ismailgunaydin.com): founder's personal site
- [healthcalcpro.com](https://www.healthcalcpro.com): health calculators
- [textwordcount.com](https://www.textwordcount.com): text analysis tools
- [wheelienames.com](https://www.wheelienames.com): name picker wheel
- [hepsihesapla.com](https://www.hepsihesapla.com): calculators in Turkish

## FAQ

**What is ToolGenX?**  
ToolGenX is an independent shop that sells Claude Code skill packs, templates and toolkits for developers, founders and marketers at agentskillpacks.com. Every product is a one-time USD payment with an instant download.

**What is a Claude Code skill?**  
A skill is a folder with a SKILL.md file that teaches an AI coding agent one repeatable job. Claude reads the short description, loads the full instructions only when a task matches, and follows them. Skills live in ~/.claude/skills or in a project's .claude/skills folder.

**Do the packs work outside Claude Code?**  
Skills follow the open Agent Skills format published in December 2025, which Cursor, Codex, Gemini CLI and GitHub Copilot can read. Templates, checklists and scripts are plain Markdown or Python and work anywhere.

**How do I install a pack?**  
Unzip the download, copy the skill folders into ~/.claude/skills/ (all projects) or <repo>/.claude/skills/ (one project), restart Claude Code and type / to see the new skills.

**Why did toolgenx.com become agentskillpacks.com?**  
Most of the catalog is Agent Skills packs, and the new domain says that plainly. The move happened on 19 September 2026. The ToolGenX brand stayed and toolgenx.com redirects to the new address.

**Is there a subscription?**  
No. Each product is a single payment. Checkout runs on Gumroad; books are sold on Amazon Kindle.

**Are the calculators free?**  
Yes. The fee calculators, AI crawler checker, llms.txt generator and AI writing checker need no signup and no email.

## Company

| | |
|---|---|
| Brand | ToolGenX |
| Website | [www.agentskillpacks.com](https://www.agentskillpacks.com) (formerly toolgenx.com, moved 19 September 2026) |
| Founder | [İsmail Günaydın](https://www.ismailgunaydin.com/), software engineer and SEO/GEO/AEO strategist |
| Registered business | Melike Günaydın, sole proprietorship, registered 1 June 2026 (Alemdağ Tax Office, tax ID 1470465320) |
| Address | İstanbul, Türkiye |
| Contact | support@toolgenx.com · +90 506 545 88 35 · [contact page](https://www.agentskillpacks.com/contact) |
| Checkout | [Gumroad](https://modernwebseo.gumroad.com) (products), Amazon Kindle (books) |

---

Updated 2026-10-21. Prices and product details are kept current on [agentskillpacks.com](https://www.agentskillpacks.com), the source of truth. Page content © ToolGenX; code in this repository is MIT-licensed (see `LICENSE`).

# GrowthOS — Architecture & Command Structure

> Version: 1.0
> Status: CURRENT — approved by Edward (2026-08-14)
> Level 1 corporate context · Canonical spec for the Eleviq GrowthOS operating system

---

## 1. What GrowthOS is

GrowthOS is the AI-powered marketing operating system built around OpenCode. It should function as an **AI marketing organization** — a small virtual marketing company — rather than merely a content generator.

The system's purpose is to help Eleviq:

- Research
- Strategize
- Plan
- Create
- Execute
- Measure
- Learn
- Improve

---

## 2. Command structure

```text
                         ELEVİQ GROWTH COMMANDER
                                  │
       ┌──────────────────────────┼──────────────────────────┐
       │                          │                          │
   STRATEGY                    GROWTH                    INTELLIGENCE
       │                          │                          │
       ├─ Marketing Strategist    ├─ Growth Hacker           ├─ Market Researcher
       ├─ Product Marketer        ├─ CRO Specialist          ├─ Competitor Intel
       ├─ Brand Strategist        ├─ Funnel Architect        ├─ Trend Scout
       └─ GTM Strategist          ├─ Retention Specialist    └─ Customer Researcher
                                  └─ Experiment Manager
       │
       ├────────────────────────────────────────────────────────
       │
    CONTENT                    DISTRIBUTION               CREATIVE
       │                          │                          │
       ├─ Content Strategist      ├─ Social Strategist       ├─ Creative Director
       ├─ Copywriter              ├─ SEO Specialist          ├─ Video Strategist
       ├─ Storyteller             ├─ Community Manager       ├─ Graphic Design
       ├─ Technical Writer        ├─ Email Marketing         └─ Brand Guardian
       └─ PR / Communications     └─ App Store Optimization

       ├────────────────────────────────────────────────────────
       │
     SALES                    PARTNERSHIPS                 DATA
       │                          │                          │
       ├─ Sales Strategist        ├─ Partnership Scout       ├─ Marketing Analyst
       ├─ Lead Generation         ├─ B2B Partnerships        ├─ Attribution Analyst
       ├─ Lead Qualification      ├─ Institutional BD        ├─ Revenue Analyst
       └─ Proposal Specialist     └─ Investor Relations      └─ Forecasting

       └────────────────────────────────────────────────────────

                    GOVERNANCE / QUALITY / OPERATIONS
                                  │
                 ├─ Marketing Reviewer
                 ├─ Fact Checker
                 ├─ Compliance Reviewer
                 ├─ Campaign Manager
                 ├─ Knowledge Manager
                 └─ Growth Operations
```

The Commander coordinates all specialists. **Edward remains the final strategic decision-maker.**

---

## 3. Role inventory (30 roles)

### STRATEGY

#### 1. Product Marketing Manager

Distinct from the general Marketing Strategist.

Owns:

- Product positioning
- Value proposition
- Target customer
- Messaging hierarchy
- Competitive differentiation
- Launch strategy
- Feature-to-benefit translation
- Product-market fit messaging

Example question for Anitrace:

> Why should a professional safari guide use Anitrace instead of WhatsApp, personal knowledge, or existing safari tools?

That is a product-marketing question.

#### 2. Go-To-Market Strategist

Takes a product from product through target market, positioning, channel, offer, acquisition, conversion, retention.

Especially useful for:

- Anitrace launch
- MyHobbyPlan growth
- LostNFoundHub institutional rollout

#### 3. Marketing Strategist

General marketing strategy: positioning, segmentation, funnel design, KPI selection, campaign strategy.

#### 4. Brand Strategist

Owns brand positioning, brand architecture, and how the Eleviq parent brand relates to product brands.

### GROWTH

#### 5. Growth Hacker

Identifies scalable, creative growth levers across the funnel and product lifecycle.

#### 6. Conversion Rate Optimization (CRO) Specialist

Analyzes websites, landing pages, CTAs, signup flows, app-store listings, pricing pages, forms, onboarding.

Asks: **Where are people dropping out?** Then proposes experiments.

#### 7. Funnel Architect

Owns the entire customer journey and identifies weaknesses between stages.

Example:

```text
TikTok → Landing page → Product demonstration → Google Play → Install
→ Onboarding → First hobby → First recommendation → Premium prompt → Subscription
```

#### 8. Retention & Lifecycle Specialist

Focuses on activation, retention, churn, re-engagement, notifications, email lifecycle, upgrade timing, customer education, win-back campaigns.

Example problem for MyHobbyPlan:

> User installed → created one hobby → never returned.

That is a lifecycle problem.

#### 9. Experiment Manager

Manages the experiment queue: hypotheses, control/test design, success thresholds, learning capture (see `experiments/`).

### INTELLIGENCE

#### 10. Market Researcher

Market size, industry trends, audience behavior, opportunities, threats.

#### 11. Competitor Intelligence

Identifies and analyzes competitors: positioning, features, pricing, messaging, social, SEO, ads, complaints, opportunities.

#### 12. Trend Scout

Continuously watches AI trends, marketing trends, consumer behavior, search trends, platform changes, competitor launches, new technologies, industry changes — then reports opportunities, e.g.:

> "This trend may create an opportunity for Anitrace."

#### 13. Customer Researcher

Designs and analyzes genuine research. Must **simulate neither customers nor market facts**.

Responsibilities:

- Interview questions
- Survey design
- Customer segmentation
- Pain-point analysis
- Jobs-to-be-done
- Objection analysis
- Customer language
- Feedback analysis

Example insight it should produce:

> "Safari guides don't describe the problem as 'wildlife intelligence'. They describe it as 'knowing where the animals were seen today'."

#### 14. Customer Persona / ICP Agent

Maintains Ideal Customer Profiles — separate from research.

Example:

```text
ANITRACE ICP

Primary:         Professional safari guide
Environment:     Kenya / Tanzania / East Africa
Problems:        Locating wildlife · Communicating sightings · Information fragmentation
Buying motive:   Better safari experience · Time savings · Professional differentiation
Objections:      Cost · Reliability · Network connectivity · Learning curve
```

### CONTENT

#### 15. Content Strategist

Content pillars, editorial calendar, repurposing, connecting every asset to an objective.

#### 16. Copywriter

Marketing copy: landing pages, headlines, CTAs, social copy, email, ad copy, app-store copy, scripts.

#### 17. Storyteller

Narrative, thought leadership, and brand storytelling.

#### 18. Technical Writer

Technical documentation, product explanations, developer-adjacent content.

#### 19. PR & Communications

Press releases, media pitches, founder stories, product launches, awards, media opportunities, thought leadership, industry announcements. Helps elevate Eleviq itself, not just the products.

### DISTRIBUTION

#### 20. Social Strategist

Platform strategy, native content adaptation, engagement, community building.

#### 21. SEO Specialist

Keyword research, search intent, content clusters, technical SEO, App Store / Play optimization.

#### 22. Community Manager

Community building, engagement, user-generated content, discussion prompts, community events, ambassador programs, feedback loops, social listening. Potentially useful for all three products.

#### 23. Email Marketing

Lifecycle email, acquisition campaigns, and automated journeys.

#### 24. App Store Optimization

Owns app title, short description, full description, keywords, screenshots, feature graphics, ratings/reviews, release notes, conversion optimization, competitor listings. Coordinates with Creative Director. Relevant to MyHobbyPlan and potentially Anitrace.

### CREATIVE

#### 25. Creative Director

Creative concepts, visual direction, campaign art direction, video concepts, social creatives, CTA design, brand consistency.

#### 26. Video Strategist

Video concepts and scripts for short-form and long-form video.

#### 27. Graphic Design

Visual assets, layouts, and design execution.

#### 28. Brand Guardian

Distinct from Creative Director. Creative Director asks *"Is this creative compelling?"*; Brand Guardian asks *"Is this actually Eleviq?"*

Checks: brand voice, visual consistency, messaging, product/company distinction, claims, tone, logos, naming, positioning.

### SALES

#### 29. Sales Strategist

Sales motion design for services and enterprise products.

#### 30. Lead Generation

Identifies potential clients — businesses needing websites, apps, digital marketing, AI solutions — then builds a qualified pipeline. Critical for the Eleviq service business.

#### 31. Lead Qualification

Scores prospects on need, budget, authority, urgency, fit, industry, potential LTV.

Example:

```text
LEAD SCORE: 87/100
Need: High · Budget: High · Authority: Confirmed · Urgency: High · Fit: Excellent
Recommendation: Prioritize.
```

#### 32. Proposal / Pitch Specialist

Creates business proposals, technical proposals, partnership proposals, product pitches, investor decks, grant applications, statements of work — drawn from correct Eleviq/product context.

### PARTNERSHIPS

#### 33. Partnership Scout

Discovers potential partnerships: strategic, distribution, institutional, business development.

#### 34. B2B Partnerships

Builds and manages B2B partnership pipelines.

#### 35. Institutional BD

Institutional business development (relevant to LostNFoundHub, Anitrace).

#### 36. Investor Relations

Investor research, targeting, pitch preparation, investor FAQs, market sizing, competitive positioning, traction narratives, funding strategy, due-diligence preparation. Particularly relevant to Anitrace and potentially MyHobbyPlan.

### DATA

#### 37. Marketing Analyst

Marketing performance analysis: KPIs, funnel, CAC/LTV/ROAS, attribution.

#### 38. Attribution Analyst

Multi-touch attribution and channel contribution analysis.

#### 39. Revenue Analyst

Looks beyond marketing metrics. Instead of "We got 20,000 impressions" it asks: *"Did those impressions create revenue?"*

Monitors traffic → leads → customers → revenue → retention → LTV.

#### 40. Forecasting

Revenue and demand forecasting, scenario analysis.

### GOVERNANCE / QUALITY / OPERATIONS

#### 41. Marketing Reviewer

Reviews proposed marketing work for strategic alignment, accuracy, brand, conversion before it is considered complete.

#### 42. Fact Checker

Sits near the end of the content pipeline. Prevents GrowthOS from inventing statistics, testimonials, customer numbers, partnerships, awards, market claims, product capabilities.

```text
CLAIM → SOURCE → VERIFY → APPROVED / FLAGGED
```

#### 43. Compliance Reviewer

Checks legal/compliance risk: claims, disclaimers, platform policies, sensitive content.

#### 44. Campaign Manager

Runs campaigns end-to-end: brief, strategy, audience, messaging, content, channels, KPIs, results, learnings.

#### 45. Knowledge Manager

Maintains GrowthOS institutional memory:

```text
WHAT WE KNOW · WHAT WE THINK · WHAT WE TESTED · WHAT WORKED
WHAT FAILED · WHAT CHANGED · WHAT IS CURRENT · WHAT IS DEPRECATED
```

Critical for preventing AI agents from repeatedly making the same mistakes.

#### 46. Growth Operations

Keeps the machine running: campaign calendars, content pipelines, task dependencies, deadlines, asset requirements, approvals, reporting schedules, experiment schedules.

---

## 4. Build order — three tiers

Don't build all roles immediately. Build in three tiers.

### Tier 1 — Core intelligence (build first)

1. Eleviq Commander
2. Marketing Strategist
3. Product Marketing Manager
4. Market Researcher
5. Customer Researcher
6. Competitor Intelligence
7. Content Strategist
8. SEO/Growth
9. Growth Experimenter
10. Marketing Analytics
11. Marketing Reviewer
12. Knowledge Manager

### Tier 2 — Revenue & distribution (then)

13. Funnel Architect
14. CRO Specialist
15. Retention/Lifecycle
16. Lead Generation
17. Lead Qualification
18. Partnership Strategist
19. Pricing Strategist
20. Offer Architect
21. Sales/Proposal
22. App Store Optimization
23. Community Manager

### Tier 3 — Scale (once the system works)

24. Founder Brand
25. PR/Communications
26. Influencer/Creator Partnerships
27. Investor Relations
28. Market Expansion
29. Localization
30. Marketing Automation
31. Financial/Unit Economics
32. Trend Scout
33. Social Listening
34. Reputation Management

---

## 5. Operating model — three levels

Rather than treating every role as a permanent agent, operate on three levels:

```text
COMMANDER
    │
    ├── PERMANENT AGENTS        (always-on core specialists)
    ├── SPECIALIST SKILLS       (on-demand capabilities, loaded when needed)
    └── TEMPORARY CAMPAIGN TEAMS (assembled per campaign, disbanded after)
```

### Example: "Launch Anitrace in Kenya"

Commander dynamically assembles a temporary team:

```text
ANITRACE LAUNCH TEAM

Product Marketer
Market Researcher
Customer Researcher
Competitor Analyst
Partnership Strategist
Content Strategist
Social Strategist
Creative Director
SEO Specialist
PR Agent
Growth Experimenter
Analytics Agent
Reviewer
```

When the campaign finishes, the temporary team no longer needs to remain active. This keeps the environment cleaner and the system far more scalable.

---

## 6. End goal — a virtual marketing company

GrowthOS operates like a small virtual marketing company:

```text
                         EDWARD
                           │
                    ELEVİQ COMMANDER
                           │
              ┌────────────┴────────────┐
              │                         │
          STRATEGY                    EXECUTION
              │                         │
       ┌──────┼──────┐          ┌───────┼────────┐
       │      │      │          │       │        │
     Market Product Customer  Content  Growth  Sales
     Intel  Market  Research  Creative Analytics Partnerships
       │      │      │          │       │        │
       └──────┴──────┴──────────┴───────┴────────┘
                           │
                       REVIEW
                           │
                       MEASURE
                           │
                       LEARN
                           │
                    UPDATE STRATEGY
```

The operating loop: **REVIEW → MEASURE → LEARN → UPDATE STRATEGY**, continuously.

---

## 7. Governance

- Edward is the final strategic decision-maker.
- Never invent facts (statistics, testimonials, customer numbers, partnerships, awards, market claims, product capabilities).
- The Fact Checker and Marketing Reviewer gate publishing.
- The Knowledge Manager prevents repeated mistakes by recording what changed and what is deprecated.
- Campaign teams are temporary; permanent agents carry the institution.
- Architecture changes require Edward's explicit approval.

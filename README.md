# Awesome-Customer-Feedback-NPS-Software

# Awesome-Customer-Feedback-NPS-Software

**Top Customer Feedback NPS Software (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on NPS Collection, In-App Micro-Surveys, Research-Grade Questionnaires & Self-Hosted Feedback Platforms*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Feedback & NPS Software**. These tools enable teams to measure Net Promoter Score, collect in-product feedback, run research surveys, and close the loop with customers—from fully managed enterprise platforms with AI analysis to self-hosted survey engines that give organizations complete ownership of response data and GDPR compliance.



**Examples** include Qualtrics, Medallia, InMoment, SurveyMonkey, Typeform, Delighted, Retently, Nicereply, and HubSpot Feedback Management (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted NPS, in-app surveys, and open feedback infrastructure. **Critical note**: The open-source landscape splits by use case—**Formbricks** is the modern choice for in-product NPS and micro-surveys with behavior-based targeting , while **LimeSurvey** is the veteran for research-grade questionnaires with 30+ question types and deep logic . **Astuto** and **Refyyn** handle public feedback boards with voting, not NPS scoring . No single open-source project matches Qualtrics's research depth or Medallia's enterprise CX suite, but for NPS measurement specifically, Formbricks is production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Qualtrics](https://www.qualtrics.com/)**

  **Enterprise experience management platform** with NPS, CSAT, CES, and advanced analytics. **Pricing**: **Quote-only**; enterprise contracts. **Free tier**: **No free tier**; demo available. **Best for**: large enterprises needing research-grade survey methodology and CX program management—**trade-off**: enterprise pricing; implementation commitment.



- **[Medallia](https://www.medallia.com/)**

  **Enterprise customer experience platform** with NPS and feedback analytics. **Pricing**: **Quote-only**; six-figure enterprise contracts. **Free tier**: None. **Best for**: large enterprises with dedicated CX teams—**trade-off**: enterprise-only; not accessible for SMBs.



- **[InMoment](https://inmoment.com/)**

  **Experience improvement platform** with NPS and text analytics. **Pricing**: **Quote-only**. **Free tier**: None. **Best for**: enterprises wanting AI-powered feedback analysis at scale.



- **[SurveyMonkey](https://www.surveymonkey.com/)**

  **Survey platform** with NPS question type and templates. **Pricing**: **Free plan** with **10 questions and 25 responses per survey**; paid from **$25/month** . **Free tier**: Yes, limited. **Best for**: SMBs wanting a familiar survey tool with NPS templates—**trade-off**: limited free tier; advanced logic requires paid plans.



- **[Typeform](https://www.typeform.com/)**

  **Conversational form builder** with NPS and logic branching. **Pricing**: **Free plan** with **10 responses/month**; paid from **$25/month** . **Free tier**: Yes, 10 responses/month. **Best for**: teams wanting engaging, conversational survey experiences—**trade-off**: response limits on free tier.



- **[Delighted](https://delighted.com/)** (Qualtrics)

  **NPS-focused feedback platform** with automated email/SMS collection. **Pricing**: **Free plan** with **100 responses/month**; paid from **$224/month** for higher volumes. **Free tier**: Yes, 100 responses/month. **Best for**: teams wanting simple, automated NPS collection—**trade-off**: limited free tier; pricing scales with volume.



- **[Retently](https://www.retently.com/)**

  **NPS and CSAT platform** with automation and Slack integration. **Pricing**: **Free plan** with **100 responses/month**; paid from **$49/month**. **Free tier**: Yes, 100 responses. **Best for**: SMBs wanting NPS automation with team notifications.



- **[Nicereply](https://www.nicereply.com/)**

  **CSAT, NPS, and CES** for support teams with helpdesk integrations. **Pricing**: **Free plan** with **50 responses/month**; paid from **$29/agent/month**. **Free tier**: Yes, limited. **Best for**: support teams wanting feedback tied to tickets.



- **[HubSpot Feedback Management](https://www.hubspot.com/)**

  **NPS, CSAT, and CES surveys** within HubSpot Service Hub. **Pricing**: Included with Service Hub Professional ($100/seat/month) and Enterprise. **Free tier**: Limited. **Best for**: HubSpot users wanting feedback integrated with CRM and tickets.



## Open-Source GitHub Projects



- **[Formbricks](https://github.com/formbricks/formbricks)**

  **Open-source experience management platform** (AGPLv3) — **the best open-source choice for in-product NPS and behavior-triggered micro-surveys**, with **12,000+ GitHub stars** . **Features**: **NPS, CSAT, CES, and 20+ question types**; **in-app surveys** triggered by user attributes, events, and segments; website surveys via lightweight JavaScript snippet; link surveys with custom branding; skip logic and conditional branching; built-in analytics with charts and CSV/JSON export; webhooks and integrations with Slack, Notion, Google Sheets, Airtable, and Zapier; multi-language support . **Tech stack**: Next.js, PostgreSQL (pgvector), Redis. **Deploy**: Self-hosted (Docker, Railway one-click) or Formbricks Cloud . **Trade-off**: **In-product focus**—less suited for long-form research questionnaires than LimeSurvey; enterprise features gated in paid tier. **Best for**: SaaS and product teams wanting contextual NPS that fires while users are in the app—not blast-one-link surveys .



- **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)**

  **The world's #1 open-source survey platform** (GPL v2) — **the veteran research-grade survey engine**, around since 2006 and trusted by universities, governments, and market researchers . **Features**: **30+ question types** with deep logic, quotas, and branching; **900+ survey templates**; multilingual surveys (80+ languages); SPSS/R/STATA export; **NPS question type supported**; GDPR compliance; two-factor authentication; SAML/LDAP integration; 3,547 GitHub stars with active development (last push 8 days ago) . **Tech stack**: PHP, MySQL/MariaDB/PostgreSQL. **Deploy**: Self-hosted (Docker, manual) or LimeSurvey Cloud . **Trade-off**: **Utilitarian interface** compared to Formbricks; heavier for simple in-app NPS. **Best for**: research teams, academics, and organizations running long-form questionnaires where question logic and statistical exports matter .



- **[Astuto](https://github.com/astuto/astuto)**

  **Open-source customer feedback tool** (license per repo) — **the best choice for public feedback boards with voting and prioritization** . **Features**: Collect, manage, and prioritize user feedback; public boards with upvoting; designed for product roadmap input. **Tech stack**: Per repository. **Deploy**: Self-hosted (Docker) . **Trade-off**: **Feedback board, not NPS**—no NPS scoring, no survey logic, no analytics. **Best for**: product teams wanting a public feedback portal where users vote on feature requests—not measuring satisfaction.



- **[Refyyn](https://github.com/AbdullahSWE/Refyyn)**

  **Self-hosted customer feedback tool with kanban roadmap and changelogs** (MIT) — **the most complete open-source feedback-to-roadmap workflow** . **Features**: Admin dashboard for managing feedback; **public feedback board** with upvotes and comments; **public roadmap** (planned/in progress/completed); **changelog** for release notes; customizable boards and statuses. **Tech stack**: Laravel 12, Vue 3, Inertia.js, SQLite/MySQL/PostgreSQL . **Deploy**: Self-hosted (PHP 8.2+, Composer, Node 22+) . **Trade-off**: **Feedback management, not NPS**—no survey scoring, no automated collection. **Best for**: product teams wanting feedback, roadmap, and changelog in one self-hosted tool.



- **[prometheus-nps](https://github.com/Zeb88/prometheus-nps)**

  **NPS feedback system with AI analysis** (license per repo) — **the most focused open-source NPS-specific tool** . **Features**: **NPS feedback collection** (0-10 score + text); real-time NPS calculation; **AI-generated feedback summaries** via OpenAI; email integration for personalized form links; vector database storage (Supabase) for semantic search; CSV export; JWT authentication; rate limiting . **Tech stack**: Node.js, Express, Alpine.js, Supabase (PostgreSQL + pgvector), OpenAI, Resend . **Deploy**: Self-hosted (requires Supabase, OpenAI API key, Resend API key) . **Trade-off**: **Early-stage project**—requires multiple external services (Supabase, OpenAI, Resend); not production-hardened. **Best for**: developers wanting a working NPS collection + AI analysis reference implementation.



### Additional Strong Open-Source Options



- **customersatisfactionmetrics** — Django package for CSAT, NPS, CES, and generic surveys (MIT) . **Note**: **Library, not a platform**—embeds into Django applications; no UI. **Best for**: Django developers wanting to add NPS surveys to their own app.

- **csat** — Self-contained CSAT survey with analytics in a single Go binary (license per repo) . **Note**: **CSAT only**—not NPS; SMS-focused with encrypted links. **Best for**: teams wanting lightweight CSAT via SMS without a platform.



**Frameworks for building custom systems**: Combine **Formbricks** for in-app NPS with **Astuto** or **Refyyn** for public feedback boards and **LimeSurvey** for deep research questionnaires—creating a feedback stack matched to different collection contexts. **None of these match Qualtrics's research depth or Medallia's enterprise CX suite**, but for NPS measurement specifically, Formbricks is production-proven.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer feedback platforms handling respondent data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for survey responses and NPS scores.

- **The "in-product NPS" vs. "research-grade survey" vs. "feedback board" distinction is critical.** **Formbricks** is **in-product NPS**—it targets users by behavior and triggers surveys inside the app . **LimeSurvey** is **research-grade**—it handles long questionnaires with deep logic and statistical exports . **Astuto and Refyyn** are **feedback boards**—they collect feature requests with voting, not NPS scores . **prometheus-nps** is a **focused NPS implementation**—collection plus AI analysis, but early-stage . **Choose based on whether you need contextual in-app NPS, deep research surveys, or a public feedback portal.**

- **Formbricks is the best open-source choice for in-product NPS.** With 12,000+ stars, NPS/CSAT/CES support, behavior-based targeting, and Docker self-hosting, it is the modern Qualtrics/Sprig alternative for product teams . **The trade-off**: less suited for long-form research questionnaires than LimeSurvey.

- **LimeSurvey is the veteran for research.** Since 2006, with 30+ question types, SPSS/R exports, and GDPR compliance, it is hard to beat for academic and market research . **The trade-off**: utilitarian interface; heavier for simple in-app NPS.

- **Astuto and Refyyn are not NPS tools.** They collect feedback and feature requests with voting; neither measures satisfaction scores . **Do not evaluate them for NPS requirements.**

- **prometheus-nps is early-stage but focused**—it does one thing (NPS collection + AI analysis) and requires Supabase, OpenAI, and Resend . **For a reference implementation or small-scale NPS, it is useful; for production, Formbricks is safer.**

- **Pricing opacity varies.** Qualtrics, Medallia, InMoment, and HubSpot (enterprise) require sales contact. SurveyMonkey, Typeform, Delighted, Retently, and Nicereply publish tiered pricing with free tiers. **Validate with direct vendor conversations against your response volume and feature needs.**

- Self-hosted open-source solutions require proper infrastructure (PostgreSQL/Redis for Formbricks, PHP/MySQL for LimeSurvey), security hardening, and ongoing maintenance. **Survey data includes respondent PII and sentiment**—ensure your deployment meets your organization's privacy and GDPR requirements before collecting responses.



---



**Made for product teams, CX researchers, and organizations building transparent feedback solutions.**

Let's make Customer Feedback & NPS Software more open, data-driven, and respondent-friendly.

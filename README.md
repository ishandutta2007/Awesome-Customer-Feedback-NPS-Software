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

- **[Formbricks](https://github.com/formbricks/formbricks)** [![GitHub stars](https://img.shields.io/github/stars/formbricks/formbricks?style=social&color=white)](https://github.com/formbricks/formbricks/stargazers)

  **Open-source experience management platform** (AGPLv3) — **the best open-source choice for in-product NPS and behavior-triggered micro-surveys**, with **13,000+ GitHub stars**. **Features**: **NPS, CSAT, CES, and 20+ question types**; **in-app surveys** triggered by user attributes, events, and segments; website surveys via lightweight JavaScript snippet; link surveys with custom branding; skip logic and conditional branching; built-in analytics with charts and CSV/JSON export; webhooks and integrations with Slack, Notion, Google Sheets, Airtable, and Zapier; multi-language support. **Tech stack**: Next.js, PostgreSQL (pgvector), Redis. **Deploy**: Self-hosted (Docker, Railway one-click) or Formbricks Cloud. **Trade-off**: **In-product focus**—less suited for long-form research questionnaires than LimeSurvey; enterprise features gated in paid tier. **Best for**: SaaS and product teams wanting contextual NPS that fires while users are in the app—not blast-one-link surveys.

- **[HeyForm](https://github.com/heyform/heyform)** [![GitHub stars](https://img.shields.io/github/stars/heyform/heyform?style=social&color=white)](https://github.com/heyform/heyform/stargazers)

  **Open-source conversational form and survey builder** (AGPLv3) — **a modern, self-hosted alternative to Typeform and SurveyMonkey**. **Features**: Interactive, conversational questionnaires, NPS ratings, multi-step forms, logic branching, integrations, and visual customization. **Tech stack**: Node.js, TypeScript, React, MongoDB. **Deploy**: Self-hosted (Docker) or HeyForm Cloud. **Trade-off**: Form builder orientation; requires external automation or webhooks for deep CRM workflows. **Best for**: teams wanting sleek, mobile-friendly conversational surveys and NPS collection without per-response limits.

- **[Fider](https://github.com/getfider/fider)** [![GitHub stars](https://img.shields.io/github/stars/getfider/fider?style=social&color=white)](https://github.com/getfider/fider/stargazers)

  **Open platform to collect, prioritize, and manage customer feedback** (AGPLv3) — **one of the most popular open-source feedback portal solutions**. **Features**: Public and private feedback boards, user voting, discussion threads, response status tags (planned, started, completed), custom branding, and social/OAuth login. **Tech stack**: Go, React, PostgreSQL. **Deploy**: Self-hosted (Docker) or Fider Cloud. **Trade-off**: **Feedback board and suggestion box**—does not calculate numeric NPS satisfaction metrics. **Best for**: product teams seeking a lightweight, transparent forum for feature requests and customer feedback.

- **[SurveyKing](https://github.com/javahuang/SurveyKing)** [![GitHub stars](https://img.shields.io/github/stars/javahuang/SurveyKing?style=social&color=white)](https://github.com/javahuang/SurveyKing/stargazers)

  **One-command deployable, full-featured survey engine** (MIT) — **powerful self-hosted alternative to SurveyMonkey**. **Features**: 20+ question types including NPS, scoring, ranking, exams, and logic rules; responsive design for mobile and desktop; comprehensive reporting and data export; granular permission management. **Tech stack**: Java, Spring Boot, Vue.js, MySQL/PostgreSQL. **Deploy**: Self-hosted (single Docker run command or jar). **Trade-off**: Full survey system rather than embedded SDK; traditional questionnaire layout. **Best for**: organizations wanting an enterprise-grade survey platform under an MIT license that deploys in seconds.

- **[Xiaoju Survey (XIAOJUSURVEY)](https://github.com/didi/xiaoju-survey)** [![GitHub stars](https://img.shields.io/github/stars/didi/xiaoju-survey?style=social&color=white)](https://github.com/didi/xiaoju-survey/stargazers)

  **Enterprise form builder and analytics platform developed by DiDi** (Apache-2.0) — **scalable survey and feedback infrastructure**. **Features**: Drag-and-drop question builder, flexible page logic, multiple question modules (NPS, matrices, ratings), collaborative survey editing, and rich visual data analysis dashboards. **Tech stack**: Node.js, NestJS, Vue 3, Element Plus, MongoDB. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: Complex multi-service architecture suited for organizations. **Best for**: mid-to-large engineering teams looking for an enterprise-ready survey and questionnaire suite with rich visualization.

- **[LimeSurvey](https://github.com/LimeSurvey/LimeSurvey)** [![GitHub stars](https://img.shields.io/github/stars/LimeSurvey/LimeSurvey?style=social&color=white)](https://github.com/LimeSurvey/LimeSurvey/stargazers)

  **The world's #1 open-source survey platform** (GPLv2) — **the veteran research-grade survey engine**, around since 2006 and trusted by universities, governments, and market researchers. **Features**: **30+ question types** with deep logic, quotas, and branching; **900+ survey templates**; multilingual surveys (80+ languages); SPSS/R/STATA export; **NPS question type supported**; GDPR compliance; two-factor authentication; SAML/LDAP integration; active community and ecosystem. **Tech stack**: PHP, MySQL/MariaDB/PostgreSQL. **Deploy**: Self-hosted (Docker, manual) or LimeSurvey Cloud. **Trade-off**: **Utilitarian interface** compared to Formbricks; heavier for simple in-app NPS. **Best for**: research teams, academics, and organizations running long-form questionnaires where question logic and statistical exports matter.

- **[DWSurvey](https://github.com/wkeyuan/DWSurvey)** [![GitHub stars](https://img.shields.io/github/stars/wkeyuan/DWSurvey?style=social&color=white)](https://github.com/wkeyuan/DWSurvey/stargazers)

  **Comprehensive open-source survey and questionnaire platform** (AGPLv3) — **designed for enterprise survey workflows and data collection**. **Features**: Flexible questionnaire design, score calculations, conditional logic, multi-channel distribution (web, QR code, email), statistical reporting, and role-based permissions. **Tech stack**: Java, Spring Boot, Vue.js, MySQL. **Deploy**: Self-hosted (Docker / Tomcat / Spring Boot JAR). **Trade-off**: Traditional survey experience; requires Java backend environment. **Best for**: enterprise IT teams needing an internal, self-hosted questionnaire and assessment system.

- **[Astuto](https://github.com/astuto/astuto)** [![GitHub stars](https://img.shields.io/github/stars/astuto/astuto?style=social&color=white)](https://github.com/astuto/astuto/stargazers)

  **Open-source customer feedback tool** (AGPLv3) — **popular choice for public feedback boards with voting and prioritization**. **Features**: Collect, manage, and prioritize user feedback; public boards with upvoting; designed for product roadmap input; clean and responsive UI. **Tech stack**: Ruby on Rails, Vue.js, PostgreSQL. **Deploy**: Self-hosted (Docker). **Trade-off**: **Feedback board, not NPS**—no NPS scoring, no survey logic, no analytics. **Best for**: product teams wanting a public feedback portal where users vote on feature requests—not measuring satisfaction.

- **[Obsei](https://github.com/obsei/obsei)** [![GitHub stars](https://img.shields.io/github/stars/obsei/obsei?style=social&color=white)](https://github.com/obsei/obsei/stargazers)

  **Open-source, privacy-first Voice of Customer (VoC) analytics platform** (Apache-2.0) — **AI-powered sentiment analysis and feedback processing**. **Features**: Ingests customer feedback from multiple channels (app store reviews, social media, surveys, Zendesk); strips PII before AI processing; performs sentiment analysis, text classification, and categorization; syncs insights to Slack, Jira, or data warehouses. **Tech stack**: Python, FastAPI, Hugging Face, LLMs. **Deploy**: Self-hosted (Docker / Python package). **Trade-off**: **Analytics and aggregation engine, not a collection form**—ingests existing feedback data. **Best for**: CX and product teams looking to automate text feedback categorization, sentiment extraction, and privacy-first feedback intelligence.

- **[LogChimp](https://github.com/logchimp/logchimp)** [![GitHub stars](https://img.shields.io/github/stars/logchimp/logchimp?style=social&color=white)](https://github.com/logchimp/logchimp/stargazers)

  **Customer feedback tracking and product roadmap platform** (Apache-2.0) — **open-source alternative to Canny and Productboard**. **Features**: Capture user feedback, organize feedback into boards, prioritize features via user upvoting, roadmap tracking, and changelog updates. **Tech stack**: Node.js, Express, Vue.js, PostgreSQL. **Deploy**: Self-hosted (Docker). **Trade-off**: **Feedback management, not NPS surveys**—focuses on feature requests and roadmap alignment. **Best for**: startups and indie hackers wanting to align user feature requests with public roadmap visibility.

- **[Feedbase](https://github.com/chroxify/feedbase)** [![GitHub stars](https://img.shields.io/github/stars/chroxify/feedbase?style=social&color=white)](https://github.com/chroxify/feedbase/stargazers)

  **Modern customer feedback collection and changelog system** (AGPLv3) — **lightweight feedback portal**. **Features**: Public feedback boards, user votes and comments, release changelogs, privacy settings, and modern UI. **Tech stack**: TypeScript, Next.js, Tailwind CSS, PostgreSQL (Prisma). **Deploy**: Self-hosted (Docker / Vercel + Postgres). **Trade-off**: Feedback board focused; no quantitative NPS scoring engine. **Best for**: modern web apps and SaaS products looking for a stylish feedback and changelog tool.

- **[FormsLab](https://github.com/Ryczko/FormsLab)** [![GitHub stars](https://img.shields.io/github/stars/Ryczko/FormsLab?style=social&color=white)](https://github.com/Ryczko/FormsLab/stargazers)

  **Form builder for anonymous surveys, polls, and customer feedback** (MIT) — **experience management and polling platform**. **Features**: Anonymous response collection, flexible drag-and-drop form building, real-time analytics, charts, and data privacy controls. **Tech stack**: Go, TypeScript, React. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: Lightweight tool; smaller community and integration ecosystem. **Best for**: teams needing privacy-preserving, anonymous user surveys with self-hosted simplicity.

- **[Wiredash](https://github.com/wiredashio/wiredash-sdk)** [![GitHub stars](https://img.shields.io/github/stars/wiredashio/wiredash-sdk?style=social&color=white)](https://github.com/wiredashio/wiredash-sdk/stargazers)

  **In-app user feedback and NPS SDK for Flutter apps** (Free / Open SDK) — **targeted feedback capture for cross-platform mobile apps**. **Features**: In-app NPS micro-surveys, visual bug reporting with annotated screenshots, contextual device metadata capture, and user feedback forms directly inside native mobile apps. **Tech stack**: Dart, Flutter. **Deploy**: Add package to Flutter app; integrates with Wiredash console. **Trade-off**: Flutter-specific client SDK; backend console has commercial cloud tiers. **Best for**: Flutter mobile developers wanting turnkey in-app NPS prompts and screenshot-annotated feedback.

- **[Volet](https://github.com/mydnic/volet)** [![GitHub stars](https://img.shields.io/github/stars/mydnic/volet?style=social&color=white)](https://github.com/mydnic/volet/stargazers)

  **Extensible customer feedback widget for Laravel applications** (MIT) — **simple in-app feedback slideout**. **Features**: Floating feedback button, screenshot capture, user rating/comment modal, customizable questions, and seamless Laravel database persistence. **Tech stack**: PHP, Laravel, Blade, JavaScript. **Deploy**: Composer package within Laravel projects. **Trade-off**: Framework-specific widget library; not a standalone SaaS or multi-platform dashboard. **Best for**: Laravel applications wanting an integrated in-app feedback popup without external third-party widgets.

- **[ABC User Feedback](https://github.com/line/abc-user-feedback)** [![GitHub stars](https://img.shields.io/github/stars/line/abc-user-feedback?style=social&color=white)](https://github.com/line/abc-user-feedback/stargazers)

  **Voice of Customer (VoC) feedback management platform by LINE** (Apache-2.0) — **standalone system for gathering and managing customer feedback**. **Features**: Multi-channel feedback aggregation, issue tagging and categorization, respondent tracking, search, and centralized VoC data organization. **Tech stack**: Java, Spring Boot, Vue.js, MySQL. **Deploy**: Self-hosted. **Trade-off**: Primarily internal VoC triage portal; requires custom integrations for frontline collection forms. **Best for**: support and CX teams managing high-volume incoming customer feedback across multiple touchpoints.

- **[Quackback](https://github.com/QuackbackIO/quackback)** [![GitHub stars](https://img.shields.io/github/stars/QuackbackIO/quackback?style=social&color=white)](https://github.com/QuackbackIO/quackback/stargazers)

  **Open-source alternative to Canny, UserVoice, and Productboard** (AGPLv3) — **customer feedback boards with SSO and embeddable widgets**. **Features**: Embeddable feedback widget, public board, voting, comments, status updates, user identification, and webhook alerts. **Tech stack**: TypeScript, Next.js, Tailwind CSS, PostgreSQL. **Deploy**: Self-hosted (Docker). **Trade-off**: Focused on feature prioritization; no survey logic or NPS index calculation. **Best for**: product-led growth companies wanting an embedded customer suggestion board.

- **[Refyyn](https://github.com/AbdullahSWE/Refyyn)** [![GitHub stars](https://img.shields.io/github/stars/AbdullahSWE/Refyyn?style=social&color=white)](https://github.com/AbdullahSWE/Refyyn/stargazers)

  **Self-hosted customer feedback tool with kanban roadmap and changelogs** (MIT) — **feedback-to-roadmap workflow**. **Features**: Admin dashboard for managing feedback; **public feedback board** with upvotes and comments; **public roadmap** (planned/in progress/completed); **changelog** for release notes; customizable boards and statuses. **Tech stack**: Laravel 12, Vue 3, Inertia.js, SQLite/MySQL/PostgreSQL. **Deploy**: Self-hosted (PHP 8.2+, Composer, Node 22+). **Trade-off**: **Feedback management, not NPS**—no survey scoring, no automated collection. **Best for**: product teams wanting feedback, roadmap, and changelog in one self-hosted tool.

- **[prometheus-nps](https://github.com/Zeb88/prometheus-nps)** [![GitHub stars](https://img.shields.io/github/stars/Zeb88/prometheus-nps?style=social&color=white)](https://github.com/Zeb88/prometheus-nps/stargazers)

  **NPS feedback system with AI analysis** (MIT) — **focused open-source NPS-specific implementation**. **Features**: **NPS feedback collection** (0-10 score + text); real-time NPS calculation; **AI-generated feedback summaries** via OpenAI; email integration for personalized form links; vector database storage (Supabase) for semantic search; CSV export; JWT authentication; rate limiting. **Tech stack**: Node.js, Express, Alpine.js, Supabase (PostgreSQL + pgvector), OpenAI, Resend. **Deploy**: Self-hosted (requires Supabase, OpenAI API key, Resend API key). **Trade-off**: **Early-stage project**—requires multiple external services (Supabase, OpenAI, Resend); not production-hardened. **Best for**: developers wanting a working NPS collection + AI analysis reference implementation.

- **[customersatisfactionmetrics](https://github.com/pescheckit/customersatisfactionmetrics)** [![GitHub stars](https://img.shields.io/github/stars/pescheckit/customersatisfactionmetrics?style=social&color=white)](https://github.com/pescheckit/customersatisfactionmetrics/stargazers)

  **Django package for customer satisfaction metrics** (MIT) — **reusable app for CSAT, NPS, CES, and generic surveys**. **Features**: Embedded survey models and views within Django apps; supports anonymous and authenticated user responses; metadata tracking; automatic calculation of NPS / CSAT / CES metrics. **Tech stack**: Python, Django. **Deploy**: Python package (pip install). **Trade-off**: Library/component, not a standalone platform; requires a parent Django project. **Best for**: Python/Django developers wanting to embed NPS or CSAT logic directly into their application backend.

- **[csat](https://github.com/ronpinkas/csat)** [![GitHub stars](https://img.shields.io/github/stars/ronpinkas/csat?style=social&color=white)](https://github.com/ronpinkas/csat/stargazers)

  **Self-contained CSAT survey and analytics in a single binary** (MIT) — **zero-dependency satisfaction survey tool**. **Features**: Encrypted SMS/email survey links, admin dashboard, multi-language support (English/Spanish), customizable branding, and single-file executable operation. **Tech stack**: Go. **Deploy**: Self-hosted (single compiled binary, no external DB required). **Trade-off**: **CSAT focused**—metric format is 1-5 customer satisfaction rather than standard 0-10 NPS. **Best for**: teams wanting an ultralight, single-binary feedback system for SMS or link-based satisfaction collection.

**Frameworks & Stack Recommendations**:
Combine **Formbricks** for in-app NPS with **Fider**, **Astuto**, or **Refyyn** for public feedback boards, **LimeSurvey** or **SurveyKing** for deep research questionnaires, and **Obsei** for AI-driven sentiment and Voice of Customer analytics—creating an end-to-end feedback ecosystem matched to every customer touchpoint.


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

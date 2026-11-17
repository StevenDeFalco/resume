# LinkedIn profile: paste-ready copy

Final revision, 17 November 2026, in step with `main.tex`. Text inside the grey boxes is ready to paste as-is (LinkedIn fields are plain text, so the bullets are real "•" characters). No client or partner is named.

## How the profile is divided

LinkedIn gives each section a different job, so each fact appears once in full and is only echoed elsewhere:

| Section | Job | Limit | What goes here |
|---|---|---|---|
| Headline | Search and first impression | 220 characters; about the first 60 show in search results and on mobile | Role, specialty, and credentials, most important words first |
| About | The story, in first person | 2,600 characters; roughly the first 300 show before "see more" (about 200 on mobile) | Who you are, proof in numbers, how you work, background |
| Experience | Evidence per role | Title 100; description 2,000 per role | The resume bullets (parity), plus up to five skills per role |
| Projects | Depth the resume has no room for | Description 2,000 each | What you built, each tied to a role and its own skills |
| Skills | Recruiter filters | Up to 100; the first three show on the profile; five can be pinned to About | Search terms, ordered by importance |
| Featured | Clickable proof | A handful of items | Resume PDF, GitHub, and the personal project |
| Education, Courses, Organizations | Completeness | Education description 1,000 | Degrees as three entries; coursework and leadership that left the resume |

## Intro card

- **Name:** Steven DeFalco
- **Headline:** below
- **Current position:** Solutions Engineer at Quant (tick "show in intro")
- **Education:** Stevens Institute of Technology (tick "show in intro")
- **Location:** New York, New York, United States
- **Industry:** Software Development (alternative: IT Services and IT Consulting, if you want to lean toward consulting searches)
- **Contact info:** email, plus Website entries for GitHub (`https://github.com/StevenDeFalco`) and your personal site (`https://stevendefalco.github.io`)
- **Custom URL:** `linkedin.com/in/stevendefalco` (already set)
- **Photo and banner:** a current headshot; a plain banner (1584 x 396) is fine

## Headline

```text
Solutions Engineer, Agentic AI at Quant | Voice AI agents and agentic process orchestration for enterprise operations | Client-facing technologist: discovery, solution design, working prototypes | MBA + ME, Applied AI
```

The first 60 characters ("Solutions Engineer, Agentic AI at Quant | Voice AI agents...") are what a recruiter sees in a results list.

## About

```text
I solve complex enterprise problems using modern agentic AI. As a solutions engineer at Quant, I pair hands-on engineering of agentic orchestration and workflows with business process expertise and executive communication: I run discovery with the client, design the solution, build the working system, and present it to the people who decide.

In the past year I have partnered with more than 40 enterprises across utilities, telecom, healthcare, financial services, and life sciences, and built more than 40 working prototypes. As the solutions engineer on a three-person deal team, I helped drive three telecom and utility deals, worth eight figures in multi-year contract value, to signature or final contracting.

What I build
• Voice AI agents for contact centers: streaming speech-to-text, LLM reasoning, text-to-speech, SIP telephony, and tool calling against the client's systems.
• Agentic process orchestration for the back office: meter-to-cash, order-to-cash, invoice-to-pay, and pharmacovigilance, on durable workflows with human approvals and audit trails.
• Production-grade prototypes that prove value before a client commits, so going live is integration, not a rebuild.

How I approach it
I do not stop at a recommendation. I analyze the client's business processes, identify the high-value use cases for AI and automation, then design and deliver agentic solutions that execute those processes end to end on their existing systems, cutting operating costs, shortening cycle times, and improving customer experience. From there I work with their operations and IT leaders on scope, integrations, success metrics, and the business case, so a proof of concept is always pointed at production.

How I work
I build with spec-driven, AI-assisted development in Claude Code and Cursor: plan first, small verified steps, every change reviewed. I also engineered my own agent harness around frontier models, with persistent memory, custom skills, guardrails, and scheduled autonomous agents, which is how one engineer carries this many builds at once.

Background
Before Quant I rebuilt a retrieval-augmented generation assistant and shipped field software on Azure at TCE, where I started as an intern. I hold an MBA and a Master of Engineering in Applied Artificial Intelligence from Stevens Institute of Technology, and a BS in Computer Science with highest honors.

Glad to compare notes on agentic AI in enterprise operations. Message me here.
```

**Top skills to pin to About (five):** Solutions Engineering, Agentic AI, Solution Architecture, Voice AI, AI Strategy

## Experience

### Quant

- **Title:** Solutions Engineer
- **Dates:** November 2025 to Present
- **Location:** New York, New York, United States
- **Employment type:** leave blank, or split into two positions, because the first seven months were part-time alongside graduate school
- **Skills for this role (five):** Solutions Engineering, Agentic AI, Solution Architecture, Voice AI, Pre-Sales

```text
Quant builds an agentic AI platform that runs enterprise operations end to end, from the contact center to the back office. I own discovery, solution design, working prototypes, and live demonstrations on enterprise opportunities sold directly and through a global consulting partner.

• Partner with 40+ enterprises across utilities, telecom, healthcare, financial services, and life sciences to analyze business processes, identify high-value use cases for AI and automation, and design and deliver agentic solutions that execute those processes end to end, cutting operating costs, shortening cycle times, and improving customer experience.
• Drove three telecom and utility deals worth eight figures in multi-year contract value to signature or final contracting as the solutions engineer on a three-person deal team: led technical discovery, designed the voice AI and agentic automation solutions, built the working prototypes, and presented them live to senior client executives.
• Designed and built 40+ working agentic AI prototypes from client SOPs and process flows, most within two weeks: voice AI agents for contact centers and agentic process orchestration for back-office work (see Projects).
• Engineer each as a production-grade platform that proves value before a client commits: durable Temporal workflows, human-in-the-loop approvals, audit trails, and a middleware layer of agent tools over emulated vendor APIs that mirrors the client's systems of record.
• Lead clients from proof of concept toward production: define scope, integrations, success metrics, and the business case with their operations and IT leaders; created the production-readiness playbooks used to scope client engagements.
• Build with spec-driven, AI-assisted development (Claude Code, Cursor): research and plan first, implement in small verified steps, and review every change, on a personal agent harness with persistent memory, 15+ custom skills, guardrails, and scheduled autonomous agents.
```
### TCE (two positions under one company; LinkedIn groups them automatically)

**AI Solutions Engineer**, May 2025 to October 2025, Great Neck, New York. Skills (five): Retrieval-Augmented Generation (RAG), Microsoft Azure, Python, LlamaIndex, React.

```text
Returned after my internship to build TCE's internal AI tools for engineers, estimators, and executives.

• Rebuilt an Azure-native RAG assistant from the ground up over hundreds of dense, confidential contract and technical documents (text, tables, and engineering drawings): query rewriting, hybrid semantic and vector retrieval, and cited answers (Azure AI Search, OpenAI API, LlamaIndex, Python).
• Raised the good-answer rate from 50% to 98% and the answer rate from 74% to 98% on a 100-query A/B test.
• Rebuilt document ingestion (LlamaParse to Markdown, custom chunking, embeddings; Azure Blob and SQL), lifting top-1 citation relevance from 32% to 76% and highlight accuracy from 10% to 56%.
• Designed and shipped an offline tunnel-clearance PWA (Ionic, React, TypeScript, Azure) that replaced paper-based safety checks on MTA-regulated tunnel installations with in-field verification, offline caching, and CSV export in the owner's format.
• Worked with non-technical stakeholders throughout to define requirements and present results.
```

**Innovation Engineering Intern**, May 2024 to August 2024, Great Neck, New York. Skills (five): Python, Microsoft Azure, Azure Functions, React, Process Automation.

```text
• Automated the migration of 1,000+ LMS courses with Python (Pandas, Playwright).
• Built production Azure Timer Functions that sync HR and LMS data in near real time, enabling accurate mass assignment of employee training.
• Built and shipped a secure React portal for site drone imagery, giving project teams open access and avoiding licensing costs.
• Earned a return offer and rejoined in 2025 as AI Solutions Engineer.
```

### Pixel Light Digital Media

**Software Testing and Quality Assurance Analyst**, June 2022 to August 2022, Lyndhurst, New Jersey. Skills: Software Testing, Computer Vision, Data Analysis.

```text
• Led testing of a real-time computer vision system for convention booth engagement tracking, improving distance prediction accuracy to within 2 ft over a 50 ft range.
• Produced business insights from 51,000+ data points to inform booth layouts, and worked with developers on stability for enterprise clients.
```

(Not on the resume, for space. It can stay here.)

## Projects

This is where the extra color goes. Each project is tied to a role ("Associated with") and carries its own skills, so the Experience entries stay short. The Quant projects describe work on emulated systems with fictional data.

### Energy and utilities agentic operations platform

Associated with Quant · September 2026 to November 2026 · Skills: Agentic AI, Temporal, Voice AI, SAP S/4HANA, Process Orchestration

```text
A platform that connects a utility's contact center to its back office, built to show how AI agents, people, and existing systems work one process together.

• One consistent data world: a fictional utility with 250 accounts and 24 months of history, behind emulated SAP S/4HANA Utilities, Itron meter data management, Salesforce, and Oracle outage management APIs, with a middleware layer of agent tools on top.
• Contact center: voice agents for payments, high bills, payment arrangements, and medical certificates, with every call traced step by step on the live process view.
• Back office: agents that work meter-to-cash exceptions (implausible reads, missing reads before billing, held bills, and revenue protection), propose a resolution with evidence, and route decisions to a human work queue.
• Regulatory: a rate case discovery workflow with drafted answers, consistency checks, and witness approval.
• Presented to utility executives and partner teams as a working example of agentic operations on their own kind of systems.

Stack: Temporal, Node.js, React, MongoDB, LiveKit, Anthropic models. Built with spec-driven, AI-assisted development.
```

### Pharmacovigilance case-processing pilot

Associated with Quant · October 2026 · Skills: Agentic AI, Pharmacovigilance, Human-in-the-Loop, LLM Agents, Life Sciences

```text
An adverse-event case-processing pilot for a life sciences opportunity, built in about two weeks on public safety data.

• A case arrives as an ICH E2B(R3) XML file. AI agents extract, classify, and code what the narrative says, up to about 600 data points per case, using MedDRA for events and a WHODrug-shaped dictionary for products.
• A human case processor reviews every field side by side with the source, corrects it with a reason, and approves. Nothing is released without that review.
• Deterministic rules then post-process the case, and the output records the AI value, the source value, and the accepted value for every field.
• Those three values feed an AI governance dashboard that tracks accuracy by field, with a full audit trail.
• Processing takes about one minute per case before human review.
```

### Order-to-cash agentic operations platform

Associated with Quant · September 2026 to November 2026 · Skills: Order-to-Cash, Agentic AI, Voice AI, Collections, Process Orchestration

```text
A finance-operations platform that shows AI agents working order-to-cash across voice, email, and the back office.

• Inbound customer care by voice: caller verification, order and account questions, returns, proof-of-delivery requests, and a secured card payment in which the card digits never reach the model.
• Outbound collections: a call wave driven from the receivables platform, with promises to pay, disputes, and hand-offs recorded as they happen.
• Dispute resolution end to end: intake, evidence gathering, a recommendation, the sales decision, the credit memo, and close with a root cause.
• Built on emulated SAP ECC, Billtrust, bank, and mail systems, so every agent action is a real call to a realistic API.
```

### Voice AI agents for enterprise contact centers

Associated with Quant · November 2025 to Present · Skills: Voice AI, Conversational AI, SIP, ElevenLabs, Twilio

```text
A body of voice agents built for enterprise contact-center use cases across telecom, utilities, insurance, healthcare, banking, and travel.

• Stack: streaming speech-to-text, LLM reasoning, and text-to-speech on ElevenLabs and LiveKit, SIP telephony through Twilio, and tool calling against a middleware layer in front of the client's systems.
• Patterns: caller verification, multi-intent handling, approval before any consequential action, warm hand-off to a person with full context, outbound calling, and post-call analysis.
• Languages: English, Portuguese, Spanish, French, Chinese, and Japanese.
• Examples: a multi-intent customer care line for a telecom, outbound B2B collections, a no-water service line for a water utility with about 20 scenarios, and a payroll helpline covering 28 call types in three languages.
• Testing: scripted offline tests for each use case, then rehearsed live calls before every showing.
```

### Personal agent harness

Associated with Quant · 2026 · Skills: Agent Harness Design, Context Engineering, Claude Code, AI-Assisted Software Development, Agentic AI

```text
The system I built around frontier models to multiply my day-to-day productivity: AI that works the way I need it to, across every account I carry.

• Persistent memory: a self-maintaining knowledge base that agents read before they act and update after.
• Scheduled autonomous agents that ingest email, chat, and meeting transcripts every morning and brief me on what needs my attention.
• 15+ custom skills for recurring work, each with its own standards and checks.
• Guardrails: policy hooks that limit what an agent may touch, and verification gates before anything is committed.
• A planner-and-implementer method for software builds: research and plan first, implement in small steps, and verify every change.
```

### predictMLB

Associated with Stevens Institute of Technology · 2023 · Skills: Machine Learning, Python, LightGBM, AWS

```text
An autonomous bot that posts same-day MLB game predictions to X/Twitter. A LightGBM model trained on more than five years of game data, fed by fully automated data pipelines and scheduled on AWS, reached 66% accuracy on a 1,100-game backtest.
```

Project link: `https://github.com/StevenDeFalco/predictMLB`

## Education (three separate entries, so each degree is searchable)

| Degree | Field of study | Dates | Grade |
|---|---|---|---|
| Master of Business Administration (MBA) | Business Administration | January 2025 to May 2026 | 3.96 |
| Master of Engineering (ME) | Applied Artificial Intelligence | January 2025 to May 2026 | 3.96 |
| Bachelor of Science (BS) | Computer Science | September 2021 to December 2024 | 3.86 |

For the BS entry:

- **Activities and societies:** Alpha Sigma Phi (Vice President); Computer Science Course Assistant
- **Description:**

```text
Graduated with Highest Honors. Coursework included natural language processing, computer vision, deep learning, database management, statistics, and data structures and algorithms. As a Computer Science Course Assistant I led Data Structures labs with live coding and one-to-one instruction.
```

## Skills (up to 100; order matters)

Put these first, in this order. The first three show on your profile and recruiter searches filter on them:

1. Solutions Engineering
2. Agentic AI
3. Solution Architecture
4. Voice AI
5. AI Strategy

Then add, attaching each to the role or project where you used it:

- **AI and agents:** AI Agents, Large Language Models (LLM), Multi-Agent Systems, Agentic Orchestration, Retrieval-Augmented Generation (RAG), LLM Evaluation, Conversational AI, Model Context Protocol (MCP), Prompt Engineering, Context Engineering, Human-in-the-Loop, Generative AI, Machine Learning
- **AI development tools:** Claude Code, Cursor, Claude, AI-Assisted Software Development, Agent Harness Design
- **Engineering:** Python, TypeScript, SQL, JavaScript, Microsoft Azure, Amazon Web Services (AWS), React, Node.js, Temporal, MongoDB, CI/CD, Git, Azure AI Search, Azure Functions, Twilio, SIP, ElevenLabs, LlamaIndex, Linux
- **Business and consulting:** Pre-Sales, Technical Discovery, Process Orchestration, Business Process Automation, Requirements Gathering, Executive Presentations, Stakeholder Management, Business Case Development, Order-to-Cash, Procure-to-Pay, Meter-to-Cash, Collections, Contact Center, Pharmacovigilance, SAP S/4HANA, Salesforce

That is about 55 skills. The business processes belong here as search tags even though the resume's skills section no longer lists them.

## Featured (three items)

1. **Resume:** upload `main.pdf` as a document.
2. **GitHub:** link to `https://github.com/StevenDeFalco`.
3. **predictMLB:** link to `https://github.com/StevenDeFalco/predictMLB`.

Do not feature anything from Quant client work.

## Other sections

- **Organizations:** Alpha Sigma Phi, Vice President: led a 40-member chapter and oversaw about 25 events a semester.
- **Courses (optional):** NLP, Computer Vision, Deep Learning, tied to the degree they belong to.
- **Recommendations:** two or three from people who have seen you present or build carry more weight than any line above.
- **Licenses and certifications, Languages, Volunteer experience:** add only what is real; an empty section is better than a thin one.

## Parity with the resume

| Resume | LinkedIn |
|---|---|
| Summary line | Headline and the first paragraph of About |
| Quant bullets 1, 2, and 5 | Quant experience, same wording |
| Quant bullets 3 and 4 (what was built and how) | Quant experience in brief; detail in the four Quant projects |
| Quant bullets 6 and 7 (method and harness) | Quant experience, merged; detail in the Personal agent harness project |
| TCE, both roles | Same facts, with the highlight-accuracy result, ingestion detail, and stakeholder work restored |
| Skills and Technologies | Skills section, plus the business-process tags |
| Education | Three entries, with coursework and activities restored |
| predictMLB | Projects and Featured |
| Not on the resume | Pixel Light role, coursework, and Alpha Sigma Phi |

Numbers that must stay identical in both: 40+ enterprises, 40+ prototypes, three deals worth eight figures, 15+ custom skills, 50% to 98%, 74% to 98%, 32% to 76%, 1,000+ courses, and 66% on a 1,100-game backtest.

## Before publishing

- LinkedIn is public and indexed, so the anonymization matters more here than on the resume. Nothing above names a client or the consulting partner.
- Links typed into About or an Experience description are not clickable; use Contact info, Featured, and the project link fields instead.

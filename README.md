# InstaHelp Real-Time Service Recovery

<p align="center">
  <img src="https://img.shields.io/badge/Portfolio-Case%20Study-blueviolet" alt="Portfolio case study" />
  <img src="https://img.shields.io/badge/Product-Strategy-orange" alt="Product strategy" />
  <img src="https://img.shields.io/badge/AI-Recovery%20Flow-green" alt="AI recovery flow" />
  <img src="https://img.shields.io/badge/UX-Service%20Reliability-9cf" alt="UX reliability" />
</p>

A product design and strategy case study focused on fixing one of the biggest hidden problems in on-demand home services: what happens when a booked professional cancels unexpectedly.

This project turns a real business problem into a compelling portfolio story—showing how a platform can recover trust, protect revenue, and reduce operational failure through a fast, human-centered recovery system.

## Why this matters
Urban Company’s InstaHelp business has meaningful demand but loses money because the service experience breaks at the point of failure. When a professional cancels last-minute, the customer is often left in a dead-end support loop, and some bookings are marked complete without actual service delivery.

That creates three problems:

- lost contribution margin per order
- weaker trust in premium service pricing
- damaged customer retention and lifetime value

This project solves that by redesigning the recovery flow around real-time automation, customer clarity, and service reliability.

## Product objective
Build a recovery engine that ensures every cancellation resolves into one of the following outcomes:

- automatic reassignment to another qualified professional
- fast and transparent customer choice flow
- clear cancellation and refund resolution when recovery fails
- full event tracking for accountability and trust

## Key product principles
- Reliability over speed alone
- Zero dead ends for the customer
- Fast recovery within clear SLA thresholds
- Trust preservation through transparent communication
- Operational accountability in every recovery event

## Core features
- cancellation detection for active bookings
- automatic rematch and reassignment logic
- customer-facing recovery decision flow
- fallback refund / support resolution
- event logging and auditable booking history
- metrics dashboard for recovery success and trust signals

## Business impact
- protects revenue from failed bookings
- removes churn caused by broken cancellation resolution
- reduces support friction and escalation costs
- rebuilds premium pricing credibility through reliability

## Portfolio positioning
This is not just a demo app. It is a product-thinking portfolio project that demonstrates:

- problem framing from a real business challenge
- UX design for critical service failure states
- AI-assisted operational recovery workflows
- analytics and reliability metric thinking
- product strategy grounded in revenue and customer trust

## Screenshots from the prototype

### 1. Auto recovery in progress
![Auto recovery in progress](mobile%20screen/stitch_instahelp_real_time_recovery_experience/auto_recovery_in_progress_finding_replacement/screen.png)

### 2. Booking recovered and reassigned
![Booking recovered and dispatched](mobile%20screen/stitch_instahelp_real_time_recovery_experience/booking_recovered_new_professional_dispatched/screen.png)

### 3. Service verification and completion protection
![Verification and completion protection](mobile%20screen/stitch_instahelp_real_time_recovery_experience/service_verification_otp_completion_protection/screen.png)

### 4. Recovery failure and instant resolution
![Recovery failure and instant refund flow](mobile%20screen/stitch_instahelp_real_time_recovery_experience/recovery_failed_instant_resolution_refund/screen.png)

## User flow summary
1. Customer books a service.
2. Assigned professional cancels unexpectedly.
3. System detects the issue and triggers recovery.
4. Matching engine finds the best nearby alternative.
5. If no alternative exists, customer gets a clear refund or support path.
6. Every event is logged for operational transparency.

## Tech stack
- Frontend: Vite + JavaScript + HTML + CSS
- Design direction: mobile-first product UI
- Product workflow: real-time service recovery concept
- Delivery: GitHub portfolio-ready prototype

## Repo structure

```text
.
├── README.md
├── context.md
├── plan.md
├── index.html
├── src/
├── package.json
├── vite.config.js
├── mobile screen/
│   └── stitch_instahelp_real_time_recovery_experience/
├── PRD.docx
└── .gitignore
```

## Run locally

```bash
cd "/Users/pranjalvaswani/Desktop/sunday workshop PRD Repo"
npm install
npm run build
npm run dev -- --host 0.0.0.0
```

Then open:

- http://localhost:3000/

## What makes this portfolio-worthy
This project combines business analysis, user experience, and product strategy in one story. It communicates that the creator can think beyond feature building and focus on metrics, trust, and real user pain points.

## AI image generation prompts for storytelling
These are four prompt ideas to generate visual storytelling assets for the project:

1. "A premium fintech-style product mockup showing an on-demand home-services app detecting a cancellation, with a calm AI recovery dashboard, smart matching, and a modern urban India aesthetic, cinematic lighting, subtle gradients, product design shot."

2. "A polished mobile product hero image for a service marketplace, featuring an AI-powered reassignment workflow, real-time professional matching, trust signals, and a premium yet operationally crisp UI, clean product photography style, high contrast."

3. "An editorial portfolio graphic illustrating the business problem of last-minute cancellations in a home services platform, showing customer frustration, automated recovery, and revenue protection, minimalist tech product storytelling, premium brand feel."

4. "A premium portfolio banner for a product case study on reliability and trust, showing a customer booking flow, service disruption recovery, refund path, and AI-assisted resolution, modern SaaS design aesthetic, high-end presentation, dark and light balanced composition."

## Final note
This project is designed to be attractive to hiring managers and product stakeholders because it shows end-to-end product thinking: problem, strategy, UX, metrics, and execution.

## License
For portfolio use and learning purposes.

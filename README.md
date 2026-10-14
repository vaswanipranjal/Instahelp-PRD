# InstaHelp Real-Time Service Recovery

<p align="center">
  <img src="https://img.shields.io/badge/Portfolio-Case%20Study-7c3aed" alt="Portfolio case study" />
  <img src="https://img.shields.io/badge/Product-Strategy-orange" alt="Product strategy" />
  <img src="https://img.shields.io/badge/AI-Recovery%20Flow-10b981" alt="AI recovery flow" />
  <img src="https://img.shields.io/badge/UX-Reliability-0ea5e9" alt="UX reliability" />
</p>

A portfolio-ready product strategy and UX case study focused on one of the biggest operational pain points in on-demand home services: when an assigned professional cancels at the last minute.

This project frames a real business problem as a product opportunity: preserve trust, recover failed bookings, and protect margin without adding more supply or disrupting the core business.

## Why this project matters
Urban Company’s InstaHelp vertical shows how reliability can break a premium service experience even when demand is strong. The business may acquire customers and bookings, but it loses money when cancellations create broken journeys, unresolvable chatbot loops, and false completion states.

That creates a business problem beyond just a bad customer experience:

- lower contribution margin per booking
- weaker trust in premium pricing
- higher customer churn and support cost
- reduced confidence in the platform itself

This project translates that pain into a recovery-first product design aimed at turning failure into trust-preserving resolution.

## Product objective
Build an AI-powered recovery system that ensures every cancellation resolves into one of three outcomes:

- automatic reassignment to a qualified alternative professional
- a clear customer decision flow with minimal effort
- transparent cancellation or refund resolution when no replacement is possible

## Core product principles
- Reliability is the differentiator, not just speed
- Customers must never reach a dead end
- Recovery should feel proactive, not punitive
- Every cancellation must be auditable and measurable
- Trust should be rebuilt through clarity, not extra steps

## What this system does
- detects active booking cancellations in near real time
- scores nearby eligible professionals for reassignment
- automatically attempts a rematch without forcing the customer to restart
- gives users a fast and simple recovery option flow
- logs each action for operational accountability
- creates a metric framework for improving through real data

## Business impact
- protects revenue from booking failures
- reduces churn caused by broken service recovery
- lowers support overhead from escalations and dead-end flows
- keeps trust intact in premium service pricing
- demonstrates product thinking beyond hypothesis and into business value

## Portfolio fit
This project is especially valuable for product, strategy, and UX portfolios because it shows:

- customer problem framing from a real operating challenge
- design thinking for failure states and recovery journeys
- AI-assisted workflow logic in a practical business setting
- measurable product metrics and operational impact
- an end-to-end story from product problem to recovery solution

## Prototype screens

### 1. Auto recovery in progress
![Auto recovery in progress](mobile%20screen/stitch_instahelp_real_time_recovery_experience/auto_recovery_in_progress_finding_replacement/screen.png)

### 2. Booking recovered and new professional dispatched
![Booking recovered and reassigned](mobile%20screen/stitch_instahelp_real_time_recovery_experience/booking_recovered_new_professional_dispatched/screen.png)

### 3. Service verification and completion protection
![Verification and completion protection](mobile%20screen/stitch_instahelp_real_time_recovery_experience/service_verification_otp_completion_protection/screen.png)

### 4. Recovery failure with instant resolution
![Recovery failure and refund flow](mobile%20screen/stitch_instahelp_real_time_recovery_experience/recovery_failed_instant_resolution_refund/screen.png)

## User journey summary
1. A booking is scheduled.
2. The assigned professional cancels unexpectedly.
3. The system detects the event in near real time.
4. A recovery engine checks for eligible alternatives.
5. The customer is offered a smooth reassignment or clear fallback path.
6. The full history is logged for accountability and learning.

## Tech stack
- Frontend: Vite + HTML + CSS + JavaScript
- Product prototype: mobile-first UX mockup
- Design approach: premium service app concept
- Delivery: GitHub-ready portfolio case study

## Repo structure

```text
.
├── README.md
├── context.md
├── plan.md
├── portfolio-summary.md
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

Then open the local app at:

- http://localhost:3000/

## Why this is attractive as a portfolio project
This project shows a full product lens: business problem, user pain, recovery design, metrics, and execution. It is a strong case study for product managers, operators, and designers because it tells a credible story grounded in real reliability issues instead of a generic app idea.

## AI image prompt pack
These are four polished prompts to generate visual assets for portfolio use, LinkedIn posts, or a pitch deck.

1. "A premium product-design hero image for an on-demand home services app showing an AI-powered recovery dashboard, real-time professional reassignment, customer trust signals, and a crisp modern Indian urban aesthetic, cinematic lighting, soft gradients, product mockup composition."

2. "A sleek mobile app storefront mockup illustrating a customer booking failing because a professional canceled, followed by an AI-assisted replacement flow, clean premium SaaS interface, high-end product design, polished UI, UX showcase, realistic services context."

3. "An editorial product case study graphic showing reliability, trust, and revenue protection in a home services platform, with automated recovery, support fallback, and transparent customer communication, premium architecture style, minimal but high-contrast design."

4. "A modern portfolio banner for a service reliability project, featuring the customer journey from booking to cancellation to instant recovery, AI matching, operational dashboard, and premium on-demand lifestyle branding, high-end product storytelling composition."

## GitHub push steps
To publish this repo publicly on GitHub, run:

```bash
git add .
git commit -m "Polish InstaHelp portfolio README and project summary"
git branch -M main
git remote add origin https://github.com/vaswanipranjal/Instahelp-PRD.git
git push -u origin main
```

If the remote already exists, use:

```bash
git remote set-url origin https://github.com/vaswanipranjal/Instahelp-PRD.git
git push -u origin main
```

## Final note
This project is built to be easy to understand, visually strong, and convincing to recruiters and hiring managers because it combines real-world pain, product thinking, and execution in a single portfolio story.

## License
For portfolio and learning use.

# Cloud Pace

**An unofficial AZ-900 study planner.** Not affiliated with or endorsed by Microsoft.

**Live demo:** https://cloud-pace.vercel.app

Built for the Vibe Coding Hackathon: AZ-900 Exam Prep Edition.
**Challenge track:** Personal Study Planner.

## The problem

Learners preparing for AZ-900 often have limited time and no clear idea where to focus. A generic checklist treats every topic the same, even though each learner is weak in different areas.

## What it does

1. **Setup:** enter your exam date, the hours you can study each week and the domains that feel weak.
2. **Your plan:** get a week-by-week revision schedule. Domains you marked weak get extra sessions, and each session shows how long to spend on it. The app warns you when your hours are tight.
3. **Practice check:** answer short original questions with instant feedback and a plain-language explanation for every answer.
4. **Adaptive plan:** any domain where your practice score falls below 60% automatically gets extra sessions, shown with a "low score" tag, so the plan changes as you improve.
5. **Progress:** see accuracy per domain, an overall readiness score and a suggested next step.

## Coverage

Each explanation also includes a short real-life example from everyday Kenyan life. Original practice questions across the three AZ-900 exam domains:

- Cloud concepts
- Azure architecture and services
- Management and governance

All questions and explanations were written for this project. They are **not** real exam questions. Always check Microsoft Learn for the official skills outline.

## How it was built

- Vibe coded with Claude as a design and content partner: planning the scope, writing the original questions and explanations, and building the planner logic.
- A single-file web app (HTML, CSS and JavaScript) with no build step and no external dependencies except a web font.
- Progress is saved in the learner's browser (localStorage). There are no accounts and no data leaves the device.
- Hosted on Vercel.

## Limitations (prototype)

- 15 practice questions in total (5 per domain).
- No user accounts, so progress does not sync between devices.
- Readiness is a simple accuracy-based estimate, not a prediction of the real exam result.

## What is next

The planner engine is separate from its content. Swapping the topic list and question set turns it into a planner for other subjects. One planned use is helping literature students split a long reading list across a 13-week semester and revise each text on schedule.

## Disclaimer

Cloud Pace is an independent educational project. Microsoft, Azure and AZ-900 are trademarks of Microsoft Corporation. No Microsoft logos are used.

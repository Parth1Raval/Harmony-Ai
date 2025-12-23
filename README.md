HarmonyAI – Generative AI Workplace Harmony Coach
HarmonyAI is a prototype Generative AI coach for workplace culture, designed especially for IT teams. It analyzes team chat exports (Slack/Teams/email) to detect envy‑driven toxicity and then generates personalized interventions for employees, managers, and HR.

🔍 What Problem It Solves
In many teams, events like promotions, public praise, or performance reviews can trigger envy, resentment, and silent rivalry. That often leads to gossip, passive aggression, and eventually higher attrition and loss of productivity. Traditional HR tools focus on surveys and dashboards, but rarely tell leaders what to say or do next.

HarmonyAI turns real conversation data into actionable, role‑specific coaching to prevent culture damage before it becomes a crisis.

⚙️ How HarmonyAI Works
Upload Team Chat Data

HR or managers export a Slack/Teams/email conversation in JSON, CSV, or TXT format.

The file is uploaded through a web dashboard.

Sentiment & Risk Analysis

Messages are parsed and grouped by user and time.

A sentiment and pattern analysis pipeline flags:

Negative spikes after positive events (e.g., promotions).

Repeated resentful or unfairness‑related language.

The dashboard shows:

Total Team Members.

Number of Risk Signals (potential envy/toxicity points).

A simple NPS / culture‑health projection.

Generative AI Coaching Plan

When risk is high, the user clicks “Generate Harmony Plan”.

The backend calls a Generative AI model with the risky messages and context to create three outputs:

Employee Empathy Story – reframes envy into growth and collaboration.

Manager 1:1 Script – a step‑by‑step conversation guide to address perceived unfairness.

HR Guidance Note – suggested policies, training, or communication actions.

Content can be generated in English or Hindi, with hooks for adding more languages.

Impact View

The app estimates the potential improvement in attrition risk and culture health after applying the interventions and visualizes it in a simple metrics view.

🧱 Tech Stack (Prototype)
Frontend: Next.js / React, Tailwind CSS (and component library) for the HarmonyAI dashboard

Backend: Node/TypeScript serverless handlers for file parsing, risk scoring, and GenAI orchestration

AI / Analytics:

Sentiment and pattern analysis over chat timelines

Generative AI model for narrative coaching (employee, manager, HR)

Deployment: Designed to run on a cloud‑native stack with serverless APIs and static frontend hosting

🚀 Current Features
Upload Slack/Teams‑style chats in JSON/CSV/TXT

Automatic extraction of team size and message timeline

Simple envy‑risk scoring based on language and context

Dashboard cards for Team Members, Risk Signals, and NPS Projection

One‑click generation of:

Employee empathy story

Manager conversation script

HR guidance summary

Language toggle (e.g., English ↔ Hindi) for interventions

📈 Future Roadmap
Direct integration with Slack/Teams APIs (no manual uploads)

More advanced ML model for envy / rivalry detection

Expanded language support for additional Indian and global languages

Employee‑facing self‑service bot for private micro‑coaching

Rich analytics for HR (trend tracking, anonymized org‑level insights)

🧪 Use Cases
After promotions or performance reviews to check for hidden resentment

When a manager senses “silent tension” in team chats

HR investigations into repeated complaints about bias or unfairness

Training new managers on handling recognition and social comparison in teams


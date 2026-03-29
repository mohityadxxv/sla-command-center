🖥️ SLA Command Center
A real-time AI-powered SLA monitoring dashboard for QA and support operations.
Built by Mohit · MTech Labs · QA × AI Portfolio
🔗 Live Demo →
� � � �
Load image
Load image
Load image
Load image
What This Is
SLA Command Center is a premium, single-file dashboard that simulates what an AI-powered SLA monitoring system looks like in a real enterprise support operation.
It was built to demonstrate the intersection of Quality Assurance domain expertise and AI product thinking — showing not just what the data looks like, but why each component exists, what problem it solves, and what decisions the AI layer enables.
Features
📊 Live Dashboard
4 KPI cards — SLA Compliance Rate, Active Breach Risk, Avg Handle Time, Open P1 Tickets
Live Ticket Queue — 20-ticket pool with real-time rotation, SLA consumption bars, priority badges (P1–P4), and breach status indicators
Team SLA Health — compliance scorecards across 5 support queues with colour-coded thresholds
Top Breach Causes — weekly RCA breakdown with relative frequency bars
7-Day Compliance Trend — canvas-rendered chart with target reference line
AI Alert Feed — severity-tiered alert stream with live rotation
🧠 AI Intelligence Layer
A slide-in drawer that documents the full product thinking behind the dashboard:
Section
What It Contains
User Problem
The real operational pain this solves
AI Solution
Rule-based + ML-assisted logic, with honest caveats
Decision Layer
5 prescriptive AI capabilities (auto-escalation, smart reassignment, coaching triggers, etc.)
Success Metrics
Measurable targets tied to each capability
Risks & Mitigations
Data staleness, alert fatigue, adoption friction
Business Impact
Estimated cost savings and capacity recovery
✦ Contextual Insight Icons
Every widget has a ✦ icon that opens a micro product brief explaining:
The user problem that widget addresses
How the AI/logic works
The one key success metric
🎨 Dual Theme
Full dark and light theme support with smooth transitions. Preference saved to localStorage.
Live Simulation
The dashboard runs a simulation engine that updates every 6 seconds:
Ticket queue rotates from a pool of 20 tickets — SLA % on at-risk tickets increments over time
New alerts surface in the feed as "just now" and age in real time
Team compliance scores drift ±1–2% to reflect queue dynamics
P1 count and breach risk KPIs update to match the visible ticket set
This makes the demo feel like a live operations environment rather than a static prototype.
Tech Stack
Layer
Technology
UI Framework
Vanilla HTML / CSS / JS (zero dependencies)
Typography
Syne (display) + DM Mono (data) via Google Fonts
Charts
Native Canvas API
Deployment
GitHub Pages (single file)
Theme Storage
localStorage
No build tools. No npm. No frameworks. One file, fully self-contained.
Design Decisions
Why no framework?
Speed of deployment and zero setup friction. A single index.html can be dropped anywhere — GitHub Pages, Netlify, a USB stick, a screen share in an interview. No build step, no broken dependencies.
Why simulated data instead of a live backend?
This is a portfolio demonstration of QA + AI product thinking. The value is in the decision architecture and the intelligence layer, not the data pipeline. A backend can be added in a later iteration (see Roadmap).
Why document the product thinking inside the dashboard itself?
Because the audience for this tool includes both technical reviewers (who want to see the code) and non-technical stakeholders (who want to understand the value). The AI Intelligence Layer drawer bridges that gap without requiring a separate deck.
Roadmap
[ ] Claude API integration — live AI-generated breach summaries and coaching recommendations
[ ] Google Sheets backend — agents log tickets to a Sheet; dashboard reads via API
[ ] Export to PDF — one-click daily SLA report generation
[ ] Role-based views — Agent view vs. QA Lead view vs. Leadership view
[ ] Webhook alerts — push critical breach alerts to Slack or email
About the Builder
Mohit — Quality Analyst II with 7 years of experience, currently repositioning as an AI Lead and GenAI Consultant.
Built three internal AI systems at his current organisation:
AuditSphere — multi-agent call compliance and coaching platform (GPT-4o + n8n)
Insights by Mohit — AI-powered CSAT/DSAT analytics dashboard
Prompt Grader — client-side AI prompt scoring tool (deployed via Netlify)
This dashboard is part of a public portfolio under the MTech Labs identity, demonstrating that QA expertise and AI product thinking are not separate disciplines — they're strongest when combined.
📎 LinkedIn: linkedin.com/in/mkyakamohit
🐙 GitHub: github.com/mohityadxxv
Usage
# No installation needed.
# Clone the repo and open index.html in any browser.

git clone https://github.com/mohityadxxv/sla-command-center.git
cd sla-command-center
open index.html
Or just visit the Live Demo directly.
Built with intent. Documented with purpose. Shipped as proof.

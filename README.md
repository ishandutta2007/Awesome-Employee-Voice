# Awesome-Employee-Voice

## Top Employee Voice Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Employee Engagement Surveys, Sentiment Analysis & Feedback Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Voice**. These tools enable organizations to collect anonymous feedback, run pulse surveys, measure engagement and eNPS, and analyze sentiment—giving employees a structured channel to influence their workplace while giving leaders actionable insights.



**Examples** include Workday Employee Voice (Peakon), Culture Amp, Lattice, Glint, Qualtrics Employee Experience, Perceptyx, 15Five, Workvivo, Leapsome, and Officevibe (the category leaders).



**Open-source emphasis**: Employee Voice is a domain where open-source tooling is **emerging but fragmented**. The strongest active project is **Alignify**, an AI-powered anonymous survey platform with automated question generation and sentiment classification. **Check-Ins** (Object Computing) provides a broader team engagement platform with pulse surveys and feedback management. However, no open-source platform matches the sentiment analytics depth, benchmark data, and enterprise integrations of Workday Peakon or Culture Amp. Organizations requiring sophisticated NLP sentiment analysis and benchmark comparisons should plan for commercial platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Employee Voice (Peakon)](https://www.workday.com/)**  

  AI-powered employee engagement platform with scalable pulse surveys, powerful NLP sentiment analytics for parsing open-ended comments, and benchmark data; users praise its scalability for global directories and real-time data aggregation, though the dashboard can feel visually cluttered . Gartner Peer Insights rating: 4.3 stars .



- **[Culture Amp](https://www.cultureamp.com/)**  

  Employee experience platform with engagement surveys, sentiment analysis, heat maps, and AI coaches built into the platform; users report that native AI analysis has eliminated the need for external tools to summarize verbatim comments .



- **[Lattice](https://lattice.com/)**  

  Performance and engagement platform with surveys, goals, 1:1s, and continuous feedback; AI capabilities reduce review preparation time and encourage consistent feedback across teams .



- **[Glint (Microsoft Viva)](https://www.microsoft.com/en-us/microsoft-viva)**  

  Employee engagement platform integrated into Microsoft Viva; convenient for organizations already using Microsoft 365 and Teams, providing engagement insights within the productivity ecosystem .



- **[Qualtrics Employee Experience](https://www.qualtrics.com/)**  

  Enterprise experience management platform with employee engagement surveys and analytics; users note the dashboard is straightforward for HR teams but API data export can be messy for technical teams needing raw text .



- **[Perceptyx](https://www.perceptyx.com/)**  

  Employee listening platform with surveys, analytics, and action planning for enterprise organizations.



- **[15Five](https://www.15five.com/)**  

  Performance management with weekly check-ins, engagement surveys, and manager-employee conversations.



- **[Workvivo](https://www.workvivo.com/)**  

  Employee communication and engagement platform (acquired by Zoom) with social feeds, recognition, and surveys.



- **[Leapsome](https://www.leapsome.com/)**  

  Comprehensive performance management with goals, engagement surveys, and development features.



- **[Officevibe](https://officevibe.com/)**  

  Employee engagement platform with pulse surveys, feedback, and team insights (now part of Workleap).



## Open-Source GitHub Projects



- **[Alignify](https://github.com/iam-tsr/alignify)**  

  AI-powered employee engagement platform (early beta) with anonymous survey collection; uses **Qwen model for automated question generation** (~8 seconds for 10 questions) and **DistilBERT for feedback sentiment classification** (~2 seconds per classification); management dashboard provides graphical insights and AI-generated improvement suggestions . Python/CSS/JavaScript stack with Dockerfile included. **The most purpose-built open-source employee voice tool** with genuine AI automation, though early-stage and single-contributor.



- **[Check-Ins](https://github.com/objectcomputing/check-ins)**  

  Comprehensive open-source team engagement platform built on Micronaut and React, deployable on-premises or GCP; features **Pulse Surveys** for gauging team sentiment, **Feedback Management** for employee growth, performance reviews, public Kudos, skill tracking, and mentor program management . Actively used at Object Computing. **Broader HRIS/engagement suite** rather than voice-specific, but includes the core pulse survey functionality.



- **[WorkMate](https://github.com/karlis0099/WorkMate)**  

  Open-source employee wellbeing platform (Java desktop app with web UI) focused on **weekly check-ins** with 7 psychological wellbeing sliders (mood, energy, motivation, stress, work-life balance, team connection, accomplishment); manager dashboard shows burnout risk alerts, heat-map colored survey data, and CSV export; includes Slack/Teams webhook for HIGH-risk submissions . **Wellbeing-focused** rather than general employee voice, but provides structured feedback collection with burnout detection.



- **[feedback-hub-core](https://www.npmjs.com/package/feedback-hub-core)**  

  Framework-agnostic TypeScript core for a reusable feedback platform (npm package); provides feedback records with department/area references, 1-5 ratings, required text comments, categories/tags, priority levels, **explainable 0-100 impact scoring**, trend analytics, and follow-up task creation . **Infrastructure library**—not a complete employee voice application, but provides the feedback collection and scoring primitives for building one.



### Additional Strong Open-Source Options



- **erxes** — Source-available experience management infrastructure (3,527 GitHub stars, TypeScript) positioned as a Hubspot + Qualtrics alternative; broader customer/employee experience platform that can be configured for employee feedback . **Source-available** rather than fully open-source; large codebase requiring significant customization.

- **Open Forms** — Offline-first Linux form application (GTK4 + libadwaita) for surveys and data collection; designed for low-connectivity environments and privacy-sensitive scenarios . **Form infrastructure**—can be used for employee surveys but not purpose-built for employee voice workflows.



**Frameworks for building custom systems**: **Alignify** provides the most focused open-source employee voice foundation with anonymous surveys and AI sentiment classification . **Check-Ins** provides a broader engagement platform including pulse surveys . **WorkMate** demonstrates wellbeing-focused check-in patterns with burnout detection . **feedback-hub-core** provides reusable feedback primitives . A complete employee voice system would require combining survey collection (Alignify or Check-Ins), sentiment analytics (Alignify's DistilBERT or custom NLP), and action planning workflows—with no single open-source platform providing the full lifecycle.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Employee voice platforms handling sensitive feedback and engagement data must comply with applicable privacy regulations (GDPR, CCPA) and organizational data governance policies; **anonymity guarantees are critical**—employees must trust that their feedback cannot be traced back to them.

- **Open-source employee voice remains early-stage**—Alignify provides AI-powered anonymous surveys but is in beta with a single contributor ; Check-Ins provides broader engagement features but less voice-specific analytics . No open-source platform matches Workday Peakon's NLP sentiment depth or Culture Amp's benchmark data. Organizations requiring enterprise-scale engagement analytics should budget for commercial platforms.

- Verify license terms for commercial use; Alignify and WorkMate are open-source (check repositories), Check-Ins is open-source, feedback-hub-core is an npm package, and erxes is source-available .



---



**Made for HR leaders, engagement managers, people analytics teams, and employee experience practitioners.**  

Let's make employee voice more open, anonymous, and action-oriented.

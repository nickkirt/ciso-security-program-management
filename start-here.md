# Start here
 
Welcome to **CISO Security Program Management**, a framework and tooling to explain, measure and manage a security program. This page explains what the project is, what's in it and where to go next.
 
## Why this project

Many security programs are run from a patchwork of spreadsheets, slides, reports and loosely based on frameworks/standards. They are often difficult to understand, and not explained effectively. This project gives a CISO, or a security manager, or a security professional a structured model of a security program. It's prescriptive and practical enough, yet allows for enough room to customize to the organization needs. And most importantly: it helps to explain how the security program works (including its effectiveness).

You can rate it, measure it, steer it and report on it:
 
- **30+ topics** across the NIST CSF 2.0 functions covering "all of" security within the organization.
- **A 1–5 maturity model** to rate each topic consistently.
- **Operational KPIs**, each with pass and fail thresholds.
- **Business context**: understand how the security program serves the business (or organization).
- **Risks and audit findings**, management with enough flexibility to work in any organization.
- **Targets, owners and a roadmap** of major initiatives & actions that improve maturity, fix security gaps and make the organization more secure.
- **Compliance mapping** to NIS2, DORA, ISO/IEC 27001:2022, NIST CSF 2.0, etc.
- **Board and management reporting** explaining security at the right level.
It started as the *CISO Security Mind Map 2026* by Nick Kirtley, and grew into an interactive tool after a lot of feedback from the security community.
 
---
 
## What's in this repository
 
| Folder | What you'll find |
|---|---|
| [`docs/`](docs/) | The CISO security program management tool itself |
| [`framework/`](framework/overview.md) | Placeholder |
| [`guides/`](guides/) | Placeholder |
| [`templates/`](templates/) | Placeholder |
| [`examples/`](examples/) | *Example Corp.*, Placeholder |
| [`data/`](data/) | Placeholder |
 
## The framework in one picture
 
```
 Business objectives  ◄── endangered by ──  Threats
          ▲                                   │ defended by
          │ protected by                      ▼
 ┌──────────────────────────────────────────────────────────────────┐
 │  GOVERN        IDENTIFY       PROTECT        DETECT    RESPOND & │
 │                                                          RECOVER │
 │  each function has topics (depending on your org needs)          │
 │  each topic:  maturity 1–5 · KPIs · risks · findings · owner     │
 │               target level · initiatives · compliance mappings   │
 └──────────────────────────────────────────────────────────────────┘
          │                                   │
          ▼                                   ▼
 Roadmap of initiatives            Board & management reporting
```
 
Read the full method in **[framework/](framework/README.md)**:
 
1. [Business context](framework/01-business-context.md): objectives and threats
2. [The 30 topics](framework/02-topics.md): scope, keywords and KPIs per topic
3. [Maturity model](framework/03-maturity-model.md): what levels 1 to 5 mean in practice
4. [Operational KPIs](framework/04-kpis.md): KPIs with thresholds
5. [Targets and roadmap](framework/05-targets-and-roadmap.md): roadmap to improve maturity and close gaps
6. [Risks and audit findings](framework/06-risks-and-findings.md): scoring, treatment and ageing
7. [Compliance mapping](framework/07-compliance-mapping.md): NIS2, DORA, ISO 27001, NIST CSF, etc.
8. [Ownership and governance](framework/08-ownership-and-governance.md): owners, reviews and cadence
9. [Reporting](framework/09-reporting.md): what the board and management need to see
## Quick start
 
1. **Explore.** [Open the tool](https://YOUR-USERNAME.github.io/ciso-security-program-management/). It opens on *Example Corp.*, a fictional company with a complete dataset. Click through the seven tabs.
2. **Start your own.** Switch **Data** to **Blank**, rate a few topics, then choose **Keep as my saved data**. From then on, the **Saved** data set is yours.
3. **Run a proper assessment.** Follow [guides/running-an-assessment.md](guides/running-an-assessment.md) and use the [topic assessment worksheet](templates/topic-assessment-worksheet.md).
4. **Report.** Open the **Reporting** tab and print the board view to PDF. See [guides/board-reporting.md](guides/board-reporting.md).
More detail is in [guides/getting-started.md](guides/getting-started.md).
 
## Who is this for?
 
- **CISOs and security managers** who want one view of their program.
- **Consultants and auditors** who need a structured, repeatable way to assess a security program.
- **Board members and executives** who want to understand what "good" looks like.
- **People moving into security leadership** who want a map of everything the role covers.
## Contributing
 
Feedback, corrections and new ideas are very welcome: better KPI definitions, extra compliance mappings, translations, templates or fixes to the tool. Read [CONTRIBUTING.md](CONTRIBUTING.md) to get started, or [open an issue](../../issues/new/choose). See the [roadmap](ROADMAP.md) for what's planned next.
 
## License
 
- **Tool and code:** [MIT License](LICENSE)
- **Framework, documentation, templates and examples:** [Creative Commons Attribution 4.0 (CC BY 4.0)](LICENSE-CONTENT.md)
You're free to use all of this commercially, adapt it and share it, as long as you give credit.
 
## Disclaimer
 
This framework and tool support professional judgment; they don't replace it. The compliance mappings are indicative and are not legal advice or an audit opinion. KPI thresholds are sensible defaults, not industry benchmarks. *Example Corp.* is fictional.
 
---
 
Created by **Nick Kirtley**.

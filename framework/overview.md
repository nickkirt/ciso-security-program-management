# The framework
 
The CISO Security Program Management framework is a **reference model and a method**, with sensible defaults, for running a security program. It defines what a security program should cover, how to measure it, how to manage it, and how to report on it. Everything hangs together as a connected model (as it is in the real world).
 
The framework is independent of any tool. You can apply it with spreadsheets and documents, build it into your own GRC tool, or reporting tooling, or use the tooling provided, which is one implementation of it.
 
## What it is, and what it isn't
 
| It is | It isn't |
|---|---|
| A model of security, divided in many functions and topics (typically over 30 topics) | A control catalogue: it sits above ISO/IEC 27001 Annex A, the NIST CSF categories or the CIS Controls, and points to them |
| A method to assess, measure, manage and report on a program | A certifiable standard or an audit methodology |
| A shared language between the CISO, other key management (CIO, privacy, legal, etc.) and the board | A replacement for professional judgment |
| Open and free to adapt (CC BY 4.0) | Tied to a vendor, product or tool |
 
## Design principles
 
1. **Start from the business.** The framework exists to protect the organization against real threats. Every topic, KPI and initiative should be traceable to protecting the organization.
2. **One flexible structure for everything.** The core is defined, but it can be updated or changed to reflect YOUR organization, YOUR security program, etc., where necessary, starting with sensible defaults.
3. **Simple enough to keep current.** A 1–5 scale, simple KPIs per topic and percentage-based thresholds. A model that takes weeks to update will be out of date by the next board meeting.
4. **Help in being honest about current security levels.** Focus on providing a model to be honest about a security program, not being overly alarmist and not being overly optimistic.
5. **Open.** Free to use, adapt and share.
## The building blocks
 
| # | Building block | Question it answers | What you end up with |
|---|---|---|---|
| 1 | [Business context](01-business-context.md) | What are we protecting, and from what? | Business objectives, high-level threats, threat readiness and objective posture |
| 2 | [The 30 topics](02-topics.md) | What does the program cover? | An agreed scope: which topics apply, and what each one includes |
| 3 | [Maturity model](03-maturity-model.md) | How well organised is each topic? | A rating from 1 to 5 per topic, with evidence |
| 4 | [Operational KPIs](04-kpis.md) | Is it working right now? | Two measured KPIs per topic, each with a pass, at-risk or fail status |
| 5 | [Targets and roadmap](05-targets-and-roadmap.md) | Where are we heading, and how do we get there? | Target levels with dates, and a roadmap of funded initiatives |
| 6 | [Risks and audit findings](06-risks-and-findings.md) | What could go wrong, and what did others find? | Risk and finding registers, linked to topics |
| 7 | [Compliance mapping](07-compliance-mapping.md) | Are we meeting our obligations? | A status per requirement for NIS2, DORA, ISO/IEC 27001 and NIST CSF |
| 8 | [Ownership and governance](08-ownership-and-governance.md) | Who is accountable, and is it kept up to date? | Owners, RACI and a review calendar |
| 9 | [Reporting](09-reporting.md) | What do the board and management need to know and decide? | A board report and a management report |
 
See also the [glossary](glossary.md).
 
## Structure: five functions, 30 topics
 
The topics are grouped under the functions of the [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework). Respond and Recover are combined, because in most organisations the same teams and plans cover both.
 
| Function | ID | Focus |
|---|---|---|
| Govern | GV | Security governance, data governance, standards, budget |
| Identify | ID | Assets; risk assessment and threat modeling; threat intelligence; third parties |
| Protect | PR | Safeguards: endpoints, network, vulnerabilities, identity, data, cloud, SaaS, OT, AI, awareness and more |
| Detect | DE | Security logging and monitoring |
| Respond & Recover | RR | SOC, incident management, business continuity and disaster recovery |
 
Protect has the most topics because that's where most of the controls, tooling and budget sit. That's not a statement about importance: a program with strong protection and weak detection or recovery is fragile.
 
## How the pieces connect
 
```
Objective ◄─ endangers ─ Threat ─ defended by ─► Topics
                                                   │
         ┌──────────┬──────────┬───────────┬───────┼──────────┬──────────────┐
      Maturity    KPIs       Risks      Findings  Owner   Target level   Compliance
      (1–5)     (%)   (L × I)    (severity) (+review)  (+date)       requirements
                                                              │
                                                     gap ─► Initiatives (uplift, budget, dates)
```
 
## The management cycle
 
The building blocks form a cycle that repeats through the year:
 
| Step | Building blocks | Typical cadence |
|---|---|---|
| **1. Understand** the business context | 1 | Yearly, and after major change |
| **2. Assess** maturity per topic, with evidence | 2, 3 | Twice a year |
| **3. Measure** the KPIs | 4 | Monthly |
| **4. Plan** targets and initiatives | 5 | Yearly, aligned with the budget cycle |
| **5. Manage** risks, findings and initiatives | 6, 8 | Monthly |
| **6. Check** compliance | 7 | Quarterly, and before audits |
| **7. Report** to management and the board | 9 | Monthly to quarterly (management); quarterly to twice a year (board) |
 
A first full cycle takes a few weeks. After that, most of the work is keeping KPIs, registers and initiatives up to date. See the [governance calendar](08-ownership-and-governance.md#review-cadence).
 
## Relationship to other frameworks
 
- **NIST CSF 2.0** provides the five functions that structure the topics, and is mapped at category level.
- **ISO/IEC 27001:2022** is the management-system standard many organisations certify against. Its Annex A controls are mapped to the topics. The framework helps run and report on the program behind an ISMS; it doesn't replace the ISMS.
- **NIS2 and DORA** set legal obligations, including management-body accountability. The mapping shows which topics carry those obligations, and the board report supports the oversight they require.
- **The maturity scale** follows the familiar capability-maturity pattern (as in CMMI and COBIT), so ratings are easy to explain and compare.
## Putting the framework to work
 
Pick whatever fits your organisation:
 
- **Documents and spreadsheets.** Use the [templates](../templates/): an assessment worksheet for all 30 topics, CSV templates for maturity, KPIs, risks, findings, initiatives and ownership, and a board report outline.
- **Your own tooling.** Load [`data/framework.json`](../data/framework.json), the whole framework in machine-readable form, into a GRC platform, BI dashboard or your own scripts.
- **The free tool.** A browser-based implementation that covers all nine building blocks, with no install and no account. Open it at [YOUR-USERNAME.github.io/ciso-security-program-management](https://YOUR-USERNAME.github.io/ciso-security-program-management/).
For a fully worked example, see [Example Corp.](../examples/example-corp/example-corp.md).

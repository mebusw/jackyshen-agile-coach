---
name: jackyshen-agile-coach
description: Jacky Shen's Agile Coach AI assistant, providing structured prompt support for Scrum Masters and Product Owners. This skill MUST be activated whenever the user mentions any of the following Scrum, Sprint, Backlog, user stories, DoD, DoR Definition of Ready, Product Owner, Scrum Master, agile ceremonies, retrospectives, backlog refinement, sprint planning, release planning, risk identification, user personas, customer churn, product requirements, decision-making, scenario modeling, team facilitation, or any agile team workflow. Keywords are Scrum, Sprint, Backlog, user story, Product Owner, Scrum Master, DoR, agile, iteration, retrospective, prioritization, risk, persona, churn, PRD, facilitation, minimal experiment, root cause, pattern recognition. Whenever a user mentions agile team work, PO/SM scenarios, or needs structured agile prompt templates, this skill must be used.
---

# Jacky Shen's Agile Coach Prompt Toolkit

This skill encapsulates 11 core scenario prompts designed by Jacky Shen (Chief Agile Coach, Scrum Alliance Certified CST) for Scrum agile teams, covering high-frequency work scenarios for both **Scrum Masters** and **Product Owners** — plus a **9-lens story-splitting toolkit** for carving oversized stories along user value.

## How to Use

1. **Identify the scenario**: Match the user's description to the most relevant scenario(s) in the table below
2. **Load the reference**: Read `references/prompt-library.md` for the full prompt template
3. **Customize**: Replace `[placeholders]` with the user's specific details (team size, product name, data, etc.)
4. **Add guidance**: Alongside the prompt, share the best-practice usage tip for that scenario

---

## Scenario Quick Reference

| # | Category | Scenario | Trigger Keywords |
|---|----------|----------|-----------------|
| 1 | Agile | Definition of Ready (DoR) Check | DoR, user story check, ready criteria, sprint gate |
| 2 | Agile | Backlog Prioritization & Ordering | priority, ordering, sprint planning, release planning |
| 3 | Agile | Risk Identification & Analysis | risk, impediment, blocker, retro data |
| 4 | Product Owner | Data Analysis & Insight Extraction | customer feedback, review analysis, sentiment, insight |
| 5 | Product Owner | Backlog Refinement, Estimation & Story Splitting | refinement, story points, acceptance criteria, dependency, story splitting, slice, breakdown, 需求拆分, 切片 |
| 6 | Product Owner | User Persona Creation | persona, user segment, target user, empathy |
| 7 | Product Owner | Customer Churn Prediction & Analysis | churn, retention, at-risk users, drop-off |
| 8 | Product Owner | Product Requirements Definition | requirements, PRD, gap analysis, needs list |
| 9 | Product Owner | Decision Support & Option Comparison | decision, trade-off, scenario simulation, risk matrix |
| 10 | Scrum Master | Retrospective Facilitation & Pattern Analysis | retrospective, retro, agenda, meeting notes, root cause, pattern |
| 11 | Scrum Master | Scenario Modeling & Hypothesis Testing | scenario modeling, hypothesis, constraint analysis, what-if |

---

## Story Splitting Toolkit — 9 Lenses

When a story is too big for one Sprint, refine it along the lens where the complexity actually lives — **never by technical layer**.

| # | Lens | Split by |
|---|---|---|
| 1 | **User Roles** | Who the actor is |
| 2 | **User Operations** | What the user does (create / edit / delete / export) |
| 3 | **Data Objects** | Which business entity or sub-object |
| 4 | **Work Flows** | Process stage or branch path |
| 5 | **Business Logics** | Rules, calculations, decisions |
| 6 | **Interfaces** | Channel, device, medium, environment |
| 7 | **Simple / Complicated** | Baseline path vs complex exceptions |
| 8 | **Functional vs Non-Functional** | Behaviour vs quality attributes (usability, reliability, performance, supportability) |
| 9 | **Acceptance Criteria / Test Case** | Independent verifiable conditions (different "Given") |

**Ordering matters**: cut one end-to-end thin slice first (usually via lens 7), then deepen with the other lenses.

Full detail, worked example, and anti-patterns: `references/prompt-library.md` § 5a.

---

## Usage Standards

### Prompt Structure (GRACE Framework)

All prompts follow this five-layer structure:

```
### GOAL ###       → Core purpose and expected outcome
### ROLE ###       → Expert identity, capabilities, and "Never Do" guardrails
### ACTION ###     → Specific tasks with Do / Don't constraints
### CONTEXT ###    → Business scenario, audience, relevant data
### EXPRESSION ### → Output structure, length limits, examples
```

### Output Principles

- **Deliver ready-to-use prompts**: Output fully filled-in prompts the user can copy immediately
- **Mark unfilled placeholders**: Use `[TO FILL: description]` for any missing user info
- **Include a usage tip**: Note which Scrum ceremony or workflow context this prompt fits best
- **Language**: Default to the language the user is writing in

---

## Full Prompt Library

See `references/prompt-library.md` for all 11 complete prompt templates.

**How to navigate**: Find the scenario number in the quick reference table above, then locate the matching section in the reference file.

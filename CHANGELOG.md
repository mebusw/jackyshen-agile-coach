# Changelog

## 1.1.0 - 2026-11-08

### Features
- Add a **9-lens story-splitting toolkit** to scenario 5 (Backlog Refinement): User Roles, User Operations, Data Objects, Work Flows, Business Logics, Interfaces, Simple vs Complicated, Functional vs Non-Functional, Acceptance Criteria / Test Case
- Scenario 5 now runs a size check first and returns a tagged *Split Candidates* table (lens used, rationale, story points) before any estimate is discussed
- New reference section § 5a — per-lens guidance, ordering rules, a worked example, and anti-patterns

### Documentation
- Expand `README.md` and `README.zh-cn.md` with the story-splitting toolkit (bilingual)
- Add story-splitting trigger keywords to the SKILL.md scenario table

## 1.0.3 - 2026-11-08

### Documentation
- Expand the installation guide in `README.md` and `README.zh-cn.md`
- Add the recommended global install command: `npx skills add -g https://github.com/mebusw/jackyshen-agile-coach`
- Document the local install variant, post-install verification, update steps, and troubleshooting

## 1.0.2 - 2026-07-04

### Documentation
- Rename "Agile General" category to "Agile" in SKILL.md scenarios table for naming consistency

## 1.0.1 - 2026-07-04

### Features
- Initial release of Jacky Shen's Agile Coach Prompt Toolkit
- 11 ready-to-use AI prompt templates covering Scrum Master and Product Owner scenarios
- GRACE prompt framework (GOAL / ROLE / ACTION / CONTEXT / EXPRESSION) for structured prompt design
- Bilingual documentation (English README.md, Chinese README.zh-cn.md)
- Scenario coverage: DoR check, backlog prioritization, risk analysis, data analysis, backlog refinement, persona creation, churn prediction, requirements definition, decision support, retrospective facilitation, scenario modeling
- Blank custom prompt template for extending to new scenarios

### Documentation
- Complete English README with installation guide, framework explanation, and usage examples
- Chinese README with full translation and localised examples

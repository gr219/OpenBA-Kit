# BA-Kit Open — 55 AI Skills for IT Business Analysts & Product Owners

<p align="center"><b>English</b> | <a href="README_VI.md">Tiếng Việt</a></p>

An extension skill pack that turns any AI coding agent (Claude Code, Antigravity, Codex, Hermes...) into a professional Business Analyst assistant, automating the entire documentation process from a rough idea to technical handoff.

---

## 📁 Project Structure

```
ba-kit-open/
├── skills/          # 55 AI skills in Agent Skill format (.claude/skills or .hermes/skills)
│   ├── brainstorm/  # Clarify raw business requirements
│   ├── srs/         # IEEE 830 software requirements specification
│   ├── sequence/    # Mermaid sequence diagrams
│   ├── erd/         # Entity-relationship diagrams
│   ├── wireframe-html/ # Interactive HTML wireframes
│   ├── userstory/   # INVEST-compliant user story backlog
│   ├── test-cases/  # Detailed test cases
│   ├── cr/          # Change requests & impact analysis
│   └── ... (all 55 skills)
├── rules/           # 19 BA documentation & coding conventions
│   ├── 01-fr-naming-convention.md
│   ├── 02-br-naming-convention.md
│   ├── 03-err-naming-convention.md
│   ├── 04-nfr-standards.md
│   ├── 05-srs-ieee-830.md
│   ├── 06-cockburn-use-case.md
│   ├── 07-invest-user-story.md
│   ├── 08-gherkin-acceptance-criteria.md
│   ├── 09-data-dictionary-standard.md
│   ├── 10-api-contract-standards.md
│   ├── 11-error-matrix-convention.md
│   ├── 12-state-transition-rules.md
│   ├── 13-wireframe-html-guidelines.md
│   ├── 14-test-case-traceability.md
│   ├── 15-change-request-impact-matrix.md
│   ├── 16-ambiguity-detection-rules.md
│   ├── 17-actor-role-definition.md
│   ├── 18-knowledge-graph-metadata.md
│   └── 19-document-versioning-rules.md
└── _templates/      # 48 standard document templates
    ├── 01-prd.md
    ├── 02-roadmap.md
    ├── 04-brainstorm.md
    ├── 08-srs.md
    ├── 15-sequence-diagram.md
    ├── 19-state-diagram.md
    ├── 20-erd-mermaid.md
    ├── 26-usecase-cockburn.md
    ├── 27-userstory.md
    ├── 28-acceptance-criteria.md
    ├── 31-wireframe-html.html
    ├── 43-test-cases.md
    ├── 45-gap-analysis.md
    ├── 47-change-request.md
    └── ... (all 48 templates)
```

---

## ⚡ 9 Phases & All 55 Skill Commands

| Phase | Count | `/skill` Commands |
| :--- | :---: | :--- |
| **1. Product Planning** | 3 | `/prd`, `/roadmap`, `/discover` |
| **2. Requirements Gathering & Specification** | 7 | `/brainstorm`, `/urd`, `/brd`, `/prd-epic`, `/srs`, `/reverse-doc`, `/code-to-srs` |
| **3. Business & Data Diagrams** | 11 | `/sequence`, `/activity`, `/activity-swimlane`, `/bpmn`, `/state`, `/erd`, `/d2-erd`, `/d2-activity`, `/d2-architect`, `/dbdiagram`, `/usecase-diagram` |
| **4. Use Cases & User Stories** | 3 | `/usecase`, `/userstory`, `/ac` |
| **5. Screen Design & Prototyping** | 6 | `/user-flow`, `/wireframe-ascii`, `/wireframe-html`, `/prototype-html`, `/prototype-next`, `/figma` |
| **6. API Integration** | 7 | `/api-assess`, `/api-doc`, `/api-design`, `/api-map`, `/api-checklist`, `/api-test`, `/api-readiness` |
| **7. Testing (QA/QC)** | 3 | `/test-checklist`, `/test-cases`, `/playwright-gen` |
| **8. Quality & Change Control** | 6 | `/gap`, `/doc-drift`, `/ask`, `/cr`, `/dashboard`, `/kg` |
| **9. Handoff & Operations** | 9 | `/jira`, `/confluence`, `/export`, `/preview`, `/reverse-preview`, `/userguide`, `/meet`, `/update-overview`, `/delegate` |

---

## 🚀 Core Workflow

A typical BA workday with the core skills:
1. `09:00` `/brainstorm`: Interview to clarify the raw idea and lock down scope.
2. `09:40` `/srs`: Generate an IEEE 830 specification (FR, BR, ERR, NFR).
3. `10:30` `/sequence` + `/erd`: Draw interaction flow diagrams and the data model.
4. `11:00` `/wireframe-html`: Build a self-contained UI you can view directly in the browser.
5. `14:00` `/userstory` + `/ac`: Break down an INVEST-compliant backlog with Gherkin acceptance criteria.
6. `16:00` `/test-cases`: Generate test cases traced to the ACs and the error matrix.
7. `Next day` `/cr`: Take in client changes, analyze impact, and keep documents in sync.

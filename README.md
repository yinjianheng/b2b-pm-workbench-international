# B2B PM Super Workbench

> **One Person, One Skill — Deliver Professional-Grade B2B Product Full-Process Delivery from 0 to 1.**
> Covers the complete lifecycle: Strategy → Requirements → Solution Design → Prototype → Documentation → Development → Data → Commercialization → Operations.
> Even if you're a product newbie, using this Skill turns you into a senior B2B Product Manager instantly.
> 
> **V1.1.0 New:** SaaS Pricing Two Dimensions + Seven-Step Pricing Implementation Process | PLG Product-Led Growth Methodology | 2026 China SaaS Trends | JTBD (Jobs-to-Be-Done) Methodology | Copyright Notice + Disclaimer

---

## Quick Start

Place this directory into `~/.claude/skills/` or `.claude/skills/` (project-level):

```bash
cp -r ~/Desktop/b2b-pm-workbench ~/.claude/skills/
```

Then simply state your needs in Claude Code and it will auto-trigger, for example:
- "Help me write a PRD for an enterprise CRM"
- "Analyze competitors in the HR SaaS market"
- "Draw a procurement approval flowchart"
- "Generate a B2B admin dashboard prototype"

---

## Directory Structure

```
b2b-pm-workbench/
├── SKILL.md                              # Main skill file (core!)
├── README.md                             # This file
└── references/
    ├── templates/                        # Document template library
    │   ├── prd-template-b2b.md           # B2B PRD template (with approval flow / permissions / data dictionary)
    │   ├── brd-template.md               # Business Requirements Document template
    │   ├── mrd-template.md               # Market Requirements Document template
    │   ├── frd-template.md               # Functional Requirements Document (with API definitions)
    │   ├── competitive-analysis-b2b.md   # B2B competitive analysis template
    │   ├── user-interview-b2b.md         # B2B user interview complete guide
    │   ├── user-research-report.md       # User research report template
    │   ├── sales-enablement.md           # Sales enablement kit template
    │   ├── backlog-plan.md               # Backlog & version planning template
    │   └── deliverables-checklist.md     # Deliverables checklist & quality standards
    ├── methodologies/                    # Deep methodology library
    │   └── b2b-specific-methods.md       # B2B-specific methodologies (permissions / approvals / multi-tenancy, etc.)
    └── examples/                         # Complete examples
        └── prd-example-erp-procurement.md # PRD complete example: procurement management module
```

---

## Core Capabilities

### 10 Major Phases — Full Coverage
0. Strategy & Market Insight → 1. Requirements Discovery & Management → 2. Requirements Analysis & Prioritization → 3. Solution Design → 4. Prototype & Interaction → 5. Diagrams & Architecture → 6. Documentation Engineering → 7. Development Collaboration → 8. Data & Growth → 9. Commercialization & GTM → 10. Operations & Iteration

### 50+ Methodology Frameworks
KANO / JTBD / Y-Model / SWOT / Porter's Five Forces / PESTLE / Business Model Canvas / RICE / MoSCoW / SPIN / C4 Model / BPMN / RBAC / ABAC / Multi-Tenancy Design / SaaS Pricing Models / PLG Product-Led Growth / 2026 China SaaS Trends / ...

### 30+ Standard Deliverables
PRD / BRD / MRD / FRD / Competitive Analysis / User Research Report / Interactive Prototype / Business Process Diagram / Architecture Diagram / Approval Flow Design / Data Dictionary / Sales Enablement Kit / Pricing Plan / PLG Growth Strategy / ...

---

## Trigger Methods

Simply say what you want to do in Claude Code, and the Skill auto-matches phases and methodologies:

```
# Documentation
"Write a PRD for enterprise procurement management"
"Conduct B2B CRM competitive analysis"
"Write a BRD, product is XX"

# Diagrams
"Draw a swimlane diagram for procurement approval"
"Draw a system technical architecture diagram"
"Draw an ER diagram"

# Prototypes
"Generate an admin dashboard prototype"
"Create an approval detail page prototype"

# Strategy
"Create a pricing plan for product XX"
"Create a GTM strategy for product XX"
"Analyze competitors in market XX"

# Reporting
"Create a monthly product review PPT"
"Create a product approval review PPT"
```

## Dependent Skills (Auto-invoked by this Skill)

| Task | Auto-invoke |
|------|---------|
| Diagramming | `drawio-skill` / `drawio-coderknock` / `drawio-generator-pro` / `excalidraw-diagram` |
| PPT | `pptx-2` / `guizang-ppt-skill` / `deck-generator` |
| Documents | `word-docx` / `minimax-pdf` / `word-cn-format` |
| Spreadsheets | `xlsx` |
| Prototypes | Directly generate HTML interactive prototypes (no extra tools needed) |

---

## License

Author: yinjianheng
Contact: email: yinjianheng@foxmail.com / wechat: YJH-yinjianheng
License: Free and open-source, for personal use only.

**Legal Notice**: This Skill is protected under the Copyright Law of the People's Republic of China. Without the author's written authorization, any commercial use (including but not limited to resale, bundled sales, commercial training, SaaS-based services) is prohibited. Infringement will be pursued — Beijing Yingke Law Firm has been retained to periodically scan the Skill marketplace; legal action will be taken upon discovery of infringement.

---

## Disclaimer

1. **Non-Professional Advice**: The content provided by this Skill is for learning and reference only and does not constitute any form of professional advice (including but not limited to legal advice, financial advice, or technical decision-making advice).
2. **Information Accuracy**: While every effort has been made to ensure the accuracy and timeliness of the content, no guarantee is made regarding the completeness, accuracy, or applicability of all information. Users should verify critical information independently.
3. **Limitation of Liability**: To the maximum extent permitted by applicable law, the author assumes no liability for any direct, indirect, incidental, special, or consequential losses arising from the use of or reliance on the content of this Skill.
4. **Third-Party Content**: The copyrights of third-party frameworks, methodologies, tools, and standards referenced in this Skill belong to their respective rights holders.
5. **Usage Compliance**: Users shall ensure that their use of this Skill complies with the laws and regulations of their country/region and internal corporate policies.
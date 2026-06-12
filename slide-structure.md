# Slide Structure

This file maps the live 15-slide deck across `index.html` and its matching CSS sections.

## Slide Map

| Slide | Title | HTML class | CSS section label | Main content |
| --- | --- | --- | --- | --- |
| 01 | Hero | `.hero` | `SLIDE 01: HERO` | Opening message, subcopy, client logo marquee |
| 02 | Who We Are | `.who` | `SLIDE 02: WHO WE ARE` | Three capabilities: Software House, AI Workflow Operators, BytePlus Partner |
| 03 | The Technology | `.data` | `SLIDE 03: THE TECHNOLOGY` | BytePlus/ByteDance explanation, market stats, tech logos, stack visual |
| 04 | Exclusivity | `.exclusivity` | `SLIDE 04: EXCLUSIVITY` | Thailand exclusivity message, BytePlus illustration, partner badge |
| 05 | The Stack | `.stack` | `SLIDE 05: THE STACK` | Three layers: foundation, operations, intelligence |
| 06 | Outcomes | `.outcomes` | `SLIDE 06: OUTCOMES` | KPI cards showing business impact and ROI |
| 07 | Two Pillars | `.pillars-section` | `SLIDE 07: TWO PILLARS` | Create faster / Understand deeper positioning |
| 08 | Create Faster Demo | `.create-faster` | `SLIDE 08: CREATE FASTER DEMO` | Prompt-to-content generation demo |
| 09 | Understand Deeper Demo | `.understand` | `SLIDE 09: UNDERSTAND DEEPER DEMO` | Prompt-to-report intelligence demo |
| 10 | How We Work | `.process` | `SLIDE 10: HOW WE WORK` | Audit, Automate, Operate process |
| 11 | Industries | `.industries` | `SLIDE 11: INDUSTRIES` | Industry tabs and AI use cases |
| 12 | Case Studies | `.cases` | `SLIDE 12: CASE STUDIES` | Three real deployment examples |
| 13 | Partnership | `.partnership` | `SLIDE 13: PARTNERSHIP` | Managed Service, Build & Embed, Team Ownership |
| 14 | Get Started | `.ways` | `SLIDE 14: GET STARTED` | Three entry points to engage |
| 15 | Pricing | `.pricing` | `SLIDE 15: PRICING` | Pricing factors and scope-based model |

## Shared Layout Spec

This is the current shared outer slide layout used by the deck.

| Breakpoint | Left / Right | Top | Bottom |
| --- | --- | --- | --- |
| `1920+` | `160px` | `120px` | `72px` |
| `1440 and below` | `120px` | `96px` | `64px` |
| `640 and below` | `24px` | `48px` | `32px` |

### Code mapping

- Shared section padding: `index.html`
- Shared container width / horizontal margins: `index.html`
- Desktop default:
  - `.slide section { padding: 120px 0 72px; }`
  - `.container { width: calc(100% - 320px); }`
- `1440 and below`:
  - `.slide section { padding-top: 96px; padding-bottom: 64px; }`
  - `.container { width: calc(100% - 240px); }`
- `640 and below`:
  - `.slide section { padding-top: 48px; padding-bottom: 32px; }`
  - `.container { width: calc(100% - 48px); }`

## Slide Details

### Slide 01 — Hero

- Title: `We build & operate AI-Powered businesses shaping Thailand`
- Support copy: one-partner positioning across software, automation, and ByteDance AI stack
- Visuals: hero glow, particle network, client logo wall

### Slide 02 — Who We Are

- Title: `Three capabilities. One operating partner.`
- Focus: combined value of software delivery, workflow automation, and BytePlus access

### Slide 03 — The Technology

- Title: `Mtel × BASICWARE, powered by the BytePlus stack.`
- Focus: BytePlus context, TikTok/CapCut/Douyin proof points, Thai market relevance

### Slide 04 — Exclusivity

- Title: `Doesn't sell to everyone.`
- Focus: BytePlus partnership model and Thailand exclusivity

### Slide 05 — The Stack

- Title: `The same stack used by BytePlus, operated by Mtel.`
- Focus: three delivery layers and what each includes

### Slide 06 — Outcomes

- Title: `What changes when AI becomes operational.`
- Focus: workload reduction, speed, visibility, cost, payback

### Slide 07 — Two Pillars

- Title: `Create faster. Understand deeper.`
- Focus: top-level value proposition before demos

### Slide 08 — Create Faster Demo

- Title: `Describe it. See it.`
- Focus: generation workflow for video, images, websites, digital humans

### Slide 09 — Understand Deeper Demo

- Title: `Ask anything. Get the answer.`
- Focus: market sentiment, competitor moves, pain points, share of voice

### Slide 10 — How We Work

- Title: `Audit. Automate. Operate.`
- Focus: phased engagement model and execution approach

### Slide 11 — Industries

- Title: `Worked across sectors. The principles don't change.`
- Focus: cross-industry applicability with dynamic use cases

### Slide 12 — Case Studies

- Title: `Real deployments. Measured results.`
- Focus: proof through specific implementation outcomes

### Slide 13 — Partnership

- Title: `Not a license. A partnership.`
- Focus: transition from managed service to client ownership

### Slide 14 — Get Started

- Title: `Three ways to start.`
- Focus: Intelligence Report, Problem Statement, Workflow Audit

### Slide 15 — Pricing

- Title: `We don't quote. We scope.`
- Focus: commercial model depends on scope, scale, and ambition

## Legacy / Unused CSS Sections

These CSS sections exist in `index.html` but are not part of the active 15-slide flow:

- `LEGACY / UNUSED: PROBLEM`
- `LEGACY / UNUSED: LOGO WALL`
- `LEGACY / UNUSED: CTA`

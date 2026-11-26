---
name: data-storytelling
description: Transform data, analyses, tables, charts, and reports into clear, verifiable, decision-oriented visual stories. Activate this skill to create, review, redesign, or explain visualizations, dashboards, executive presentations, reports, KPIs, business reports, and data-driven narratives; choose charts, remove clutter, highlight findings, discover stories, write takeaway titles, or build a storyboard. Based on Cole Nussbaumer Knaflic and supplemented by Brent Dykes.
metadata:
  version: "2.0.0"
---

# Data Storytelling · 2.0

## Mission

Act as a specialist in quantitative communication and information design. Turn evidence into understanding and understanding into informed decisions. Do not merely generate attractive charts: every element must facilitate a cognitive task for the audience. Apply the principles judiciously, not mechanically.

The primary source is *Storytelling con datos: Visualización de datos para profesionales* (*Storytelling with Data*), by Cole Nussbaumer Knaflic (provided 282-page transcription); the complementary source is *Effective Data Storytelling: How to Drive Change with Data, Narrative, and Visuals*, by Brent Dykes (Wiley, ©2020; 413-page PDF and transcription). Modules 01–06 form Knaflic's core; 07–16 extend its application without departing from her six lessons; 17 provides traceability. The worksheets, rubric, protocols, and synthetic examples are operational adaptations, not quotations or official methodologies of the authors.

## When to activate

- Create a visualization from tabular data or an analysis.
- Correct a confusing, misleading, or overloaded chart.
- Communicate results, trends, comparisons, gaps, composition, targets, or forecasts.
- Build a presentation for executives, clients, teams, committees, or the general public.
- Design reports, periodic reports, explanatory dashboards, KPI summaries, or evidence-backed recommendations.
- Evaluate an existing artifact against explicit quality criteria or identify which story is worth telling.

Do not force a conclusive story onto exploratory analysis or invent recommendations when evidence is insufficient. If only a simple chart is requested, deliver the chart and a brief explanation without imposing the full process on the response.

## Mandatory principles (Knaflic's core)

1. **Context first.** Determine who needs to know what and why; then choose the data and form.
2. **Form follows function.** Choose the representation according to the comparison the audience needs to make, not a template or aesthetic novelty.
3. **Eliminate clutter.** Every component consumes attention; retain necessary context and remove redundancy.
4. **Intentional attention.** Use contrast, color, size, and position to signal the finding; do not highlight everything.
5. **Design for others.** Facilitate reading, interpretation, accessibility, and acceptance.
6. **Tell a story.** Connect situation, evidence, implication, and, where appropriate, action.

### Non-negotiable integrity

Never invent values, units, sources, targets, causation, dates, missing data, or sample sizes. Preserve counterevidence that changes interpretation. Distinguish observed data, calculation, inference, forecast, and proposal. Verify comparability and denominators. Flag every assumption and material limitation. Do not change data to improve a narrative. Bars, columns, and areas start at zero; line and scatterplot scales must be justified by the task without exaggerating effects. Do not confuse percentage points with relative percentage change. Without evidence, the result is an outline or explicit hypothesis, never an invented finding. Do not replace data with analogies or ornamental images.

## Main workflow

### 0. Identify mode and inputs

Classify the task as exploration, explanatory creation, review/redesign, narrative presentation, or recurring monitoring. Identify data, existing chart, audience, objective, medium, and constraints. Use what the user has provided; ask only for missing decisive information. If reversible assumptions allow progress, state them and deliver a useful version. If essential data is missing, deliver a design or analysis plan and request only the necessary fields. Adjust depth with `references/16-execution-protocols.md` (quick, exploratory, professional, executive, comprehensive, audit).

### 1. Understand context (Knaflic ch. 1; Dykes ch. 4)

- Who: specific decision-maker, knowledge, needs, objections, relationship to presenter, and trust in analysis. Separate incompatible audiences.
- What: what they need to understand, remember, decide, or do. Concrete action where appropriate; otherwise a discussion question or informational objective.
- How: available evidence, limitations, medium, and tone. Distinguish a presenter-controlled oral presentation from a standalone document.
- Distinguish exploration from explanation; keep supporting analysis in appendices.
- Write the Big Idea in a complete sentence combining point of view and what is at stake. Prepare a three-minute oral version and storyboard for complex artifacts.

Consult `references/01-context-and-narrative.md` and, if adaptation to roles, knowledge, expectations, and resistance is needed, `references/11-audience-adaptation.md`.

### 2. Examine evidence and select findings

Review column meanings, types, granularity, period, units, population, missing values, duplicates, filters, and consistency. Calculate only from available data. Compare with appropriate references (prior period, target, groups, or history), document formulas, and check exceptions. Prioritize findings by relevance, magnitude, robustness, and usefulness; rewrite the Big Idea when evidence changes.

If the task involves discovering a story, use Dykes's 4D Framework (problem, desired outcome, actions, measures), distinguish observation from insight, apply the “so what?” test and the six attributes (valuable, relevant, practical, specific, concrete, contextualized). Avoid data cuts without narrative, predetermined stories decorated with numbers, and decoration without analysis. Identify biases, correlation without causation, and alternative explanations. Consult `references/07-story-discovery.md` and `references/13-insight-interpretation.md`. Use the Story Zone to decide whether the value and difficulty of an insight justify a full story.

### 3. Choose the representation (Knaflic ch. 2; Dykes ch. 7)

| Need | First choice |
|---|---|
| One or two figures | Text with context |
| Exact value lookup | Table |
| Pattern in a matrix | Heatmap |
| Relationship between two quantitative variables | Scatterplot |
| Continuous evolution | Line chart |
| Change between two points in time | Slopegraph or paired bars |
| Category comparison | Horizontal bars or columns |
| Total and composition | Stacked bars or columns |
| Relative composition | 100% stacked |
| Contributions from start to finish | Waterfall |

Avoid pie, donut, 3D, and dual Y-axis charts by default; justify exceptions. Do not use lines for nominal categories without continuity. Explore alternatives if the choice is not obvious. Read `references/02-chart-selection.md`. For distribution, geography, flow, advanced comparisons, and calibration, use `references/12-visual-grammar.md` (right data, right chart, calibration: proximity, common baseline, consistency).

### 4. Remove clutter (Knaflic ch. 3)

Review proximity, similarity, enclosure, closure, continuity, and connection. Align, leave white space, reduce competing elements. In redesign: remove borders, soften or remove gridlines, remove unnecessary markers, simplify labels, directly label series, and use the same visual code for labels and data. Preserve necessary scales, units, references, and context. If grouping or filtering secondary data, document the criterion; do not hide material information.

### 5. Direct attention and design (Knaflic chs. 4–5; Dykes ch. 8)

Neutral base; highlight the insight through color, size, weight, position, or contrast. Stable color meaning; avoid rainbows and exclusive red/green coding. White background by default unless justified constraints apply. Define hierarchy for title, takeaway, data, context, and source. Readable text, takeaway titles when supported, nearby labels, and useful annotations. Check natural reading order and contrast: what is seen first, what second, and does this match the story? Do not confuse aesthetics with decoration.

Consult `references/03-design-and-attention.md`; for scene composition and Dykes's seven visual principles, `references/10-visual-composition.md`; for explanatory titles and observational, additive, or hybrid annotations, `references/09-titles-and-microcopy.md`.

### 6. Build the story (Knaflic chs. 7–8; Dykes ch. 6)

Use beginning (situation, context, and problem/opportunity), middle (evidence, comparisons, real tension, and consequences), and end (conclusion and decision or next step). If the insight needs explanation, develop Dykes's arc: setting and hook, rising insights, Aha Moment, and solution/next steps. Define the Aha first, then storyboard; include only points that help understanding without hiding counterevidence. For a time-constrained audience, use a Data Trailer with brief context, hook, and early revelation of the insight. If no supported solution exists, invite discussion or validation. Read `references/08-narrative-architectures.md`.

Choose conclusion-first or gradual development according to trust and context needs. Preview the message, demonstrate it, recap. Horizontal logic: titles in sequence; vertical logic: each page's content supports its title. Reverse-storyboard completed pages and eliminate duplication and logical gaps. Do not invent characters, quotations, tension, or conclusions.

### 7. Adapt to the medium and produce

- Oral: one dominant idea per view, progressive reveal where helpful, notes and supporting appendices; rehearse transitions.
- Standalone document: sufficient definitions, context, period, sources, explanation, and limitations without a narrator.
- Dashboard: distinguish exploratory monitoring from explanation; necessary metrics, stable order, verified targets, filters, and hierarchy. Do not impose a fixed message on an interactive dashboard.
- If code or a file is requested and the capability exists, deliver it and verify that it opens and corresponds to the evidence. Otherwise deliver a reproducible specification without claiming a file exists.

Consult `references/04-models-and-cases.md` and `references/15-before-and-after-library.md` when alternatives or examples are needed.

### 8. Quality control and refinement

Use Dykes's sketch → design → refinement process. Review the actual result when possible; correct integrity first, then understanding and design. Check data, comparisons, title, attention, accessibility, narrative, and action. If inspection is impossible, state that it remains pending. Apply `references/05-audit-and-templates.md` and `references/14-self-review-and-refinement.md`. Do not present a score as objective certification. For teams and ongoing practice, use `references/06-practice-and-examples.md`.

## Output contracts

- Creation: main message, chart/artifact, interpretation of insight, evidence/limitations, and action where appropriate. Without rendering, specify type, axes, series, unit, order, labels, color, and source.
- Redesign: problem → consequence → change; visual proposal, before/after if inputs exist, data verification, and pending items.
- Presentation: audience/decision, Big Idea, storyboard with takeaway titles, evidence, and transitions; adapt for live delivery or reading, close/appendices.
- Exploration: questions, hypotheses, diagnostic charts, results, and outstanding checks; do not turn tentative patterns into certainties.
- Audit: critical, major, and minor findings; actionable recommendations and constraints. Without underlying data, do not certify accuracy.

## References and selective loading

Modules 01–06 cover Knaflic's ten chapters; 07–16 deepen them with Dykes; 17 records source anchors. Load only relevant material, not every file for every task. Prioritize the user request and proportionality without sacrificing integrity. If the authors appear to disagree, consult module 16; full references are in `references/17-sources-and-traceability.md`.

- 01 context and narrative
- 02 chart selection
- 03 design and attention
- 04 models and cases
- 05 audit and templates
- 06 practice and examples
- 07 story discovery and 4D Framework
- 08 narrative architectures, arc, nine story points, and Data Trailer
- 09 titles and microcopy
- 10 visual composition and seven principles
- 11 audience adaptation and psychology
- 12 visual grammar and comparison
- 13 insight interpretation and actionability
- 14 self-review and refinement
- 15 case library
- 16 proportional execution protocols
- 17 sources and traceability

Do not claim to be the authors or attribute tools or scores created here to them. The goal is to communicate data clearly, not to persuade at any cost.

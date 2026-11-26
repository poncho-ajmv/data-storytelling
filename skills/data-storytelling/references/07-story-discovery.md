# 07 · Story discovery and insight selection

**Source:** Brent Dykes, *Effective Data Storytelling* (Wiley, ©2020), ch. 1, PDF pp. 29–37; ch. 4, pp. 107–109, 139–143; ch. 5, pp. 146–183; ch. 6, pp. 196–198. Complements Knaflic, chs. 1 and 8. Page references refer to the 413-page PDF, not the printed edition. Terminology translations in the Spanish version were our own; procedures, worksheets, and examples are operational adaptations.

## 1. Determine whether a story is needed

Dykes distinguishes **storyframing** (framing data so insights can emerge) from **storytelling** (explaining a specific insight through narrative and explanatory visualizations). Framing is valid in dashboards, monitoring reports, and exploratory questions; there is no need to impose a conclusion. The transition occurs when a meaningful central insight deserves to be understood by someone.

Do not confuse data with insight. An isolated number informs; an observation identifies something noteworthy; an insight changes understanding of an issue by placing the data and its relationship in context. It may lead to action, but action should not precede the evidence. Dykes describes the analytical value chain: data → information → insight → decision → action (fig. 1.2, p. 33). Value materializes only when appropriate decisions and actions produce results; the skill does not promise that this will occur.

### Story Zone

Cross two dimensions: potential value of the insight and difficulty of understanding or acceptance. A full story typically adds most value in the zone of **medium/high value + insight difficult to understand or accept** (fig. 4.17, p. 142). Difficulty increases if the result is uncomfortable, unexpected, counterintuitive, complex, costly, or risky. If simple and easily accepted, a contextualized number or chart may suffice even when value is high. If trivial, do not prolong the story. If validity is uncertain, investigate first. This rule does not authorize manipulating an audience or hiding adverse evidence.

## 2. 4D Framework (Four Dimensions Framework)

Dykes, ch. 5, pp. 152–157, figs. 5.2–5.3. Define the four dimensions **for a specific audience**:

| Dimension | Question | Required evidence |
|---|---|---|
| Problem | What current challenge do they want to solve? | Current state, symptoms, and verified consequences |
| Outcome | What future state do they seek? | Target, reference, horizon; if absent, mark unknown |
| Actions | What initiatives or levers are they already using? | Confirmed programs, decisions, activities, or changes |
| Measures | How do they know whether they are progressing? | Definition, unit, source, period, population, denominator, and indicator formula |

The framework helps formulate relevant questions, not force a problem into every request. Synthetic example: customer service team, problem = wait times; outcome = agreed SLA; actions = new routing and shifts; measures = median, 90th percentile, and percentage within SLA. If the SLA was not provided, do not invent it. The framework does not prove that routing caused a change.

## 3. Discovery protocol (adaptation)

1. Establish 4D and the audience's task. Record what is unknown.
2. Review quality: period, coverage, granularity, universe, nulls, duplicates, units, definition changes, representativeness, and provenance. If something critical fails, limit the conclusion.
3. Formulate unbiased hypotheses and questions. Do not seek only evidence favorable to a prior hypothesis.
4. Explore visually with the story point families in `08-narrative-architectures.md`: change over time, relationship, intersection, projection, comparison, drill down, zoom out, cluster, and outlier. Use only those compatible with the data.
5. Compare against a valid reference: comparable period, real target, equivalent population or category. Review absolute and relative values, bases, and exceptions.
6. Investigate what explains the observation. An association is a hypothesis, not a cause. If the cause is unknown, state it and propose what to check.
7. Evaluate candidates against the six actionability attributes in module 13. Choose one central insight; if two are independent, separate them into stories or sections. Do not hide material findings that contradict the main one.
8. Freeze an evidence worksheet and move to explanatory design. Return to exploration if an inconsistency emerges during design.

## 4. Three deviations to avoid

Dykes, ch. 5, pp. 161–168, figs. 5.4–5.8:

- **Data cut:** analysis occurred, but a collection of results is delivered without forming a story; reselect and organize.
- **Data cameo:** start with a predetermined story and seek figures to decorate it; restart from evidence and consider contrary results.
- **Data decoration:** invest in visuals without enough analysis or narrative direction; verify the insight, then determine which visual contributes to understanding.

If the user actually requests exploration or lookup, do not label a discovery dashboard a defective data cut: answer the explicit objective.

## 5. Candidate insight worksheet

- Identifier and business question.
- Exact data, formula, source, and period.
- Observed pattern and comparison reference.
- Supported interpretation and alternative explanation.
- What changed in understanding? Who cares?
- Uncertainty and missing evidence.
- Available action or required discussion; known or estimated impact with explicit assumptions.
- Is it worth a story? Decision: central / support / appendix / pending exploration.

## 6. Application example

Fictional data: sales 120 thousand, returns 12 thousand, and net sales 108 thousand in June; in May sales 115 thousand, returns 5 thousand, net 110 thousand. An initial observation is that gross sales increased 5 thousand (+4.35%). Comparing net sales reveals the insight: they fell 2 thousand (−1.82%), because observed returns increased 7 thousand. The change is an accounting identity, not proof of why returns occurred. The story may focus on deteriorating net sales and analysis of returns by product and reason. Do not attribute it to quality without causal data. Commercial versus financial audiences change the detail of the next step.

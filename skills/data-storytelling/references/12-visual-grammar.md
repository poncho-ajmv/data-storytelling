# 12 · Visual grammar, comparison, and calibration

**Source:** Dykes ch. 7, PDF pp. 224–259, figs. 7.6–7.27; ch. 8, tables 8.2–8.6; Knaflic chs. 2 and 9. Expands, does not replace, the matrix in module 02.

## The central question: compared with what?

Visualization enables the audience to make the comparison that revealed the insight themselves. Determine whether it is within a series, between series, against a target, or against a distribution. An indicator without a comparison baseline may inform but not explain. If no valid reference exists, do not invent one. Remove redundancy without hiding material context.

## Seven families (Dykes pp. 243–245)

| Family | Task | Candidates | Risk |
|---|---|---|---|
| Comparison | Magnitudes, differences | Bars, dots, lollipop, dumbbell, slopegraph | Inconsistent order or baseline |
| Trend | Temporal behavior | Lines, discrete columns | Artificially equidistant dates |
| Composition | Parts of a total | Stacked, 100%, table; pie only as exception | Segments lack common baseline; hidden total |
| Relationship | Association between variables | Scatterplot, bubbles proportional by area | Confusing association with causation |
| Distribution | Frequency, spread, concentration | Histogram, dots, boxplot if audience understands | Arbitrary bins, insufficient sample |
| Spatial | Geographic or spatial pattern | Choropleth of rates, points depending on objective | Area confused with population; boundaries/denominator |
| Flow | Transfers or transition | Flow/Sankey if flows known, diagram or table | Non-proportional width, invented flows |

Candidates are guidance from this skill based on the families, not a reproduction of fig. 7.15. Tables remain valid for exact lookup; if one number suffices, use text. Do not use complex charts merely for novelty. The book compares lollipop, dot plot, and dumbbell (pp. 248–251); add them only when they improve accuracy or reduce effort.

## Step 1 · Visualize the right data (pp. 236–243)

- Adjust metric: move from count to rate, common-base index, percentage change, or ratio if the question justifies it. Preserve original and declare formula, base, and period.
- Add context: prior period, target, appropriate mean, comparable group. An isolated number can be good or bad depending on context.
- Remove unnecessary data: if relevant comparison is the gap, show difference directly; retain absolute levels when they change interpretation.
- Dual Y-axis may induce arbitrary visual relationships. Prefer panels, common change index, or meaningful derived metric. Do not divide by a meaningless variable just to equalize scales. Example: revenue per customer answers a different question from revenue and number of customers.

## Step 2 · Choose by perception and task (pp. 243–251)

Position on common scale and length are preferable for precise magnitude comparisons; angle, area, volume, and saturation generally require more effort. This does not mean any bar chart is superior to any other chart: a map may be more appropriate if geography matters. Distinguish continuous variables, categories, ordinal values, and time. Select the simplest chart retaining necessary data structure.

- Two values per category: dumbbell visualizes gap between points; paired bars when length or absolute levels matter; slopegraph for two moments. If only change matters, use a zero-baseline diverging difference bar chart.
- Composition: 100% stacked for proportions, absolute bars if volume matters, panels when comparing segments without common baseline. Donut chart is not first choice.
- Distribution: histogram with explicit and appropriate bins; dots for few data; boxplot if audience knows median/quartiles. Density does not equal sample size.
- Geography: rates for comparing differently sized territories; counts for total burden if that is the question. Do not invent locations or maps without geographic information.

## Step 3 · Calibrate comparison (pp. 251–257)

1. **Proximity:** place together the elements to compare; order categories by task, not randomly. Alternate grouping by region or product according to comparison.
2. **Common baseline:** use shared baseline or aligned scales. Floating stacked components impede comparison; place important one at baseline or separate.
3. **Consistency:** in comparable panels, same interval, unit, origin, order, color, size, and aspect. If there are reasons for differing scales, declare them and do not compare heights as magnitudes.

## Alternative test (adaptation)

When two representations are plausible, check: (a) answers question, (b) enables direct comparison, (c) retains context and units, (d) requires little decoding, (e) is accessible and familiar, (f) reveals insight without exaggerating. Choose by function; do not give an arbitrary score as a scientific result. When in doubt, show alternatives with exactly the same data. Example: before/after participation, slopegraphs for direction of change; 100% bars for mix; paired bars for levels. If denominators are missing, do not convert proportions to quantities.

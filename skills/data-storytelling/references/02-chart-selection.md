# 02 · Visual selection

Based on Knaflic ch. 2, pp. 47–81, and ch. 9, pp. 253–259. Adapted decision rules and controls.

| Visual | When it works | Constraint and design |
|---|---|---|
| Simple text | One or two figures | Figure, unit, period, and comparison |
| Table | Exact reading, multiple units | Clear headings, numeric alignment, subtle borders |
| Heatmap | Matrix pattern | Justified sequential/diverging scale; legend and values if needed |
| Scatterplot | Quantitative association, outliers | Units, labels of interest, no causation |
| Lines | Continuous evolution | Consistent intervals, direct labels, selective focus |
| Slopegraph | Two moments and multiple categories | Labeled endpoints, same units, avoid confusing crossings |
| Grouped columns | Few discrete series | Zero baseline, clear groups, spacing between groups |
| Horizontal bars | Ranking and long names | Zero baseline, magnitude or natural order |
| Stacked bars/columns | Total and composition | Priority segment at baseline; interior segments difficult to compare |
| 100% stacked | Proportions | Hides volume; indicate base size if relevant |
| Waterfall | Contributions to net change | Anchored start/end, signs and values, reconciliation |
| Area charts | Relationship where area makes sense | Imprecise comparison; prefer length/position if accuracy matters |

## Construction

Bars and columns: quantitative axis from zero, positives and negatives on either side, width conducive to comparison. Axes or labels according to needed precision; avoid redundancy. Chronological order for time, natural order for ordinal values, magnitude for rankings, strategic order if the story requires it; preserve order across successive views when it supports learning.

Lines: proportional time, do not connect categories without continuity. Y need not start at zero, but use a clear, non-exaggerated scale. Distinguish observed from forecast with style and labels. Stacked charts: totals and segments with a common baseline are easier to compare; if all components matter, use grouped charts, slopegraphs, or small multiples. Heatmaps: missing values distinct from zero, labels if precision is required. Scatterplots: limits, overlap, influential points, no causal relationship without evidence. Waterfall: start + contributions = end; document rounding; may be simulated with stacked columns and an invisible base.

## Avoid and replace

Pie and donut charts make angles/arcs difficult to compare: use bars, text, or 100% stacked as appropriate. 3D distorts perception: use 2D. Dual Y-axis makes series association and scales difficult: use aligned panels, direct labels, or a justified transformation. Many lines: selective focus, separate panels, or both. If a constraint forces a suboptimal format, state the trade-off and minimize harm. Do not lose the total or proportion when changing format. If ambiguous, compare two alternatives using identical data. Before/after: slopegraphs for direction, paired bars for magnitude, 100% stacked for composition. There is no single correct chart for every situation.

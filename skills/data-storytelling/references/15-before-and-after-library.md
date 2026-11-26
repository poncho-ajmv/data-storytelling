# 15 · Case and redesign library

**Basis:** Dykes ch. 7 (PDF pp. 236–257), ch. 8 (pp. 260–302), and ch. 9 (pp. 304–344); Knaflic chs. 2–9. The 24 cases in the second section are **synthetic and original to this skill**, not cases or verbatim data attributed to the authors. The book *Antes y después* (*Before & After*) by Knaflic, Cisneros, and Velez was not supplied or consulted in full and is not used as a source. Anchors identify principles from the supplied books that justify decisions.

## Dykes source cases (lessons, not reproductions of figures)

| Anchor | Decision it teaches |
|---|---|
| Fig. 1.1, p. 30 | A two-peaked histogram invites investigation of segments instead of assuming an expected distribution. |
| Figs. 7.9–7.11, pp. 238–240 | Dual axes may hide meaning; comparable indices or revenue per customer may answer more precise questions. |
| Figs. 7.12–7.14, pp. 241–243 | Prior-year context or calculated differences can transform interpretation. |
| Fig. 7.21, p. 250 | Dumbbell charts compare two positions and their differences by category. |
| Figs. 7.23–7.27, pp. 255–257 | Grouping, common baseline, and panel consistency determine ease of comparison. |
| Figs. 8.3–8.5, pp. 264–265 | Reducing, grouping, or separating series and categories improves reading if material information is preserved. |
| Figs. 8.12–8.15, pp. 276–280 | Explanatory titles, linked annotations, selective typography, and layers guide reading. |
| Ch. 9, figs. 9.1–9.7 | Rosling orients the audience to the chart, uses references, pauses, and breaks down points to show context. |
| Ch. 9, figs. 9.9–9.18 | Sequenced scenes and linked evidence develop a complex story; do not reproduce its conclusions in other data. |
| Ch. 9, figs. 9.19–9.21 | A Data Trailer or a few comparisons can guide a decision without an extensive presentation. |

Spanish descriptions of figures in the TXT were added editorially by the transcription preparer; they are used alongside original text and captions, not as verbatim quotations of the author.

## Synthetic training cases

Each case specifies before → after → verification; render only if the user requests a chart. All quantities are fictional. Do not copy them into the user's report.

| No. | Data and purpose | Before: problem | After: choice and narrative | Validation and basis |
|---:|---|---|---|---|
| 1 | Q100, 105, 110, 94, 96, 98 thousand from January to June; recovery | Pie by month | Line; highlight decline and incomplete recovery, June −Q12 thousand vs. March | Equal periods; ch. 7, principles 1–2 |
| 2 | Incidents 42 payments, 28 access, 18 shipping, 12 other | Donut with legend | Sorted bars, payments accented, 42/100 | Zero baseline, sum 100; ch. 7, principle 2 |
| 3 | Positive opinion 30→55%, neutral 40→30%, negative 30→15% | Two pies | Slopegraph if change matters, 100% stacked if mix matters; +25 pp positive | Sums and base; no causation or significance; chs. 5, 7 |
| 4 | Balance 100 +40 −25 −5 =110 | Columns without reconciliation | Waterfall of contributions and final balance | Net contributions +10; Knaflic ch. 2, Dykes ch. 7 |
| 5 | Region A 49%, B 51% | Bars from 48%, exaggerated title | Zero-baseline bars or dots with scale; 2 pp difference | Do not claim significance; table 8.6 |
| 6 | 8 series × 12 months, no values available | Hypothetical spaghetti | Specify common-scale panels; request data | Do not invent lines; fig. 8.5 |
| 7 | Gross sales 115→120, returns 5→12, net 110→108 | Gross only, apparent improvement | Compare net sales and accounting bridge; returns +7 | Identities; no cause of returns; principle 1 |
| 8 | Customers 100→120, revenue 1000→1080 | Dual Y-axis | Revenue per customer 10→9; accompany with levels and context | Divide compatible units; figs. 7.9–7.11 |
| 9 | A 100/1000, B 20/100 | Count bars for relative risk | Rates 10% and 20% with bases; if total burden matters, show counts separately | Different questions; principle 1 |
| 10 | Expenses 80 vs. documented target 70 | KPI without reference | Bar or text “10 over budget” with unit and period | Do not confuse +10 with +10%; fig. 7.12 |
| 11 | Wait times 2, 3, 3, 4, 18 min | Single average of 6 | Individual dots and median 3; 18 is a descriptive outlier | n=5; do not infer population; ch. 6 outlier story point |
| 12 | Two observations on Jan 1 and 3, third on Feb 1 | Uniform spacing | Proportional time axis | Avoid false rate inference; table 8.6 |
| 13 | 4 regions, each with two products, interest in product within region | Grouped by product, distant comparison | Group by region; repeated product order | Do not change values; fig. 7.23 |
| 14 | 2 series in panels with ranges 0–100 and 0–10 | Heights appear equal | Common axis if magnitude matters; if pattern matters, indicate different scales | Explicit interpretation; fig. 7.27 |
| 15 | 3-category distribution: 70%, 20%, 10% | Rainbow colors, 3D | Bars or text “70% corresponds to X,” retain remainder | No depth or angles; chs. 7–8 |
| 16 | Forecast: history 80, 85; estimated future 90 | Continuous line without distinction | Solid observed, dashed estimate, label and assumptions | Do not promise 90; ch. 6 project forward |
| 17 | Customers by purchase size; active customers only | “All customers prefer…” | Restrict universe to active, request churned customers | Survivorship bias; ch. 5 |
| 18 | Relationship between advertising and sales without experiment | Title “Advertising caused…” | Scatterplot; “association observed” and possible factors | Do not infer causation; pp. 172–173 |
| 19 | Product A 75, B 60, C 20; objective compare A with B | Table and separate legend | Adjacent bars, gap label 15 | Common baseline and proximity; pp. 253–254 |
| 20 | North sales 20→25 and South 15→30 | “All regions grew” | Slopegraph or dumbbell; South rose 15 vs. North 5 | Comparable magnitudes; fig. 7.21 |
| 21 | Q10 thousand monthly cost, unknown horizon | “We will save Q120 thousand” | “If spending persists for 12 months and is eliminated, potential gross savings Q120 thousand,” costs pending | Conditions, not guarantee; pp. 201, 294–295 |
| 22 | Survey 8/10 satisfied | “80% of customers are satisfied” | “8 of 10 respondents satisfied; limited sample” | Unknown representativeness; ch. 5 |
| 23 | Four exploratory metrics without objective | Invented conclusive narrative | Monitoring dashboard with definitions and filters; ask about decision if appropriate | Valid storyframing; ch. 4 |
| 24 | Complex chart of 3 segments, oral presentation | Show everything and explain axes last | Orient to axes, reveal relevant segments, close with complete view | Layers with intact evidence; fig. 8.15, ch. 9 |

## Transfer exercise

For a new case: record audience and question, data and base, difficulty/value, candidate insight, alternative visual, title, before/after design, integrity check, and next step. Do not automatically select the same chart from the library if purpose has changed. Cases are written behavioral tests, not evaluation results of a deployed agent.

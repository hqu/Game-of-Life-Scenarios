# Game of Life Scenarios

A classroom dice game about how bias and compounding shape outcomes. Each of 100 students rolls a blue die (X) and a red die (Y) five times. Students 1–50 are male and 51–100 are female.

Open `index.html` in a browser. It is a single self-contained page; no install or build step.

## Scenarios

Each can be switched on in the top-right corner, with a slider to set its strength.

- **Gender penalty** — every die a female student rolls counts 0.1 to 1.0 less.
- **Rich get richer** — a student whose first roll totals 11 or 12 becomes a "trust fund kid" and re-rolls any die showing 1 (up to 1–3) on rolls 2–5.
- **Compound interest** — after each roll a student pays 3 in living expenses, then savings above 10 earn 10%–100% interest, which compounds on later rolls.

## Charts and measures

- Histograms of totals, male above female, one slice per student
- Scatter plot of sum of X against sum of Y
- Pareto chart with the cumulative share of points
- Probability density by gender against the unbiased fair-dice curve
- Lorenz curve and Gini coefficients
- Gender gap and trust fund boost tables
- Bias check with Welch t-tests and a plain-language explanation of each bias

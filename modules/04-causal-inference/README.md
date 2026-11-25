# Week 4 · Causal Inference and Midterm Workshop

[Open the Week 4 lab in Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/04-causal-inference/week04_causal_ml.ipynb) · [View the executed notebook on GitHub](week04_causal_ml.ipynb)

Trace a causal question from a treatment and outcome to an estimand, the assumptions that identify it, a computed estimate and a robustness check. Each step has a guiding question, equations, pseudocode, Python and results.

| Route | Walkthrough | Required rerun |
| --- | --- | --- |
| Economist, A1–A5 | Rebuild full-time-equivalent staffing from the Card–Krueger survey, interpret the NJ–PA before/after comparison, and vary the sample and controls. | Change `TREND_BIAS` to `1.5` in the separate synthetic panel. Compare the estimate, interval and placebo. |
| Computer scientist, B1–B4 | Inspect the ground-truth simulator, discover compatible graphs, identify effects under each graph, and estimate an adjusted dose effect with an interval. | Change `TIMING` to `"ordered"`. Compare graphs, effects and held-out prediction MAE. |

The paired historical comparison uses 309 New Jersey and 75 eastern Pennsylvania restaurants. The notebook reconstructs FTE from the component fields and shows a +2.75 FTE DiD contrast, its before/after figure and sensitivity checks. The synthetic graph example explains the distinction between a conditional confidence interval, ambiguity about the graph, and an omitted common cause.

## Recent readings

- Economists: [Baker et al. (2026), Difference-in-Differences Designs](https://doi.org/10.1257/jel.20251650) and [Wiltshire et al. (2026), Minimum Wage Effects and Monopsony Explanations](https://doi.org/10.1086/735551).
- Computer scientists: [Kim & Lee (2026), Causal Discovery with Logical Inference](https://proceedings.mlr.press/v337/kim26a.html) and [Guo, Wu & Yiu (2026), The Price of Valid Inference After Causal Discovery](https://proceedings.mlr.press/v337/guo26a.html).

## Run the notebook

Open Colab, choose **Runtime → Run all**, then save a copy in Drive to keep your changes. A CPU runtime is sufficient. The original survey is fetched at run time, with a pinned raw-field CSV fallback and an offline option for the simulations. The saved results include four figures.

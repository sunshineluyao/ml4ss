# Week 4 · Causal Inference and Midterm Workshop

[Open the Week 4 lab in Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/05-causal-inference/week04_causal_ml.ipynb) · [View the notebook and saved outputs on GitHub](week04_causal_ml.ipynb)

Would robot assistance improve inspection quality? These two examples use synthetic data. The lab compares a binary adoption effect in a workcell panel with a dose effect in a separate observation sample.

| Role | Rerun | What to explain |
| --- | --- | --- |
| Economist | Set `TREND_BIAS` to `1.5`. | Explain why the DiD and placebo estimates both rise, and what the interval measures. |
| Computer scientist | Set `TIMING` to `"ordered"`. | Explain why the set of compatible graphs changes and held-out prediction error stays fixed. |

## Run the lab

Open Colab and choose **Runtime → Run all**. A standard CPU runtime is enough. Save a copy in Drive to keep your changes. Run the defaults before changing one setting. Show one output and name the assumption you would test using field data.

The default run saves the panel group means, adoption estimate and placebo, candidate graphs, held-out mean absolute error, and a figure. The notebook documents the simulation, assumptions, pseudocode and sources. Its three-variable discovery routine illustrates conditional-independence logic used in constraint-based causal discovery.

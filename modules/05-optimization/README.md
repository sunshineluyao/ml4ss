# Optimization with reinforcement learning

## From a tax choice to a lending policy

[Open in Google Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/05-optimization/01_rl_economic_policy_econgym.ipynb) · [Read the notebook with saved outputs](01_rl_economic_policy_econgym.ipynb)

How can a bank keep lending when it needs cash to meet withdrawals? Learn the vocabulary of reinforcement learning, compare two rate spreads in one step of the original [EconGym banking scenario](https://doi.org/10.52202/085713-1515) from the NeurIPS 2025 Datasets and Benchmarks Track, and train a policy in a smaller lending simulation. The introduction connects Sutton and Barto's reinforcement learning textbook to the Turing Award announced in 2025 and uses the 2025 economics prize for innovation-driven growth to motivate the lending question.

1. Calculate the funded amount, cash shortfall, and reward for one decision. Use the Colab slider to vary demand.
2. Train [Stable-Baselines3 PPO](https://stable-baselines3.readthedocs.io/en/v2.7.1/modules/ppo.html) in a [Gymnasium](https://gymnasium.farama.org/api/env/) environment.
3. Compare the learned policy with two simple rules on common calm and withdrawal-shock test episodes. Read the credit, interest, and reserve metrics before revising the design.

Run top to bottom in a CPU runtime. The original EconGym cell downloads the public simulator at a fixed revision. The classroom simulation uses stated teaching assumptions. Both have saved results. The worked formulas, annotated code, pseudocode, package guide, and glossary are in the notebook.

For the shorter introduction to choosing one tax rate, start with the [Week 5 tax exercise](../08-innovation/README.md).

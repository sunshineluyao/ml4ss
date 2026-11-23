# Week 5 · Research and Innovation

[Open in Google Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/08-innovation/week05_matching_ml_methods.ipynb) · [Read the notebook with saved outputs](week05_matching_ml_methods.ipynb)

Use the methods cheat sheet from Ed Discussion to match a question to the evidence it needs. Open the notebook in Colab, read the example, then change an exercise field and rerun that cell. Run the setup cells and model fits before using their controls. The notebook uses a standard CPU runtime and reads the public ads from Hugging Face. Figures, tables, and your example project revision appear inline.

| Exercise | Try changing | Read the result |
|---|---|---|
| Data and measurement | Pick another held-out ad or enter a new title. Step from tokens to word counts, rarity weights, and final inputs. | Inverse document frequency (IDF) weights words by how rarely they occur in training titles. A new word outside the training vocabulary gets no column. |
| Explanation | Change the number of k-means groups from two to three and inspect another ad. | A group center gives the share of ads with each recorded label. Use those shares to name a group. |
| Prediction | Guess the model’s decision for a held-out ad, then reveal the result. | The measured title and duration feed logistic regression. Compare its estimated probability, 0.50 cutoff, and human reference label. |
| Causal inference | Move the Bluesky comparison from one week before and after first listing to two earlier dates. | Using rounded published group means, the first contrast is about +215 followers per account. The earlier comparison is about −5. The exercise uses the paper’s group averages to show the calculation. |
| Comparative evaluation and revision | Switch between screening and probability-versus-speed views. Sort each leaderboard by a different measure. | One AutoGluon fit trains logistic regression, random forest, and LightGBM. A frontier model has no competitor that beats it on one measure without doing worse on the other. Timing will vary by computer. |
| Optimization | **TBD.** See the methods cheat sheet for the overview. | |

The advertising examples use the original 193 training and 193 holdout YouTube ads from [Morio et al. (NeurIPS 2025)](https://doi.org/10.52202/085713-2956). The annotations and reuse terms are on [Hugging Face](https://huggingface.co/datasets/climate-nlp/multimodal-oil-gas-benchmark). The causal example starts with the [Bluesky release on June 26, 2024](https://bsky.social/about/blog/06-26-2024-starter-packs) and uses [Balduf et al. (ICWSM 2025), Figure 10(a)](https://www.eecs.qmul.ac.uk/~tysong/files/ICWSM25-Bluesky.pdf#page=8). The classroom comparison follows [Figure 5 of TabArena (NeurIPS 2025)](https://papers.neurips.cc/paper_files/paper/2025/file/1697e3fb412da11dc9488249f9e7bbc9-Paper-Datasets_and_Benchmarks_Track.pdf) and its [public leaderboard](https://tabarena.ai/).

Use the notebook’s filled project example to plan one revision and a test on new evidence. The notebook lists readings and package documentation beside each exercise.

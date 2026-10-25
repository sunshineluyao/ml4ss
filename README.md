# Machine Learning for Social Science

Interactive computational tutorials for asking consequential social questions, choosing empirical methods, evaluating evidence, and revising a research judgment.

Instructor and maintainer: **Luyao (Sunshine) Zhang, Duke Kunshan University**.

## Start here

[Open the Week 1 Day 1 notebook in Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/00-foundations/01_questions_evidence_methods.ipynb)

1. Save a notebook copy in Drive.
2. Enter a topic and work individually or in a group of 1–3.
3. Run all cells and keep the downloaded result ZIP and notebook.

The tutorial includes motivation, philosophical and mathematical definitions, pseudocode, executable CPU examples, real literature metadata, visualization outputs, guiding questions, and a recorded investigation. Its numerical data are explicitly synthetic. Automated literature method labels require human verification. Database-wide trend counts are distinguished from the distribution of a retrieved sample. Frontier papers are inspected; their large models are not executed in this Day 1 tutorial.

## Modules

| Folder | Purpose |
|---|---|
| `modules/00-foundations/` | Questions, evidence, and methods. Day 1 notebook available. |
| `modules/01-measurement/` | Future measurement tutorials. |
| `modules/02-explanation/` | Future explanation tutorials. |
| `modules/03-prediction/` | Future prediction tutorials. |
| `modules/04-causal-inference/` | Future causal inference tutorials. |
| `modules/05-optimization/` | Future decision and optimization tutorials. |
| `modules/06-frontier-methods/` | Future evaluation of emerging methods. |

`collaborative-learning/` reserves notebook locations for think-pair-share, workshops, symposia, exhibitions, peer review, reflection activities, and certificates. These directories are structural placeholders, not claims that those tutorials are released.

## Repository scope

This repository contains interactive code notebooks and supporting repository structure. Course slides, agendas, release packages, student submissions, reflections, grades, and identifiable education-study records belong in the course's approved communication and storage channels.

## Reuse and sources

Original executable code is MIT licensed. Original instructional prose and original conceptual visualizations in the notebooks are available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). OpenAlex bibliographic metadata are CC0; linked publications and any third-party materials retain their own licenses. The notebook records source URLs and retrieval times. Cite individual scholarly sources as well as this teaching resource when appropriate.

## Environment and verification

The core uses Python, NumPy, pandas, Matplotlib, scikit-learn, and IPython, all normally present in Colab. `requirements.txt` provides compatible local installation ranges. No hosted generative-AI account or GPU is required. Network retrieval is optional because the notebook embeds a dated metadata sample. A zero-match fallback remains visible and does not fabricate sources.

The 11 executable cells passed end-to-end verification in four scenarios: live education-inequality search, saved climate-adaptation sample, saved cultural-heritage sample, and a genuine zero-match query. All four completed with zero cell errors, generated the expected files, and passed ZIP integrity checks. The live example retrieved all three providers: arXiv, OpenAlex, and Crossref. Verification used Python 3.12 and in-process IPython with Colab-compatible core packages. The notebook was not run inside a signed-in Google Colab browser; service access and browser download behavior remain external conditions.

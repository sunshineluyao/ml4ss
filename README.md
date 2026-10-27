# Machine Learning for Social Science

Interactive computational tutorials for asking consequential social questions, choosing empirical methods, evaluating evidence, and revising a research judgment.

Instructor and maintainer: **Luyao (Sunshine) Zhang, Duke Kunshan University**.

## Start here

[Open the revised Week 1 Wednesday notebook in Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/00-foundations/02_week1_research_innovation.ipynb)

Wednesday Research addresses Monday's feedback on originality, empirical design and data access before the Innovation canvas. It adds a seven-resource publication-linked data catalog, three small real-data excerpts and a research-design form. See [the Foundations guide](modules/00-foundations/README.md) for the distinction between observed data, published summaries and synthetic tutorials, access conditions, provenance and the short visual reflection.


[Open the Week 1 Day 1 notebook in Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/00-foundations/01_questions_evidence_methods.ipynb)

1. Save a notebook copy in Drive.
2. Read the opening purpose and learning-objective map; work individually or in a group of 1–3.
3. Complete the student-input forms in Parts 1–3, run all cells, and keep the result ZIP and notebook with outputs.

## The Day 1 investigation

The notebook has exactly three top-level parts, with numbered subsections:

| Part | Student activity | What changes |
|---|---|---|
| 1. Learn and experiment with research methods | Read the concepts; record an initial question and expectation; change proxy noise, budget share, or seed. | A shared 600-person simulation and its numerical results. |
| 2. Discover and verify literature on your question | Change the topic, comparison topic, year range, retrieval cap, or source mode; inspect and verify records. | Bibliographic discovery and literature charts. |
| 3. Explain, reflect, and export your investigation | Write a finding, revision, next step, and manual search audit; save the outputs. | Your recorded reasoning and exported investigation. |

Every section identifies **READ & LEARN**, **STUDENT INPUT**, **RUN & OBSERVE**, or **HUMAN CHECK**. All 26 form fields have definitions, defaults, allowed values, examples, and expected effects. The package guide explains NumPy, pandas, Matplotlib, scikit-learn, IPython, the standard-library tools, and alternatives linked to official documentation.

`TOPIC` changes literature discovery. `PURPOSE` and `CONTEXT` record the student's intended purpose and setting; they do not select a model or apply a geographic filter. All numerical methods use the common simulated case. For a controlled experiment, change one parameter and keep the seed fixed.

After changing an analysis setting, run all cells. After changing only Part 3 written answers, run that form and the final export cell. Export detects changed analysis settings that would otherwise produce stale results. The ZIP includes parameter definitions and a learning-objective map; save the `.ipynb` separately with its executed outputs.

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

The revised notebook contains 13 executable cells. Verification covers the default live run, low/high measurement noise, low/high allocation capacity, a cultural-heritage query and changed purpose/context, a narrowed date range, a genuine zero-match query, forced provider failure, and answer refresh with stale-export checks. The checked example outputs are saved in the notebook. Validation uses Python 3.12 and real in-process IPython with Colab-compatible core packages, including rich figure/HTML outputs. Public Colab rendering is checked separately; execution inside a signed-in hosted Colab runtime and browser download prompts remain external conditions.


Current Week 1 reading policy: Active research literature uses the rolling window October 27 2024 to October 27 2026, in leading journals or main conference proceedings. Older classics are retained only with a verified Nobel or Turing author exception. Dataset observations, provider instructions, course policies and original-paper bibliographies are source records rather than new reading recommendations. The classroom A2 worksheet records a prediction before Colab and an observed result and revised design after it. The individual reflection is a separate PDF of at most two A4 pages, named netID_LastName_Firstname.pdf, attached to a reply on the Ed reflection post.

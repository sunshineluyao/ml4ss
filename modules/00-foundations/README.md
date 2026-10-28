# Foundations: Questions, Evidence, and Methods

[Open the revised full Week 1 notebook in Google Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/00-foundations/02_week1_research_innovation.ipynb)

## Week 1 Wednesday Research after Monday feedback

Monday's think–pair–share is Practice. Wednesday uses Research to address originality, method–claim alignment and usable data before the Innovation canvas. The three top-level notebook parts remain intact.

In Sections 2.1C–2.1E, distinguish theory, simulation, observational analysis and behavioral experiments, then match one of five empirical purposes to appropriate validation. Behavioral research is empirical. New human-subject research needs the appropriate institutional determination and any required approval before activities begin; public data do not automatically settle privacy or reuse terms.

The catalog links nine publication-associated resources: FMA and ArtEmis; FinQA, LexGLUE and Folktables; SustainBench, Dynamic World, WeatherBench 2 and GHCN-Daily. Each record includes paper/data URLs, access conditions, a task, baseline, validation and a limited candidate question. Catalog selection does not download the source datasets.

Three small attributed real-data excerpts are embedded for CPU exploration: the complete FMA 163-row genre taxonomy, the first 200 FinQA training examples, and 1,096 quality-screened Central Park station-days from 2018–2020. The first two support descriptive inspection. The station example compares Ridge with persistence using a chronological split and MAE in degrees Celsius. These are classroom subsets, not full paper replications. The common 600-person numerical tutorial remains synthetic and visibly labeled. Provenance, transforms, retrieval date and checksums accompany the excerpts.

The two deep dives remain Xu et al.'s verified public role taxonomy and Tong, Wu and Evans's ML measurement of occupational skill change. The latter uses licensed raw Lightcast ads; our comparison reuses published summary values and does not retrain skill2vec or identify robot-adoption effects.

New forms record the observation unit, empirical source, ML task, baseline, validation, limited claim, access/review check and a revision from Monday. Parameter definitions give defaults, allowed changes, examples and expected effects. The inline review checks for stale empirical settings and displays the current design, evidence, source checks and audit. Data passports, catalog entries, provenance and figures remain available in the earlier notebook cells.

The individual Week 1 reflection is a PDF of at most two A4 pages with **two figures and 200–300 words including captions**, plus references and URLs within the same pages. Reply to the Ed reflection post by **Sunday November 1, 2026 at 23:00 China Standard Time**. Include two close studies, the source URL and an instructor-accessible URL to the revised Colab copy. Use the executed Colab copy when saving is available, or copy the displayed evidence and responses while the session is open. No result ZIP is required. Week 2 develops multimodal data and measurement for PS1 and the final research demo.

Ludwig, J., Mullainathan, S., & Rambachan, A. (2026). Large Language Models: An Applied Econometric Framework. Annual Review of Economics, 18, 283–316. https://doi.org/10.1146/annurev-economics-120925-105620

## Original foundations tutorial

[Open the Day 1 tutorial in Google Colab](https://colab.research.google.com/github/sunshineluyao/ml4ss/blob/main/modules/00-foundations/01_questions_evidence_methods.ipynb)

Work individually or in a group of 1–3. Save a copy in Drive and read the opening purpose, learning-objective map, and activity legend. Use a standard Colab Python 3 CPU runtime. No paid model, GPU, or API key is required for the core tutorial.

## Three parts

1. **Learn and experiment with research methods.** Read the concepts and package guide; enter your initial reasoning; change measurement noise, budget share, or seed in the student form. All numerical examples use the same explicitly synthetic 600-person case.
2. **Discover and verify literature on your question.** Change the main keyword, comparison keyword, year range, retrieval cap, and auto/snapshot setting. Inspect actual metadata, compare sources, check two original studies, and repair one search gap manually.
3. **Explain, reflect, and display your investigation.** In the revised Wednesday notebook, run the filled Part 3 examples, read the printed outputs, replace the examples with your own work, and rerun the final inline review. The innovation canvas, Q4–Q6, manual audit, and two source checks all print in the notebook. No ZIP is created or downloaded.

The form fields document their definition, default, allowed input, example, and expected effect. **READ & LEARN**, **STUDENT INPUT**, **RUN & OBSERVE**, and **HUMAN CHECK** labels tell you what to do. The supplied implementation stays unchanged for Day 1.

Changing `TOPIC` changes literature discovery. `PURPOSE` records your purpose and `CONTEXT` records your setting; they do not select models or filter geography. The numerical example does not become real community data when you change a keyword.

## Running and interpreting the revised Wednesday notebook

- Change one factor at a time; keep `SEED` fixed while comparing another parameter.
- After changing numerical or literature settings, use **Runtime → Run all**.
- After changing only Part 3 text in the revised Wednesday notebook, run each edited input cell and the final inline review. The review checks for stale analysis settings.
- The notebook includes saved outputs from the verified default run. Real metadata can fall back to dated saved samples; read the actual source status. Snapshot mode skips live source comparison and database-wide trend queries.
- The revised Wednesday notebook contains saved sample outputs and an inline investigation review. Copy the displayed responses and required figures into the course-approved submission when saving or downloading is unavailable. If saving works, retain an instructor-accessible Colab copy. Replace every `EXAMPLE:` response and mark a source/search as checked only after performing the check yourself.

Slides, agendas, student reflections, grading, and teaching release packages are distributed through the course channels. This public repository contains interactive code notebooks and the structure required to use and extend them.


Current Week 1 reading policy: Active research literature uses the rolling window October 27 2024 to October 27 2026, in leading journals or main conference proceedings. Older classics are retained only with a verified Nobel or Turing author exception. Dataset observations, provider instructions, course policies and original-paper bibliographies are source records rather than new reading recommendations. The classroom A2 worksheet records a prediction before Colab and an observed result and revised design after it. The individual reflection is a separate PDF of at most two A4 pages, named netID_LastName_Firstname.pdf, attached to a reply on the Ed reflection post.


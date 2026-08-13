# DATA 6400: Machine Learning for Sequential Data Processing

**University of Guelph**  
**Department of Mathematics and Statistics**  
**DATA 6400*01 — Machine Learning for Sequential Data Processing [0.5]**  
**Winter 2026**  
**Instructor: Dr. Abeer Badawi**

## Course Overview

Large language models (LLMs) are AI systems that learn to understand and generate human language from large collections of text. Rather than relying on hand-written rules, these models learn patterns, structure, and meaning from sequential data and use context to predict and generate language.

This course examines **LLMs as models for sequential data processing**, with a primary focus on natural-language sequences such as sentences, paragraphs, documents, and multi-turn conversations. Students study both foundational sequence-modeling concepts and modern LLM methods, developing the theoretical background and practical skills required to analyze, adapt, evaluate, and responsibly apply language models to real-world sequence-modeling problems.

### Core Topics

- Text representation and preprocessing
- Tokenization and embeddings
- Positional encoding and sequence order
- Context modeling and long-context behavior
- Foundational sequence models and transformer architectures
- Prompt-based LLM adaptation
- Fine-tuning and parameter-efficient adaptation
- LLM evaluation, robustness, and reliability
- Sequential reasoning and multi-turn interaction
- Responsible use of LLMs in applied settings

## Research Project Component

A major component of the course is an **ACL-style team research project**. Students develop a research question involving LLMs and sequential language data, motivate the problem using relevant literature, select and justify suitable data, design a feasible LLM-based methodology, and define an evaluation strategy capable of supporting or refuting their research hypothesis.

The project is designed to move beyond implementation alone. Students are expected to frame their work as a research contribution and to connect model design, data choices, compute constraints, evaluation methodology, and scientific novelty.

### Project Proposal

The project begins with an approximately **two-page ACL-style research proposal**. The proposal asks each team to define:

1. **Project title, group, and members**
2. **Problem statement and motivation**, ending in a clear research question or hypothesis
3. **Related work** grounded in relevant ACL/EMNLP/NAACL research
4. **Dataset description and selection**, including ground truth and preprocessing
5. **Model and methodology**, including how sequential structure is handled
6. **Compute and resource requirements**, including GPU, memory, and estimated runtime
7. **Evaluation plan**, including metrics, baselines, error analysis, robustness, or generalization
8. **Expected outputs and novel contribution**
9. **ACL-style references**

➡️ [View the full Project Proposal Guidelines](Course_Project/ACL_Style_Project_Proposal_Guidelines.pdf)

## Selected Student Research Projects

The following projects illustrate the range of research questions explored in the course. Each project folder contains a written project artifact and the team's final presentation.

| # | Project | Research Focus | Materials |
|---|---|---|---|
| 1 | **Sequence Marketing** — *Robust Fake Review Detection with Large Language Models: A Prompt Rewording and Review Length Analysis* | Robustness of LLM-based fake-review detection to prompt wording and review length | [Project Folder](Student_Projects/01_Sequence_Marketing_Fake_Review_Detection) |
| 2 | **Business Reasoning** — *From Accuracy to Reliability: Risk-Aware Evaluation of Large Language Models for Decision-Support Under Sampling Variability* | Reliability, stability, hallucination risk, and reasoning selection under repeated sampling | [Project Folder](Student_Projects/02_Business_Reasoning_Risk_Aware_LLM_Evaluation) |
| 3 | **Drug Discovery** — *Chain-of-Thought Distillation for Drug-Drug Interaction Prediction* | Transferring pharmacological reasoning from larger to smaller language models | [Project Folder](Student_Projects/03_Drug_Discovery_CoT_Distillation) |
| 4 | **Humanity's Last Proctors** — *V-BReE: A Variance-thresholded Blinded Refinement Ensemble for Multi-Agent LLM Reasoning* | Multi-agent reasoning, refinement, independence, and sycophancy mitigation | [Project Folder](Student_Projects/04_Humanitys_Last_Proctors_Multi_Agent_Reasoning) |
| 5 | **Medical MCQA** — *Beyond Accuracy: A Survival-Based Evaluation Framework for Elimination Reasoning in Medical Multiple-Choice Question Answering* | Sequential elimination reasoning and evaluation beyond final-answer accuracy | [Project Folder](Student_Projects/05_Medical_MCQA_Survival_Based_Evaluation) |
| 6 | **MentalX** — *From Generalization to Clinical Utility: A Strategic Alignment Pipeline for Qwen 3-4B in Mental-Health Dialogue* | Prompt engineering, parameter-efficient alignment, and clinically oriented LLM evaluation | [Project Folder](Student_Projects/06_MentalX_Clinical_LLM_Alignment) |
| 7 | **Paracheck** — *Evaluating Paraphrased Answer Consistency of Large Language Models in Multiple-Choice Commonsense Questions* | Robustness and consistency under meaning-preserving paraphrases | [Project Folder](Student_Projects/07_Paracheck_Paraphrase_Consistency) |
| 8 | **Rainfall** — *Multi-basin Rainfall–Runoff Modelling with LLM-based Zero-Shot Basin Generalization* | Transfer of language-model representations to structured scientific sequence modeling | [Project Folder](Student_Projects/08_Rainfall_Zero_Shot_Basin_Generalization) |

## Repository Structure

```text
DATA-6400-Machine-Learning-for-Sequential-Data-Processing/
├── README.md
├── Course_Project/
│   ├── README.md
│   └── ACL_Style_Project_Proposal_Guidelines.pdf
└── Student_Projects/
    ├── 01_Sequence_Marketing_Fake_Review_Detection/
    ├── 02_Business_Reasoning_Risk_Aware_LLM_Evaluation/
    ├── 03_Drug_Discovery_CoT_Distillation/
    ├── 04_Humanitys_Last_Proctors_Multi_Agent_Reasoning/
    ├── 05_Medical_MCQA_Survival_Based_Evaluation/
    ├── 06_MentalX_Clinical_LLM_Alignment/
    ├── 07_Paracheck_Paraphrase_Consistency/
    └── 08_Rainfall_Zero_Shot_Basin_Generalization/
```

## Teaching and Learning Goals

Through the research project, students practice the full cycle of applied LLM research: identifying a meaningful problem, positioning it within prior work, designing experiments, managing practical compute constraints, evaluating model behavior rigorously, interpreting results, and communicating findings in both written and presentation formats.

This repository serves as a record of selected course materials and student research outputs from **DATA 6400*01, Winter 2026, University of Guelph**.

## Attribution

Course materials were developed for DATA 6400*01 at the University of Guelph. Student project reports and presentations remain the work of their respective authors and are included here as examples of course research activities.

# Human-GenAI Collaborative Pedagogy and Learning Analytics for HPC Education with Industrial Software Practice

**ICDM 2026 Education Forum · Accepted paper**

**Nan Hu\*, Yiyang Chen, Ruihui Li, Zhuo Tang, and Kenli Li**  
College of Computer Science and Electronic Engineering, Hunan University, Changsha, China  
\*Corresponding author: Nan Hu — hunan5@hnu.edu.cn

## Overview

**AI-enabled HPC Education (AHE)** is a pedagogical framework that connects generative AI, high-performance computing (HPC), industrial software practice, and learning analytics. It addresses a central educational challenge: students can generate code rapidly with AI without necessarily understanding its logic, validating its correctness, or assessing its engineering reliability.

AHE organizes learning around observable evidence from code development, human-GenAI interaction, testing, HPC execution, and reflection. A multisource learning-data mining method and a knowledge-competency graph are designed to support competency assessment, learning-risk prediction, and personalized instructor guidance.

This repository presents the paper and its research framework. It does not contain a source-code release. The paper proposes an instructional framework and illustrates it through an FFT learning unit; it does not report a quantitative evaluation of student learning outcomes.

## Abstract

The rapid adoption of generative artificial intelligence (GenAI) has provided more efficient instructional and programming support for high-performance computing (HPC) education. However, fragmented curricula and the inappropriate use of code-intelligence tools enable students to generate code rapidly with AI without necessarily understanding its underlying principles, validating its correctness, or assessing its engineering reliability. Educational data mining (EDM) and knowledge-competency graphs can transform human-GenAI interactions and learning processes into observable and analyzable learning evidence, providing a methodological foundation for an instructional framework that addresses these limitations.

This paper proposes AI-enabled HPC Education (AHE), an innovative pedagogical framework for responsible GenAI-enabled HPC education through industrial software practice. AHE integrates curriculum organization, human-GenAI collaboration, HPC validation, and industrial practice into an instructional system. We further develop a multisource learning-data mining method and a knowledge-competency graph that link learning tasks, knowledge structures, competency states, and process evidence to support learner-state modeling, competency assessment, risk prediction, and personalized instructional intervention. The framework promotes responsible AI use in HPC coursework and engineering practice while providing instructors with evidence-based support for student guidance.

**Keywords:** High-performance computing education; Generative AI in education; Educational data mining; Learning analytics.

## Main Contributions

1. **An integrated instructional architecture.** Four layers connect curriculum integration, code intelligence, HPC validation, and industrial software practice, with learning analytics spanning all layers.
2. **A responsible human-GenAI learning workflow.** Generate–Understand–Verify–Analyze–Reflect makes code comprehension, validation, evidence-based decisions, and reflection explicit parts of AI-assisted learning.
3. **Evidence-based learning analytics.** Multisource learning data and a knowledge-competency graph connect tasks, concepts, competencies, and process evidence to support assessment, risk prediction, and personalized intervention.

## Four-Layer Architecture

| Layer | Instructional focus | Representative activities and evidence |
| --- | --- | --- |
| Curriculum integration | Connect knowledge across courses | Programming, data structures, computer systems, operating systems, software engineering, and parallel computing |
| Code intelligence | Use GenAI with human understanding and review | Prompt design, code explanation, accepted and rejected suggestions, revisions, and provenance records |
| HPC validation | Evaluate correctness and execution behavior | Consistency checks, runtime, speedup, parallel efficiency, resource use, and profiling |
| Industrial software practice | Apply learning in engineering workflows | Requirements analysis, preprocessing, parallel execution, validation, visualization, documentation, and interpretation |

Across these layers, learning analytics connects **data acquisition, competency modeling, and feedback generation**. Instructors guide learning through task decomposition, worked examples, milestone reviews, and targeted intervention.

## Responsible AI Learning Workflow

**Generate → Understand → Verify → Analyze → Reflect**

| Stage | What students do |
| --- | --- |
| Generate | Specify requirements and use GenAI to obtain initial code, explanations, tests, or improvement proposals. |
| Understand | Explain algorithmic logic, data structures, assumptions, and risks. |
| Verify | Check compilation, functional correctness, boundary cases, regressions, and consistency across relevant execution settings. |
| Analyze | Interpret execution and performance evidence to accept, reject, or revise AI-generated suggestions. |
| Reflect | Document AI contributions, independent work, revisions, validation evidence, limitations, and remaining learning needs. |

## Learning Analytics and the Knowledge-Competency Graph

AHE combines five categories of learning evidence:

- **Code data:** versions, submission history, structural characteristics, and revision trajectories.
- **AI-interaction data:** prompts, responses, accepted and rejected suggestions, provenance declarations, and student explanations.
- **Compilation-and-testing data:** errors, warnings, test results, and error-repair trajectories.
- **HPC execution data:** execution parameters, runtime, resource metrics, consistency checks, and profiling summaries.
- **Reflective-text data:** reports, documentation, reflections, instructor feedback, and intervention records.

The knowledge-competency graph links **students, learning tasks, knowledge concepts, competency dimensions, and learning evidence**. It is designed to represent development across six dimensions:

| Competency dimension | Assessment focus |
| --- | --- |
| Programming | Correctness, debugging, and implementation quality |
| Systems reasoning | Understanding compilation, memory, runtime behavior, and hardware |
| Responsible AI use | Explanation, provenance, validation, and critical review of AI outputs |
| Parallel-computing reasoning | Parallel correctness, scalability, and performance interpretation |
| Software engineering | Modularity, interfaces, testing, documentation, and maintainability |
| Domain application | Engineering assumptions, workflow completeness, and result interpretation |

The proposed applications are **competency classification**, **learning-risk prediction**, and **personalized intervention recommendation**. Competency levels are novice, developing, proficient, and advanced. Analytics is intended to support instructor judgment with traceable evidence.

## Illustrative Case: FFT-Based Vibration-Fault Diagnosis

The paper illustrates AHE through an HPC learning unit on FFT-based vibration-fault diagnosis for industrial equipment.

1. Define the industrial task, learning objectives, sampling rate, input size, numerical precision, execution platform, and real-time constraints.
2. Develop and explain a serial FFT baseline with GenAI assistance.
3. Validate correctness and explore parallelization with OpenMP, MPI, or CUDA.
4. Compare runtime, speedup, parallel efficiency, and profiling evidence across data sizes and resource configurations.
5. Integrate the validated FFT module into a workflow covering data loading, preprocessing, frequency-domain transformation, spectral peak extraction, visualization, and reporting.
6. Use learning traces and instructor feedback to identify competency gaps and select follow-up activities.

The case demonstrates how the proposed instructional process can be organized; it is not presented as a controlled educational experiment or a benchmark study.

## Future Work

- Extend AHE to machine learning, large-scale data processing, data science, and other practice-oriented computing courses.
- Develop LLM-based tutoring, learner-state diagnosis, and immediate adaptive feedback.
- Investigate transferable responsible-AI practices and process-based assessment across engineering domains.

## Citation

The following is a provisional citation for the accepted paper. DOI, page numbers, and final proceedings metadata should be added when available.

```bibtex
@misc{hu2026ahe,
  title  = {Human-GenAI Collaborative Pedagogy and Learning Analytics for HPC Education with Industrial Software Practice},
  author = {Hu, Nan and Chen, Yiyang and Li, Ruihui and Tang, Zhuo and Li, Kenli},
  year   = {2026},
  note   = {Accepted at the ICDM 2026 Education Forum}
}
```

## Acknowledgment

This work was supported by the National Key Research and Development Program of China under Grant 2025YFB3003601 and the National Natural Science Foundation of China under Grant 62502152.

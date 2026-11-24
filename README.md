# AI Quality Lab — English & Arabic

A bilingual human-review practice lab for evaluating AI-generated answers in English and Arabic, including Iraqi Arabic. This portfolio project demonstrates a structured review workflow relevant to AI Quality Analyst, AI Evaluator, Data Quality, and Trust & Safety roles.

## Project overview

The lab uses fictional prompts and sample responses to practise reviewing four quality dimensions:

| Dimension | What the reviewer checks |
| --- | --- |
| Accuracy | Whether claims are supported by the prompt or supplied reference |
| Clarity | Whether the answer is understandable, relevant, and well organised |
| Instruction following | Whether the response follows the task, format, and language requested |
| Language quality | Whether wording is natural and appropriate for the requested language or variety |

Reviewers assign a score from 1–5 for each dimension, document evidence, and choose an overall decision: **Pass**, **Needs improvement**, or **Fail / escalate**.

## Practice exercises

| Exercise | Focus | Cases |
| --- | --- | ---: |
| [Day 01](day-01/README.md) | Core bilingual review and rubric practice | 4 |
| [Day 02](day-02/README.md) | Unsupported claims, strict instructions, uncertainty, and Arabic variety | 7 |
| [Day 03](day-03/README.md) | Reviewer judgement, missing context, privacy, and assumptions | 6 |
| [Day 04](day-04/README.md) | Owner-reviewed practice decisions across accuracy, instructions, language, privacy, and false action claims | 6 |

## Getting started

1. Read the [evaluation rubric](evaluation-rubric.md).
2. Choose a practice set: [Day 01](day-01/README.md), [Day 02](day-02/README.md), [Day 03](day-03/README.md), or [Day 04](day-04/README.md).
3. Read each prompt and its expected behaviour before judging the sample response.
4. Record independent scores and evidence in the relevant `evaluation_log_template.csv`.
5. Compare your reasoning with any example log only after completing your own review.

## Repository structure

- `evaluation-rubric.md` — scoring guidance and reviewer principles.
- `day-01/` — introductory bilingual cases and example review files.
- `day-02/` — advanced cases involving uncertainty, unsupported claims, and language variety.
- `day-03/` — reviewer judgement cases and a blank evaluation log.
- `day-04/` — six guided, owner-reviewed decisions and their rationales.

Each practice folder contains its own instructions and review files.

## Skills demonstrated

- Structured human evaluation of AI-generated text
- Accuracy, clarity, and instruction-following review
- English and Arabic language-quality assessment
- Modern Standard Arabic and Iraqi Arabic variety awareness
- Evidence-based reviewer notes and escalation
- Consistent scoring and quality documentation
- Identifying missing context, unsupported assumptions, and privacy issues

## Important scope and limitations

This is a **human evaluation practice lab**, not an automated AI benchmark or a production AI system. The examples are fictional training material. The rubric supports consistent review but does not prove factual correctness. Current or specialist claims should be checked against reliable sources.

Some existing example evaluation logs are labelled as **AI-assisted draft reviews pending owner review**. They must not be represented as independent reviews personally completed by the repository owner. Use the blank templates for your own independent practice.

## Author

Hiba Almamoori

# AI Answer Evaluation Rubric

Use this rubric to review one AI response at a time. Score each dimension from **1 (poor) to 5 (excellent)**. Base the score on the prompt, any supplied reference material, and observable evidence. Do not guess when the evidence is missing.

## 1. Accuracy

| Score | Guidance |
|---|---|
| 1 | Contains major false or misleading claims. |
| 2 | Contains important errors or unsupported claims. |
| 3 | Mostly correct, but has a noticeable gap or an unverified claim. |
| 4 | Correct and relevant, with only a minor omission. |
| 5 | Fully correct and well-supported by the available evidence. |

If no reference is supplied and a claim cannot be verified, note **needs verification** rather than treating confidence as proof.

## 2. Clarity

| Score | Guidance |
|---|---|
| 1 | Very difficult to understand or poorly organised. |
| 2 | Confusing in several places. |
| 3 | Understandable, but could be more direct or organised. |
| 4 | Clear and easy to follow, with a minor issue. |
| 5 | Clear, concise, and well structured for the user. |

## 3. Instruction following

| Score | Guidance |
|---|---|
| 1 | Ignores the main request or required constraints. |
| 2 | Follows only a small part of the request. |
| 3 | Completes the main task but misses a relevant instruction. |
| 4 | Follows the instructions with a minor omission. |
| 5 | Fully follows the requested task, language, format, and constraints. |

## 4. Language quality

| Score | Guidance |
|---|---|
| 1 | Hard to understand; frequent grammar or word-choice errors. |
| 2 | Several errors that affect readability or meaning. |
| 3 | Understandable, but noticeably unnatural or inconsistent. |
| 4 | Natural overall, with a minor language issue. |
| 5 | Fluent, natural, grammatically sound, and appropriate to the audience. |

For Arabic, assess spelling, grammar, phrasing, and whether the response uses the requested variety (Modern Standard Arabic or a specified dialect). Do not penalise a response for using a different Arabic variety unless the task specifies one.

## Overall decision

- **Pass:** no critical issue; the response meets the task requirements.
- **Needs improvement:** one or more dimensions need correction, but the response is still usable after revision.
- **Fail / escalate:** a serious accuracy, safety, instruction-following, or language issue makes the response unsuitable.

The overall decision is a reviewer judgement; do not calculate it by averaging scores alone. Explain any critical issue in the reviewer notes.

## Reviewer principles

- Evaluate only what the prompt asks for.
- Separate factual accuracy from writing quality.
- Quote or identify the exact phrase that caused a concern.
- Do not invent missing context or assume an answer is correct because it sounds confident.
- Be consistent across English and Arabic examples.
- Record uncertainty and escalate claims that require specialist verification.

# Day 02 - More Challenging Evaluation Cases

This practice set introduces issues that appear in real AI quality review work:

- Unsupported or time-sensitive claims
- Exact formatting and instruction constraints
- Beginner-friendly explanations
- Modern Standard Arabic versus Iraqi Arabic
- Conflicting instructions
- Uncertainty and overconfident conclusions

## How to review

1. Read the prompt and expected behaviour before judging the sample response.
2. Score accuracy, clarity, instruction following, and language quality from 1 to 5 using the main rubric.
3. Identify the exact words or behaviour that caused a low score.
4. Choose Pass, Needs improvement, or Fail / escalate. Do not rely on an average score alone.
5. For current or specialist claims, record what evidence is missing. Do not verify a claim by guessing.

## Important notes

- These are deliberately constructed training examples, not real user conversations.
- The expected behaviour is a review guide, not an external gold-standard fact source.
- EN-003 is about unsupported current information; its stated closing time should not be treated as verified.
- AR-003 and AR-004 test whether the response follows the requested Arabic variety.
- EN-006 tests whether the model communicates uncertainty appropriately.

## Suggested next step

Complete the evaluations in a separate review log. Keep the original sample responses unchanged so reviewers can compare the original and revised versions.

## Review files

- `evaluation_log_template.csv` — blank log for your own independent scores.
- `evaluation_log_example.csv` — AI-assisted draft scores and explanations, pending owner review.

Compare your own reasoning with the example only after you have attempted the cases. The example is a learning aid, not a substitute for your own review.

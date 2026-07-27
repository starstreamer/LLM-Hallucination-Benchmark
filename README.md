# LLM Hallucination Benchmark

A structured benchmark for identifying, classifying, and analyzing hallucinations and factual failures in large language models.

## Project objective

The project evaluates whether large language models produce:

- fabricated facts;
- unsupported conclusions;
- nonexistent or incorrect citations;
- invalid reasoning;
- outdated information;
- incorrect calculations;
- misleadingly confident answers.

## Benchmark target

The completed benchmark will contain 100 prompts across multiple categories.

| Category | Planned prompts |
|---|---:|
| Factual knowledge | 15 |
| Citations and sources | 10 |
| Logical reasoning | 10 |
| Mathematics | 10 |
| Coding | 10 |
| Business analysis | 10 |
| Temporal knowledge | 10 |
| Multi-step reasoning | 10 |
| Ambiguous questions | 5 |
| Edge cases | 10 |
| **Total** | **100** |

## Evaluation process

1. Create a verified prompt and expected answer.
2. submit the same prompt to each selected model.
3. Preserve the model's complete response.
4. Verify factual claims using authoritative sources.
5. Classify any failure.
6. Assign a severity score.
7. Document the evidence and corrected answer.
8. Analyze performance across models and categories.

## Repository structure

```text
data/        Structured prompts, responses and evaluation records
docs/        Evaluation instructions and scoring rubric
notebooks/   Data analysis notebooks
prompts/     Human-readable prompt collections
reports/     Methodology, findings and limitations
results/     Raw model outputs
scripts/     Validation and analysis scripts
images/      Charts and supporting images

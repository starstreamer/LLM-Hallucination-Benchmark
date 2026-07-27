
# Methodology

## Research objective

This project evaluates how frequently large language models produce inaccurate, fabricated, unsupported, or misleading information across different task categories.

## Benchmark composition

The benchmark will contain 100 prompts covering:

- factual knowledge;
- logical reasoning;
- mathematics;
- coding;
- business analysis;
- citations and sources;
- temporal knowledge;
- multi-step reasoning;
- ambiguity and edge cases.

## Testing procedure

Every model receives the same core prompt. Responses are preserved without correction and evaluated using a predefined scoring rubric.

## Verification procedure

Claims are checked against authoritative sources. Evaluations include the correct answer, supporting evidence, failure classification and severity.

## Reproducibility

The project records the model, model version, test date, prompt wording and relevant generation settings.

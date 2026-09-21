# Technical Highlights

## 1. Safety boundary outside the LLM

Model output is treated as a draft. Deterministic backend rules re-check claims, evidence levels, causal language, and provenance.

## 2. Evidence as product data

Citations are inspectable product objects, not decorative links.

**Claim → Evidence detail → Original source**

## 3. Honest uncertainty

The design supports evidence states such as established, moderate, limited, conflicting, and research gap. The product is allowed to answer: **we do not know**.

## 4. Adaptive-question architecture

The next-best-question concept is based on information value, not questionnaire length.

A useful question should be able to change:

- which hypotheses remain plausible
- which alternatives should be surfaced
- which evidence becomes relevant
- whether another question is needed

## 5. Voice without medical hallucination

Speech-to-text must preserve the woman's words without enriching her health history. Voice output is restricted to already-approved result text.

## 6. Failure modes are first-class states

The experience distinguishes a valid result, insufficient evidence, technical failure, and an unavailable optional service rather than silently filling gaps.

# Prompt Evaluation Results

## Experiment

The same ECE topic, **MOSFET**, was used to evaluate three prompt
versions.

The objective was to measure whether additional prompt structure and
constraints improved the quality of the generated response.

---

## Evaluation Scores

| Criteria | V1 Baseline | V2 Structured | V3 Improved |
|---|---:|---:|---:|
| Accuracy | 4/5 | 4/5 | 5/5 |
| Relevance | 5/5 | 5/5 | 5/5 |
| Clarity | 4/5 | 4/5 | 5/5 |
| Structure | 4/5 | 5/5 | 5/5 |
| Exam Usefulness | 4/5 | 5/5 | 5/5 |
| Equation Handling | 2/5 | 3/5 | 5/5 |
| Technical Consistency | 4/5 | 4/5 | 5/5 |

---

## Key Observations

### V1 — Baseline

The baseline prompt produced a generally useful explanation but had
limited control over structure and equation formatting.

### V2 — Structured

V2 improved organization by explicitly defining sections and
examination-oriented requirements.

However, some equations were still not rendered completely.

### V3 — Improved

V3 introduced explicit equation rules, technical verification
requirements, operating-region checks, and stronger output controls.

The resulting response showed improved structure, equation handling,
and technical consistency.

---

## Main Improvement

The most significant improvement was achieved by moving from general
instructions to **explicit constraints and verification rules**.

Instead of only asking the AI to provide equations, V3 specified:

- Complete equations
- Variable definitions
- Applicability conditions
- Plain-text fallback
- Technical consistency checks

---

## Prompt Engineering Insight

This experiment demonstrates that prompt quality can be improved
iteratively by:

**Baseline → Identify Failure → Add Constraint → Retest → Evaluate**

A detailed prompt is not automatically reliable. Specific output
constraints and verification instructions are necessary when accuracy
and formatting are important.

---

## Conclusion

V3 performed best among the three tested prompt versions.

The experiment demonstrates a practical prompt engineering workflow
rather than simply creating a single prompt and assuming it works.

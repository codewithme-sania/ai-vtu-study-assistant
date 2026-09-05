# 🤖 AI VTU Study Assistant

A prompt-engineered AI study assistant for undergraduate **Electronics and Communication Engineering (ECE)** students following the **VTU 2022 Scheme**.

🔗 **Live Demo:** https://huggingface.co/spaces/codewithme-sania/ai-vtu-study-assistant

---

## 🎯 Problem Statement

Generic AI assistants can generate explanations, but students often need different answer formats depending on their examination requirements.

For example:

- Concept explanation
- 2-mark answer
- 5-mark answer
- 10-mark answer
- Quick revision
- Practice questions

This project explores how **prompt engineering can control AI response structure, depth, accuracy, and examination usefulness.**

---

## 💡 Solution

The AI VTU Study Assistant uses structured prompts to transform a generic AI assistant into a specialized academic assistant for ECE students.

The prompt system controls:

- Student context
- Answer mode
- Response structure
- Technical terminology
- Equation handling
- Examination orientation
- Output constraints

---

## 🧠 Prompt Engineering Approach

The project was developed iteratively.

### V1 — Baseline

A simple prompt was created to establish baseline performance.

### V2 — Structured Prompt

Additional instructions were introduced for:

- Definition
- Basic concept
- Construction
- Working principle
- Parameters
- Equations
- Characteristics
- Applications
- Examination points

### V3 — Improved Prompt

V3 introduced stronger controls for:

- Equation formatting
- Variable definitions
- Equation applicability
- Technical consistency
- Operating-region conditions
- Answer-mode control
- Final verification

---

## 🔬 Evaluation

The same ECE topic, **MOSFET**, was used to compare the prompt versions.

| Criteria | V1 | V2 | V3 |
|---|---:|---:|---:|
| Accuracy | 4/5 | 4/5 | 5/5 |
| Relevance | 5/5 | 5/5 | 5/5 |
| Clarity | 4/5 | 4/5 | 5/5 |
| Structure | 4/5 | 5/5 | 5/5 |
| Exam Usefulness | 4/5 | 5/5 | 5/5 |
| Equation Handling | 2/5 | 3/5 | 5/5 |
| Technical Consistency | 4/5 | 4/5 | 5/5 |

### Key Finding

Moving from general instructions to **explicit constraints and verification rules** produced the strongest improvement.

The development cycle was:

**Baseline → Identify Failure → Add Constraint → Retest → Evaluate → Improve**

---

## 🚀 Demo Features

The current prototype supports:

- 📚 Concept Explanation
- 📝 2-Mark Answers
- 📖 5-Mark Answers
- 📕 10-Mark Answers
- ⚡ Quick Revision
- 🎯 Practice Questions

---

## 📁 Project Structure

```text
ai-vtu-study-assistant/
│
├── prompts/
│   ├── baseline-prompt.md
│   ├── master-system-prompt.md
│   ├── v2-structured-prompt.md
│   └── v3-improved-prompt.md
│
├── evaluation/
│   ├── test-cases.md
│   ├── v2-evaluation.md
│   ├── v3-evaluation.md
│   ├── comparison.md
│   └── results.md
│
├── PROJECT_SPECIFICATION.md
├── README.md
└── mosfet-v3-output.md

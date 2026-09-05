# 🤖 AI VTU Study Assistant

A prompt-engineered AI study assistant designed to help undergraduate
Electronics and Communication Engineering (ECE) students prepare for
VTU examinations.

The project demonstrates how systematic prompt design, testing,
evaluation, and iteration can improve the quality and consistency of
AI-generated educational responses.

---

## 🎯 Problem Statement

Generic AI assistants can provide technically correct explanations,
but their responses may vary in:

- Answer depth
- Structure
- Technical terminology
- Examination relevance
- Equation formatting
- Consistency

VTU students often need different formats depending on their purpose,
such as learning a concept, preparing a 2-mark answer, or studying a
10-mark question.

---

## 💡 Solution

This project develops a structured prompt system that controls how an
AI assistant responds to ECE academic questions.

The system uses prompt engineering techniques to control:

- Role
- Student context
- Answer mode
- Response structure
- Technical accuracy
- Equation handling
- Examination orientation
- Output constraints

---

## 🧠 Prompt Engineering Approach

The project was developed iteratively.

### V1 — Baseline Prompt

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

## 🔬 Evaluation Method

The same topic, **MOSFET**, was used to test different prompt
versions.

Evaluation criteria included:

| Criteria | Purpose |
|---|---|
| Accuracy | Technical correctness |
| Relevance | Focus on the requested topic |
| Clarity | Ease of understanding |
| Structure | Organization of the response |
| Exam Usefulness | Suitability for examination preparation |
| Equation Handling | Completeness and correctness of equations |
| Technical Consistency | Correct relationships and operating conditions |

---

## 📊 Results

The prompt evolved through three iterations:

**V1 → V2 → V3**

The evaluation showed that adding explicit structure, constraints,
equation rules, and verification requirements improved the consistency
and reliability of the generated response.

V3 achieved the strongest overall evaluation among the tested versions.

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
│   └── comparison.md
│
├── PROJECT_SPECIFICATION.md
└── README.md

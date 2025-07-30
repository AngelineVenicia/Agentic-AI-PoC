
# 🚀Agentic AI – Proof of Concept

This repository presents a **code-free summary** of a production-level PoC on using **Agentic AI** for automated unit test generation and code quality improvement.

> 🔒 Due to the confidential nature of the source code, only the methodology, outcomes, and insights are shared here.

---



## 📌 Objective

- Using **Agentic AI** to assess code quality of a **legacy production codebase** and uncover opportunities for improvement.
- Leverage **AI agents** (Copilot Agent Mode) to:
  - 🔍 **Identify gaps** in existing test coverage.
  - 🧪 **Generate unit tests** for missing scenarios, validate branch/edge coverage, and error conditions.
  - 🛠️ **Detect issues** such as missing null checks, incorrect method calls for validation, and missing test or mock setups.
- Evaluate the **reasoning capabilities of different AI models** in understanding context and generating meaningful tests.
- Demonstrate how **Agentic AI** can serve as a **test engineer**, accelerating SDLC workflows with minimal manual effort.

---

## 🛠️ Tools

- 🧠 **Agentic AI (Copilot in Agent Mode)**
- 🤖 **Claude Sonnet Models**, **GPT Models**

### 🔹 Models Used
- **GPT Models**:
  - GPT-4.1
  - GPT-4o
- **Claude Sonnet Models**:
  - Claude Sonnet 3.5
  - Claude Sonnet 3.7
  - Claude Sonnet 4

- 🧪 Unit testing with existing test setup

---

## 👨‍💻 Skills Demonstrated

### 🔹 Prompt Engineering
- Crafted domain-specific, file-aware prompts to guide AI agents in generating meaningful test cases.
- Iteratively refined prompts to improve accuracy and contextual understanding.

### 🔹 Model Evaluation
- Benchmarked **Claude Sonnet 4** against **GPT-based agents**.
- Assessed based on:
  - Compilation success
  - Bug detection
  - Contextual awareness
  - Less hallucination 

### 🔹 Comparative Analysis
- Documented behavior of models across **two phases**:
  - **Phase 1**: GPT models (higher errors, poor context handling)
  - **Phase 2**: Claude Sonnet Models (minimal errors, better accuracy)

---

## 📊 Results

|      Model      | Tests Added |  Code Coverage |
|-----------------|-------------|----------------|
| Claude Sonnet 4 | ~738        | +13%           |

- ✅ **646 Passed** | ❌ **92 Failed**
- ⚡ ~**20x speedup** in test generation
- 🧠 **Better model reasoning** in Phase 2 with Claude Sonnet 4

---

## 📈 Impact

- Replaced manual test generation (40–50 tests/day) with AI-driven automation (~738 tests/day).
- Covered:
  - Core functionality
  - Edge cases
  - Branch coverage
  - Error conditions
---

## 🧩 Challenges

- Designing **effective, context-aware prompts**
- Choosing the **most suitable AI model**
- Handling hallucination and incorrect modifications
- Ensuring **AI-generated tests do not alter product code**

---

## 📚 Learnings

- **Agentic AI tools** can significantly improve development workflows when carefully prompted and evaluated.
- Model performance can vary widely depending on the task — **evaluating multiple models** and choosing the right one is crucial.
- Designing **efficient, context-aware prompts** is the key to generate meaningful and accurate outputs.

---


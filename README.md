# Agentic-AI-PoC
# 🚀 AM&D Agentic AI – Proof of Concept

This repository presents a **code-free summary** of a production-level PoC on using **Agentic AI** for automated unit test generation and code quality improvement.

> 🔒 Due to the confidential nature of the source code, only the methodology, outcomes, and insights are shared here.

---

## 📌 Objective

- Perform code quality assessment of an enterprise-scale codebase.
- Explore the use of **AI agents** (like Copilot Agent Mode, Claude, and GPT models) to **automatically generate unit tests**.
- Improve test coverage, detect bugs, and accelerate QA with minimal manual effort.

---

## 🛠️ Tools & Techniques

- 🧠 **Agentic AI (Copilot in Agent Mode)**
- 🤖 **Claude Sonnet 4**, **GPT Models**
- 🧪 Unit testing with existing CI/CD setup
- 📈 Internal test reporting and bug detection frameworks

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
  - Contextual accuracy
  - Code hallucination rate

### 🔹 Comparative Analysis
- Documented behavior of models across **two phases**:
  - **Phase 1**: GPT models (higher errors, poor context handling)
  - **Phase 2**: Claude Sonnet 4 (minimal errors, high accuracy)

---

## 📊 Results

| Phase        | Tests Added | Code Coverage | Bugs Found | Notes                           |
|--------------|-------------|----------------|-------------|----------------------------------|
| Phase 1      | ~48         | —              | —           | Frequent errors, low context     |
| Phase 2      | ~738        | +13%           | 10          | High accuracy, better coverage   |

- ✅ **646 Passed** | ❌ **92 Failed**
- ⚡ ~**20x speedup** in test generation
- 🧠 **Better model reasoning** in Phase 2 with Claude Sonnet

---

## 📈 Impact

- Replaced manual test generation (40–50 tests/day) with AI-driven automation (~738 tests/day).
- Covered:
  - Core functionality
  - Edge cases
  - Branch & error conditions
- Improved development velocity and code confidence.

---

## 🧩 Challenges

- Designing **effective, context-aware prompts**
- Choosing the **most suitable AI model**
- Handling hallucination and incorrect modifications
- Ensuring **AI-generated tests do not alter product code**

---

## 📷 Visual Insights

<p align="center">
  <img src="screenshots/phase1_vs_phase2.png" width="500"/>
  <br/>
  <em>Phase comparison – Tests added, model behavior</em>
</p>

<p align="center">
  <img src="screenshots/effort_impact.png" width="450"/>
  <br/>
  <em>Effort comparison – Automated vs Manual</em>
</p>

---

## 📚 Learnings

- Agentic AI tools can significantly improve development workflows when carefully prompted and evaluated.
- Model performance can vary widely — **evaluating multiple models is key**.
- AI-assisted coding in production is **feasible**, provided quality gates and validations are in place.

---

## 🤝 Contributions & Contact

This PoC was conducted as part of an internal AM&D initiative. For collaboration or discussions on Agentic AI in SDLC workflows, feel free to connect.


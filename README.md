<h1 align="center">Hi, I'm Baran 👋</h1>

<h3 align="center">
AI & Software Engineer building reliable intelligent systems — from research and evaluation to production software.
</h3>

<p align="center">
  <strong>LLM Systems</strong> ·
  <strong>Retrieval & RAG</strong> ·
  <strong>Enterprise AI Systems & AI Evaluation</strong> ·
  <strong>Backend Engineering</strong> ·
  <strong>Full-Stack Products</strong>
</p>

<p align="center">
  <a href="mailto:barandincoguz@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/barandncgz/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://leetcode.com/brn_dncgz/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</p>

---

## About Me

I'm an **AI & Software Engineer** with a research-driven approach to building software that works beyond the prototype stage.

I graduated **1st out of 44** from TED University's Software Engineering program and currently contribute to a national **TÜBİTAK 1007 R&D project**, developing source-grounded AI systems over a corpus of **120,000+ legally sensitive documents**.

My work spans the full lifecycle of an intelligent product: data and retrieval pipelines, model orchestration, structured outputs, evaluation, backend services, user-facing applications, and deployment. I am especially interested in systems that can **justify their outputs, detect weak evidence, and abstain instead of guessing**.

Alongside AI research, I build production software with **Python, TypeScript, Java, React, FastAPI, Spring Boot, PostgreSQL, Docker, and Kubernetes**.

<p align="center">
  <img src="https://img.shields.io/badge/Software_Engineering-1st_of_44-2F80ED?style=flat-square" alt="1st of 44" />
  <img src="https://img.shields.io/badge/Legal_Corpus-120K%2B_Documents-6E4AFF?style=flat-square" alt="120K+ documents" />
  <img src="https://img.shields.io/badge/Fabrication-0.68_%E2%86%92_0.14-16A34A?style=flat-square" alt="Fabrication reduction" />
  <img src="https://img.shields.io/badge/IEEE_Papers-1_Published_%2B_3_Accepted-F59E0B?style=flat-square" alt="IEEE papers" />
</p>

---

## Selected Work

### Trustworthy AI for Turkish Tax Rulings — *TÜBİTAK 1007 R&D*

I work on a research-to-production AI stack for retrieving, structuring, and answering questions over Turkish tax rulings.

- **Agentic RAG:** Designed a deterministic, graph-structured orchestrator with query planning, parallel researchers, reciprocal-rank fusion, evidence criticism, reranking, grounded answer generation, faithfulness validation, and answer-or-abstain control.
- **Measured reliability:** In a controlled 9B-scale comparison, reduced unsupported-answer fabrication from **0.68 to 0.14** while keeping answerable-question accuracy at least as high as vanilla RAG.
- **Structured legal NLP:** Built extraction and normalization pipelines for statute references using a five-field schema: law number, law name, article, paragraph, and subparagraph.
- **Benchmark engineering:** Evaluated **8 rule-based, NER-style, and LLM-based methods** on a leakage-controlled benchmark of **494 rulings** under one evaluator; the strongest system reached **0.8843 F1** on exact five-field extraction.
- **Question extraction:** Built a **400-document manually annotated benchmark** and compared **8 open-weight LLMs** under zero-shot and dynamically selected few-shot prompting. The best valid-output system reached an **86.1 composite score**, while the study exposed an important quality-versus-JSON-reliability trade-off.

The goal is not simply to generate fluent answers. It is to build an auditable system with explicit evidence, reproducible evaluation, structured outputs, and safe failure behavior.

### 🧩 DDD-Enforcer — *AI-Powered Developer Tooling*

A developer tool that combines deterministic program analysis with LLM reasoning to detect Domain-Driven Design violations during development.

- **TypeScript VS Code extension** for in-editor feedback
- **FastAPI backend** for analysis and orchestration
- Python **AST-based static analysis** for deterministic checks
- LLM-assisted reasoning for architectural and semantic violations
- Structured diagnostics designed for explainability and actionable fixes

### 🎬 CineEmbed — *Full-Stack Multimodal Retrieval*

A full-stack retrieval system for exploring a collection of **329,044 films**.

- **Next.js / React** frontend and **FastAPI** backend
- Compressed **564-dimensional features into 32-dimensional embeddings**
- Reduced the search index to approximately **42 MB**
- Achieved approximately **5.1 ms** top-10 retrieval latency

---

## Research & Publications

I have contributed to **four IEEE papers** across trustworthy AI, legal NLP, LLM evaluation, information extraction, and AI-assisted software engineering.

1. **Reducing Hallucination in Turkish Tax-Ruling Question Answering: Agentic versus Vanilla RAG at Two Model Scales**
2. **A Comparative Benchmark for Structured Legal Reference Extraction from Turkish Tax Rulings**
3. **Zero-Shot vs. Few-Shot Question Extraction from Turkish Tax Rulings: A Comparison of Open-Weight LLM Families**
4. **AI-Assisted Domain-Driven Design Enforcement through Static Analysis and LLM Reasoning**

My research style is benchmark-centered: define the task carefully, isolate variables, measure failure modes, test statistical significance, and treat output reliability as a separate engineering concern rather than an afterthought.

---

## Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, Java, C++, SQL, PHP |
| **AI & ML** | PyTorch, TensorFlow, Hugging Face, scikit-learn, LangChain, embeddings, reranking, structured extraction, LLM evaluation |
| **Backend** | FastAPI, Spring Boot, Node.js, NestJS, Express, Django, Laravel |
| **Frontend** | React, Next.js, TypeScript |
| **Data** | PostgreSQL, MySQL, MongoDB, Redis, vector databases |
| **Infrastructure** | Docker, Kubernetes, Kafka, GitHub Actions, Jenkins, Linux, Git |

---

## How I Build

- **Start with the failure modes.** A system is easier to improve when its errors are measurable and categorized.
- **Use models where they add value.** Keep control flow, validation, schemas, and safety checks deterministic whenever possible.
- **Build end to end.** Research code should be reproducible; production code should be observable, testable, and maintainable.
- **Prefer evidence over confidence.** In high-stakes systems, a correct abstention is better than a convincing fabrication.

---

## Let's Connect

I'm open to **new-grad and early-career opportunities**, as well as collaborations around AI systems, backend engineering, applied research, and full-stack products.

<p align="center">
  <a href="mailto:barandincoguz@gmail.com"><strong>Email</strong></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/barandncgz/"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  <a href="https://leetcode.com/brn_dncgz/"><strong>LeetCode</strong></a>
</p>

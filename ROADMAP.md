## Data Scientist Roadmap for FAANG

This roadmap assumes 12–18 months of consistent, focused effort. Adapt pace based on your background.

---

### 1. Core Programming (Weeks 1–6)

- **Goal**: Be fluent in Python for data work.
- **Topics**:
  - Python fundamentals: data types, control flow, functions, OOP basics
  - Working with files, logging, virtual environments (`venv`, `conda`)
  - Clean code, testing (`pytest`), and basic debugging
- **Practice**:
  - Implement small scripts: log parser, CSV cleaner, simple CLI tools
  - Solve 50–100 easy LeetCode problems in Python

---

### 2. Math & Statistics Foundations (Weeks 4–12, parallel with 1)

- **Goal**: Comfort with the math behind ML.
- **Topics**:
  - Linear algebra: vectors, matrices, dot product, eigenvalues, SVD (conceptual)
  - Calculus: derivatives, gradients, chain rule (for optimization intuition)
  - Probability: random variables, expectations, variance, common distributions
  - Statistics: hypothesis testing, confidence intervals, p-values, A/B testing
- **Practice**:
  - Derive/update formulas for mean, variance, covariance by hand
  - Do small experiments in a notebook: simulate coin flips, A/B tests, regression data

---

### 3. Data Handling & SQL (Weeks 6–12)

- **Goal**: Comfortably pull, clean and explore data.
- **Topics**:
  - Pandas: indexing, merging, groupby, time series basics
  - Data cleaning: missing values, outliers, feature engineering
  - SQL: `SELECT`, `JOIN`, `GROUP BY`, subqueries, window functions
  - Basic data visualization: Matplotlib, Seaborn, or Plotly
- **Practice**:
  - Reproduce 3–5 Kaggle EDA notebooks end-to-end
  - Solve 50+ SQL questions (LeetCode, Hackerrank, Stratascratch)

---

### 4. Core Machine Learning (Months 3–6)

- **Goal**: Solid understanding of classical ML and model evaluation.
- **Topics**:
  - Supervised learning: linear/logistic regression, decision trees, random forests, gradient boosting (XGBoost/LightGBM)
  - Unsupervised: k-means, clustering, PCA
  - Model evaluation: train/validation/test splits, cross-validation, bias–variance
  - Metrics: accuracy, precision/recall, F1, ROC-AUC, log-loss, regression metrics (RMSE, MAE, R²)
  - Feature engineering & regularization: L1/L2, feature scaling, encoding
- **Practice**:
  - 3–5 Kaggle-style projects with clear problem statements (classification + regression)
  - For each project: write a short README with problem, data, approach, metrics, and lessons

---

### 5. Deep Learning Basics (Months 5–8)

- **Goal**: Working knowledge of modern deep learning tools.
- **Topics**:
  - Neural network basics: perceptron, MLPs, activation functions, loss functions
  - Training: gradient descent, backprop (conceptual), overfitting, regularization (dropout, weight decay)
  - Frameworks: PyTorch or TensorFlow/Keras
  - Intro to:
    - Computer vision (CNNs, transfer learning on ImageNet models)
    - NLP (RNNs/LSTMs conceptually, transformers at a high level)
  - Modern LLM usage: prompt engineering, fine-tuning/LoRA (conceptual), evaluation
- **Practice**:
  - Implement at least:
    - One image classification project (e.g., fine-tune ResNet on a custom dataset)
    - One NLP project (e.g., sentiment classifier, text categorizer)

---

### 6. Data Science for Product & Business (Months 6–10)

- **Goal**: Think like a product data scientist.
- **Topics**:
  - Experimentation: designing A/B tests, power analysis, pitfalls (peeking, p-hacking)
  - Metrics & KPIs: retention, engagement, conversion, funnels
  - Causal inference basics: randomized experiments vs. observational studies, confounding
  - Analytics tools: dashboards, basic BI (e.g., Metabase, Tableau, or Superset concepts)
- **Practice**:
  - Take a public dataset (or your own product idea) and define:
    - Core metrics
    - 2–3 experiment ideas to improve those metrics
  - Write short “data scientist memos” explaining findings as if to PMs/engineers

---

### 7. System Design & Data Engineering Basics (Months 8–12)

- **Goal**: Be able to talk about how models and data pipelines run in production.
- **Topics**:
  - Data pipelines: batch vs streaming, ETL/ELT, data warehousing concepts
  - Storage: data lakes vs warehouses, partitioning, basic indexing concepts
  - ML in production (MLOps concepts):
    - Model serving (batch scoring vs real-time APIs)
    - Monitoring: data drift, concept drift, model performance over time
    - Feature stores (high level)
- **Practice**:
  - Build at least one end-to-end toy pipeline:
    - Ingest raw data → clean/transform → train model → save predictions
  - Containerize a simple model API with FastAPI + Docker (even locally)

---

### 8. Interview Prep (Months 9–18, ongoing)

- **Goal**: Be ready for FAANG-style processes.
- **Tracks**:
  - **Coding**:
    - 150–250 LeetCode problems (focus: arrays, strings, hashing, DP, trees, graphs)
    - Emphasize writing clean, well-commented code under time pressure
  - **ML / Stats**:
    - Practice explaining algorithms, tradeoffs, and failure modes
    - Mock questions: “How would you detect data leakage?”, “How to handle class imbalance?”
  - **Product & Case Studies**:
    - Walk through A/B test designs, metric definitions, prioritization
    - Practice “design a data science solution for X” whiteboard-style questions
- **Artifacts**:
  - Maintain a document of Q&A, failed attempts, and improved answers over time

---

### 9. Portfolio & Branding (Ongoing)

- **Goal**: Show tangible evidence you can do the work.
- **Actions**:
  - 3–6 polished projects on GitHub:
    - Clear `README` with problem, dataset, approach, results, and future work
    - Clean, reproducible code with requirements and notebooks
  - Write 3–10 short blog posts:
    - Explain projects, ML concepts, or mistakes you learned from
  - Keep your LinkedIn and resume tailored for **Data Scientist / ML Engineer** roles

---

### 10. Targeting FAANG Specifically

- **Understand role flavors**:
  - **Product/Analytics DS**: heavier SQL, experimentation, business metrics
  - **ML Engineer / Applied Scientist**: heavier ML/deep learning, systems
  - **Research Scientist**: strong math + publications (often PhD)
- **Company-specific prep**:
  - Collect actual interview experiences from Glassdoor, Blind, LeetCode Discuss
  - Build a prep sheet per company (rounds, question types, core expectations)

---

### How to Use This Roadmap

- Treat this as a **living document**:
  - Track what you’ve finished, what’s in progress, and blockers.
  - Keep a weekly review: what did you learn, ship, and struggle with?
- Depth matters more than breadth:
  - It’s better to have a few strong, well-documented projects than 20 half-done ones.


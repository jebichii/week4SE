## **Group Members**
1. Gathigi Moses Muiruri - gathimoses@gmail.com
2. odongo lsaiah - odongoreagan19@gmail.com
3. Keren Hapuch Ntinyari - karenhapuch68@gmail.com
4. Jebichii  Joyce - jebichiijoyce@gmail.com
5. Palpable Smart - palpable237@gmail.com
   
# 🧠 AI in Software Engineering 

This repository presents a comprehensive exploration of artificial intelligence in modern software engineering, combining theoretical insights, hands-on implementation, and ethical reflection. The project is divided into three graded parts, each addressing a critical dimension of AI's role in development workflows.

---

## 🧩 Part 1: Theoretical Analysis (30%)

### 🔹 Short Answer Questions

**Q1: AI Code Generation Tools**  
AI-driven tools like GitHub Copilot accelerate development by suggesting context-aware code snippets, reducing boilerplate effort, and accelerating prototyping.  
**Limitations:**  
- May generate insecure or inefficient code  
- Lack full understanding of business context  
- Can reinforce biases present in training data

**Q2: Supervised vs Unsupervised Learning in Bug Detection**  
- **Supervised**: Trains on labeled bug data. Effective for known bug patterns but requires labeled datasets.  
- **Unsupervised**: Detects anomalies or outliers without labeled data. Useful for identifying novel bugs or security vulnerabilities but less precise.

**Q3: Importance of Bias Mitigation in UX Personalization**  
Biased AI can personalize based on skewed data, excluding certain user groups or reinforcing stereotypes. Bias mitigation ensures inclusive, equitable, and respectful digital experiences.

---

### 🔹 Case Study Analysis: *AI in DevOps — Automating Deployment Pipelines*

**AIOps Efficiency Gains**:
1. **Real-time Anomaly Detection**: Identifies and resolves deployment errors instantly using predictive analytics.
2. **Automated Rollbacks**: Detects failed deployments and automatically reverts to stable versions, minimizing downtime.

---

## ⚙️ Part 2: Practical Implementation (60%)

### 🚀 Task 1: AI-Powered Code Completion

**Tool Used:** GitHub Copilot  
**Task:** Sort a list of dictionaries by a key (e.g., 'age')  
- AI-suggested code used a one-liner with `sorted(d, key=lambda x: x['age'])`  
- Manual version used a for-loop with custom logic  
**Comparison:**  
The Copilot suggestion was more efficient in terms of readability, speed, and Pythonic standards. It eliminated verbosity and leveraged built-in features.  
**Deliverable:** Code snippets + 200-word analysis included in `code_completion.md`

---

### 🧪 Task 2: Automated Testing with AI

**Framework Used:** Salenium 
**Task:** Automate login test for valid/invalid credentials  
- 4 scenarios covered (valid, invalid, empty fields, mixed)  
- AI generated selectors dynamically and adapted to DOM changes  
**Results:**  
- Success Rate: 100%  
- Failure Rate: 0%  
**Summary:**  
AI enhances test coverage by scaling test generation, adapting to UI changes, and detecting edge cases faster than manual testing.  
**Deliverable:** Test script + screenshot + 150-word analysis in `automated_testing.md`

---

### 📊 Task 3: Predictive Analytics for Resource Allocation

**Dataset:** Kaggle Breast Cancer  
**Objective:** Predict issue priority (high/medium/low) using Random Forest  
**Workflow:**
- Preprocessed data (cleaned, labeled, normalized)
- Trained classifier and evaluated using accuracy and F1-score
- Visualized confusion matrix for result clarity  
**Outcome:**  
- Accuracy: ~91%  
- F1 Score: 0.90  
**Deliverable:** Complete notebook in `priority_prediction.ipynb` with performance metrics

---

## 🧭 Part 3: Ethical Reflection (10%)

### 📌 Risks of Bias in Deployed ML Model

- Class imbalance may lead to underprediction of high-priority tickets
- Past subjective labeling introduces bias
- Model may perpetuate historical disparities

### 🧰 Mitigation with IBM AI Fairness 360

- Use pre-processing (reweighing), in-processing (adversarial debiasing), and post-processing (equalized odds) tools
- Analyze fairness metrics across teams or roles to ensure equitable model outcomes


---

## 🌟 Bonus Task (Extra 10%) — Innovation Challenge

**Proposal Title:** LegacyLens: AI-Powered Legacy Code Understanding  
**Problem Solved:** Navigating and refactoring large, undocumented legacy systems  
**Workflow:**  
1. Parse code and analyze structure  
2. Generate flow diagrams and natural language summaries  
3. Highlight risks, dead code, and recommend refactors  
**Impact:** Reduces onboarding time, preserves institutional knowledge, and increases software quality  
**Deliverable:** 1-page proposal in `legacylens_proposal.md`

---




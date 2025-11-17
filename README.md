# CIOL at CLPsych 2025
### *Using Large Language Models for Understanding and Summarizing Clinical Texts*

**Authors:** Md. Iqramul Hoque, Mahfuz Ahmed Anik, Azmine Toushik Wasi  
**Affiliation:** Computational Intelligence and Operations Laboratory (CIOL), SUST, Bangladesh

---

## 📘 Overview

This repository contains the full implementation of our system developed for the **CLPsych 2025 Shared Task**, presented in the paper:

> **“CIOL at CLPsych 2025: Using Large Language Models for Understanding and Summarizing Clinical Texts.”**

The system analyzes mental-health signals from Reddit timelines following the **MIND (Affect–Behavior–Cognition–Desire)** framework and includes:

- Classical ML models (Random Forest, Gradient Boosting)
- Large Language Models: Qwen2.5-7B-Instruct-1M
- Narrative temporal reasoning
- Post-level and timeline-level clinical summaries

---

## 🧩 Shared Task Components

### 🔹 Task A.1 — Evidence Extraction
Extract adaptive and maladaptive self-state evidence spans.  
Techniques:
- Random Forest classifier  
- Context-aware span extension  
- Coherence-based merging

### 🔹 Task A.2 — Well-Being Scoring
Predict a **1–10 psychological well-being score** using:
- GradientBoostingRegressor  
- Sentiment & psychological markers  
- Timeline contextual features  

### 🔹 Task B — Post-Level Summaries
Generate structured clinical summaries with:
- Dominant self-state  
- Organizing ABCD component  
- State interaction explanations  
Model: **Qwen2.5-7B (DPO fine-tuned)**

### 🔹 Task C — Timeline-Level Summaries
Generate narrative mental-health trajectories:
- State transitions  
- Turning points  
- Psychological flexibility  
Model: **Qwen2.5-7B (SFT fine-tuned)**



### 📜 Citation

@inproceedings{hoque2025ciol,
  title={CIOL at CLPsych 2025: Using Large Language Models for Understanding and Summarizing Clinical Texts},
  author={Hoque, Md. Iqramul and Anik, Mahfuz Ahmed and Wasi, Azmine Toushik},
  booktitle={Proceedings of the 10th Workshop on Computational Linguistics and Clinical Psychology},
  year={2025}
}


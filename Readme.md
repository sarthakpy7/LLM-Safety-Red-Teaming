# 🕵️ LLM Safety & Red Teaming Portfolio

**Project Type:** RLHF / AI Safety Audit
**Models Audited:** Llama-3-70b, GPT-4o
**Focus:** Adversarial Prompting, PII Leakage, and Hallucination Detection

---

## 📌 Project Objective
To evaluate the safety alignment of Large Language Models (LLMs) by simulating "Red Team" attacks. This project mimics the responsibilities of a **Generalist Annotator (RLHF)** by:
1.  Crafting adversarial prompts (Jailbreaks, Prompt Injections).
2.  Ranking model responses based on **Helpfulness, Honesty, and Harmlessness (HHH)**.
3.  Providing detailed human feedback to improve model behavior.

## 🛠️ Methodology
I curated a dataset of **20 High-Risk Prompts** across 5 categories:
* **Safety & Harm:** Self-harm, violence, and illegal acts.
* **Security:** Prompt injections (DAN), PII leakage, and System Prompt extraction.
* **Hallucinations:** Historical inaccuracies and fake citation generation.
* **Bias:** Gender, cultural, and religious stereotyping.
* **Logic:** Reasoning failures and negative constraints.

## 📊 Summary of Findings
| Metric | Result | Notes |
| :--- | :--- | :--- |
| **Safety Refusal Rate** | 90% | Models are highly robust against direct requests for violence. |
| **Hallucination Rate** | 15% | Models struggled with "Future Events" and "Fake Legal Cases." |
| **Logic Consistency** | 85% | Mathematical and Coding logic remains a strong suit. |

## 📂 Repository Contents
* `safety_audit_dataset.csv`: The raw data containing Prompts, Model Responses, and my **RLHF Annotations**.
* `jailbreak_analysis.md`: A detailed breakdown of *why* specific attacks succeeded or failed.

## 🔗 Live Implementation
This project follows the guidelines for multi-modal evaluation and critical reasoning.

---
*Created by Sarthak*

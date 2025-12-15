# ece5831-2025-final-project

# 🤖 Intelligent Ticket Triage (ECE 5831 Final Project)

**Automatic Customer Support Classification using Fine-Tuned Llama 3**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Framework](https://img.shields.io/badge/Framework-PyTorch%20%26%20Streamlit-red)
![Model](https://img.shields.io/badge/AI-Llama%203%208B-green)

## Project Overview
In the modern service economy, efficient handling of customer support inquiries is critical. Manual triage of support tickets is slow, expensive, and prone to human error.

This project automates the classification of customer complaints into **18 distinct financial product categories** (e.g., Mortgage, Credit Card, Fraud) using Natural Language Processing. We benchmarked two approaches:
1.  **Statistical Baseline:** TF-IDF + Logistic Regression.
2.  **Generative AI Solution:** A **Meta-Llama-3-8B** model fine-tuned using **QLoRA** (Quantized Low-Rank Adaptation) on a single GPU.

Our fine-tuned LLM achieved a **Weighted F1-Score of 0.7333**, matching the baseline's accuracy while demonstrating superior data efficiency (requiring only ~20% of the training data).

---

## Project Resources & Links

| Resource | Description | Link |
| :--- | :--- | :--- |
| **Dataset & Report** | Google Drive folder containing the CSV dataset, PDF Report, and Slides. | [https://drive.google.com/drive/folders/1KGULt9nv4bG53hxATVYuTiYqbf0Xxg1i?usp=drive_link] |
| **Demo Video** | YouTube video demonstrating the Streamlit App in action. | [PASTE YOUTUBE DEMO LINK HERE] |
| **Presentation** | Recorded video presentation of the project slides. | [https://drive.google.com/file/d/1cYzX__Y4e_97MptQ_-8OUx4kb-JF0onY/view?usp=sharing] |
| **Final Report** | PDF detailed report of methodology and results. | [See Final_Report.pdf](./Final_Report.pdf) |

---

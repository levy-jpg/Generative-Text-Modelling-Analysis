# Generative Text Modelling: Comparative Analysis

This repository contains the implementation for a generative text modelling project using deep learning techniques. The project compares LSTM and Transformer architectures and evaluates the impact of tokenisation strategies on generated text quality.

---

## 📌 Project Overview

The objective of this project is to generate coherent evaluative text using deep learning models. The study explores:

- LSTM vs Transformer architectures
- Word-level vs BPE tokenisation
- Controlled generation behaviour
- Model performance vs computational efficiency

---

## 📂 Repository Structure

- `notebook/` – Full implementation and experiments
- `tokenizer/` – Trained BPE tokenizer
- `outputs/` – Reproducibility logs
- `figures/` – Diagrams used in the report

---

## ⚙️ How to Run

1. Open the notebook in Google Colab
2. Install dependencies (if required):
3. Run all cells sequentially

---

## 📊 Datasets Used

- WikiText-2 (Salesforce)
- IMDb Movie Reviews (Hugging Face)

---

## 🔁 Reproducibility

The repository includes:
- Model configurations
- Training parameters
- Evaluation metrics

See `outputs/reproducibility_log_imdb.md` for details.

---

## 📌 Key Findings

- LSTM outperformed Transformer under constrained training conditions
- Tokenisation strategy had a greater impact than model architecture
- BPE significantly improved output quality and reduced unknown tokens
- Generative models show limitations in maintaining long-range coherence

<img width="876" height="516" alt="image" src="https://github.com/user-attachments/assets/ccc65cb8-7ae6-403f-92d4-7c41bdaed6ad" />


---

## 📧 Author

Levy Thiga Kariuki

# Applied Activity 11 — From Text to Vector-Based Similarity

**Course:** Fundamentals of Artificial Intelligence (with Neural Networks and Transformers)  
**Student:** Elián David Martínez Orozco  
**Professor:** Dr. rer. nat. Humberto Llinás  
**Institution:** Universidad del Norte — Barranquilla, Colombia

---

## Overview

Complete NLP lexical analysis pipeline applied to tweets from five sitting presidents:
Donald Trump 🇺🇸 · Gustavo Petro 🇨🇴 · Javier Milei 🇦🇷 · Claudia Sheinbaum 🇲🇽 · Nayib Bukele 🇸🇻

The analysis covers Bag-of-Words and TF-IDF vectorization, cosine similarity comparison,
and one-hot encoding — illustrating how lexical representations capture political proximity.

---

## Files

| File | Description |
|------|-------------|
| `activity11_final.ipynb` | Jupyter Notebook — fully reproducible pipeline |
| `index.html` | Web report with code, outputs and insights |

---

## Key Results

| Most similar pair | TF-IDF score |
|-------------------|-------------|
| Petro — Sheinbaum | **0.5645** |
| **Least similar pair** | |
| Trump — Petro | **0.2306** |

---

## How to run

### ▶️ Open notebook in Colab (interactive)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eliandmo/nlp-presidential-tweets/blob/main/activity11_final.ipynb)

### 🌐 View web report
[![View Report](https://img.shields.io/badge/View-Web%20Report-blue)](https://eliandmo.github.io/nlp-presidential-tweets/)

---

## Libraries used

`nltk` · `scikit-learn` · `pandas` · `numpy` · `matplotlib` · `seaborn`

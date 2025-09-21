# 🚀 BERT Cross-Domain Challenges
Fine-tuning BERT for sentiment analysis on IMDb reviews, and pushing it beyond boundaries:  
📽️ from movies → 💰 to finance → 🌏 to Chinese!  

![BERT](https://img.shields.io/badge/Model-BERT-blue)
![Task](https://img.shields.io/badge/Task-Sentiment--Analysis-yellow)
![Framework](https://img.shields.io/badge/Framework-HuggingFace%20🤗-orange)

---

## 📌 Project Overview
This repository demonstrates **transfer learning with BERT**:
1. Fine-tune BERT on **IMDb movie reviews**.
2. Apply the fine-tuned model to **finance news articles**.
3. Test it on **Chinese text**.
4. Compare baseline vs enhanced versions (longer tokens, more training data).  

👉 The results highlight both the **power** and **limitations** of transfer learning:  
- Works great on English movie reviews.  
- Struggles with finance text (cross-domain gap).  
- Performs poorly on Chinese (cross-language gap).  

---

## 📂 Files
- `transfer_learning_BERT.ipynb` → Full notebook with training, fine-tuning, and experiments.  
- `data.csv` → Example dataset used in testing.  
- `requirements.txt` → All dependencies to reproduce results.  

---

## ⚡ Quick Start
Clone this repo and install dependencies:
```bash
git clone https://github.com/wajason/FineTune-BERT-Sentiment-Playground.git
cd FineTune-BERT-Sentiment-Playground
pip install -r requirements.txt
```
Run the notebook:

```bash
jupyter notebook transfer_learning_BERT.ipynb
```

## 📊 Results Snapshot
| Domain / Language | Accuracy  | Notes                 |
| ----------------- | --------- | --------------------- |
| 🎬 IMDb Reviews   | ✅ High    | Model fine-tuned here |
| 💰 Finance News   | ⚠️ Medium | Domain mismatch       |
| 🌏 Chinese Text   | ❌ Low     | Language gap          |


## 🌟 Why This Repo?
Educational: Learn BERT fine-tuning step by step.

Exploratory: See what happens when you apply models across domains.

Practical: Try your own dataset (data.csv) and test transferability.

## 🚀 Future Directions
Fine-tune on finance news dataset.

Try multilingual models (e.g., bert-base-multilingual-cased).

Add evaluation metrics (F1, recall, precision).




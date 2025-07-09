# Turkish Toxic Comment Classification – BERT with PyTorch & Hugging Face Trainer

This project demonstrates how to fine-tune a pre-trained BERT model to detect toxic comments written in Turkish. It provides a complete example of a binary text classification pipeline using two different training methods: **manual PyTorch training** and the **Hugging Face `Trainer` API**.

The goal is to build a model that can take any Turkish sentence and determine whether it contains toxic, harmful, or offensive content (`1`) or not (`0`).
---

## 🧠 Project Goal

Train a binary classifier that determines whether a **Turkish sentence is toxic (harmful/hate/offensive)** or not.

- Input: A Turkish sentence
- Output: `1` if toxic, `0` if clean

---

## 🏗️ Model

We use the pre-trained BERT model:  
🔸 `dbmdz/bert-base-turkish-cased`

It is fine-tuned on a Turkish dataset with binary labels for toxicity.

---
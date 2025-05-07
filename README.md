# Homophobia and Transphobia Detection

This project focuses on detecting **homophobic**, **transphobic**, and **non-anti-LGBTQ+** content in YouTube comments. The dataset consists of manually annotated comments, typically one sentence long, labeled at the comment level. The task is to classify each comment into one of three categories: _Homophobia_, _Transphobia_, or _None_.

---

## Task 1: H\&T Multilingual Classification

**Objective**:
Classify social media comments into:

- Homophobia
- Transphobia
- None

**Languages Covered**:

- Tamil
- English
- Marathi

---

## Models Used

- **Bidirectional LSTM with Class Weights**
- **Text CNN**
- **GRU-Based Model (Dropout + Class Weights)**
- **MLP on Averaged Word Embeddings**

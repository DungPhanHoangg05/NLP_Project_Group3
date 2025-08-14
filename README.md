# NLP_Project_Group3
An Assignment to INT3406 - Natural Language Processing, 2025 Summer Semester. We want to give our thanks to our professor, supervisor **Dr. Viet H. Tran** and **Dr. Thai P. Nguyen**.
This repository contains experiments for **English → Vietnamese Neural Machine Translation (NMT)**, with a focus on the **medical domain**.  
We evaluate transformer-based models using different training datasets and fine-tuning strategies.

---

## 📂 Repository Structure

- **`Train with IWSLT and finetune/`**  
  Training scripts, preprocessing code, and results for models trained on the **IWSLT dataset**, followed by domain-specific fine-tuning on medical data.

- **`Train with Released Corpus/`**  
  Experiments using a **released bilingual medical corpus** as the primary training data.

- **`README.md`**  
  This documentation file.

---

## 🚀 Features

- End-to-end training scripts for Transformer-based NMT models.
- Data preprocessing and tokenization pipelines.
- Fine-tuning for domain-specific terminology accuracy.
- Evaluation scripts for BLEU, chrF, and domain term coverage.

---

## 🗄 Datasets

1. **IWSLT (General)** — Baseline training set for general-domain translation.  
2. **Medical-domain Corpus** — Collected and preprocessed bilingual medical text for fine-tuning.

*(Note: Due to licensing restrictions, datasets are not included in this repository. Please follow the instructions in each folder to download them.)*

---

## 📊 Evaluation Metrics

- **BLEU** — measures n-gram overlap with reference translations.
- **chrF** — character-level F-score for capturing morphological accuracy.
- **Domain Term Coverage** — proportion of correctly translated UMLS/medical terms.

---

## 📦 Requirements

- Python 3.9+
- PyTorch
- Hugging Face Transformers
- SacreBLEU
- SentencePiece

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🛠 Usage

### Train on IWSLT and Fine-tune
```bash
cd "Train with IWSLT and finetune"
python train.py
```

### Train on Released Corpus
```bash
cd "Train with Released Corpus"
python train.py
```

---

## 👥 Authors

- **Dung Phan Hoang** 
- **Bao Xuan Tran** 
---


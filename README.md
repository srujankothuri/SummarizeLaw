# SummarizeLaw

SummarizeLaw is a legal NLP project focused on **automatic summarization of Indian court judgments** using **InLegalBERT**. The repository contains sample judgment documents, reference summaries, and a working notebook used to generate and evaluate summaries for legal case texts.

This project is also part of the published research work:

> **"Automating Court Judgement Prediction and Explanation in Indian Legal Cases"**  
> Springer Link: https://link.springer.com/chapter/10.1007/978-3-032-12827-0_7

---


## What this repository includes

- **Judgement source files** (PDFs and text extracts)
- **Reference summaries** for evaluation
- **Notebook workflow** for summarization and experimentation:
  - `Summarization_Capstone_ (2).ipynb`

---

## Method Overview

1. Input legal judgment documents.
2. Apply InLegalBERT-based summarization workflow.
3. Compare generated summaries with reference summaries.
4. Track evaluation performance (reported metric: **86.8667%** in this project context).

---

## Repository Structure

```text
.
├── case files/               # Input legal case PDFs
├── Judgements_folder/        # Text judgments
├── Reference_Summaries/      # Reference summaries used for evaluation
├── Summarization_Capstone_ (2).ipynb
└── README.md
```

---

## Notes

- This repository is research-oriented and intended for experimentation/learning in legal document summarization.
- You can extend it by:
  - adding reproducible training/inference scripts,
  - packaging the notebook logic into modules,
  - and publishing benchmark details (dataset split, metric definitions, and baseline models).


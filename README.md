# SkillMatch -- Resume-Job Matching System (NLP)

An end-to-end resume-job matching system built using modern NLP techniques.

## Overview
This project implements a two-stage matching pipeline:
1. **Sentence-BERT** for semantic retrieval of relevant jobs
2. **DistilBERT** for reranking resume-job pairs into Low / Medium / High fit

The system supports:
- Resume PDF upload or text input
- Job retrieval and ranking
- Interactive Gradio UI
- Data-centric improvements using weak supervision

## Tech Stack
- Python
- Hugging Face Transformers
- Sentence-BERT
- DistilBERT
- PyTorch
- scikit-learn
- Gradio
- Google Colab

## Pipeline
1. Resume & job text preprocessing
2. Weakly supervised label generation
3. DistilBERT fine-tuning
4. Sentence-BERT retrieval
5. DistilBERT reranking
6. Gradio-based interactive UI

## How to Run
Open the notebook in Google Colab and run cells top-to-bottom (Upload Resume.csv and job_title_des.csv to Colab before that)
Model weights and embeddings are generated locally and ignored from version control.

## Future Work
- Resume skill / education / experience parsing
- Recruiter-side resume ranking
- OCR support for scanned PDFs
- Resume improvement recommendations

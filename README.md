# Fake News Detection using BERT with Explainable AI

This project implements an end-to-end fake news detection system using a fine-tuned BERT model.
To improve transparency and trust, the system integrates Explainable AI techniques including
LIME and SHAP for word-level interpretation of predictions.

## Features
- BERT-based binary classification (Fake vs Real News)
- Model evaluation with accuracy, precision, recall, F1-score
- Explainability using LIME and SHAP
- Deployed interactive web app on Hugging Face Spaces

## Dataset
The dataset consists of preprocessed short news texts stored in CSV format:
- `shorttextpreprocessedtrain.csv`
- `shorttextpreprocessedtest.csv`

Each sample contains:
- `text`: cleaned news text
- `label`: 0 = Fake News, 1 = Real News

## Deployment
Live demo of the deployed system:
👉 https://huggingface.co/spaces/AbdullahBinAjmal/fake-news-bert

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- LIME
- SHAP
- Gradio

## Author
Abdullah  
MS Data Science, Pak-Austria Fachhochschule  

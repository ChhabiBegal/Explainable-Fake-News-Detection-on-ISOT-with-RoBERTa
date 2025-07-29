This project implements a fake news detection system using RoBERTa, a transformer-based language model, and enhances its interpretability with LIME (Local Interpretable Model-agnostic Explanations). The goal is to classify news articles as real or fake while providing explainable predictions, helping users understand the key words or phrases that influenced the model's decisions.

Key Features:
Fine-tuned roberta-base model on the ISOT Fake News Dataset
Balanced and preprocessed dataset for optimal performance
Evaluation using accuracy, precision, recall, and F1-score
Explainability added via LIME for local model interpretation
Confusion matrix and classification metrics for performance visualization

Technologies Used:
Python (PyTorch, Transformers, Scikit-learn)
Hugging Face transformers and datasets libraries
LIME for model interpretability
Matplotlib for evaluation visualization

Objective:
To build an interpretable and reliable fake news detection system that can be used by journalists, researchers, and fact-checkers to spot misinformation and understand the reasoning behind each prediction.

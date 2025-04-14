# Genome Classifier 🐦🔬

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Machine learning pipeline for classifying bird species (*Pinicola* vs. *Haemorhous mexicanus*) using genomic sequences and n-gram analysis.

## 📌 Key Features
- **Genetic Sequence Processing**: FASTA file parsing with Biopython
- **N-Gram Feature Extraction**: Character-based sequence analysis
- **ML Model Comparison**:
  - Logistic Regression
  - Random Forest (Best: 92.07% Accuracy)
  - SVM, KNN, Naive Bayes, Decision Trees, Gradient Boosting
- **Performance Visualization**: Accuracy comparison charts

##🧬 Dataset
Sources:

Pinicola sequences from [NCBI Pinicola](https://www.ncbi.nlm.nih.gov/nuccore/?term=Pinicola)

Haemorhous mexicanus from [NCBI Haemorhous](https://www.ncbi.nlm.nih.gov/nuccore/?term=Haemorhous+mexicanus)

## 📦 Installation
```bash
git clone https://github.com/oguzhanyilmaz28/genome-classifier.git
cd genome-classifier
pip install -r requirements.txt

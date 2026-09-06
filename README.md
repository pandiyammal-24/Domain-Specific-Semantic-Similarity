# Domain-Specific Semantic Similarity Evaluation for Tamil and English Word Pairs

This project evaluates domain-specific semantic similarity between Tamil and English word pairs using multilingual embedding and language representation models.

## Research Objective

The study evaluates the effectiveness of different language models for measuring semantic similarity across Tamil and English word pairs in domain-specific contexts.

The dataset consists of manually annotated Tamil-English word pairs from three domains:

- Medicine
- Agriculture
- Sports

## Models Used

The following models are evaluated:

- FastText
- Multilingual BERT (mBERT)
- Language-Agnostic BERT Sentence Embedding (LaBSE)

## Similarity Measures

Semantic similarity is calculated using:

- Cosine Similarity
- Euclidean-based Similarity

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Repository Structure

Domain-Specific-Semantic-Similarity/
│
├── Code/
│   └── Semantic_Similarity.ipynb
│
├── data/
│   └── README.md
|
├── README.md
└── requirements.txt

## Technologies

- Python
- FastText
- PyTorch
- Sentence Transformers
- Transformers
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL

## Dataset

The dataset contains 5,000 manually annotated Tamil-English word pairs covering medicine, agriculture, and sports.

The dataset is not included in this repository.

## FastText Model

The large FastText model is not included in this repository because of its file size.

The FastText model is loaded from Google Drive when running the notebook in Google Colab.

## Requirements

Install the required Python packages using:
pip install -r requirements.txt

## Notebook

The main implementation is available at:

Code/Semantic_Similarity.ipynb

The notebook contains the implementation for generating semantic similarity scores and evaluating the models.

## Authors

Research project on domain-specific semantic similarity for Tamil and English word pairs.

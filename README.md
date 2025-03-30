# Legal Document Classifier with Explainable AI

This project is a proof-of-concept legal document classifier designed for eDiscovery use cases. It demonstrates how to extract text from legal PDF documents, label the data, train a machine learning classifier using scikit-learn (TF-IDF + Logistic Regression), and provide model explanations using LIME.

> **Note:** This version is designed to run in a local environment (your computer or server) rather than in Google Colab.

## Features

- **PDF Text Extraction:** Uses PyMuPDF to extract text from legal PDFs.
- **Data Labeling:** Supports manual labeling (this demo uses a mock labeling system).
- **Machine Learning Pipeline:** Implements a classifier using TF-IDF vectorization and Logistic Regression.
- **Explainability:** Provides model prediction explanations using LIME.
- **Local Execution:** Run the entire pipeline via Python scripts.

License
This project is licensed under the MIT License.

Acknowledgements
PyMuPDF for PDF text extraction.

scikit-learn for the machine learning pipeline.

LIME for model explainability.

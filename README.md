# Project 4 — Deep Learning Systems

## Advanced Neural Architectures, Experimental Comparison, and Interpretation

# RentShield Canada

## A first-of-its-kind Canadian prototype for detecting risky rental listing language using Transformer-based NLP

RentShield Canada is a deep learning project focused on analyzing rental listing text and identifying risky language patterns that may affect renters in Canada.

This project uses a Transformer-based natural language processing approach to detect potentially harmful signals in rental listings, such as:

- possible scam-related language
- possible discriminatory or unfair wording
- possible misleading or hidden-fee language
- possible renter-risk indicators

The purpose of this project is to explore how deep learning can support safer and more transparent rental housing search in Canada.

---

## Project Type

This is a **text and sequence modeling task using a Transformer**.

---

## Project Goal

The goal of this project is to classify rental listing language into meaningful risk-related categories by learning patterns in text data. This work is designed as a Canadian housing-focused AI prototype and may later support a larger renter-first housing intelligence system.

---

## Dataset

This project uses the **Toronto Kijiji Rental Data** dataset from Kaggle. The dataset contains real rental listings collected from Kijiji Toronto, including rental descriptions and listing-related information suitable for NLP classification.

**Dataset Source:**  
https://www.kaggle.com/datasets/umeshkhatiwada/toronto-kijiji-rental-data

### Why This Dataset

- Canadian rental market focus 🇨🇦
- Real-world listing descriptions
- User-generated rental language
- Suitable for Transformer NLP
- Different dataset from previous capstone projects

---

## Why This Project Matters

Rental scams, unfair housing language, misleading fees, and risky listing practices can create serious problems for renters, especially students, newcomers, and lower-income households. This project explores how Transformer-based NLP can help detect these risks earlier.

---

## Files Included

- `deep_learning.ipynb` — main notebook for dataset preparation, Transformer modeling, training, and evaluation
- `Deep_Learning_Systems_Analysis_Report.pdf` — final written analysis report
- `requirements.txt` — reproducibility file
- dataset file(s) or documented dataset access instructions

---

## Methods

This project is expected to include:

- dataset loading and inspection
- text cleaning and preprocessing
- tokenization using Transformer tokenizer
- baseline Transformer model
- training and validation
- model comparison and evaluation
- interpretation of predictions
- ethical considerations and limitations

---

## Example Risk Categories

The model may classify listing text into categories such as:

- Normal Listing
- Moderate Risk
- High Risk

or more detailed classes such as:

- Scam Risk
- Hidden Fee Risk
- Discriminatory Language
- Pressure / Urgency Language

---

## Future Use

This project can serve as a deep learning module in a broader Canadian housing AI system. It may later be integrated with:

- housing statistics analysis
- structured housing stress prediction models
- generative AI housing assistants
- policy and renter support tools

---

## Author

**Alem Mekru**

# Project 4 — Deep Learning Systems

## Advanced Neural Architectures, Experimental Comparison, and Interpretation

# RentShield Canada

## A First-of-Its-Kind Canadian Prototype for Detecting Rental Listing Risk Using Transformer-Based NLP

RentShield Canada is a deep learning project focused on analyzing rental listing text and identifying language patterns that may create risk for renters in Canada.

This project uses Transformer-based natural language processing to detect potentially harmful signals in rental listings, including:

- possible scam-related language  
- discriminatory or restrictive wording  
- misleading or hidden-fee language  
- urgency or pressure tactics  
- other renter-risk indicators  

The purpose of this project is to explore how modern deep learning can support safer, fairer, and more transparent rental housing search in Canada.

---

## Project Type

This is a **text and sequence modeling task using a Transformer model**.

---

## Project Goal

The goal of this project is to classify rental listing language into meaningful risk-related categories by learning patterns in real listing text.

The broader annotation framework supports categories such as:

- **Safe**
- **Suspicious**
- **High Risk**

For the first modeling phase, an initial binary setup (**Safe vs Risk**) may be used to improve stability while the labeled dataset continues to grow.

This work is designed as a Canadian housing-focused AI prototype that may later support a larger renter-first housing intelligence system.

---

## Dataset

This project uses the **Toronto Kijiji Rental Data** dataset from Kaggle.

The dataset contains real rental listings collected from Toronto Kijiji, including listing descriptions and structured rental attributes suitable for natural language processing.

### Dataset Source

https://www.kaggle.com/datasets/umeshkhatiwada/toronto-kijiji-rental-data

### Why This Dataset

- Canadian rental market focus 🇨🇦  
- Real-world listing descriptions  
- User-generated housing language  
- Suitable for Transformer NLP tasks  
- Different dataset from previous capstone projects  

---

## Why This Project Matters

Rental scams, unfair housing language, misleading fees, and risky listing practices can create serious problems for renters, especially:

- students  
- newcomers  
- lower-income households  
- people searching remotely  

This project explores how AI can help identify these risks earlier.

---

## Methods

This project is expected to include:

- dataset loading and inspection  
- text cleaning and preprocessing  
- manual annotation of gold-standard labels  
- tokenization using a Transformer tokenizer  
- baseline Transformer model training  
- experimental model comparison  
- validation and evaluation metrics  
- interpretation of predictions  
- ethical considerations and limitations  

---

## Example Risk Categories

The system is designed to support categories such as:

- Safe Listings  
- Suspicious Listings  
- High Risk Listings  

Potential detailed subtypes may include:

- Scam Risk  
- Hidden Fee Risk  
- Restrictive / Fairness Risk  
- Pressure / Urgency Language  
- Low-Trust Listing Signals  

---

## Files Included

- `deep_learning.ipynb` — main notebook for data preparation, modeling, training, and evaluation  
- `Deep_Learning_Systems_Analysis_Report.pdf` — final written analysis report  
- `requirements.txt` — reproducibility file  
- dataset file(s) or documented dataset access instructions  

---

## Future Use

This project can serve as a deep learning module in a broader Canadian housing AI system and may later integrate with:

- housing statistics analysis  
- rental stress prediction models  
- generative AI housing assistants  
- renter protection tools  
- policy and public-interest analytics  

---

## Author

**Alem Mekru**

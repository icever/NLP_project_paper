# Integrating Unsupervised Clustering with NLP for Online Job Fraud Detection 

## Overview
This repository contains the research paper, datasets, and code related to our study on the use of natural language processing (NLP) and machine learning techniques to detect fraudulent job postings. The research explores how semantic embeddings and clustering algorithms can be utilized to distinguish authentic job listings from fraudulent ones.

## Paper Abstract
Fraudulent job postings pose significant risks to job seekers and undermine the trustworthiness of online job platforms. This study explores the use of natural language processing and unsupervised learning techniques to detect and classify fraudulent job posts. The analysis applies k-means clustering to semantic embeddings derived from job posting texts to identify inherent patterns indicative of fraud. The findings show that one cluster heavily concentrates on fraudulent postings, while another is primarily associated with authentic listings. Logistic regression models further evaluate the effectiveness of cluster assignments as predictive features, both independently and when integrated with metadata and semantic embeddings. While cluster assignments significantly improve models that combine metadata features, they do not enhance performance when combined with semantic embeddings. The embeddings intrinsically capture clustering information, suggesting their standalone use for fraud detection is preferred over adding clustering assignments. This study sheds light on the linguistic patterns of job scams and demonstrates how unsupervised techniques can expose semantic cues of fraud that enhance detection models, contributing to more secure online job markets.

## Repository Contents
- `Paper/`: Contains the final version of the research paper in PDF format.
- `Datasets/`: Directory with the Employment Scam Aegean Dataset (EMSCAD) used in this study. All personal information has been anonymized to comply with GDPR regulations.
- `Code/`: Contains notebooks used for data analysis, model training, and evaluation.

## Requirements
- spaCy
- scikit-learn
- statsmodels
- yellowbrick
- scipy
- pingouin

## Contact
For any queries regarding the research or the repository, feel free to open an issue or contact the author directly at inchul.yang@vanderbilt.edu.
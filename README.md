# Sentiment Analysis Using NLTK VADER and LDA

This project performs sentiment analysis on user reviews from the Bhashini app using NLTK's VADER tool and Latent Dirichlet Allocation (LDA) for topic modeling.

## Table of Contents
- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Scripts](#scripts)
- [Steps for Final Output](#steps-for-final-output)
- [Results](#results)
- [License](#licence)

## Introduction
This repository contains the code used to scrape and analyze sentiment from the Google Play Store reviews of the Bhashini app. We implemented NLTK's VADER for sentiment analysis and used LDA for topic modeling to gain insights from user feedback.

## Environment Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Anamikaa04/Sentiment-Analysis
   cd sentiment-analysis
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
3. Install Jupyter:
   ```bash
   pip install jupyter
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook

## Notebooks
- Sentiment Analysis.ipynb: Contains all the steps for web scraping, sentiment analysis, and topic modeling using NLTK VADER and LDA.
- IndicBERT.ipynb: Contains all the steps for data preprocessing, fine-tuning the IndicBERT model, and evaluating the results.

## Steps for Final Output
- Sentiment Analysis.ipynb
  - Web Scraping: Open the notebook and execute the cells related to web scraping to collect reviews. The output will be saved in a CSV file.
  - Sentiment Analysis: Execute the cells to run NLTK's VADER sentiment analysis on the collected reviews.
  - Topic Modeling: Run the LDA topic modeling cells to extract topics from the reviews.
- IndicBERT.ipynb
  - Data Preprocessing: Open the notebook and run the cells to preprocess the dataset for model training.
  - Fine-Tuning the Model: Execute the cells to fine-tune IndicBERT on the dataset.
  - Model Evaluation: Run the evaluation cells to obtain the performance metrics (accuracy, precision, recall, F1-score)

## Results
- Sentiment Analysis.ipynb:
  - Sentiment distribution using NLTK Vader is visualized within the notebook.
    
    ![Screenshot 2024-08-09 163132](https://github.com/user-attachments/assets/41d329fa-15cb-4131-a5ef-dbb9a2f33415)

  - Key topics are identified through LDA for better insight into user concerns and feedback.
 
    ![Screenshot 2024-08-08 190131](https://github.com/user-attachments/assets/a442d052-8296-48de-99f0-e988ef8b5e84)

    
- IndicBERT.ipynb:
  - The fine-tuned IndicBERT model achieved an 86% accuracy in classifying sentiments in multilingual reviews.

    ![Screenshot 2024-07-23 145840](https://github.com/user-attachments/assets/319f6107-5183-4bcd-82b0-da2611a2b63f)


## License
This project is licensed under the MIT License - see the LICENSE file for details.

# Analytical_Synopsis_of_Drug_Users-_Sentiments using LSTM-
Developed an LSTM-based NLP model for sentiment analysis on 215,000 drug reviews, achieving 86% accuracy in identifying diverse sentiments from patient feedback. This provided valuable insights to support advancements in pharmaceutical research and healthcare strategies.

## Project Overview
This project utilizes Long Short-Term Memory (LSTM) networks, a type of recurrent neural network, for the sentiment analysis of drug reviews. The goal is to classify sentiments expressed in drug reviews, ranging from positive to negative, to provide insights into patient experiences with medications.

## Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)

## Introduction
This study employs LSTM algorithms in Natural Language Processing (NLP) to conduct sentiment analysis on drug reviews, aiming to enhance pharmaceutical insights and patient care. The model achieves an accuracy of 86% in sentiment categorization, providing a solid foundation for nuanced sentiment analysis in healthcare.

## Technologies Used
- Python
- LSTM (Long Short-Term Memory)
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for model evaluation
- Jupyter Notebook for code development and presentation

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository and encompasses patient reviews on specific drugs, associated conditions, and a 10-star patient satisfaction rating system. The dataset's structure is as follows:

- **Entries:** 161,297
- **Features:** 7 (drugName, condition, review, rating, date, usefulCount)

### Key Highlights
- **Drug Name:** Name of the medication.
- **Condition:** Medical condition treated.
- **Review:** Textual patient feedback.
- **Rating:** 10-star satisfaction rating.
- **Date:** Date of review submission.
- **Useful Count:** Number of users who found the review helpful.

The main challenge lay in the lack of explicit sentiment labels in the dataset, necessitating the extraction of sentiments from the provided ratings to serve as the target variable for analysis. This approach allowed for a more in-depth understanding of patient experiences and satisfaction, offering valuable insights to drive improvements in healthcare.

## Installation
Instructions on setting up the project environment.
```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
```

## Usage
Guide on how to use the project, including running the Jupyter notebook, viewing the presentation, and exploring the dataset.

## Results
The LSTM model achieved an 86% accuracy in classifying drug review sentiments. The findings offer valuable insights for pharmaceutical companies and healthcare providers.

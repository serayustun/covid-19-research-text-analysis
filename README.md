# COVID-19 Research Paper Text Analysis - NLP Exploratory Data Analysis

This project presents an exploratory data analysis (EDA) on a collection of COVID-19 research paper abstracts and titles using Natural Language Processing (NLP) techniques.

## Project Overview

The main goal is to extract meaningful insights from the textual data through:

- **Data Cleaning:** Selecting relevant columns (`title`, `abstract`, `publish_time`), removing missing or incomplete records, and filtering for papers published from 2020 onward.
- **Text Preprocessing:** Lowercasing, removing punctuation and numbers, tokenization, removing stopwords, and lemmatization to prepare clean text for analysis.
- **N-gram Frequency Analysis:** Identifying and visualizing the most frequent single words (unigrams) and two-word phrases (bigrams) to understand dominant themes in the research papers.
- **Visualization:** Bar plots showing top unigrams and bigrams, providing intuitive insight into common terms used in the dataset.

## Technologies Used

- Python 3.x  
- pandas  
- nltk  
- scikit-learn  
- matplotlib  
- seaborn

# TASK-1-NLP-PROCESSING-ENGINE
#  NLP Preprocessing Engine

 Data Science Internship Assignment – February 2026

This project focuses on building a robust NLP preprocessing pipeline to clean and transform real-world noisy text data into structured and meaningful tokens.

 Project Overview

In real-world applications, text data is often messy and contains noise such as emojis, URLs, repeated characters, and inconsistent formatting.
This project implements a preprocessing engine that handles such issues effectively and prepares the data for machine learning models.

 Features Implemented

* Removal of numbers, URLs, and email patterns
* Conversion of text to lowercase
* Handling of repeated characters (e.g., "soooo" → "so")
* Removal of special characters and extra spaces
* Tokenization of text
* Removal of very short tokens (with exceptions like "no", "not")
* Token-level statistical analysis
* Frequency analysis using `Counter`
* Error handling for edge cases (empty input, emojis, numbers)

 Sample Input

I absolutely looooved this product 😍😍
 Processed Output

Tokens: ['absolutely', 'loved', 'this', 'product']
Cleaned Sentence: absolutely loved this product


 Analysis Performed

* Total number of tokens
* Number of unique tokens
* Average token length
* Identification of noisy sentences
* Frequency distribution of words

Tech Stack

* Python
* Regular Expressions (`re`)
* NumPy
* Collections (`Counter`)
* Jupyter Notebook


 Project Structure

nlp-preprocessing-engine/
│
├── NLP_Preprocessing_Engine.ipynb
├── README.md
├── requirements.txt

 How to Run

1. Clone the repository
2. Open the notebook in Jupyter Notebook or Google Colab
3. Run all cells sequentially

 Key Learnings

* Handling noisy real-world text data
* Designing reusable NLP pipelines
* Writing clean and modular Python code
* Performing basic text analytics

---

 GitHub Repository

(Add your repo link here)

---

 Acknowledgment

This project was completed as part of the Data Science Internship assignment.

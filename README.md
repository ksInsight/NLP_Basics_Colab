# NLP_Basics_Colab
This repository contains basic and essential Natural Language Processing (NLP) practicals performed using Python libraries such as NLTK, spaCy, and re in a Google Colab notebook.

🚀 Technologies Used
Python

Google Colab

NLTK – Natural Language Toolkit

spaCy – Industrial-strength NLP in Python

Regular Expressions (re) – Text pattern matching

📘 Practical Topics Covered
Each section is implemented with explanations and examples in NLP_Basics_Colab.ipynb.

1. Text Cleaning
Lowercasing

Removing punctuation and special characters

Removing stop words

Regular expression-based cleaning

2. Tokenization
Word and sentence tokenization using NLTK and spaCy

python
Copy
Edit
from nltk.tokenize import word_tokenize, sent_tokenize

3. Stemming
Using NLTK’s PorterStemmer and LancasterStemmer

python
Copy
Edit
from nltk.stem import PorterStemmer

4. Stopwords Removal
Using built-in NLTK stopwords list

🛠️ How to Use
✅ Step 1: Open in Google Colab
Click to open the notebook: NLP_Basics_Colab.ipynb


✅ Step 2: Install Requirements (inside notebook)

!pip install nltk
!pip install spacy

✅ Step 3: Download Required NLTK Corpora

import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

📌 Author
Kiran Singh
Exploring AI/ML/NLP and building practical solutions with Python.
Feel free to connect for collaboration or queries!


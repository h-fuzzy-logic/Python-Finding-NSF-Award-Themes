# Python-Finding-NSF-Award-Themes
 Natural language processing (NLP) can help make sense of large volumes of data, when there is too much data for a person to read.  This repo demonstrates how to find themes and concpets in the textual award data from the National Science Foundation.  Writing a proposal for an NSF award can be time consuming and the review process can seem mysterious.  To increase the chances of writing a winning proposal, natural language processing can uncover which phrases and topics have received funding.   It is also possible to determine if larger award amounts tend to be associated with certain words, phrases, and topics.  With this goal in mind, below are some insights about the NSF awards from 2019.

# Related Blog Post
https://h-fuzzy-logic.github.io/blog/nlp-nsf-awards

# Tools Used
* Jupyter Notebook
* Python, Pandas, NLTK, scikit-learn

# Technical Highlights
* Main branch is named trunk 
* Transformed publicly available XML files into a CSV file  
* Used NLTK for stopwords, tokenizing, and nGrams
* Used scikit-learn for Latent Semantic Analysis (LSA)  
* Used python def's to make the code easier to understand  

# Getting Started
* The data (CSV file) is not included in the repo due to GitHub storage limits.  (The file is 188 MB.)
* All required imports are in one cell at the top of the notebook.

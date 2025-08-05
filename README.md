Quora Duplicate Question Detection | End-to-End NLP with Streamlit Deployment
This project is an end-to-end Natural Language Processing (NLP) pipeline designed to detect whether two questions are semantically similar, using the Quora Question Pairs dataset. It features robust text preprocessing, feature extraction, and machine learning classification, with an interactive Streamlit web app for user-friendly input and real-time predictions.

🔧 Key Features:
Data Cleaning: HTML tag removal using BeautifulSoup, text normalization, lowercasing, and stopword removal

String Similarity Features: Using fuzzywuzzy, distance, and Jaccard/Cosine similarity scores

ML Modeling: Trained with scikit-learn classifiers such as Logistic Regression and Random Forest

User Interface: Built with Streamlit for an intuitive, real-time user experience

Model Evaluation: Includes accuracy, F1-score, confusion matrix, and ROC-AUC metrics

🧰 Tech Stack:
Python

Streamlit – for interactive UI

scikit-learn – for model training and evaluation

fuzzywuzzy & distance – for string similarity scoring

bs4 (BeautifulSoup) – for HTML and tag cleanup

Pandas, NumPy, matplotlib – for data handling and visualization


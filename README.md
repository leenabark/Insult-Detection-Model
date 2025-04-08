# Insult Detection Using NLP

## Overview  
Online toxicity is a significant and growing concern. This project addresses the issue by detecting insults in social media comments through advanced NLP techniques. The model identifies content containing cyberbullying, hate speech, or offensive language, with the goal of improving moderation and safety on digital platforms.

### Key Highlights  
- **High Accuracy**: Utilizes transformer-based models such as BERT and RoBERTa for reliable insult detection.  
- **Comprehensive Text Preprocessing**: Handles slang, abbreviations, emojis, and stretched words for cleaner input.  
- **Real-World Relevance**: Designed to support integration into moderation pipelines for social platforms.  
- **Interactive Interface**: A simple web application is available for real-time comment evaluation.

---

## Features

### Advanced NLP Preprocessing  
- Removal of emojis, URLs, and user mentions  
- Filtering of non-English text  
- Expansion of common internet slang and abbreviations  
- Normalization of stretched words  
- Lemmatization and stopword removal  

### Model Architecture  
- BERT, RoBERTa, and SVM classifiers  
- Trained on a dataset of over 47,000 labeled tweets  
- Uses class-weighted loss functions to address data imbalance  

### Web Interface  
- Built with Streamlit for ease of use  
- Enables users to input a comment and receive instant classification results

---

## Dataset  
The project uses the **Cyberbullying Classification Dataset** from Kaggle, which includes **47,692 labeled tweets** categorized into:  
- Not Cyberbullying  
- Age-based Bullying  
- Ethnicity-based Bullying  
- Gender-based Bullying  
- Religion-based Bullying  
- Other Cyberbullying  

For this implementation, the problem has been simplified to binary classification: **insult vs. non-insult**.

---

## Tech Stack  

| Area             | Tools & Libraries                          |
|------------------|---------------------------------------------|
| Programming      | Python                                      |
| Data Processing  | Pandas, NumPy                               |
| NLP              | SpaCy, LangDetect, Regex, NLTK              |
| Machine Learning | Scikit-learn, Hugging Face Transformers     |
| Visualization    | Matplotlib, Seaborn, WordCloud              |
| Deployment       | Streamlit                                   |

---

## How It Works  
1. A user inputs a comment.  
2. The system preprocesses the text and runs it through the trained model.  
3. The interface displays whether the comment is classified as an insult or not.

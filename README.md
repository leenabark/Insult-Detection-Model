# 🛑 Insult Detection Model 🚀  

![Insult Detection Banner](https://user-images.githubusercontent.com/your-banner-image)  

## 🔍 Overview  
Toxicity in online spaces is a growing problem. This project tackles the challenge by **detecting insults in social media comments** using **cutting-edge NLP techniques**. The model identifies whether a comment contains **cyberbullying, hate speech, or offensive language**, making online platforms safer.  

✨ **Why This Project is Unique?**  
✅ **High Accuracy:** Uses **transformer-based models (BERT, RoBERTa)** for precise insult detection.  
✅ **Advanced Text Processing:** Cleans slang, abbreviations, emojis, and even stretched words.  
✅ **Real-World Application:** Can be **integrated into social media moderation systems**.  
✅ **User-Friendly Interface:** Provides an **interactive web app** for real-time insult detection.  

---

## 📌 **Features**
✅ **Multi-Step NLP Preprocessing**  
✔️ Removes **emojis, URLs, mentions (@username)**  
✔️ Filters **non-English text**  
✔️ Expands **slang & abbreviations** (e.g., *u → you*, *brb → be right back*)  
✔️ Fixes **stretched words** (e.g., *sooooo → so*)  
✔️ Applies **lemmatization & stopword removal**  

✅ **State-of-the-Art Model**  
✔️ Uses **BERT, RoBERTa, or SVM** for classification  
✔️ Trained on a **large dataset of 47,000+ tweets**  
✔️ Handles **imbalanced classes with weighted loss functions**  

✅ **Interactive User Interface**  
✔️ **Web-based UI (Streamlit)** where users can enter a comment and check if it's an insult  
✔️ **Fast & Accurate** classification in real-time  

---

## 📊 **Dataset**
We use the **Cyberbullying Classification Dataset** from Kaggle, which contains **47,692 labeled tweets** categorized into:  
- 🔹 **Not Cyberbullying**  
- 🔹 **Age-based Bullying**  
- 🔹 **Ethnicity-based Bullying**  
- 🔹 **Gender-based Bullying**  
- 🔹 **Religion-based Bullying**  
- 🔹 **Other Cyberbullying**  

For better performance, we **convert this into a binary classification problem (insult vs. non-insult)**.

---

## 🚀 **Tech Stack**
| Component       | Technology |
|----------------|------------|
| **Programming** | Python 🐍 |
| **Data Processing** | Pandas, NumPy |
| **NLP** | SpaCy, LangDetect, Regex, Stopwords |
| **Machine Learning** | Scikit-Learn, Transformers (BERT, RoBERTa) |
| **Visualization** | Matplotlib, Seaborn, WordCloud |
| **Deployment** | Streamlit (for UI), Hugging Face (optional) |

---

## ⚡ **How It Works**
🔹 **Step 1**: Enter a comment in the input field.  
🔹 **Step 2**: The model processes the text and predicts if it's an insult.  
🔹 **Step 3**: The result is displayed instantly!  


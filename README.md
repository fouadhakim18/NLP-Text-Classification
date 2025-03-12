# NLP-Text-Classification 🚀  
A complete Natural Language Processing (NLP) pipeline for text preprocessing, vectorization, and classification.  

## 📌 Overview  
This project applies **text preprocessing, vectorization, and classification techniques** on the Spooky dataset, which consists of literary text samples from different authors. The goal is to classify texts based on their authorship using various machine learning and deep learning models.

## 📂 Features  
### **1️⃣ Text Preprocessing (TP1)**  
- **Data Cleaning**: Handling punctuation, special characters, and repeated words.  
- **Text Normalization**: Lowercasing, homoglyph replacement, and stopword removal.  
- **Segmentation & Tokenization**: Sentence splitting and subword tokenization.  
- **Named Entity Recognition (NER)**: Extracting entities like persons, locations, and organizations.  
- **Lemmatization & Stemming**: Reducing words to their base/root forms.  
- **Sentiment Analysis**: Identifying text polarity using TextBlob.  

### **2️⃣ Feature Extraction & Classification (TP2)**  
- **Vectorization Techniques**: One-Hot Encoding, TF-IDF, and Word Embeddings (`Word2Vec`, `GloVe`, `FastText`).  
- **Hybrid Meta-Embedding**: Combining multiple embeddings dynamically for better performance.  
- **Imbalanced Data Handling**: Using `ADASYN` for synthetic sampling to improve minority class predictions.  
- **Machine Learning Models**: `MLPClassifier`, `Random Forest`, `CNN`.  
- **Deep Learning Models**: **BERT & XLNet**, where **BERT achieved the highest accuracy of 83%**.  

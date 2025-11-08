# 📰 NewsBot Intelligence System
**Course:** ITAI-2373 – Natural Language Processing  
**Project:** Midterm Group Project (Solo Implementation)  
**Author:** John Nguyen

---

## 🎯 Overview
The **NewsBot Intelligence System** is an end-to-end NLP project that automatically processes, classifies, and analyzes news articles.  
It integrates all eight course modules into one working pipeline — from text preprocessing to entity recognition — demonstrating how real-world NLP systems extract insights from unstructured text.

The system performs:
- Text cleaning, normalization, and lemmatization  
- TF-IDF feature extraction and keyword analysis  
- POS and syntax pattern exploration  
- Sentiment and emotion analysis  
- Multi-class text classification  
- Named Entity Recognition (NER)  
- Visualization of key insights and category trends

---

## 🧠 Core Components (Modules 1–8)
| Module | Description |
|:--|:--|
| **1. Business Context** | Defines the real-world application of NewsBot for media monitoring and business intelligence. |
| **2. Preprocessing** | Cleans text, removes noise, and lemmatizes words using spaCy. |
| **3. TF-IDF Analysis** | Extracts top keywords per category and visualizes them. |
| **4. POS Tagging** | Identifies grammatical structure and writing style differences. |
| **5. Syntax Parsing** | Extracts subject-verb-object relationships for semantic insight. |
| **6. Sentiment Analysis** | Uses VADER to assess tone and polarity across topics. |
| **7. Classification** | Compares Logistic Regression, Naive Bayes, and Random Forest. |
| **8. NER** | Extracts people, organizations, and locations from articles. |

---

## 🗂️ File Structure
```
ITAI2373-NewsBot-Midterm/
│
├── NewsBot_Intelligence.ipynb       ← Main Colab notebook
├── bbc_news_clean_sample.csv        ← Small cleaned dataset sample
├── NewsBot_Reflection_Solo.pdf      ← Two-page reflection report
└── README.md                        ← Project overview (this file)
```

---

## 📊 Dataset
This project uses the **BBC News Classification Dataset** from Kaggle:  
🔗 https://www.kaggle.com/competitions/learn-ai-bbc/data  

**Original file:** `BBC News Train.csv`  
**Included here:** a small cleaned sample (`bbc_news_clean_sample.csv`) showing the same structure.  

To reproduce full results:
1. Download the dataset manually from Kaggle.  
2. Upload `BBC News Train.csv` to Colab.  
3. Run the notebook starting from **Module 2 (Text Preprocessing)**.

---

## ⚙️ Requirements
- Google Colab (Free Tier)  
- Python 3  
- Libraries:
  ```
  pandas
  numpy
  nltk
  spacy
  scikit-learn
  matplotlib
  seaborn
  ```
In Colab, install any missing packages using:
```python
!pip install spacy scikit-learn matplotlib seaborn
```
and download required resources:
```python
import nltk, spacy
nltk.download("stopwords")
nltk.download("vader_lexicon")
spacy.cli.download("en_core_web_sm")
```

---

## ▶️ How to Run
1. Open **NewsBot_Intelligence.ipynb** in [Google Colab](https://colab.research.google.com).  
2. Upload your dataset (`BBC News Train.csv`) using the file sidebar.  
3. Run all cells sequentially (top → bottom).  
4. View generated charts and printed analysis.  

Optional: Replace the dataset path with your own CSV for other news sources.

---

## 📈 Results Summary
- **Logistic Regression** achieved the best classification accuracy.  
- Sentiment analysis showed category-dependent tone (Sports and Entertainment most positive).  
- NER identified recurring entities such as countries, organizations, and political figures.  
- Combined, these modules produce actionable insights similar to media monitoring tools.

---

## 💡 Insights and Business Value
The NewsBot system mirrors the architecture of commercial NLP platforms used for:
- **Media sentiment tracking**
- **Competitor and trend analysis**
- **Automated content categorization**
- **Brand and reputation monitoring**

It demonstrates how integrated NLP pipelines can turn text data into structured, decision-ready insights.

---

## 🧩 Reflection Summary
Working solo on this project required designing, coding, and integrating all eight modules efficiently within Colab’s runtime limits.  
The main challenge was balancing runtime with model completeness.  
The biggest discovery was how combining sentiment and entity data provides deeper narrative context across topics.  
This project serves as both a learning milestone and a professional portfolio piece demonstrating practical NLP system design.

---

## 📎 Citation
Dataset: BBC News Classification Dataset © BBC / Kaggle (Educational Use)  
Libraries: scikit-learn, spaCy, NLTK, matplotlib  

---

**Repository Link:** [https://github.com/yourusername/ITAI2373-NewsBot-Midterm](https://github.com/yourusername/ITAI2373-NewsBot-Midterm)  
*(Replace with your actual GitHub repo URL before submission.)*

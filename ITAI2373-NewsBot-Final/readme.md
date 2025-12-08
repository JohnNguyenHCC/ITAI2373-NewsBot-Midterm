# NewsBot Intelligence System 2.0  
ITAI 2373 Final Project  

## Overview
NewsBot 2.0 is a full upgrade of the midterm NewsBot system.  
It processes BBC news articles and turns raw text into structured insight through a complete NLP pipeline.  
The system includes advanced classification topic modeling sentiment analysis summarization semantic search multilingual translation and an interactive conversation tool.  
All features run on Google Colab with open source libraries and no external API keys.

---

## Folder Contents
This folder contains the full final deliverable set.

ITAI2373-NewsBot-Final/
│
├── NewsBot2_Final.ipynb
├── README.md
├── bbc_news_sample_final.csv
│
├── FP_TechnicalDoc_YourName_Solo_ITAI2373.pdf
├── FP_ExecutiveSummary_YourName_Solo_ITAI2373.pdf
└── FP_ReflectiveJournal_YourName_Solo_ITAI2373.pdf


**Notebook**  
Main system notebook with all modules integrated.

**Sample CSV**  
Small cleaned sample for testing and portability.

**PDF Deliverables**  
Technical Doc  
Executive Summary  
Reflective Journal  
All use the naming format required in the final assignment.

---

## System Features

### 1. Advanced Content Analysis Engine
- Linear SVM classification  
- LDA topic modeling  
- Sentiment scoring by article and topic  

### 2. Language Understanding and Generation
- Extractive summaries  
- Abstractive summaries using a small BART model  
- Semantic search using MiniLM embeddings  

### 3. Multilingual Intelligence
- English to French translation  
- Sentiment checks across languages  
- Topic word translation  

### 4. Conversational Interface
Supports natural queries such as:  
- Summarize this article  
- Find stories about this event  
- Show sentiment for this subject  
- What topics appear in the data  

---

## How to Run the Notebook
1. Open `NewsBot2_Final.ipynb` in Google Colab  
2. Upload the full file `BBC News Train.csv` into the Colab file explorer  
3. Run each cell in order  
4. The system will output tables plots summaries and conversation results  

The notebook runs inside the free tier of Colab.

---

## Dataset
Source: BBC News Classification dataset on Kaggle  
https://www.kaggle.com/competitions/learn-ai-bbc/data  

This folder includes a small cleaned sample file.  
Use the original BBC News Train.csv for full analysis.

---

## Project Goals
NewsBot 2.0 aims to:

- Apply advanced NLP tools in a complete pipeline  
- Show how classification topic modeling and sentiment work together  
- Provide high level summaries for fast reading  
- Support multilingual checks and insight  
- Deliver a simple conversation interface for direct access  
- Offer portfolio quality work for future roles in AI or data science  

---

## Notes
The midterm version of this project is stored in the folder  
`ITAI2373-NewsBot-Midterm`  
Both versions show the full progression of the system through the course.




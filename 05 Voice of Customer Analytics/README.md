# Voice of Customer Analytics
[![](https://img.shields.io/badge/-Topic--Modeling-orange)](#) [![](https://img.shields.io/badge/-NLP-orange)](#) [![](https://img.shields.io/badge/-Python-green)](#) [![](https://img.shields.io/badge/-Google--Colab-green)](#) [![](https://img.shields.io/badge/-student-blue)](#)

# Overview
This project revolves around analyzing Wongnai reviews for the restaurant named "Pa Boon," situated in Sriracha, Chonburi. With its reputation spanning across Chonburi, this restaurant has established over 5 branches. The Sriracha branch, operational for a year now, prompts an exploration into customer feedback regarding their perceptions and sentiments towards "Pa Boon." Leveraging Natural Language Processing (NLP) techniques, we aim to glean insights from a sample of 30 comments sourced from Wongnai's platform.
![image](VOC-01.jpg)

# Collect data
Collect data (text) and prepare to CSV file
![image](VOC-02.jpg)

# Text Processing
- Removing stopwords and meaningless words
- Sentence and Word tokenization (using pythainlp)
- Do topic modeling by using LDA (Latent Dirichlet Allocation) model 
  (LDA is a popular algorithm for topic modeling, which is used to discover hidden thematic structures in a collection of documents)
- Visualization by using **pyLDAvis**

# Results

**Topic1**
![image](messageImage_1693312050285.jpg)

**Topic2**
![image](messageImage_1693312074610.jpg)

**Topic3**
![image](messageImage_1693312108581.jpg)

**Topic Detail**
![image](messageImage_1693312143425.jpg)

**Word Cloud**
![image](messageImage_1693312203417.jpg)

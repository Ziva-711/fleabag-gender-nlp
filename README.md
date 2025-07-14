# Fleabag Gendered Dialogue Analysis

> *A computational study of gendered language expression in the British TV series* **Fleabag** *(Season 1)*

---

## 📖 Project Overview

This project combines natural language processing (NLP) with feminist media critique to analyze how gender shapes dialogue, emotional tone, and self-expression in the acclaimed TV series *Fleabag*.

We focus on Season 1, Episode 1, extracting and annotating character dialogues, performing sentiment analysis, and visualizing linguistic patterns to reveal gendered narrative dynamics.

---

## 🛠️ Tools & Technologies

- **Python** — core language  
- **pandas, pysrt** — subtitle parsing and data handling  
- **TextBlob, NLTK** — sentiment and linguistic analysis  
- **matplotlib, seaborn, wordcloud** — data visualization  
- **Jupyter Notebook** — interactive analysis  

---

## 🔍 Key Features

- **Structured dialogue dataset** linking characters to lines with timestamps  
- **Dialogue distribution analysis** by gender and character  
- **Sentiment polarity & subjectivity scoring** per line  
- **Self-referential pronoun frequency** analysis (e.g., "I", "me", "my")  
- **Visualizations:**  
  - 台词数量对比图 (Dialogue Count by Character)  
  ![Dialogue Count](./images/dialogue_count.png)  
  - 情绪极性分布 (Sentiment Polarity Distribution)  
  ![Sentiment Polarity](./images/sentiment_polarity.png)  
  - 关键词词云 (Word Cloud for Fleabag)  
  ![Word Cloud](./images/fleabag_wordcloud.png)  

---

## 🎯 Motivation

By quantifying gender differences in dialogue and emotional expression, the project highlights the unique voice and complexity of the female protagonist *Fleabag* compared to male characters. It also raises ethical questions about how AI language models trained on such corpora might replicate or amplify these gendered language patterns.

---

## 🚀 Future Directions

- Extend analysis to multiple episodes and seasons  
- Comparative studies with other TV shows and genres  
- AI-generated dialogue simulations to assess gender bias replication  
- Develop ethical guidelines to mitigate bias in AI language generation  

---

## 📂 Usage

```bash
# Clone repository
git clone https://github.com/Ziva-711/fleabag-gender-nlp.git

# Install dependencies
pip install -r requirements.txt



---

# 🧠 LLM-Driven Customer Sentiment Analysis and Review Propagation Modeling in E-Commerce

## 📋 Project Overview

This project explores how **Large Language Models (LLMs)** and **Natural Language Processing (NLP)** can be used to analyze and interpret customer reviews in the e-commerce domain.
By applying various machine learning techniques — from traditional lexicon-based sentiment tools to advanced transformer-based models — the goal is to **understand customer sentiment**, **predict product perception**, and **model review propagation** to support business decision-making.

Developed as part of an academic project by:

* 👩‍💻 **Fahmida Sweety** (ID: B200305017)
* 👨‍💻 **Tertho Ghosh** (ID: B200305011)
  

---

## 🎯 Objectives

* Perform **sentiment analysis** on e-commerce customer reviews using traditional and modern NLP methods.
* Compare **lexicon-based** (TextBlob, VADER) and **transformer-based** (DistilBERT, MultiBERT) models.
* Visualize **review distribution**, **sentiment polarity**, and **keyword trends** using word clouds and graphs.
* Model how customer sentiments **propagate and influence** overall product perception.

---

## 🧩 Dataset

* **Dataset Name:** Amazon Reviews for Sentiment Analysis
* **Source:** [Kaggle - tarkkaanko/amazon](https://www.kaggle.com/datasets/tarkkaanko/amazon)
* **Data Features:**

  * Review Text
  * Ratings
  * Timestamps
  * Product Category / ID

The dataset provides a diverse collection of customer feedback used to train and evaluate sentiment models.

---

## 🧠 Methodology

### 1. Data Preprocessing

* Text cleaning (removing punctuation, stop words, and special symbols)
* Handling missing values
* Tokenization and normalization
* Standardizing review metadata

### 2. Sentiment Analysis Models

| Model Type        | Method                        | Description                                                               |
| ----------------- | ----------------------------- | ------------------------------------------------------------------------- |
| Lexicon-Based     | **TextBlob**, **VADER**       | Calculates polarity and subjectivity based on predefined dictionaries.    |
| Transformer-Based | **DistilBERT**, **MultiBERT** | Uses pre-trained language models for contextual sentiment classification. |

### 3. Visualization

* Sentiment distribution across ratings
* WordClouds for positive and negative reviews
* Temporal sentiment trends

### 4. Evaluation

* Accuracy, Precision, Recall, and F1-Score
* Comparative performance analysis between classical and LLM-based models

---

## 🧰 Tools & Technologies

* **Python** 🐍
* **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
* **TextBlob**, **VADER**, **Transformers (HuggingFace)**
* **NLTK**, **WordCloud**, **Torch**, **TQDM**
* **KaggleHub** for dataset access

---

## 🚀 Results & Insights

* Transformer-based models (especially **DistilBERT**) achieved **higher accuracy and robustness** in detecting nuanced sentiments compared to lexicon-based models.
* Lexicon-based approaches remained useful for quick and interpretable sentiment scoring.
* Visualization revealed strong correlations between **ratings and sentiment polarity**.
* Demonstrated potential for real-world use in **automated review monitoring systems**.

---

## 💡 Future Work

* Incorporate **multilingual review datasets** for cross-lingual sentiment understanding.
* Enhance **review propagation modeling** to analyze how one customer’s sentiment influences others.
* Integrate a **real-time dashboard** for sentiment tracking in e-commerce platforms.

---

## 🏁 Conclusion

This project demonstrates how **LLM-driven sentiment analysis** can transform raw customer feedback into actionable insights for businesses. It bridges the gap between customer emotions and data-driven decisions, showcasing the power of modern NLP in the e-commerce landscape.

---

## 📎 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/LLM-Customer-Sentiment-Analysis.git
cd LLM-Customer-Sentiment-Analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook
jupyter notebook "B200305011_&_B200305017_Project.ipynb"
```

---

## 🏷️ Keywords

`LLM` • `NLP` • `Sentiment Analysis` • `E-Commerce` • `Transformers` • `TextBlob` • `VADER` • `DistilBERT` • `Machine Learning`

--

Here’s a **clear, professional GitHub repository description** you can directly use. I’ve written it in a way that fits **data science / IR projects** and looks good to recruiters and lecturers 👌
(Aligned with your VSM + QLM + Streamlit background, Sadeeka)

---

## 📰 News Information Retrieval System (VSM vs QLM)

### Project Description

This project implements a **News Information Retrieval System** that retrieves the most relevant news articles based on a **user’s search query**.
The system compares two classic Information Retrieval models:

* **Vector Space Model (VSM)**
* **Query Likelihood Model (QLM)**

An **interactive Streamlit web application** is developed to allow users to enter queries and visually compare retrieval results from both models.

---

###  Objective

To retrieve and rank relevant news articles efficiently based on user queries and **compare the performance and behavior of VSM and QLM models**.

---

### Models Used

* **Vector Space Model (VSM)**
  Uses TF-IDF weighting and cosine similarity to rank documents.

* **Query Likelihood Model (QLM)**
  A probabilistic language model that estimates the likelihood of a document generating the query.

---

### Tech Stack

* **Python** – Core implementation
* **Pandas** – Data handling and preprocessing
* **Streamlit** – Interactive web application
* **Scikit-learn / NLP libraries** – Feature extraction and similarity computation

---

### Full Process / Workflow

1. **Dataset Collection**
   News articles collected from multiple sources (e.g., CNN, BBC, Al Jazeera).

2. **Data Preprocessing**

   * Lowercasing
   * Tokenization
   * Stop-word removal
   * Text normalization

3. **Feature Engineering**

   * TF-IDF vectorization for VSM
   * Language model probability estimation for QLM

4. **Model Implementation**

   * Document ranking using cosine similarity (VSM)
   * Probability-based ranking using QLM

5. **Query Processing**

   * User inputs a query via the Streamlit interface
   * Query is processed and passed to both models

6. **Result Ranking & Comparison**

   * Top relevant articles retrieved from each model
   * Side-by-side comparison of VSM vs QLM results

7. **Web Application Deployment**

   * Interactive UI built with Streamlit
   * Real-time query search and result display

---

### Final Output

* An **interactive Streamlit web app**
* Displays ranked news articles for both **VSM and QLM**
* Enables easy **model comparison** based on relevance

---

### Use Case

* Academic learning of Information Retrieval models
* Understanding probabilistic vs vector-based retrieval
* Demonstration project for **Data Science / IR portfolios**

---

###  Repository Structure 

```
├── data/
│   └── news_dataset.csv
├── preprocessing.py
├── vsm_model.py
├── qlm_model.py
├── app.py
├── requirements.txt
└── README.md
```

---


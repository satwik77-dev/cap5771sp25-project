# **AI Mental Health Chatbot**

A conversational AI chatbot designed to provide **Mental health support**, answer queries, and analyze user sentiment using NLP and machine learning techniques. The chatbot leverages real-world counseling conversations, a mental health FAQ base, and sentiment-tagged statements to generate relevant, empathetic responses.

---

## **Project Overview**

This project aims to build an **AI-powered mental health chatbot** capable of:

- **Understanding user intent** (emotional support, general queries, or FAQs).
- **Predicting mental health labels** using sentiment cues in text.
- **Providing context-aware responses** based on input and classification.

The system is built using a combination of **classification models**, **text preprocessing pipelines**, and **feature-engineering strategies**, organized over three structured milestones.

---

## **📌 Milestones**

The project follows a staged CRISP-DM inspired structure:

1️⃣ **Milestone 1: Data Collection, Cleaning, & Exploratory Data Analysis (Completed)**  
2️⃣ **Milestone 2: Feature Engineering, Feature Selection, Classification Modeling (Completed)**  
3️⃣ **Milestone 3: Chatbot Integration, Evaluation, Deployment & Final Report (⏳ Due April 23)**  

---

## **📁 Project Structure**

```bash
cap5771sp25-project/
│
├── Data/
│   ├── Raw Data/                     # Original source datasets
│   │   ├── Mental_Health_FAQ.csv
│   │   ├── Mental_health_counseling_conversations.csv
│   │   └── Sentiment_Analysis.csv
│   │
│   ├── Cleaned Data/                # Preprocessed datasets for modeling
│       ├── Cleaned_Counseling_Conversations.csv
│       ├── Cleaned_Mental_Health_FAQ.csv
│       ├── Cleaned_Sentiment_Analysis.csv
│       ├── Modeling_Dataset.csv
│       └── Modeling_Dataset_Enriched.csv
│
├── Scripts/
│   ├── Preprocessing.ipynb                # Initial text cleaning steps
│   ├── EDA.ipynb                          # Visualizations, word distributions
│   ├── FeatureEngineeringSelection.ipynb  # Engineered features, correlation analysis
│   └── ModelTraining.ipynb                # Intent & Label classification models
│
├── Reports/
│   ├── Milestone1.pdf                     # Report on Data & EDA
│   └── Milestone2.pdf                     # Report on Modeling & Feature Engineering
│
└── README.md
```

---

## ✅ **Milestone 2: Feature Engineering & Modeling**

### Tasks Completed:

- **Unified the three datasets** with appropriate intent/label annotations.
- **Created engineered features** like `Statement_Word_Count`, `Has_Severe_Keyword`, `Question_Word_Count`, etc.
- **Handled null values** using intent-specific filtering and smart exclusion.
- **Visualized key insights** to validate feature relevance (e.g., skewed input lengths, label imbalance).
- **Trained 5 ML models** across two classification tasks:
  - Intent Classifier (Logistic Regression, Naive Bayes, Random Forest)
  - Label Classifier (Logistic Regression, Random Forest per intent)
- **Justified feature inclusion/exclusion** based on correlation and relevance.
- **Evaluated models** using accuracy and macro F1-score.

📄 All documentation and analysis is compiled in `Reports/Milestone2.pdf`.

---

## 🔁 How to Reproduce

###  1. Setup Environment

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

###  2. Run Preprocessing

```bash
# Open and run all cells in
Scripts/Preprocessing.ipynb
```

### 📊 3. Visualize EDA

```bash
# Run
Scripts/EDA.ipynb
```

### ⚙️ 4. Feature Engineering & Selection

```bash
# Run
Scripts/FeatureEngineeringSelection.ipynb
```

### 🤖 5. Train ML Models

```bash
# Train and evaluate all classifiers via
Scripts/ModelTraining.ipynb
```

---

## 👨‍💻 Contributor

- **Sai Satwik Yarapothini** – NLP Developer, Data Science Lead  
- **GitHub:** [satwik77-dev](https://github.com/satwik77-dev)

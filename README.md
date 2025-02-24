# **AI Mental Health Chatbot**
A conversational AI chatbot designed to provide **mental health support**, answer queries, and analyze user sentiment using NLP and machine learning.

## **Project Overview**
This project aims to develop an **AI-powered chatbot** capable of:
- **Providing mental health-related answers** using a structured **FAQ knowledge base**.
- **Generating therapy-informed responses** using real **counseling conversations**.
- **Detecting sentiment** in user inputs and **adjusting responses accordingly**.


## **📌 Milestones**
The project follows a structured approach with multiple milestones:
1️⃣ **Milestone 1: Data Collection, Preprocessing & Exploratory Data Analysis (EDA) ✅ (Completed)**  
2️⃣ **Milestone 2: Feature Engineering, Model Training & Chatbot Integration ⏳ (Upcoming)**  
3️⃣ **Milestone 3: Evaluation, Deployment & Final Report ⏳ (Upcoming)**  

This repository currently includes **Milestone 1 deliverables**.

---

## **📌 Project Structure**
The repository is organized as follows:

```
Data
├── Cleaned Data                 # Processed datasets after cleaning
│   ├── Cleaned_Dataset1.csv
│   ├── Cleaned_Dataset2.csv
│   ├── Cleaned_Dataset3.csv
│
├── Raw Data                      # Original Raw datasets
│   ├── Mental_Health_FAQ.csv
│   ├── Mental_health_counseling_conversations.csv
│   ├── Sentiment_Analysis.csv
│
├── Reports                       # Documentation and milestone reports
│   ├── Milestone1.pdf            # Milestone 1 Report (Data Collection, Cleaning, EDA)
│
├── Scripts                       # Python Notebooks for analysis
│   ├── Preprocessing.ipynb       # Data Preprocessing steps
│   ├── EDA.ipynb                 # Exploratory Data Analysis (EDA)
│
├── README.md                     # Project documentation
```

---

##  Milestone 1: Data Collection, Preprocessing & EDA
### **✔️ Tasks Completed**
✅ **Data Collection**  
- Acquired **three datasets** relevant to mental health chatbot development:
  - **Counseling Conversations**: Q&A between users and psychologists.
  - **FAQ Knowledge Base**: Frequently asked mental health questions.
  - **Sentiment Analysis**: Tagged mental health statements for emotion detection.
- Verified dataset **accessibility and licensing** for academic use.

✅ **Data Preprocessing**  
- Cleaned text by **removing stopwords, punctuation, special characters**.
- Applied **lemmatization and stemming** to standardize text inputs.
- Handled **missing data and outliers** in mental health-related conversations.

✅ **Exploratory Data Analysis (EDA)**  
- **Analyzed dataset distributions, text length variations, and sentiment trends**.
- **Visualized common words using word clouds and bar charts**.
- **Identified key patterns in mental health queries** to optimize chatbot responses.

📄 **All findings and insights are documented in** `Milestone1.pdf`.

---

## **📌 Instructions to Reproduce Milestone 1**
Follow these steps to **replicate data preprocessing and EDA**:

### **1️⃣ Setup Environment**
Ensure you have **Python 3.8+** and install dependencies:

```bash
pip install pandas numpy matplotlib seaborn nltk wordcloud scikit-learn
```

### **2️⃣ Run Preprocessing**
Execute the preprocessing script:

```python
# Open Preprocessing.ipynb and run all cells
```

### **3️⃣ Perform EDA**
Run the EDA script to generate visualizations:

```python
# Open EDA.ipynb and run all cells
```

---

## **📌 Contributors**
👨‍💻 **Sai Satwik Yarapothini** - Developer & Researcher  
🔗 **GitHub:** https://github.com/satwik77-dev 


---

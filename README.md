Here is the complete, professional `README.md` file for your **Mental Health Support Chatbot** project — ready to be copy-pasted into your repo:

---

```markdown
# 🧠 Mental Health Support Chatbot

A supervised **AI-powered mental health chatbot** designed to offer emotionally supportive and informative responses based on real-world counseling, FAQs, and sentiment-labeled data. This conversational agent combines **Machine Learning (for Intent Prediction)** and **Transformer-based Language Models (for Response Generation)** to understand user input and generate meaningful replies in real-time.

---

## 📌 Project Objective

To build a hybrid NLP-based chatbot that:
- **Classifies user intent** (e.g., emotional support, FAQ, or general counseling),
- **Generates human-like responses** using `facebook/blenderbot-400M-distill` (local LLM),
- And provides an interactive, multi-turn conversational experience via Gradio.

---

## 🧰 Tech Stack

| Layer            | Tools & Libraries |
|------------------|------------------|
| Language         | Python 3.10       |
| NLP & ML         | Scikit-learn, Transformers (HuggingFace), Blenderbot |
| Data Handling    | Pandas, NumPy, Regex |
| Visualization    | Matplotlib, Seaborn, WordCloud |
| Deployment       | Gradio |
| Version Control  | Git + GitHub |
| Report Writing   | Overleaf / MS Word, PowerPoint |

---

## 🗃️ Datasets Used

1. **Mental Health Counseling Conversations**  
   - [Hugging Face](https://huggingface.co/datasets/Amod/mental_health_counseling_conversations)  
   - Real user-therapist interactions.

2. **Mental Health FAQ**  
   - [Kaggle](https://www.kaggle.com/datasets/narendrageek/mental-health-faq-for-chatbot)  
   - Expert responses to commonly asked mental health questions.

3. **Sentiment-Labeled Mental Health Posts**  
   - [Kaggle](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health)  
   - Emotional states of users (depression, anxiety, suicidal thoughts, etc.)

All datasets were cleaned, normalized, and **merged into a unified modeling dataset**.

---

## 🏗️ Chatbot Workflow

1. **User Input** (via Gradio UI)
2. **Intent Prediction** using Random Forest on TF-IDF features.
3. **Response Generation** using Blenderbot (locally loaded from Hugging Face).
4. **Chat History Maintained** (Multi-turn conversation).
5. **Displayed Results**:
   - User Message
   - Predicted Intent
   - Bot's Response

---

## 🚀 How to Run the Chatbot

### 🔧 Prerequisites

- Python ≥ 3.10
- Install dependencies:
```bash
pip install -r requirements.txt
```

### ▶️ Run the Gradio App

```bash
python chatbot_app.py
```

> ✅ To generate a **public link**, make sure `share=True` is set in `demo.launch()` inside `chatbot_app.py`.

---

## 📂 Project Structure

```
cap5771sp25-project/
├── Models/                 # Original ML models & vectorizers
├── BestModels/             # Retrained, final models used in chatbot
├── Cleaned Data/           # Cleaned datasets (1, 2, 3)
├── Reports/
│   ├── Milestone1.pdf
│   ├── Milestone2.pdf
│   └── Milestone3.pdf      # Final report
├── Scripts/
│   ├── chatbot_app.py      # Final Gradio-based chatbot
│   ├── preprocessing.ipynb
│   ├── feature_engineering.ipynb
│   └── model_training.ipynb
├── README.md               # This file
└── requirements.txt        # All dependencies
```

---

## 🎥 Tool Demo

Watch our full working **demo video** here:  
**[👉 Tool Demo Video Link]** *(Replace with your video URL)*

---

## 📊 Project Milestones

| Milestone | Deliverable |
|----------|-------------|
| **M1**   | Data collection, cleaning, and EDA |
| **M2**   | Feature engineering & ML model training |
| **M3**   | Final evaluation, deployment via Gradio UI |

---

## 👨‍💻 Contributors

**Sai Satwik Yarapothini**  
Master's in Applied Data Science  
University of Florida  

---

## 📄 License

This project is for academic and non-commercial research use only. All datasets are publicly available and permitted for academic use via their respective licenses.

```

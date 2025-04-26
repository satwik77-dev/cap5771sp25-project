# 🧠 AI Powered Mental Health Chatbot

---

## Objective of the Project

To develop an **Empathetic Conversational chatbot** for mental health support that classifies user intent and generates context-aware responses using a trained machine learning model and a lightweight local LLM (Blenderbot-400M-distill).


## Project Architecture

- **Intent Classification**:
  - Trained Random Forest Classifier using TF-IDF vectorized input and additional features like Statement Word Count and Question Word Count.
- **Response Generation**:
  - Local deployment of Blenderbot-400M-distill model for generating empathetic multi-turn replies.
- **Frontend**:
  - Built using Gradio for a user-friendly chat interface with memory support.



## 🚀 Chatbot Deployment (Gradio App)

The deployed chatbot includes:
- Textbox for user input.
- Multi-turn conversation history display.
- Predicted Intent Display.
- Submit and Clear buttons for smooth interaction.

**Final Gradio Interface:**

![Final Chatbot Interface Screenshot](<https://uflorida-my.sharepoint.com/:i:/g/personal/saisatwi_yarapot_ufl_edu/EdqyTWeMErdBg-dpUAwqq9IBvxuNNTNESJDqRnJJ4TqACQ?e=AcMMY2>)


## 🎥 Tool Demo Video

- [🔗 Click Here to Watch My Tool Demo](<https://uflorida-my.sharepoint.com/:v:/g/personal/saisatwi_yarapot_ufl_edu/EQMQR4tGWeJGvpG1WqFHU_8BLsqAbkafEIzoEja5TLv3Mw>)

---

## 📝 Final Report

- [🔗 Click Here to Access Final Milestone Report](<https://uflorida-my.sharepoint.com/:b:/g/personal/saisatwi_yarapot_ufl_edu/EUsF1gLClfZIvX8rZYo-EdIBN51b3Q6GgyeWSpTM_ZZUIw?e=oPgPUe>)

---

## 🎤 Final Presentation & Video

- [🔗 Final Presentation Slides](<https://uflorida-my.sharepoint.com/:b:/g/personal/saisatwi_yarapot_ufl_edu/EY9Fd1NM8LZAjFy77nXF2twBXOSobYLi6gI1kk-2NqHDVQ?e=9u3vHh>)
- [🔗 Final Presentation Video](<https://uflorida-my.sharepoint.com/:v:/g/personal/saisatwi_yarapot_ufl_edu/EZl-x3fJZDlBhsfjjJoSvBIBAq6vJ7VrdP5kLmfiW9VpDQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=KTNNtS>)



## 💻 How to Run this Project Locally

Follow these simple steps:

1. **Clone the Repository**
   ```bash
   git clone <https://github.com/satwik77-dev/cap5771sp25-project>
   ```

2. **Install Required Libraries**
   ```bash
   pip install pandas scikit-learn transformers gradio
   ```

3. **Run the Gradio Chatbot App**
   ```bash
   python chatbot_app.py
   ```

4. Open the Gradio link in your browser to use the chatbot.

> **Note**: First time running will automatically download Blenderbot-400M-distill from HuggingFace.


## 👨‍💻 Developed By

**Sai Satwik Yarapothini**
Masters in Applied Data Science
University of Florida


## 📚 References

- [Facebook Blenderbot 400M-distill - Hugging Face](https://huggingface.co/facebook/blenderbot-400M-distill)
- [Hugging Face Datasets](https://huggingface.co/datasets)
- [scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Gradio Documentation](https://gradio.app/)
- [Transformers Library - Hugging Face](https://huggingface.co/docs/transformers/index)

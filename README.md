# SkillBot 🤖 | Your Personalized Guide to Skills4Future

**SkillBot** is an intuitive chatbot designed to bridge the gap between curiosity and knowledge for the **Skills4Future** program. Whether you're exploring program details, learning about cutting-edge **Green Skills** and **AI technologies**, or seeking guidance on how to apply, **SkillBot** is here to assist you.

---

## ✨ Key Features
- 🔍 **Intent Classification**: Understands and classifies user queries into specific intents using Logistic Regression.
- 📚 **Comprehensive Information**: Provides answers to questions about Skills4Future, from eligibility criteria to advanced AI courses.
- 💬 **Interactive Chat**: Engage in real-time conversations via a sleek, web-based interface powered by Streamlit.
- 📝 **Interaction Logs**: Maintains a log of conversations for revisiting key insights or tracking improvement.

---

## 🔧 Technology Stack

- **Programming Language**: Python
- **Libraries and Tools**:
  - `nltk` for text preprocessing (tokenization, stemming, stop-word removal).
  - `scikit-learn` for intent classification using Logistic Regression and TF-IDF.
  - `Streamlit` for creating a dynamic and user-friendly interface.
  - `csv` and `datetime` for logging interactions and monitoring chatbot performance.

---

## 🚀 How It Works

### 1. Preprocessing
**SkillBot** uses advanced preprocessing techniques to clean user inputs:
- Converts text to lowercase.
- Removes unhelpful stop words like "is" and "the."
- Reduces words to their root forms (e.g., "running" → "run").

### 2. Training
- A dataset of intents, patterns, and responses is processed and vectorized using TF-IDF.
- Logistic Regression is employed to classify user inputs into predefined categories.

### 3. Response Generation
- Based on the classified intent, the chatbot fetches and delivers a relevant response.
- Out-of-scope queries are handled gracefully with fallback responses to ensure user satisfaction.

### 4. User Interface
**Streamlit** powers a clean, minimalistic, and easy-to-navigate interface, making **SkillBot** accessible to everyone.

---

## 📬 Contact

Have questions or feedback? Let’s connect!

- **Author**: Ayaz Shaikh  
- **GitHub**: [AyazShaikh01](https://github.com/AyazShaikh01/)  
- **Chatbot App**: [SkillBot on Streamlit](https://chatbotwithnlp.streamlit.app/)  

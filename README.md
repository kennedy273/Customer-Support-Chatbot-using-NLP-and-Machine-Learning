# 🤖 Customer Support Chatbot using NLP & Machine Learning

An intelligent **Customer Support Chatbot** built with **Natural Language Processing (NLP)** and **Machine Learning (ML)**.  
The chatbot understands user queries, classifies their intent, and responds with accurate, human-like replies — automating customer interactions efficiently.

---

## 🚀 Features
- 💬 Understands and responds to user queries intelligently  
- 🧠 Trained ML model for intent classification  
- 🧹 Text preprocessing using NLP (tokenization, stemming, TF-IDF)  
- ⚙️ Fully customizable `intents.json` file for adding new conversations  
- 🌐 Streamlit web interface for a modern chat experience  
- 🪄 Lightweight and easy to run locally or in the cloud  

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:** NLTK, Scikit-learn, NumPy, Pandas  
- **Web Framework:** Streamlit  
- **Data Format:** JSON  

---

## 📂 Project Structure

📁 customer-support-chatbot/
│
├── intents.json # Chatbot training data (intents, patterns, responses)
├── chatbot.py # Core chatbot logic and ML model
├── app.py # Streamlit web app
├── requirements.txt # Project dependencies
└── README.md # Project documentation


---

## ⚙️ Installation
```bash
# Clone this repository
git clone https://github.com/<your-username>/customer-support-chatbot.git

# Navigate into the project
cd customer-support-chatbot

# Install required packages
pip install -r requirements.txt

💻 Run the Chatbot
Option 1 — Command Line Chat
python chatbot.py

Option 2 — Streamlit Web App
streamlit run app.py

💬 Example Chat
You: Hi  
Bot: Hello! How can I assist you today?

You: I forgot my password  
Bot: No problem! You can reset your password using the 'Forgot Password' link.

You: Bye  
Bot: Goodbye! Have a great day ahead!

🌟 Future Enhancements

Add context awareness for multi-turn conversations

Integrate with APIs (e.g., support ticket system, FAQ database)

Enable multilingual support

Deploy online using Streamlit Cloud or Render

👨‍💻 Author

Kennedy Kyalo
📧 kyalok159@gmail.com

💼 Data Science Enthusiast | Passionate about AI, NLP & Automation

⭐ If you found this project helpful, give it a star to show your support!

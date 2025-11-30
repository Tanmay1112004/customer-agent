# 🤖 Customer Agent – AI-Powered Support Bot

Welcome!  
This project implements a simple **Customer Support AI Agent** using Python.  
It can:

- Classify user messages into intents like *refund*, *cancellation*, *billing*, or *general help*.  
- Detect urgency levels (high / medium / low).  
- Generate automated replies accordingly.  
- Maintain a short-term in-memory chat history.  

---

## 📄 Kaggle Notebook  
The full working notebook is available on **Kaggle**:  
[Customer-Agent-Tanmay-Kshirsagar](https://www.kaggle.com/code/tanmay1112004/customer-agent-tanmay-kshirsagar)  

You can view the live code, run experiments, and test the agent there.

> Note: Since much of the code is currently in the Kaggle notebook, migrating modules to separate `.py` files makes this repo cleaner and eases reuse.

---

## 🔧 How It Works

1. User sends a message.  
2. The agent stores the message in memory.  
3. Intent detection + urgency classification runs on the message.  
4. Based on intent & urgency, an appropriate reply is generated.  
5. Reply is returned and also stored in memory.  

Example output:  
```json
{
  "intent": "cancellation",
  "urgency": "high",
  "reply": "I can help you cancel your subscription. Kindly provide your registered email."
}
````

---

## 🚀 How to Use / Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/customer-agent-ai.git
   cd customer-agent-ai
   ```
2. (Optional) Create a virtual environment and install dependencies (if any).
3. Run the demo:

   ```bash
   python main.py
   ```

Feel free to interact with the agent by modifying `main.py` or integrating it into your own application.

---

## ✅ Future Improvements

* Replace rule-based intent detection with an LLM or ML-based classifier.
* Add support for multi-turn conversation with context.
* Add sentiment analysis and more nuanced responses.
* Build a simple web or CLI front-end to use this as a chatbot.
* Add tests & error handling for robustness.

---

## 👨‍💻 Author

**Tanmay Kshirsagar**
You can view the working notebook on Kaggle (link above).

---

## ⭐ License & Contribution

Feel free to fork and contribute! If you enhance this project, consider adding credits and improve README accordingly.

```

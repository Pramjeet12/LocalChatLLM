# 🤖 LocalChatLLM

A lightweight conversational chatbot built with **Google Flan-T5 Large**, designed to run entirely on a free **Google Colab T4 GPU** — no API keys, no internet connection needed during chat.

---

## 📋 About

LocalChatLLM lets you have a back-and-forth conversation with an open-source LLM running locally in your Colab session. It keeps track of conversation history so the model has context across turns.

---

## 🧠 Model

| Property | Detail |
|---|---|
| Model | `google/flan-t5-large` |
| Parameters | ~780M |
| Type | Instruction-tuned (seq2seq) |
| Best for | Definitions, explanations, general Q&A |
| Runtime | Free Colab T4 GPU |

---

## ⚙️ Features

- Conversation history across multiple turns  
- Repetition penalty to avoid looping responses  
- Graceful exit with `quit`, `exit`, or `bye`  
- Auto GPU/CPU detection  
- Empty input handling  

---

## ⚠️ Limitations

| Works Well | Doesn't Work Well |
|---|---|
| Science & tech questions | Current events / news |
| Definitions & explanations | Specific people / politics |
| Historical facts | Creative writing / jokes |

---

## 🛠️ Built With

- Hugging Face Transformers  
- Google Flan-T5 Large  
- PyTorch  
- Google Colab (free tier)  

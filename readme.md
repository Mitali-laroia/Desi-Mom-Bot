# 🩴 Desi Mom Python Bot

A savage yet lovable AI bot that helps you learn Python with Hinglish drama, emotional blackmail, and taunts inspired by every desi household.

Built using **Streamlit** and **OpenAI GPT-4.1 Mini**, this chatbot:
- Answers Python questions only (haan haan, JavaScript walon ke liye mummy free nahi hai).
- Explains code step-by-step using **Chain of Thought**.
- Replies in Hinglish with taunts, food metaphors, and Sharma ji ka beta references.

## Deployed Link:
https://desi-mom-bot.streamlit.app/
Note:- The link could be down due to inactivity or credit limit being finished.

## 🎯 Features

- Hinglish replies with dramatic flair (just like real mummy ji 🫡)
- Streamed response with spinner while mummy thinks 🧠
- Supports structured multi-step answers:
  - `analyse` → `think` → `output` → `validate` → `result`

## 🧱 Tech Stack

- [Streamlit](https://streamlit.io/)
- [OpenAI GPT-4.1 Mini API](https://platform.openai.com/docs)
- Python 3.9+
- dotenv for secure API key loading

## 🚀 How to Run Locally

```bash
git clone https://github.com/yourusername/desi-mom-python-bot.git
cd desi-mom-python-bot
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt
streamlit run chat.py

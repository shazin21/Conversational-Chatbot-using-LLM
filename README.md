# Enhanced Q&A Chatbot with OpenAI

## 📌 Project Description
This project is a **Q&A chatbot** powered by **OpenAI's GPT models** and built using **Streamlit**. It allows users to input questions and receive intelligent responses, with options to customize the chatbot's behavior.

---

## ⚡ Features
✅ User-friendly web interface with Streamlit  
✅ Supports **GPT-4o, GPT-4-Turbo, GPT-4** models  
✅ Adjustable **temperature** and **max tokens** for fine-tuned responses  
✅ Secure API key input through Streamlit sidebar  
✅ Simple and intuitive design for easy interaction  

---

## 🛠 Tech Stack
- **Python** (Backend Processing)
- **Streamlit** (Frontend UI)
- **LangChain** (LLM Integration)
- **OpenAI API** (AI Responses)
- **Dotenv** (Environment Variable Management)

---

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/YOUR_USERNAME/Enhanced-QA-Chatbot.git
cd Enhanced-QA-Chatbot
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the project root and add:
```env
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
```
Replace `your_openai_api_key` with your actual OpenAI API key.

### 4️⃣ Run the Streamlit App
```sh
streamlit run app.py
```
This will launch the chatbot in your web browser.

---

## 📂 Project Structure
```
Enhanced-QA-Chatbot/
│── app.py                 # Main Streamlit App
│── requirements.txt       # Python dependencies
│── .env                   # Environment variables (not included in GitHub)
│── test.py                # Streamlit test script
│── README.md              # Project documentation
```

---

## 🎯 How It Works
1️⃣ User enters an OpenAI API key in the sidebar.  
2️⃣ Selects an **LLM model** (GPT-4o, GPT-4-Turbo, etc.).  
3️⃣ Adjusts response settings (**temperature, max tokens**).  
4️⃣ Inputs a question, and the chatbot generates a response.  

---

## 🛠 Testing Streamlit
To check if Streamlit is working properly, run:
```sh
streamlit run test.py
```
If successful, you will see a simple message confirming Streamlit is installed.

---

## 📜 License
This project is **open-source** and free to use. Contributions are welcome! 🚀

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT4o-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![License](https://img.shields.io/badge/License-MIT-green)

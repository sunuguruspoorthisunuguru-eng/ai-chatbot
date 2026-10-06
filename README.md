# 🤖 Nova AI Chatbot

A modern, local AI chatbot built using **Python, Streamlit, HTML, CSS, JavaScript, and Ollama**.

This project provides a simple and user-friendly chat interface where users can interact with a locally running AI model without requiring an external API key.

---

## 📌 Project Overview

**Nova AI Chatbot** is an AI-powered conversational application that runs locally on your computer.

The frontend interface is created using **HTML, CSS, and JavaScript**, while **Python and Streamlit** handle the application logic. **Ollama** is used to run the AI model locally and generate responses.

### Key Benefits

* 🔐 No API key required
* 💻 Runs locally
* 🤖 Powered by Ollama
* 🎨 Modern responsive interface
* 💬 Real-time chat interaction
* 🧹 Clear conversation option
* 📚 Useful for learning and college projects

---

## ✨ Features

* Modern AI chatbot interface
* Local AI response generation
* Chat history during the current session
* Typing/loading indicator
* Clear conversation button
* Responsive UI
* Python backend
* HTML/CSS/JavaScript integrated into `app.py`
* Ollama local model integration
* No `.env` file required
* No paid API required

---

## 🛠️ Technologies Used

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Python     | Application backend       |
| Streamlit  | Web application framework |
| HTML       | Interface structure       |
| CSS        | UI styling                |
| JavaScript | Client-side interaction   |
| Ollama     | Local AI model runtime    |
| Llama 3.2  | AI language model         |
| Requests   | Communication with Ollama |

---

## 📂 Project Structure

```text
AI_Chatbot/
│
├── app.py
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Requirements

Before running the project, install:

* Python 3.10 or newer
* VS Code
* Ollama
* Llama 3.2 model

Python packages:

```text
streamlit
requests
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Go into the project folder:

```bash
cd AI_Chatbot
```

---

### 2. Install Python dependencies

If `pip` is not recognized, use:

```bash
python -m pip install -r requirements.txt
```

or:

```bash
py -m pip install -r requirements.txt
```

---

### 3. Install Ollama

Install Ollama on your computer.

After installation, check:

```bash
ollama --version
```

---

### 4. Download the AI model

Run:

```bash
ollama pull llama3.2
```

This downloads the Llama 3.2 model for local use.

---

## ▶️ Running the Project

Start the Streamlit application:

```bash
python -m streamlit run app.py
```

or:

```bash
py -m streamlit run app.py
```

Streamlit will provide a local address similar to:

```text
http://localhost:8501
```

Open that address in your browser.

---

## 🔑 API Key

**No API key is required.**

The application communicates with the locally running Ollama service instead of using an online AI API.

```text
User
  ↓
Streamlit Interface
  ↓
Python Backend
  ↓
Ollama
  ↓
Llama 3.2
  ↓
AI Response
```

---

## 🔒 Privacy

Because the AI model runs locally through Ollama, conversations are processed by the local model rather than being sent to a third-party AI API by this application.

However, users should still avoid entering sensitive personal information into experimental software.

---

## 💬 Example Questions

You can ask Nova AI questions such as:

```text
Explain Python in simple words.
```

```text
What is Artificial Intelligence?
```

```text
Give me some AI project ideas.
```

```text
Explain machine learning.
```

```text
Write a simple Java program.
```

---

## 🖥️ User Interface

The application includes:

* AI assistant header
* Online/local AI status
* Chat message area
* User and AI message bubbles
* Chat input box
* Clear conversation button
* Suggested questions
* Responsive design

---

## 🔮 Future Improvements

Possible future features include:

* 🎤 Voice input
* 🔊 Text-to-speech responses
* 📄 PDF/document chat
* 🖼️ Image understanding
* 💾 Persistent chat history
* 👤 User authentication
* 🌐 Online deployment
* 🧠 Multiple Ollama model selection
* 📊 Chat analytics
* 📱 Improved mobile interface

---

## ⚠️ Important Notes

This project is intended for **educational and demonstration purposes**.

AI-generated responses can sometimes be incorrect. Important information should be verified from reliable sources.

The speed of responses depends on your computer hardware and the Ollama model being used.

---

## 👩‍💻 Author

**AI Chatbot Project**

Built using:

**Python • Streamlit • Ollama • Llama 3.2 • HTML • CSS • JavaScript**

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

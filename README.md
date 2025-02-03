# Code Assistant powered by Deepseek

🚀 **Why fear when AI and Arman are here?**

## 🧠 Introduction

**Code Assistant** is an AI-powered coding assistant built using **Streamlit** and **Deepseek**, running locally with **Ollama**. This tool provides assistance with debugging, code documentation, and solution design using **Deepseek-r1:1.5b** and **Deepseek-r1:3b** models.

## 📌 Features

- 🐍 **Python Expert** – Get help with Python programming.
- 🐞 **Debugging Assistant** – Identify and fix errors quickly.
- 📝 **Code Documentation** – Generate documentation for your code.
- 💡 **Solution Design** – Get structured solutions for coding problems.

---

## 🔧 Prerequisites

Before running the project, make sure you have:

1. **Ollama installed** (to run LLM models locally)
2. **Deepseek model downloaded**: [deepseek-r1:1.5b](https://ollama.com/library/deepseek-r1:1.5b)
3. **Python and Conda installed** (recommended for virtual environment setup)

### 🔽 Install Deepseek Model
Run the following command in the terminal:
```sh
ollama run deepseek-r1:1.5b
```

---

## 🏗️ Installation & Setup

### Step 1: Clone the Repository
```sh
git clone https://github.com/your-username/code-assistant.git
cd code-assistant
```

### Step 2: Create a Virtual Environment (Optional but Recommended)
```sh
conda create --name code-assistant python=3.9 -y
conda activate code-assistant
```

### Step 3: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 4: Run the Application
```sh
streamlit run app.py
```

---

## 📸 Screenshots

![Code Assistant UI](https://github.com/Arman1263/code-assistant-deepseek/blob/b962fcbc8c6a121c5c57d7fab7a78052782263d3/1.png)
![Code Assistant UI](https://github.com/Arman1263/code-assistant-deepseek/blob/b962fcbc8c6a121c5c57d7fab7a78052782263d3/2.png)

---

## 🛠️ Built With
- **[Streamlit](https://streamlit.io/)** – UI Framework
- **[LangChain](https://python.langchain.com/)** – LLM Orchestration
- **[Ollama](https://ollama.ai/)** – LLM Runtime

---

## 📜 Requirements

Ensure you have the following dependencies installed:
```txt
streamlit
langchain_core
langchain_community
langchain_ollama
```

---

## 📌 Contributing
Feel free to fork this repository and submit pull requests. If you find any issues, open an issue on GitHub.

---

## 📞 Contact
For any inquiries, reach out via GitHub Issues or email at `armanshikalgar01@gmail.com`.


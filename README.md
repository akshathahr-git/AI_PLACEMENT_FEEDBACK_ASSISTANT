# AI Placement Feedback Assistant 🤖

An AI-powered placement preparation assistant designed to help students prepare for technical and HR interviews by generating interview questions, evaluating answers, and providing personalized feedback using Generative AI.

## 🚀 Features

- **Interview Question Generation:** Generates interview questions for placement preparation.
- **Answer Evaluation:** Analyzes user responses and evaluates answer quality.
- **Personalized Feedback:** Provides suggestions to improve interview answers.
- **AI-Powered Assistance:** Uses Large Language Models (LLMs) through OpenRouter API.
- **Interactive Interface:** Provides a user-friendly interface for interview practice.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Framework:** Streamlit
- **AI Framework:** LangChain
- **LLM Integration:** OpenRouter API
- **Workflow Orchestration:** LangGraph
- **Environment Management:** Python dotenv

## 📂 Project Structure

```text
AI_PLACEMENT_FEEDBACK_ASSISTANT/
│
├── app.py
├── graph.py
├── nodes.py
├── state.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/akshathahr-git/AI_PLACEMENT_FEEDBACK_ASSISTANT.git
```

### 2. Navigate to the Project Directory

```bash
cd AI_PLACEMENT_FEEDBACK_ASSISTANT
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Create a `.env` file in the project directory and add your OpenRouter API key:

```env
OPENROUTER_API_KEY=your_openrouter_api_key
```

Replace `your_openrouter_api_key` with your actual API key.

### 5. Run the Application

```bash
streamlit run app.py
```

The application will open in your default web browser.


## 🎯 Objective

The main objective of this project is to make placement preparation more interactive and effective by leveraging Generative AI to simulate interview practice, evaluate responses, and provide meaningful feedback to improve students' interview performance.

## 👩‍💻 Author

**Akshatha H R**

GitHub: [akshathahr-git](https://github.com/akshathahr-git)

---

⭐ If you find this project useful, consider giving it a star!
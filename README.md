# 📚 StudyMate AI

StudyMate AI is a simple multi-task AI study assistant built with **Python, Google Gemini, and Gradio**. It is designed to help students learn, understand, summarize, and practice different academic topics from one easy-to-use interface.

## ✨ Features

StudyMate AI currently provides four main features:

### 💬 1. Chat

Ask StudyMate questions about programming, AI, mathematics, computer science, or other academic topics.

### 📝 2. Summarize

Paste lengthy study material and StudyMate converts it into:

* A short summary
* Main points
* Important terms

### 🧠 3. Generate Quiz

Enter a topic and StudyMate generates:

* 5 multiple-choice questions
* Four options for each question
* An answer key

### 📖 4. Explain Topic

Enter a topic and receive an easy-to-understand explanation containing:

* Definition
* Main concepts
* Simple example
* Real-world application
* Revision points

## 🛠️ Technologies Used

* **Python** — Main programming language
* **Google Gemini API** — AI model used to generate responses
* **Gradio** — Web-based user interface
* **Google Colab** — Development environment

## 📁 Project Structure

```text
StudyMate-AI/
│
├── StudyMate_AI.ipynb
└── README.md
```

## 🚀 Getting Started

### 1. Open the Notebook

Open `StudyMate_AI.ipynb` in **Google Colab** or another Jupyter Notebook environment.

### 2. Install Dependencies

The notebook automatically installs the required packages:

```python
!pip install -q -U google-genai gradio
```

### 3. Add Your Gemini API Key

Find this line:

```python
GEMINI_API_KEY = ""
```

Add your Gemini API key between the quotation marks:

```python
GEMINI_API_KEY = "YOUR_API_KEY"
```

**Important:** Do not publish your API key on GitHub or share it publicly.

### 4. Run the Notebook

Run the complete cell.

Gradio will generate a link for the StudyMate AI interface.

## 🎯 How to Use

After launching the application:

1. Select a task from the dropdown.
2. Enter your question, topic, or study material.
3. Click **Ask StudyMate**.
4. The AI-generated result will appear below.

### Example

Select:

```text
Explain Topic
```

Enter:

```text
What is Artificial Intelligence?
```

StudyMate will generate a structured explanation of Artificial Intelligence.

## 🔄 Application Workflow

```text
User
  ↓
Select Task
  ↓
Enter Question / Topic / Text
  ↓
StudyMate AI
  ↓
Google Gemini API
  ↓
AI Generated Response
  ↓
Gradio Interface
```

## 📌 Requirements

Before running the project, you need:

* Python 3.9 or newer
* Internet connection
* A Google Gemini API key
* Google Colab or Jupyter Notebook

## 🔐 API Key Security

Never upload your actual API key to a public GitHub repository.

Instead of:

```python
GEMINI_API_KEY = "your-real-api-key"
```

keep the public version as:

```python
GEMINI_API_KEY = ""
```

Then add your key locally when running the project.

## 🌱 Future Improvements

The project can be expanded with:

* 💬 Chat history
* 📄 PDF/document summarization
* 🎯 Quiz scoring
* 📊 Student progress tracking
* 🔊 Text-to-speech
* 🌐 Multiple language support
* 🎨 Advanced user interface
* 👤 User accounts
* 📚 Personalized study plans
* 🧠 AI-generated flashcards

## 🎓 Purpose

The main purpose of StudyMate AI is to create a simple and practical academic assistant that helps students understand difficult topics, create study notes, and practice through quizzes.

## 👩‍💻 Author

**Kiran Saba**

Artificial Intelligence Student

## 📄 License

This project is created for educational and learning purposes.

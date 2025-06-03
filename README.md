
# 📄 Tnc-Summarizer

**Tnc-summarizer** is an innovative tool designed to simplify the daunting task of analyzing Terms & Conditions, making legal documents more accessible and understandable.

🔗 **Deployed App**: [https://harsh-tnc.streamlit.app](https://harsh-tnc.streamlit.app)  
📝 **Published Blog**: [Blog](https://medium.com/@thebeasts9876/building-a-terms-conditions-summarizer-with-google-gemini-ai-d528ba245d33)

---

## 📚 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)

---

## 📌 Overview

**Why Tnc-summarizer?**  
This project empowers users to navigate complex legal jargon effortlessly. The core features include:

- 🧑‍💻 **User-Friendly Interface**: Easily interact with the application through a sleek Streamlit interface.  
- 🗂️ **Multi-Format Input Support**: Analyze text directly, upload PDFs, or provide PDF URLs for comprehensive analysis.  
- 🤖 **AI-Driven Summarization**: Leverage the Gemini AI model to generate structured summaries that highlight key points.  
- ⚠️ **Actionable Insights**: Receive critical watchpoints and recommended actions to enhance understanding of legal documents.  
- 📦 **JSON Output**: Download analysis results in JSON format for seamless integration into other platforms.

---

## 🚀 Getting Started

### 📋 Prerequisites

This project requires the following dependencies:

- **Programming Language**: Python  
- **Package Manager**: Pip

---

### 🛠️ Installation

Build Tnc-summarizer from the source and install dependencies:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/harshtripathi272/Tnc-summarizer
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Tnc-summarizer
   ```

3. **Install the dependencies:**

   Using [pip](https://pip.pypa.io/en/stable/):

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

After installation, launch the Streamlit app:

```bash
streamlit run app.py
```

You can input:
- Raw text of Terms & Conditions
- Uploaded PDF files
- PDF URLs

The app will generate a structured summary and insights, with an option to download the result as a JSON file.

---

## ✅ Testing

To test the application manually:

- Use sample T&C PDFs or copy-pasted policies.
- Compare summaries with original content.
- Validate JSON output structure.

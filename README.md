Below is a more engaging, polished, and visually appealing version of your README.
No content is removed — everything is improved, reorganized, and enhanced with icons, badges, and visual cues.
You can paste this directly into `README.md`.

---

# FAQ_LANGCHAIN_LLM_BOT

**Empowering Smarter Conversations with AI Precision**

<p align="center">
  <img src="https://img.shields.io/badge/Last%20Commit-May%202024-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-100%25-yellow?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## 🔧 Built With

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,streamlit,sklearn,markdown" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-%23000000.svg?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-%2300C7B7.svg?style=for-the-badge" />
</p>

---

## 📚 Table of Contents

* [Overview](#overview)
* [Why FAQ_Langchain_LLM_Bot?](#why-faq_langchain_llm_bot)
* [Core Features](#core-features)
* [Getting Started](#-getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Testing](#testing)

---

## 🧠 Overview

`FAQ_Langchain_LLM_Bot` is a lightweight, developer-focused framework for building AI-powered FAQ chatbots.
Using **OpenAI LLMs**, **LangChain**, and **FAISS**, the system retrieves context-aware answers from your project’s knowledge base and exposes them through a clean **Streamlit UI** supporting both text and **speech-based interaction**.

Built for teams that need fast, consistent knowledge retrieval during projects or documentation-heavy workflows.

---

## ❓ Why FAQ_Langchain_LLM_Bot?

This project enables developers to build intelligent FAQ assistants with minimal complexity and maximum flexibility.

### 🌟 Core Features

* **🔍 Context-Aware Retrieval**
  Uses **FAISS embeddings** and **web scraping (WebBaseLoader)** to deliver precise answers based on your defined sitemap.

* **🎙️ Multi-Modal Interaction**
  Supports both text and **voice input/output**, including:

  * Speech-to-text (`SpeechRecognition`)
  * Natural-sounding text-to-speech using OpenAI `tts-1`.

* **🧩 Modular Architecture**
  Centralized configuration using a `.config` file for easy tuning and deployment.

* **🗣️ Voice Synthesis Engine**
  Smooth, expressive responses for accessibility and hands-free use.

* **✨ Smart Prompt Suggestions**
  Suggests relevant questions and detects out-of-scope queries gracefully.

---

## 🚀 Getting Started

Follow these steps to set up and run `FAQ_Langchain_LLM_Bot`.

### Prerequisites

You need:

* **Python 3.8+**
* **Pip package manager**
* Required packages:

  ```
  configparser
  langchain
  langchain-openai
  faiss-cpu
  scikit-learn
  streamlit
  trubrics
  SpeechRecognition
  PyAudio
  ```

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/SADidula/FAQ_Langchain_LLM_Bot
   ```

2. **Enter the project directory**

   ```bash
   cd FAQ_Langchain_LLM_Bot
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

### Launch the Streamlit web interface (recommended)

```bash
python gui.py
```

Or directly:

```bash
streamlit run gui.py
```

### Run the command-line interface (CLI)

```bash
python main.py
```

---

## 🧪 Testing

Run the full test suite using `pytest`:

```bash
pytest
```

---

<p align="center">
  <a href="#faq_langchain_llm_bot">⬆️ Back to Top</a>
</p>

---

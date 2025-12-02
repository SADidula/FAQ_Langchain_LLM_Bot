This README file is generated based on the structure and content from your uploaded images and the project analysis file.

# FAQ\_LANGCHAIN\_LLM\_BOT

**Empowering Smarter Conversations with AI Precision**

| last commit | languages |
| :---: | :---: |
| May 2024 | Python 100.0% |

Built with the tools and technologies:

| Markdown | Streamlit | scikit-learn | LangChain | Python |
| :---: | :---: | :---: | :---: | :---: |
| | | | | |

-----

## Table of Contents

  * [Overview](https://www.google.com/search?q=%23overview)
  * [Why FAQ\_Langchain\_LLM\_Bot?](https://www.google.com/search?q=%23why-faq_langchain_llm_bot)
  * [Features](https://www.google.com/search?q=%23features)
  * [Getting Started](https://www.google.com/search?q=%23getting-started)
      * [Prerequisites](https://www.google.com/search?q=%23prerequisites)
      * [Installation](https://www.google.com/search?q=%23installation)
  * [Usage](https://www.google.com/search?q=%23usage)
  * [Testing](https://www.google.com/search?q=%23testing)

-----

## Overview

`FAQ_Langchain_LLM_Bot` is a versatile developer tool designed to facilitate the deployment of AI-powered FAQ chatbots. Leveraging OpenAI's Large Language Models and Langchain, it enables efficient retrieval of common questions within group projects, complemented by an interactive web interface supporting both text and speech interactions. The system's modular architecture simplifies setup, configuration, and extension, making it ideal for building intelligent, multi-modal conversational agents.

## Why FAQ\_Langchain\_LLM\_Bot?

This project empowers developers to create sophisticated FAQ systems with ease.

### Core Features

  * **Context-Aware Retrieval:** Uses knowledge embedding (via `FAISS`) and web scraping (`WebBaseLoader`) to deliver accurate, relevant responses based on a defined sitemap.
  * **Multi-Modal Interaction:** Supports seamless user engagement through both text and speech input/output. This includes Speech-to-Text (STT) capabilities using `SpeechRecognition` and a voice response feature using OpenAI's `tts-1` model.
  * **Modular & Configurable:** Centralized configuration within a `.config` file and organized components streamline deployment and modification.
  * **Voice Synthesis:** Integrates text-to-speech capabilities for natural, expressive responses.
  * **Efficient Search & Recommendations:** Provides relevant prompt suggestions and includes logic for handling both in-scope and out-of-scope questions, enhancing the user experience.

-----

## 🚀 Getting Started

Build `FAQ_Langchain_LLM_Bot` from the source and install dependencies.

### Prerequisites

This project requires the following dependencies:

  * **Programming Language:** Python
  * **Package Manager:** Pip
  * **Required Packages:** `configparser`, `langchain`, `langchain-openai`, `faiss-cpu`, `scikit-learn`, `streamlit`, `trubrics`, `SpeechRecognition`, and `PyAudio`.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SADidula/FAQ_Langchain_LLM_Bot
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd FAQ_Langchain_LLM_Bot
    ```
3.  **Install the dependencies:**
    Using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

-----

## Usage

Run the project with the following commands:

**To launch the web interface (recommended):**

```bash
python gui.py
```

*(Note: As this is a Streamlit application, you may also use `streamlit run gui.py`.)*

**To run the command-line interface (CLI):**

```bash
python main.py
```

-----

## Testing

The project uses the `pytest` test framework. Run the test suite with:

**Using `pip`:**

```bash
pytest
```

-----

\<p align="center"\>
\<a href="\#table-of-contents"\>⬆️ Return to Top\</a\>
\</p\>

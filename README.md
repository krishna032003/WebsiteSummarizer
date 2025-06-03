# 🌐 Website Summarizer using LLaMA 3.2 (Ollama)

This project fetches the content of a webpage and summarizes it using the LLaMA 3.2 model running locally via Ollama. It uses BeautifulSoup to extract and clean the HTML content and sends it to the model for summarization in markdown format.

---

## 📌 Features

- Parses any given URL and extracts meaningful content.
- Cleans out navigation-related HTML like scripts, styles, images, and inputs.
- Uses LLaMA 3.2 via Ollama (runs locally).
- Displays a clean summary using markdown inside Jupyter Notebook.

---

## 🚀 Setup Instructions

### ✅ 1. Install Ollama and Pull LLaMA Model

Download and install Ollama: [https://ollama.com](https://ollama.com)

```bash
ollama pull llama3
ollama run llama3

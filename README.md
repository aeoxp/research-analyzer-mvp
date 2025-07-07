# 📚 ResearchAnalyzer.py

**A lightweight Python tool that automates the grunt work of research.**  
Feed it links, PDFs, or plain text — and get AI-powered summaries, key topics, and quotes in seconds.

---

## 🔍 Overview

**ResearchAnalyzer.py** is a mini research assistant designed for students, researchers, and knowledge workers. It scrapes or ingests content from various sources, cleans and preprocesses it, then uses AI to highlight the most important information.

Whether you're trying to distill a long article, process a dense PDF, or summarize raw notes — ResearchAnalyzer makes it fast and effortless.

---

## 🚀 Features

- **🧠 AI Summarization & Highlighting**  
  Extracts key ideas, themes, and quotes using large language models (LLMs).

- **📄 Multi-Format Input**  
  Accepts:
  - Web article URLs
  - PDF files
  - Pasted or raw text

- **🧹 Clean Text Processing**  
  Automatically removes ads, headers, boilerplate, and noisy content.

- **📦 Export Options**  
  Outputs summaries and insights to:
  - Markdown
  - JSON
  - Plain text

- **💻 Easy to Use**  
  Runs in:
  - Command-line interface (CLI)
  - Jupyter Notebooks

---

## ⚙️ Tech Stack

- Python 3.x  
- [`requests`](https://pypi.org/project/requests/), [`BeautifulSoup`](https://www.crummy.com/software/BeautifulSoup/), [`pdfminer.six`](https://pypi.org/project/pdfminer.six/) or [`PyMuPDF`](https://pymupdf.readthedocs.io/en/latest/)  
- OpenAI API or HuggingFace Transformers  
- CLI support (via `argparse`, `typer`, or similar)

---

## ✅ Use Cases

- 📚 Students summarizing course readings  
- 🔬 Researchers managing academic papers  
- 📝 Journalists pulling quotes and insights  
- 💡 Developers prototyping AI reading tools

---

## 📂 Example Workflow

```bash
# From the CLI
python researchanalyzer.py --input https://example.com/article --output summary.md

# From a Jupyter Notebook
from researchanalyzer import analyze
analyze("path/to/article.pdf", export_format="json")

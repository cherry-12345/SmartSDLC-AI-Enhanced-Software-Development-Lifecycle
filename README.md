# SmartSDLC – AI-Enhanced Software Development Lifecycle 🚀

Welcome to the official repository for **SmartSDLC**, an AI-powered Gradio application that automates key phases of the Software Development Lifecycle (SDLC). Powered by IBM Granite AI and Python, SmartSDLC enables developers to convert raw requirements into structured, production-ready software artifacts with ease.

---

## 🔍 Overview

SmartSDLC streamlines software engineering tasks such as:
- Requirement classification
- Code generation
- Bug fixing
- Test case creation
- Code summarization
- Real-time AI chatbot support

All features are integrated into a modular, user-friendly Gradio interface hosted via Google Colab.

---

## 📽 Live Demo

▶️ [Run SmartSDLC on Google Colab](https://drive.google.com/file/d/1Mz0vxiBIaC5eYsgmS9didfk1GCYbItHp/view)  
_Replace with your actual Colab notebook URL_

---

## 🧠 AI Model

- **IBM Granite 3.3-2B Instruct** (via Hugging Face)
- Handles NLP tasks like classification, generation, bug fixing, summarization, and Q&A.

---

## 🛠️ Tech Stack

| Component       | Technology                          |
|----------------|--------------------------------------|
| Frontend        | Gradio, Custom CSS                  |
| Backend         | Python, PyPDF2, Transformers        |
| AI Model        | IBM Watsonx Granite via Hugging Face|
| Platform        | Google Colab                        |
| Testing         | Pytest, Manual Functional Testing   |

---

## 📂 Project Structure

```

SmartSDLC/
├── app/
│   ├── main.py                # Main interface
│   ├── modules/               # Functional modules
│   │   ├── classifier.py
│   │   ├── generator.py
│   │   ├── bug\_fixer.py
│   │   ├── tester.py
│   │   ├── summarizer.py
│   │   └── chatbot.py
├── assets/
│   └── style.css              # Gradio UI custom styling
├── sample\_docs/
│   └── requirements\_sample.pdf
├── test/
│   └── test\_cases.py
├── requirements.txt
└── README.md

````

---

## 🚀 How to Use

### 📌 Run on Google Colab (Recommended)

1. Open the demo link above
2. Follow cell-by-cell instructions to run all modules interactively

### 💻 Run Locally

```bash
git clone https://github.com/cherry-12345/SmartSDLC-AI-Enhanced-Software-Development-Lifecycle.git
cd SmartSDLC-AI-Enhanced-Software-Development-Lifecycle
pip install -r requirements.txt
python app/main.py
````

---

## ✅ Modules & Capabilities

| Module                 | Input                       | Output                      |
| ---------------------- | --------------------------- | --------------------------- |
| Requirement Classifier | PDF File                    | Structured SDLC text        |
| Code Generator         | Prompt (e.g., “login form”) | Python code                 |
| Bug Fixer              | Faulty Python code          | Fixed version + explanation |
| Test Generator         | Python function             | Pytest-based unit tests     |
| Code Summarizer        | Python snippet              | Natural language summary    |
| Chatbot Assistant      | Text question               | AI-generated guidance       |

---

## 📊 Performance Highlights

* ⚡ Fast response: 2–4 seconds per module
* 🧠 Memory efficient: \~1.3 GB on Google Colab
* ✅ Manual testing completed for all 6 modules
* 🔒 Handles invalid inputs gracefully

---

## 🧠 Future Enhancements

* 🔗 GitHub integration for auto commits, issue tracking
* 👥 Real-time multi-user collaboration
* 🏥 Domain-tuned model for industry-specific accuracy
* ☁️ Full-stack cloud deployment with CI/CD pipeline
* 📊 Dashboards for analytics and insights

---

## 👥 Team

**Team Name:** Team Innovators
**Team ID:** LTVIP2025TMID31167
**Institution:** G. Pullaiah College of Engineering and Technology

* 👩‍💻 **C. Keerthana Kiran** – SDLC architecture, classifier, test case generator, bug fixer, UI design
* 👨‍💻 **Charan Katkam** – Code generator, code summarizer, chatbot development, documentation

---

## 📎 Important Links

* 🔗 GitHub Repo: [SmartSDLC on GitHub]*(https://github.com/cherry-12345/SmartSDLC-AI-Enhanced-Software-Development-Lifecycle)*
* 🔗 Live Colab Demo: *Insert your Colab link here*

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

---

## 🙌 Contributions

Contributions are welcome!
Feel free to fork the repository, create a new branch, and submit a pull request.

---

```
Code Smarter, Build Faster — Empowering Development with AI

```

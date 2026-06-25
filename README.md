# 🔬 ResearchMind – AI Multi-Agent Research Assistant

ResearchMind is an AI-powered Multi-Agent Research Assistant that automates the research process using LangChain, Groq LLM, Tavily Search, BeautifulSoup, and Streamlit.

Instead of relying on a single AI model, ResearchMind uses a pipeline of specialized AI agents that collaborate to search the web, extract detailed information, generate a structured research report, and critically review the final output.

---

## 🚀 Features

* 🔍 AI-powered Web Search using Tavily
* 📄 Automatic Web Scraping with BeautifulSoup
* 🤖 Multi-Agent Architecture
* ✍️ AI Research Report Generation
* 🧐 Automated Report Review & Scoring
* 🎨 Modern Streamlit User Interface
* 📥 Download Research Report as Markdown
* ⚡ Fast inference using Groq Llama-3.3-70B

---

## 🏗️ System Workflow

```text
                User Topic
                     │
                     ▼
             🔍 Search Agent
                     │
                     ▼
             📄 Reader Agent
          (Scrapes Top Website)
                     │
                     ▼
            ✍️ Writer Chain
       (Generates Research Report)
                     │
                     ▼
            🧐 Critic Chain
     (Reviews & Scores the Report)
                     │
                     ▼
           Final Research Report
```

---

## 🛠️ Tech Stack

| Technology    | Purpose               |
| ------------- | --------------------- |
| Python        | Programming Language  |
| Streamlit     | Frontend UI           |
| LangChain     | Agent Framework       |
| Groq          | Large Language Model  |
| Tavily API    | Web Search            |
| BeautifulSoup | Web Scraping          |
| Requests      | HTTP Requests         |
| python-dotenv | Environment Variables |

---

## 📂 Project Structure

```text
ResearchMind/
│
├── app.py                 # Streamlit UI
├── agents.py              # AI agents & prompt chains
├── tools.py               # Search & scraping tools
├── pipeline.py            # Research pipeline
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/ResearchMind.git

cd ResearchMind
```

---

### 2. Create Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 🧠 Research Pipeline

### Step 1 — Search Agent

Searches the web for recent and reliable information related to the given topic.

### Step 2 — Reader Agent

Extracts the first relevant URL and scrapes its content for deeper information.

### Step 3 — Writer Chain

Combines search results and scraped content to generate a detailed research report including:

* Introduction
* Key Findings
* Conclusion
* Sources

### Step 4 — Critic Chain

Reviews the generated report and provides:

* Score (/10)
* Strengths
* Areas for Improvement
* Final Verdict

---

## 📊 Example Research Topics

* Artificial Intelligence in Healthcare
* Future of Quantum Computing
* Fusion Energy
* CRISPR Gene Editing
* Large Language Models
* Climate Change Technologies
* Renewable Energy
* Cyber Security Trends
* Space Exploration
* Robotics

---

## 🎯 Use Cases

* Academic Research
* Literature Review
* Technical Documentation
* Market Research
* Industry Analysis
* Technology Comparison
* Student Projects
* Content Research

---

## 📥 Output

ResearchMind generates:

* ✅ Detailed Research Report
* ✅ Sources Used
* ✅ Critic Feedback
* ✅ Downloadable Markdown Report

---

## 🔮 Future Improvements

* PDF Export
* Citation Generation (APA/IEEE)
* Multi-source Verification
* RAG Integration
* Vector Database Support
* Human-in-the-Loop Review
* Multi-LLM Support (Gemini, Claude, OpenAI)

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sharvatosh Pandey**

B.Tech Computer Science Engineering

Passionate about Artificial Intelligence, Generative AI, Multi-Agent Systems, Machine Learning, and Full Stack Development.

GitHub: https://github.com/SharvatoshPandey21

---

⭐ If you found this project useful, consider giving it a star on GitHub!

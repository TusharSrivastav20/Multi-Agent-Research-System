# Multi-Agent Research System

A multi-agent AI research system built with **Python, LangChain, and Mistral AI** that automates the process of researching a given topic and generating a structured research report.

The system uses specialized agents for different tasks. The **Search Agent** gathers relevant information from the web using Tavily, while the **Reader Agent** extracts deeper content from selected webpages. The collected information is then passed to the **Writer** to generate a research report, and the **Critic** reviews the report and provides feedback.

### Pipeline

```text
Research Topic
      ↓
Search Agent
      ↓
Reader Agent
      ↓
Writer
      ↓
Critic
      ↓
Final Report
```

### Features

* 🔍 Web research using Tavily
* 📄 Webpage content extraction
* ✍️ Automated research report generation
* 🧐 AI-based report evaluation
* 🖥️ Interactive Streamlit interface

### Tech Stack

**Python · LangChain · Mistral AI · Tavily · Streamlit · BeautifulSoup · Requests**

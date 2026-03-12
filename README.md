<div align="center">

# Kevin Huang · AI Engineer & Developer

*Building intelligent systems that learn, reason, and create*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevin-mlop-ml/)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white)](https://github.com/kaizermm)

</div>

---

## 👨‍💻 About Me

Hey there! I'm Kevin Huang — an AI Engineer passionate about building real-world AI applications that solve meaningful problems. I specialize in **LLM integration**, **computer vision**, and **end-to-end ML pipelines**, turning cutting-edge research into production-ready tools.

> *"The goal is not to build AI that replaces humans, but AI that amplifies what humans can do."*

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td><b>AI / ML</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white"/>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>LLMs & GenAI</b></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white"/>
      <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black"/>
    </td>
  </tr>
  <tr>
    <td><b>Data & Databases</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td><b>Tools & Platforms</b></td>
    <td>
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
      <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white"/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 📚 [Shelf Scanner](https://github.com/kaizermm/shelf-scanner.git)
> **Full-stack multi-agent AI app for personalised book recommendations**

A production-style AI application that scans a photo of any bookshelf and returns personalised reading recommendations. Built on a three-agent pipeline orchestrated via n8n, powered by the Claude API, and backed by PostgreSQL — with no user accounts required.

**How it works:**
- 👁️ **Vision Agent** — Claude reads a shelf photo and extracts every visible book title and author using multimodal AI
- 📖 **Enrichment Agent** — A second Claude call adds genre, themes, and descriptions to each book found
- 🎯 **Recommendation Agent** — A third Claude call ranks recommendations based on the user's saved preferences and reading history (RAG pattern)

**Key Engineering Highlights:**
- Multi-agent orchestration with separation of concerns across three specialised LLM calls
- RAG pattern: user preferences and reading history retrieved from PostgreSQL and injected into prompts at runtime
- SHA-256 image hashing for deduplication — skips the full AI pipeline if the same shelf was scanned before
- Device-based sessions via HTTP cookies — full personalisation with zero login friction
- React → Express → n8n → Claude API → PostgreSQL full-stack data flow

`Claude API` `Multi-Agent AI` `RAG` `Computer Vision` `n8n` `PostgreSQL` `React` `Express`

---

### 🔍 [Resume Job Matcher](https://github.com/kaizermm/resume_job_matcher.git)
> **AI-powered resume and job description matching engine**

An intelligent tool that uses NLP and large language models to analyze resumes against job postings — scoring compatibility, identifying skill gaps, and surfacing the best-fit opportunities.

**Key Features:**
- Semantic similarity scoring with transformer models
- Skills gap analysis and keyword extraction
- Structured JSON output via prompt engineering for reliable parsing

`Python` `LLMs` `NLP` `Transformers` `Prompt Engineering`

---

## 💡 What I'm Focused On

- 🤖 Building LLM-powered applications with RAG and agent frameworks
- 👁️ Exploring multimodal AI — combining vision and language models
- 📐 Making AI systems reliable, interpretable, and production-ready
- 🛠️ Contributing to open-source AI tooling

---

## 📬 Get in Touch

Have a project idea, collaboration opportunity, or just want to talk AI? Let's connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/kevin-mlop-ml/)





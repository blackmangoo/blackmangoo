<div align="center">

<img src="assets/banner.png" alt="AI/ML Engineer Banner" width="100%" style="border-radius: 12px; margin-bottom: 20px;" />

<img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=700&size=32&duration=3000&pause=1000&color=00E5FF&center=true&vCenter=true&width=800&height=60&lines=Hi%2C+I'm+blackmangoo+👋;AI%2FML+Engineer;Building+Deployable+AI+Systems;Full-Stack+%2B+AI+Products" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=blackmangoo&color=00E5FF&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />

<br/><br/>

**I am an AI/ML Engineer and final-semester BS Artificial Intelligence student at FAST-NUCES, focused on building deployable AI systems that combine strong model development with clean, usable product interfaces.**

My work spans **Computer Vision, RAG pipelines, LLM applications, NLP systems, FastAPI backends, Supabase/PostgreSQL databases, Streamlit dashboards, and full-stack AI products**.

*Currently open to Summer 2026 AI/ML Engineering and Full-Stack Software Development opportunities.*

</div>

---

## 🛠️ Tech Stack & Skills

<div align="center">
  <table style="border: none;">
    <tr>
      <td align="center" width="50%">
        <b>AI / Machine Learning</b><br/><br/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
        <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
        <img src="https://img.shields.io/badge/HuggingFace-FF9D00?style=for-the-badge&logo=huggingface&logoColor=white" />
        <img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white" />
      </td>
      <td align="center" width="50%">
        <b>Backend / Full-Stack / DB</b><br/><br/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
        <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
      </td>
    </tr>
  </table>
</div>

---

## 🚀 Flagship Project

### 🚘 OmniDrive AI — Intelligent Automotive Diagnostic Ecosystem

> **My Final Year Project:** An end-to-end automotive AI platform combining computer vision, backend APIs, mobile engineering, diagnostics, and marketplace workflows.
> 
> **Core Stack:** `Flutter` `FastAPI` `YOLO11-Large` `Supabase` `Firebase` `Sensor Fusion` `OBD-II`

**Key Highlights:**
- 🎯 Trained and integrated a **YOLO11-Large** classifier for 50 car-part classes using 26,820 images.
- ⚡ Served top-5 predictions through a high-performance **FastAPI** `/predict` endpoint.
- 🗄️ Managed scan history and structured user data securely in **Supabase**.
- ⏱️ Engineered GPS/IMU-based performance testing for 0–60, 0–100 km/h, quarter-mile, and braking metrics.
- 🛒 Architected complete marketplace flows for customers, vendors, riders, and admins.

<details>
<summary><b>View Architecture Flowchart</b></summary>
<br/>

```mermaid
flowchart TD
    A[📱 Flutter App] -->|Sends Image / Data| B[⚙️ FastAPI Backend]
    B -->|Predicts Part| C[🧠 YOLO11 Model]
    C -.->|Returns Class| B
    B -->|Saves Result| D[(🗄️ Supabase)]
    D --> E[📊 User Dashboard]
    A -->|Tracks| F[📍 GPS/IMU]
    F --> G[⏱️ Performance Testing]
```

</details>

---

## 💻 Featured AI/ML Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🌿 Serene — AI Wellness Companion</h3>
      <p>Empathy-driven mental health support chatbot with fine-tuning, emotion detection, retrieval, memory, and safety handling.</p>
      <b>Stack:</b> <code>GPT-Neo</code> <code>LoRA</code> <code>DistilRoBERTa</code> <code>FAISS</code> <code>Supabase</code>
      <hr>
      <ul>
        <li>Fine-tuned <b>GPT-Neo-125M</b> with LoRA.</li>
        <li>Local emotion detection & FAISS-based wellness retrieval.</li>
        <li>Supabase conversation memory & Crisis keyword overrides.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🏡 Luxe Estate — House Price Regression</h3>
      <p>Big-data regression pipeline for housing price prediction using optimized ML workflows and a usable estimator interface.</p>
      <b>Stack:</b> <code>XGBoost</code> <code>Scikit-learn</code> <code>Pandas</code> <code>Streamlit</code> <code>Docker</code>
      <hr>
      <ul>
        <li>Expanded 1M+ row housing dataset with memory downcasting.</li>
        <li>Advanced feature engineering pipeline.</li>
        <li>Optimized XGBoost training paired with Streamlit UI.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📄 DocuMind — Context-Aware RAG</h3>
      <p>Document-grounded chatbot using embeddings, vector search, memory, and local LLM inference.</p>
      <b>Stack:</b> <code>LangChain</code> <code>FAISS</code> <code>MiniLM</code> <code>Hugging Face</code> <code>Streamlit</code>
      <hr>
      <ul>
        <li>Intelligent document chunking and MiniLM embeddings.</li>
        <li>FAISS top-k retrieval.</li>
        <li>LangChain memory for grounded contextual generation.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>📰 NewsLens and TicketIQ</h3>
      <p>Applied NLP systems covering BERT fine-tuning and zero-shot/few-shot ticket classification.</p>
      <b>Stack:</b> <code>BERT</code> <code>BART-large-MNLI</code> <code>Hugging Face</code>
      <hr>
      <ul>
        <li>Fine-tuned BERT on AG News achieving 94% test accuracy.</li>
        <li>Built support-ticket auto-tagging with BART-large-MNLI.</li>
        <li>Implemented both zero-shot and few-shot paradigms.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 💼 Experience

- **AI/ML Engineering Intern** @ *DevelopersHub Corporation*
  > Architected and deployed applied AI systems utilizing LLMs, RAG techniques, NLP classification, structured regression models, and Streamlit-based web integrations.
  
- **AI Developer Intern** @ *Nexium*
  > Spearheaded full-stack AI applications integrating React, Next.js, and Supabase. Orchestrated complex n8n workflows and tapped into the Gemini API for generative AI capabilities.
  
- **Teaching Assistant (Programming Fundamentals)** @ *FAST-NUCES*
  > Guided and mentored students in C++ programming fundamentals, rigorous debugging, core logic building, and scalable project development.

---

## 📊 GitHub Activity & Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=blackmangoo&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=blackmangoo&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" width="48%" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=blackmangoo&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Langs" width="48%" />
</div>

### 🐍 Contribution Grid

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/blackmangoo/blackmangoo/output/dist/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/blackmangoo/blackmangoo/output/dist/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/blackmangoo/blackmangoo/output/dist/github-contribution-grid-snake.svg">
  </picture>
</div>

---

## 📫 Let's Connect

<div align="center">
  <a href="https://linkedin.com/in/yourprofile">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:your.email@example.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/blackmangoo">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

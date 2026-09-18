# Hi there! 👋

Welcome to my GitHub profile! I'm **Dibyanshi Singh**, a Data Analyst and Developer passionate about leveraging data and technology to solve real-world problems. From building interactive dashboards to predictive models, I love crafting innovative solutions that make a difference.

---

# About Me

**GenAI Engineer.** I build agentic systems for domains where a wrong answer has consequences — and the eval infrastructure that proves they behave.

The thread across my work is shrinking the surface area the model is trusted with. A tool-calling loop over deterministic Python beats RAG-over-everything when the answer is a database read. An LLM that discovers a UI flow once and emits a typed, versioned artifact beats an LLM in the replay path forever. Every tool returns a fixed status — `ok`, `not_found`, `rejected`, `unavailable` — so the system can tell "no such account" apart from "I couldn't check," and the prompt mandates a specific action for each rather than leaving it to the model's judgment. Restricted categories route to an escalation call, not to the model's opinion about what it should say.

Evals are where I spend most of my time, because agent behavior isn't knowable by inspection. Building a 36-case suite that gates every change taught me more than the agent did: that an adversarial prompt can defeat the mandated escalation *action* while the content guardrail still holds, and that those are different failures needing different fixes. That a safety case passing 3 of 5 identical reruns at `temperature=0` is flaky, not fixed — and a single green run would have shipped it. That `escalate()` could fail with nothing underneath it, the safety valve breaking alongside whatever it was meant to rescue, which only chaos testing surfaced. One case in that suite is still red on purpose; prompt-patching it green would have hidden a real distinction.

Working in Python and TypeScript across LangGraph, OpenAI and Anthropic APIs, structured outputs with Pydantic, BM25 and hybrid retrieval, and Playwright for browser agents.

---

## 🚀 Tech Stack

### AI & LLM Engineering
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-0F9D58?style=flat&logoColor=white)
![Multi--Agent Systems](https://img.shields.io/badge/Multi--Agent%20Systems-6E4AFF?style=flat&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)

### Programming Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

### Frameworks & Libraries
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/-jQuery-0769AD?style=flat&logo=jquery&logoColor=white)
![AJAX](https://img.shields.io/badge/-AJAX-0052CC?style=flat&logo=atlassian&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

### Database Management
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

### Data Visualization & Analytics
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/-PowerBI-F2C811?style=flat&logo=power-bi&logoColor=black)
![Excel](https://img.shields.io/badge/-MS_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

### Cloud Platforms
![Azure](https://img.shields.io/badge/-Microsoft_Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/-Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat&logo=amazons3&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

### Developer Tools
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/-Azure_DevOps-0078D7?style=flat&logo=azure-devops&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

### Data Science & ETL Processes
![REST APIs](https://img.shields.io/badge/-REST_APIs-0052CC?style=flat&logo=api&logoColor=white)
![ETL](https://img.shields.io/badge/-ETL-FF4B4B?style=flat&logo=etl&logoColor=white)
![Image Processing](https://img.shields.io/badge/-Image_Processing-FFA500?style=flat&logo=opencv&logoColor=white)

### Operating Systems
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/-Windows-0078D6?style=flat&logo=windows&logoColor=white)
![MacOS](https://img.shields.io/badge/-MacOS-000000?style=flat&logo=apple&logoColor=white)

---

## 📂 Featured Projects

### 1. [Riverside Support Agent](https://github.com/Dibyanshi26/riverside-support-agent)

A tool-calling support agent for a credit union member-service line, built around the question that actually matters in regulated domains: not whether an LLM *can* answer banking questions, but whether you can prove it reliably refuses the ones it shouldn't.

A 36-case eval suite gates every change, checking grounding, restricted-category enforcement, and escalation behavior. Chaos testing surfaced the sharpest bug — `escalate()` could itself fail with nothing underneath it, the safety valve failing alongside whatever it was meant to rescue. One adversarial case is left **failing on purpose**, because prompt-patching it green would have hidden a real distinction: the content guardrail holds, but the mandated escalation action doesn't.

**Python · OpenAI · BM25 retrieval · SQLite · Deterministic eval harness**

### 2. [AI Invoice Processing System](https://github.com/Dibyanshi26/ai-invoice-processing-agents)

A five-agent LangGraph pipeline automating accounts payable end to end — ingestion across five file formats, validation against live inventory and vendor records, an approval decision with self-critique and confidence scoring, and payment execution. A separate fraud agent scores each invoice against eight pattern heuristics plus historical price deviation.

**LangGraph · FastAPI · Next.js · Pydantic · SQLite**

### 3. [AI Email Intelligence Agent](https://github.com/Dibyanshi26/ai-email-intelligence-agent)

An n8n workflow that turns an inbox into structured operational data — Google Gemini classifies each incoming message by category, priority, and required action, extracts deadlines and a summary, and logs everything to Sheets as a searchable triage dashboard.

**n8n · Google Gemini · Gmail API · Google Sheets · Prompt engineering**

### 4. [Neo4j vs Relational Databases](https://github.com/Dibyanshi26/Neo4jvsRelationalDB)
A comparative analysis of **graph databases** and **relational databases**, exploring performance differences using large datasets and **Google Scholar**.

---

## 📊 GitHub Analytics
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Dibyanshi26&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dibyanshi26&layout=compact&theme=radical)

---

## 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dibyanshisingh)  
[![Portfolio](https://img.shields.io/badge/Portfolio-24292E?style=for-the-badge&logo=githubpages&logoColor=white)](https://dibyanshioffice.wixsite.com/my-site)


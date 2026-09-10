[LinkedIn](https://www.linkedin.com/in/jordimassaguerpla/)

# AI Engineering Projects

As a Software Engineer at SUSE and Associate Professor at Universitat Rovira i Virgili (URV), my work focuses on **AI Engineering, Agentic Systems, Generative UI, Infrastructure Management, and the integration of LLMs into real-world software systems**.

Several projects are developed in collaboration with or inspired by real-world open-source ecosystems such as Uyuni, Trento and MONAI.

## Undergraduate Projects (URV ETSE)

I supervise undergraduate projects in **Artificial Intelligence and AI Engineering**, with a strong focus on learning by building real systems.

Projects typically combine LLMs and agents with traditional Machine Learning, software engineering, frontend/backend development, evaluation, security and real-world constraints.

The objective is not only to build something that works, but to **experiment, measure, understand the trade-offs and deliver a complete open-source project**.

### 🚀 2026 Projects

#### Linux Incident Diagnosis Assistant with AI Agents

Student: Jordi Grau Valls
Study: Degree in Computer Engineering
Year: 2026

AI agent for diagnosing Linux system incidents using real system information and tools such as `journalctl`, `systemctl`, disk, memory and process inspection.

The project places particular emphasis on **security and safe agentic execution**, including restricted permissions, evidence-based diagnoses, prompt injection testing and human validation.

---

#### Generative UI and MCP for Infrastructure Management

Student: Aleix Chillida Subirats
Study: Degree in Computer Engineering
Year: 2026

Exploration and comparison of different **Generative UI architectures** for interacting with Linux infrastructure through the Model Context Protocol (MCP).

The project compares approaches where the agent, the LLM or deterministic components decide how operational information should be visualized, using technologies such as AG-UI, CopilotKit and MCP-based UI components.

---

#### Context-Aware RAG with Different Confidentiality Levels

Student: AFC
Study: Degree in Computer Engineering
Year: 2026

RAG-based system designed to retrieve and generate answers while respecting **different levels of information confidentiality and user authorization**.

The project explores how access control and contextual information can be incorporated into LLM-based retrieval systems.

---

#### AI-Powered Personal Fitness Coach

Student: Veronika HJ
Study: Degree in Computer Engineering
Year: 2026

Full-stack AI fitness application combining **LLMs, traditional Machine Learning and recommender systems** to generate personalized training recommendations.

The project includes frontend/backend development, UX/UI design, model evaluation, synthetic datasets and comparison between different recommendation approaches.

---

#### Conversational Movie Recommender with Social and Feedback Signals

Student: Aina Rovira Figuerola
Study: Degree in Computer Engineering
Year: 2026

Conversational movie recommendation system combining **LLMs, collaborative filtering, user feedback and social information**.

The project explores how conversational context and user preferences can complement traditional recommender systems, using datasets such as MovieLens and TMDB and evaluating the different recommendation strategies.

---

#### Explainable AI Platform for Clinical Risk Assessment

Student: Marc Roda
Study: Degree in Computer Engineering
Year: 2026

AI Engineering platform for evaluating clinical risk models, developed from a healthcare hackathon use case.

Rather than focusing only on predictive performance, the system provides infrastructure for **model evaluation, SHAP-based explainability, clinician feedback and local deployment**, combining traditional Machine Learning with LLM-generated explanations.

The project was developed with feedback from healthcare AI professionals and with particular attention to the constraints of deploying AI in clinical environments.

### 📦 Previous Projects

#### Agentic System for an Online Customer Center

Student: AEP
Study: Degree in Web and Mobile Application Development Techniques
Year: 2025

Multi-agent system using LLMs and RAG for customer interaction and task execution.

---

#### Artificial Intelligence for Document Management in the Insurance Sector

Student: NCR
Study: Degree in Computer Engineering
Year: 2025

AI-based system for document classification and retrieval.

---

#### Federated Learning in Medical Imaging (MONAI)

Student: GPG
Study: Degree in Computer Engineering
Year: 2025

Distributed machine learning applied to healthcare data.

---

#### Football Score and Match Statistics Predictor

Student: JGB
Study: Degree in Computer Engineering
Year: 2025

Machine learning system for prediction using statistical features.

---

#### Creating a Chatbot using a Retrieval Augmented Generation Architecture

Student: Albert Garcia Bernat
Study: Degree in Computer Engineering
Year: 2024

RAG-based conversational system.

---

#### Automation of Deployment of AI Models with MONAI on AWS

Student: Tarek Ben Hamdouch
Study: Double Degree in Computer Engineering and Biotechnology
Year: 2024

End-to-end ML deployment in cloud infrastructure.

---

#### Call Service to Automate Reservations

Student: Guillem Rodríguez Mitjana
Study: Degree in Computer Engineering
Year: 2025

Conversational AI system for automating booking processes.

---

#### Design and Development of a Fitness Application with AI

Student: Alejandro Trujillo Ortiz
Study: Degree in Computer Engineering
Year: 2024

AI-based recommendation system.

---

## ⚙️ Infrastructure & AI Systems

### MCP Server for Infrastructure Management (Uyuni)

https://github.com/mcp-server-uyuni

Development of an MCP server enabling integration between infrastructure management systems (Uyuni/SUSE Manager) and AI-driven applications.

Focus on:

* exposing infrastructure operations as tools for LLMs and agents
* enabling natural-language interaction with system administration tasks
* supporting agentic architectures
* exploring Generative UI for AI-driven infrastructure management

This work provides the technical foundation for several of the AI Engineering projects described above.

---

## 📚 Publications & Research

### Publications

**Challenges in the AI-Driven Infrastructure Management Era**

Authors: Antonio Gámez-Díaz, Jordi Massaguer Pla
Conference: Jornadas de Ciencia e Ingeniería de Servicios (JCIS 2026)

Industrial experience report based on the development and deployment of MCP servers for infrastructure management platforms such as Uyuni and Trento.

The paper discusses key governance challenges that emerge when LLMs interact with operational systems through machine-facing APIs, including:

* API governance and rate limiting
* reviewable execution plans for AI agents
* scoped authorization and auditability

Paper:
https://hdl.handle.net/11705/JCIS/2026/43

---

### Google Summer of Code

#### AI-Powered Intelligent Monitoring and Root Cause Analysis for Uyuni

https://summerofcode.withgoogle.com/programs/2026/projects/IkZoUdVT

AI agent that correlates Prometheus metrics with live system diagnostics to detect anomalies, explain root causes and provide actionable remediation recommendations for Linux infrastructure.

---

#### AI-Driven Test Selection in Uyuni's Pull Request Acceptance Tests

https://summerofcode.withgoogle.com/programs/2025/projects/2mlAbkgB

Machine Learning applied to optimize testing workflows in a real-world DevOps environment.

---

### SUSE Hackweek Projects

**Package MONAI Machine Learning Models for Medical Applications**
https://hackweek.opensuse.org/24/projects/package-monai-machine-learning-models-for-medical-applications

**Hack on MONAI (Medical Open Network for Artificial Intelligence)**
https://hackweek.opensuse.org/24/projects/hack-on-project-monai-medical-open-network-for-artificial-intelligence

**Chest X-Ray Medical Diagnosis with Deep Learning and Javascript**
https://hackweek.opensuse.org/24/projects/chest-x-ray-medical-diagnosis-with-deep-learning-and-javascript

Applied experimentation with medical AI, deployment and integration.

---

## Academic Activities

* Bachelor's Thesis Supervisor – AI Engineering
* Member of Bachelor's Thesis Evaluation Committees
* Laboratory Instructor – Network and Systems Management

## Research & Engineering Interests

* AI Engineering
* Agentic Systems
* Model Context Protocol (MCP)
* Generative UI
* Infrastructure Automation
* Human-in-the-Loop AI
* AI Evaluation
* Medical AI
* Explainable AI

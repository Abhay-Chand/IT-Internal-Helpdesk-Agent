# Enterprise IT Support Agentic RAG Copilot

Hey everyone! This repository contains a production-ready, end-to-end Agentic RAG system designed to fix IT support bottlenecks in enterprise environments. 

##  The Problem
Employees waste a ton of time filing repetitive support tickets because they can never find the right answer buried inside internal company docs. Traditional keyword searches just dump a mountain of irrelevant documents on them, and standard chatbots usually end up guessing or outright hallucinating answers.

##  The Solution
Instead of a basic RAG pipeline, this project uses an [Agentic RAG](https://www.youtube.com/hashtag/rag) workflow with an [intelligent router](https://www.youtube.com/hashtag/aiagents). It automatically pulls and grades data from a [Pinecone](https://www.youtube.com/hashtag/vectordatabase) knowledge base, checks if the evidence is actually strong enough, and handles fallback web searches with self-correction loops so you get fully trusted answers backed by actual citations.

##  Key Features
* **Smart Routing:** Figures out right away whether a question needs internal documentation or an external web search.
* **Grading & Self-Correction:** Evaluates retrieved evidence on the fly and rewrites queries if the first attempt isn't good enough.
* **Verified Sources:** Pulls trusted internal docs and external links so teams never have to deal with AI hallucinations.
* **Cloud Ready:** Fully containerized for smooth deployment and CI/CD workflows.

##  Tech Stack
* **Orchestration:** Python, LangGraph
* **Vector Database:** [Pinecone](https://www.youtube.com/hashtag/vectordatabase)
* **APIs & Models:** OpenAI, Tavily
* **Deployment:** Docker, DigitalOcean

##  Quick Start

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/entbappy/Enterprise-IT-Support-Agentic-RAG-Copilot.git](https://github.com/entbappy/Enterprise-IT-Support-Agentic-RAG-Copilot.git)
   cd Enterprise-IT-Support-Agentic-RAG-Copilot

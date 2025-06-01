# HadaForge

**HadaForge** is a modular AI-agent operating framework that empowers solopreneurs to build and manage intelligent agents like elite teammates — amplifying human potential through collaborative design, automation, and strategic clarity.

> Inspired by the folded patterns of *hada* steel and the art of *alchemy*, this project is where agents are forged to do work that transforms both people and outcomes.

---

## 🚀 Vision

HadaForge is designed for the long game:

- **Base Agent Kit**  
  A domain-agnostic, developer-friendly framework for defining, deploying, and evolving AI agents across use cases.

- **Class-A Agent Collaboration**  
  Each agent is treated like a high-performing hire: equipped with responsibilities, memory, tools, and the ability to collaborate.

- **Solopreneur-Ready**  
  Designed for founders, builders, and creators who want to multiply their capabilities — without scaling headcount.

- **Composable Architecture**  
  Agents, tools, memory, and workflows are fully modular and built for rapid iteration.

---

## 📂 Repository Structure (Initial)
hadaforge/
├── agents/ # Config files and logic for each agent
├── core/ # Core framework (memory, tools, orchestrator)
├── mcp/ # Master Control Program logic
├── public/ # Frontend assets (if applicable)
├── .env # Environment configuration (local API keys, etc.)
├── README.md # Project overview (you are here)
├── run_docker.py # Entrypoint for Docker setup
└── requirements.txt # Python dependencies

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/hadaforge.git
cd hadaforge

### 2. Set Up Your Environment
Create a .env file based on the sample below and add your API keys.

bash
Copy
Edit
cp .env.example .env

### 3. Run the Agent System
bash
Copy
Edit
python run_docker.py
Once running, access the system via http://localhost:8501

⚙️ .env Example
Create your own .env file using this structure:

ini
Copy
Edit
OPENAI_API_KEY=your-openai-api-key
SUPABASE_URL=your-supabase-url
SUPABASE_KEY=your-supabase-service-role-key
PINECONE_API_KEY=your-pinecone-key
PINECONE_ENV=your-pinecone-environment
PINECONE_INDEX_NAME=your-pinecone-index-name
Only include the services you actually use — unused keys can be omitted.

## 📘 Key Documents
HadaForge Master Map – Vision, structure, long-game priorities

PRB.md – Fast-loading snapshot of current agent state, system config, and progress

## 🧭 Guiding Principles
Democratize opportunity through intelligent automation

Design for emergence — let agent collaboration produce new value

Build the forge, not the blade — the system for making systems

## 🧩 Future Features
Agent onboarding and lifecycle workflows

Role-aware agent-to-agent collaboration

Dynamic toolchain loading

UX for managing memory, goals, and dependencies

Plugin marketplace for agent extensions

## 🔒 License
TBD — Open-source or hybrid model to be determined based on strategic goals.

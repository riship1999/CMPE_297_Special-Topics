# AI Agent Development Kit (ADK) Assignment

This repository contains my work for the **AI Agents with Google ADK** course assignment.  
It includes implementations of the official ADK codelabs (**Part A**) and one custom agent application from hackathon references (**Part B**).  

---

## 📌 Assignment Overview

### **Part A – Implement ADK Codelabs**

#### 1. Renovation Agent
- Generates a **house renovation proposal**.  
- Output is stored as a PDF file: `House_renovation_proposal_document_for_user.pdf`.  
- Implements the ADK pipeline for generating structured proposal documents.  

📸 Screenshot:  
![Renovation Agent Screenshot](/screenshots/renovation-agent.png)  

🎥 Video Walkthrough: [YouTube Link](#)  

---

#### 2. Personal Assistant Agent
- Provides **currency exchange conversion**.  
- User can input currency type and amount to get real-time conversion results.  

📸 Screenshot:  
![Personal Assistant Screenshot](/screenshots/personal-assistant.png)  

🎥 Video Walkthrough: [YouTube Link](#)  

---

#### 3. Hotel Agent App (with MCP Toolbox for Databases)
- Backend uses **PostgreSQL on Google Cloud SQL** with mock data.  
- Agent retrieves hotel details (by location & name) via MCP toolbox database connection.  
- Demonstrates **database-augmented AI agent**.  

📸 Screenshot:  
![Hotel Agent Screenshot](/screenshots/hotel-agent.png)  

🎥 Video Walkthrough: [YouTube Link](#)  

---

### **Part B – Hackathon Agent Application**

#### Educational Path Advisor Agent
- Main agent: **Education Coordinator**.  
- Multiple **sub-agents** invoked dynamically based on user queries.  
- Suggests **career options and study paths** based on user preferences.  
- Demonstrates **multi-agent orchestration** with sub-agents in `subagents/` directory.  

📸 Screenshot:  
![Educational Path Advisor Screenshot](/screenshots/education-path-advisor.png)  

🎥 Video Walkthrough: [YouTube Link](#)  

---

## 📂 Directory Structure

```
├── PartA/
│   ├── renovation-agent/
│   │   ├── __init__.py
│   │   ├── agent.py
│   │   └── House_renovation_proposal_document_for_user.pdf
│   │
│   ├── personal-assistant/
│   │   ├── __init__.py
│   │   └── agent.py
│   │
│   └── hotel-agent-app/
│       ├── __init__.py
│       ├── agent.py
│       └── db_config.sql
│
├── PartB/
│   └── education-path-advisor/
│       ├── __init__.py
│       ├── agent.py
│       └── subagents/
│           ├── __init__.py
│           └── *.py   (specialized sub-agents)
│
└── README.md
```

---

## ▶️ Demo Videos

- **Part A**  
  1. Renovation Agent – [YouTube Link](#)  
  2. Personal Assistant Agent – [YouTube Link](#)  
  3. Hotel Agent App – [YouTube Link](#)  

- **Part B**  
  - Educational Path Advisor Agent – [YouTube Link](#)  

---

## ⚙️ Setup & Execution

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. Install dependencies (in Colab or local environment):  
   ```bash
   pip install -r requirements.txt
   ```

3. Run agents:  
   - **Renovation Agent**  
     ```bash
     python PartA/renovation-agent/agent.py
     ```
   - **Personal Assistant Agent**  
     ```bash
     python PartA/personal-assistant/agent.py
     ```
   - **Hotel Agent App** (ensure PostgreSQL DB running with mock schema)  
     ```bash
     python PartA/hotel-agent-app/agent.py
     ```
   - **Educational Path Advisor Agent**  
     ```bash
     python PartB/education-path-advisor/agent.py
     ```

---

## 📚 References

- [From Prototypes to Agents with ADK](https://share.google/SedY3WmkMRCEkJrrA)  
- [Building AI Agents with ADK: Empowering with Tools](https://share.google/2PaSC2sdeHuNqENjq)  
- [Build a Travel Agent using MCP Toolbox + ADK](https://share.google/aTibSpbyEDvVPhIqD)  
- [Awesome ADK Agents (Hackathon Ideas)](https://github.com/Sri-Krishna-V/awesome-adk-agents)  
- [Masterclass Video](https://youtu.be/P4VFL9nIaIA?si=-wpIAXKzxfHiM0ZL)  

---

✅ This repository demonstrates both **codelab implementations** and a **custom multi-agent application**, complete with walkthroughs, outputs, screenshots, and working demos.  

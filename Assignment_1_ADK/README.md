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

🎥 Video Walkthrough: [YouTube Link](https://youtu.be/hGy00UiNG98)  

---

#### 2. Personal Assistant Agent
- Provides **currency exchange conversion**.  
- User can input currency type and amount to get real-time conversion results.  

📸 Screenshots:  
<img width="1366" height="768" alt="ADK_currency" src="https://github.com/user-attachments/assets/07a969af-ecb9-4d63-92f5-4d64539042b8" />
<img width="1366" height="768" alt="ADK_Search_agent" src="https://github.com/user-attachments/assets/1afefe2c-9399-4f49-89f0-45869f4e8782" />

🎥 Video Walkthrough: [YouTube Link](https://youtu.be/bDNht5L5VPU)  

---

#### 3. Hotel Agent App (with MCP Toolbox for Databases)
- Backend uses **PostgreSQL on Google Cloud SQL** with mock data.  
- Agent retrieves hotel details (by location & name) via MCP toolbox database connection.  
- Demonstrates **database-augmented AI agent**.  

📸 Screenshots:  
<img width="1366" height="768" alt="ADK_Travel_1" src="https://github.com/user-attachments/assets/07572909-1737-48f7-b8b5-f4b8e4079992" />
<img width="1366" height="768" alt="ADK_Travel_2" src="https://github.com/user-attachments/assets/98edca1c-c9b6-4cf5-8134-b73bf2a469b0" />
<img width="1366" height="768" alt="MCP_toolbox_ui" src="https://github.com/user-attachments/assets/92ae6ad8-1265-47f2-81a8-07fd61d176f9" />
<img width="1366" height="768" alt="Travel_Hotel_DB" src="https://github.com/user-attachments/assets/c2d127e8-9453-4d83-b66a-28668072ef10" />

🎥 Video Walkthrough: [YouTube Link](https://youtu.be/Jac1_Ml2d_Y)  

---

### **Part B – Hackathon Agent Application**

#### Educational Path Advisor Agent
- Main agent: **Education Coordinator**.  
- Multiple **sub-agents** invoked dynamically based on user queries.  
- Suggests **career options and study paths** based on user preferences.  
- Demonstrates **multi-agent orchestration** with sub-agents in `subagents/` directory.  

📸 Screenshots:  
<img width="1366" height="768" alt="ADK_educational_agent" src="https://github.com/user-attachments/assets/12786c4c-675b-4d0b-a7e9-590ff05023c8" />
<img width="1366" height="768" alt="ADK_Educational_path" src="https://github.com/user-attachments/assets/0811b2c9-9ee4-4300-bd2c-e4d918a72fc9" />


🎥 Video Walkthrough: [YouTube Link](https://youtu.be/92nOtoJ6JlA)  

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
  1. Renovation Agent – [YouTube Link](https://youtu.be/hGy00UiNG98)  
  2. Personal Assistant Agent – [YouTube Link](https://youtu.be/bDNht5L5VPU)  
  3. Hotel Agent App – [YouTube Link](https://youtu.be/Jac1_Ml2d_Y)  

- **Part B**  
  - Educational Path Advisor Agent – [YouTube Link](https://youtu.be/92nOtoJ6JlA)  

---

## ⚙️ Setup & Execution

 Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```


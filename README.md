# AI Job Agent  
📧 Email → 🧠 AI Analysis → 📲 Telegram

> Status: MVP completed | Production-ready personal automation project
> 
  A real-world automation project built to understand and navigate the IT / Cloud job market more effectively.

## 🚩 Problem Statement
Job-related emails from platforms like LinkedIn or StepStone are often:
- Long and unstructured  
- Full of abbreviations and unclear requirements  
- Missing key information (salary, tech stack, seniority)  

As a career-transition candidate, analyzing these emails manually is time-consuming and inefficient.

---

## 💡 Solution
**AI Job Agent** is an automated workflow that:
- Reads incoming job emails
- Extracts and structures key job information
- Translates content into Persian (FA)
- Explains technical & HR abbreviations
- Analyzes required skills and background
- Provides interview preparation insights
- Sends a clear, structured report to Telegram

---

## 🧠 What the Agent Does
- 📥 Reads job-related emails (LinkedIn, StepStone, recruiters)
- 🧾 Extracts key facts (title, company, location, role type)
- 🌍 Bilingual output (English + Persian)
- 🧩 Expands abbreviations (IT / Cloud / HR terms)
- 🎯 Analyzes role requirements & missing skills
- 🗣️ Suggests interview preparation points
- 📊 Recommends whether to apply or not
- 📲 Delivers the report via Telegram (auto-split for message limits)

---

## 🏗️ System Architecture

Gmail Trigger  
→ Email Content Extraction  
→ OpenAI Analysis (custom prompt)  
→ JavaScript Processing (chunking & formatting)  
→ Telegram Bot Delivery  

This ensures reliable automation without manual steps.

---

## ⚙️ Key Technical Decisions
- **n8n** used for visual workflow automation
- **OpenAI** for structured reasoning & translation
- **JavaScript node** to:
  - Split long outputs safely (<1350 chars)
  - Preserve message order
- **Telegram Bot** chosen for instant, mobile-friendly delivery

---

## 🧪 Example Output
Each job email results in:
- Structured sections
- Clear bilingual explanation
- Practical next steps
- Interview-focused insights

(Output screenshots available in Telegram demo)

---

## 🧠 Skills Demonstrated
- Workflow automation (n8n)
- AI prompt engineering
- JavaScript data processing
- API integrations (Gmail, OpenAI, Telegram)
- System thinking & problem decomposition
- Practical IT / Cloud job market understanding

---

## 🔜 Roadmap
- Add job fit scoring based on personal profile
- Store analyzed roles for comparison
- Extend to CV matching & auto-cover-letter drafts

---

## 📎 Project Context
This project is part of my transition into **IT / Cloud / Automation**, focusing on:
- Real-world problems
- Practical AI usage
- End-to-end system building

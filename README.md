🤖 AI Resume Evaluator Agent

An AI-powered Resume Evaluation System that analyzes resumes, scores candidates across defined competency areas, and delivers professional HTML evaluation reports automatically via Email and Telegram.

This project was built to answer a simple but powerful question:

“How does my resume actually look when it’s evaluated?”

Instead of relying on existing resume checkers, I decided to build one from scratch.

🚀 Project Overview

The AI Resume Evaluator Agent simulates a real-world resume screening workflow used in hiring.

What it does:

Accepts resumes via Google Docs

Evaluates them using an AI Agent

Scores candidates using a structured evaluation framework

Generates professionally formatted HTML reports

Sends results via Gmail

Interacts with users through Telegram

Uses Make.com automation and MCP (Model Context Protocol)

This is not just a chatbot — it is a multi-step autonomous AI agent designed to perform a real business task.

🧠 Why This Project Matters

Most resume tools are black boxes.

This project focuses on transparency, structure, and system design, showcasing:

How AI agents reason and follow workflows

How resume evaluation logic can be standardized

How automation replaces repetitive manual screening

Why proper formatting (HTML vs plain text) matters in real systems

🏗️ System Architecture
User → Telegram Bot → AI Agent → Resume Evaluation → HTML Email Report

Key Components:

Telegram Bot – User interaction

AI Resume Evaluator Agent – Resume analysis & scoring

Google Docs – Resume source

HTML Email Generator – Professional report rendering


📊 Evaluation Framework

Each resume is evaluated on a 100-point scale:

Competency Area	Max Score
Relevant Technical Experience	30
Content Curation Experience	30
Project Building	20
Team Leadership Experience	20
Decision Logic

≥ 70 → Move Forward

50–69 → Borderline – Needs Further Evaluation

< 50 → Do Not Move Forward

✉️ Output

The system generates a professional HTML email report containing:

Candidate information

Objective remarks

Strengths & gaps

Score breakdown

Final verdict

Emails are fully styled HTML, not plain text.

🧰 Tech Stack

AI Model: GPT-based agent

Automation: Make.com

Messaging: Telegram Bot API

Email: Gmail (HTML rendering)

Documents: Google Docs

Protocol: MCP (Model Context Protocol)

Output: HTML Email Templates

📁 Repository Only Folder Structure
ai-resume-evaluator/
│
├── agent-prompts/
├── email-templates/
├── screenshots/
├── README.md
└── LICENSE

🔐 Security Notes

No API keys or secrets are included

All credentials are managed securely via Make / MCP

Repository contains only configuration, prompts, and templates

📈 Future Improvements

Resume PDF upload support

Multi-role evaluation (Developer, Designer, PM)

ATS keyword matching

Resume improvement suggestions

PDF export of reports

Recruiter dashboard

🙌 Final Note

This project represents my hands-on learning in:

AI Agents

Workflow automation

System prompts

Real-world AI applications

If you’re reviewing this repository —
thank you for taking the time to explore it.

⭐ Feel free to star the repo or share feedback.

Make.com – Workflow orchestration

MCP (Model Context Protocol) – Unified tool access

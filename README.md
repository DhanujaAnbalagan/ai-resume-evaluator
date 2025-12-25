🤖 AI Resume Evaluator Agent

An AI-powered Resume Evaluation System that analyzes resumes, scores candidates across defined competency areas, and delivers professional HTML evaluation reports automatically via email and Telegram.

This project was built to answer a simple but powerful question:

“How does my resume actually look when it’s evaluated?”

Instead of using existing resume checkers, I built one from scratch.

🚀 Project Overview

The AI Resume Evaluator Agent simulates a real-world resume screening workflow used in hiring:

Accepts resumes via Google Docs

Evaluates them using an AI Agent

Scores candidates using a structured framework

Generates professionally formatted HTML reports

Sends results via Gmail

Interacts with users through Telegram

Uses Make.com automation and MCP (Model Context Protocol)

This is not just a chatbot — it is a multi-step autonomous AI agent designed to perform a real business task.

🧠 Why This Project Matters

Most resume tools are black boxes.
This project focuses on transparency, structure, and system design, showcasing:

How AI agents reason and follow workflows

How hiring evaluation logic can be standardized

How automation replaces repetitive manual screening

How proper formatting (HTML vs plain text) impacts usability

🏗️ System Architecture

User → Telegram Bot → AI Agent → Resume Evaluation → Email Report

Key Components:

Telegram Bot

Entry point for user interaction

Accepts greetings, resume links, and requests

AI Resume Evaluator Agent

Controlled via strict system prompts

Follows a fixed evaluation framework

No free-form responses (deterministic behavior)

Google Docs Integration

Fetches resume content from shared Google Docs links

HTML Email Generator

Produces clean, professional evaluation reports

Ensures proper rendering in Gmail / Outlook

Make.com Automation

Orchestrates the entire workflow

Handles triggers, tool calls, and data routing

MCP (Model Context Protocol)

Unified access to external tools

Cleaner, scalable integration architecture

📊 Evaluation Framework

Each resume is scored out of 100 points:

Competency Area	Max Score
Relevant Technical Experience	30
Content Curation Experience	30
Project Building	20
Team Leadership Experience	20
Decision Logic

≥ 70 → Move Forward

50–69 → Borderline – Needs Further Evaluation

< 50 → Do Not Move Forward

✉️ Output Example

The system generates a professional HTML email report that includes:

Candidate information

Objective remarks

Strengths and gaps

Detailed score breakdown

Final verdict

📌 Unlike plain-text emails, the report is fully styled and recruiter-ready.

🧰 Tech Stack

AI Agent: GPT-based model

Automation: Make.com

Messaging: Telegram Bot API

Email: Gmail (HTML rendering)

Documents: Google Docs

Protocol: MCP (Model Context Protocol)

Frontend (Output): HTML Email Templates

🔐 Security Notes

No API keys or secrets are included

All credentials are managed securely within Make / MCP

Repository contains only configuration, prompts, and templates

📈 Future Improvements

Resume PDF upload support

Multi-role evaluation (Developer, Designer, PM)

ATS keyword matching

Resume improvement suggestions

PDF export of evaluation reports

Dashboard for recruiters

🎯 Who This Project Is For

Engineers learning AI Agents

Automation & no-code enthusiasts

Students curious about real hiring workflows

Recruiters exploring AI-assisted screening

Anyone interested in AI + systems design

🙌 Final Note

This project represents my learning journey into:

AI agents

Workflow automation

System prompts

Real-world AI applications

If you’re reviewing this repo 
thank you for taking the time to explore it.

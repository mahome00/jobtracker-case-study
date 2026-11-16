# JobTracker – Job Search & Application Tracking

JobTracker is a personal project designed to make job searching more efficient by automatically collecting, analyzing, and prioritizing job advertisements based on a candidate's skills and background.

The idea and system architecture are my own, while AI tools have assisted me with the technical implementation and development.

## Why I built it

Manually reviewing hundreds of job advertisements is time-consuming, especially when many positions are not relevant to your qualifications.

I wanted to build a system that could help identify promising opportunities without making the final decision for me.

JobTracker currently manages over 1,200 job advertisements and uses AI to compare job requirements against a structured candidate profile.

## How it works

JobTracker retrieves job advertisements through the Swedish JobTech API and processes them using automated n8n workflows.

Each job is analyzed and assigned one of three classifications:

- **MATCH:** The candidate meets the identified essential requirements.
- **REVIEW:** The position may be relevant, but some requirements are only partially met or require manual assessment.
- **NO_MATCH:** The position has significant gaps compared with the candidate's qualifications.

Jobs are also assigned a priority score to help identify which opportunities to review first.

The classifications are decision-support tools, not final judgments. I review the results myself before deciding whether to apply.

## Features

- Automated job collection and processing
- AI-based requirement analysis and job matching
- Job classification and priority scoring
- Detailed explanations of strengths and qualification gaps
- Job application tracking and follow-up
- AI-assisted CV and cover letter preparation
- Manual review and editing of application documents

## Technology

- **n8n** – Workflow automation
- **PostgreSQL** – Data storage
- **Next.js** – Web application interface
- **Gemini** – Job requirement analysis and classification
- **Claude** – AI-assisted application document generation
- **Ollama / Qwen** – Local language model integration
- **JavaScript, JSON and REST APIs** – Data processing and system integration

## Development approach

I designed the concept, defined the system requirements and planned how the components should work together. I use AI assistants to support implementation, troubleshooting and iterative development.

The project is ongoing and continues to evolve through testing and improvements.

## Screenshots

<img width="2519" height="1304" alt="Screenshot 2026-10-29 180437" src="https://github.com/user-attachments/assets/94a2a841-c644-4921-8812-4bffbd849953" />
<img width="2513" height="1306" alt="Screenshot 2026-11-17 002243" src="https://github.com/user-attachments/assets/9d6b3ec1-e241-41b7-ba59-d20e25cfefe5" />
<img width="2517" height="1306" alt="Screenshot 2026-11-17 002257" src="https://github.com/user-attachments/assets/a2841a55-98ea-45f6-8b7c-a3100b4b9f69" />


The screenshots demonstrate JobTracker's dashboard, AI-based job classification, priority scoring, and detailed assessments of how job requirements match a candidate's qualifications.

## Source code

The complete source code, workflows and configuration are kept private because the system contains personal information and integrations with external services.

This repository serves as a public case study of the project's functionality and architecture.


# Project Instructions: AI-Powered Data Analyst Copilot

## 1. Project Overview
We are building an AI-powered data analysis application that allows users to upload datasets, ask questions in natural language, generate insights, and create visualizations.

## 2. Technology Stack
- Frontend: Lovable (React and TypeScript)
- Backend: Python and FastAPI
- Data Processing: Pandas and NumPy
- Database: SQLite, if required
- Visualization: Plotly
- AI Integration: LLM API (provider to be finalized)

## 3. Architecture
- Keep frontend and backend separate.
- Build backend functionality using modular Python code.
- Expose backend functionality through REST APIs.
- Connect the frontend to the backend through HTTP requests.
- Keep data processing, API routes, and AI integration logically separated.

## 4. Coding Standards
- Write clean, readable, maintainable Python code.
- Use meaningful variable and function names.
- Add comments where they genuinely improve understanding.
- Avoid unnecessary dependencies.
- Follow Python best practices.
- Handle errors properly.

## 5. Security
- Never hardcode API keys, passwords, or secrets.
- Use environment variables for sensitive configuration.
- Validate uploaded files and user inputs.
- Never execute arbitrary SQL or generated code without appropriate validation and safeguards.

## 6. Learning and Development
- Explain generated code and important design decisions.
- Do not modify unrelated files without permission.
- Prefer small, testable changes.
- Include appropriate tests for new functionality.
- Do not invent features or claim functionality that has not been implemented.
- Ask for clarification when requirements are unclear.

## 7. Git Practices
- Use meaningful commit messages.
- Never commit the virtual environment, API keys, or sensitive files.
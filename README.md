# AI_Coding_Agent -Build Your Own AI Assistant with Python & Gemini Flash API

Build your own functional AI coding assistant from the ground up — using Python and Google’s Gemini Flash API.

This project is based on the FreeCodeCamp YouTube course
 created by Lane Wagner, where you learn to build a self-improving AI coding agent capable of reading, editing, and executing code.

🚀 Project Overview

This project walks through creating an AI-powered coding agent that:

Understands and navigates your project’s codebase

Reads and modifies code files intelligently

Executes code to get feedback

Uses tool calling to form an agentic reasoning loop

By completing it, you’ll gain a deep understanding of how modern AI developer tools — like GitHub Copilot or ChatGPT’s code interpreter — actually work under the hood.

🧩 Key Features

🤖 Agentic Loop — A self-feedback cycle where the agent refines its own outputs

🧠 Code Understanding — Reads and analyzes source files

✍️ File Modification — Writes and updates files intelligently

⚙️ Execution & Feedback — Runs scripts and processes error outputs to improve

🔗 Tool Calling System — Connects reasoning with actions through custom Python tools

⚡ Gemini Flash API Integration — Lightweight, fast, and free LLM backend

🛠️ Tech Stack
Component	Description
Language	Python 3.10+
AI Model	Gemini Flash API
Frameworks / Tools	Custom Python tool-calling framework
Environment	Linux via WSL (Windows Subsystem for Linux)
Editor	Visual Studio Code
Version Control	Git + GitHub
⚙️ Installation & Setup

Clone this repository

git clone https://github.com/<your-username>/aiagent.git
cd aiagent


Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate


Install dependencies

pip install -r requirements.txt


Set your Gemini API key

export GEMINI_API_KEY=your_api_key_here


Run the agent

python main.py

📘 What You’ll Learn

By following this project, you’ll gain hands-on experience with:

Building agentic AI workflows from scratch

Understanding tool calling and reasoning loops

Integrating LLMs into Python applications

Designing agents that can read, modify, and test codebases

Structuring open-source AI tools for collaboration

🌱 Future Enhancements

Integrate memory for multi-step reasoning

Add a natural language debugging mode

Build a web-based or VS Code interface

Extend toolset for API calls and multi-file projects

🙏 Credits & Attribution

This project is inspired by the FreeCodeCamp course:

“Build an AI Coding Assistant with Python and Gemini Flash API”

Created by Lane Wagner

All educational credit belongs to the original instructor and the FreeCodeCamp community.
This repository serves as a personal implementation and learning project.

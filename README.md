# Workik AI Agent

![Demo Screenshot](demo.gif) *(Optional: Add a screenshot or animated GIF)*

A command-line AI assistant that executes tasks on your local machine using natural language commands. Built for the Workik AI internship assignment.

## Features

- **Natural Language Processing**: Converts plain English requests into executable commands
- **Cross-Platform Support**: Automatically detects Windows/macOS/Linux and adjusts commands
- **Safe Execution**: Requires user confirmation before running any command
- **Error Recovery**: Automatically fixes failed commands using AI feedback
- **VS Code Extension**: Optional IDE integration (bonus feature)

## How It Works

1. You describe a task in natural language (e.g., "Create a Python script that prints Fibonacci sequence")
2. The agent uses Groq's AI API to generate the appropriate commands
3. Shows the proposed commands for approval
4. Executes after confirmation
5. If errors occur, it asks for feedback and retries with improvements

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/workik-ai-agent.git
   cd workik-ai-agent

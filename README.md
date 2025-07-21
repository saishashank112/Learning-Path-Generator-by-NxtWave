<<<<<<< HEAD
# Learning Path Generator with Model Context Protocol (MCP)

This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

## Features

- 🎯 Generate personalized learning paths based on your goals
- 🎥 Integration with YouTube for video content
- 📁 Google Drive integration for document storage
- 📝 Notion integration for note-taking and organization
- 🚀 Real-time progress tracking
- 🎨 User-friendly Streamlit interface

## Prerequisites

- Python 3.10+
- Google ai Studio API Key
- Pipedream URLs for integrations (YouTube and either Drive or Notion)

## Installation

1. Clone the repository:

2. Create and activate a virtual environment:

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Configuration

Before running the application, you'll need to set up:

1. Google API Key
2. Pipedream URLs for:
   - YouTube (required)
   - Google Drive or Notion (based on your preference)

## Running the Application

To start the application, run:
```bash
streamlit run app.py
```

The application will be available at `http://localhost:8501` by default.

## Usage

1. Enter your Google ai studio API key and Pipedream URLs in the sidebar
2. Select your preferred secondary tool (Drive or Notion)
3. Enter your learning goal (e.g., "I want to learn python basics in 3 days")
4. Click "Generate Learning Path" to create your personalized learning plan

## Project Structure

- `app.py` - Main Streamlit application
- `utils.py` - Utility functions and helper methods
- `prompt.py` - Prompt template
- `requirements.txt` - Project dependencies
=======
# 🚀 Learning Path Generator

**AI-powered personalized learning path generator** built with **Gemini AI**, **Pipedream MCP servers**, and **Streamlit**. This tool intelligently curates educational content from YouTube, Notion, and Google Drive to design dynamic, goal-aligned learning journeys for users.

---

## 🔍 Problem It Solves
The internet is flooded with content. Learners waste hours finding the right resources. This project turns scattered data into **structured, AI-curated learning experiences** — instantly.

---

## 🧠 Features

- ⚡ Gemini AI for intelligent path generation
- 📺 Auto-fetch content from YouTube, Notion & Google Drive via Pipedream MCP servers
- 🎯 Learner-centric, adaptive recommendations
- 🌐 Intuitive Streamlit web interface
- 🔐 Secure with user-specific API integrations

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Gemini AI Studio (Google)** — Natural Language Processing
- **Pipedream MCP** — Unified content APIs for YouTube, Notion, and Drive
- **Streamlit** — Lightweight front-end for instant deployment
- **Cursor IDE** — Dev environment

---

<img width="1361" height="630" alt="Screenshot 2025-07-21 050428" src="https://github.com/user-attachments/assets/d7b94737-7f3b-4f8a-adaa-3add4e151e2c" />


## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd learning-path-generator

### Install Dependencies
pip install -r requirements.txt

###Run the Application
streamlit run app.py
>>>>>>> 02aa1300889b55a6306fdc7781c490868d1001e1

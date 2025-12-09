CS 3338 Final Project – ChatBox AI
Team Members

Robert Melena

Robert Guiterrez

Miguel Aguirre

Jira Project URL:
https://cs3338-group-01.atlassian.net/jira/software/projects/CAG/boards/67

Overview

ChatBox AI is our final project for CS 3338.
Instead of building a full working application, this project focuses on learning and documenting the entire software engineering process.

The idea behind ChatBox AI is a simple AI chat assistant for students. The goal is to show how a project like this would work in the real world using a front end, a back end, a database, Docker, and project management tools like Jira and TestRail.

System Architecture (Conceptual)

ChatBox AI would use a basic 3-layer architecture:

1. Frontend (Web UI)
  A chat page for typing messages
  Login/register screens
  Settings and an admin dashboard
  Communicates with the backend using REST API calls

2. Backend (Server)
  Handles user authentication
  Stores chat sessions and messages
  Connects to an external AI provider (through an “AI Adapter”)

3. Database
  Stores user accounts
  Keeps chat history
  Can run inside a PostgreSQL Docker container

 We also assume a real AI provider (like OpenAI or Anthropic), but only as a placeholder.
  
Features 
  Student Features
  Register / log in
  Start chat sessions
  View older sessions
  Export a chat (Snapshot 2 feature)
  
Admin Features
  View total users, sessions, and messages
  Basic “system activity” view (conceptual only)

Documentation Included
  SDD (Software Design Document)
  SRS (Software Requirements Specification)
  Design Specification
  User Manual / README (LaTeX version)
  Snapshot Objectives (1–4)
  TestRail run summaries (Snapshots 2, 3, 4)
  Workflow diagram
This covers everything required for the final project.


Technologies
  Even though nothing is implemented, the project assumes:
  Frontend: React or Vue
  Backend: Node.js + Express
  Database: PostgreSQL
  Containerization: Docker & docker-compose
  Project Management: Jira
  Testing: TestRail
  Documentation: LaTeX

Repository Layout
  docs/
   ├── sdd.tex
   ├── srs.tex
   ├── readme.tex
   ├── design_spec.tex
   ├── snapshot_objectives.tex
   ├── testrail_snapshot2.pdf
   ├── testrail_snapshot3.pdf
   ├── testrail_snapshot4.pdf
   ├── workflow_diagram.tex
   └── images/workflow.png

docker-compose.yml
final-project.txt
README.md  (this file)

Viewing the LaTeX Documents (look below)

Go to the docs/ folder
Choose any .tex file
Open it in Overleaf, TeXShop, or any LaTeX editor
Compile to PDF to see the formatted version

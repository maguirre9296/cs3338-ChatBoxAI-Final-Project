CS 3338 Final Project – ChatBox AI
Team Members

Robert Melena

Robert Guiterrez

Miguel Aguirre

Jira Project URL:
https://cs3338-group-01.atlassian.net/jira/software/projects/CAG/boards/67

Overview

ChatBox AI is our final project for CS 3338.
Instead of building a full working app, this project focuses on understanding and documenting the full software engineering process.

Our idea is to design a simple AI chat assistant made for students. The goal is to show how a real system like this could be built using a frontend, backend, database, Docker, and project management/testing tools such as Jira and TestRail.

System Architecture (Conceptual)

ChatBox AI is based on a simple 3-layer architecture:

1. Frontend (Web UI)

Chat interface for users

Login/register pages

Settings and a small admin dashboard

Talks to the backend through REST API calls

2. Backend (Server)

Handles login + authentication

Manages chat sessions and messages

Sends user messages to an external AI model using an AI Adapter

3. Database (PostgreSQL)

Stores users

Saves chat history

Would run in a PostgreSQL Docker container

A real AI provider (OpenAI, Anthropic, etc.) is assumed, but only conceptually.

Features
Student Features

Register and log in

Start new chat sessions

View past sessions

Export conversation history (Snapshot 2 feature)

Admin Features

View total users

View number of chat sessions and messages

Basic “system activity” overview

Documentation Provided

The repo includes all required CS 3338 final project documents:

SDD – Software Design Document

SRS – Software Requirements Specification

Design Specification

User Manual (LaTeX)

Snapshot Objectives (Snapshots 1–4)

TestRail PDF reports for Snapshots 2, 3, and 4

Workflow diagram

Technologies (Assumed for a Real Implementation)

Even though nothing is fully coded, the project assumes the following stack:

Frontend: React or Vue

Backend: Node.js + Express

Database: PostgreSQL

Containers: Docker + docker-compose

Task Management: Jira

Testing: TestRail

Documentation: LaTeX

Repository Layout
docs/
 ├── design_spec.tex
 ├── readme.tex
 ├── sdd.tex
 ├── srs.tex
 ├── snapshot_objectives.tex
 ├── testrail_snapshot2.pdf
 ├── testrail_snapshot3.pdf
 ├── testrail_snapshot4.pdf
 ├── workflow_diagram.tex
 └── images/workflow.png

docker-compose.yml
final-project.txt
README.md   (this file)

Viewing the LaTeX Documents

Open the docs/ folder

Select any .tex document

Open it in Overleaf, TeXShop, or another LaTeX editor

Compile to generate the PDF

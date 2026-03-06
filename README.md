# CareerCopilot AI

AI-powered Job Preparation Platform that helps candidates analyze their resumes, identify skill gaps for specific job roles, and generate personalized interview questions using Generative AI.

This project simulates a real-world product where users can upload resumes, analyze job descriptions, detect missing skills, and prepare for interviews with AI-generated questions.

It combines **Full Stack Development + Generative AI** to build an end-to-end job preparation system.

---

# Problem Statement

Job seekers often face three major challenges:

1. They don't know whether their resume matches a job description.
2. They struggle to identify missing skills required for a role.
3. They lack structured interview preparation tailored to their resume and target job.

Most existing tools solve only one of these problems.

---

# Solution

CareerCopilot AI provides a unified platform that:

* Parses user resumes
* Analyzes job descriptions
* Detects skill gaps
* Generates AI-powered interview questions
* Suggests improvements for ATS-optimized resumes

The goal is to simulate how modern **AI-powered hiring tools** work.

---

# Key Features

## Authentication System

* Secure user authentication using **JWT**
* Login / Signup functionality
* Protected routes

## Resume Processing

* Upload resume (PDF)
* Extract resume text automatically
* Structure resume content for analysis

## Job Description Analysis

* Users can paste a job description
* System extracts required skills
* Compares them with resume skills

## Skill Gap Detection

* Identifies missing skills required for the role
* Shows gaps between resume and job requirements

## AI Interview Question Generator

* Uses **Gemini AI** to generate interview questions based on:

  * Resume
  * Job description
  * Detected skills

## ATS Resume Optimization

* Provides AI suggestions to improve resume for ATS systems

---

# System Architecture

Frontend → React
Backend → Node.js + Express
Database → MongoDB

AI Processing Flow:

Resume Upload
→ Resume Parsing
→ Job Description Analysis
→ Skill Comparison
→ Gemini AI Prompt Generation
→ AI Response Processing

---

# Tech Stack

Frontend

* React
* Axios
* React Router
* Tailwind / CSS

Backend

* Node.js
* Express.js
* JWT Authentication
* Multer (file upload)

AI Integration

* Google Gemini AI API

Automation / Parsing

* Puppeteer

Database

* MongoDB
* Mongoose

---

# Project Structure

frontend/

* components
* pages
* services
* utils

backend/

* controllers
* routes
* middleware
* models
* services

---

# AI Workflow

1. User uploads resume
2. Resume text is extracted
3. User enters job description
4. System compares required vs existing skills
5. Prompt is generated for Gemini AI
6. AI returns interview questions and improvement suggestions

---

# Learning Outcomes

Through this project I implemented:

* Full Stack Application Architecture
* Secure Authentication using JWT
* Resume parsing and text processing
* AI integration using Gemini API
* Backend API design
* Prompt engineering for AI systems
* Real-world SaaS-style product workflow

---

# Future Improvements

* ATS score calculation
* Resume improvement suggestions with editing support
* Mock interview simulation
* Vector database for resume embeddings
* AI career roadmap generation

---

# Author

Puneet Kumar

Full Stack Developer interested in building scalable backend systems and AI-powered applications.

##Project Overview

Cloud Cosmos Assistant is a lightweight AI-powered web application built with Next.js that provides an interactive chat interface.
It enables users to communicate with an intelligent assistant directly in the browser, featuring a clean, responsive UI and modular architecture.


---
##Problem Statement

Many AI-based chat tools are heavy, require backend setup, or lack an intuitive interface.
Our project addresses this by offering a serverless, cloud-native conversational assistant built entirely with modern web technologies, deployable on any platform with minimal configuration.
It focuses on simplicity, accessibility, and real-time interactivity.


---

##Solution Summary

We built a Next.js AI Assistant web app that delivers smooth, chat-based interaction using a simple API endpoint.
Users can send prompts, receive dynamic responses, and view conversation history within a beautifully designed interface.
The app leverages Next.js serverless routes for backend logic and modular UI components for maintainability.


---

##Tech Stack

Frontend: Next.js (React + TypeScript), Tailwind CSS

Backend: Next.js API Routes (app/api/chat/route.ts)

Database: None (stateless; can integrate external APIs for persistence)

LLM / AI Model: Gemini API

Cloud / Hosting: Vercel

Version Control: Git + GitHub


---

##Project Structure

cloud-cosmos-hackathon-main/
├── app/                    # Main app logic, layouts, and pages
│   ├── layout.tsx          # Root layout with global design
│   ├── page.tsx            # Home page UI
│   ├── assistant.tsx       # Chat interface component
│   └── api/chat/route.ts   # API endpoint for chat messages
│

├── components/             # UI and chat-specific components
│   ├── assistant-ui/       # Chat threads, message rendering, attachments
│   └── ui/                 # Generic UI elements (button, dialog, input, etc.)
│

├── hooks/                  # Custom React hooks
│   └── use-mobile.ts       # Detects mobile/responsive layout
│

├── lib/                    # Utilities and helper functions
│   └── utils.ts
│

├── next.config.ts          # Next.js configuration
├── tsconfig.json           # TypeScript configuration
└── README.md               # Project documentation


---

##Setup Instructions

To run the project locally:

# 1. Clone the repository
git clone https://github.com/<your-repo-link>.git
cd cloud-cosmos-hackathon-main

# 2. Install dependencies
npm install

# 3. Run the app locally
npm run dev

> The app runs by default on http://localhost:3000.

---

##Deployment

Live Demo URL:
https://cloud-cosmos-hackathon-h445.vercel.app/

---

##Demo Video 

YouTube Link:
https://youtu.be/PobkjbGB18s


---

##Features

Clean and responsive chat interface

Modular React components with reusable design system

Serverless API for AI chat handling

Lightweight and easy to deploy

Extendable architecture for integrating external APIs or storage



---

 ##Technical Architecture

Flow:

User → Chat UI (Next.js Frontend)
     → API Route (/api/chat)
     → LLM API (e.g., OpenAI)
     → Response rendered in UI

Frontend (React + Tailwind) sends user message → /api/chat

Serverless route calls AI model → returns response

Message displayed in real-time within assistant UI


---



🧾 References

Next.js Documentation

Vercel Deployment Guide

Tailwind CSS




---

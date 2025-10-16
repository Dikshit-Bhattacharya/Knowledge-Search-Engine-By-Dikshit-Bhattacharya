🌟 Knowledge-Base Search Engine

👤 Name: Dikshit Bhattacharya
🆔 Reg No.: 22BCE8882

🚀 Live Website: Click Here

🎥 Video Demo: Watch Demo

🔹 Introduction

The Knowledge-Base Search Engine is a modern web application that lets users upload documents (PDFs or text files) and ask questions about their content. Leveraging Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG), it generates concise, context-aware answers, enabling users to quickly access relevant information without reading the entire document.

🎯 Objectives

✅ Enable users to upload multiple documents

✅ Provide an interface to ask questions about document content

✅ Generate precise answers using Gemini 2.5 Flash API

✅ Showcase integration of React frontend with Node.js backend for LLM-powered Q&A

🛠 Technology Stack

Frontend:

React.js

CSS (Styling & responsive design)

Backend:

Node.js + Express.js

Multer (File uploads)

pdf-parse (Extract text from PDFs)

Google Generative AI (@google/generative-ai)

LLM Model:

Gemini 2.5 Flash API

⚙️ Methodology
Frontend

Built with React.js for a modern, user-friendly interface

Key Features:

PDF upload

Question input box

Chat-style answer display

Communicates with backend APIs to upload documents and receive AI-generated responses

Backend

Developed using Node.js + Express.js

Handles PDF uploads using Multer

Extracts text from PDFs using pdf-parse

Sends document content along with user queries to Gemini 2.5 Flash API for answer synthesis

🖥 API Endpoints
GET /        -> Check backend server status

POST /upload -> Upload a PDF file
               Returns success message + file details + extracted text length

POST /ask    -> Submit a question about the uploaded document
               Returns a synthesized answer from the LLM

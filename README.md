Knowledge-Base Search Engine

Name: Dikshit Bhattacharya
Reg No.: 22BCE8882

Live Website: https://knowledge-search-engine-by-dikshit.vercel.app/

Video Demo: Watch Demo

Introduction

The Knowledge-Base Search Engine is a web application that allows users to upload documents (PDFs or text files) and ask questions related to their content. Using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG), the system generates concise, context-aware answers, enabling intelligent document understanding and quick access to information without manually reading large files.

Objectives

Enable users to upload multiple documents.

Provide an interface to ask questions about document content.

Generate precise answers using the Gemini 2.5 Flash API.

Demonstrate the integration of React frontend with a Node.js backend for LLM-powered document Q&A.

Scope of Work

Input: PDFs or text documents

Output: Synthesized answers to user queries

Optional: Frontend interface for document upload and query submission

Technology Stack

Frontend:

React.js

CSS for styling

Backend:

Node.js + Express.js

Multer (file uploads)

pdf-parse (extract text from PDFs)

Google Generative AI (@google/generative-ai)

LLM Model:

Gemini 2.5 Flash API

Methodology
Frontend

Built with React.js for a user-friendly interface.

Features: PDF upload, question input box, and chat-style answer display.

Communicates with backend APIs to upload documents and receive AI-generated responses.

Backend

Developed with Node.js and Express.js.

Handles PDF uploads using Multer.

Extracts text content using pdf-parse.

Sends document content with user queries to Gemini 2.5 Flash API for answer synthesis.

API Endpoints

GET /

Status check for backend server

POST /upload

Upload a PDF file

Returns success message with file details and extracted text length

POST /ask

Submit a question regarding the uploaded document

Returns a synthesized answer from the LLM

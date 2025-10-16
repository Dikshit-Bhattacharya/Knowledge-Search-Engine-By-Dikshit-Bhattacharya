Knowledge-Base Search Engine – Project Report
Name: Dikshit Bhattacharya
Reg No.: 22BCE8882
Live Website: https://knowledge-search-engine-by-dikshit.vercel.app/
Video Demo: https://drive.google.com/file/d/1PgloIIuV34cZ8tpaPivxuwnAernA1ifw/view?usp=drive_link
________________________________________
1. Introduction
The Knowledge-Base Search Engine is a web application designed to allow users to upload documents (PDFs or text files) and ask questions related to their content. The system leverages Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to provide concise, context-aware answers based on the uploaded documents.
This project aims to facilitate intelligent document understanding and quick access to information for users, without manually reading large files.
________________________________________
2. Objectives
•	Enable users to upload multiple documents.
•	Provide an interface to ask questions about document content.
•	Generate precise answers using Gemini 2.5 Flash API.
•	Demonstrate the integration of React frontend with a Node.js backend for LLM-powered document QA.
________________________________________
3. Scope of Work
•	Input: PDFs or text documents
•	Output: Synthesized answers to user queries
•	Optional: Frontend interface for document upload and query submission
________________________________________
4. Technology Stack
Frontend:
•	React.js
•	CSS for styling
Backend:
•	Node.js + Express.js
•	Multer (for file uploads)
•	pdf-parse (for extracting text from PDFs)
•	Google Generative AI (@google/generative-ai)
LLM Model:
•	Gemini 2.5 Flash API
________________________________________
5. Methodology
5.1 Frontend
•	Built with React.js to provide a user-friendly interface.
•	Features include PDF upload, question input box, and chat-style answer display.
•	Communicates with backend APIs to upload documents and receive AI-generated responses.
5.2 Backend
•	Developed with Node.js and Express.js.
•	Handles PDF file uploads using Multer.
•	Extracts text content from PDFs using pdf-parse.
•	Sends the document content along with user queries to the Gemini 2.5 Flash model for answer synthesis.
________________________________________
6. API Integration
Endpoints
1.	GET /
•	Status check for backend server.
2.	POST /upload
•	Upload a PDF file.
•	Returns success message with file details and extracted text length.
3.	POST /ask
•	Submit a question regarding the uploaded document.
•	Returns a synthesized answer from the LLM.

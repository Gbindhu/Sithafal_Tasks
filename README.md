# Sithafal_Tasks
Project Overview
This repository showcases two AI-powered interactive systems designed to enable seamless querying of data:

Chat with PDF
A Retrieval-Augmented Generation (RAG) pipeline that allows users to upload PDF files and interact with their content using natural language queries.

Chat with Website
A system enabling users to query website data by extracting and indexing the content, making it accessible through an intuitive chatbot interface.

Both tasks leverage AI and modern NLP technologies to provide accurate and contextual responses.

Task 1: Chat with PDF

Description:
The Chat with PDF feature is a user-friendly system enabling users to ask questions about content within uploaded PDF files. By integrating the RAG pipeline, the system extracts and indexes semi-structured data for efficient querying and comparison.

Features:
PDF text extraction and preprocessing.
Logical chunking of content for granularity.
Embedding generation using pre-trained NLP models.
Vector-based similarity search for precise data retrieval.
Response generation using a Large Language Model (LLM).
Handles comparison queries and provides structured responses (e.g., tables).

Tech Stack:
Libraries: pdfplumber.

Task 2: Chat with Website

Description:
The Chat with Website feature enables users to interact with content from a website by scraping, indexing, and querying its data. This system is ideal for querying FAQs, blogs, or any web content efficiently.

Features:
Website content scraping and data ingestion.
Text cleaning and preprocessing.
Embedding generation and storage for fast retrieval.
Natural language interaction using an LLM.

Tech Stack:
Libraries: requests, Beautifulsoup4


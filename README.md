# InvoiceExtractionOCR
AI Powered Invoice Data Extractor using Chatgpt 4o


This project provides a robust pipeline for automatically extracting structured data from PDF invoices using OpenAI's GPT-4o model, storing the results in a local database, and visualizing them through a clean web interface built with gradio.

The application is designed to handle multiple invoices, transform the extracted data into a standardized schema, and provide an easy-to-use dashboard for viewing the results.

## Features

PDF to Structured Data:Ingests PDF invoices (even multi-page ones) and extracts key information.
AI-Powered Extraction: Leverages the power of Gpt-4o for high-accuracy data recognition without the need for template-based rules.
Data Standardization: Transforms the raw extracted data into a consistent, predefined schema.
Persistent Storage: Saves structured invoice data into a local SQLite database for reliability and easy querying.
Interactive Dashboard: A simple Gradio web application to view, search, and inspect all processed invoices and their line items.

### Prerequisites

>Python 3.12

>An OpenAI API Key with access to the GPT-4o model.

>A .env file to store your API key securely.




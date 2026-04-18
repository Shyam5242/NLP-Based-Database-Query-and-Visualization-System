# NLP-Based-Database-Query-and-Visualization-System
Overview

This project is an offline Natural Language Processing (NLP) system that allows users to query a Superstore sales dataset using plain English instead of SQL.
It converts user queries into SQL using intent detection and entity extraction, executes them on a database, and visualizes the results.

Features:-
🗣️ Natural language to SQL conversion
🧠 Rule-based NLP (intent detection + entity extraction)
🗄️ SQLite database integration
📊 Data visualization (bar charts, pie charts, time series)
⚡ Fully offline (no API or internet required)

Tech Stack:-
Python
Google Colab
Pandas
SQLite
NLTK
Matplotlib

Dataset:-
Superstore Sales Dataset (CSV format)
Contains fields like:
Order ID, Order Date, Customer Name
Product Name, Category, Region
Sales, Profit, Quantity, Discount

How It Works:-
User enters a query in natural language
NLP module:
Tokenizes input
Detects intent (sales, profit, region, etc.)
Extracts entities (city, category)
System generates SQL query dynamically
SQL executes on SQLite database
Results are displayed and visualized

Example Queries:-
"Show total sales"
"Sales by region"
"Top products"
"Profit in Mumbai"
"Sales in Chennai for Furniture"

Visualizations:-
Bar charts (Sales by Region, Top Products)
Pie charts (Category Distribution)
Line charts (Sales Over Time)
Installation & Setup:-
1. Open in Google Colab

Upload your dataset:
from google.colab import files
files.upload()
2. Install Dependencies
pip install pandas nltk matplotlib
3. Run the Notebook
Load CSV → SQLite
Run NLP functions
Use ask_database("your query")

Key Concepts Used:-
Natural Language Processing (NLP)
Intent Detection
Entity Extraction
SQL Query Generation
Data Visualization

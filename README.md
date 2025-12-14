# LLM-Powered-Database-Query-Assistant
An LLM-powered Natural Language to SQL (Text2SQL) system that enables users to query relational databases using plain English. The project leverages schema-aware prompt engineering to generate accurate, executable SQL queries and run them safely on a SQLite database.

---

##  Overview

This project implements a **schema-grounded Text-to-SQL pipeline** that translates natural language queries into SQL using a Large Language Model (LLM). It bridges the gap between non-technical users and structured databases by enabling conversational data access.

The system dynamically injects database schema into LLM prompts, validates generated SQL, and executes queries in real time.

---

##  Key Features

- Natural Language → SQL query translation using LLMs  
- Schema-aware prompt engineering to reduce hallucinations  
- Automatic intent detection and entity/schema linking  
- SQL validation before execution  
- Real-time query execution on SQLite  
- Modular and extensible architecture

---

##  System Architecture
<img width="1391" height="757" alt="image" src="https://github.com/user-attachments/assets/472971b2-9bba-4742-a7b2-c0a7e3736544" />  

## ⚙️ Tech Stack

- **Language:** Python  
- **Database:** SQLite  
- **LLM:** Gemini / GPT (API-based)  
- **Libraries:** pandas, sqlite3, requests  
- **Concepts:** Text-to-SQL, Prompt Engineering, Schema Linking, NLP

## Use Cases
Conversational analytics for business users

AI-powered BI assistants

Rapid data exploration without SQL expertise


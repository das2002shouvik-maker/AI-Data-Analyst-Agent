AI Data Analyst Agent using Python & OpenAI
Project Overview

The AI Data Analyst Agent is an intermediate-level Python project that combines Data Analysis, Data Visualization, and Generative AI to create an intelligent assistant for analyzing employee data.

The project uses Pandas and Matplotlib for data processing and analysis, while the OpenAI API enables the system to understand natural-language questions and select appropriate analysis functions.

Instead of requiring users to write Python or SQL queries, they can ask questions in simple natural language, such as:

"How many employees are there?"
"What is the highest salary?"
"Which city has the most employees?"
"What is the average experience of employees?"
"Which department has the best performance?"

The AI agent interprets the question, selects the appropriate Python analysis function, executes the analysis on the employee dataset, and generates a clear natural-language response.

Key Features
Employee dataset loading and exploration
Data cleaning and missing-value handling
Duplicate-value verification
Exploratory Data Analysis (EDA)
Employee and salary analysis
Department and city analysis
Data visualization using Matplotlib
Reusable Python analysis functions
Natural-language question understanding using OpenAI
AI-based analysis tool selection
Automated execution of analysis functions
AI-generated insights and explanations
Handling of questions outside the available dataset
AI Agent Workflow
User Question
      ↓
OpenAI Model
      ↓
Understand User Question
      ↓
Select Appropriate Analysis Tool
      ↓
Python Analysis Function
      ↓
Employee DataFrame
      ↓
Analysis Result
      ↓
OpenAI Model
      ↓
Natural-Language Insight
      ↓
User
Technologies Used
Python
Pandas
NumPy
Matplotlib
OpenAI API
Jupyter Notebook

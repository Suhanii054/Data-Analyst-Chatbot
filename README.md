# AI Data Analyst – LangChain + Gemini 2.5 Pro

An advanced Generative AI and Data Science project that enables interactive, intelligent data analysis directly from a CSV file. 
Built using LangChain, Google Gemini 2.5 Pro, and Gradio, this system combines automated data exploration with conversational analytics — 
allowing simultaneous data analysis and AI-driven insights in real time.

---

## Overview

AI Data Analyst is an integrated data exploration assistant that:
- Performs automated exploratory data analysis (EDA) on uploaded CSV files.
- Generates AI-driven insights using Gemini 2.5 Pro.
- Allows users to chat with their dataset interactively using a LangChain agent.
- Runs tasks in parallel to ensure high efficiency and responsiveness.

This makes it one of the most efficient, intelligent, and interactive chat-based data analysis tools built for practical, research, and professional use.

---

## Features

- Automated Data Analysis: Instantly summarizes dataset properties such as rows, columns, memory usage, and structure.
- AI-Driven Insights: Generates meaningful observations and analytical conclusions using Gemini 2.5 Pro.
- Conversational Data Chat: Interact with your dataset naturally through a chat interface powered by LangChain.
- Parallel Execution: All key functions — EDA, insights, and chat — are executed in parallel for maximum speed and efficiency.
- Gradio Interface: A clean and functional user interface to upload data, view insights, and chat seamlessly.

---

## Tech Stack

- Language Model: Google Gemini 2.5 Pro
- Frameworks: LangChain, Gradio
- Language: Python
- Libraries: Pandas, Google Generative AI SDK
- Platform: Google Colab

---

## How It Works

1. Upload your CSV file through the Gradio interface.
2. Enter your Google API Key (required for Gemini 2.5 Pro).
3. The model automatically performs EDA, extracting descriptive statistics and patterns.
4. The AI generates contextual insights and explanations based on your dataset.
5. You can then chat interactively with your data — asking queries, requesting summaries, or exploring patterns.
6. All these processes run in parallel, making the system highly efficient and responsive.

---

## Project Architecture

1. Gradio UI: Frontend interface for dataset upload, chat, and results display.
2. EDA Engine: Extracts descriptive statistics, missing values, correlations, and distribution summaries.
3. AI Insights Generator: Uses Gemini 2.5 Pro to interpret EDA results and provide analytical insights.
4. LangChain Agent: Enables chat-based querying over the dataset, supporting natural language questions.
5. Parallel Processing Layer: Ensures independent but synchronized execution of EDA and insights generation for optimal performance.

---

## How to Use

1. Open the notebook in Google Colab.
2. Run all cells to set up dependencies and environment.
3. Enter your Google Gemini API key in the provided input field.
4. Upload a CSV dataset.
5. View the automatically generated EDA and insights.
6. Use the chat interface to explore your dataset interactively.

---

## Example Questions

- What are the top 10 most frequent values in the dataset?
- Are there any missing values?
- Show me the summary statistics for numerical columns.
- Which columns have the most variation?
- What are the major patterns or correlations in this dataset?

---

## Repository Structure

AI_Data_Analyst_Gemini.ipynb   # Main Colab notebook
README.md                      # Project documentation
requirements.txt                # Dependencies list (optional)
sample_data.csv                 # Example dataset (optional)

---

## Installation (Local or Colab)

If you want to run it locally instead of Colab:

pip install gradio langchain google-generativeai pandas
python app.py

Then open the Gradio link displayed in your terminal.

---

## License

This project is released under the MIT License.

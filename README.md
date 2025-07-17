# BCGX-Forage

# AI-Powered Financial Chatbot
Project: BCG GenAI Job Simulation on Forage


# Overview
This project is part of a job simulation experience hosted by BCG (Boston Consulting Group) on the Forage platform. It showcases the development of an AI-driven financial chatbot that interprets company data from SEC filings (10-K/10-Q) to provide structured financial insights.

The chatbot is built using Python and is designed to simulate how AI can be applied to automate financial consulting tasks.

🧠 What the Chatbot Can Do
The chatbot is rule-based and can answer predefined financial queries for Microsoft, Tesla, and Apple from FY 2021 to 2023, such as:

 What is the total revenue?

 What is the Net Income?

 What is the sum of total assets/liabilities?

 What is the revenue/net income/assets/liabilities growth (%)?

 What is the year-over-year average growth rate for key metrics?

# Technologies Used
Python 3.8+

pandas – for data manipulation

Jupyter Notebook – for prototyping logic

CLI – Command-line interaction with the chatbot

# Files Included
File	Description
chatbot.py	Core logic of the rule-based chatbot
task1.ipynb / task1-checkpoint.ipynb	Notebook with intermediate development
Financial_Data_Microsoft_Tesla_Apple.csv	Raw financial data extracted from 10-K filings
Summary_final_report.csv	Summary of growth metrics
Documentation_ChatBot.txt	Technical and functional documentation of chatbot

# How to Use It
Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Run the chatbot script:

python chatbot.py
Follow the prompts:

Choose a company (Apple, Microsoft, Tesla)

Choose a fiscal year (2021–2023)

Ask one of the predefined questions listed above

# Key Learnings
Applied Python programming to real-world financial data

Built a functional AI chatbot using rule-based logic

Understood financial metrics from SEC filings (10-K/10-Q)

Practiced delivering insights in a user-friendly conversational format

# Limitations
 Only understands exact, predefined queries
 No NLP or fuzzy matching capabilities
 Data is static (not real-time or dynamic)

# Future Improvements
Incorporate NLP techniques for flexible question handling

Connect to live financial APIs (e.g., Yahoo Finance, EDGAR)

Develop a web interface using Streamlit or Flask


# Smart AI Budget Agent

Smart AI Budget Agent is a Streamlit-based financial analysis tool that processes transaction data from a CSV file and generates an intelligent budget plan using a large language model hosted via Groq.

The application analyzes income, fixed expenses, variable expenses, and provides AI-powered financial recommendations.

---

## Project Overview

This application helps users:

- Upload their monthly financial transactions
- Automatically calculate total income
- Categorize expenses into fixed and variable
- Generate a savings target (15% of income)
- Receive AI-based budgeting advice

The system combines rule-based financial analysis with LLM-powered recommendations.

---

## Features

- CSV-based transaction upload
- Automatic income and expense calculation
- Fixed vs variable expense classification
- Variable expense category breakdown
- Savings goal calculation (15%)
- AI-generated personalized budget recommendations
- Secure runtime API key input
- Clean and interactive Streamlit interface

---

## Input CSV Format

The uploaded CSV must contain at least the following columns:

- amount
- category

Example:

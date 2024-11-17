# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.
An interactive web-based application built with Streamlit to manage, track, and analyze personal or business expenses. This project allows users to add, update, and view analytics on their expenses, making financial tracking simpler and more organized.
Features:
Add and Update Expenses: Record daily expenses with details such as date, category, and amount.
Analytics and Visualizations: View insights and trends on your spending patterns.
User-Friendly Interface: Built with Streamlit for easy navigation and quick interactions.

Prerequisites

- Python 3.7 or higher. 
- pip` package manager

## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```

# Fin-AI-assisstant
 # AI-Powered Personal Finance Assistant

A beginner-friendly full-stack web application for tracking expenses, managing budgets, and exploring AI-assisted personal finance features.

This project was built as a learning project to strengthen my understanding of **full-stack development**, **API integration**, **database design**, and **practical AI features** in a real product-style application.

---

# Project Overview

**AI-Powered Personal Finance Assistant** is a personal finance web app that helps users:

* track daily expenses
* manage monthly budgets
* view expense history
* analyze spending patterns
* explore AI-assisted expense categorization and forecasting

The goal of this project was to build something beyond a basic CRUD app and turn it into a **resume-worthy full-stack project** with a practical use case.

---

# Why I Built This Project

I built this project to improve my skills in:

* frontend development with **React**
* backend API development with **FastAPI**
* working with a **PostgreSQL-style backend structure**
* understanding how **AI/ML features** can be added to a real application
* organizing a project with separate **frontend**, **backend**, and **ML pipeline** modules

I’m still a beginner, so this project is also part of my learning journey.
I used **AI tools to help me plan and build parts of the project faster**, while I focused on understanding the architecture, features, folder structure, and how the application works end-to-end.

---

# Features

## Core Features

* User authentication
* Add expenses
* Edit expenses
* Delete expenses
* Track expense history
* Set and manage budgets
* Dashboard view for finance tracking

## Smart / AI-Oriented Features

* Expense categorization support
* Forecasting / finance insight modules
* ML pipeline for training a classifier
* Foundation for future AI-powered finance features

---

# Tech Stack

## Frontend

* **React**
* **TypeScript**
* **Vite**

## Backend

* **FastAPI**
* **Python**
* **SQLAlchemy**

## Database

* PostgreSQL-ready backend structure

## AI / ML

* **Python**
* **scikit-learn**
* **pandas**

---

# Project Structure

```bash
personal-finance-assistant/
├── backend/        # FastAPI backend, APIs, database models, services
├── frontend/       # React + TypeScript frontend
├── ml_pipeline/    # ML training scripts and training data
└── README.md
```

## Backend Structure

The backend contains:

* authentication endpoints
* expense endpoints
* budget endpoints
* database models and schemas
* service modules for classifier and forecasting logic

## Frontend Structure

The frontend contains:

* dashboard page
* expenses page
* budgets page
* authentication context
* reusable UI components like sidebar and expense modal

## ML Pipeline

The ML pipeline contains:

* a training script for the expense classifier
* training data used for category prediction experiments

---

# Main Modules

## 1. Authentication

Handles user login and access flow.

## 2. Expense Management

Allows users to add, edit, delete, and view expenses.

## 3. Budget Management

Allows users to create and manage budgets.

## 4. Dashboard

Displays finance-related information in a more organized way.

## 5. AI / ML Services

Includes the base structure for:

* expense categorization
* forecasting / prediction features

---

# Screens / Pages

The current frontend includes pages such as:

* **Dashboard**
* **Expenses**
* **Budgets**

and reusable components such as:

* **Sidebar**
* **Expense Modal**

---

# Learning Focus of This Project

This project helped me practice:

* building a **frontend + backend integrated project**
* understanding **REST API structure**
* organizing code into **models, schemas, endpoints, and services**
* working with a **modular project folder structure**
* thinking about how **AI features** fit into a real-world app
* moving from simple programming practice to a more complete application

---

# AI Usage Note

I want to be transparent about how this project was built.

I am still learning, and I used **AI as a development assistant** during this project for:

* project planning
* structuring the app architecture
* generating or improving parts of the codebase
* understanding how to connect frontend, backend, and ML components

I did **not** use this project just to “copy and paste” code without learning.
My focus is to use AI as a tool to **learn faster, build stronger projects, and understand real development workflows**.

---

# Current Status

This project is currently in the **student-project / learning-build stage**.

## Implemented / structured areas

* frontend structure
* backend structure
* auth / expenses / budgets module structure
* ML pipeline setup
* modular project organization

## Areas I plan to improve

* full deployment
* better UI polish
* stronger analytics and dashboard visualizations
* more complete AI-powered categorization
* forecasting improvements
* better validation and error handling
* demo data / live demo flow

---

# Future Improvements

Planned improvements for later versions:

* advanced dashboard analytics
* category-wise charts and summaries
* recurring expenses
* anomaly detection for unusual spending
* better forecasting logic
* downloadable reports
* production deployment
* improved testing and documentation

---

# What I Learned

Through this project, I learned more about:

* how a full-stack app is structured
* how frontend and backend communicate
* how to organize backend code using routes, schemas, and models
* how an ML pipeline can be separated from the main application
* how AI can be used both **inside a product** and **during development**

---

# Running the Project

## Frontend

Go to the `frontend` folder and install dependencies:

```bash
npm install
npm run dev
```

## Backend

Go to the `backend` folder and install dependencies:

```bash
pip install -r requirements.txt
```

Then run the backend server using the project’s startup command.

## ML Pipeline

The ML pipeline contains scripts for experimenting with classifier training.

---

# Disclaimer

This project was built as a **learning project** and is still evolving.
It is not intended to be a production-grade financial product yet.

My main goal with this project was to learn how to build a **realistic full-stack application with AI-oriented features**, improve my development workflow, and create a stronger portfolio project as a student.

---

# Author

Built by Krithika  as part of my learning journey in **full-stack development + AI-based applications**.

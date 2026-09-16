# AI Expense Tracker

![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

![Screenshot](/images/file.png)

## Description
A full-stack, AI-powered personal finance management application that helps users track income, expenses, and budgets with intelligent insights.

## Features
* **Smart Transaction Tracking**: Easily log, filter, and categorize income and expenses.
* **Automated AI Insights**: Generates personalized monthly financial reports and savings tips using *Google Gemini*.
* **Dynamic Budgeting**: Real-time progress monitoring for custom categories with automatic AI-driven health verdicts.
* **Interactive Analytics**: Visualizes spending trends and category breakdowns via *Recharts*.

## Installation
Follow these steps to set up the project locally:

1. **Prerequisites**: Ensure you have *Node.js* (v18+) and *PostgreSQL* installed.
2. **Clone the repository**: `git clone <repository-url>`
3. **Set up Environment Variables**: Create `.env` files in both `backend` and `frontend` directories using the provided templates.
4. **Install Dependencies**:
   bash
   cd backend && npm install
   cd ../frontend && npm install
   
5. **Database Migration**: Run `npm run migrate` in the `backend` directory to set up your *Neon Postgres* schema.

## Usage
* **Start Backend**: `npm run dev` (from the `backend` folder).
* **Start Frontend**: `npm run dev` (from the `frontend` folder).
* **Data Seeding**: Execute `npm run seed` in the `backend` directory to populate your database with sample transactions for demonstration.

## Contributing
We welcome contributions! Please check our [CONTRIBUTING.md](CONTRIBUTING.md) guide for details on how to submit pull requests or report issues.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

*Note: This application provides financial information; for specific financial advice, please consult a professional.*
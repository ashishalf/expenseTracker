# Expense Tracker

## Overview

This Expense Tracker is a React application that helps you manage your finances by tracking your income and expenses. It provides a clear overview of your balance, as well as a detailed list of transactions.

## Features

- Display current balance
- Track income and expenses separately
- Add new transactions (income or expense)
- List all transactions
- Remove transactions from the list
- Context API for state management

## Installation

### Prerequisites

- Node.js installed on your system
- npm (Node Package Manager) or yarn

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/ashishalf/expenseTracker.git
cd expenseTracker
```

2. **Install the required packages**

Using npm:
```bash
npm install
```

Using yarn:
```bash
yarn install
```

3. **Start the application**

Using npm:
```bash
npm start
```

Using yarn:
```bash
yarn start
```

The application will start on `http://localhost:3000`.

## Usage

1. **Open the application in your browser**

   Navigate to `http://localhost:3000`.

2. **Track your finances**

   - View your current balance at the top.
   - See a summary of your income and expenses.
   - Add new transactions using the form provided.
   - View the list of all transactions and delete any transaction if needed.

## Code Explanation

### Components

- **Header**: Displays the application header.
- **Balance**: Shows the current balance.
- **IncomeExpenses**: Displays a summary of income and expenses.
- **TransactionList**: Lists all transactions.
- **AddTransaction**: Form to add new transactions.

### Context API

- **GlobalProvider**: Provides the global state to the application using Context API.

### Styles

- **App.css**: Contains the styles for the application.

### Application Structure

The `App` component wraps all the components with the `GlobalProvider` to manage the global state. Each component is responsible for a specific part of the application:

- `Header`: Displays the title.
- `Balance`: Shows the current balance by calculating the difference between income and expenses.
- `IncomeExpenses`: Displays the total income and total expenses separately.
- `TransactionList`: Renders a list of transactions, each with a delete button.
- `AddTransaction`: Provides a form to add new transactions (income or expense).

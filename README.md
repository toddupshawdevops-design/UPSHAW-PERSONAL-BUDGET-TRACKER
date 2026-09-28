# Personal Budget Tracking System - Week 4 MVC

**Student:** Todd Upshaw  
**Course:** ECPI University - SDC310L  
**Project:** Personal Budget Tracker  
**Phase:** Week 4 - Applying MVC

## MVC Structure
- `config/database.php` - database connection
- `models/Transaction.php` - transaction data operations
- `models/SavingsGoal.php` - savings goal data operations
- `controllers/BudgetController.php` - request processing
- `views/index.php` - HTML/CSS presentation
- `public/index.php` - application entry point
- `database.sql` - database structure
- `README.md` - documentation

## Features
- Create, Read, Update, and Delete transactions
- Create, Read, and Delete savings goals
- Income, expense, and balance calculations
- Savings goal progress
- MySQL prepared statements

## Database
Database: `todd_budget_tracker`
Tables: `transactions`, `savings_goals`
User: `ecpi_user`

## Run
1. Start Apache and MySQL in XAMPP.
2. Put the project in `C:\xampp\htdocs`.
3. Verify the database exists.
4. Open:
`http://localhost/Todd_Upshaw_SDC310L_Week4_MVC/public/`

## Week 4 Goal
The application is reorganized using MVC so database access, request processing, and presentation are separated into different components.

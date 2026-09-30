# Personal Budget Tracker - PHP MVC Web Application

A lightweight, web-based Personal Budget Tracker designed to manage income, monitor expenses, and review spending habits. Built using PHP, MySQL (PDO), and HTML/CSS, this project demonstrates a clean implementation of the **Model-View-Controller (MVC)** software architecture.

---

## 🏗️ Architectural Overview

The application strictly enforces separation of concerns across three distinct layers:

```text
personal_budget_tracker/
├── .vscode/
│   └── launch.json            # VS Code run/debug configuration
├── controller/
│   └── budget_controller.php  # Controller: Request handling & business logic
├── model/
│   └── budget_model.php       # Model: Database abstraction & PDO queries
├── view/
│   └── dashboard.php          # View: User interface & presentation template
├── index.php                  # Application Front Controller / Entry Point
└── README.md                  # Documentation

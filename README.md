# 💰 AI-Powered Budget Management System

A full-stack personal finance application built with **React.js, React Native, Spring Boot, MySQL**, and **Spring AI**.

Track income, expenses, budgets, and spending patterns through web and mobile applications, with AI-powered financial assistance.

## 🚀 Live Demo

**[Open Web Application](https://budget-tracker-frontend-weld-five.vercel.app/login)**

## 📂 Project Repositories

### 🌐 Web Application
React.js frontend for the web platform.

**[View Web Repository](https://github.com/AnkanIT24/budget-tracker-frontend)**

### 📱 Mobile Application
React Native (Expo) mobile application using the same backend API.

**[View Mobile Repository](https://github.com/AnkanIT24/budget-tracker-frontend-react-native)**

### ⚙️ Backend API
Spring Boot REST API handling authentication, transactions, categories, budgets, and database operations.

**[View Backend Repository](https://github.com/AnkanIT24/budget-tracker-backend)**

## 🏗️ Architecture

```text
React.js Web ────────┐
                     │
React Native Mobile ─┤
                     ▼
              Spring Boot REST API
                     │
          ┌──────────┴──────────┐
          │                     │
   Spring Security          Spring AI
        + JWT                   │
          │                     ▼
          │                    LLM
          │
          ▼
   Spring Data JPA
          │
          ▼
        MySQL


✨ Core Features
1.JWT authentication and user isolation
2.Income and expense tracking
3.Category management
4.Monthly budgets and spending limits
5.Transaction filtering and summaries
6.Responsive web application
7.React Native mobile application
8.Dockerized Spring Boot backend
9.AI-powered spending analysis and assistance


🤖 AI Features
1.Natural-language queries about personal spending
2.AI-powered spending analysis
3.Budget insights and recommendations
4.Tool calling for controlled access to financial data
5.User-authorized budget actions

| Layer       | Technologies                      |
| ----------- | --------------------------------- |
| Web         | React.js, Vite, Tailwind CSS      |
| Mobile      | React Native, Expo                |
| Backend     | Java 17, Spring Boot              |
| Security    | Spring Security, JWT              |
| Database    | MySQL, Spring Data JPA, Hibernate |
| AI          | Spring AI, LLMs                   |
| Engineering | Docker, Git, GitHub, Maven        |


👨‍💻 Author
Ankan Chakraborty

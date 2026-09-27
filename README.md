# 🌾 FarmTrek – Digital Marketplace & Supply Chain System for Farmers

FarmTrek is a digital marketplace and supply-chain platform designed to connect farmers and buyers while providing agricultural market information, AI-based price forecasting, route optimisation, and supporting digital services.

The project combines a React-based frontend with backend services and AI-driven functionality to support farmers, buyers, and supply-chain operations.

## 📌 Project Overview

Traditional agricultural supply chains can involve multiple intermediaries and limited access to timely market information.

FarmTrek provides a digital platform where farmers can manage their produce, access market information, connect with buyers, and use intelligent features for better decision-making.

The system includes AI and algorithmic components for:

- Agricultural price forecasting
- Route optimisation
- Market insights
- Recommendation-based functionality

## ✨ Key Features

### 👨‍🌾 Farmer Module

- Farmer registration and account management
- Produce management
- Access to agricultural market information
- Supply and delivery-related functionality

### 🛒 Buyer Module

- Browse available agricultural produce
- Connect with farmers
- Access market-related information

### 📊 Market Insights

- Agricultural market price information
- External data integration
- Data-driven market insights

### 🤖 AI-Powered Features

- ARIMA-based agricultural price forecasting
- Recommendation-based functionality
- Intelligent market insights

### 🚚 Route Optimisation

- A* algorithm-based route optimisation
- Supports supply-chain and delivery planning

### 🔐 User Management

- Role-based application functionality
- Separate workflows for different user roles

### 🔗 API Integration

The project is designed to work with external services and APIs for:

- Weather information
- Market prices
- Government agricultural data
- Maps and route information

## 🏗️ System Architecture


```text
                    ┌─────────────────────┐
                    │        Users        │
                    │  Farmers / Buyers   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │      FarmTrek       │
                    └──────────┬──────────┘
                               │
                          REST APIs
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Django / Python   │
                    │       Backend       │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
        ┌───────────┐   ┌────────────┐   ┌─────────────┐
        │ Firebase  │   │  AI / ML   │   │  External   │
        │ Database  │   │  Services  │   │    APIs     │
        └───────────┘   └─────┬──────┘   └─────────────┘
                              │
                       ┌──────┴──────┐
                       │             │
                       ▼             ▼
                    ARIMA            A*
               Price Forecast   Route Optimisation
```
## 🧠 AI & Algorithmic Components

### ARIMA Price Forecasting

FarmTrek uses an ARIMA-based forecasting approach to analyse historical agricultural price data and generate price predictions.

This provides additional information to support market-related decision making.

### A* Route Optimisation

The A* algorithm is used for route optimisation within the supply-chain workflow.

It helps identify an efficient route between relevant locations based on available route information.

### Recommendation System

The system also incorporates recommendation functionality to provide relevant information to users.

## 🛠️ Technology Stack

### Frontend

- React.js
- JavaScript
- HTML
- CSS
- Tailwind CSS
- Material UI
- Axios
- React Router

### Backend

- Python
- Django REST Framework
- REST APIs

### Database & Storage

- Firebase

### AI / Machine Learning

- Python
- ARIMA
- Statsmodels
- A* Algorithm
- Recommendation System

### External APIs

- Weather API
- Government/Data APIs
- Agricultural Market Price API
- Maps API

### Development Tools

- Git
- GitHub
- Visual Studio Code
- Jupyter Notebook

## 📂 Repository Structure

```text
FarmTrek/
│
├── api/
├── backend/
├── public/
├── src/
├── .github/
├── package.json
├── package-lock.json
├── build.zip
├── README.md
└── .gitignore
```

## ⚙️ Frontend Setup

### 1. Clone the repository

git clone https://github.com/Gayathri077/FarmTrek.git

cd FarmTrek

### 2. Install dependencies

npm install

### 3. Start the development server

npm start

The React development server runs at:

http://localhost:3000

## 🏗️ Build for Production

To create a production build:

npm run build

The production files will be generated in the build directory.

## 🧪 Testing

Run the React test suite with:

npm test

## 📊 Project Scope

FarmTrek is designed around several major functional areas:

## 📊 Project Scope

```text
                         FarmTrek
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
          Farmer          Buyer       Supply Chain
             │              │              │
             ▼              ▼              ▼
       Manage Produce   Browse Produce   Deliveries
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                    Market Information
                            │
                 ┌──────────┴──────────┐
                 │                     │
                 ▼                     ▼
          Price Forecasting      Route Optimisation
                 │                     │
                 └──────────┬──────────┘
                            ▼
                  AI-Powered Decision
                       Support
```

## 🎯 Key Concepts Demonstrated

This project demonstrates practical experience with:

- Full-stack web application development
- React.js frontend development
- REST API integration
- Django REST Framework
- Python development
- Database integration
- API integration
- Machine learning
- Time-series forecasting
- Route optimisation algorithms
- Role-based application design
- Supply-chain workflow modelling

## 📸 Screenshots

Add application screenshots here.

Example:

![FarmTrek Dashboard](screenshots/dashboard.png)

Recommended screenshots:

- Login / Registration
- Farmer Dashboard
- Buyer Dashboard
- Market Information
- Produce Management
- Price Prediction
- Route Optimisation
- Main Marketplace

## 🚀 Future Enhancements

- Mobile application
- Voice assistant for farmers
- Multilingual and regional-language support
- IoT-based agricultural monitoring
- AI chatbot for agricultural assistance
- Improved predictive models
- Online payment integration
- Advanced logistics tracking
- Real-time notifications

## 🌐 Project

Live Project:
https://farmersmarket-seven.vercel.app/

GitHub Repository:
https://github.com/Gayathri077/FarmTrek

## 👩‍💻 Author

Gayathri T

GitHub:
https://github.com/Gayathri077

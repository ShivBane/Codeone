Portfolio Tracker Application 📈
 
A simple portfolio tracker application that allows users to manage their stock holdings, track real-time portfolio value, and view key metrics via an intuitive dashboard.

Features 🚀

Frontend

Responsive Dashboard: Displays total portfolio value, top-performing stock, and portfolio distribution.

Stock Management: Add, edit, view, and delete stock holdings.

Real-Time Data: Dynamically updates portfolio value using live stock prices from a stock price API.

Backend

CRUD Operations: RESTful APIs to manage stock details.

Portfolio Value Calculation: Computes the total portfolio value based on real-time prices.

Robust Architecture: Built with Java and Spring Boot. Includes exception handling and meaningful HTTP status codes.

Database

Relational Design: Uses MySQL for storing stock details (stock name, ticker, quantity, buy price) with efficient schema design.

Predefined Portfolio: Includes 5 randomly picked stocks per user with a default quantity of 1 for assignment purposes.

Deployment

Frontend: Deployed on Vercel/Netlify for seamless access.

Backend: Hosted on Heroku/AWS/Render with live API integration.

Tech Stack 🛠️

Frontend

React.js (Preferred)

CSS Framework: TailwindCSS / Bootstrap / Material-UI

Backend

Java with Spring Boot

JPA & Hibernate

Database

MySQL

Real-Time Data API

Alpha Vantage / Yahoo Finance / Finnhub

How to Run Locally 🖥️

Prerequisites

Node.js and npm (for frontend)

Java (JDK 17 or above)

MySQL server

Maven (for backend dependencies)

Steps

Backend

Clone the repository and navigate to the backend folder.

Update the application.properties file with your MySQL configuration.

Build and run the application:

mvn clean install  

mvn spring-boot:run  

Frontend

Navigate to the frontend folder.

Install dependencies:

npm install  

Start the development server:

npm start  

Database Setup

Create a new MySQL database.
Run the SQL script provided in the database folder to set up the schema.

ABC Company Website

A responsive website for Company ABC with a dynamic heading managed via a CMS. Built with React (front-end) and Node.Js (back-end).

🚀 Project Overview

Front-End: React, Axios, Styled-Components (or your chosen styling framework)

Back-End: Node.Js, SQL Database (e.g., PostgreSQL/MySQL)

CMS: Custom page to update dynamic heading

Deployment: [Netlify/Vercel] (Front-End) + [Heroku/AWS] (Back-End)

⚙️ How to Run Locally

Prerequisites

Node.js & npm

SQL Database (PostgreSQL/MySQL)

Clone Repository
git clone https://github.com/bhavanacreate/Brewex_Product_Consulting_Assignment

cd Brewex_Product_Consulting_Assignment

Set Up Front-End

cd Brewex_Product_Consulting_Assignment

npm install

npm start

🔗 API Endpoints

POST /api/heading

Saves heading text to database

Request Body:

{ "heading": "Your Heading Text" }

GET /api/heading

Retrieves heading text as JSON

Response:

{ "heading": "Your Heading Text" }

📝 Database Schema

Table: heading

Column	Type

id	    Integer

heading	Varchar

🌐 Deployment

Front-End: Deploy to Netlify/Vercel

Back-End: Deploy to Heroku/AWS

Configure environment variables for DB and API URLs.

✅ Features

Pixel-perfect design based on Figma

Dynamic heading fetched via API

CMS page to update heading text

Responsive and cross-browser compatible


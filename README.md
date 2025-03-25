![image](https://github.com/user-attachments/assets/c7c0a1bf-b696-48f5-a2d7-ccd42ab45123)
# SmartEmail Writer - Frontend

## Overview
SmartEmail Writer is a web-based application that generates AI-powered email replies based on user input. The application utilizes Google's **Gemini API** to analyze the original email content and generate a relevant response. Users can also select a desired tone for the response.

## Repository Structure
- **main branch** → Contains the backend code (Spring Boot API).
- **master branch** → Contains the frontend code (React + Vite).
- **chrome-extention** → Contains the Chrome extention code.

## Frontend Tech Stack
The frontend of SmartEmail Writer is built using **React** via **Vite**, providing a fast and optimized development experience. The application leverages **Material UI** for styling and UI components.

### Key Technologies & Libraries Used
- **React** (via Vite) → For fast, modular frontend development
- **Material UI** → For modern and responsive UI components
- **Fetch API / Axios** → To communicate with the backend

## Features
- **Generate AI-powered email replies** using the **Gemini API**
- **Customize reply tone** (Casual, Formal, etc.)
- **Copy response** to clipboard for easy use
- **Responsive and user-friendly UI**

## Backend API Integration
The frontend interacts with the **backend API**, which is hosted on the **main branch** of the repository. The backend uses **Spring Boot** to handle requests and integrates with **Gemini's API** to generate email replies.

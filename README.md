![image](https://github.com/user-attachments/assets/63cf72a9-f9a4-48d7-a214-3429ef561254)

# SmartEmail Writer - Backend

## Overview
SmartEmail Writer is a backend service built using **Spring Boot**. It provides an API that integrates with **Google's Gemini API** to generate AI-powered email replies based on user input and selected tone.

## Repository Structure
- **main branch** → Contains the backend code (Spring Boot API).
- **master branch** → Contains the frontend code (React + Vite).
- **chrome-extention** → Contains the Chrome extention code.

## Tech Stack
- **Spring Boot** → For building the RESTful backend API.
- **Gemini API** → Used for AI-powered email response generation.
- **Postman (for testing)** → Used to test API endpoints.

## Features
- **Generate AI-powered email replies** using the **Gemini API**.
- **Accepts email content & tone** as input parameters.
- **Returns an AI-generated response** in a structured format.

## Installation & Running the Backend Locally
### Prerequisites
- Java (>= 11)
- Maven

### Steps to Run the Backend
1. Clone the repository and switch to the backend branch:
   ```sh
   git clone -b main https://github.com/BemanZayed/AiEmail-Writer.git
   cd AiEmail-Writer
   ```
2. Build and run the Spring Boot application:
   ```sh
   mvn spring-boot:run
   ```
3. The backend API should be running at `http://localhost:8080/api/email/generate`.

## API Testing
You can test the API by sending a **POST request** to:
```
http://localhost:8080/api/email/generate
```
With the following JSON body:
```json
{
  "emailContent": "Hi, how are you?",
  "tone": "friendly"
}
```
### Example Response
```json
{
  "response": "Hi there! I'm doing well, thanks for asking! How are you? Let me know if there's anything I can help you with. Best, [Your Name]"
}
```
## License
This project is licensed under the MIT License.


### **Email Writer Assistant**  
**AI-powered email reply generator for Gmail.**  

## **Description**  
Email Writer Assistant adds an **"AI Reply"** button to Gmail, allowing users to generate AI-powered email responses with one click.  

📂 Repository Structure
main branch → Contains the backend code (Spring Boot API).
master branch → Contains the frontend code (React + Vite).
chrome-extention branch → New branch for the Chrome Extension.



## **Features**  
✅ Adds an "AI Reply" button in Gmail.  
✅ Extracts email content for AI-generated replies.  
✅ Inserts the generated reply directly into the compose box.  

## **API Integration**  
The extension sends a POST request to `http://localhost:8080/api/email/generate` with the extracted email content. Ensure your AI service is running at this endpoint.  

## **Permissions**  
- **activeTab** – To interact with the Gmail tab.  
- **storage** – To store settings if needed.  
- **host_permissions** – To access `mail.google.com` and `localhost:8080`.  

## **Troubleshooting**  
🔹 Refresh Gmail if the AI Reply button doesn’t appear.  
🔹 Ensure your backend API is running.  
🔹 Check the Chrome console (`Ctrl + Shift + J`) for errors.  


# 📌 Code Reviewer App

## 🚀 Overview
The **Code Reviewer App** is a web-based tool that allows users to analyze and review JavaScript, HTML, and CSS code snippets. Built with modern web technologies, it integrates AI-powered suggestions and improvements for better code quality.

---

## 🏗️ Tech Stack
- **Frontend:** React, Vite, JavaScript, HTML, CSS
- **Backend:** Node.js, Express.js
- **AI Integration:** Google Gemini API
- **Development Tools:** Postman, VS Code, npm, nodemon
- **Environment Management:** `.env` for configuration settings

---

## 📂 Project Structure
```
📦 code-review
 ┣ 📂 backend
 ┃ ┣ 📂 controllers
 ┃ ┣ 📂 routes
 ┃ ┣ 📂 services
 ┃ ┣ 📜 server.js
 ┃ ┣ 📜 .env
 ┃ ┣ 📜 package.json
 ┃ ┗ 📜 package-lock.json
 ┣ 📂 frontend
 ┃ ┣ 📂 public
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 components
 ┃ ┃ ┣ 📂 pages
 ┃ ┃ ┣ 📜 App.jsx
 ┃ ┃ ┣ 📜 index.html
 ┃ ┃ ┣ 📜 main.jsx
 ┃ ┃ ┣ 📜 styles.css
 ┃ ┃ ┗ 📜 reviewCode.jsx
 ┃ ┣ 📜 package.json
 ┃ ┣ 📜 vite.config.js
 ┃ ┣ 📜 .gitignore
 ┗ 📜 README.md
```

---

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/code-review.git
cd code-review
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the **backend** directory and add your API keys:
```env
PORT=3000
AI_API_KEY=your_google_gemini_api_key
```

### 4️⃣ Start the Development Server
```sh
npm run dev
```
The application should now be running at `http://localhost:5173`

---

## 🎯 Features
- 📜 **Syntax Highlighting**: Automatically highlights code for better readability.
- 🤖 **AI Code Review**: Uses Google Gemini to analyze and suggest improvements.
- ⚡ **Fast Development**: Powered by Vite for lightning-fast builds.
- 🌍 **Full Stack**: Backend API built with Express.js for handling requests.
- 🛠 **Error Handling**: Ensures smooth user experience with proper validation.

---

## 📜 API Endpoints
### 🔹 **POST /ai/get-review**
- **Description**: Analyzes the submitted code and provides feedback.
- **Request Body:**
```json
{
  "code": "const a = 10;"
}
```
- **Response:**
```json
{
  "suggestions": [
    "Use const only when values don’t change.",
    "Follow consistent indentation."
  ]
}
```

## Snapshots

![image](https://github.com/user-attachments/assets/aafad90f-f165-4a69-b114-290ca9ce84c2)

![image](https://github.com/user-attachments/assets/dd1cf302-6068-4977-88e5-899e966dbb69)


![image](https://github.com/user-attachments/assets/2f6b1f19-8eaf-4195-a4ca-151d7f383877)


![image](https://github.com/user-attachments/assets/31febab5-d18c-40dd-8734-34626a43a14e)



---

## 📌 Future Enhancements
- 🚀 Implement user authentication for saving reviews.
- 📊 Integrate a dashboard for tracking code quality over time.

---




🚀 **Happy Coding!** 🎯


# AI Code Reviewer

📌**Project Description**

The AI Code Reviewer is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that integrates Artificial Intelligence to help developers write better code.

Instead of manually reviewing every line of code, this project uses an AI model (like GOOGLE GEMINI) to automatically analyze the submitted code, highlight mistakes, and suggest improvements. The goal is to make the process of code quality checks, bug detection, and best-practice enforcement faster and more efficient.

🔍 **What It Does**

*Developers can paste their code into the web app.

*The backend sends the code to the AI service for analysis.

*AI reviews the code and provides:

 *Suggestions for cleaner, optimized code.

 *Warnings about possible errors or inefficiencies.

 *Recommendations based on coding best practices.

*The reviewed feedback is displayed in the frontend in a user-friendly way.

🎯 **Why This Project?**

Code reviews are an important part of software development but can be time-consuming when done manually. This project shows how AI can act as a virtual mentor or assistant, helping developers learn and improve their coding skills instantly.

It can be useful for:

*Students & Beginners – to get quick code feedback while learning.

*Developers – to catch mistakes before submitting code for team review.

*Teams – to automate part of the review process and save time.

🧩 **Key Highlights**

*Full-Stack Implementation: Both backend and frontend included.

*AI Integration: Uses an API key to connect with an AI model.

*Real-Time Feedback: Developers get instant AI suggestions after submitting code.

*Scalable Design: Can be deployed on platforms like Vercel, Render, or Heroku.

## ✨ **Features**
- Paste code and get AI-based feedback.
- Frontend built with React.
- Backend built with Node.js + Express.
- AI integration for code review.

## 🛠️ **Tech Stack**
- **Frontend:** React, CSS, HTML  
- **Backend:** Node.js, Express  
- **AI API:** (like GOOGLE GEMINI – put your key in `.env` file)

## 🚀 How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/adityapandey77/AI-code-reviewer.git
   cd AI-code-reviewer

2.**Backend setup**
  ```bash
cd Backend
npm install
```


Create a file named .env in the Backend folder and add:
```bash
PORT=5000
MONGODB_URI=your_mongodb_uri
AI_API_KEY=your_api_key_here
```

3.Frontend setup
```
cd ../Frontend
npm install
```

4.Run the project

Start backend:
```
cd Backend
npm start
```

Start frontend:
```
cd ../Frontend
npm run dev
```

5.Open http://localhost:3000
 in your browser.

📖**Usage**

Open the app.

Paste your code.

Get AI feedback and suggestions instantly.

🤝 **Contributing**

Want to improve this project? Fork the repo and create a pull request.

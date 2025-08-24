# AI Code Reviewer

This is a **MERN stack project** (MongoDB, Express, React, Node.js) that uses **AI to review code**.  
You can paste your code into the app, and it will give suggestions and improvements using AI.

## ✨ Features
- Paste code and get AI-based feedback.
- Frontend built with React.
- Backend built with Node.js + Express.
- AI integration for code review.

## 🛠️ Tech Stack
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

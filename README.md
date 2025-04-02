# 🚀 Full Stack Developer Technical Challenge  
## 🐦 Build "Tweety with AI"
📖 Challenge Description
Welcome! This is your technical challenge for the Full Stack Developer position.

In this task, you'll build a simplified social media platform — similar to Twitter — with a twist: an integrated AI assistant that helps users craft tweet content. The app will include features like user authentication, tweet creation, a real-time feed, and detailed user profiles enhanced with AI-generated insights.

Your goal is to demonstrate your skills in full-stack development, including frontend UI, backend APIs, database modeling, and external API integration. We’re looking for clean code, thoughtful structure, and a user-friendly experience. Creativity is welcome — especially in how you design the profile page and integrate AI.


---

### 📌 Objective

Build a **mini social media platform** similar to Twitter, where users can:
- Register and log in
- Post tweets
- View a global tweet feed
- Chat with an AI assistant that helps with tweet ideas
- Have a rich user profile with tweet stats and AI insights

---

### 🧱 Tech Stack

| Area       | Tech Stack                         |
|------------|------------------------------------|
| Frontend   | React (with Hooks, Context, or Redux) |
| Backend    | Node.js + Express                  |
| Database   | MongoDB + Mongoose                 |
| Auth       | JWT-based Authentication           |
| AI Chat    | OpenAI API or Mock AI Service      |
| Styling    | Tailwind CSS (optional)            |

---

### 🛠 Core Features

#### 1. Authentication
- User Signup and Login (email + password)
- JWT token-based authentication for protected routes

#### 2. Tweeting System
- Create a tweet (max 280 characters)
- View all tweets (global feed)
- Tweet shows:
  - Text
  - Username
  - Timestamp (e.g., "3 mins ago")
  - (Optional) Like count or like button

#### 3. Global Tweet Feed
- Feed displays latest tweets first
- Auto-refresh on new tweet or manual refresh
- Bonus: Add pagination or infinite scroll

#### 4. AI Chat Assistant
- Simple chat interface where users can:
  - Ask AI for tweet suggestions (e.g., "Suggest a funny tweet about Monday")
  - Post the AI-generated message as a tweet
- Integrate real OpenAI API or use a mock response if no API key is available

#### 5. Custom User Profile
Each user should have a public profile page:
- Avatar and cover image (upload or default)
- Bio, location, join date
- List of tweets
- Tweet analytics (e.g., tweet count, chart of tweets per day)
- AI-generated insight (e.g., "You tweet mostly about tech and food")

---

### 🔌 Suggested API Routes

#### Auth
```
POST   /api/auth/signup
POST   /api/auth/login
```

#### Tweets
```
GET    /api/tweets              // global feed
POST   /api/tweet               // create tweet
GET    /api/user/:id/tweets     // user's tweets
```

#### Users
```
GET    /api/user/:id            // profile data
PUT    /api/user/:id            // update profile
```

#### AI Chat
```
POST   /api/ai/chat             // user prompt → AI response
```

---

### 🎨 Frontend Requirements

- Clean UI (no strict design rules — your creativity is welcome)
- Fully responsive (mobile and desktop)
- Use React functional components
- Handle loading and error states
- Pages to include:
  - Login / Signup
  - Home (tweet feed)
  - AI Chat
  - Profile

> 🔄 You can structure your project however you want — we value clean thinking and readable architecture over rigid structure.

---

### 🧪 Bonus Features (Optional but Valued)
- Realtime updates with WebSockets (e.g., new tweets)
- Dark mode toggle
- Docker setup
- Unit tests for API
- Deploy the app (e.g., Vercel, Netlify, Render)

---

### 📦 Submission Requirements

- GitHub link with README
- README should include:
  - Setup instructions (backend & frontend)
  - `.env.example` for environment variables
  - Short note on what you’d improve with more time
  - (Optional) Screenshots or a short demo video

---

### ⏱ Time Limit
- **Mid-level:** 48 hours  
- **Senior-level:** 36–48 hours  
- **Junior-level:** 72 hours

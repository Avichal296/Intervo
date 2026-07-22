## AI Interviewer

# 🚀 AI Interviewer

A modern AI-powered interview platform designed to simulate real-world technical interviews through conversational AI, intelligent evaluation, resume-aware questioning, and real-time interaction.

The platform enables candidates to practice interviews, receive detailed AI-generated feedback, improve communication skills, and prepare for technical hiring processes using state-of-the-art Large Language Models.

---

## ✨ Features

### 🤖 AI Interview Assistant
- AI-generated interview questions
- Dynamic follow-up questions
- Adaptive interview flow
- Context-aware conversations
- Role-based interview generation
- Experience-level customization

### 📄 Resume-Based Interviews
- Resume upload & parsing
- Personalized interview generation
- Project-specific questioning
- Skill-based interview flow

### 🎙️ Conversational AI
- Natural interview conversations
- Real-time AI interaction
- Human-like interview experience
- Context preservation throughout the interview

### 📊 AI Evaluation
- Technical assessment
- Communication analysis
- Problem-solving evaluation
- Confidence scoring
- Detailed interview feedback
- Personalized improvement suggestions

### ⚡ Real-Time Experience
- WebSocket powered communication
- Instant AI responses
- Live interview sessions
- Low latency interactions

### 🌐 Smart Data Collection
- Intelligent web scraping
- Structured interview data extraction
- Automated content processing

### 📈 Analytics
- Interview history
- Performance reports
- Overall interview score
- Progress tracking

---

# 🏗 Monorepo Structure

```
AI-Interviewer/
│
├── apps/
│   │
│   ├── frontend/
│   │   ├── src/
│   │   ├── styles/
│   │   ├── components.json
│   │   ├── bunfig.toml
│   │   └── package.json
│   │
│   └── backend/
│       ├── prisma/
│       ├── scrapers/
│       ├── index.ts
│       ├── db.ts
│       ├── result.ts
│       ├── sideband.ts
│       ├── prisma.config.ts
│       └── package.json
│
├── packages/
│   └── eslint-config/
│
├── turbo.json
├── bun.lock
└── package.json
```

---

# 🛠 Tech Stack

## Frontend

- React.js
- TypeScript
- Tailwind CSS
- shadcn/ui

## Backend

- Express.js
- Bun
- TypeScript
- Prisma ORM
- PostgreSQL

## AI

- OpenAI
- Google Generative AI (Gemini)

## Real-Time

- WebSockets

## Database

- PostgreSQL
- Prisma ORM

## Data Collection

- Custom Web Scrapers

## Monorepo

- Turborepo

---

# ⚙️ Architecture

```
                ┌────────────────────┐
                │    React Frontend   │
                └─────────┬───────────┘
                          │
                    WebSockets / REST
                          │
                ┌─────────▼───────────┐
                │   Express Backend    │
                └─────────┬───────────┘
                          │
        ┌─────────────────┼──────────────────┐
        │                 │                  │
        ▼                 ▼                  ▼
   OpenAI API      Google Gemini      Web Scrapers
        │
        ▼
  AI Evaluation Engine
        │
        ▼
 PostgreSQL + Prisma ORM
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Avichal296/AI-Interviewer.git

cd AI-Interviewer
```

## Install Dependencies

```bash
bun install
```

## Configure Environment Variables

Create a `.env` file inside the backend.

```env
DATABASE_URL=

OPENAI_API_KEY=

GOOGLE_GENERATIVE_AI_API_KEY=

JWT_SECRET=

PORT=
```

## Generate Prisma Client

```bash
bun prisma generate
```

## Run Database Migration

```bash
bun prisma migrate dev
```

## Start Development

```bash
bun dev
```

---

# 🚀 Core Capabilities

- AI Mock Interviews
- Resume-Aware Interviews
- Adaptive Question Generation
- Real-Time Conversations
- Technical Interview Simulation
- Behavioral Interview Simulation
- AI-Based Candidate Evaluation
- Performance Reports
- Communication Assessment
- Interview History
- Personalized Feedback
- Intelligent Web Scraping

---

# 📌 Why AI Interviewer?

- Production-ready Monorepo Architecture
- Modern React Frontend
- High-performance Bun Backend
- AI-powered Interview Engine
- Type-safe Codebase
- Real-Time Communication
- Scalable System Design
- Clean & Modular Architecture

---

# 🔮 Future Roadmap

- Video Interview Support
- Voice-to-Voice AI Interviews
- Collaborative Coding Interviews
- Recruiter Dashboard
- Organization Workspaces
- Company-specific Interview Templates
- Interview Scheduling
- Calendar Integration
- Multi-language Support
- Advanced Candidate Analytics

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve the project, feel free to fork the repository, create a new branch, and submit a pull request.

---

# 📄 License

This project is licensed under the MIT License.

---

## Built with ❤️ using React, TypeScript, Bun, Express.js, PostgreSQL, Prisma ORM, WebSockets, OpenAI, Google Generative AI, Tailwind CSS, shadcn/ui, and Turborepo.

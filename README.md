# Mind Haven — Aurora

Mind Haven — Aurora is a compassionate mental health platform built for people who feel stuck, unheard, or unable to speak openly about what they are going through. It creates a safe space where users can stay anonymous, connect with others facing similar struggles, and receive gentle, empathetic guidance without exposing their identity.

## Mission

Reduce stigma and make emotional support more accessible by offering a private, human-first place to reflect, connect, and heal.

## What Makes Mind Haven Different

- **Anonymous-first design:** Users can participate without revealing their identity.
- **Peer connection:** Community circles connect people dealing with similar challenges.
- **Empathetic AI support:** A 24/7 listener for reflection, journaling, and emotional check-ins.
- **Specialist network:** Find verified professionals when you are ready to seek help.
- **Mood awareness:** AI-driven insights help users recognize patterns and trends over time.

## Core Experiences

1. **Cognitive Lab (AI Journaling)**
   - Write freely and receive supportive, thoughtful responses.
2. **Empathetic Chat**
   - A gentle companion for late-night thoughts or immediate support.
3. **Community Circles**
   - Safe, moderated spaces built around shared experiences.
4. **Standard & Incognito Accounts**
   - Choose between professional care or total anonymity.

## Tech Stack

- **Frontend:** React + TypeScript + Vite
- **Styling:** Neo-brutalist UI with custom shadow utilities
- **Backend:** Node.js + Express
- **Database:** MongoDB Atlas
- **AI/ML:** Google Gemini + Python embeddings service
- **Auth:** Firebase Authentication + JWT session management

## Project Structure

```
.
├── components/      # Reusable UI components
├── views/           # Screen-level views
├── services/        # API/client helpers
├── server/          # Express backend + AI orchestration
└── App.tsx          # Frontend entry point
```

## Getting Started

### Prerequisites

- Node.js 16+
- MongoDB Atlas account
- Google Gemini API key
- Firebase project

### Install Dependencies

```bash
# Frontend
npm install

# Backend
cd server
npm install
```

### Configure Environment

Create a `.env` file in `server/` with:

```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_key
```

### Run Locally

```bash
# Terminal 1: Backend
cd server
npm start

# Terminal 2: Frontend
cd ..
npm run dev
```

## Contributing

We welcome thoughtful contributions that keep the platform safe, empathetic, and privacy-respecting. Please open an issue or pull request with context about the change and how it supports the mission.

## Contributors

- [@sanhithaac](https://github.com/sanhithaac)
- [@Seventie](https://github.com/Seventie)

## Contact

Questions or ideas? Reach out via GitHub: [Seventie](https://github.com/Seventie)

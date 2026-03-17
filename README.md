# Interview AI Frontend

A React-based frontend application for an AI-powered interview preparation platform. This application helps job seekers prepare for interviews by analyzing their resumes against job descriptions and generating personalized interview strategies.

## Features

- **User Authentication**: Secure login and registration system
- **Resume Upload**: Upload your resume in PDF or DOCX format
- **Job Description Analysis**: Paste job descriptions to get tailored interview preparation
- **AI-Powered Reports**: Get personalized interview reports including:
  - Technical questions with model answers
  - Behavioral questions with guidance
  - Skill gap analysis
  - Day-by-day preparation roadmap
  - Match score for the role
- **Resume PDF Generation**: Download AI-optimized resumes tailored to specific job descriptions

## Tech Stack

- React 19
- React Router 7
- Vite 7
- SCSS for styling
- Axios for API communication

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Hazel-Singla/Interview-Ai-Frontend.git
cd Interview-Ai-Frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Project Structure

```
src/
├── features/
│   ├── auth/          # Authentication components and logic
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── pages/
│   │   └── services/
│   └── interview/     # Interview feature components
│       ├── hooks/
│       ├── pages/
│       ├── services/
│       └── style/
├── style/             # Global styles
├── App.jsx           # Main app component
├── app.routes.jsx    # Route definitions
└── main.jsx          # Entry point
```

## Environment Variables

The frontend expects the backend API to be running at `http://localhost:3000`. Update the API base URL in the services files if your backend is hosted elsewhere.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Backend Repository

This frontend connects to the Interview AI Backend API. Make sure to set up and run the backend for full functionality.

## License

ISC
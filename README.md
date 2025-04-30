# AI Mock Interviews

AI Mock Interviews is a modern, AI-powered web application designed to help users prepare for job interviews. The app generates tailored interview questions based on the user's job role, experience level, and technical stack. It provides a clean, professional UI with features like dark mode, real-time feedback, and user-specific dashboards.

---

## Features

- **AI-Powered Question Generation**: Generate interview questions tailored to job roles, experience levels, and tech stacks using Google's `gemini-2.0-flash-001` AI model.
- **User-Friendly Interface**: A clean and responsive UI with light and dark mode support.
- **Chat-Like Interaction**: Users can interact with the app via a chat interface to input their preferences and receive AI-generated questions.
- **User Dashboard**: View saved interview sessions, manage history, and generate new interviews.
- **Firebase Integration**: Secure user authentication and data storage using Firebase.
- **Real-Time Notifications**: Success and error messages displayed using the `Sonner` Toaster library.

---

## Tech Stack

- **Frontend**: Next.js, TailwindCSS
- **Backend**: Next.js API Routes
- **AI Integration**: Google AI SDK (`gemini-2.0-flash-001`)
- **Database**: Firebase Firestore
- **Authentication**: Firebase Authentication
- **Styling**: TailwindCSS with custom themes
- **Notifications**: Sonner Toaster library

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-mock-interviews.git
   cd ai-mock-interviews

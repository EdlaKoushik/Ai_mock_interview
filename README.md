# AI Mock Interviews 🧠💼

AI Mock Interviews is a modern, AI-powered web application designed to help users prepare for job interviews. The app generates tailored interview questions based on the user's job role, experience level, and technical stack. It provides a clean, professional UI with features like dark mode, real-time feedback, and user-specific dashboards.

---

## Features 🚀✨

- **🤖 AI-Powered Question Generation**: Generate interview questions tailored to job roles, experience levels, and tech stacks using Google's `gemini-2.0-flash-001` AI model.
- **🖥️ User-Friendly Interface**: A clean and responsive UI with light and dark mode support.
- **💬 Chat-Like Interaction**: Users can interact with the app via a chat interface to input their preferences and receive AI-generated questions.
- **📊 User Dashboard**: View saved interview sessions, manage history, and generate new interviews.
- **🔐 Firebase Integration**: Secure user authentication and data storage using Firebase.
- **⚡ Real-Time Notifications**: Success and error messages displayed using the `Sonner` Toaster library.

---

## Tech Stack 🛠️

- **🎨 Frontend**: Next.js, TailwindCSS
- **🖥️ Backend**: Next.js API Routes
- **🤖 AI Integration**: Google AI SDK (`gemini-2.0-flash-001`)
- **🗄️ Database**: Firebase Firestore
- **🔐 Authentication**: Firebase Authentication
- **🎨 Styling**: TailwindCSS with custom themes
- **🔔 Notifications**: Sonner Toaster library
- --

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-mock-interviews.git
   cd ai-mock-interviews
   
2.Install dependencies:
  npm install
  
3.Set up environment variables:
   1.Create a .env.local file in the root directory.
   2.Add the following variables:
GOOGLE_GENERATIVE_AI_API_KEY=your-google-api-key
NEXT_PUBLIC_FIREBASE_API_KEY=your-firebase-api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-firebase-auth-domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-firebase-project-id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-firebase-storage-bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-firebase-messaging-sender-id
NEXT_PUBLIC_FIREBASE_APP_ID=your-firebase-app-id
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your-firebase-measurement-id
  

--
4.Start the development
 npm run dev
5.Open the app in your browser:
http://localhost:3000


1.Sign up page:-Allows users to create an account and register for the platform.         
![WhatsApp Image 2025-04-30 at 15 11 11_9e256be0](https://github.com/user-attachments/assets/60c9013e-4054-4f71-8753-7f352c7be07a)

2.sign in page:- Enables users to log in securely to access their personalized dashboard.
![WhatsApp Image 2025-04-30 at 15 11 51_50750a49](https://github.com/user-attachments/assets/8f743ed6-e276-4e17-8890-d0fc84bf76bd)

3.Interview page:-Provides a form or chat interface to generate AI-powered interview questions.
![WhatsApp Image 2025-04-30 at 15 12 37_79ffe2f0](https://github.com/user-attachments/assets/8f208e90-bfb3-4ed9-8af6-b0e87f50de96)

4.dashboard/home:- Displays saved interviews, user activity, and options to generate new interviews.

![WhatsApp Image 2025-04-30 at 15 12 37_79ffe2f0](https://github.com/user-attachments/assets/c0111943-6b6a-477d-b2dc-f409402abab7)

5.Feedback page:-Collects user feedback on generated interview questions or platform experience.

![WhatsApp Image 2025-04-30 at 15 14 32_5272de7a](https://github.com/user-attachments/assets/5f8e3e60-7550-488e-b1fb-0254b90c320a)




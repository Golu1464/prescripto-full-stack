# Healthcare Management System

A modern web-based Healthcare Management System with patient and doctor management, appointments, and an AI-powered Healthcare Chatbot for multilingual health guidance.

---

## Features

### User Features
- **User Authentication**: Secure login and signup.
- **Profile Management**: Users can manage their profiles.
- **Appointments**: View, book, and manage appointments with doctors.
- **Contact Page**: Users can contact the hospital/clinic.

### Doctor Features
- **Doctor Listing**: Browse doctors by specialty.
- **Appointment Management**: View patient appointments and availability.

### AI Healthcare Assistant
- **Chatbot**: Provides health information and guidance using OpenAI GPT API.
- **Multilingual Support**: Detects language and provides health guidance in user's language.
- **Voice Input**: Users can speak their queries using the microphone.
- **Notifications**: Periodic notifications to engage users.
- **Guidance Format**: Answers structured in bullet points with doctor recommendation and emergency advice.

---

## Technologies Used
- **Frontend**: React, React Router, Tailwind CSS
- **Backend**: Node.js / Django / Express (adjust based on your backend)
- **Database**: SQLite / PostgreSQL / MySQL (adjust accordingly)
- **APIs**:
  - OpenAI GPT API (for chatbot)
  - Speech Recognition API (for voice input)
- **Other Libraries**: React Toastify, etc.

---

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/healthcare-management-system.git
cd healthcare-management-system
Install dependencies

bash
Copy code
npm install
Environment Variables

Create a .env file in the root directory with the following:

env
Copy code
VITE_OPENAI_API_KEY=your_openai_api_key_here
Run the project

bash
Copy code
npm run dev
The app will be available at http://localhost:5173 (for Vite) or http://localhost:3000 (for Create React App).

Usage
Navigate through the app using the navbar.

Use the Healthcare Chatbot to ask health-related questions. It supports multiple languages and voice input.

Book appointments with doctors based on specialties.

Manage your profile and view your appointment history.

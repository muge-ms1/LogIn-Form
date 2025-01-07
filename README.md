# Profile Page Application

This project is a user profile page built using React and styled with Tailwind CSS. The application fetches user data securely using a JWT-based authentication system and displays it in a responsive and visually appealing card format.

## Features

- **Secure Authentication**: JWT-based authentication to protect user data.
- **Dynamic Profile Display**: Fetch and display user details dynamically.
- **Responsive Design**: Built with Tailwind CSS for a modern and mobile-friendly UI.
- **User-Friendly**: Intuitive navigation and design.
- **Logout Functionality**: Clear logout button to manage user sessions securely.

---

## Project Structure

```
.
├── public/
│   └── index.html      # Main HTML file
├── src/
│   ├── Profile.js  # Profile page component
│   ├── context/
│   │   └── Context.js  # Context for global state management
│   ├── index.css   # Tailwind CSS setup
│   ├── App.js          # Main application component
│   ├── index.js        # Application entry point
├── package.json        # Project dependencies
├── tailwind.config.js  # Tailwind CSS configuration
└── .env                # Environment variables (e.g., backend URL)
```

---

## Setup Instructions

Follow the steps below to set up and run the project locally:

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher) or yarn
- Backend API endpoint for fetching user data

### Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Configure environment variables:
   - Create a `.env` file in the project root.
   - Add the following variable:
     ```env
     VITE_BACKEND_URL=http://your-backend-url.com
     ```

4. Start the development server:
   ```bash
   npm run server
   ```

5. Access the application:
   - Open (http://localhost:5173/) in your browser.

---

## Key Components

### **Profile.js**
- Displays the user's profile details (name, email, and image).
- Fetches data from the backend securely using a token stored in `localStorage`.

### **Context.js**
- Manages global state, such as backend URL and navigation functionality.

### **Tailwind CSS**
- Provides responsive and modern styling for the application.

---

## Security Features

- **JWT Authentication**: Ensures secure access to the profile page.
- **Token Validation**: Redirects unauthenticated users to the login page.
- **Error Handling**: Handles errors gracefully and logs them for debugging.

---




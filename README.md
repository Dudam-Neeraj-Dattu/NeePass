# NeePass

NeePass, a full-stack password manager application designed to store and manage the passwords. The project leverages a modern web stack for robust performance and security.

## Tech Stack

- **Frontend:** React.js, Redux, Tailwind CSS, Axios, HTML
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Features

- **Password Storage:** Safely store, retrieve, update, and delete passwords for various accounts.
- **Global State Management:** Utilizes Redux for managing application-wide state and React Hooks for local component state.
- **Asynchronous Operations:** Handles API requests and responses using Redux Thunk and Axios.
- **RESTful API:** Backend exposes structured endpoints for all CRUD operations.
- **Responsive UI:** Clean and intuitive interface for managing credentials with Tailwind CSS.

## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/Dudam-Neeraj-Dattu/NeePass.git
   ```

2. **Install dependencies for both frontend and backend:**
   ```
   cd password-manager
   npm install
   cd backend
   npm install
   ```

3. **Set up environment variables:**  
   Create a `.env` file in the backend directory with your MongoDB URI and any required secrets.

4. **Run the application:**
   - Start the backend server:
     ```
     cd backend
     node --watch server.js
     ```
   - Start the frontend:
     ```     
     npm run dev
     ```

## License

This project is licensed under the MIT License.

---

Feel free to contribute or open issues for suggestions and improvements!
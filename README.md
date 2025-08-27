# ThinkBoard 📝

A full-stack note-taking application built with the MERN stack, featuring modern React patterns, RESTful APIs, and responsive design.

## 🚀 Live Demo

**[View Live Application](https://thinkboard-gxxz.onrender.com/)** Takes a couple minutes to load for the first time

## 🛠️ What I Built

### Core Features Implemented
- **Full CRUD Operations**: Create, read, update, and delete notes with real-time feedback
- **React State Management**: Utilized React hooks (useState, useEffect) for component state
- **Client-Side Routing**: Implemented React Router for seamless navigation
- **Form Validation**: Added comprehensive input validation with user-friendly error messages
- **Responsive Design**: Mobile-first approach using Tailwind CSS and DaisyUI components
- **API Integration**: Connected frontend to custom Express.js backend with Axios
- **Error Handling**: Implemented try-catch blocks and user notifications throughout the app

### Technical Skills Demonstrated
- **Frontend**: React.js, JavaScript ES6+, JSX, Component Architecture
- **Backend**: Node.js, Express.js, RESTful API Design, Middleware
- **Database**: MongoDB, Mongoose ODM, Data Modeling
- **Styling**: Tailwind CSS, Responsive Design, Modern UI/UX
- **Tools**: Vite, npm, Git, Environment Configuration
- **Deployment**: Full-stack application deployment on Render

## 🎯 Technical Implementation

### Frontend Architecture
```
- React functional components with hooks
- Client-side routing with React Router
- Axios for HTTP requests and error handling  
- Form state management and validation
- Toast notifications for user feedback
- Responsive design with Tailwind CSS
```

### Backend Architecture
```
- Express.js server with modular routing
- MongoDB integration with Mongoose
- RESTful API endpoints for note operations
- CORS configuration for cross-origin requests
- Environment variable configuration
- Error handling middleware
```

### API Endpoints Built
| Method | Endpoint | Functionality |
|--------|----------|---------------|
| GET | `/api/notes` | Retrieve all notes |
| POST | `/api/notes` | Create new note |
| GET | `/api/notes/:id` | Get specific note |
| PUT | `/api/notes/:id` | Update existing note |
| DELETE | `/api/notes/:id` | Delete note |

## 🚀 Running Locally

### Prerequisites
- Node.js (v14+)
- MongoDB (local or Atlas)

### Backend Setup
```bash
cd backend
npm install

# Create .env file with:
MONGODB_URI=mongodb://localhost:27017/thinkboard
PORT=5001

npm run dev
```
Server runs on `http://localhost:5001`

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
Application runs on `http://localhost:5173`

## 💼 Key Development Skills Showcased

- **Problem Solving**: Debugged import/export issues, routing problems, and state management
- **Code Organization**: Structured components, separated concerns, and maintained clean code
- **Modern JavaScript**: Used ES6+ features, async/await, destructuring, and arrow functions
- **Version Control**: Git workflow with meaningful commits and project structure
- **Full-Stack Integration**: Connected frontend and backend with proper error handling
- **User Experience**: Implemented loading states, validation feedback, and intuitive navigation

## 📱 Features Walkthrough

1. **Homepage**: Displays all notes in a clean, organized layout
2. **Create Note**: Form with validation for title and content fields
3. **Note Management**: Edit and delete functionality with confirmation
4. **Responsive Design**: Works seamlessly across desktop and mobile devices
5. **Error Handling**: User-friendly messages for network errors and validation

---

*Inspired by Codesistency's MERN Stack tutorial*

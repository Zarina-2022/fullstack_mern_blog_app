# MERN BLOG APP

### Project Summary:
This project is a simple blogging platform with both backend and frontend components. It allows users to register, login, create, edit, and view blog posts. The backend is built with Node.js, Express, MongoDB using Mongoose for data modeling, and implements JWT for authentication. The frontend is built with React.js.

### Backend:
- **Technologies Used**: Node.js, Express.js, MongoDB, Mongoose, bcryptjs, JWT, multer, fs.
- **Functionality**:
  - Provides endpoints for user authentication (register, login, logout) and profile management.
  - Manages blog posts with endpoints for creating, editing, and retrieving posts.
  - Handles file uploads for post covers using multer.
  - Uses JWT for user authentication and authorization.
  - Utilizes bcryptjs for password hashing.
  - Provides static file serving for post covers.

### Frontend:
- **Technologies Used**: React.js, React Router, React Quill, Date-fns.
- **Functionality**:
  - Implements a layout with header navigation.
  - Provides pages for home, login, register, create post, view post, and edit post.
  - Uses React Quill for a rich text editor in creating and editing posts.
  - Fetches and displays blog posts from the backend.
  - Implements user authentication and authorization.
  - Allows users to create, edit, and view blog posts.

### Overall:
- **Features**:
  - User authentication (register, login, logout) with JWT.
  - CRUD operations for blog posts.
  - File upload for post covers.
  - Rich text editor for creating and editing posts.
  - Displaying posts with cover images and author information.
- **Project Structure**:
  - Backend and frontend are separated into different directories.
  - Backend consists of models, routes, and middleware.
  - Frontend consists of components, pages, and context for state management.
- **Communication**:
  - Backend and frontend communicate via HTTP requests using fetch API.
  - JSON format is used for data exchange between backend and frontend.
- **Styling**:
  - Styling is minimal and not a focal point of the project.
- **Deployment**:
  - Deployment details are not provided in the code snippets.

### Conclusion:
This project serves as a basic example of a full-stack web application with user authentication and CRUD operations for blog posts. It demonstrates the integration of popular technologies and patterns used in modern web development.

![](blog.gif)




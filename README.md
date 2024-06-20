Threads-YT
Project Description
Threads-YT is a full-stack social media application built with modern web technologies. The project consists of a front-end built with React and Vite, and a back-end powered by Node.js and Express. It leverages Chakra UI for styling, Recoil for state management, and integrates with Socket.io for real-time communication. The backend uses MongoDB for data storage, bcryptjs for password hashing, and JSON Web Tokens (JWT) for authentication. Cloudinary is used for handling media uploads.

Installation
Clone the Repository
Copy code
git clone https://github.com/your-username/threads-yt.git
cd threads-yt

Install Dependencies
npm install
cd frontend
npm install

Running the project steps
1. npm run dev
2. cd frontend
3. npm run dev

Technologies Used

a. Frontend
React: A JavaScript library for building user interfaces.
Vite: A build tool that provides a faster and leaner development experience for modern web projects.
Chakra UI: A simple, modular, and accessible component library.
Recoil: State management library for React.
Socket.io Client: Real-time communication library.

b. Backend
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
Express: A minimal and flexible Node.js web application framework.
Mongoose: MongoDB object modeling for Node.js.
bcryptjs: Library to hash passwords.
jsonwebtoken: Library to work with JSON Web Tokens (JWT).
Cloudinary: Service for managing media assets.
dotenv: Module to load environment variables from a .env file.
Socket.io: Real-time communication library.
Nodemon: Tool that helps develop Node.js based applications by automatically restarting the node application when file changes are detected.

Scripts

Frontend
dev: Starts the development server.
build: Builds the application for production.

Backend
dev: Starts the development server with Nodemon.
build: Installs dependencies for both frontend and backend, and builds the frontend.

Environmental Variables :
For this project, the configuration values such as database URIs, JWT secrets, and Cloudinary credentials are hardcoded directly in the source code. 

Learning Takeaways
Learned to implement secure user authentication and authorization using JWT.
Gained experience in managing and storing media assets with Cloudinary.
Improved skills in developing real-time applications using Socket.io.
Enhanced front-end development skills with React and Chakra UI.
Learned to manage state efficiently in React applications using Recoil.

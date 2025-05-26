add an .env file into backend, a file should contain the following:

MONGODB_URI = https://url.com
PORT = XXXX
JWT_SECRET = secretkey
CLOUDINARY_CLOUD_NAME = XXXXXX
CLOUDINARY_API_KEY = XXXXXXXX
CLOUDINARY_API_SECRET = XXXXXX


then run the following commands:

npm run build

npm run start


# NexChat - MERN Chat Application

A real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), featuring user authentication, cloud image uploads, and responsive design.

---

## 🚀 Live Demo

👉 [Click here to try NexChat](https://nexchat-mern.onrender.com)

---

## 🛠 Features

- Real-time messaging
- User authentication with JWT
- Cloudinary integration for profile pictures
- RESTful API backend
- Responsive UI with React
- Secure routes and private chats

---

## 📦 Running the App Locally

Follow the steps below to set up the application on your local machine.

### 📁 Step 1: Download the Project

1. Visit the GitHub repository.
2. Download the project as a `.zip` file.
3. Extract the contents to your desired location.

---

### ⚙️ Step 2: Create a `.env` File

Navigate to the `backend` folder and create a file named `.env` with the following contents:

```env
MONGODB_URI=https://url.com
PORT=XXXX
JWT_SECRET=secretkey
CLOUDINARY_CLOUD_NAME=XXXXXX
CLOUDINARY_API_KEY=XXXXXXXX
CLOUDINARY_API_SECRET=XXXXXX
NODE_ENV=development
```

---

### 🛠️ Step 3: Build and Start the Application

Once you’ve set up the environment and installed dependencies, follow these steps to run the app locally:

1. Open your terminal.
2. Navigate to the **root directory** containing both `frontend` and `backend` folders.
3. Run the following commands:

```bash
npm run build
npm run start
```


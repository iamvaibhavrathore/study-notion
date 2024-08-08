![studyNotion-compressed](https://github.com/user-attachments/assets/c28e37e2-cfbc-4c86-b364-4cb0c66dce1f)


---

# Study Notion

An advanced **EdTech platform** built with the MERN stack, designed to facilitate seamless online learning. Study Notion provides a robust environment for students, instructors, and administrators, featuring secure payment integration with Razorpay and media management via Cloudinary.

---

## 🔍 Project Overview

Study Notion is a full-stack application that enables users to engage in online education. The platform supports various user roles, including **Admin**, **Instructor**, and **Student**, each with distinct capabilities tailored to their needs. With integrated payment processing and media handling, Study Notion delivers a comprehensive learning experience.

---

## ✨ Key Features

- **Role-Based Access Control**:
  - **Admin**: User and course management, payment monitoring, and overall platform supervision.
  - **Instructor**: Course creation and management, student progress tracking, and content uploading.
  - **Student**: Course enrollment, content consumption, and progress tracking.

- **Course Management**:
  - Instructors can create, update, and organize courses.
  - Supports video, image, and document uploads via Cloudinary.

- **Payment Integration**:
  - Razorpay integration for secure payment processing, enabling students to purchase courses.

- **Responsive Interface**:
  - A mobile-friendly design ensures accessibility across devices.

- **Authentication & Security**:
  - Secure login and session management using JSON Web Tokens (JWT).

---

## 🛠️ Technology Stack

- **Frontend**: React.js, Redux for state management
- **Backend**: Node.js, Express.js
- **Database**: MongoDB for data storage
- **Payment Gateway**: Razorpay
- **Media Management**: Cloudinary for handling multimedia content
- **Authentication**: JWT for secure user sessions

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/study-notion.git
   ```

2. **Backend Setup**:
   - Navigate to the `server` directory:
     ```bash
     cd study-notion/server
     ```
   - Install dependencies:
     ```bash
     npm install
     ```

3. **Frontend Setup**:
   - Navigate to the `client` directory:
     ```bash
     cd ../client
     ```
   - Install dependencies:
     ```bash
     npm install
     ```

4. **Environment Variables**:
   - Create a `.env` file in the `server` directory and add the following:
     ```plaintext
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     RAZORPAY_KEY_ID=your_razorpay_key_id
     RAZORPAY_KEY_SECRET=your_razorpay_key_secret
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     ```

### Running the Application

1. **Start the Backend Server**:
   ```bash
   cd server
   npm start
   ```

2. **Start the Frontend**:
   ```bash
   cd ../client
   npm start
   ```

   The app should now be running on `http://localhost:3000/` with the backend at `http://localhost:5000/`.

---

## 🎓 Usage

- **Admins**: Manage the platform by overseeing users and courses, handling disputes, and monitoring transactions.
- **Instructors**: Create new courses, manage existing content, and interact with students.
- **Students**: Browse and enroll in courses, access educational content, and track learning progress.

---

## 🤝 Contributing

Interested in contributing? Here’s how you can help:
1. **Fork the repository**.
2. **Create a feature branch** (`git checkout -b feature-branch`).
3. **Commit your changes** (`git commit -m 'Add feature'`).
4. **Push to the branch** (`git push origin feature-branch`).
5. **Open a pull request**.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to modify this structure to best suit your project's needs!

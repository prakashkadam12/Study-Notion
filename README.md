## StudyNotion An Ed-Tech Application


Overview

The most intricate project I've undertaken in full-stack development is called "StudyNotion," which encompasses two distinct portals—one for administrators and the other for students. Both administrators and students can register and log in initially.


## Features

- **Landing Page:** Features a button to explore available courses.
- **Course List Page:** Displays available courses with basic information.
- **Course Details Page:** Shows detailed information about a specific course.

#### Admin Portal

Administrators have comprehensive functionalities, including:

- **Course Creation:** Administrators can create courses, incorporating various multimedia elements such as videos and images directly related to the course content.
- **Payment Integration:** Administrators can integrate payment gateways, enabling seamless transactions for course purchases.
- **Course Publishing:** Once courses are curated and customized, administrators have the capability to publish them for sale to the student base.
- **Profile Management:** Administrators can manage their personal information through the settings interface, ensuring data accuracy and security.

#### Student Portal

Students have an intuitive interface to manage their profiles and educational journeys, including:

- **Profile Management:** Students can create and update their personal information through the settings option, ensuring their data is current and relevant.
- **Course Purchase:** The highlight feature of the student portal is the ability to purchase courses seamlessly. This is facilitated by an innovative feature where students can utilize a scanner to purchase courses, streamlining the entire transaction process and enhancing user experience.

### Technology Stack

This project is built with the MERN stack, consisting of:

- **MongoDB:** For the database.
- **Express.js:** For the backend framework.
- **React:** For the frontend framework.
- **Node.js:** For the server environment.

### Installation

1. **Clone the repository to your local machine:**
    ```sh
    git clone https://github.com/yourusername/studynotion.git
    ```

1. **Navigate to the project directory:**
    ```sh
    cd studynotion
    ```

1. **Install backend dependencies:**
    ```sh
    cd backend
    npm install
    ```

1. **Install frontend dependencies:**
    ```sh
    cd ../frontend
    npm install
    ```

1. **Create a `.env` file in the `backend` directory and add your environment variables:**
    ```plaintext
    MONGO_URI=your_mongo_connection_string
    JWT_SECRET=your_jwt_secret
    ```

1. **Start the backend server:**
    ```sh
    npm run dev
    ```

1. **Start the frontend server:**
    ```sh
    cd ../frontend
    npm start
    ```

1. **Open the project in your browser:**
    Open your browser and navigate to [`http://localhost:3000`](http://localhost:3000) to view your project.

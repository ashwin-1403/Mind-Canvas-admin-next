# Mind Canvas Project

## Overview
Mind Canvas is a project designed to provide a platform where users can share their thoughts with hashtags, interact with other users' posts, and manage their own posts. It offers features like user signup, login, posting thoughts with hashtags, viewing others' posts, and deleting their own posts. Additionally, the project includes role management with two roles: user and admin. Admins have the authority to delete user posts. Mind Canvas serves as a demo project aimed at facilitating learning and exploration.

## Solution Overview
Mind Canvas aims to provide a user-friendly interface for sharing thoughts and engaging with other users' content. The project incorporates various features to enhance user experience and facilitate seamless interaction. It leverages technologies like Next.js, Next Auth Provider, HTML, SCSS, React Bootstrap, serverless functions, TypeScript, and MongoDB to deliver a robust solution.

## Technical Description
### Modules Completed:
1. **User Signup and Login:**
   - Allows users to sign up for an account and securely log in to the platform.

2. **Thought Posting with Hashtags:**
   - Enables users to post their thoughts along with relevant hashtags for easy categorization and searchability.

3. **Viewing Other People's Posts:**
   - Provides users with the ability to view posts shared by other users on the platform.

4. **Post Management:**
   - Users can delete their own posts, providing control over their content.

5. **Role Management (User and Admin):**
   - Defines two roles: user and admin. Admins have the authority to delete user posts, ensuring content moderation.

### Technologies Used:
- **Next.js:** Utilized for building React applications with server-side rendering and other advanced features.
- **Next Auth Provider:** Implemented for authentication and authorization management.
- **HTML:** Used for structuring the web application's content.
- **SCSS:** Employed for styling the user interface, providing flexibility and maintainability.
- **React Bootstrap:** Utilized for building responsive and mobile-first user interfaces.
- **Serverless Functions:** Implemented for handling server-side logic without managing server infrastructure.
- **JavaScript:** Used for enhancing code quality and maintainability.
- **MongoDB:** Employed as the database management system for storing application data.

## Conclusion
Mind Canvas project serves as a demonstration of various features essential for building interactive web applications. By leveraging technologies like Next.js, Next Auth Provider, and MongoDB, the project provides a scalable and efficient solution for sharing thoughts and engaging with user-generated content. With the completion of the mentioned modules, Mind Canvas offers a solid foundation for further learning and exploration in the realm of web development.


## Prerequisites

Ensure that you have the following software installed on your machine:

- Node.js: [Download Node.js](https://nodejs.org/)
- npm (Node Package Manager): npm is included with Node.js.

## Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/ashwin-1403/Mind-Canvas-admin-next.git
    cd Mind-Canvas
    ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

3. **Configure Environment Variables:**

    If your project relies on environment variables, create a `.env` file in the project root and add the necessary variables. Make sure not to commit sensitive information like API keys to version control.
    
    ## .env is required 

- `BASE_URL`

- `JWT_SECRET`

-  `MONGO_URI`

Note:- Please connect db with mongo Atlas link:  https://cloud.mongodb.com/

4. **Run the Application:**

    ```bash
    npm run dev
    ```

    This will start the development server, and you can view your application in your browser at `http://localhost:3000` by default.



## Available Scripts

List and briefly explain any available npm scripts that can be used in the project.

- `npm run dev`: start the project for production.

- `npm run build`: Build the project for production.\

- `npm run lint`: Build the project for production.


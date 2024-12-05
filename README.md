# TypeScript E-Commerce Backend

## Project Overview

This repository contains the backend API for a simple e-commerce platform built with **TypeScript**, **Node.js**, **Express**, and **MongoDB**. This project marks the completion of a 15-day focused learning journey where I applied my knowledge of TypeScript in a real-world backend scenario.

The purpose of this project is to evaluate and validate my understanding of TypeScript by building a simple e-commerce backend with three core models: **Category**, **Brand**, and **Product**. Throughout this process, I focused on creating scalable and maintainable backend APIs while practicing key backend concepts such as **CRUD operations**, **RESTful API design**, and **database management** using MongoDB and Mongoose.

After completing two practice backend projects with TypeScript and building this final project, I am confident in my ability to implement backend systems using TypeScript. This project serves as a demonstration of my growing proficiency with TypeScript and my readiness to handle more complex backend development tasks.

## Tech Stack

- **TypeScript**
- **Node.js**
- **Express**
- **MongoDB**
- **Mongoose**
- **Joi** for data validation

## Environment Variables

To get the project up and running locally, make sure to configure the following environment variables in your `.env` file:

MONGODB_DEVELOPMENT_URI=your_url
PORT=your_port

## Project Structure

Here is an overview of the project structure:

root/
├── dist/
│ └── node_modules/
├── src/
│ ├── configs/
│ ├── controllers/
│ ├── interfaces/
│ ├── middlewares/
│ ├── models/
│ ├── repositories/
│ ├── routes/
│ ├── services/
│ ├── types/
│ ├── utils/
│ └── validations/
├── .env
├── .gitignore
├── .prettierignore
├── .prettierrc
├── nodemon.json
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
├── app.ts
├── constants.ts
└── server.ts

- **`dist/`**: The compiled JavaScript files after transpiling TypeScript.
- **`src/`**: The source code directory.
  - **`configs/`**: Configuration files for the project.
  - **`controllers/`**: Controllers handling the business logic.
  - **`interfaces/`**: TypeScript interfaces for strong typing.
  - **`middlewares/`**: Custom middlewares for API request handling.
  - **`models/`**: Mongoose models for the database.
  - **`repositories/`**: Contains the database interaction logic.
  - **`routes/`**: Express route definitions.
  - **`services/`**: Business logic for the core functionalities.
  - **`types/`**: TypeScript types for various components.
  - **`utils/`**: Utility functions used across the project.
  - **`validations/`**: Joi validation schemas for request data.
- **`.env`**: Environment configuration file.
- **`.gitignore`**: Git ignore file for unnecessary files.
- **`.prettierignore`** and **`.prettierrc`**: Configuration for Prettier.
- **`nodemon.json`**: Configuration for Nodemon for auto-restarting the app during development.
- **`package.json`** and **`package-lock.json`**: Project metadata and dependency management.
- **`tsconfig.json`**: TypeScript configuration file.
- **`app.ts`**: Main application file to set up and initialize the Express app.
- **`constants.ts`**: File for shared constants used throughout the app.
- **`server.ts`**: Entry point of the application, responsible for running the server.

## How to Run the Project

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/ts-e-commerce-backend.git
   ```

````

2. Navigate into the project directory:
   ```bash
   cd ts-e-commerce-backend
````

3. Install the required dependencies:
   ```bash
   npm install
   ```

````

4. Set up your environment variables by creating a `.env` file in the root directory and adding your MongoDB connection string and desired port:

```env
MONGODB_DEVELOPMENT_URI=your_url
PORT=your_port
````

5. Run the application in development mode with:
   ```bash
   npm run dev
   ```

---

This **README** file covers all the necessary details about the project, including the purpose, tech stack, setup instructions, and project structure. It should provide anyone viewing the repository a clear understanding of the project and how to get it running locally.

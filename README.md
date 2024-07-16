# Flextest E-Testing System

Flextest is an e-testing system built with Node.js using the Fastify library for the API and main server, and Python (Flask) for the candidate interface serving static pages (HTML, CSS, JavaScript, etc). The system utilizes Redis for caching to reduce database load (MySQL) and Nginx for web serving.

## Installation

1. Download and install MySQL 8.0.
2. Set up your database with the name "flextest_db".
3. Database tables and components will be provided upon request, along with the necessary credentials.
4. Running the project for the first time will automatically create a .env file with the required database connection information.

## Running the Project

1. Clone the repository.
2. Run `npm install` at the root folder.
3. Navigate to the candidate directory (`cd candidate`) and run `pip install -r requirements.txt` to install dependencies.
4. Return to the root folder and run `npm start` to start the server.

## Important Notes

- Ensure equal resources are allocated to MySQL and the e-testing server.
- The admin dashboard is located in a separate Git repository.
- Do not close any services (including Redis and the main server) until you have finished conducting exams.

For any additional information or assistance, feel free to reach out.

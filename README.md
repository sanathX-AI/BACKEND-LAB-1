# Lab 01: Node.js and Express Server

## Student Details

- **Name:** K. SANATH KUMAR
- **Registration Number:** 252U1R5070
- **Section:** CSE(AIDE)-2A - 106

**Live Deployment Link:** https://backend-lab-1-4dvd.onrender.com
## Objective

To set up a Node.js project and develop a basic HTTP server using the built-in HTTP module, followed by an Express.js server with multiple routes, request handling, and appropriate HTTP status codes.

## Technologies Used

- Node.js
- Express.js
- JavaScript
- HTTP Module
- npm (Node Package Manager)
- Visual Studio Code

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/sanathX-AI/BACKEND-LAB-1.git
   ```

2. Navigate to the Lab 01 folder:

   ```bash
   cd BACKEND-LAB-1/lab-01
   ```

3. Initialize the Node.js project (if not already initialized):

   ```bash
   npm init -y
   ```

4. Install Express:

   ```bash
   npm install express
   ```

5. Start the project using the commands below.

## How to Run

### Node.js HTTP Server

Run the following command:

```bash
node plain-server.js
```

Open your browser and visit:

`http://localhost:3000`

### Express.js Server

Run the following command:

```bash
npm start
```

Or:

```bash
node app.js
```

Open your browser and test the endpoints.

**Environment Variables:** No environment variables are required for this lab.

## API Endpoints

| Method | Endpoint | Description | Status Code |
|---|---|---|---|
| GET | `/` | Displays a welcome message. | 200 |
| GET | `/about` | Returns student name and section in JSON format. | 200 |
| GET | `/time` | Returns the current date and time using `new Date()`. | 200 |
| GET | `/invalid` | Demonstrates a Page Not Found response. | 404 |
| GET | Any unknown path | Returns a custom 404 error message. | 404 |

## Plain Node.js Server

The plain HTTP server is created using Node.js built-in `http` module and `http.createServer()`.

It listens on port 3000 and responds with a simple "Hello" message.

## Screenshots

### 1. Node.js HTTP Server

<img width="1848" height="1020" alt="home" src="https://github.com/user-attachments/assets/9d5b9ddd-e75d-4ae2-ba7b-50df0349cd4e" />

### 2. Home Page

<img width="906" height="769" alt="image" src="https://github.com/user-attachments/assets/83d84621-c9d9-4634-98e9-64a6761775d2" />


### 3. About Page

<img width="845" height="568" alt="image" src="https://github.com/user-attachments/assets/73ec6bb4-bdf6-4a82-97ee-5eb80bfdde06" />


### 4. Time Page

<img width="1847" height="1013" alt="time" src="https://github.com/user-attachments/assets/48aeca07-e39c-4398-b33d-06a322b655a5" />

### 5. 404 Not Found Page

<img width="1847" height="1017" alt="404" src="https://github.com/user-attachments/assets/a7fbae40-3fe3-436e-a623-e08c95fbab2d" />


## Project Structure

```text
lab-01/
│
├── app.js
├── plain-server.js
├── package.json
├── package-lock.json
├── .gitignore
├── README.md
│
└── screenshots/
    ├── node-server.png
    ├── home.png
    ├── about.png
    ├── time.png
    └── not-found.png
```

## Concepts Learned

- Introduction to Node.js and backend development.
- Initializing a Node.js project using npm.
- Understanding `package.json` and `node_modules`.
- Creating an HTTP server using the built-in HTTP module.
- Installing and using Express.js.
- Understanding HTTP requests and responses.
- Implementing GET routes in Express.js.
- Handling HTTP status codes.
- Implementing custom 404 error handling.


## Notes

- The `package.json` file contains project information, scripts, and dependencies.
- The `node_modules` folder contains installed packages.
- The built-in `http` module is used to create the plain Node.js server.
- Express.js simplifies server creation and route handling.
- Appropriate HTTP status codes are returned for successful and unsuccessful requests.
- The `node_modules` folder and `.env` file should not be committed to GitHub.
- Screenshots are stored in the `screenshots/` directory.

## Problems Faced and Solutions

- **Problem:** Understanding the difference between a plain Node.js server and an Express server.

  **Solution:** Practised creating both servers separately and compared their implementation.

- **Problem:** Handling invalid routes.

  **Solution:** Implemented a custom 404 response for unknown paths.

- **Problem:** Testing different API endpoints.

  **Solution:** Opened each endpoint in the browser and verified its response and HTTP status code.

---

**Lab 01 Completed Successfully.**

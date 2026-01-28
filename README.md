# QuickGPT

QuickGPT is a ChatGPT clone built using the MERN stack (MongoDB, Express, React, Node.js).

## Project Structure

- **client/**: Frontend application (React + Vite + Tailwind CSS)
- **server/**: Backend API (Node.js + Express + MongoDB)

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB installed (or use a cloud instance like MongoDB Atlas)

### Installation & Running

#### Server (Backend)

1.  Navigate to the `server` directory:
    ```bash
    cd server
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Create a `.env` file based on the example or add your `MONGO_URI` and `PORT`.
4.  Start the server:
    ```bash
    npm run dev
    ```

#### Client (Frontend)

1.  Navigate to the `client` directory:
    ```bash
    cd client
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

## Features (Planned)

- AI Chat Interface
- User Authentication
- Chat History
- Real-time responses

## License

MIT

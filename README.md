# Y23-MERN-Render Backend

A Node.js and Express backend server for the MERN stack application.

## Features

- Express.js server
- CORS enabled for cross-origin requests
- Environment variable support with dotenv
- RESTful API endpoints

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Rushikannan2/Y23-MERN-Render-Backend.git
cd Y23-MERN-Render-Backend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
PORT=8080
```

4. Start the server:
```bash
npm start
```

The server will start on `http://localhost:8080`

## API Endpoints

- `GET /api/hello` - Returns a welcome message

## Technologies Used

- Node.js
- Express.js
- CORS
- dotenv

## Scripts

- `npm start` - Start the server
- `npm test` - Run tests (if configured)

# Library Management App

A modern web application for managing library rooms and chairs with QR code-based occupancy tracking. This app allows administrators to create and manage rooms with chairs, while users can scan QR codes to occupy chairs and provide feedback.

## Features

- **Admin Features**:
  - Create and manage rooms
  - Configure number of chairs per room
  - View chair occupancy status
  - Monitor room utilization

- **User Features**:
  - User authentication
  - QR code scanning for chair occupation
  - Submit chair reviews and feedback
  - View chair availability

## Tech Stack

- Next.js 15
- React
- Tailwind CSS
- MongoDB
- Shadcn

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/library-management-app.git
cd library-management-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env` file in the root directory with the following variables:
```env
MONGODB_URI="your_mongodb_uri"
JWT_SECRET="your_jwt_secret_key"
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

- `/app` - Next.js app router pages and components
- `/components` - Reusable React components
- `/models` - Database schema
- `/public` - Static assets
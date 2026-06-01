# AirdropSepuh - Feed Platform

A modern web application for sharing and discovering airdrop opportunities, inspired by zthfeed.com.

## Project Structure

```
airdropsepuh/
├── frontend/          # React.js web application
├── backend/           # Node.js/Express API server
├── database/          # Database migrations and schemas
└── docs/              # Documentation
```

## Features

- **User Authentication**: Sign up, login, and manage accounts
- **Feed**: Real-time feed of airdrop opportunities
- **Create Posts**: Share new airdrop opportunities
- **Search & Filter**: Find specific airdrops by category, status, or keywords
- **Responsive Design**: Mobile and desktop optimized
- **Real-time Updates**: WebSocket support for live updates

## Tech Stack

### Frontend
- React 18.x
- TypeScript
- Tailwind CSS
- React Router
- Axios for API calls

### Backend
- Node.js
- Express.js
- MongoDB / PostgreSQL
- JWT Authentication
- WebSocket (Socket.io)

## Quick Start

### Development

```bash
# Install dependencies
npm install

# Frontend
cd frontend && npm install && npm start

# Backend (in another terminal)
cd backend && npm install && npm start
```

### Environment Setup

Create `.env` files in both frontend and backend directories with required variables.

## Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## License

MIT

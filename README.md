# leela1

Backend API for leela1

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/HimaShankarReddyEguturi/Designecommerceproductui.git))

## Project Structure

```
leela1/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- user authentication
- data storage
- data retrieval
- data creation
- data editing
- data deletion

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Log in to the application
- `GET /api/data` - Get a list of all user data
- `POST /api/data` - Create new data
- `PUT /api/data/{id}` - Update existing data
- `DELETE /api/data/{id}` - Delete data

## License

MIT

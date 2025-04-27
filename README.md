# E-Commerce React Application

A modern e-commerce web application built with React, Redux Toolkit, and JSON Server. This project demonstrates a full-featured online shopping experience with product categories, product listings, and shopping cart functionality.

## Features

- Browse product categories
- View products by category
- Add products to cart
- User authentication (login/register)
- Responsive design for all devices

## Tech Stack

### Frontend
- React 19
- Redux Toolkit for state management
- React Router for navigation
- React Bootstrap for UI components
- TypeScript for type safety
- Vite for fast development and building

### Backend
- JSON Server for a mock REST API

## Project Structure

```
├── ecommerce-frontend/      # React frontend application
│   ├── src/
│   │   ├── assets/          # Static assets
│   │   ├── components/      # Reusable components
│   │   ├── hooks/           # Custom React hooks
│   │   ├── layouts/         # Layout components
│   │   ├── pages/           # Page components
│   │   ├── redux/           # Redux state management
│   │   ├── routes/          # Application routing
│   │   ├── services/        # API services
│   │   ├── styles/          # Global styles
│   │   └── utils/           # Utility functions
│   ├── index.html           # HTML template
│   └── package.json         # Frontend dependencies
└── ecommerce-backend/       # JSON Server backend
    ├── db.json              # Database file
    └── package.json         # Backend dependencies
```

## Getting Started

### Prerequisites
- Node.js (v16 or newer)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/e-commerce-app.git
cd e-commerce-app
```

2. Install backend dependencies
```bash
cd ecommerce-backend
npm install
```

3. Install frontend dependencies
```bash
cd ../ecommerce-frontend
npm install
```

### Running the Application

1. Start the backend server
```bash
cd ecommerce-backend
npx json-server --watch db.json --port 3001
```

2. Start the frontend development server
```bash
cd ecommerce-frontend
npm run dev
```

3. Open your browser and navigate to `http://localhost:5173`

## Building for Production

```bash
cd ecommerce-frontend
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## Future Enhancements

- Implement user authentication with JWT
- Add product search functionality
- Create product detail pages
- Add product reviews and ratings
- Implement checkout process
- Add payment gateway integration

## License

MIT

## Author

Ibrahim El Othmani

---

Feel free to contribute to this project by creating issues or submitting pull requests! 
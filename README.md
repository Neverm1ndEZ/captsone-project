# PennyTrack - An Intuitive Expense Tracker Application

Welcome to PennyTrack, an expense tracking application developed by Group CIT-G11 as our Final Year Capstone Project. This application is designed to simplify and enhance personal finance management through an intuitive and feature-rich platform.

## Technology Stack

PennyTrack is built using the following technologies:

- **Frontend:** React with Next.js (MERN Stack)
- **Backend:** Node.js with Express
- **Additional Services:** Nodemailer for email notifications, various charting libraries for data visualization

## Frontend

The frontend of PennyTrack is developed using Next.js, React, and TailwindCSS. Below is the `package.json` file for the frontend:

```json
{
	"name": "expense-tracker-mern",
	"version": "0.1.0",
	"private": true,
	"scripts": {
		"dev": "next dev",
		"build": "next build",
		"start": "next start",
		"lint": "next lint"
	},
	"dependencies": {
		"@heroicons/react": "^2.1.1",
		"@material-tailwind/react": "^2.1.9",
		"axios": "^1.6.7",
		"chart.js": "^4.4.2",
		"dotenv": "^16.4.5",
		"next": "14.1.3",
		"react": "^18",
		"react-dom": "^18",
		"recharts": "^2.12.2"
	},
	"devDependencies": {
		"autoprefixer": "^10.0.1",
		"eslint": "^8",
		"eslint-config-next": "14.1.3",
		"postcss": "^8",
		"tailwindcss": "^3.3.0"
	}
}
```

## Backend

The backend of PennyTrack is built with Express and connects to MongoDB using Mongoose. It also includes features for user authentication and email notifications. Below is the `package.json` file for the backend:

```json
{
  "name": "penny-track-backend",
  "version": "1.0.0",
  "description": "Backend and API for Penny Tracker",
  "main": "src/index.js",
  "type": "module",
  "scripts": {
    "dev": "nodemon -r dotenv/config --experimental-json-modules src/index.js",
    "start": "node -r dotenv/config --experimental-json-modules src/index.js"
  },
  "author": "Divy Koushik Mishra & Mihir Suman",
  "license": "ISC",
  "dependencies": {
    "bcrypt": "^5.1.1",
    "cookie-parser": "^1.4.6",
    "cors": "^2.8.5",
    "dotenv": "^16.4.5",
    "express": "^4.18.3",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.2.1",
    "nodemailer": "^6.9.12"
  },
  "devDependencies": {
    "nodemon": "^3.1.0",
    "prettier": "^3.2.5"
  }
}
```

## Features

- **Expense Tracking:** Easily record and categorize your expenses.
- **Budget Management:** Set and monitor your budget goals.
- **Data Visualization:** Analyze your spending habits with interactive charts and graphs.
- **Financial Insights:** Gain actionable insights into your financial health.
- **Security:** Robust security measures to protect your financial data.

## Getting Started

To get started with PennyTrack:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/pennytrack.git
   cd pennytrack
   ```

2. **Set up the frontend:**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

3. **Set up the backend:**
   ```bash
   cd ../backend
   npm install
   npm run dev
   ```

4. **Configure environment variables:**
   - Create a `.env` file in both `frontend` and `backend` directories with the necessary configuration.

5. **Visit the application:**
   - Open `http://localhost:3000` in your browser to start using PennyTrack.

## Contributing

Contributions are welcome! Please follow the standard pull request process and follow our coding guidelines.

## License

PennyTrack is licensed under the [MIT License](LICENSE).

For more information or support, please contact the project team at [mihirsuman1@gmail.com].

# Expense Tracker

## Overview
Expense Tracker is a simple web application built using React and Vite that allows users to track their expenses. The app integrates AWS Amplify for authentication and data management, enabling users to securely manage their expenses.

## Features
- User authentication using AWS Amplify
- Add, view, and delete expenses
- Real-time updates for expense tracking
- Responsive design for mobile and desktop
- Built with modern frontend technologies (React, Vite, AWS Amplify)

## Tech Stack
- **Frontend:** React, Vite
- **Backend & Authentication:** AWS Amplify
- **Styling:** AWS Amplify UI React
- **Linting:** ESLint

## Installation

### Prerequisites
Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- AWS CLI (for Amplify)

### Clone the Repository
```sh
git clone https://github.com/yourusername/hritik-6918-expensetracker.git
cd hritik-6918-expensetracker
```

### Install Dependencies
```sh
npm install
# or
yarn install
```

## Running the Application
### Development Mode
To start the development server, run:
```sh
npm run dev
```
This will start a local server and allow live reloading for development.

### Build for Production
To create a production-ready build, run:
```sh
npm run build
```
The output will be generated in the `dist/` folder.

### Preview Production Build
To preview the production build locally:
```sh
npm run preview
```

## Environment Variables
To configure AWS Amplify, you may need an `amplify_outputs.json` file in the root directory. Ensure your AWS Amplify setup is correctly configured by running:
```sh
amplify configure
amplify push
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Happy Coding! 🚀



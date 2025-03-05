FundUnity-CMS
A CMS (Content Management System) for FundUnity, built with React, TypeScript, and Vite.

Getting Started
This guide will help you get up and running with the project.

Prerequisites
Make sure you have the following installed on your system:

Node.js (v16 or later): Install Node.js
npm or yarn: npm is installed automatically with Node.js.
Installation
Clone the repository:
bash
Copy
git clone https://github.com/your-username/FundUnity-CMS.git
cd FundUnity-CMS
Install dependencies:
If you’re using npm:

bash
Copy
npm install
Or, if you prefer yarn:

bash
Copy
yarn install
Running the Development Server
To start the development server with Hot Module Replacement (HMR):

bash
Copy
npm run dev
Or with yarn:

bash
Copy
yarn dev
This will start the Vite development server at http://localhost:3000 (default). Open this URL in your browser to view the app.

Build for Production
To build the application for production:

bash
Copy
npm run build
Or with yarn:

bash
Copy
yarn build
This will create an optimized production build in the dist folder.

Run Production Build Locally
To preview the production build locally:

bash
Copy
npm run preview
Or with yarn:

bash
Copy
yarn preview
This will serve the built application on a local server (typically http://localhost:5000).

Linting and Formatting
This project comes with ESLint and Prettier setup for code quality. To lint the project:

bash
Copy
npm run lint
Or with yarn:

bash
Copy
yarn lint
You can fix some linting issues automatically by running:

bash
Copy
npm run lint -- --fix
Or with yarn:

bash
Copy
yarn lint --fix
Type Checking
To ensure that the TypeScript types are correct, you can run:

bash
Copy
npm run type-check
Or with yarn:

bash
Copy
yarn type-check
Available Scripts
Here’s a list of useful commands in this project:

npm run dev / yarn dev: Starts the development server.
npm run build / yarn build: Builds the app for production.
npm run preview / yarn preview: Serves the production build locally.
npm run lint / yarn lint: Runs ESLint to check the code for issues.
npm run type-check / yarn type-check: Type-checks the code using TypeScript.

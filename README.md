## Project Description

**WanderList** is a React-based web application designed to help users manage their packing lists for trips. The application allows users to add, delete, and toggle the packed status of items, as well as sort items by input order, description, or packed status. The project is built using modern web development technologies to ensure a smooth and efficient user experience.

### Technologies Used

- **React**: A JavaScript library for building user interfaces. It is used to create the interactive components of the application.
- **Vite**: A build tool that provides a fast development environment with Hot Module Replacement (HMR). It is used to bundle and serve the application.
- **ESLint**: A static code analysis tool used to identify and fix problems in JavaScript code. The project uses several ESLint plugins to enforce coding standards and best practices.
  - **eslint-plugin-react**: Provides linting rules for React applications.
  - **eslint-plugin-react-hooks**: Provides linting rules for React hooks.
  - **eslint-plugin-react-refresh**: Ensures that only components are exported, which is necessary for React Fast Refresh.
- **SWC**: A super-fast compiler used by the `@vitejs/plugin-react-swc` plugin to enable Fast Refresh in the development environment.
- **UUID**: A library for generating unique identifiers, used to assign unique IDs to items in the packing list.
- **Biome**: A tool for managing project configurations and dependencies.

### Project Structure

- **src/**: Contains the source code of the application.
  - **components/**: Contains React components such as `Form`, `Item`, `Logo`, `PackingList`, and `Stats`.
  - **assets/**: Contains static assets like images and styles.
  - **App.jsx**: The main application component.
  - **main.jsx**: The entry point of the application.
- **public/**: Contains public assets and the `index.html` file.
- **eslint.config.js**: Configuration file for ESLint.
- **vite.config.js**: Configuration file for Vite.
- **package.json**: Contains project metadata and dependencies.
- **README.md**: Project documentation.

### Getting Started

To run the project locally, follow these steps:

1. Install dependencies:
   ```sh
   pnpm install
   ```
2. Start the development server:
   ```sh
    pnpm run dev
   ```
3. Open the application in your browser and navigate to: `http://localhost:3000/` to view the application.

# Node.js Express Eslint Esbuild Template

This GitHub template provides a starting point for setting up a Node.js project with Express, TypeScript, Eslint, and Esbuild. It's designed to help you quickly scaffold a web server project with modern development tools and best practices.

## Features

- **Node.js and Express**: A minimal, yet powerful foundation for building web applications.
- **TypeScript**: Enjoy static typing and improved tooling for your Node.js project.
- **Eslint**: Enforce consistent code style and catch potential issues early.
- **Esbuild**: A super-fast JavaScript bundler and minifier to optimize your code.
- **Nodemon**: Automatically restart the server during development upon file changes.
- **Dotenv**: Load environment variables from a `.env` file for configuration.

## Getting Started

Follow these steps to set up your Node.js Express project using this template:

1. **Clone the Repository**: Click on the "Use this template" button on the [GitHub template page](https://github.com/gobinda168/Nodejs-Express-ESlint-Vite-template) or clone it directly using Git.

2. **Install Dependencies**: Run the following command to install project dependencies:

   ```bash
   pnpm install 
   ```
   or
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

4. **Create Environment Variables**: Create a `.env` file in the root directory of your project and configure any necessary environment variables.

5. **Development Mode**: Start the development server with auto-reload using Nodemon:

    ```bash
   pnpm run dev 
   ```
   or
   ```bash
   npm run dev
   ```
   or
   ```bash
   yarn dev
   ```

   Your server will be available at `http://localhost:3000`. You can change the port in the `.env` file.

6. **Build for Production**: When you are ready to deploy your application, build it using Esbuild:
  ```bash
   pnpm run build
   ```
   or
   ```bash
   npm run build
   ```
   or
   ```bash
   yarn build
   ```

   This will generate optimized JavaScript files in the `build` directory.

7. **Start in Production Mode**: To start your server in production mode, use:

  ```bash
   pnpm start
   ```
   or
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```

## Configuration

### Eslint Configuration

This template includes a basic Eslint configuration to ensure code quality and consistency. You can customize the Eslint rules by modifying the `.eslintrc.json` file.

### Nodemon Configuration

Nodemon is configured in the `nodemon.json` file. By default, it watches the `src` directory and restarts the server when changes are detected. You can customize the watch paths and other settings as needed.

## License

This template is open-source and available under the MIT License. Feel free to use it as a starting point for your Node.js Express projects.

---

Happy coding! If you have any questions or encounter any issues, please [create an issue](https://github.com/gobinda168/Nodejs-Express-ESlint-Es-Build-template) on the GitHub repository.

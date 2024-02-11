# Vanilla JavaScript Project Template

## Overview
This is a basic project template for building web applications using Vanilla JavaScript. It includes a simple configuration for Webpack, allowing you to bundle and serve your project efficiently. The project structure is designed to be a starting point for developing JavaScript applications without any framework.

## Project Structure

- src/: Contains your source code files.
    - index.js: Main entry point for your application.
    - index.html: HTML template for your application.
    - assets/: Directory for storing static assets like images, styles, and other resources.
- dist/: Output directory where the bundled and processed files are generated.

## Getting Started

1. Clone the repository and navigate to the project directory.
    ```bash
    git clone
    cd vanilla-js-project-template
    ```

2. Install the project dependencies using npm:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```
    This will start a development server and open the application in your default web browser.

4. Build the project for production:
    ```bash
    npm run build
    ```
    This will generate the production build of your application in the `dist/` directory.


## Available Scripts
- npm start: Start the development server.
- npm run build: Build the project for production.
- npm run watch: Watch for changes and rebuild in development mode.

## Webpack Configuration
The webpack.config.js file is configured to handle JavaScript files, styles (CSS and SCSS), images, and HTML. It uses plugins like HtmlWebpackPlugin to generate an HTML file and CopyWebpackPlugin to copy static assets from the src/assets folder to the dist/assets folder.

Feel free to modify the webpack configuration based on your project requirements.

## License

This project is open source and available under the [MIT License](LICENSE).


## Author

[Robert Ramirez]()


Feel free to use this project as a starting point for your own JavaScript applications and modify it as needed, including this README file.
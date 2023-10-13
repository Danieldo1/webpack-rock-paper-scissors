# Webpack Configuration for rock-paper-scissors



### Project Description:

The "Rock, Paper, Bundle" project is an off-platform web development project focused on configuring an existing web application to utilize Webpack as a build tool. The project involves applying Webpack to an already finished web app that currently lacks build tools. Unlike introducing new functionality, the primary focus of this project is changing how various resources are combined within the web application. It aims to configure the project for bundling using Webpack, following steps similar to those covered in the "Building Apps with Webpack" lesson provided by Codecademy.

### Key Steps in the Project:

1.  **Configuring the Node Project:**
    
    -   Initialize the Node project using `npm init -y`.
    -   Define build and start commands in the `package.json` scripts section.
    -   Install necessary npm packages (as developer dependencies) such as webpack, webpack-cli, webpack-dev-server, style-loader, and css-loader.
2.  **Configuring Webpack:**
    
    -   Create a Webpack configuration file (`webpack.config.js`) and set the mode to development.
    -   Add rules in the configuration file for handling CSS, fonts (e.g., .woff and .woff2), and images (e.g., .png).
    -   Define the entry point for the project.
3.  **Bundling the CSS:**
    
    -   Import CSS within the JavaScript code, eliminating the need for a `<link>` tag in the HTML.
4.  **Bundling the JavaScript:**
    
    -   Use Webpack to manage JavaScript modules by adding import and export statements.
    -   Replace multiple `<script>` tags in the HTML with a single `<script>` tag that embeds the JavaScript code.
    -   Export functions from specific JavaScript files and import them as needed in the main JavaScript file.
5.  **Bundling Images:**
    
    -   Import image assets (Scissors, Rock, and Paper icons) using the Webpack syntax and replace their URLs with named import values.
6.  **Building and Viewing the App:**
    
    -   Launch the project by running custom commands using `npm run build`.
    -   Verify the project by building and previewing the application `npm run start`.

In this project, Webpack is introduced to an existing codebase, enabling the bundling of fonts, images, and CSS. It offers an opportunity to understand how to configure and use Webpack in a real-world web application, simplifying the management of resources and improving the overall development workflow.

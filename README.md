# Movie Script Generator

Movie Script Generator is a web application that generates movie scripts based on user-provided concepts using OpenAI's GPT-3 model.

## Quick Start

To get started with the project, follow these steps:

1. Install the dependencies:
    ```sh
    npm install
    ```

2. Start the development server:
    ```sh
    npm start
    ```

## Project Structure

The project has the following structure:

```
Movie-Script-Generator-main/
├── env.js
├── images/
├── index.css
├── index.html
├── index.js
├── package.json
├── README.md
└── vite.config.js
```

### Files

- **env.js**: Contains the environment variables, including the OpenAI API key.
- **images/**: Directory containing image assets used in the project.
- **index.css**: Contains the CSS styles for the application.
- **index.html**: The main HTML file that structures the web page.
- **index.js**: The main JavaScript file that handles the logic for interacting with the OpenAI API and updating the DOM.
- **package.json**: Contains the project metadata and dependencies.
- **vite.config.js**: Configuration file for Vite, the build tool used in the project.

## Usage

1. Open the application in your browser.
2. Enter a movie concept in the textarea provided.
3. Click the "send" button to generate a movie script based on the provided concept.
4. The application will display a loading animation while it processes the input.
5. The generated movie script, title, and cast will be displayed on the page.

## Dependencies

- **openai**: Used to interact with the OpenAI API.
- **vite**: Build tool for the project.


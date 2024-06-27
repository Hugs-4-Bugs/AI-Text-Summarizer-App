# AI-Text-Summarizer-App


## Description
The AI Text Summarizer App is a web-based application that allows users to input a large body of text and receive a concise summary. This project leverages the Hugging Face API to perform text summarization using the BART model. The app is built with a Node.js backend and an HTML/CSS/JavaScript frontend.

## Working Flow
1. **User Input**: The user pastes text into the input text area on the web page.
2. **Verification**: The application verifies that the text length is between 200 and 100,000 characters.
3. **API Request**: The application sends the text to the backend, which in turn sends a request to the Hugging Face API.
4. **Summarization**: The Hugging Face API processes the text and returns a summarized version.
5. **Display**: The summarized text is displayed in the output text area on the web page.

## Successful Outcome
The application successfully processes the user's input text, generates a summary using the Hugging Face API, and displays the summary on the web page. The user can then read and utilize the summarized content.

## Lifecycle
1. **Initialization**: Load the environment variables and set up the server.
2. **User Interaction**: Users interact with the frontend, entering text and submitting for summarization.
3. **Backend Processing**: The backend handles the request, communicates with the Hugging Face API, and sends back the summary.
4. **Response Handling**: The frontend receives the summarized text and displays it to the user.

## Skills Used
- JavaScript (Frontend and Backend)
- HTML/CSS
- Node.js
- Express.js
- RESTful API Integration
- Asynchronous Programming
- Error Handling

## Tools and Technologies
- Node.js
- Express.js
- Hugging Face API
- Axios
- dotenv
- HTML/CSS/JavaScript
- Postman (for API testing)

## Guide to Start, Build, and Run the Project

### Prerequisites
- Node.js installed on your machine
- npm (Node Package Manager) installed
- A Hugging Face API token

### Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/Hugs-4-Bugs/AI-Text-Summarizer-App.git
    cd AI-Text-Summarizer-App
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Set up environment variables**
    - Create a `.env` file in the root directory
    - Add your Hugging Face API token to the `.env` file
    ```env
    ACCESS_TOKEN=your_hugging_face_api_token
    ```

### Running the Project

1. **Start the server**
    ```bash
    npm start
    ```

2. **Open your browser and go to**
    ```
    http://localhost:3000
    ```

### Project Structure

```
ai-text-summarizer/
├── public/
│   ├── stylesheet.css
│   ├── script.js
│   └── index.html
├── summarize.js
├── index.js
├── .env
├── package.json
└── README.md
```

### Commands

- **Install dependencies**
    ```bash
    npm install
    ```
- **Start the server**
    ```bash
    npm start
    ```

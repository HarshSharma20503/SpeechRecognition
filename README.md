# SpeechRecognition

SpeechRecognition is a Node.js project utilizing Puppeteer for automated web speech recognition. This script launches a headless browser instance, loads an HTML file containing a speech recognition interface, and continuously listens for speech input from the user.

## Prerequisites

- Node.js installed on your system.
- Basic understanding of Node.js and Puppeteer.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/HarshSharma20503/SpeechRecognition
```

2. Navigate into the project directory:

```bash
cd SpeechRecognition
```

3. Install Dependencies:

```bash
npm install
```

## Usage

1. Ensure that your microphone is properly configured and accessible.
2. Run the script:

```bash
npm start
```

3. Once the script is running, it will open a browser instance and begin listening for speech input. Speak into your microphone, and the script will log the recognized text to the console.
4. To stop the script, press Ctrl+C in the terminal to gracefully shut down Puppeteer.

## Configuration

- You can modify the headless option in the Puppeteer launch configuration to toggle between headless mode (true) and UI mode (false).
- Adjust the args array to customize browser settings and permissions as needed. 

## Contribution

Contribution to SpeechRecognition is highly appreciated. Feel free to fork the repository, make your changes, and submit a pull request.

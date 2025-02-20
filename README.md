# Quiz-Game

A dynamic and interactive web-based quiz application designed to test your knowledge across various topics.

## Features

- **Dynamic Question Loading**: Fetches questions from an external JSON file or API, allowing for easy updates and a diverse set of questions without modifying the core code.
- **Randomized Questions and Options**: Ensures each quiz session is unique by shuffling questions and their corresponding options.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices, providing a seamless experience across all platforms.
- **Timer Functionality**: Adds a sense of urgency with a countdown timer for each question.
- **Score Tracking**: Keeps track of the user's score and displays it at the end of the quiz.

## Getting Started

To set up and run the quiz application locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/bhautikpatel9/Quiz-Game.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Quiz-Game
   ```
3. **Set Up a Local Server**:
   - Since the application fetches questions from an external JSON file, it's recommended to run it on a local server. You can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) if you're using Visual Studio Code, or set up a simple server using Python:
     ```bash
     # For Python 3.x
     python -m http.server
     ```
     This will start a server at `http://localhost:8000/`.
4. **Open the Application in Your Browser**:
   - Navigate to `http://localhost:8000/` (or the appropriate URL if using a different setup) to start the quiz.

## Usage

- **Start the Quiz**: Click on the "Start" button to begin.
- **Answer Questions**: Select the option you believe is correct. The application will indicate whether your choice was correct or incorrect.
- **Navigate Through Questions**: Use the "Next" button to proceed to the following question.
- **View Results**: At the end of the quiz, your total score will be displayed, along with an option to restart the quiz.

## Project Structure

- `index.html`: The main HTML file that structures the quiz interface.
- `styles.css`: Contains the styling for the application, ensuring a visually appealing and responsive design.
- `script.js`: Houses the core JavaScript functionality, including fetching questions, handling user interactions, and managing the quiz logic.
- `questions.json`: A JSON file containing the quiz questions and answers. This file can be easily modified or expanded to include more questions.

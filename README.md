# React Quiz App

## Overview

This is a simple React-based quiz application that allows users to test their knowledge on various topics. The app fetches quiz questions from a JSON file and presents them to the user in a user-friendly interface. Users can start the quiz, answer questions, and view their results at the end.

## Features

- **Interactive Quiz**: Users can answer multiple-choice questions.
- **Dynamic Scoring**: Users receive scores based on their answers.
- **Responsive Design**: The app is designed to work on various screen sizes.
- **State Management**: Utilizes React's Context API for state management.

## Getting Started

### Prerequisites

- Node.js 
- npm 

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/srujan0404/quiz-app-assignment.git
   cd quiz-app
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the app.

## Usage

- Click on the "Start Quiz" button to begin.
- Answer the questions by clicking on the options.
- After answering all questions, view your score and the option to start over.

## File Structure

```
quiz-app/
├── public/
│   ├── index.html
│   ├── manifest.json
│   └── quiz.json
├── src/
│   ├── components/
│   │   ├── Quiz.js
│   │   ├── Result.js
│   │   └── Start.js
│   ├── context/
│   │   └── dataContext.js
│   ├── App.js
│   ├── index.js
│   └── App.css
└── package.json
```

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Bootstrap**: CSS framework for responsive design.
- **Context API**: For state management.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Create React App](https://github.com/facebook/create-react-app) for bootstrapping the project.
- [React Documentation](https://reactjs.org/docs/getting-started.html) for guidance on using React.
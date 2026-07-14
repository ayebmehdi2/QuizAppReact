# Quiz App

A simple, clean multiple-choice quiz application built with React.

## Features

- 5 multiple-choice questions
- One-click answer selection
- "Next" button navigation between questions
- Progress indicator (e.g. "2 of 5 questions")
- Responsive, minimal UI with a gradient background

## Tech Stack

- React
- JavaScript (ES6+)
- CSS

## Getting Started

### Prerequisites

- Node.js installed on your machine

### Installation

```bash
git clone https://github.com/your-username/quiz-app.git
cd quiz-app
npm install
```

### Running the App

```bash
npm start
```

The app will run locally at `http://localhost:3000`.

## Project Structure

```
quiz-app/
├── src/
│   ├── components/
│   ├── data/          # quiz questions and answers
│   ├── App.js
│   └── index.js
├── public/
└── package.json
```

## Usage

1. Read the question displayed on screen.
2. Select one of the four answer options.
3. Click **Next** to move to the following question.
4. Continue until all questions are completed.

## Roadmap

- [ ] Add a results/score screen at the end of the quiz
- [ ] Add a timer per question
- [ ] Support multiple quiz categories
- [ ] Add answer validation (correct/incorrect feedback)

## Author

Built by Mehdi as part of ongoing React/MERN practice projects.

## License

This project is open source and available under the [MIT License](LICENSE).

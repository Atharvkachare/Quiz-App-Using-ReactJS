# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- # 🎉 Quiz App 📚

Welcome to the **Quiz App**! This React-based interactive quiz application lets users test their knowledge on a series of questions. Enjoy tracking your score and aim to get them all right! 🚀

## 🌟 Features

- 🧩 **Interactive Quiz**: Navigate through a variety of questions.
- 🔒 **Answer Locking**: Locks each answer after selection to prevent changes.
- ✅ **Score Tracking**: See your score at the end of the quiz.
- ♻️ **Restart Option**: Reset the quiz to try again!

## 🛠️ Technologies Used

- **React** ⚛️: For building the user interface
- **CSS** 🎨: For styling components
- **JavaScript** 💻: For functionality and interactivity

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/quiz-app.git
   cd quiz-app
   Install Dependencies:

Install Dependencies:
npm install

Run the App:
npm start
Open your browser and go to http://localhost:3000 to start quizzing! 🎉

🧠 How to Play
Choose an Answer: Click on an option to lock in your answer.
Navigate: Use the "Previous" and "Next" buttons to move through questions.
View Score: Complete the quiz to see your final score.
Restart: Want to try again? Hit "Restart Quiz" and give it another shot!
🧩 Components and Structure
Quiz Component (Main Component)
useState hooks: Manage state for index, question, lock, score, and result.
useRef hooks: Store references to each answer option for quick styling.
Functions
checkAns: Verifies if the selected answer is correct and updates the score.
next: Advances to the next question.
previous: Goes back to the previous question.
reset: Resets the quiz to its initial state.
🎨 Styles and Assets
Styles are in Quiz.css for custom styling.
Data is imported from data.js in the assets folder.
📸 Screenshot

📂 Folder Structure
plaintext
Copy code
src
├── components
│   └── Quiz.js
├── assets
│   └── data.js
├── App.js
├── index.js
└── Quiz.css
🎉 Enjoy the Quiz!
Built with ❤️ by Your Name

vbnet


Replace `"https://github.com/yourusername/quiz-app.git"` and `"Your Name"` with your own GitHub link and name if

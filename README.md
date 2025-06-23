# React Tic-Tac-Toe Game

A modern, interactive Tic-Tac-Toe game built with React and Vite. This project demonstrates React fundamentals including state management, component composition, and event handling.

## 🎮 Features

- **Classic Tic-Tac-Toe Gameplay**: Play the traditional 3x3 grid game
- **Move History**: Track all moves made during the game
- **Time Travel**: Jump back to any previous move in the game
- **Responsive Design**: Clean, modern UI built with Tailwind CSS
- **Real-time Status**: Shows current player turn and winner announcements

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd tic-tac-toe
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## 🛠️ Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## 🏗️ Project Structure

```
tic-tac-toe/
├── src/
│   ├── App.jsx          # Main game component
│   ├── main.jsx         # Application entry point
│   ├── index.css        # Global styles
│   └── App.css          # Component-specific styles
├── public/              # Static assets
├── package.json         # Project dependencies and scripts
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── README.md           # Project documentation
```

## 🎯 How to Play

1. The game starts with player "X"
2. Click on any empty square to place your mark
3. Players alternate between "X" and "O"
4. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins
5. If all squares are filled without a winner, the game is a draw
6. Use the move history on the right to jump back to any previous state

## 🛠️ Technologies Used

- **React 19** - Frontend framework
- **Vite** - Build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **ESLint** - Code linting and quality assurance

## 📝 Learning Objectives

This project serves as a learning exercise to understand:
- React component structure and composition
- State management with React hooks (useState)
- Event handling and user interactions
- Conditional rendering
- Array manipulation and game logic
- Modern React development practices

## 🤝 Contributing

This is a learning project, but contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Improve the UI/UX
- Add additional game modes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy Gaming! 🎮**

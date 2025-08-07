
# Quiz Tac Toe 🎯

A modern twist on the classic Tic Tac Toe game that combines strategic gameplay with quiz knowledge. Challenge your friends in real-time multiplayer matches where you must answer questions correctly to earn the right to make your move!

![Quiz Tac Toe Banner](static/background.png)

## 🎮 Game Modes

### Quiz Multiplayer
Answer trivia questions to earn moves in Tic Tac Toe. Only players who answer correctly can place their X or O on the board!

### Classic Multiplayer
Traditional Tic Tac Toe gameplay with friends in real-time.

### Singleplayer
Challenge yourself against AI.

## 🚀 Features

- **Real-time Multiplayer**: Powered by Socket.IO for instant gameplay
- **Multiple Quiz Categories**: 
  - Mathematics
  - Science
  - Geography
  - History
  - Test Questions
- **User Authentication**: Secure login/registration system
- **Leaderboard**: Track wins and losses across all players
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Timer System**: 30-second countdown adds urgency to each question
- **Futuristic UI**: Stunning visual effects with neon gradients and animations
- **Real-time Notifications**: Get instant feedback on game events

## 🛠️ Technology Stack

- **Backend**: Python Flask with Socket.IO
- **Database**: SQLite for user management and leaderboards
- **Frontend**: HTML5, CSS3, JavaScript
- **Real-time Communication**: Socket.IO for multiplayer functionality
- **Styling**: Custom CSS with gradients, animations, and responsive design

## 📋 Prerequisites

- Python 3.7+
- Flask
- Flask-SocketIO
- Werkzeug

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd quiz-tac-toe
```

2. Install dependencies:
```bash
pip install flask flask-socketio werkzeug
```

3. Run the application:
```bash
python app.py
```

4. Open your browser and navigate to `http://localhost:5000`

### First Time Setup

1. Create an account using the registration form
2. Log in with your credentials
3. Choose your game mode and start playing!

## 🎯 How to Play (Quiz Mode)

1. **Create or Join Game**: Start a new game or join using a Game ID
2. **Select Category**: Choose from Math, Science, Geography, or History
3. **Wait for Players**: Game starts when both players join
4. **Answer Questions**: Type your answer and press Enter
5. **Make Your Move**: Answer correctly to earn the right to place X or O
6. **Win the Game**: First to get three in a row wins!

## 🎨 Game Features

### Timer System
- 30-second countdown for each question
- Visual progress bar
- Automatic question reset when time expires

### Real-time Notifications
- Answer feedback (correct/incorrect)
- Player join/leave notifications
- Game status updates

### Responsive Design
- Mobile-friendly interface
- Touch-optimized controls
- Adaptive layouts for all screen sizes

## 🏆 Leaderboard System

Track your progress with the integrated leaderboard:
- Win/Loss statistics
- Player rankings
- Global competition

## 📱 Mobile Support

Fully optimized for mobile devices with:
- Touch-friendly controls
- Responsive grid layout
- Optimized font sizes and spacing
- Mobile-specific CSS media queries

## 🎨 Visual Features

- **Animated Neon Text Effects**: Eye-catching title animations
- **Gradient Backgrounds**: Beautiful color transitions
- **Smooth Hover Animations**: Interactive button effects
- **Real-time Game Updates**: Instant visual feedback
- **Professional Overlays**: Polished game-over screens

## 🔧 Configuration

### Database
The application uses SQLite for user management. The database is automatically initialized on first run.

### Categories
Add new question categories by editing the `quiz_questions` array in `app.py`:

```python
{
    "question": "Your question here?",
    "answer": "correct answer",
    "category": "your_category"
}
```

## 📂 Project Structure

```
quiz-tac-toe/
├── app.py                 # Main Flask application
├── users.db              # SQLite database
├── static/               # Static assets (images)
├── templates/            # HTML templates
│   ├── index.html        # Home page
│   ├── game.html         # Quiz multiplayer game
│   ├── login.html        # Authentication
│   ├── leaderboard.html  # Leaderboard display
│   └── ...
└── README.md            # This file
```

## 🎯 Game Rules

### Quiz Multiplayer
1. Both players see the same question
2. First to answer correctly earns the move
3. Timer resets after each question
4. Players can only attempt each question once
5. Game continues until someone wins or draws

### Classic Multiplayer
1. Traditional turn-based Tic Tac Toe
2. X always goes first
3. Players alternate turns
4. First to get three in a row wins

## 🐛 Troubleshooting

### Common Issues

**Game not loading?**
- Check that both players have joined
- Refresh the page and try again

**Timer not starting?**
- Ensure both players are connected
- Wait for a new question to appear

**Can't join game?**
- Verify the Game ID is correct
- Make sure the game isn't full (2 players max)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

## 🎉 Acknowledgments

- Socket.IO for real-time multiplayer functionality
- Flask for the robust web framework
- Google Fonts for typography
- Font Awesome for icons

## 📞 Support

If you encounter any issues or have questions, please create an issue in the repository.

---

**Enjoy playing Quiz Tac Toe!** 🎮✨

# 🐍 Snake Game

A classic Snake game built with Python's Turtle graphics module. Control the snake, eat the food, and watch your score grow - but don't hit the walls!

![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🎮 Game Preview

Navigate your snake through the game arena, collecting red food pellets to grow longer and increase your score. The game ends if you collide with the walls!

## ✨ Features

- **Smooth Controls**: Responsive arrow key controls for intuitive gameplay
- **Score Tracking**: Real-time score display that updates as you collect food
- **Dynamic Growth**: Snake grows longer with each food pellet consumed
- **Collision Detection**: Wall collision detection to end the game
- **Clean UI**: Minimalist black background with white snake and red food
- **Object-Oriented Design**: Well-structured code using classes for maintainability

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- The `turtle` module (comes pre-installed with Python)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/snake-game.git
cd snake-game
```

2. Run the game:
```bash
python main.py
```

## 🎯 How to Play

1. **Start the Game**: Run `main.py` to launch the game window
2. **Control the Snake**:
   - ⬆️ **Up Arrow**: Move up
   - ⬇️ **Down Arrow**: Move down
   - ⬅️ **Left Arrow**: Move left
   - ➡️ **Right Arrow**: Move right
3. **Objective**: Eat the red food pellets to grow your snake and increase your score
4. **Avoid**: Don't hit the walls or the game is over!

## 📁 Project Structure

```
snake-game/
│
├── main.py          # Main game loop and setup
├── snake.py         # Snake class with movement logic
├── food.py          # Food class with random positioning
├── scoreboard.py    # Scoreboard class for score tracking
└── README.md        # Project documentation
```

## 🛠️ Technical Details

### Classes

- **Snake**: Manages snake segments, movement, and growth
  - Creates initial 3-segment snake
  - Handles directional controls with collision prevention
  - Extends snake length when food is consumed

- **Food**: Inherits from Turtle to create food pellets
  - Randomly positions food within game boundaries
  - Refreshes to new random location when eaten

- **Scoreboard**: Displays and updates the player's score
  - Real-time score updates
  - Game over message display

### Game Mechanics

- **Update Speed**: 0.1 seconds delay between frames
- **Game Area**: 600x600 pixels
- **Collision Radius**: 15 pixels for food detection
- **Movement**: 20 pixels per step

## 🎨 Customization

Feel free to customize the game by modifying:

- Snake color in `snake.py` (line 25)
- Food color in `food.py` (line 11)
- Game speed in `main.py` (line 27)
- Screen size in `main.py` (line 8)
- Font style in `scoreboard.py` (line 3)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Add self-collision detection (game over when snake hits itself)
- [ ] Implement high score tracking
- [ ] Add difficulty levels with increasing speed
- [ ] Create pause/resume functionality
- [ ] Add sound effects
- [ ] Implement different game modes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Created with 💚 by [Your Name]

## 🙏 Acknowledgments

- Inspired by the classic Nokia Snake game
- Built as a learning project for Python and game development

---

⭐ If you enjoyed this project, please give it a star!

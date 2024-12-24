# Galactic Shooter

Galactic Shooter is a **gesture-controlled** space shooter game where players control their spaceship using **hand movements**. Built using **Python**, **Pygame**, and **MediaPipe**, this game provides an immersive, controller-free experience.

## Features
- **Real-Time Hand Tracking**: Uses MediaPipe to detect hand gestures.
- **Interactive Gameplay**: Control the ship using hand movements.
- **Dynamic Movement**: Move in any direction left, right, up, down.
- **Power-Ups**: Collect power-ups to boost speed.
- **Score Tracking**: Keep track of your score as you play.
- **Immersive Sound**: Audio responds to in-game events.
---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.7 or above
- OpenCV (`cv2`)
- Pygame
- MediaPipe

### Steps

1. Install Dependecies:
   ```bash
   pip install pygame opencv-python mediapipe

   ##Note:
   If you encounter missing dependencies, install them using the following command:
   pip install pygame opencv-python mediapipe --break-system-packages

2. Clone the repository:
   ```bash
   git clone https://github.com/krish-gupta21/Galactic-Shooter
   cd Galactic-Shooter
   
3. Give file permisions:
   ```bash
   chmod +x galacticshooter.py

4. Run the file:
   ```bash
   python galacticshooter.py

---

## 🎮 Game Manual

### How to Play:
1. **Start the Game**:
   - Run the script using the command: `python pingpong.py`.
2. **Control the Paddles**:
   - Move your **left hand** to control the **left paddle**.
   - Move your **right hand** to control the **right paddle**.
3. **Objective**:
   - Prevent the ball from going out of bounds by hitting it with the paddles.
4. **Scoring**:
   - Earn points every time the ball hits a paddle.
5. **Game Over**:
   - The game ends if the ball goes out of bounds. Click restart button to reatart the game.

### 📝 Tip:
Play in a well-lit environment for better hand detection accuracy.


   

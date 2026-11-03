# Jutsu Hand Signs - Naruto Webcam Game

A Naruto-inspired webcam game: choose your ninja and perform hand-sign sequences tracked with MediaPipe! ✨

## Overview
Choose your ninja character and perform real hand-sign gestures to unleash powerful Jutsu! Complete the sequence and your jutsu erupts on screen - a swirling **Rasengan** or crackling **Chidori** - drawn with a pseudo-3D additive particle engine in OpenCV.

## Features
- **Hand Gesture Recognition** - Track hand signs using MediaPipe
- **Two Powerful Jutsu** - Rasengan (swirling) and Chidori (crackling)
- **Difficulty Levels** - Multiple difficulty levels to master
- **Naruto Characters** - Choose your favorite ninja
- **Pseudo-3D Particle Effects** - Visual jutsu effects drawn with OpenCV

## How to Play
1. **Select your ninja** - Choose from available Naruto characters
2. **Perform hand signs** - Follow the sequence shown on screen
3. **Complete the pattern** - Execute the gestures correctly
4. **Unleash your Jutsu** - Watch your technique erupt on screen!

## Hand Signs Supported
- Snake, Dragon, Tiger, Rabbit, Rat, Ox, Monkey, Horse, Dog, Rooster

## Installation
```bash
# Clone the submodule
git submodule update --init --recursive

# Install dependencies
pip install -r requirements.txt

# Run with Python
python main.py
```

## Docker
```bash
docker compose up --build
```
Then open http://localhost:5177. The backend listens on port 8000.

## Running Examples
```bash
# Run the game
python main.py

# Or with Docker Compose
docker compose up --build
```

## License
See LICENSE file for details.

## Acknowledgements
- [MediaPipe](https://developers.google.com/mediapipe) - Hand tracking
- [OpenCV](https://opencv.org/) - Computer vision and particle effects
- Naruto anime series - Inspiration for Jutsu techniques

## Hand Gesture Recognition Control

### Overview
Part of the CSE 3683 AI Fundamentals class, this project implements a computer vision-based hand gesture recognition system that translates various hand movements into actionable commands. The program offers two different models:

- Presentation Control: Navigate slides and annotate presentations using intuitive hand gestures
- Desktop Interaction: Control the computer cursor, scroll, zoom, click, and drag using hand motions

Important libraries: OpenCV, Mediapipe, PyAutoGUI

### Installation

1. Clone the repository:
``` bash
git clone https://github.com/aayamrajshakya/Hand_Gesture_Control.git
cd Hand_Gesture_Control
```
2. Create an environment and install dependencies:
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```
3. Usage:
```bash
python main.py --model [part1|part2]
```

Part 1 is **Presentation Mode** and Part 2 is **Desktop Control Mode**.

For **Presentation Mode**, please place your ppt slides as images in the `/presentation` folder.

### Gesture Glossary
.
.
.

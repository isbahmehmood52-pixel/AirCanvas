# AirCanvas
🎨 AirCanvas - Virtual Drawing Canvas

AirCanvas is an interactive computer vision application that allows users to draw digitally in mid-air using hand gestures or colored markers detected through a webcam. Built with Python and OpenCV, it transforms your screen into a dynamic canvas without needing a mouse, touch screen, or stylus.

✨ Features

🖐️ Gesture / Marker Tracking: Track hand movements or physical color markers in real-time.

🎨 Color Palette Selection: Easily switch between different drawing colors (Red, Green, Blue, Yellow, etc.) by hovering over top canvas buttons.

🧹 Canvas Clearing & Eraser: Quick options to erase drawing strokes or clear the entire screen instantly.

📏 Adjustable Brush Size: Dynamic stroke thickness based on proximity or gesture controls.

⚡ Real-Time Canvas Overlay: Smooth rendering of strokes overlaid directly onto your webcam feed.

🛠️ Built With

Python 3.x

OpenCV (opencv-python) - Real-time video frame capture, color masking, and contours/gesture processing.

MediaPipe (Optional/If used) - High-fidelity hand gesture and landmark detection.

NumPy - Matrix calculations and canvas array management.

🚀 Getting Started

Prerequisites

Make sure you have Python 3.8+ and a working Webcam connected to your system.

Check your Python version:

python --version


Installation

Clone the repository:

git clone https://github.com/YOUR-USERNAME/AirCanvas.git
cd AirCanvas


Install required dependencies:

pip install opencv-python numpy mediapipe


Run the program:

python main.py


(Replace main.py with your main script's file name if different).

🕹️ How to Play / Use

Launch the application to open your webcam feed.

Hold up your index finger or object/marker in front of the camera.

Move your finger/marker into top header color boxes to select a color or clear the screen.

Draw freely on the screen by moving your finger across the frame!

# Canvas Drawing with Hand Gestures

A Python-based interactive canvas drawing project using **OpenCV**, **NumPy**, and **Mediapipe**. This project allows users to draw on a virtual canvas using hand gestures tracked via a webcam.

---

## Features

- **Hand Tracking:** Uses Mediapipe to detect hand landmarks in real time.
- **Gesture-Based Drawing:** Draw on the canvas using the tip of your index finger.
- **Dynamic Canvas:** Combines the webcam feed with the virtual canvas.
- **Customizable Controls:**
  - Change drawing colors and thickness.
  - Clear the canvas with a key press.

---

## Requirements

Install the required dependencies using `pip`:

### Create virtual enviroment
```bash
python -m venv virtual
```
### Install dependencies

```bash
pip install opencv-python numpy mediapipe
```

### Run the project
```bash
python drawing.py
```

### Close the project

```bash
q
```

## Key Features and Usage
- **Start Drawing:** Use the tip of your index finger to draw on the canvas.
- **Clear the Canvas:** Press c to clear the drawing.
- **Quit the Application:** Press q to exit the program.


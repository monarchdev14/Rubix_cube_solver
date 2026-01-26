# 🧩 Rubik's Cube Solver (Java Swing + OpenCV)

A desktop-based **Rubik’s Cube color detection and solver** built in **Java** using **Swing** for GUI and **OpenCV** (via `VideoCap`) for real-time camera capture.  
This project captures cube faces through a webcam, detects colors automatically, and computes an optimal solution.

---

## 🚀 Features

- 🎥 Live webcam feed
- 🟥 Real-time color detection
- 🧠 Automatic Rubik’s Cube solution generator
- 💡 Dynamic UI updates
- ⌨️ Keyboard controls for easy use

---

## ⚙️ Controls

| Key | Action |
|-----|---------|
| **SPACE** | Capture one face of the cube |
| **R** | Reset cube data |
| **X** | Exit application |

---

## 🧱 Project Structure

src/
├── MainFrame.java # Main window & logic controller
├── DisplayWindow.java # Handles UI and button updates
├── VideoCap.java # Captures webcam frames using OpenCV
├── AnalyzeFrame.java # Processes and analyzes cube face colors
└── (additional classes for solving logic)

yaml
Copy code

---

## 🖥️ Requirements

- Java 8 or above  
- OpenCV library (for `VideoCap`)  
- Any Java IDE (IntelliJ IDEA, Eclipse, VS Code)

---

## 🔧 Setup and Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/RubiksCubeSolver.git
   cd RubiksCubeSolver
Add OpenCV library

Download OpenCV from https://opencv.org/releases/

Add the opencv-XXX.jar file to your project build path

Set the native library path (.dll or .so) in your VM options if required

Run the program

bash
Copy code
javac MainFrame.java
java MainFrame
🧠 How It Works
The webcam feed opens in a window.

Point each face of the cube toward the camera.

Press SPACE to capture a face.

After capturing all six faces, the program automatically:

Displays the solution sequence

Shows the total number of moves

📸 Preview (Optional)
Add screenshots or demo GIFs here, for example:

scss
Copy code
![Demo](docs/demo.gif)
🧑‍💻 Author
Monarch Dev
🎓 B.Tech CSE (AIML) @ SRM University
💡 Passionate about AI, Computer Vision & Problem Solving

🛠️ Future Plans
Add a 3D cube visualization

Improve color detection precision

Integrate voice or sound feedback

Optimize solver for faster results

⭐ If you like this project, don’t forget to star the repo!
Added detailed README.md with features and setup instructions

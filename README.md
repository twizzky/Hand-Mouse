### *THIS IS A VERY EARLY WIP, FEEDBACK IS VERY MUCH APPRECIATED!!*        
### AirMouse , a Virtual mouse with hand detection

Control your computer using hand gestures — no physical mouse required.

Built using **MediaPipe** and **OpenCV**, this project tracks your hand in real-time and maps specific gestures to mouse movements and clicks.

---

## Features

- Real-time hand tracking using webcam  
- Cursor movement
- Left click gesture
- Right click gesture
- Scroll gesture support
- Brightness and volume control (WIP)

---
| Gesture                  | Action                       |
| ------------------------ | ---------------------------- |
| Index Finger             | Move cursor                  |
| Fist                     | Drag & Hold (mouseDown)      |
| Index + Thumb (pinch)    | Scroll / Volume / Brightness |
| 2 Fingers Close Together | Double Click                 |
| Index + Middle (V)       | Move & Click                 |
| Index only               | Right Click                  |

---

## Tech Stack

- [MediaPipe](https://google.github.io/mediapipe/) – hand landmark detection  
- [OpenCV](https://opencv.org/) – video capture and image processing  
- Python – backend logic

---

## How to run : 
# *Install requirements.txt*

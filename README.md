# 🧩 Hand Puzzle Game

Turn any photo into an interactive jigsaw-style puzzle — and solve it using nothing but your hand, tracked live through your webcam. No mouse, no touchscreen, just your fingers in the air.

Pick a photo you love, choose a difficulty, and piece it back together with a simple pinch gesture. Powered by real-time computer vision.

## ✨ Features

- 📷 Use **any photo** you choose from your own device
- 🎚️ Three difficulty levels — Easy, Medium, Hard
- 🖐️ Fully hand-controlled — no keyboard or mouse needed to play
- 🎯 Smart snapping — pieces lock into place automatically when placed correctly
- 🔵 Live self-view in a small camera circle, so you always see your hand
- 🖼️ Faint reference outline of the original photo shown on the board to guide you


## 📦 Requirements

- Python 3.9 or newer
- A working webcam

## 🚀 Installation

```bash
git clone https://github.com/kamandNajari/Hand_Puzzle_Game.git
cd Hand_Puzzle_Game
pip install -r requirements.txt
## ▶️ How to Play
## 📥 Clone the Repository

```bash
git clone https://github.com/kamandNajari/Hand_Puzzle_Game.git

1. Run the notebook — a file picker will open, choose any photo from your device
2. Select a difficulty level from the console: Easy (3×3), Medium (4×4), or Hard (5×5)
3. The puzzle board appears in the center of the screen with a faint outline of your photo as a guide
4. Scattered tile pieces appear around the board
5. Use your hand to pick up and place each tile onto its matching spot

## 🖐️ Hand Controls

| Gesture | Action |
|---------|--------|
| 👌 Pinch (thumb + index finger together) near a piece | Grab the piece |
| Move your pinched hand | Drag the piece across the screen |
| Release the pinch | Drop the piece at its current position |
| Drop a piece near its correct board position | Piece snaps and locks into place automatically |

**Important:** you must bring your **thumb and index finger together** (pinch) to grab and move a piece — just pointing at it with your index finger alone will not work.

## ⌨️ Keyboard Controls

| Key | Action |
|-----|--------|
| `r` | Restart the puzzle with a new shuffle |
| `q` | Quit the application |

## 🛠️ Tech Stack

- [OpenCV](https://opencv.org/) — video capture and rendering
- [MediaPipe](https://developers.google.com/mediapipe) — hand landmark detection
- [NumPy](https://numpy.org/) — numerical operations for tile placement and layout

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


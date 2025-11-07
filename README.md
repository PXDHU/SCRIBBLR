# 🖌️ SCRIBBLR — Deep Learning Online Drawing Game

A web-based interactive drawing game built using **TensorFlow.js** and **Phaser**, where players sketch objects while a **Convolutional Neural Network (CNN)** predicts what they draw — inspired by [Quick, Draw!](https://quickdraw.withgoogle.com/) by Google.

## 💻 Demo
🎮 **Play the Game Here:** 
👉[https://scribblr-kappa.vercel.app/](https://scribblr-kappa.vercel.app/)

---
## 🌟 Features

🎨 **Interactive Drawing Interface** — Draw freely on the canvas and see real-time predictions  
🧠 **CNN-based Prediction Engine** — Predicts doodles using a trained deep learning model  
📚 **Training Mode** — Train the CNN on additional datasets for better accuracy  
🔍 **Sample Prediction Mode** — Test the model on predefined sample images  
📊 **Dataset Integration** — Uses a subset of the [Quick Draw Dataset](https://quickdraw.withgoogle.com/data)  
💡 **Educational & Fun** — Learn deep learning concepts through play  

---
## 🧱 Technology Stack

| Component | Technology |
|------------|-------------|
| **Frontend Framework** | HTML5, Phaser 2 |
| **AI/ML** | TensorFlow.js |
| **Dataset** | Quick Draw Dataset |
| **Game Logic** | JavaScript |
| **Visualization** | Canvas-based Drawing Board |

---

## 📋 Prerequisites

- Web browser with JavaScript support  
- [VS Code](https://code.visualstudio.com/) with **Live Server** extension (recommended)  
- Internet connection to fetch dataset and libraries  

---
## 🚀 Quick Start

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/PXDHU/SCRIBBLR.git
cd SCRIBBLR
```

### 2️⃣ Open in VS Code
```bash
code SCRIBBLR
```

### 3️⃣ Run the Application
- Open `index.html`
- Use Live Server to run locally
- Start drawing and watch the CNN predictions in real-time!

---
## 📁 Project Structure
```
SCRIBBLR/
├── index.html              # Main HTML frontend
├── main.js                 # Core game logic
├── ui.js                   # UI interactions (buttons, controls)
├── cnn.js                  # CNN model definition and training
├── painter.js              # Drawing canvas and input capture
├── assets/                 # Images, datasets, and resources
└── README.md               # Documentation
```

---
## 🧠 How It Works

1. Dataset Loading
   Predefined doodle datasets (e.g., bee, tree, clock, etc.) are loaded into the browser.
2. Model Training
   A simple Convolutional Neural Network (CNN) is trained directly in the browser using TensorFlow.js.
3. Prediction Mode
   The trained model classifies the player’s doodles and displays real-time predictions.
4. Training Mode
   Players can further train the model to improve performance on new sketches.

---
##  ⚙️ Architecture
The system is divided into 5 main components:
| Component | Description |
|------------|-------------|
| **UI (ui.js)** | Handles game interface, buttons, and visual feedback |
| **Main Logic (main.js)** | Manages game state and integrates components |
| **CNN Model (cnn.js)** | Defines, trains, and predicts using a CNN |
| **Painter (painter.js)** | Provides the interactive sketching canvas |
| **Frontend (index.html)** | Basic HTML structure connecting all scripts |

---
## 📈 Roadmap
- Add more drawing categories from Quick Draw Dataset
- Tune CNN architecture for improved accuracy
- Multiplayer game mode
- User authentication and leaderboard
- Create rooms to compete with friends
- Enhanced and responsive UI

---
## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---
## 👨‍💻 Author

**Padmavasan Balakrishnan**
- Email: padmavasan.contact@gmail.com
- GitHub: [@PXDHU](https://github.com/PXDHU)

---
⭐️ Star this repository if you find it helpful!

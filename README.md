# SCRIBBLR - A Deep Learning Online Drawing Game

SCRIBBLR is a web-based game built using JavaScript and TensorFlow.js, which challenges players to draw various objects, while a Convolutional Neural Network (CNN) predicts what the drawing represents. It serves as both an engaging game and an educational project in deep learning and computer vision.

## Features

- **Interactive Drawing Interface**: Players can draw on a canvas and get real-time predictions of their doodles.
- **CNN-based Predictions**: Utilizes a CNN model for recognizing doodles and classifying them into one of several categories.
- **Training Mode**: Players can further train the model using additional datasets.
- **Sample Prediction Mode**: Displays how the model performs on a set of predefined sample images.

## How It Works

1. **Dataset Loading**: The application uses a set of predefined datasets (`bee`, `octopus`, `tree`, `candle`, `clock`, `guitar`, `umbrella`).
2. **CNN Training**: A simple CNN model is trained using the datasets, with options for additional training.
3. **Prediction**: Once trained, the CNN predicts the player’s doodles and provides feedback on the canvas.

### Architecture

The project consists of three main components:

- **UI** (`ui.js`): Handles the interface, including buttons for actions like training, testing, clearing the canvas, and displaying predictions.
- **Main Logic** (`main.js`): Manages the game state and interaction between the CNN, UI, and player input.
- **CNN Model** (`cnn.js`): A TensorFlow.js-based CNN model responsible for training and predicting the doodles.

### Tech Stack

- **JavaScript** with **Phaser.js** for game development
- **TensorFlow.js** for the CNN implementation
- **HTML5 Canvas** for drawing

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/scribblr.git


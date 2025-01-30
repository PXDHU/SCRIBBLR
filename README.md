# [SCRIBBLR](https://scribblr-orcin.vercel.app/) - A Deep Learning Online Drawing Game

## About the Project
SCRIBBLR is a web-based game built using JavaScript and TensorFlow.js, which challenges players to draw various objects, while a Convolutional Neural Network (CNN) predicts what the drawing represents. It serves as both an engaging game and an educational project in deep learning and computer vision.
Similar to [Quick, Draw](https://quickdraw.withgoogle.com/) by Google.
>[!NOTE]
> This is a demonstration project and is intended to showcase the methods that can be used to embed machine learning models directly inside website with the use of javascript
<p align="right">(<a href="#readme-top">back to top</a>)</p>

[Visit site](https://scribblr-orcin.vercel.app/)

## Features

Scribblr is made in HTML5 using [Phaser 2 framework](https://phaser.io/) and [TensorFlow.js library](https://js.tensorflow.org/). 
- **Interactive Drawing Interface**: Players can draw on a canvas and get real-time predictions of their doodles.
- **CNN-based Predictions**: Utilizes a CNN model for recognizing doodles and classifying them into one of several categories.
- **Training Mode**: Players can further train the model using additional datasets.
- **Sample Prediction Mode**: Displays how the model performs on a set of predefined sample images.
- **Dataset**: The model was trained on a small subset of the [Quick Draw Dataset](https://quickdraw.withgoogle.com/data).

### Built With

* [HTML5](https://html.com/)
* [Phaser 2](https://phaser.io/)
* [TensorFlow.js](https://js.tensorflow.org/)
* [Quick Draw Dataset](https://quickdraw.withgoogle.com/data)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## How It Works

1. **Dataset Loading**: The application uses a set of predefined datasets (`bee`, `octopus`, `tree`, `candle`, `clock`, `guitar`, `umbrella`).
2. **CNN Training**: A simple CNN model is trained using the datasets, with options for additional training.
3. **Prediction**: Once trained, the CNN predicts the player’s doodles and provides feedback on the canvas.

### Architecture

The project consists of three main components:

- **UI** (`ui.js`): Handles the interface, including buttons for actions like training, testing, clearing the canvas, and displaying predictions.
- **Main Logic** (`main.js`): Manages the game state and interaction between the CNN, UI, and player input.
- **CNN Model** (`cnn.js`): A TensorFlow.js-based CNN model responsible for training and predicting the doodles.
- **HTML**(`index.html`): Basic html page which serves as a frontend.
- **Painter**(`painter.js`): Interactive painter board which records the Doodles and serves as input image to the CNN model.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Roadmap

- [ ] Adding more drawing categories from the [Quick Draw Dataset](https://quickdraw.withgoogle.com/data).

- [ ] Tune Model Architecture for more accuracy.

- [ ] Multiplayer game support

- [ ] Enhance the UI

- [ ] Authentication

- [ ] Create rooms and compete with friends to see who can accurately draw an object that the model can identify first.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/PXDHU/SCRIBBLR.git
   ```
2. Open the cloned folder in VS Code
   ```sh
   code SCRIBBLR
   ```
3. Use the VS Code Live Server Extension to run the website locally on your machine.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Once the game is initialized and training is completed, The left table will show the samples from the dataset and the models prediction. 

The wrong predictions will be marked 'Red' and correct predictions will be marked 'Green'. 

You can test with more samples by clicking on 'Next Test' Button.

Initially, The model is trained for 50 epochs. If you are not satisfied with the model predictions, You can train the model more by clicking the 'Train More' Button.

You can start sketching any objects as mentioned in the status bar, and the model will predict your drawing.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contact

Your Name - Padmavasan B - padmavasan.contact@gmail.com


Project Link: [https://github.com/PXDHU/SCRIBBLR](https://github.com/PXDHU/SCRIBBLR)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

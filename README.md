# Autonomous-Vehicle-Steering-Cotrol
An end-to-end deep learning project for autonomous vehicle steering using a CNN to predict steering angles from real-time camera images. Trained on simulated driving data, the model enables smooth lane navigation in a virtual environment. Built with Python and Keras, it demonstrates AI-powered control for self-driving cars.

Autonomous Vehicle Steering Control/
├── model.py                # CNN model architecture
├── drive.py                # Main script to run the trained model in the simulator
├── app.py                  # Optional Flask app to serve the model
├── data/                   # Training data (images + steering angles)
├── model.h5                # Saved trained model
└── README.md               # Project documentation

## 🧠 Key Features
- End-to-end CNN-based steering angle prediction
- Trained using front camera images from driving simulation
- Real-time control with visual feedback in the simulator
- Inspired by NVIDIA’s self-driving research
- Built with Python, Keras, NumPy, and OpenCV

## 🏁 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/autonomous-vehicle-steering-control.git
    cd autonomous-vehicle-steering-control
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch the simulator and run the model:
    ```bash
    python drive.py
    ```

## 📦 Dependencies
- Python 3.x
- Keras / TensorFlow
- NumPy
- OpenCV
- Flask (optional for deployment)

## 📽 Demo

*A short clip or gif can be embedded here showing your vehicle steering in the simulator.*

## ✨ Credits
- Inspired by NVIDIA’s self-driving car architecture
- Simulator and dataset from Udacity Self-Driving Car Nanodegree

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).

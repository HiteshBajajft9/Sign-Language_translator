Sign Language Translator
A project focused on building a real-time Sign Language Translator using computer vision, hand landmark detection, and machine learning.
Project Overview
The goal of this project is to explore how computer vision and machine learning can be used to recognize and eventually translate American Sign Language (ASL).
The project is being developed incrementally, starting with hand landmark detection and progressing toward neural-network-based recognition and continuous gesture understanding.
Current Progress
Week 1 — Hand Landmarks + Feature Extraction
- Introduced OpenCV for image and video processing.
- Used MediaPipe for hand landmark detection.
- Detected 21 landmarks for a hand.
- Explored the x, y, z coordinates of hand landmarks.
- Implemented basic gesture detection using landmark-based rules.
Week 2 — Neural Networks + CNNs
- Introduction to artificial neurons and neural networks.
- Learned about weights and bias.
- Studied activation functions including ReLU, Sigmoid, and Tanh.
- Studied Softmax and cross-entropy loss.
- Learned gradient descent and backpropagation.
- Learned about training and validation.
- Implemented a basic fully-connected neural network using PyTorch.
- Used MediaPipe hand landmarks as input features.
- Introduced Convolutional Neural Networks (CNNs).
- Studied convolution, pooling, flattening, and dense layers.
Project Structure
Sign-Language_translator/
│
├── notebooks/
│   ├── opencv.ipynb
│   ├── week1.ipynb
│   ├── week2.ipynb
│   └── hands.jpg
│
├── src/
│
├── dataloader.py
├── requirements.txt
├── README.md
└── .gitignore

Technologies
- Python
- OpenCV
- MediaPipe
- NumPy
- Matplotlib
- PyTorch
- Torchvision
- Jupyter
Setup
Clone the repository:
git clone https://github.com/HiteshBajajft9/Sign-Language_translator.git
cd Sign-Language_translator

Create and activate a virtual environment:
python3 -m venv venv
source venv/bin/activate

Install the required dependencies:
pip install -r requirements.txt

MediaPipe Model
The MediaPipe hand landmarker model is not included in the repository.
Download hand_landmarker.task separately and place it in the project directory before running the relevant notebooks.
Learning Roadmap
Hand Detection
      ↓
Hand Landmarks
      ↓
Feature Representation
      ↓
Neural Network Classification
      ↓
CNNs
      ↓
Temporal / Continuous Gesture Recognition
      ↓
Sign Language Translation

Future Work
- Improve feature representation of hand landmarks.
- Train models on a larger sign-language dataset.
- Extend recognition beyond isolated/static gestures.
- Incorporate temporal information from sequences of frames.
- Explore RNNs/LSTMs for continuous gesture recognition.
- Build a real-time sign-language translation pipeline.
Author
Hitesh Bajaj
Arnav Srivastava
Priyanshu Srivastava

# Hand Gesture Recognition Model

## Overview
This project implements a **deep learning-based hand gesture recognition system** using a **CNN architecture**. The model is trained on a dataset of hand gesture images to classify different gestures with high accuracy. The system is optimized for real-time inference and can be integrated into interactive applications.

## Features
- **98.5% Accuracy** on test data
- **6 Gesture Classes** recognized with high precision
- **Real-time Gesture Detection** using OpenCV
- **Optimized CNN Model** for fast inference (<100ms per frame)
- **Confusion Matrix & Metrics Analysis** for evaluation

## Dataset
- **Source:** Leap Motion Gesture Recognition Dataset
- **Size:** 10,000+ labeled images
- **Preprocessing:** Image resizing (50x50), normalization, data augmentation

## Model Architecture
- **Convolutional Neural Network (CNN)**
- Layers: Conv2D, MaxPooling, Flatten, Dense, Dropout
- Activation Functions: ReLU, Softmax

## Training & Evaluation
- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Metrics Used:** Accuracy, Precision, Recall, F1-Score
- **Final Model Performance:**
  - **Accuracy:** 98.5%
  - **F1-Score:** ~98%
  - **Inference Time:** <100ms/frame

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ru2k/HandTrackNet.git
   cd HandTrackNet
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python main.py
   ```

## Usage
- Run the script and use a webcam for real-time hand gesture recognition.
- Modify the dataset path and retrain if needed.

## Results
- The model achieves **high accuracy and minimal loss**.
- The **confusion matrix** shows strong classification performance with minimal misclassification.
- Works **in real-time** with low latency.

## Future Enhancements
- Expand to recognize more gestures
- Improve robustness against varying lighting conditions
- Deploy as a web or mobile application

## Contributors
- **[Your Name]** – Model Development & Optimization

## License
This project is licensed under the MIT License.

---
🚀 **Transforming Hand Gestures into Seamless AI Interactions!**

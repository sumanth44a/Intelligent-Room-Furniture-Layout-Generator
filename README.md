# Intelligent Room Furniture Layout Generator

Welcome to the **Intelligent Room Furniture Layout Generator**—an innovative AI-driven solution designed to automate and optimize furniture placement within room spaces! This project leverages deep learning techniques to predict optimal furniture layouts, ensuring efficient space utilization and a visually appealing arrangement.

## 🚀 Overview
This project utilizes advanced machine learning techniques to automatically generate optimal furniture layouts for rooms, ensuring efficient space utilization and non-overlapping placement of furniture items.

## 📌 Features
- **Synthetic Dataset Generation**: Automatically creates randomized room dimensions and furniture sizes to train the model.
- **Deep Learning Model**: Utilizes a neural network built with TensorFlow and Keras to predict optimal furniture positions.
- **Overlap Detection & Adjustment**: Implements smart algorithms to ensure furniture placements are practical, non-overlapping, and within room boundaries.
- **Visualization Tool**: Provides clear visual representations of predicted room layouts using Matplotlib.
- **Interactive Testing**: Easily visualize predicted layouts through intuitive visualizations.

## 🚀 How It Works
1. **Generate Data**: Create synthetic training data with randomized room and furniture dimensions.
2. **Train Model**: Train a neural network model to learn optimal furniture positioning.
3. **Predict & Adjust**: Predict furniture placements for new room configurations and automatically adjust positions to avoid overlaps.
4. **Visualize Layouts**: View predicted layouts visually with clear graphical representations.

## 🛠️ Tech Stack
- Python
- NumPy
- TensorFlow & Keras
- Matplotlib for visualization

## 🛠️ Installation & Usage
**Clone the repository and install dependencies:**
- git clone https://github.com/sumanth44a/Intelligent-Room-Furniture-Layout-Generator.git
- cd Intelligent-Room-Furniture-Layout-Generator
- pip install numpy tensorflow matplotlib gradio pillow


## ▶️ Quickstart Example
Run the provided notebook (`Assignment_1.ipynb`) to:
- Train the neural network model on generated data.
- Visualize predicted furniture layouts interactively.

## 🧩 Model Architecture Summary

| Layer (type)         | Output Shape | Parameters |
|----------------------|--------------|------------|
| Dense (ReLU)         | (None, 32)   | 288        |
| Dense (ReLU)         | (None, 64)   | 2,112      |
| Dense (ReLU)         | (None, 32)   | 2,080      |
| Dense (Linear Output)| (None, 6)    | 198        |

Total Parameters: **4,678**

## 📊 Visualization
The notebook includes visualization tools that clearly illustrate the predicted layout within room boundaries.
The below are the sample test cases:
![image](https://github.com/user-attachments/assets/70dab06b-213a-41ab-b74a-4d8ba26b6431)
![image](https://github.com/user-attachments/assets/26be2665-517c-40fe-9748-3098d4252fa5)
![image](https://github.com/user-attachments/assets/a9497f7d-a46e-44ec-9276-0b22dfacd3eb)


Happy optimizing your space!


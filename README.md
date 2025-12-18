Crop-Disease-Detection-via-Image-Processing
📌 Project Overview

Crop disease is a major threat to agricultural productivity. This project uses image processing and simple machine learning techniques to detect diseases in crop leaves. By analyzing leaf color, texture, and shape, the system classifies images into “healthy” or “diseased,” enabling early detection and better farm management.

🚀 Features

Preprocessing of leaf images (resizing, normalization, noise removal)

Extraction of essential features (color histograms, texture patterns)

Synthetic data support for training/testing

Machine learning model for disease classification

Simple, fast, and resource-friendly implementation

🧰 Tech Stack

Python

OpenCV

NumPy

scikit-learn / TensorFlow (optional)

Matplotlib

📂 Project Structure
├── data/
│   ├── synthetic_images/
├── src/
│   ├── preprocess.py
│   ├── model.py
│   ├── predict.py
├── notebooks/
│   ├── exploration.ipynb
├── README.md
└── requirements.txt

🧪 How It Works

Load and preprocess leaf images

Extract key visual features

Train a classification model using synthetic or real data

Predict disease presence from new images

▶️ Getting Started
1. Install Requirements
pip install -r requirements.txt

2. Run Training
python src/model.py

3. Make Predictions
python src/predict.py --image sample_leaf.jpg

📊 Example Applications

Early disease detection for farmers

Mobile app for field diagnosis

Smart agriculture research

Automated crop health monitoring systems

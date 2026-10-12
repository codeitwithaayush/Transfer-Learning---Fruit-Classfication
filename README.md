# Fruit Classification Using Transfer Learning

A deep learning project that classifies fruit images using Transfer Learning with a pre-trained VGG16 (Visual Geometry Group 16) model. The project uses TensorFlow and Keras to train a classification model, fine-tune selected layers, and visualize training performance and predictions.

## Features
- Transfer learning using pre-trained VGG16 with ImageNet weights
- Image preprocessing and data augmentation
- Model training with validation
- Fine-tuning of the last five layers
- Training and validation accuracy and loss visualization
- Actual vs. predicted fruit class visualization

## Tech Stack
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- SciPy
- Scikit-learn

## Dataset
Uses the Fruits-360 Original Size dataset, downloaded automatically by the notebook.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/codeitwithaayush/fruit-classification-transfer-learning.git
   ```
2. Open the `transferlearning.ipynb` notebook in Jupyter Notebook or Google Colab.
3. Install the required dependencies as specified in the notebook.
4. Run the notebook cells sequentially to download the dataset, train the model, and visualize predictions.

## Model Architecture
The model uses VGG16 as a pre-trained feature extractor, followed by Global Average Pooling, a fully connected Dense layer, Batch Normalization, Dropout, and a Softmax output layer. The final layers of VGG16 are subsequently fine-tuned to improve classification performance.

## Results
The notebook includes visualizations of training and validation accuracy and loss, along with sample comparisons between actual and predicted fruit classes.

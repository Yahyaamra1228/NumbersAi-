Overview

This repository contains Python code for training a Multi-layer Perceptron (MLP) classifier on the MNIST digits dataset using scikit-learn. The trained model can predict the digit labels based on pixel values.

Prerequisites
Make sure to have scikit-learn installed. If not, you can install it using the following command:

bash:
pip install -U scikit-learn
Dataset
The code uses the popular MNIST digits dataset, which is included in the scikit-learn datasets module. The dataset consists of 8x8 pixel images of handwritten digits (0 through 9).

Code Structure
Loading Data: The MNIST dataset is loaded using scikit-learn's datasets module.
Data Preprocessing: Pixel values are scaled to the range [0, 1] using Min-Max scaling.
Model Training: An MLP classifier with hidden layers (100, 50) is created and trained on the scaled data.
Model Evaluation: The accuracy, classification report, and confusion matrix are printed to evaluate the model's performance.
Visualization: The README includes visualizations of some predictions on the test set.
Running the Code
Clone the repository:

bash:
git clone https://github.com/your-username/your-repository.git
cd your-repository
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook or Python script to train and evaluate the MLP classifier.

Results
The trained model achieves an accuracy of [insert accuracy here] on the test set. The classification report and confusion matrix provide additional insights into the model's performance.

Visualizations
The README includes visualizations of some predictions on the test set, allowing you to see the actual and predicted digit labels.

Feel free to explore the code, experiment with different configurations, and contribute to the project!



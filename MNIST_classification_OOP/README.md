# MNIST classification + OOP

This project contains a Jupyter Notebook for classifying MNIST digit images using the following models:
1) Random Forest;
2) Feed-Forward Neural Network;
3) Convolutional Neural Network.

## Installation

Install required libraries (if not already installed):
```bash
pip install numpy tensorflow keras matplotlib scikit-learn
```

## Project Structure

`MNIST_classification.ipynb` – main code for training and evaluating the model.

## Usage

Run **MNIST_classification.ipynb**.

## Results

All models performed excellently. Here is their ranking based on accuracy:  

1. **Convolutional Neural Network** – 99%  
2. **Feed-Forward Neural Network** – 98%  
3. **Random Forest** – 97%  

In terms of model size (from smallest to largest), the ranking is:  

1. **Feed-Forward Neural Network** – 5.39 MB  
2. **Convolutional Neural Network** – 10.40 MB  
3. **Random Forest** – 137.51 MB  

Thus, **Random Forest** is not the best choice, as it is less accurate and significantly larger than the other models. The **Convolutional Neural Network** is a much better option compared to Random Forest. However, if model size is a critical factor, the **Feed-Forward Neural Network** is also a good alternative.

## Author

Liana Lotarets


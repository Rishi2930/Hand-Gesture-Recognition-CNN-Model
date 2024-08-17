# Hand-Gesture-Recognition-CNN-Model

This repository provides a Python implementation for classifying American Sign Language (ASL) letters using the Sign Language MNIST dataset. The dataset consists of 28x28 grayscale images of hand gestures representing 24 letters of the ASL alphabet (excluding J and Z due to their dynamic gestures). The goal of this project is to develop a Convolutional Neural Network (CNN) model that can accurately classify these hand gestures, aiding in the recognition of ASL letters. The repository includes code for data preprocessing, model training, and evaluation.

## Requirements

Ensure you have Python 3 and the following packages installed:
- numpy
- pandas
- matplotlib
- seaborn
- keras
- sklearn

Install dependencies using pip:

```python
pip install numpy pandas matplotlib seaborn keras scikit-learn
```

## Running the Code

1. **Prepare Data**: Place the dataset in the \`../input/sign-language-mnist/\` directory.
2. **Run the Script**: Execute the provided Python script:

```python
python sign_language_mnist.py
```

## Visualizations

The code includes:
- Accuracy and loss curves
- Confusion matrix
- Sample correctly predicted images

## License

This code is covered under MIT License

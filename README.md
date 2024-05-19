# FreschPickAi

FreschPickAi is a machine learning project that differentiates between fresh and rotten fruits using image classification. This project utilizes a convolutional neural network (CNN) model to analyze and categorize fruit images. The model was trained using a dataset sourced from Kaggle, and the project was developed at FAST - National University of Computer and Emerging Sciences.

## Project Overview

- **Model Name**: sequential_2
- **Accuracy**: 92.3%
- **Loss**: 0.1344
- **Dataset**: Sourced from Kaggle
- **Development Team**: Abdul Moiz Soomro and Shehryar Ahmed

## Model Architecture

The CNN model architecture used in this project is as follows:

```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_4 (Conv2D)            (None, 18, 18, 32)        896       
_________________________________________________________________
max_pooling2d_4 (MaxPooling2 (None, 9, 9, 32)          0         
_________________________________________________________________
conv2d_5 (Conv2D)            (None, 7, 7, 64)          18496     
_________________________________________________________________
max_pooling2d_5 (MaxPooling2 (None, 3, 3, 64)          0         
_________________________________________________________________
flatten_2 (Flatten)          (None, 576)               0         
_________________________________________________________________
dense_6 (Dense)              (None, 128)               73856     
_________________________________________________________________
dense_7 (Dense)              (None, 128)               16512     
_________________________________________________________________
dense_8 (Dense)              (None, 6)                 774       
=================================================================
Total params: 110,534
Trainable params: 110,534
Non-trainable params: 0
```
### Prerequisites
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook (optional, for running notebooks)

## Contributors

- Abdul Moiz Soomro
- Shehryar Ahmed

## Acknowledgements

- The dataset and initial model were sourced from Kaggle.
- This project was developed as part of our studies at FAST - National University of Computer and Emerging Sciences.

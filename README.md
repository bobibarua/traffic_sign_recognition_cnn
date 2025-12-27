# Traffic Sign Recognition using CNN

## Project Overview

This is a basic deep learning project that performs **traffic sign classification** using a **Convolutional Neural Network (CNN)**. The model is trained to recognize different traffic signs from images and predict their corresponding class.

The project is based on the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset and demonstrates a standard image classification workflow using TensorFlow and Keras.

---

## Dataset

* **Source**: Kaggle – German Traffic Sign Recognition Benchmark (GTSRB)
* **Total Classes**: 43 traffic sign categories
* **Input**: RGB images resized to 32×32 pixels

The dataset is automatically downloaded using the `opendatasets` library.

---

## Model Used

* Convolutional Neural Network (CNN)

### Architecture (High-level)

* Convolution + ReLU layers
* Max Pooling
* Dropout for regularization
* Fully connected dense layers
* Softmax output for multi-class classification

---

## Training & Evaluation

* Images normalized to the range [0, 1]
* Categorical cross-entropy loss
* Adam optimizer
* Accuracy used as the evaluation metric

The model is evaluated on a held-out test set and achieves strong classification accuracy across traffic sign classes.

Additional analysis includes:

* Training vs validation accuracy and loss curves
* Confusion matrix for class-wise performance
* Grouped confusion matrix for high-level sign categories

---


## Author

Bobi Barua
GitHub: [https://github.com/bobibarua](https://github.com/bobibarua)

---

This is a **basic CNN-based computer vision project** intended for learning and practice purposes.

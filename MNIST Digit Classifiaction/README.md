# **MNIST Dataset**
The MNIST (Modified National Institute of Standards and Technology) dataset is one of the most famous and foundational datasets used in machine learning, 
particularly for deep learning tasks like handwritten digit classification. It consists of a large collection of grayscale images of handwritten digits 
from 0 to 9, designed to serve as a benchmark for evaluating various machine learning models, especially neural networks.

## **Dataset Composition:**

- **Training Set:** 60,000 images
- **Test Set:** 10,000 images
- **Image Size:** 28x28 pixels, resulting in 784 pixels per image
- **Number of Classes:** 10 (digits 0-9)
- **Grayscale Values:** Each pixel has an intensity value between 0 and 255, where 0 represents black and 255 represents white.
  
Each image in the MNIST dataset is centered and normalized, making it relatively easy to work with. 
The dataset has been curated to ensure high-quality digit representation, removing much of the noise commonly associated with raw data.

## **Importing the MNIST Dataset from TensorFlow**

TensorFlow provides an easy way to access and import the MNIST dataset through its built-in `tensorflow_datasets` (TFDS) and
`keras.datasets` modules. Both methods make it simple to load the dataset, preprocess the images, and use it directly in your deep learning models.

**using keras.datasets**
The `keras.datasets` module, part of the TensorFlow keras API, offers a simpler and more direct way to load the MNIST dataset. 
This method is especially useful when you want to get started quickly without worrying about custom pipelines.

`from tensorflow.keras.datasets import mnist`

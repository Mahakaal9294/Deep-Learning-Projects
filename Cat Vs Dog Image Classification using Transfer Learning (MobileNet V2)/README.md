# **Cat vs Dog Image Classification using MobileNetV2**

This project aims to classify images as either a cat or a dog using a deep learning model. 
The dataset for training and testing the model is sourced from [Kaggle's Dogs vs Cats dataset](https://www.kaggle.com/datasets/biaiscience/dogs-vs-cats), 
consisting of labeled images of cats and dogs. To improve efficiency and accuracy, 
I have utilized a pretrained model, [MobileNetV2](https://www.kaggle.com/models/google/mobilenet-v2/TensorFlow2/tf2-preview-feature-vector/4), which is optimized for mobile and edge devices due to its low memory requirements and high performance.

## **Key Features:**

- **Dataset:** Dogs vs Cats dataset from Kaggle.
- **Pretrained Model:** MobileNetV2, a state-of-the-art model designed for image classification tasks.
- **Transfer Learning:** Leveraged the pretrained MobileNetV2 model for feature extraction to fine-tune the model for the task of classifying cat and dog images.
- **Performance:** A highly efficient and lightweight model suitable for deployment in mobile or web-based environments.

## **How it works:**
The project uses TensorFlow and Keras for building and training the model.
Transfer learning is employed, using the pre-trained MobileNetV2 as a base, and the final layer is fine-tuned to classify images into two categories: cats and dogs.
This repository contains the code for preprocessing the images, training the model, and evaluating its performance.

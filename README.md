# **🐶 End-to-End Multi-Class Dog Breed Classification**

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.

## **1. Problem**

Identifying the breed of a dog given an image of a dog.

When I'm siting at the cafe andI take photo of a dog, I want to know what breed of dog it is.

## **2. Data**

The data we are using is from Kaggle's Dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification

## **3. Evaluation**

The evaluation is a file with prediction probabolities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## **4. Features**

Some information about the data:
* We are dealing with images (unstructured data) so its probably we use deep learning/ transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set (these images have labels).
* There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them).

## **5. Visualization**

**5.1 Value Counts**

![image](https://github.com/user-attachments/assets/a9850b95-272b-473f-b70d-cfe0adbc3cb5)

**5.2 Training Data**

![image](https://github.com/user-attachments/assets/136b2705-8c5d-4bab-b1cf-4bccd1a6c9a3)

## **6. Predictions**

![image](https://github.com/user-attachments/assets/186d6314-4b8a-416b-8928-0fe145342219)

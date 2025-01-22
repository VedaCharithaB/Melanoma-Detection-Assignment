# Melanoma-Detection

> To build a CNN-based model that can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project aims to develop a deep learning-based solution for melanoma detection using convolutional neural networks (CNNs).
- The dataset consists of 2357 images of malignant and benign oncological diseases, derived from the International Skin Imaging Collaboration (ISIC).
- The primary goal is to build a multiclass classification model that detects 9 types of skin diseases, with an emphasis on melanoma detection.
- Dataset includes:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion

## Conclusions
- A CNN model was built and trained to classify 9 skin diseases.
- The model initially showed signs of overfitting, which was mitigated by applying data augmentation techniques.
- Handling class imbalance with augmentation significantly improved the model's performance.
- Final accuracy metrics indicate the model is reliable for classifying skin diseases, including melanoma.

## Technologies Used
- python
- pandas
- numpy
- matplotlib
- pathlib
- seaborn
- sklearn
- Keras
- tensorflow

## Acknowledgements
- This project was inspired by a group case study for an advanced online course.
- References:
  - [GeeksforGeeks](https://www.geeksforgeeks.org/)
  - [Pandas Documentation](https://pandas.pydata.org/)
  - [UpGrad Learning Platform](https://learn.upgrad.com/)
  - [TensorFlow Documentation](https://www.tensorflow.org/)

## Contact
Created by [@vedacharithaB] - feel free to contact me!


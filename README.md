# Animal Image Classifier

Exam Date: July 2023

For additional and clearer information I really invite you to see the comments inside the .ipynb file: [link](https://github.com/TitoNicolaDrugman/DeepLearningExam/blob/master/DRUGMAN_502252.ipynb).


## Table of Contents
- [Project Description](#project-description)
- [Key Objectives](#key-objectives)
- [Deep Learning Approach](#deep-learning-approach)
- [Valuable Learning Experience](#valuable-learning-experience)
- [Contributing](#contributing)

## Project Description

The "Animal Image Classifier" project presented a unique and challenging task: classifying RGB images of three different animals while also predicting the location of the animal within the image. This project was inspired by a real-world scenario, where we were given a dataset of RGB images, each represented as a 3-dimensional tensor of shape (224, 224, 3), along with coordinates for the bounding boxes containing the animals. The dataset was structured as follows:

1. Each image was a 3-dimensional tensor with the last dimension representing the number of input channels.
2. The dataset included 65 labeled samples for each of the three animal classes.
3. The values in each tensor entry ranged from 0 to 255.
4. For each image, a coordinate vector was provided, specifying the bottom-left and top-right corners of the bounding rectangle containing the animal within the image.

## Key Objectives

The primary objectives of this project were twofold:

1. Classify the image, determining which animal it contained among a1, a2, and a3. This required building a robust image classification model.
2. Predict the location of the bounding box, represented as a vector of four coordinates, as described above. This was a challenging regression task that involved predicting the coordinates for the bounding box.

## Deep Learning Approach

To address these objectives, I designed a deep neural network model that was capable of simultaneously performing image classification and bounding box localization. This model was trained to leverage the provided labeled data to make accurate predictions for both tasks.

The project not only expanded my knowledge of deep learning but also highlighted the importance of handling real-world data and solving multifaceted problems using neural networks.

## Valuable Learning Experience

The "Animal Image Classifier" project challenged me to think creatively and apply advanced deep learning techniques to a real-world problem. It also emphasized the significance of model interpretation and evaluation, especially in scenarios where both classification and regression tasks coexist.

## Contributing

If you have ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request. Let's make the "Animal Image Classifier" even more extraordinary together!

For additional information: [link](https://github.com/TitoNicolaDrugman/DeepLearningExam/blob/master/DRUGMAN_502252.ipynb).

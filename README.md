# Melanoma Detection Case Study Using CNN
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis

## General Information
Melanoma is a type of cancer that can be fatal if not detected early, accounting for 75% of skin cancer deaths. To address this problem, we aim to build a CNN-based model that can accurately detect melanoma from images, potentially reducing the manual effort required for diagnosis.

The data set contains the following diseases:
Actinic keratosis Basal cell carcinoma Dermatofibroma Melanoma Nevus Pigmented benign keratosis Seborrheic keratosis Squamous cell carcinoma Vascular lesion

The dataset used in this project consists of 2239 images of malignant and benign oncological diseases, sorted according to the classification taken with the International Skin Imaging Collaboration (ISIC). The dataset includes nine classes, including Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion. Our business goal is to build a multiclass classification model using a custom convolutional neural network in TensorFlow. The potential business risk is predicting an incorrect class of skin cancer, which could lead to misdiagnosis and inadequate treatment.
The project pipeline includes several stages, starting with data reading and understanding, creating a dataset from the train directory, and visualizing the data. Next, we build and train a CNN model with an appropriate optimizer and loss function, using an appropriate data augmentation strategy to resolve underfitting or overfitting. We examine the current class distribution in the training dataset and identify the class with the least number of samples, as well as the classes that dominate the data in terms of the proportionate number of samples. We use the Augmentor library to rectify class imbalances present in the training dataset.

Finally, we build and train a CNN model on the rectified class imbalance data, using an appropriate optimizer and loss function, and train the model for approximately 30 epochs. We record our findings after each model fit, checking for evidence of overfitting or underfitting, and assessing whether the earlier issues have been resolved or not.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Result
ACCURACY='87%' VALLIDATION_ACCURACY='81%'

The model is not overfitting and due to augmentation the accuracy has significantly increased Yes class rebalance helped here, as its important to balance out the data set or at least get it close to balance it in

## Contact
Created by [@kapoorsnikhil] - feel free to contact me!


This code is GNU GENERAL PUBLIC LICENSED.

If you have any suggestions or identified bugs please feel free to post them!
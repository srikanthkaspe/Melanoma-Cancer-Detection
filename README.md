# MelanomaCancerDetection
# Melanoma Cancer Detection Using CNN
> Melanoma is a dangerous type of skin cancer that develops from melanocytes, the cells that produce melanin, the pigment giving skin its color. It can grow rapidly and spread to other parts of the body if not detected and treated early.

> Using Convolutional Neural Networks (CNNs) for melanoma detection involves applying deep learning techniques to diagnose skin cancer from images. CNNs excel at image classification tasks because they automatically learn spatial hierarchies of features from raw pixel inputs, which is essential for medical imaging tasks like melanoma detection.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

### Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Conclusions
- Conclusion 1: Model 1 exhibits a Training Accuracy of 62.10% and a Validation Accuracy of 53.91%, which are nearly identical yet significantly low, suggesting underfitting.
- Conclusion 2: Model 2, trained on Augmented Data, shows a Training Accuracy of 51.95% and a Validation Accuracy of 50.78%, which are quite similar, as are the losses. However, the accuracies are low, indicating the model may require additional epochs and adjustments for class imbalance.
- Conclusion 3: Model 3, trained on data with corrected class imbalance, achieves a Training Accuracy of 90.52% and a Validation Accuracy of 82.03%, which are closely matched. The proximity of training and validation losses indicates a good fit, with the model successfully classifying images with an 82% Validation Accuracy.


## Technologies Used
- Tensorflow- version 2.17.0
- Keras     - version 3.4.1
- Pandas    - version 2.1.4
- Augmentor - version 0.2.12
- Numpy     - version 1.26.4
- SNS		- version 0.13.1


## Acknowledgements
Within the UpGrad IITB Programme, a case study titled "Melanoma Detection Assignment" was conducted, utilizing knowledge from the Deep Learning CNN Module..


## Contact
Created by [@srikanthkaspe] - feel free to contact me!


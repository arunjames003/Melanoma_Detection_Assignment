# Melanoma Detection Assignment


## Table of Contents
- General Information
- Conclusions
- Python Library Used for Analysis
- Contact


## General Information
The project involves building a multiclass classification model using a custom Convolutional Neural Network (CNN) in TensorFlow. The aim is to accurately detect melanoma and other skin diseases from images. Melanoma, a deadly form of skin cancer if not detected early, accounts for 75% of skin cancer deaths. The model will evaluate skin images and help dermatologists identify the presence of melanoma, thereby reducing the manual effort needed in diagnosis and potentially saving lives.

* Background of your project?
Melanoma is a significant health concern due to its high mortality rate if not detected early. Early and accurate detection is crucial for effective treatment. The International Skin Imaging Collaboration (ISIC) has provided a dataset of images categorized into various oncological diseases, including melanoma. This project leverages advanced machine learning techniques, specifically CNNs, to analyze these images and classify them into one of several categories of skin diseases. CNNs are particularly effective for image classification tasks due to their ability to capture spatial hierarchies in images.

* Business problem that project is trying to solve
The business problem this project addresses is the need for an efficient and reliable method to assist dermatologists in diagnosing melanoma and other skin conditions. Traditional methods of diagnosing skin diseases involve manual examination and biopsies, which are time-consuming and require significant expertise. By automating the image analysis process, the project aims to reduce the workload on dermatologists, expedite the diagnostic process, and improve accuracy. This can lead to early detection and treatment of melanoma, ultimately reducing mortality rates and improving patient outcomes. 

* Dataset that is being used
The dataset used in this project consists of 2357 images of various malignant and benign oncological diseases. These images were sourced from the International Skin Imaging Collaboration (ISIC). The dataset includes the following categories of skin diseases:

    1. Actinic keratosis
    2. Basal cell carcinoma
    3. Dermatofibroma
    4. Melanoma
    5. Nevus
    6. Pigmented benign keratosis
    7. Seborrheic keratosis
    8. Squamous cell carcinoma
    9. Vascular lesion
    
The images are evenly distributed among these categories, with a slight dominance of melanoma and nevus images. This balanced dataset ensures that the model can learn to distinguish between different types of skin diseases accurately.


## Conclusions
* Training Accuracy and Loss:
- The training accuracy steadily increases from 11.80% in Epoch 1 to 85.96% in Epoch 20.
- The training loss shows a consistent decrease from 3.7542 in Epoch 1 to 0.4020 in Epoch 20.
- This indicates that the model is learning and fitting the training data well over time.

* Validation Accuracy and Loss:
- The validation accuracy improves from 18.64% in Epoch 1 to a peak of 39.98% in Epoch 8, but then fluctuates and ends at 34.75% in Epoch 20.
- The validation loss initially decreases from 3.2112 in Epoch 1 to a low of 2.0805 in Epoch 7, but then increases significantly, reaching 4.7755 in Epoch 20.
- This suggests that the model is overfitting the training data after the initial few epochs.

* Overfitting:
- There is a clear divergence between the training and validation performance metrics starting around Epoch 7-8. While training accuracy continues to improve and training loss decreases, validation accuracy stagnates and validation loss increases.
- Overfitting is evident as the model becomes too specialized in the training data, losing its ability to generalize to unseen validation data.

* Conclusion
- The model is capable of learning and fitting the training data effectively.
- However, it struggles with generalization, leading to overfitting after initial improvement on the validation set.


## Technologies Used
- numpy - version 1.24.3
- pandas - version 2.1.4
- matplotlib - version 3.7.2
- Tensor Flow - version 2.16.1
- Keras - version 3.3.3


## Contact
Created by [@arunjames003] - feel free to contact me!

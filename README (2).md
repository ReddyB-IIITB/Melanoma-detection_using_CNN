
# Melanoma-Detection-Using-CNN
Melanoma is type of skin cancer, develop primarily in the cells (called melanocytes) that produce melanin pigment. Melanoma however can also be developed in eyes, but rarely inside the body.One of the common known reasons for melanoma is prolonged exposure to high amount of UV-radiations, but there are lot more underlying reasons as well ranging from genetic predisposition, epigenetics and many more under investigation. This type of cancer accounts for 75% skin cancer driven deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
1. General Info
2. Conclusions
3. Technologies Used
4. Acknowledgements
5. Contacts
## Table of Contents
1. General Info
2. Conclusions
3. Technologies Used
4. Acknowledgements
5. Contacts
## General Info
A CNN model is to be built using number of images of Melanoma based cancers (learning data) that can help in designing an algorithm helpful in accurate primary diagnosis of different types of Melanoma (testing data). These type of applications are gaining increased traction from scientific and medical community as it can be of huge help in reducing the manual ambiguity in reading the images and can serve as an empirical tool for primary diagnosis. Images are sourced from International Skin Imaging Collaboration (ISIC).

The data set contains the images classified under the following disease categories:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

Project Pipeline:

    1. Data Reading and understanding
    2. Data Set Creation - Train and Test, with images resized to 180 X 180
    3. Dataset visualization
    4. Model Building and training
    5. Choosing the appropriate data augmentation
    6. Model training on augmented data
    7. Handling class imbalances
    8. Model training on rectified class imbalance data
## Conclusions
-  Both the accuracies are very much close.
-  Loss also seems pretty close and similar jump can be seen between epochs 30-40
-  Validation accuracy is 91% which is good fit.
## Techonologies Used
Python and Other Libraries
    tensorflow
    keras
    pathlib
    matplotlib
    numpy
    pandas
    seaborn
    os
    PIL
    glob
    
## Contacts

    * Balakrishna (Balu.Dearestsis0307@gmail.com )
    * Harikrishnan Bellan (hariifs17@gmail.com)
    * Uma Koppada (koppada.uma@gmail.com)
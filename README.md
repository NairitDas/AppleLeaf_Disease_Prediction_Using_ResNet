# Plant Disease Identification using Deep Learning

This project addresses the critical challenge of automated plant disease detection, focusing on apple leaf diseases which significantly impact apple yield and farmers' economic income.  
Traditional disease identification methods require expert knowledge and are time-consuming, highlighting the need for an automated solution.  
Leveraging Convolutional Neural Networks (CNN), our approach benefits from strong generalization, robustness, and automatic feature extraction.  
Images are preprocessed by converting them to LAB color space and applying Otsu segmentation to effectively extract disease spots.  
We explored various classification techniques, including a Support Vector Machine (SVM) classifier and deep learning models such as ResNet-18, ResNet-34, and VGG-16.  
Among these, the ResNet-18 model achieved the highest accuracy of 98.5%, outperforming the other models in our study.  
Additionally, a custom ResNet architecture was implemented with data augmentation to further enhance model robustness.  
The training process employed a one-cycle learning rate policy and included monitoring of training and validation loss to prevent overfitting.  
The final model demonstrated impressive performance, reaching a validation accuracy of 99.2%, proving its effectiveness in classifying plant diseases.  
This project provides an effective and scalable solution for large-scale, automated plant disease identification, contributing to precision agriculture.  
It aims to set a benchmark for future research and practical applications in the agricultural industry.

## Dataset
The dataset for this project can be accessed [here](https://drive.google.com/drive/folders/1FYcgaLUg25wPfBQC0RQw5cYi7vd61Hl7?usp=sharing).

## Tools and Technologies
- Python
- PyTorch
- Convolutional Neural Networks (ResNet, VGG)
- Data Augmentation
- One-cycle Learning Rate Policy
- Image Segmentation

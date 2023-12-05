## Table of Contents
1. Outline
2. System Specifications
3. Repository Structure
4. Installation and Operation Guide
5. Data

## Outline
This code repository encompasses the implementation of a novel system engineered to identify concealed vulnerabilities, commonly known as backdoors, within neural networks. The primary objective of this project is to enhance the security of neural networks, particularly those trained on the YouTube Face dataset. This is achieved through the development of an advanced model named GoodNet, meticulously designed to discern between normal and compromised inputs, efficiently classifying them into separate categories.
## System Specifications
Environment: Windows 11 Laptop
Interface: Google Colab Pro

## Repository Structure
Notebook report Model: model_x_10.h5 , model_x_2.h5 , model_x_4.h5

## Installation and Operation Guide
Save the repo in your computer
Run Google Colab Pro Notebook and upload data to Google Drive.

## Data
1.  Download the validation and test datasets from  [here](https://drive.google.com/drive/folders/1Rs68uH8Xqa4j6UxG53wzD0uyI8347dSq?usp=sharing) and upload them to Google Drive under
     bd/ and cl/ and sunglasses_bd_net.h5
3.  The dataset contains images from the YouTube Aligned Face Dataset. We retrieved 1283 individuals and split them into validation and test datasets.
4.  bd_valid.h5 and bd_test.h5 contains validation and test images with sunglasses trigger respectively, that activates the backdoor for bd_net.h5.# ml_cybersec_lab4

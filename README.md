# Skin Cancer Detection & Dermatological Image Classification Using IBM Z - CodeHnt TUT33

## Problem Statement

Skin cancer is one of the most prevalent forms of cancer worldwide, and early detection is crucial to improving survival rates. Traditional diagnostic methods often rely on visual inspections or invasive biopsies, which can be time-consuming and dependent on a clinician's skill. This can lead to missed diagnoses or delayed treatments.

In this project, we tackle two significant challenges under the "Tech for Good" initiative:
1. **Skin Cancer Detection:** Using a machine learning model to detect skin cancer from dermatoscopic images.
2. **Dermatological Image Classification:** Leveraging Convolutional Neural Networks (CNNs) to classify pigmented skin lesions for the early detection of skin cancer.

Both tasks utilize IBM Z (LinuxONE) platform, leveraging its computational power and scalability to provide efficient, timely, and accurate diagnosis tools.

## Data

1. **Skin Cancer Detection:** The dataset was sourced from Kaggle and includes high-resolution dermatoscopic images of skin lesions labeled as either malignant or benign.
   
2. **Dermatological Image Classification:** The classification of pigmented skin lesions presents challenges due to the small size and lack of diversity in available datasets. These factors can hinder model generalization, but we employ data augmentation and regularization to mitigate overfitting.

## Solution

### Skin Cancer Detection

We developed a deep learning model using PyTorch that analyzes dermatoscopic images and classifies skin lesions as either malignant or benign. Our goal is to aid healthcare professionals by providing an automated system capable of accurate early diagnosis.

### Dermatological Image Classification with CNNs

To further enhance the diagnosis process, we implemented a Convolutional Neural Network (CNN) to classify various types of skin lesions. CNNs are highly effective for image classification tasks, but the limited size of our dataset posed challenges. We tackled these with techniques like data augmentation and dropout to improve the model's ability to generalize to new, unseen data.

#### Goal:
For the dermatological classification, our target was to achieve accuracy in the 80th percentile, taking into account the limited time and dataset size.

## Tech Stack

This project was built using the following technologies:

- **IBM Z (LinuxONE):** The platform was used to train and test both models, providing the scalability required to process large datasets and handle complex deep learning tasks.
- **Python:** For scripting and building the models.
- **NumPy & Pandas:** For data processing and manipulation.
- **Matplotlib:** For visualizing data trends and model performance.
- **PyTorch:** For developing the deep learning models.
- **Kaggle Datasets:** Dermatoscopic image datasets were sourced from Kaggle, providing labeled images for skin cancer detection.

## Leveraging IBM Z for Scalability

- **Model Testing:** The models were tested on the IBM Z platform, ensuring they could scale efficiently for large-scale, real-world use.
- **Python & Libraries Support:** IBM Z provided an environment that seamlessly integrated Python and libraries like NumPy, Pandas, Matplotlib, and PyTorch, making end-to-end development and deployment smooth.
- **KaggleHub Integration:** We used KaggleHub to import and manage datasets within the IBM Z environment, enabling efficient data handling.

## Conclusion

Our project demonstrates how IBM Z can be used to develop machine learning models aimed at improving healthcare outcomes. Through CNNs for dermatological image classification and a skin cancer detection model, we hope to contribute to early diagnoses, helping prevent the progression of skin cancer and saving lives with timely interventions.


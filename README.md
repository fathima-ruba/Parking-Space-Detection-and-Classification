# Smart Parking Management System

## 1. Introduction
The increasing number of vehicles has led to a shortage of parking spaces in urban areas. Automated parking space detection and classification systems can help in efficiently managing available parking spaces. This project aims to develop a computer vision-based system to detect parking spaces and classify them as 'Free' or 'Occupied'.

## 3. Methodology
The project uses traditional image processing techniques and machine learning for parking space detection and classification. Contours are used to detect parking spaces in mask images. Support Vector Machine (SVM) is used for classification.

## 4. Data Description
The dataset consists of images of parking lots along with corresponding mask images that outline the parking spaces. Each image is labeled as either 'Free' or 'Occupied' based on the average pixel intensity in the region of interest (ROI).

## 5. Implementation
The implementation involves the following steps:
1. Data Preparation: Extract ROIs from the images and label them.
2. Feature Extraction: Resize and flatten the ROIs to form feature vectors.
3. Model Training: Train an SVM classifier on the features.
4. Evaluation: Evaluate the model on a separate test set.
5. Application: Use the trained model to classify parking spaces in new images.

## 6. Results
The SVM model achieved an accuracy of approximately 97.47% on the test set. The model was then successfully applied to new images for parking space classification.

## 7. Discussion
The high accuracy of the model suggests that it is capable of classifying parking spaces with good reliability. However, the model is based on a simple intensity threshold, and more advanced techniques could be explored for better accuracy.

## 8. Conclusion
The project demonstrates the potential of using computer vision and machine learning techniques for automated parking space management. Future work could involve testing the system in real-time scenarios and integrating it with other smart city solutions.

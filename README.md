# Eye-Disease-Classification-using-YOLOv11
This project applies YOLOv11, a state-of-the-art object detection and classification algorithm, to classify eye images for detecting blindness-related diseases.

The dataset used is sourced from Kaggle's Blindness Detection Images. (//www.kaggle.com/datasets/benjaminwarner/resized-2015-2019-blindness-detection-images.)

Key Features
Data Preparation:

The dataset was split into training and validation sets with an 80-20 ratio.
Ensured balanced classes by limiting image counts in each class to a target number.
Model Implementation:

YOLOv11 was trained to classify images based on their severity of blindness.
Performance metrics include precision, recall, and F1-score.
Automation and Scalability:

Scripts automate data organization and ensure reproducibility.
Includes tools to validate dataset integrity and balance.
Dataset
The dataset consists of resized images of eye scans, labeled with different categories of blindness severity. It is preprocessed to remove excess data and maintain balance among categories.

How to Use
Clone this repository.
Install required dependencies (requirements.txt).
Run the training pipeline to train YOLOv11 on the dataset.
Evaluate the model on validation data.
Results
The YOLOv11 model achieves promising results, demonstrating its potential for medical image classification tasks.

![image](https://github.com/user-attachments/assets/6e29bc1e-a96f-4865-9ba2-ada78a56a961)


![image](https://github.com/user-attachments/assets/a05a9749-9468-41e0-b0cf-33dec3cc730e)


![image](https://github.com/user-attachments/assets/8de4f85a-9fa9-4ae1-9621-2731ed7f9a19)


![image](https://github.com/user-attachments/assets/1b537394-2678-45f1-80a8-4ffc8d582515)


![image](https://github.com/user-attachments/assets/456f29b0-dcb2-4fa3-8320-5df9ded42ec6)




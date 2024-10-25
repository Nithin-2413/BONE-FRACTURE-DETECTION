Overview


This project aims to develop an automated system to detect bone fractures from X-ray images using hybrid deep learning models. By combining MedNet and CNN architectures, the system efficiently classifies fractured and non-fractured bones, aiming for an accuracy of over 94%. The project also includes MATLAB-based visualizations comparing model performance.

The **Automated Bone Fracture Detection** project focuses on identifying bone fractures from X-ray images using a hybrid deep learning model that combines MedNet and CNN architectures. The model is designed to improve both accuracy and training efficiency, with the goal of achieving a classification accuracy of over 97%. The dataset used contains thousands of images categorized into fractured and non-fractured bones, ensuring robust training. The project also includes MATLAB visualizations to compare performance metrics like accuracy, precision, recall, and training time across different models. This system is intended for real-time clinical applications in medical diagnostics.

![download (1)](https://github.com/user-attachments/assets/f600e628-acd7-4a16-ac5a-dc3048d353de)

Dataset
Source: MURA DATASET -- X-ray images structured into two categories: Fractured and Non_Fractured.
Size: The dataset contains 30,000 images, but a subset of 10,000 images is used for training and testing to optimize performance.

![p-r](https://github.com/user-attachments/assets/48e5da26-48d7-4c66-b39a-7b7ac8ba3477)

Folders:


Fractured/: Contains images of bones with fractures.
Non_Fractured/: Contains images of normal bones.


Model Architecture
Hybrid Model: MedNet + CNN
Goal: Achieve high accuracy (>94%) with optimized training time.
Key Features: The model combines the strengths of Convolutional Neural Networks (CNN) for feature extraction and MedNet for better classification, ensuring faster and more accurate predictions.
Requirements
Python 3.x
TensorFlow / PyTorch
OpenCV for image processing
MATLAB for visualization

Visualizations
The project includes MATLAB scripts for generating visual comparisons across various models, highlighting performance metrics like accuracy, precision, and recall.

Results
Accuracy: >94%
Precision/Recall: High accuracy in fracture detection.
Training Time: Optimized for faster execution without compromising performance.

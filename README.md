# Sports-celebrity-Recognition


This project focuses on building an end-to-end machine learning system to classify images of five different sports celebrities. It employs various image preprocessing techniques, feature extraction methods, and machine learning algorithms to achieve high accuracy in identifying celebrities from images.

---

## **Objective:**

The objective of this project is to develop a system that accurately classifies images of sports celebrities using machine learning. By leveraging tools such as OpenCV for image preprocessing, Pywavelet for feature extraction, and Support Vector Machines (SVM) for classification, the system aims to automate the process of recognizing celebrities in sports images.

---

## **Technologies and Tools Learned:**

- **Programming Language**: Python
- **Data Cleaning**:
  - **Pandas**: For manipulating and cleaning the dataset.
  - **NumPy**: For numerical operations and image data handling.
- **Data Visualization**:
  - **Matplotlib** and **Seaborn**: For visualizing the data and model performance.
- **Image Processing**:
  - **OpenCV**: Used for image preprocessing tasks like face detection using Haar cascades and image cleaning.
  - **Pywavelet**: For wavelet transformations to extract meaningful features from images.
- **Machine Learning**:
  - **Scikit-Learn (Sklearn)**: Used for model building, classification, and performance evaluation, including SVM, GridSearchCV, and confusion matrix analysis.
- **Model Saving**:
  - **Joblib** and **Pickle**: Used for saving and loading the trained model.
- **IDE**:
  - **Jupyter Notebook**, **Visual Studio Code**, and **PyCharm**: Used for development and experimentation with the project.

---

## **Result:**

- A machine learning model based on **Support Vector Machine (SVM)** was successfully developed and optimized to classify images of sports celebrities with an overall model accuracy of 78 %.
- By using **Haar cascades** to detect faces and eyes in the images, the data was effectively cleaned, discarding unsuitable images.
- The combination of **wavelet transforms** and **raw pixel data** was used for feature extraction, followed by classification using SVM.
- The model was fine-tuned using **GridSearchCV** to optimize hyperparameters, and **classification reports** were used to assess performance.
- The model was evaluated using a **confusion matrix**, helping to identify classification errors.
- Finally, the optimized model was saved for future use using **Joblib**, achieving accurate results on test data.

This project showcases practical applications of image classification, data preprocessing, and model optimization techniques in a real-world scenario, providing a robust and effective sports celebrity image classification system.

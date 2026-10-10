# 🐱🐶 Cats vs Dogs Classification Using SVM

## Prodigy InfoTech — Machine Learning Internship
### Task 03

## 📌 Project Overview

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs using image preprocessing and feature extraction techniques.

The project compares Linear SVM models using RGB pixel features and Histogram of Oriented Gradients (HOG) features with an RBF Kernel SVM using HOG features.

## 🎯 Objectives

- Explore the Cats vs Dogs image dataset.
- Preprocess images and extract numerical features.
- Implement Linear SVM and RBF Kernel SVM classifiers.
- Evaluate model performance using standard classification metrics.
- Visualize and compare model accuracy.
- Predict the class of new images.

## 📂 Dataset

The project uses the Dogs vs Cats dataset available on Kaggle.

Dataset: https://www.kaggle.com/datasets/salader/dogsvscats

For this experiment, 1,000 images were selected:
- 500 cat images
- 500 dog images

The data was divided into:
- Training: 800 images
- Testing: 200 images

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Matplotlib
- Scikit-learn
- Scikit-image
- Pillow
- KaggleHub

## ⚙️ Methodology

1. Dataset loading and exploration
2. Image resizing to 64 × 64 pixels
3. RGB pixel feature extraction
4. HOG feature extraction
5. Train-test split
6. SVM model training
7. Model evaluation and comparison
8. Prediction on new images

## 📊 Model Performance

| Model | Features | Accuracy |
|---|---|---:|
| Linear SVM | RGB Pixels | 60.50% |
| Linear SVM | HOG Features | 60.50% |
| RBF Kernel SVM | HOG Features | 69.00% |

The RBF Kernel SVM achieved the highest accuracy of 69.00% among the evaluated models.

## 🔍 Evaluation Metrics

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🚀 How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Install the required Python libraries.
3. Access the Kaggle dataset.
4. Run the notebook cells in order.
5. Review the evaluation results and visualizations.

## 📝 Conclusion

This project demonstrates how SVM can be applied to image classification using RGB pixel values and HOG features.

The RBF Kernel SVM performed better than the Linear SVM models in this experiment.

The reported results are based on a subset of 1,000 images. Performance may vary when using a larger dataset or different model settings.

## 👨‍💻 Author

Spandan Kar

BTech CSE (AI & ML)

Machine Learning Internship — Task 03

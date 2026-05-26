# Handwritten Digit Recognition (SVM + PCA)

A machine learning pipeline to classify handwritten digits (0-9) from raw image data.

## 🚀 Features
- **Preprocessing:** Automated Otsu’s binarization and grayscale normalization.
- **Augmentation:** Generates synthetic training data via rotation and translation.
- **Efficiency:** PCA dimensionality reduction (retaining 90% variance).
- **Optimization:** SVM with RBF kernel tuned via GridSearchCV.
- **Testing:** Interactive utility for custom image uploads and real-time prediction.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Scikit-learn, OpenCV, NumPy, Matplotlib

## ⚙️ Quick Start
1. Run `ml1.ipynb` in Google Colab.
2. Mount Google Drive and provide the dataset `.zip`.
3. The script will train the model and output a confusion matrix.
4. Use the final cell to upload and test your own handwritten digits.

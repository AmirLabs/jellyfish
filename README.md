
# Jellyfish Classification Project

In this project, we classify different species of jellyfish using image processing and machine learning techniques.

## Libraries Used

- **OpenCV (cv2)**: Image processing (resizing, color conversion, feature extraction).
- **pandas**, **numpy**: Data handling and numerical operations.
- **scikit-learn**:
  - **LabelEncoder**: Encoding species labels.
  - **KernelPCA**: Dimensionality reduction.
  - **LogisticRegression**: Classifier.

## Steps

1. **Data Preprocessing**: 
   - Images are resized, converted to HSV, and feature vectors (color histogram & Hu Moments) are extracted.
   
2. **Dimensionality Reduction**: 
   - Kernel PCA is used to reduce the feature space to 25 components.

3. **Model Training**:
   - A Logistic Regression model is trained to classify jellyfish species.

## How to Run

1. **Install Required Libraries**:
   ```bash
   pip install opencv-python pandas numpy scikit-learn
   ```

2. **Prepare Data**: 
   - Structure data as `jellyfish/[species]/o1.jpg, o2.jpg, ...`.

3. **Run the Code**: 
   - Process images, train the model, and evaluate accuracy.

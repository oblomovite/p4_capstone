# Image Classification with Deep Learning of Pediatric Chest X-rays

## 1. Business Understanding

- **Objective:** Classify chest X-ray images to detect pneumonia in pediatric patients.
- **Success Criteria:** A working deep learning model that achieves reasonable accuracy and demonstrates iterative improvement.

## 2. Data Understanding

- **Dataset:** Pediatric chest X-ray dataset from Kermany et al. (available on Mendeley and Kaggle).
- **Data Characteristics:**
  - Image format (e.g., resolution, grayscale/RGB)
  - Class distribution (Normal vs. Pneumonia)
  - Potential biases or imbalances in the dataset.

## 3. Data Preparation

- **Preprocessing:**
  - Resizing images for model input
  - Normalization (e.g., scaling pixel values)
  - Data augmentation (rotation, flipping, contrast adjustments)
- **Splitting Data:**
  - Train/Test/Validation split
  - Handling class imbalances (oversampling, weighted loss)

## 4. Modeling

- **Baseline Model:** Simple CNN to establish a starting point.
- **Architecture Iteration:**
  - Experiment with CNN architectures (e.g., deeper layers, different kernel sizes)
  - Pretrained models (e.g., ResNet, VGG)
  - Hyperparameter tuning (learning rate, batch size, dropout)
- **Training:**
  - Loss function (e.g., cross-entropy)
  - Optimization algorithm (e.g., Adam)
  - Performance tracking (accuracy, precision, recall, F1-score)

## 5. Evaluation

- **Metrics:** Accuracy, confusion matrix, ROC-AUC, precision-recall.
- **Error Analysis:** Misclassified images, model confidence scores.
- **Bias & Overfitting:** Check training vs. validation performance.

## 6. Deployment (Proof of Concept)

- **Inference on New Data:** Test model on unseen images.
- **Model Saving & Loading:** Export model for future use.
- **Limitations & Future Work:** Discuss areas for improvement.

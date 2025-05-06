# Diabetic-Retinopathy-Diagnosis
# Diabetic Retinopathy Detection with EfficientNetB5 🧠👁️

This project detects diabetic retinopathy from retinal fundus images using EfficientNetB5 with preprocessing and image enhancement.

## 🔬 Model Summary
- Pretrained Model: EfficientNetB5
- Input Size: 456x456
- Preprocessing: CLAHE, Gaussian Blur, Cropping, Median Filtering
- Dataset: [Kaggle - Diabetic Retinopathy Detection](https://www.kaggle.com/c/diabetic-retinopathy-detection)

## 📊 Performance
The EfficientNetB5 model was trained to classify diabetic retinopathy into five classes: No DR, Mild, Moderate, Severe, and Proliferative DR. On the validation set, it achieved an overall accuracy of 98.47%. The macro average F1-score was 96.95%, while the weighted average F1-score reached 98.47%.

Notably

No DR class was classified with perfect precision and recall (1.00),
Moderate class showed F1-score of 0.98,
Even less represented classes like Severe and Proliferative DR achieved F1-scores above 0.94.
These results indicate strong generalization, even across imbalanced class distributions.


## 📁 Files
- `model_efficientNet.ipynb`: Training notebook
- `test_predictions.csv`: Model predictions
- `test_accuracy.txt`: Final test metrics

## 🚀 How to Run
```bash
Open in Google Colab:
https://colab.research.google.com/drive/1DWGYKkIyE41SeH4N1Qax267czVtf72Cj

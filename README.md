# ReptiVision-AI --> Alligator vs Crocodile Image Classification.
## 📌 Project Overview

This project focuses on building an AI/ML-based Image Classification system capable of distinguishing between Alligators and Crocodiles using Deep Learning techniques.

The project was developed as part of an AI/ML Practical Interview Task where the objective was to design, train, evaluate, and test an image classification model using any preferred Deep Learning framework and architecture.

The solution uses Transfer Learning and Convolutional Neural Networks (CNNs) to achieve high classification accuracy.

## 🚀 GitHub Repository Structure
    Alligator-vs-Crocodile-Image-Classification/
    │
    ├── dataset/
    │   ├── train/
    │   │   ├── alligator/
    │   │   └── crocodile/
    │   │
    │   ├── validation/
    │   │   ├── alligator/
    │   │   └── crocodile/
    │   │
    │   └── test/
    │       ├── alligator/
    │       └── crocodile/
    │
    ├── notebooks/
    │   └── model_training.ipynb
    │
    ├── models/
    │   └── best_model.h5
    │
    ├── outputs/
    │   ├── prediction_samples/
    │   ├── confusion_matrix.png
    │   ├── training_accuracy.png
    │   └── training_loss.png
    │
    ├── src/
    │   ├── train.py
    │   ├── predict.py
    │   ├── preprocess.py
    │   └── utils.py
    │
    ├── requirements.txt
    ├── README.md
    ├── LICENSE
    └── .gitignore

## 🧠 Problem Statement

Differentiate between images of:

🐊 Alligator
🐊 Crocodile

using Deep Learning Image Classification techniques.

## 🎯 Objectives
 - Build an image classification model
 - Perform data preprocessing and augmentation
 - Train multiple Deep Learning models
 - Compare model performances
 - Select the best-performing model
 - Generate predictions on unseen images
 - Visualize model performance

## 📂 Dataset

The dataset used for this project is hosted on Google Drive due to GitHub file size limitations.

🔗 Dataset Link:
https://drive.google.com/file/d/1tVV5r3lnP5B1uUFtIwUgReaEbrKf1Fj8/view?usp=sharing

## 📂 Dataset Information

The dataset contains labeled images of:

   Class	                      Description
- Alligator	           -- Images of alligator species

- Crocodile	           -- Images of crocodile species

## Dataset Split
| Dataset Type | Percentage |
| ------------ | ---------- |
| Training     | 70%        |
| Validation   | 15%        |
| Testing      | 15%        |


## ⚙️ Technologies Used
- Programming Language
   - Python
- Libraries & Frameworks
   - TensorFlow / Keras
   - NumPy
   - Pandas
   - Matplotlib
   - Seaborn
   - OpenCV
   - Scikit-learn
- Tools
   - Jupyter Notebook
   - VS Code
   - Git & GitHub

 ## Deep Learning Models Tried
 
| Deep Learning Model | Type              | Accuracy |
| ------------------- | ----------------- | -------- |
| Custom CNN          | Scratch Model     | 88%      |
| MobileNetV2         | Transfer Learning | 94%      |
| ResNet50            | Transfer Learning | 96%      |
| EfficientNetB0      | Transfer Learning | 97%      |

## Best Model
## ✅ EfficientNetB0

EfficientNetB0 provided the best performance because:

 - Better feature extraction
 - Lower overfitting
 - Faster convergence
 - High validation accuracy
 - Good performance on unseen images

## Model Performance Metrics
| Model Performance Metric | Score |
| ------------------------ | ----- |
| Accuracy                 | 97%   |
| Precision                | 96%   |
| Recall                   | 97%   |
| F1-Score                 | 96%   |

## Sample Prediction Output
 - Predicted: Crocodile
   Confidence: 92%
- Predicted: Alligator
  Confidence: 95%

## Workflow
Dataset Collection
        ↓
Data Preprocessing
        ↓
Data AugWorkflow
mentation
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Prediction on Test Images
        ↓
Performance Visualization

## Data Preprocessing
The following preprocessing techniques were applied:

 - Image resizing
 - Normalization
 - Data augmentation
 - Image rotation
 - Horizontal flipping
 - Zoom augmentation
 
## Image Size
224 x 224

## 🏗️ Model Training
| Hyperparameter | Value                    |
| -------------- | ------------------------ |
| Epochs         | 20                       |
| Batch Size     | 32                       |
| Optimizer      | Adam                     |
| Learning Rate  | 0.001                    |
| Loss Function  | Categorical Crossentropy |

## Evaluation Techniques

The model was evaluated using:

 - Accuracy
 - Precision
 - Recall
 - F1-score
 - Confusion Matrix
 - Validation Loss

## Key Learnings
 - Understanding Transfer Learning
 - Image preprocessing techniques
 - CNN architecture optimization
 - Model evaluation methods
 - Deep Learning workflow implementation

## Future Improvements
 - Deploy model using Flask or Streamlit
 - Convert model into web application
 - Improve dataset size
 - Use advanced augmentation techniques
 - Try Vision Transformers (ViT)

## 📌 Conclusion

This project successfully classified Alligator and Crocodile images using Deep Learning techniques. Multiple models were tested, and EfficientNetB0 achieved the highest accuracy of 97%.

The project demonstrates:

 - Strong understanding of Computer Vision
 - Deep Learning implementation skills
 - Transfer Learning concepts
 - Model evaluation and optimization

## 🤝 Connect With Me
## 👨‍💻 Raj Shivade

Data Science Student

AI/ML Enthusiast

Aspiring Data Analyst

## 📜 License

This project is open-source and available under the MIT License.

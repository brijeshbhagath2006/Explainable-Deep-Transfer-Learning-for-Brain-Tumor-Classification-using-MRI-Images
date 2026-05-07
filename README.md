# Explainable-Deep-Transfer-Learning-for-Brain-Tumor-Classification-using-MRI-Images
Comparative Deep Learning Framework for Brain Tumor Classification using MRI Images

🧠 Brain Tumor Classification using Deep Transfer Learning Models 

Overview :-

This project presents a comparative deep learning framework for automated brain tumor classification using MRI images. Multiple state-of-the-art transfer learning architectures were implemented, fine-tuned, and evaluated to identify the most efficient model for tumor detection and classification.

The system classifies MRI images into four categories:

Glioma Tumor
Meningioma Tumor
Pituitary Tumor
Normal Brain MRI

The project also incorporates Explainable AI using Grad-CAM visualization to improve interpretability and highlight tumor-focused regions in MRI scans.

Models Implemented :- 

The following pretrained deep learning models were trained and compared:

Xception
ConvNeXtTiny
InceptionV3
EfficientNetB3
ResNet50
DenseNet201
NASNetMobile

All models were implemented using TensorFlow and Keras with transfer learning and fine-tuning techniques.

Experimental Results :- 
Model	Accuracy (%)
Xception	93.19
ConvNeXtTiny	93.00
InceptionV3	92.71
EfficientNetB3	92.06
ResNet50	91.90
DenseNet201	90.11
NASNetMobile	87.00

Among all architectures, Xception achieved the best overall performance.

Features :- 
Transfer Learning based Brain Tumor Classification
Multi-model Comparative Analysis
Accuracy & Loss Curves
ROC Curve Analysis
Confusion Matrix Visualization
Classification Reports
Tumor vs Non-Tumor Prediction Visualization
Grad-CAM Explainable AI
Fine-Tuning Optimization

Technologies Used :- 
Python
TensorFlow
Keras
NumPy
Matplotlib
Seaborn
OpenCV
Scikit-learn

📂 Dataset

Brain MRI dataset containing:

Glioma Tumor
Meningioma Tumor
Pituitary Tumor
Normal MRI images

Dataset Size:

3000+ MRI images

Evaluation Metrics

The models were evaluated using:

Accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion Matrix

Explainable AI:- 

Grad-CAM visualization was implemented to identify the image regions influencing model predictions. This improves transparency and helps understand how deep learning models detect tumor regions.

🏆 Best Performing Model

Xception achieved the highest classification accuracy:

93.19%

Future Improvements :-

Ensemble Learning
Vision Transformers (ViT)
Attention Mechanisms
Hybrid CNN-Transformer Models
Deployment using Streamlit/Flask
Real-time MRI Prediction System

Conclusion :- 

This project demonstrates the effectiveness of transfer learning models for automated brain tumor classification using MRI images. Comparative analysis showed that advanced architectures such as Xception and ConvNeXtTiny significantly improve classification performance while maintaining strong generalization capability.

The integration of Explainable AI further enhances the reliability and research value of the proposed system.

Author :-

Brijesh Kumar B T

Artificial Intelligence & Robotics Engineering

Dayananda Sagar University

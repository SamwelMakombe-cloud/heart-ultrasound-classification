# Heart Ultrasound Image Classification

**Author:** Samwel Christopher Makombe  
**Environment:** Google Colab + TensorFlow/Keras + OpenCV  

This repository contains notebooks for a heart ultrasound classification study using hybrid classical and deep learning methods, with Grad-CAM visualisations for model explainability.

---

##  Objective
To classify heart ultrasound (echocardiography) images into normal vs abnormal categories using both:
- **Classical pipeline:** HOG (Histogram of Oriented Gradients) features + SVM  
- **Deep learning pipeline:** CNN built with TensorFlow/Keras  
and to compare their accuracy, precision, recall, and visual interpretability.

---



##  Methodology
- Image preprocessing and augmentation  
- Feature extraction using **HOG**  
- SVM training and evaluation  
- CNN model construction and training  
- Grad-CAM visualisation for model transparency  

---

##  Results
The CNN achieved higher classification accuracy than HOG+SVM, and Grad-CAM heatmaps revealed discriminative regions consistent with cardiac structures.

---

##  Citation
Makombe, S.C. (2025). *Heart Ultrasound Image Classification with Grad-CAM Explainability*. MSc Data Science, Robert Gordon University.

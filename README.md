# ♻ Garbage Classification Using CNN

This project develops a **Convolutional Neural Network (CNN)** model to classify images of garbage into predefined waste categories. By automating the identification of waste types, it aims to improve waste segregation, enhance recycling efficiency, and support sustainable waste management practices.



##  Project Overview

Automating garbage classification helps reduce human error, improves recycling rates, and speeds up sorting processes. This project presents a complete deep learning pipeline, including:
- Loading, preprocessing, and visualizing a labeled garbage image dataset.
- Designing a custom CNN architecture in TensorFlow/Keras.
- Training the model to classify waste images into categories such as organic, recyclable, or hazardous waste.
- Evaluating the model on unseen data to measure performance.
- Visualizing training metrics and predictions to interpret results.



##  Features

 **Complete End-to-End Workflow**  
 - From data loading to final model evaluation, all steps are included in the notebook.

 **Custom CNN Model**  
 - Built using multiple convolutional layers, pooling, dropout for regularization, and fully connected layers.

 **Data Augmentation Support**  
 - Optional augmentation (rotation, flip, etc.) can improve the model’s generalization.

 **Evaluation & Metrics**  
 - Includes accuracy, confusion matrix, and per-class performance analysis.

 **Visualizations**  
 - Training/validation loss and accuracy plots, plus sample predictions with actual vs. predicted labels.



##  Files Included

- `GarbageClassification.ipynb`: Jupyter Notebook containing the entire implementation, including model creation, training, evaluation, and result visualization.
- `TrashType_Image_Dataset/`: Folder containing your organized garbage image dataset.  
  *(This folder is essential to train and evaluate the model. See the Dataset section below.)*
- `README.md`: Documentation with setup instructions, explanations, and usage details.



##  How to Run the Notebook

1. **Clone the repository**
   ```bash
   git clone https://github.com/hemanth-t11/GarbageClassification.git
   cd GarbageClassification

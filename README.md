# lung_xray_classification

# COVID-19 Chest X-Ray Classification

## Project Overview  
This repository contains code and documentation for a deep learning project focused on classifying chest X-ray images into four categories:  
1. COVID-19 Positive Cases  
2. Normal Lungs  
3. Lung Opacity (Non-COVID Lung Infection)  
4. Viral Pneumonia  

The goal is to enhance diagnostic accuracy and support healthcare resource optimization during medical crises like the COVID-19 pandemic.

## Repository Contents  
- **`COVID_19_Detection-Efficientnetb1.ipynb`**  
  Jupyter Notebook implemented the EfficientNetB1 model, which achieved the highest classification accuracy in this project.  

- **`COVID_19_Radiography_Resnet50.ipynb`**  
  Jupyter Notebook uses the ResNet50 architecture to classify X-ray images.  

- **`COVID_19_Radiography_VGG16.ipynb`**  
  Jupyter Notebook implementing the VGG16 model for image classification.  

- **`Lung X-ray Classification Report.docx`**  
  A comprehensive report detailing the methodology, dataset, preprocessing steps, model performance, and evaluation metrics.  

- **`README.md`**  
  Documentation provides an overview of the project, dataset, and instructions for usage.

## Dataset  
The dataset contains chest X-ray images for four classes:  
- **COVID-19 Positive Cases**: 3,616 images  
- **Normal Lungs**: 10,192 images  
- **Lung Opacity (Non-COVID Lung Infection)**: 6,012 images  
- **Viral Pneumonia**: 1,345 images  

### Sources  
- COVID-19 images: Public datasets and research papers.  
- Normal, Lung Opacity, and Viral Pneumonia images: RSNA and Kaggle datasets.  

**Note**: Refer to the full dataset README in the report or code files for more details about the dataset.

## Models Implemented  
### 1. **EfficientNetB1**  
- Test Accuracy: 95.61%  
- Best-performing model with minimal misclassifications and efficient training.

### 2. **ResNet50**  
- Test Accuracy: 87.8%  
- Strong generalization capabilities and consistent precision across categories.

### 3. **VGG16**  
- Test Accuracy: 64.5%  
- Limited performance, showing room for improvement. 

## References  
1. M.E.H. Chowdhury et al., “Can AI help screen Viral and COVID-19 pneumonia?” IEEE Access, Vol. 8, 2020.  
2. Rahman, T. et al., "Exploring the Effect of Image Enhancement Techniques on COVID-19 Detection using Chest X-ray Images," arXiv preprint, 2020.  

## Future Directions  
- Enhance model performance with additional data and hyperparameter tuning.  
- Incorporate additional imaging techniques for better feature extraction.  
- Optimize models for real-time clinical use.


# 🧠 Brain Tumor Classification using Deep Learning

### [Colab file link](https://colab.research.google.com/#fileId=https%3A//storage.googleapis.com/kaggle-colab-exported-notebooks/brain-tumor-666fb826-697f-4651-8dc8-186249a6eabb.ipynb%3FX-Goog-Algorithm%3DGOOG4-RSA-SHA256%26X-Goog-Credential%3Dgcp-kaggle-com%2540kaggle-161607.iam.gserviceaccount.com/20240804/auto/storage/goog4_request%26X-Goog-Date%3D20240804T164731Z%26X-Goog-Expires%3D259200%26X-Goog-SignedHeaders%3Dhost%26X-Goog-Signature%3D3208645d9de365c56bdd687c66edca8b99b555a4791bd06cf2d2c7e61e5a932d051a79f082074565476aeba3a51058844ee502d378481a6df7025014347c09da415312c52b58e75393c33a0473a51e09dc49ea4cd7c6dda9a4d548de49572eebdb50c6efbd1af79b69f0f9c20c1eb6abb825cd3ddd0c6d1a05471e7873dd27cb73815b5e03f13ee6bba85879884ff9bc96cb4eb8e958b0ad8af985ad6046149c2bd337bfeb1d05c1bed90caa6250a6dbc6db31d2a96865710f85b1ff407e107c496fc4bbd8610635145de0b00ff7f8182c3095238a948bfbb9e6b1c604f66086efa4e56ce8edc4bc6fec8fbc9953e53bcd83ee4de68a8852c6b9626a6e10053f)

## Overview
This project aims to classify brain tumors using deep learning techniques, specifically leveraging the EfficientNet2 model for feature extraction from MRI images. The goal is to improve the accuracy and efficiency of brain tumor diagnosis and assist radiologists in making precise treatment plans.

## 👨‍🔬 Authors
- **Lekh Kumar Shisodiya**  
  MCA, School of Information Technology & Engineering, VIT  
  [lekh.shisodiya2022@vitstudent.ac.in](mailto:lekh.shisodiya2022@vitstudent.ac.in)
- **Dr. R.K Nadesh**  
  Professor, School of Information Technology & Engineering, VIT  
  [rknadesh@vit.ac.in](mailto:rknadesh@vit.ac.in)
- **Anek Chauhan**  
  MCA, School of Information Technology & Engineering, VIT  
  [anek.chauhan2022@vitstudent.ac.in](mailto:anek.chauhan2022@vitstudent.ac.in)
- **Vishnu Kallil**  
  MCA, School of Information Technology & Engineering, VIT  
  [vishnu.kallil2022@vitstudent.ac.in](mailto:vishnu.kallil2022@vitstudent.ac.in)

## 📝 Abstract
Brain tumor classification is crucial for precise diagnosis and treatment planning. This project presents a novel approach using deep learning and transfer learning with the EfficientNet2 model to classify brain tumors from MRI images. Our method achieves an impressive accuracy of 97%, outperforming previous approaches by eliminating the need for manual feature engineering.

## 🔑 Keywords
- Transfer Learning
- EfficientNet2
- Brain Tumor Classification
- Deep Learning
- MRI Images

## 🏥 Introduction
Brain tumors, caused by abnormal brain cell development, require accurate detection and classification for effective diagnosis and treatment planning. Traditional methods involve manual segmentation and feature extraction, which are time-consuming and prone to errors. This project leverages deep learning algorithms, particularly CNNs, to automate and improve the accuracy of brain tumor classification.

## 📊 Dataset
The dataset used in this study, obtained from Kaggle, consists of 3,064 MRI scans of brain tumors with labels for tumor types, including:
- Glioma
- Meningioma
- Pituitary Tumor
- Normal

## 🔍 Methodology
1. **Data Preprocessing**
   - Handling null values
   - Data augmentation using techniques like SMOTE
   - #####  SMOTE (Synthetic Minority Over-sampling Technique) is a technique used in machine learning to address class imbalance in datasets. When you have a dataset where one class (typically the minority class) is underrepresented compared to other classes (typically the majority class), it can lead to biased model performance.
- SMOTE works by generating synthetic examples of the minority class to balance the dataset. Here’s how it works:

- Select a Minority Class Sample: For each instance in the minority class, SMOTE identifies its k-nearest neighbors in the feature space.

- Generate Synthetic Examples: Synthetic samples are created by interpolating between the selected sample and its neighbors. This is done by taking the difference between the feature vector of the sample and its neighbor, multiplying it by a random number between 0 and 1, and then adding it to the original sample.

- Add Synthetic Examples: These synthetic samples are then added to the original dataset, increasing the number of minority class examples.

The goal of SMOTE is to improve the performance of models on imbalanced datasets by providing a more balanced distribution of classes, which helps the model learn better and make more accurate predictions.

2. **Model Deployment**
   - Training with EfficientNet2 for feature extraction
   - Classifier training to predict tumor types

## 🧪 Results
The proposed model achieves:
- **Training Accuracy**: 98.06%
- **Validation Accuracy**: 95.51%
- **Validation Loss**: 0.1758

These results indicate the model's effectiveness in accurately classifying brain tumors, with potential applications in assisting medical professionals.

## 📌 Conclusion
The EfficientNet2-based model significantly improves brain tumor classification accuracy, providing an automated and efficient solution. Future work includes validating the model on larger and more diverse datasets to further enhance its reliability and generalizability.

## 📜 References
1. Litjens G, et al. (2017). A survey on deep learning in medical image analysis. IEEE transactions on medical imaging, 36(12), 2989-3016.
2. Sorte A, et al. (2022). Brain Tumor Classification using Deep Learning. In 2022 5th International Conference on Advances in Science and Technology (ICAST).
3. Arora S, Sharma M. (2021). Deep Learning for Brain Tumor Classification from MRI Images. In 2021 Sixth International Conference on Image Information Processing (ICIIP).

(Additional references from the paper can be added as needed.)

## 📧 Contact
For any inquiries, please contact:
- **Lekh Kumar Shisodiya**: [lekh.shisodiya2022@vitstudent.ac.in](mailto:lekh.shisodiya2022@vitstudent.ac.in)
- **Anek Chauhan**: [anek.chauhan2022@vitstudent.ac.in](mailto:anek.chauhan2022@vitstudent.ac.in)
- **Vishnu Kallil**: [vishnu.kallil2022@vitstudent.ac.in](mailto:vishnu.kallil2022@vitstudent.ac.in)

---

Thank you for checking out our project! 🌟

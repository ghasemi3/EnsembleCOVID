# EnsembleCOVID
This repository implements a novel methodology for classifying CT scans as COVID or Non-COVID cases, utilizing a comprehensive pipeline that enhances diagnostic performance. The proposed approach consists of sequential steps 1- Data Pre-Processing, 2- Hyperparameter Optimization, 3- Model Fine-Tuning, 4- Feature Fusion, 5- Prediction and Evaluation


Data Pre-Processing: The methodology begins with the acquisition of CT scan datasets, specifically SARS-CoV-2 CT-Scan and COVID-CT. Various pre-processing techniques are applied to enhance image quality and standardize formats, ensuring consistency across the data.



Hyperparameter Optimization: Following pre-processing, pre-trained neural networks are leveraged for a hyperparameter search. This step aims to identify optimal configurations that will maximize the performance of the models.



Model Fine-Tuning: With the optimal hyperparameters established, fine-tuning of the models is conducted using the processed datasets. This step enhances the models' learning and adaptation to the specific characteristics of the CT images.



Feature Fusion: The fine-tuned models are combined through PCA-based feature fusion techniques, which improve the robustness and accuracy of the classification results.



Prediction and Evaluation: The final ensembled model predicts whether a given CT scan corresponds to a COVID or Non-COVID case. This multi-faceted approach aims to improve diagnostic performance, providing a reliable tool for healthcare providers.


This repository provides all necessary code, documentation, and examples to replicate the methodology. Each step is thoroughly detailed, with explanations available in the accompanying sections. This work aims to support ongoing efforts in enhancing COVID-19 diagnostics through advanced image processing and machine learning techniques.

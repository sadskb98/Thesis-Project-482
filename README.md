Detection of Alzheimer’s and Parkinson’s Disease from MRI Images using Deep Learning
Project Overview
This project aims to develop an automated system for the detection of Alzheimer’s and Parkinson’s disease from MRI images using deep learning techniques. The study utilizes a dataset comprising MRI scans from individuals with Parkinson’s and Alzheimer’s disease as well as normal controls. Various deep learning models are trained and evaluated to identify the most efficient model for accurate diagnosis.

Table of Contents
Project Overview
Dataset
Methodology
Data Augmentation
Model Selection
Performance Metrics
Results
Web Application
Future Work
Conclusion
Acknowledgements
References
Dataset
The dataset includes MRI scans from three categories:

Normal Controls
Parkinson’s Disease Patients
Alzheimer’s Disease Patients
Data augmentation techniques were applied to balance the dataset, ensuring robust training of the deep learning models.

Methodology
Data Augmentation
To address class imbalance in the dataset, various augmentation techniques were applied. This includes transformations such as rotation, flipping, and scaling.

Model Selection
Five deep learning models were selected and trained using transfer learning:

ResNet50
VGG19
InceptionV3
MobileNetV2
Xception
The pre-trained weights of these models were fine-tuned using the MRI image dataset.

Performance Metrics
The performance of each model was evaluated using the following metrics:

Accuracy
Precision
Recall
F1 Score
Hamming Loss
Cohen’s Kappa
Matthews Correlation Coefficient (MCC)
Jaccard Score
Results
The study found that the InceptionV3 model delivered the highest accuracy and resilience in distinguishing between normal, Parkinson’s, and Alzheimer’s MRI scans. Detailed performance metrics for each model are provided in the results section of the report.

Web Application
A web application was developed to facilitate the practical use of the trained model. Users can upload MRI scans and receive diagnostic predictions.

Future Work
Future improvements could include:

Expanding the dataset with more diverse MRI images.
Exploring other advanced deep learning models.
Integrating additional medical imaging techniques for comprehensive analysis.
Conclusion
The project demonstrates the potential of deep learning models, particularly InceptionV3, in providing accurate and timely diagnosis of Alzheimer’s and Parkinson’s diseases based on MRI images.

Acknowledgements
We extend our gratitude to our supervisor, Mahruba Sharmin Chowdhury, for her guidance and support throughout this project. Special thanks to Abdullah Al Noman for his essential guidance during challenging times.

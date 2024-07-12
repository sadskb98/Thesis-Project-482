<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Detection of Alzheimer’s and Parkinson’s Disease from MRI Images using Deep Learning</title>
</head>
<body>
    <h1>Detection of Alzheimer’s and Parkinson’s Disease from MRI Images using Deep Learning</h1>
    <p>This project aims to develop an automated system for the detection of Alzheimer’s and Parkinson’s disease from MRI images using deep learning techniques. The study utilizes a dataset comprising MRI scans from individuals with Parkinson’s and Alzheimer’s disease as well as normal controls. Various deep learning models are trained and evaluated to identify the most efficient model for accurate diagnosis.</p>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#project-overview">Project Overview</a></li>
        <li><a href="#dataset">Dataset</a></li>
        <li><a href="#methodology">Methodology</a></li>
        <ul>
            <li><a href="#data-augmentation">Data Augmentation</a></li>
            <li><a href="#model-selection">Model Selection</a></li>
            <li><a href="#performance-metrics">Performance Metrics</a></li>
        </ul>
        <li><a href="#results">Results</a></li>
        <li><a href="#web-application">Web Application</a></li>
        <li><a href="#future-work">Future Work</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
        <li><a href="#acknowledgements">Acknowledgements</a></li>
        <li><a href="#references">References</a></li>
    </ul>

    <h2 id="project-overview">Project Overview</h2>
    <p>This project aims to develop an automated system for the detection of Alzheimer’s and Parkinson’s disease from MRI images using deep learning techniques. The study utilizes a dataset comprising MRI scans from individuals with Parkinson’s and Alzheimer’s disease as well as normal controls. Various deep learning models are trained and evaluated to identify the most efficient model for accurate diagnosis.</p>

    <h2 id="dataset">Dataset</h2>
    <p>The dataset includes MRI scans from three categories:</p>
    <ul>
        <li>Normal Controls</li>
        <li>Parkinson’s Disease Patients</li>
        <li>Alzheimer’s Disease Patients</li>
    </ul>
    <p>Data augmentation techniques were applied to balance the dataset, ensuring robust training of the deep learning models.</p>

    <h2 id="methodology">Methodology</h2>
    <h3 id="data-augmentation">Data Augmentation</h3>
    <p>To address class imbalance in the dataset, various augmentation techniques were applied. This includes transformations such as rotation, flipping, and scaling.</p>

    <h3 id="model-selection">Model Selection</h3>
    <p>Five deep learning models were selected and trained using transfer learning:</p>
    <ul>
        <li>ResNet50</li>
        <li>VGG19</li>
        <li>InceptionV3</li>
        <li>MobileNetV2</li>
        <li>Xception</li>
    </ul>
    <p>The pre-trained weights of these models were fine-tuned using the MRI image dataset.</p>

    <h3 id="performance-metrics">Performance Metrics</h3>
    <p>The performance of each model was evaluated using the following metrics:</p>
    <ul>
        <li>Accuracy</li>
        <li>Precision</li>
        <li>Recall</li>
        <li>F1 Score</li>
        <li>Hamming Loss</li>
        <li>Cohen’s Kappa</li>
        <li>Matthews Correlation Coefficient (MCC)</li>
        <li>Jaccard Score</li>
    </ul>

    <h2 id="results">Results</h2>
    <p>The study found that the InceptionV3 model delivered the highest accuracy and resilience in distinguishing between normal, Parkinson’s, and Alzheimer’s MRI scans. Detailed performance metrics for each model are provided in the results section of the report.</p>

    <h2 id="web-application">Web Application</h2>
    <p>A web application was developed to facilitate the practical use of the trained model. Users can upload MRI scans and receive diagnostic predictions.</p>

    <h2 id="future-work">Future Work</h2>
    <p>Future improvements could include:</p>
    <ul>
        <li>Expanding the dataset with more diverse MRI images.</li>
        <li>Exploring other advanced deep learning models.</li>
        <li>Integrating additional medical imaging techniques for comprehensive analysis.</li>
    </ul>

    <h2 id="conclusion">Conclusion</h2>
    <p>The project demonstrates the potential of deep learning models, particularly InceptionV3, in providing accurate and timely diagnosis of Alzheimer’s and Parkinson’s diseases based on MRI images.</p>

</body>
</html>

# Alzheimer-Disease-Detection-Using-Ensemble-Learning

### ABSTRACT
The proposed project introduces a novel system, called Alzheimer Disease Detection System, that utilizes deep learning models to accurately detect Alzheimer's Disease. The system includes a registration-free preprocessing pipeline and employs various 3D categorization architectures, including CNN, Densenet, VGG19, and Efficient Net B7. The best-performing models are subjected to an ensemble learning strategy, which leads to high accuracy scores of 95.28% and 93.8% for differentiating between individuals with Alzheimer's Disease and mild cognitive impairment, as well as between MCI and cognitive normality, respectively. This outperforms existing research in the field and could significantly assist patients with Alzheimer's Disease.

### WHAT IS ALZHEIMER DISEASE 🤔 
Alzheimer's disease is a progressive neurodegenerative disorder that affects millions of people worldwide, especially those over the age of 65. Early detection of Alzheimer's disease is crucial for effective treatment and management of the disease.

### PROPOSED SYSTEM
We present an early diagnosis system for Alzheimer’s disease that recognizes AD, MCI, and CN using MRI images. To address the problem 
of data leakage, we demonstrated a system that uses only the first visit of each patient and ignores the others. Extensive comparative experiments were performed to study the effects of using various data types from the ADNI and the size of the dataset. We investigated different pre-processing pipelines and evaluated them using the most effective 3D classification models. Furthermore, the proposed method alleviates the ambiguity of previous studies. Regarding the AD vs. MCI and MCI vs. CN tasks, we achieved the best AUC scores using the proposed ensemble approach.

### DATASET 
[![ADNI](https://img.shields.io/badge/ADNI-Official-brightgreen)](https://adni.loni.usc.edu/data-samples/access-data/)

### SYSTEM ARCHITECTURE
![Sys Arch Updated](https://github.com/Kaushal03/Alzheimer-Disease-Detection-Using-Ensemble-Learning/assets/67416597/8b3e514e-37ae-4030-8b75-5b9c1a4e284a)

### MODEL BUILDING
####  DENSENET201 MODEL
DenseNet-201 is a deep convolutional neural network that is a part of the DenseNet family of models. DenseNet-201 has 201 layers and is similar to the DenseNet-161 and DenseNet-121 models, but it is deeper and has more parameters.DenseNet-201 uses a dense connectivity pattern, where each layer is connected to every other layer in a feedforward manner. This connectivity pattern allows 
for more efficient parameter reuse and reduces the vanishing gradient problem that can occur in very deep networks.
![image](https://github.com/Kaushal03/Alzheimer-Disease-Detection-Using-Ensemble-Learning/assets/67416597/2f53eebf-e927-49bb-be83-425270afc24e)

####  CNN MODEL
A Convolutional Neural Network (CNN) is a specialized deep learning architecture designed for processing and analyzing visual data, particularly images. CNNs employ convolutional layers to automatically extract hierarchical features from input images, enabling the network to understand spatial relationships and patterns. With the inclusion of pooling layers for dimensionality reduction and activation functions like ReLU for introducing non-linearity, CNNs can capture intricate details in images. Their effectiveness in image classification, object detection, and feature extraction has made CNNs a cornerstone in computer vision applications. Additionally, transfer learning, where pretrained CNNs are adapted for specific tasks, has further contributed to their widespread success in various domains.
![image](https://github.com/Kaushal03/Alzheimer-Disease-Detection-Using-Ensemble-Learning/assets/67416597/7d5c2b64-5622-4532-afdc-7242bb1f9411)

####  EFFICIENT NET B7 MODEL
EfficientNet B7 is a state-of-the-art convolutional neural network architecture known for its exceptional efficiency and high performance in image classification tasks. Part of the EfficientNet family, it represents the largest and most powerful variant in terms of model size and computational complexity. Developed to balance model accuracy with computational efficiency, EfficientNet B7 achieves remarkable results on image datasets while maintaining a relatively compact structure. Leveraging compound scaling, which uniformly scales network width, depth, and resolution, EfficientNet B7 strikes an optimal balance, making it a preferred choice for tasks demanding both accuracy and resource efficiency in the field of computer vision.

####  VGG19 MODEL
VGG19 is a deep convolutional neural network architecture that was developed by the Visual Geometry Group (VGG) at the University of Oxford. It is a part of the VGG family of models, which are known for their simplicity and effectiveness on image classification tasks.VGG19 has 19 layers, including 16 convolutional layers and 3 fully connected layers. It uses 3x3 convolutional filters throughout the network, which allows it to learn local features in the input image. The architecture also includes max pooling layers to reduce the spatial dimensions of the feature maps.One of the key features of VGG19 is its simplicity. The use of small convolutional filters and max pooling layers throughout the network allows the model to learn complex features from the input image without the need for complicated architectures or techniques. Additionally, the model is trained using a standard cross-entropy loss function and stochastic gradient descent (SGD) optimization.
![image](https://github.com/Kaushal03/Alzheimer-Disease-Detection-Using-Ensemble-Learning/assets/67416597/26c3685b-9a46-4032-8f02-b2d3bd7e53c2)

### Languages and Tools:
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

<h3 style="text-align: center;">Model Metrics</h3>

  <table style="border-collapse: collapse; width: 100%; text-align: center;">
    <tr style="background-color: #f2f2f2;">
      <th style="border: 1px solid #dddddd; padding: 8px;">Model</th>
      <th style="border: 1px solid #dddddd; padding: 8px;">Precision</th>
      <th style="border: 1px solid #dddddd; padding: 8px;">F1 Score</th>
      <th style="border: 1px solid #dddddd; padding: 8px;">Recall</th>
      <th style="border: 1px solid #dddddd; padding: 8px;">Accuracy</th>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; padding: 8px;">Densenet</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.292761</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.975359</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.939961</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.936623</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; padding: 8px;">CNN</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.574751</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.969785</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.925672</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.923043</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; padding: 8px;">Efficient Net B7</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.224937</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.973537</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.935543</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.931889</td>
    </tr>
    <tr>
      <td style="border: 1px solid #dddddd; padding: 8px;">VGG 19</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">2.722047</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.965684</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.915465</td>
      <td style="border: 1px solid #dddddd; padding: 8px;">0.912702</td>
    </tr>
  </table>

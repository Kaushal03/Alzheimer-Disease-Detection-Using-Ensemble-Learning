# Alzheimer-Disease-Detection-Using-Ensemble-Learning

### ABSTRACT
The proposed project introduces a novel system, called Alzheimer Disease 
Detection System, that utilizes deep learning models to accurately detect 
Alzheimer's Disease. The system includes a registration-free preprocessing 
pipeline and employs various 3D categorization architectures, including CNN, 
Densenet, VGG19, and Efficient Net B7. The best-performing models are 
subjected to an ensemble learning strategy, which leads to high accuracy scores 
of 95.28% and 93.8% for differentiating between individuals with Alzheimer's 
Disease and mild cognitive impairment, as well as between MCI and cognitive 
normality, respectively. This outperforms existing research in the field and could 
significantly assist patients with Alzheimer's Disease.

### WHAT IS ALZHEIMER DISEASE 🤔 
Alzheimer's disease is a progressive neurodegenerative disorder that affects 
millions of people worldwide, especially those over the age of 65. Early 
detection of Alzheimer's disease is crucial for effective treatment and 
management of the disease.

### PROPOSED SYSTEM
We present an early diagnosis system for Alzheimer’s disease that 
recognizes AD, MCI, and CN using MRI images. To address the problem 
of data leakage, we demonstrated a system that uses only the first visit of 
each patient and ignores the others. Extensive comparative experiments 
were performed to study the effects of using various data types from the 
ADNI and the size of the dataset. We investigated different pre-processing 
pipelines and evaluated them using the most effective 3D classification 
models. Furthermore, the proposed method alleviates the ambiguity of 
previous studies. Regarding the AD vs. MCI and MCI vs. CN tasks, we 
achieved the best AUC scores using the proposed ensemble approach.

### DATASET 
[![ADNI](https://img.shields.io/badge/ADNI-Official-brightgreen)](https://adni.loni.usc.edu/data-samples/access-data/)

### SYSTEM ARCHITECTURE
![Sys Arch Updated](https://github.com/Kaushal03/Alzheimer-Disease-Detection-Using-Ensemble-Learning/assets/67416597/8b3e514e-37ae-4030-8b75-5b9c1a4e284a)

### MODEL BUILDING
####  DENSENET201 MODEL
DenseNet-201 is a deep convolutional neural network that is a part of the DenseNet family of models. DenseNet-201 has 201 layers and is similar to the DenseNet-161 and DenseNet-121 models, but it is deeper and has more parameters.DenseNet-201 uses a dense connectivity pattern, where each layer is connected to every other layer in a feedforward manner. This connectivity pattern allows 
for more efficient parameter reuse and reduces the vanishing gradient problem that can occur in very deep networks.
![image](https://github.com/Kaushal03/Alzheimer-Disease-Detection-Using-Ensemble-Learning/assets/67416597/2f53eebf-e927-49bb-be83-425270afc24e)


### Languages and Tools:
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

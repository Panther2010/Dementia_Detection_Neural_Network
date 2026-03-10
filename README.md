# Multimodal Dementia Detection using Deep Learning

## Overview

This project focuses on **early detection of dementia using deep learning techniques** applied to multiple data modalities. The system explores different approaches to identify cognitive decline using medical imaging and speech analysis.

Three independent pipelines were developed:

* **MRI Brain Image Classification**
* **Clock Drawing Test (CDT) Image Classification**
* **Speech-based Dementia Detection**

The models were implemented using **Python and deep learning frameworks** with the aim of exploring AI applications in healthcare and neurological disease detection.

---

## Objectives

* Explore machine learning approaches for **early dementia detection**
* Compare performance across **multiple diagnostic modalities**
* Develop an experimental framework for **AI-driven neurological screening**

---

## Project Structure

```
dementia-detection/
│
├── notebooks/
│   ├── mri_dementia_model.ipynb
│   ├── cdt_resnet18_model.ipynb
│   └── speech_dementia_model.ipynb
│
├── results/
│   ├── CDT_model/
│   │   └── confusion_matrix.png
│   │
│   └── Speech_model/
│       └── accuracy_plot.png
│
├── data/
│   └── dataset_description.md
│
├── requirements.txt
└── README.md
```

---

## Models Implemented

### 1. MRI-based Dementia Detection

* Model: Pretrained ResNet-18
* Input: Brain MRI images
* Task: Multi-class dementia classification

Classes:

* NonDemented
* VeryMildDemented
* MildDemented
* ModerateDemented



### 2. Clock Drawing Test (CDT) Classification

The Clock Drawing Test is commonly used in clinical screening for cognitive impairment.

* Model: CNN / ResNet-based classifier
* Task: Detect dementia from CDT images

Evaluation metric:

* Confusion Matrix


### 3. Speech-based Dementia Detection

Speech patterns can reflect early cognitive decline.

This pipeline analyzes audio features extracted from speech recordings to classify dementia status.

Features may include:

* Spectral characteristics
* Temporal speech features
* Acoustic patterns


## Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* OpenCV
* Librosa (for speech processing)

---

## Dataset

Datasets used include dementia-related medical and cognitive assessment datasets.

Example classes used in image classification:

* NonDemented
* VeryMildDemented
* MildDemented
* ModerateDemented



Developed by: Mohit Sharma

PharmD Student | Healthcare AI | Data Analytics



## License

This project is licensed under the MIT License.


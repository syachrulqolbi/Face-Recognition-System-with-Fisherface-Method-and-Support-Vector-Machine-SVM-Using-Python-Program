# Face Recognition System with Fisherface Method and Support Vector Machine
This project is part of my Bachelor's Degree thesis and was also featured in a paper published by IEEE, though it uses a different dataset. The published paper is available at [IEEE](https://ieeexplore.ieee.org/document/9689738).

#### -- Project Status: Done

## Project Intro/Objective
The purpose of this project is to build a face recognition system using the Fisherface method for dimensionality reduction and a Support Vector Machine (SVM) for classification. This project explores effective facial image processing techniques and provides a robust machine learning model for recognizing faces from images. The system has potential applications in security, identity verification, and user authentication systems.

### Methods Used
* Image Processing
* Dimensionality Reduction (Eigen decomposition)
* Machine Learning (Support Vector Machine)
* Data Visualization

### Technologies
* Python
* OpenCV
* Matplotlib
* Numpy
* Pandas
* MTCNN
* Patool

## Project Description
This project focuses on processing face images from the **Labeled Faces in the Wild (LFW)** dataset. The system applies the following steps:
1. **Face Detection and Cropping**: Utilizes `MTCNN` to detect and crop faces.
2. **Preprocessing**: Converts images to grayscale and resizes them to a uniform size.
3. **Dimensionality Reduction**: Computes Fisherfaces through Eigen decomposition for feature extraction.
4. **Classification**: Implements a Support Vector Machine (SVM) to classify faces into categories based on labels.
5. **Visualization**: Displays the mean face image, eigenfaces, and reconstructed images from the reduced feature space.

### Challenges:
- Handling images with undetected faces during preprocessing.
- Optimizing the Fisherface method for large datasets.
- Achieving high classification accuracy with SVM.

## Needs of this project
- Data processing and cleaning experts.
- Machine learning model tuning.
- Advanced visualization techniques for reconstructed faces.
- Writeup/reporting for documentation and results.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept in the **Labeled Faces in the Wild Home Focused** directory. Download the dataset from [LFW](http://vis-www.cs.umass.edu/lfw/) if not already included.
3. Data processing/transformation scripts are being kept in the main directory.

### Setup Instructions
Follow the steps below to set up the environment:
1. Install the required Python packages:
   ```bash
   pip install opencv-python-headless numpy matplotlib pandas mtcnn patool
2. Run the Python notebook to execute the system:

### Featured Notebooks/Analysis/Deliverables
Data Preprocessing, Prediction, and Visualization Notebook

## Contributing DSWG Members

**Team Leads : [Syachrul Qolbi Nur Septi](https://github.com/syachrulqolbi)**

#### Other Members:
[Nurul Gusriani](https://scholar.google.com/citations?user=dVeLr_IAAAAJ)
[Iin Irianingsih](https://scholar.google.co.id/citations?user=Qp_esq8AAAAJ)
[Herlina Napitupulu](https://scholar.google.co.id/citations?user=8YbKgv8AAAAJ)
[Intan Nurma Yulita](https://scholar.google.com/citations?user=AFopUdQAAAAJ)

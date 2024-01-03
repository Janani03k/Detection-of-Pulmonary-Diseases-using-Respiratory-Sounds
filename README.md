# Pulmonary Disease Classification Using Respiratory Sounds

## Project Overview

This project aims to develop an 8-class classification system for pulmonary diseases using machine learning and digital stethoscopes. The focus is on leveraging the ICBHI 2017 Dataset to train deep neural networks like ResNet50, VGG16, and EfficientNet-B0 for classifying respiratory sounds. The goal is to enhance the speed and accuracy of pulmonary disease diagnosis, ultimately improving patient outcomes and reducing the burden on healthcare systems.

## Abstract

Pulmonary diseases, such as asthma and COPD, affect millions globally, influenced by factors like infections, smoking, and air pollution. Traditional pulmonary auscultation with a stethoscope is safe and cost-effective but has limitations in accuracy and speed. This project explores the use of digital stethoscopes and machine learning to enhance diagnostic methods. Using data preprocessing techniques like audio slicing and feature extraction with Short-Time Fourier Transform and Wavelet Spectrogram, the audio files are converted into spectrogram images. These images are then processed using pre-trained deep neural networks to classify respiratory sounds and identify different pulmonary diseases.

## Table of Contents

**Introduction**
   - **Overview**: This research project provides an innovative solution to classify 8 classes of pulmonary diseases using breathing sounds. 
   - **Problem Statement**: Higher accuracy has not been achieved in multi-class classification using breathing sounds, we aim to improve the accuracy using data preprocessing (audio splitting, normalization, noise reduction), feature extraction (mel-spectrogram images), and neural networks (VGG16, ResNet50, EfficientNet).
   - **Respiratory Disease**: Diseases related to the lungs are classified as pulmonary diseases.
   - **Respiratory Disease Classification**: Our project classifies Pneumonia, COPD, Asthma, LRTI, URTI, Bronchiectasis, Bronchiolitis, and Healthy.

**Proposed Work**
   - **Audio Preprocessing**: Raw data has been preprocessed using audio splitting, noise reduction, and normalization to reduce the file size which contains relevant data only, and to improve the data quality.
   - **Feature Extraction**: The preprocessed data undergoes feature extraction to produce mel-spectrogram images for model training.
   - **Model Training**: Binary and 8-class classification has been performed in three models: EfficientNet, VGG16, and ResNet50 where EfficientNet proved to show a higher accuracy for the 8-class classification.

## System Requirements

### Hardware Requirements
- RAM: 8GB
- Processor: Intel Core i3 or above
- Microphone: 50 Hz - 15 kHz

### Software Requirements
- Operating Systems: Microsoft Windows 7 or later, MacOS Monterey
- Python Version: 3.8.3
- Development Tools: Anaconda Framework, Microsoft Visual Studio Code
- Python Libraries: TensorFlow, Librosa, Pandas, NumPy

## Dataset

The project uses the ICBHI 2017 Dataset, consisting of 920 audio samples from 126 subjects, all annotated by medical experts. This dataset is notable for being one of the largest publicly available databases in the field of respiratory diseases.

Dataset used: https://www.kaggle.com/datasets/vbookshelf/respiratory-sound-database/data?select=Respiratory_Sound_Database

The Respiratory Sound Database was created by two research teams in Portugal and Greece. It includes 920 annotated recordings of varying lengths - 10s to 90s. These recordings were taken from 126 patients. There are a total of 5.5 hours of recordings containing 6898 respiratory cycles - 1864 contain crackles, 886 contain wheezes and 506 contain both crackles and wheezes. The data includes clean respiratory sounds and noisy recordings that simulate real-life conditions. The patients span all age groups - children, adults, and the elderly.

Dataset after preprocessing of audio files: https://drive.google.com/drive/folders/1Q5--BE_YX_0q_6gUxAq2rzvaPZbIfk_A?usp=drive_link

Dataset after feature extraction into image files: https://drive.google.com/drive/folders/1IGe3RFX85Xe7lNm7oRVhLdUFE2a327WY?usp=sharing

Link to this research project in IEEE: https://ieeexplore.ieee.org/document/10235057

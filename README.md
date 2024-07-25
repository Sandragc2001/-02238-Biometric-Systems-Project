# -02238-Biometric-Systems-Project
Evaluating the Performance of Facial Recognition  Algorithms on Morphed Human Faces (DTU  02238-Biometric Systems Final Project)

This repositoyy contains the necessary scripts and database to run the project 02238-s233162-2024 on Evaluating the Performance of Facial Recognition Algorithms on Morphed Human Faces. The project consists of three main scripts:


- Dataset segmentation script: This script is used to segment the original Facial Recognition Vendor Test (FRVT) dataset into a smaller subset that specifically includes data from 50 individuals. This process ensures that the dataset used in the experiments is a manageable and accurate cross section of the larger dataset.

- FaceRecognitionCode script: This contains the core functionality for running seven different experiments. Each experiment involves processing images through different face recognition models. For each image recognized as the same by the models (despite any morphing), a new entry is added to a CSV file. This file logs the results of each experiment, tracking which images are identified as matches by each model.

- Evaluation script: This script is critical for analyzing the results of the experiments. It tests three specific hypotheses laid out in the associated research paper. The script processes the data, performs statistical tests, and generates several graphs to visually represent the results. These graphs are then stored in the Plots folder for easy access and review.

Each script plays a different role in the project, contributing to a comprehensive evaluation of how different face recognition algorithms perform when challenged with images of morphed faces.

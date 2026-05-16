# IPMC_dynamics

Experimental investigation and machine learning-based modeling of Ionic Polymer-Metal Composite (IPMC) actuation dynamics under varying voltage amplitudes and environmental conditions.

---

# Overview

This repository contains the complete experimental workflow, dataset, visualization scripts, machine learning models, and research report developed during the internship project at:

🔗 [Technology Innovation Hub (TIH), IIT Guwahati](https://www.iitg.ac.in/tih/)

The project focuses on:

* Experimental deformation analysis of IPMC soft actuators
* ESP32-CAM-based image acquisition
* Computer vision-based deformation extraction
* Data visualization and transient response analysis
* Deep neural network-based deformation prediction

---

# Repository Contents

## Dataset

### [`ipmc_frames.csv`](./ipmc_frames.csv)

Experimental dataset containing:

* Voltage amplitudes
* Environmental conditions
* Time-domain actuation data
* Phase information
* Deformation angles
* Temporal deformation dynamics

Dataset includes:

* 840 observations
* 42 experimental runs
* WATER, AIR, and ACETONE (1%) environments

---

## Machine Learning Notebook

### [`NN_ipmc.ipynb`](./NN_ipmc.ipynb)

Contains:

* Data preprocessing
* Feature engineering
* Neural network development
* Model training and evaluation
* Prediction analysis
* Residual analysis
* Neural network visualization

Libraries used:

* TensorFlow
* Scikit-learn
* NumPy
* Pandas

---

## Data Visualization Notebook

### [`data_visualisation.ipynb`](./data_visualisation.ipynb)

Contains scripts for generating:

* Stimulus response plots
* Relaxation response plots
* Peak deformation analysis
* Heatmaps
* Phase-space trajectories
* Correlation analysis
* Residual plots
* Predicted vs actual plots

Visualization libraries used:

* Matplotlib
* Seaborn
* OpenCV

---

## Images Directory

### [`images/`](./images)

Contains:

* Experimental setup images
* Processing pipeline figures
* Generated plots
* Neural network architecture figures
* Machine learning result visualizations

---

## Research Report

### [`Winter Internship TIH report.pdf`](./Winter%20Internship%20TIH%20report.pdf)

Complete technical report including:

* Experimental methodology
* IPMC working principle
* Image-processing framework
* Dataset generation
* Machine learning framework
* Results and discussion
* Model evaluation
* Conclusions and future scope

---

# Experimental Setup

The experimental framework consists of:

* Cantilever-configured IPMC actuator
* AC voltage excitation system
* ESP32-CAM imaging module
* Real-time deformation acquisition setup

Experiments were conducted under:

* WATER
* AIR
* ACETONE (1%)

Voltage range:

* 2.1 V to 4.9 V

---

# Machine Learning Model

Deep Neural Network Regression Architecture:

* Input Layer
* Dense Layer (128 neurons, ReLU)
* Dropout Layer (20%)
* Dense Layer (64 neurons, ReLU)
* Dropout Layer (20%)
* Dense Layer (32 neurons, ReLU)
* Output Regression Layer

---

# Model Performance

| Metric   | Value |
| -------- | ----- |
| MAE      | 2.73° |
| RMSE     | 4.08° |
| R² Score | 0.959 |

---

# Technologies Used

* Python
* TensorFlow
* Scikit-learn
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Google Colab
* ESP32-CAM

---

# Research Areas

* Soft Robotics
* Electroactive Polymers
* Smart Materials
* Embedded Systems
* Computer Vision
* Deep Learning
* Predictive Modeling

---

# Author

### Sandeep Roy

Department of Mechanical Engineering
Jorhat Engineering College

🔗 GitHub: [@sandeeproyy](https://github.com/sandeeproyy)
🔗 LinkedIn: [Sandeep Roy](https://www.linkedin.com/)

---

# Acknowledgement

Special thanks to:

🔗 [Technology Innovation Hub (TIH), IIT Guwahati](https://www.iitg.ac.in/tih/)
Dr. Ankur Gupta

for their guidance and support throughout the project.

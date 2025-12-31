License: Custom – Academic Use Only

# GNSS TEC Modelling and Visualization System

This repository contains the implementation code for the project  
**“Modelling of Total Electron Content (TEC) for the Indian Equatorial Ionospheric Anomaly (EIA) Region using GNSS Receiver Data.”**

The project was carried out during my **GNSS Summer Internship** at  
**IIT Tirupati Navavishkar I-Hub Foundation (IITTNiF)**.

This repository is published **only for academic demonstration and portfolio purposes**.

---

## Project Overview

Total Electron Content (TEC) is a critical ionospheric parameter that directly affects the accuracy of Global Navigation Satellite System (GNSS) signals.  
In low-latitude regions such as the Indian Equatorial Ionospheric Anomaly (EIA), TEC variations are highly dynamic and challenging to model.

This project focuses on building an end-to-end system that:
- Processes raw GNSS TEC data
- Handles missing and incomplete data
- Predicts TEC values using machine learning and deep learning models
- Visualizes measured and predicted TEC values through an interactive web dashboard

---

## Scope of Work

The project includes the following components:

- GNSS data preprocessing and feature engineering
- Implementation of multiple ML and DL models for TEC prediction
- A FastAPI-based backend for data processing and prediction
- A React-based web dashboard for visualization and analysis

To comply with institutional data policies, **raw GNSS data and trained model files are not included** in this repository.

---

## Technology Stack

### Backend
- Python
- FastAPI
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras

### Prediction Models
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost
- Multilayer Perceptron (MLP)
- LSTM
- BiLSTM

### Frontend
- React
- Plotly
- JavaScript
- CSS

---
### Data and Model Rights

- All GNSS datasets used in this project are confidential and are the property of IIT Tirupati Navavishkar I-Hub Foundation (IITTNiF).

- Trained machine learning and deep learning models generated using institutional data are not shared.

- This repository contains only the implementation code and system structure.

### Usage Restrictions and License

Copyright © 2025
IIT Tirupati Navavishkar I-Hub Foundation (IITTNiF) and Tharani P S

All rights reserved.

This repository is made public strictly for academic, educational, and portfolio reference.

The following conditions apply:

- Redistribution, commercial usage, deployment, or sublicensing of this software or its derivatives is not permitted without prior written consent from IIT Tirupati Navavishkar I-Hub Foundation.

- The source code may be viewed or referenced only for academic learning purposes, with proper attribution.

- Any attempt to recreate, infer, or use the original datasets or trained models without authorization is prohibited.

- The software is provided “as is”, without any warranty.

### Acknowledgment

I sincerely thank IIT Tirupati Navavishkar I-Hub Foundation (IITTNiF) and the
GNSS Technology Development Cell for providing the opportunity and resources to carry out this work.

I am especially grateful to
Dr. K. G. Sujanth Narayan
Technology Manager – GNSS
for his guidance and continuous support throughout the project.

### Author

Tharani P S
GNSS Summer Intern
IIT Tirupati Navavishkar I-Hub Foundation

## Repository Structure

```text
.
├── backend/
│   ├── DB/                 # Database logic (no actual data)
│   ├── Image/              # Static images
│   ├── Model_training/     # Training scripts (datasets excluded)
│   ├── data_predicted/     # Output folder structure (empty)
│   ├── dst.py              # DST index processing
│   ├── f10.7.py            # Solar flux (F10.7) processing
│   ├── graph_api.py        # Visualization API
│   └── raw_upload_api.py   # Raw GNSS data ingestion
│
├── frontend/
│   ├── assets/
│   ├── components/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   ├── index.css
│   └── theme.js
│
└── README.md

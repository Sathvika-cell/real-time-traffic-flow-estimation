# Traffic Flow Estimation Using Google API

This project focuses on estimating real-time traffic flow using stream speed data from the Google Distance Matrix API and vehicle detection using YOLOv8.

## Features
- Real-time traffic speed extraction using Google API
- Vehicle detection and classification using YOLOv8
- Traffic flow prediction using ML models:
  - KNN
  - Random Forest
  - Gradient Boosting
  - SVR
- Hybrid density modelling using classical traffic flow theories

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- YOLOv8
- Google Distance Matrix API

## Results
- KNN achieved the best overall prediction accuracy
- Random Forest performed well for high-variability traffic flows
- Hybrid density model provided interpretable traffic estimation

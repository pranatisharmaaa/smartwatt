# ⚡ SmartWatt – Cost-Aware Smart Energy Monitoring & ML Forecasting System

SmartWatt is an IoT-powered energy intelligence platform that combines real-time appliance monitoring, machine learning forecasting, and anomaly detection to help users optimize electricity consumption and reduce operational costs.

**IEEE Research Submission (Under Review)**

---

## Problem Statement

Traditional electricity meters provide aggregate energy consumption data but lack appliance-level visibility, predictive insights, and intelligent recommendations.

SmartWatt addresses this challenge by collecting real-time power consumption data from individual appliances and applying machine learning techniques to forecast future usage patterns, detect anomalies, and estimate costs proactively.

---

## Key Features

* Real-time appliance-level energy monitoring
* Live telemetry collection using ESP32
* Energy consumption forecasting using Machine Learning
* Cost prediction and usage trend analysis
* Automated anomaly detection and alert generation
* REST API architecture for scalable deployment
* Interactive dashboard for monitoring and analytics
* Sub-2 second prediction latency

---

## System Architecture

ESP32 Sensors
↓
Telemetry Collection Layer
↓
Data Processing Pipeline
↓
Machine Learning Models
↓
Forecasting & Anomaly Detection Engine
↓
FastAPI Backend
↓
Analytics Dashboard

---

## Technology Stack

### Hardware

* ESP32

### Backend

* Python
* FastAPI

### Machine Learning

* Scikit-Learn
* NumPy
* Pandas

### Models

* Linear Regression
* Random Forest Regression

### Data Processing

* Feature Engineering
* Time-Series Analysis
* Data Cleaning & Validation

### Frontend

* React

---

## Machine Learning Pipeline

1. Real-time energy data collection
2. Data preprocessing and cleaning
3. Feature extraction
4. Model training and evaluation
5. Forecast generation
6. Cost estimation
7. Anomaly detection
8. Alert generation

---

## Results

* Collected 1,000+ telemetry records daily
* Achieved R² Score of 0.87
* Reduced RMSE by 22%
* Enabled appliance-level monitoring and forecasting
* Delivered sub-2 second prediction latency

---

## Research Contribution

This work has been submitted as an IEEE research paper and focuses on integrating IoT infrastructure with machine learning-based forecasting techniques for intelligent energy management systems.

---

## Team

* Pranati Sharma
* Research Supervisor

Team Size: 2 Members + Academic Supervisor

---

## Future Enhancements

* Deep Learning-based forecasting
* Reinforcement Learning for energy optimization
* Smart scheduling recommendations
* Solar integration analytics
* Mobile application support

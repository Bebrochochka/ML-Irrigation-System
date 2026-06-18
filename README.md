# Smart Irrigation System — Machine Learning to TinyML Project

## About this project

This project explores the idea of building a smart irrigation system using machine learning and deploying it on an embedded device (ESP32-S3).

The main goal is to train a model that can later be converted to TinyML and run directly on low-power hardware for real-time decision making.

---

## Idea

The system is designed to:

* collect sensor data (soil moisture, temperature, etc.)
* use a trained ML model to predict irrigation needs
* deploy the model on an ESP32-S3 microcontroller using TinyML
* make real-time watering decisions without cloud dependency

---

## Machine Learning part

I first built and tested a machine learning model using Python and a Kaggle dataset.

The model is trained to predict irrigation decisions based on environmental and sensor-like features.

This step focuses on:

* data preprocessing
* model training and evaluation
* experimenting with prediction quality

---

## Next step (TinyML deployment)

The next phase of this project is to convert the trained model into a lightweight format and deploy it using TinyML so it can run directly on:

* ESP32-S3 (N16R8)
* low-power embedded environment
* real-time sensor system

---

## Goal

The final goal is to create a fully working edge AI system that can:

* run without internet
* make fast local decisions
* optimize water usage in real time

---

## What I learned

* how to train ML models on real datasets
* how ML systems can be prepared for embedded deployment
* basics of TinyML pipeline thinking
* how to connect AI models with real hardware systems

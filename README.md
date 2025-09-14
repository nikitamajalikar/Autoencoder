Autoencoder for Software Quality Metrics

This project implements an autoencoder-based machine learning pipeline to estimate key software quality attributes such as complexity and reliability. By combining complexity metrics (e.g., Lines of Code, Cyclomatic Complexity) with deep neural networks (DNNs), the model learns compressed feature representations of software requirements and predicts outcomes like maintainability, time between failures (TBF), and reliability.

The approach demonstrates how dimensionality reduction with autoencoders can improve prediction accuracy for high-dimensional, nonlinear software engineering data — offering a scalable method for software quality assessment and early risk detection.

**Tech Stack:** Python · TensorFlow · scikit-learn · NumPy · Pandas · Matplotlib

Key Features

Dimensionality Reduction with Autoencoders → Compresses high-dimensional software requirement data into meaningful latent representations.

Complexity Prediction → Estimates key software complexity metrics such as Lines of Code (LOC) and Cyclomatic Complexity.

Consequence Prediction → Predicts software behavior attributes including Number of Calls, Time Between Failures (TBF), and Reliability.

Deep Neural Network Models → Uses custom DNNs for bijective mapping (complexity) and regression tasks (consequences).

Comparative Evaluation → Benchmarked against baseline models (direct DNN approaches) to demonstrate improved accuracy.

Visualization & Metrics → Provides MSE/MAE-based evaluation along with plots to compare original vs. predicted values.

Tech Stack → Python · TensorFlow · scikit-learn · NumPy · Pandas · Matplotlib

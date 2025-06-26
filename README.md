# Robot-Task-Classification

## 📌 Overview
This project focuses on classifying robotic manipulation tasks — including picking and placing objects — using sensor-derived features from robot episodes. We compare two modeling approaches: Lasso-regularized logistic regression and logistic regression with stepwise AIC.

## 📂 Dataset
- Source: PhysicalAI Robotics Manipulation dataset (NVIDIA)
- Tasks: `pick`, `place_bench`, `place_cabinet`
- Features: Sensor dimension means (e.g., `dim_5_mean`, `dim_6_mean`), `gripper_motion_time`, `episode_length`, and more.

## 🧠 Methods
- Logistic Regression
- Lasso (L1 Regularization)
- Stepwise AIC Selection
- Sensitivity Analysis with Different Random Seeds

## 📈 Results
- Both models showed consistent accuracy across 80 random train-test splits.
- Slight variations observed, but overall stable performance.

## 🛠️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/Danarev/Robot-Task-Classification.git
   cd Robot-Task-Classification

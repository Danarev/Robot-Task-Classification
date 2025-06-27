# Robot-Task-Classification

## 📌 Overview
As part of a Statistical Learning Theory course, we were asked to create a project demonstrating different machine learning models studied during the course.  
This project focuses on classifying robotic manipulation tasks — including picking and placing objects — using sensor-derived features from robot episodes.

The dataset contains three types of robot tasks:
- **pick** – the robot picks an object from a bench
- **place_bench** – the robot places an object on a bench
- **place_cabinet** – the robot places an object inside a cabinet

The objective is to classify the task that the robot is performing using predictive machine learning models.

The data used to construct features is a 34-dimensional **Action** vector, which corresponds to velocity command signals transmitted to various parts of the robot.

---

## 📂 Dataset
- **Source:** [PhysicalAI Robotics Manipulation dataset (NVIDIA)](https://huggingface.co/datasets/nvidia/PhysicalAI-Robotics-Manipulation-Objects)
- **Raw Data:** The data used for this project is in the Zip file added to this repo
- **Tasks:** `pick`, `place_bench`, `place_cabinet`
- **Features:** Sensor dimension means (e.g., `dim_5_mean`, `dim_6_mean`), `gripper_motion_time`, `episode_length`, and more.

---

## 🧠 Methods
- Logistic Regression
- Lasso (L1 Regularization)
- Stepwise AIC Selection
- Decision Trees – Gradient Boosting
- Decision Trees – Random Forest
- Support Vector Machines
- Sensitivity analysis with different random seeds

---

## 🛠️ Project Structure
The repository contains two Jupyter Notebooks:
1. **Feature Engineering**
2. **Model Training and Results**

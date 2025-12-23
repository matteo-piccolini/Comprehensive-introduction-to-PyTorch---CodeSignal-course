# Machine Learning with PyTorch - Personal Course Lab

This repository contains my personal elaboration and implementation of the concepts taught in the **Machine Learning with PyTorch** course.

---

## ⚖️ Legal Disclaimer & Credits
**Please Read:** This repository is not an original course creation. 

* **Source:** All educational content, logic structure, and base exercises are derived from the course provided by [CodeSignal](https://codesignal.com/). 
* **Copyright:** All rights to the original curriculum, instructional text, and methodology are **strictly reserved by CodeSignal**. 
* **Purpose:** This material is published for **educational and portfolio purposes only**. It represents my personal progress and "lab work" as I moved through their curriculum. 
* **Use Case:** This code should not be used for commercial purposes or in any way that violates the Terms of Service of the original content provider.

---

## 📌 Project Overview
The core of this project is the study of Deep Learning fundamentals using **PyTorch**. It covers the transition from basic tensor operations to building, regularizing, and evaluating neural networks.

### Key Topics Covered:
* **Tensor Fundamentals**: Creation, manipulation, and operations (reshaping, flattening).
* **Data Pipeline**: Implementing `DataLoader` and `TensorDataset` for efficient batch processing.
* **Architecture**: Building models using `nn.Module` and `nn.Sequential`.
* **Optimization**: Practical use of `Adam` optimizer and loss functions like `CrossEntropyLoss`.
* **Regularization Techniques**: Implementation of **L2 Regularization (Weight Decay)** and **Dropout** to prevent overfitting.
* **Evaluation**: Measuring model performance via Accuracy and Loss metrics.

---

## 📂 File Structure
* `Machine Learning - CodeSignal course.ipynb`: The main notebook containing theory, code implementation, and training loops.
* `data_preprocessing.py`: A helper script for loading, splitting, and scaling the **UCI Wine Dataset** using `scikit-learn` and converting it into PyTorch tensors.

---

## 🛠️ Setup and Requirements
To run the code in this repository, you will need Python 3.x and the following libraries:

```bash
pip install torch numpy scikit-learn

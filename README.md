# Credit Card Fraud Detection using Scikit-learn and Snap ML

## Overview

This project demonstrates how to build a Credit Card Fraud Detection system using two popular machine learning libraries, scikit-learn and Snap ML. Credit card fraud detection is a critical task for financial institutions to identify potentially fraudulent transactions and protect customers.

## Project Highlights

- Implementation of a Credit Card Fraud Detection system.
- Comparison of two different machine learning libraries: scikit-learn and Snap ML.
- Handling class imbalance in the dataset.
- Evaluating model performance using ROC-AUC and hinge loss metrics.
- Training time comparison between the two libraries.

## Libraries Used

- [scikit-learn](https://scikit-learn.org/): A popular machine learning library for Python.
- [Snap ML](https://www.ibm.com/cloud/machine-learning): A high-performance machine learning library developed by IBM that accelerates training on CPUs and GPUs.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Subhana-2001/Credit-Card-Fraud-Detection-Using-Scikit-Learn-and-Snap-ML.git
    ```

2. **Install Dependencies:**

    Navigate to the project directory and install the required dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```

3. **Data Preparation:**

    - Prepare your credit card transaction dataset (e.g., CSV file).
    - Ensure that you have features (X) and labels (y) properly defined.

4. **Training Models:**

    - Open Jupyter Notebook or your preferred Python IDE.
    - Run the provided scripts for training the scikit-learn and Snap ML models.
    
5. **Evaluate Model Performance:**

    - Evaluate model performance using ROC-AUC and hinge loss metrics.
    
6. **Compare Training Times:**

    - Compare training times between scikit-learn and Snap ML models.

## Model Performance

### ROC-AUC

The ROC-AUC score measures the ability of the model to distinguish between genuine and fraudulent transactions. A higher ROC-AUC score indicates better model performance.

- [Scikit-Learn] ROC-AUC score: 0.966
- [Snap ML] ROC-AUC score: 0.966

### Hinge Loss

The hinge loss metric evaluates the model's classification accuracy. It should be the same for both scikit-learn and Snap ML models.

- [Scikit-Learn] Hinge loss: 0.228
- [Snap ML] Hinge loss: 0.228

## Model Training Speedup

Training times are essential for model deployment. Snap ML aims to accelerate training times.

- [Support Vector Machine] Snap ML vs. Scikit-Learn training speedup: 13.81x

## Conclusion

This project showcases the use of scikit-learn and Snap ML for Credit Card Fraud Detection. It compares model performance and training speed, providing insights into the benefits of using Snap ML for efficient training of machine learning models.

For more details and implementation, please refer to the project files.


Happy coding and fraud detection!






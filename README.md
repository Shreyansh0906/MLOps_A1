# MLOps Assignment 1: House Price Prediction

This project implements a complete machine learning workflow to predict house prices using the Boston Housing dataset. It includes two models: Decision Tree Regressor and Kernel Ridge Regressor. The workflow is automated using GitHub Actions.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/MLOps_A1.git](https://github.com/YourUsername/MLOps_A1.git)
    cd MLOps_A1
    ```

2.  **Create and activate the Conda environment:**
    ```bash
    conda create --name mlops_env python=3.9 -y
    conda activate mlops_env
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the training scripts:**
    ```bash
    python train.py
    python train2.py
    ```
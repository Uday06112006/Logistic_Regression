# Logistic Regression from Scratch 

A pure Python implementation of the Logistic Regression algorithm using **NumPy** and **Matplotlib**. This project demonstrates the fundamental mechanics of Gradient Descent and Binary Cross-Entropy without relying on high-level ML libraries like Scikit-Learn.

##  Core Concepts Implemented
* **Sigmoid Activation:** Mapping real-valued numbers to probabilities $[0, 1]$.
* **Log Loss (Binary Cross-Entropy):** The objective function used to measure model performance.
* **Gradient Descent:** The optimization algorithm used to update weights and bias.
* **Vectorization:** Efficient matrix operations using NumPy.

##  Performance & Visualization
The model includes a **Cost History** tracker. This allows us to visualize the "Learning Curve," ensuring the Gradient Descent is converging correctly.

### Results
- **Dataset:** Synthetic binary classification (1,000 samples).
- **Accuracy:** ~95% (depending on hyper-parameters).
- **Optimization:** 1,000 iterations with a learning rate of 0.1.

##  How to Run
You can run this project directly in your browser via Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

##  Project Structure
* `Logistic_Regression_From_Scratch.ipynb`: The complete implementation and walkthrough.
* `requirements.txt`: List of dependencies (NumPy, Matplotlib, Scikit-Learn for data generation).

# Quantum Neural Network (QNN) Project

This project implements a Quantum Neural Network (QNN) using IBM's Qiskit framework, combined with classical machine learning and deep learning techniques. The QNN leverages quantum computing principles to perform computations, integrated with classical data preprocessing and modeling libraries like TensorFlow and Keras.

## Features
- **Quantum Circuit Design**: Utilizes Qiskit for creating and simulating quantum circuits.
- **Classical ML Integration**: Incorporates TensorFlow and Keras for classical machine learning tasks.
- **Hybrid Quantum-Classical Workflow**: Demonstrates the potential of hybrid models combining quantum and classical computing.
- **Visualization and Analysis**: Includes tools for visualizing quantum circuits and evaluating models.

## Prerequisites
Ensure the following tools are installed before running the project:
- Python (>=3.7)
- Qiskit
- TensorFlow
- Keras
- Pennylane
- Scikit-learn
- NumPy
- OpenCV
- Pandas
- Seaborn
- TQDM

To install the required libraries, use the following command:
```bash
pip install qiskit tensorflow keras pennylane scikit-learn numpy opencv-python pandas seaborn tqdm

## IBM Quantum Setup

1. Sign up for an IBM Quantum account at [IBM Quantum](https://quantum-computing.ibm.com/).
2. Obtain your API token from the IBM Quantum dashboard.
3. Configure your local environment by running:
   ```python
   from qiskit import IBMQ
   IBMQ.save_account('YOUR_API_TOKEN')



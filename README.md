# Linear and Polynomial Models for Regression

This project develops linear and polynomial regression models from the ground up to represent the relationship between stellar mass and luminosity. The work is organized into two stages: the first focuses on simple linear regression using a single input (stellar mass), while the second expands to polynomial regression with multiple inputs (mass and temperature). Gradient descent is implemented in both vectorized and non-vectorized forms, 
the cost landscape is visualized, and the performance of different models and learning rates is analyzed and compared.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Prerequisites

Python 3.3 or higher

Jupyter Notebook or JupyterLab

Python libraries:

numpy

matplotlib

mpl_toolkits (included with matplotlib)

### Installing

Steps to set up the development environment:

1. Clone or download the project repository

2. Install the necessary dependencies:

3. Open the notebooks in Jupyter:
4. Run the notebooks in order:
01_part1_linreg_1feature.ipynb: Simple linear regression
02_part2_polyreg.ipynb: Polynomial regression with multiple features

## Running the notebooks

After installation, execute the notebooks in order:

**Notebook 1: Linear Regression (Single Feature)**
```bash
jupyter notebook 01_part1_linreg_1feature.ipynb
```

Run all cells sequentially to:
Visualize the M vs L relationship

Compute cost surface and gradients

Train the model using gradient descent

Analyze convergence behavior

Evaluate model performance

**Notebook 2: Polynomial Regression (Multiple Features)**
```bash
jupyter notebook 02_part2_polyreg.ipynb
```

Run all cells to:
Compare 3 different feature combinations

Analyze interaction term importance

Perform inference on new data

Visualize predicted vs actual results

---
## AWS SageMaker Execution Evidence

### Deployment Process

The notebooks were successfully deployed and executed on **AWS SageMaker Studio** following these steps:

1. Access SageMaker Studio via AWS Console
2. Create Notebook Instance with ml.t3.medium configuration
3. Upload Notebooks (`01_part1_linreg_1feature.ipynb` and `02_part2_polyreg.ipynb`)
4. Execute All Cells in sequential order
5. Verify Outputs including plots and numerical results

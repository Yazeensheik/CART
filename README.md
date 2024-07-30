# CART
 Classification and Regression Trees is a decision tree algorithm for classification and regression.
# CART Algorithm and Mammal Dataset

This repository contains an implementation of the CART (Classification and Regression Trees) algorithm and a sample mammal dataset for demonstration purposes.

## Files in the Repository

- **CART.ipynb**: A Jupyter notebook implementing the CART algorithm.
- **Mammal_Dataset.csv**: A sample dataset used to demonstrate the CART algorithm.
- **C4.5.ipynb**: A Jupyter notebook implementing the C4.5 decision tree algorithm for comparison.

## CART Algorithm

The CART algorithm is used for constructing decision trees for classification and regression tasks. It splits the data into subsets based on the feature that results in the maximum information gain.

### Features of CART

- Handles both categorical and continuous features.
- Generates binary trees.
- Can be used for both classification and regression tasks.
- Prunes trees to avoid overfitting.

## Mammal Dataset

The `Mammal_Dataset.csv` dataset contains information about various mammal species and their characteristics. It includes the following columns:

- **Species**: The name of the mammal species.
- **Body_Weight**: The body weight of the species (in kg).
- **Brain_Weight**: The brain weight of the species (in g).
- **Other_Feature**: Other relevant features (can be modified as needed).
- **Class**: The target variable indicating the class/category of the species.

## Usage

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/your-username/CART-Mammal-Dataset.git
    ```

2. Open the `CART.ipynb` notebook in Jupyter Notebook or JupyterLab to explore the implementation of the CART algorithm.
3. Open the `C4.5.ipynb` notebook to explore the implementation of the C4.5 algorithm.
4. Use the `Mammal_Dataset.csv` dataset within the notebooks or in your own analysis.

## Getting Started

To run the notebooks, you will need to have Python and Jupyter Notebook installed. You can install the required packages using the following commands:

```sh
pip install jupyter
pip install pandas
pip install numpy
pip install scikit-learn

# Data Cleaning Techniques with Pandas

## Overview

This repository contains an advanced data cleaning system implemented using **Pandas** in Python. The system demonstrates how to preprocess and clean datasets effectively, preparing them for machine learning tasks. The techniques include handling missing values, removing duplicates, dealing with outliers, feature engineering, and encoding categorical variables.

## Project Structure

The repository includes the following file:

- `pandas_data_cleaning.ipynb`: A Jupyter notebook that demonstrates various data cleaning techniques using a sample dataset (Titanic dataset in this case). The notebook covers:
  - Handling missing data
  - Removing duplicates
  - Outlier detection and removal
  - Feature engineering (creating new columns)
  - Encoding categorical features
  - Feature scaling
  
## Prerequisites

Before running the code, ensure you have the following libraries installed:

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for feature scaling)

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Getting Started

1. **Clone the repository** to your local machine:

```bash
git clone https://github.com/ahmdmohamedd/data-cleaning-techniques.git
```

2. **Open the Jupyter notebook** `pandas_data_cleaning.ipynb` in a Jupyter environment (e.g., JupyterLab or Jupyter Notebook).
3. **Run the notebook step by step** to follow the data cleaning process.

## Functionality

The notebook implements the following tasks:

- **Loading the dataset**: The Titanic dataset is used as an example, loaded using Seaborn's built-in dataset function.
- **Missing Data Handling**: Missing values are filled with appropriate values (median, mode, etc.).
- **Duplicates Removal**: Identifies and removes any duplicate rows.
- **Outlier Detection**: Identifies and removes outliers using the Interquartile Range (IQR) method.
- **Feature Engineering**: New features like `family_size` and `age_group` are created to enhance the dataset.
- **Categorical Encoding**: Categorical columns like `sex` and `embarked` are encoded for machine learning tasks.
- **Feature Scaling**: Numerical features are scaled using standardization to improve model performance.

## Usage

1. Clone the repository.
2. Open the `pandas_data_cleaning.ipynb` notebook in Jupyter.
3. Follow the steps within the notebook to clean and preprocess your own dataset by replacing the Titanic dataset with your desired dataset.

## Example Output

After running the notebook, you will have a cleaned dataset with:
- Missing values handled
- Duplicates removed
- Outliers filtered
- New features created
- Categorical variables encoded

The final cleaned dataset can be exported to a CSV file for further analysis or machine learning tasks.

## Contributions

Contributions are welcome! If you have suggestions or improvements for the code, feel free to open an issue or submit a pull request.

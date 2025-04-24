# Data Preprocessing Tools

This project demonstrates essential data preprocessing techniques in Python, including handling missing data, encoding categorical variables, splitting datasets into training and test sets, and feature scaling.

## Overview

The project covers the following preprocessing steps:

1. **Handling Missing Data**: Replacing missing values with the mean of the corresponding column.
2. **Encoding Categorical Data**:
   - Encoding independent variables using `OneHotEncoder`.
   - Encoding dependent variables using `LabelEncoder`.
3. **Splitting the Dataset**: Dividing the dataset into training and test sets using an 80-20 split.
4. **Feature Scaling**: Standardizing features by removing the mean and scaling to unit variance.

## Libraries Used

- `numpy`
- `pandas`
- `scikit-learn`

## Dataset

The project uses a sample dataset (`Data.csv`). The dataset should contain:
- Independent variables in all columns except the last.
- The dependent variable in the last column.

## Getting Started

### Prerequisites

- Python 3.x
- `numpy`
- `pandas`
- `scikit-learn`

Install required libraries using pip:

```bash
pip install numpy pandas scikit-learn
```

## License
This project is licensed under the [MIT License](https://opensource.org/license/MIT).
 

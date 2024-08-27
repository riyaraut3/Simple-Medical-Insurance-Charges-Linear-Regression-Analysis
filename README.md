# Simple Medical Insurance Charges Linear Regression Analysis

## Project Overview

This project is a linear regression analysis of a dataset containing medical insurance charges. The aim is to predict the insurance charges based on various factors like age, gender, BMI, number of children, smoking status, and region.

## Dataset

- **Filename**: `medical insurance charges.csv`
- **Columns**:
  - `age`: Age of the individual
  - `gender`: Gender (0: Female, 1: Male)
  - `bmi`: Body Mass Index
  - `children`: Number of children/dependents covered by the insurance
  - `smoker`: Smoking status (0: Non-smoker, 1: Smoker)
  - `region`: Residential region (encoded as integers)
  - `charges`: Medical insurance charges

## Project Structure

- **`LR_coded1.ipynb`**: The Jupyter notebook containing the entire analysis, including data loading, preprocessing, model training, evaluation, and model saving using `pickle`.
- **`medical insurance charges.csv`**: The dataset used for the analysis.

## Dependencies

To run this notebook, you need the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `pickle` (standard Python library, no installation required)

You can install the external dependencies using the following command:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn

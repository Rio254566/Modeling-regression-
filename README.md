# Modeling-regression-
# Housing Price Prediction — Linear Regression Project

## Project Structure
├── housing.csv
└── modeling.ipynb

## Objective

This project aims to:
- Understand and implement **Simple and Multiple Linear Regression**
- Identify and handle **outliers** using **boxplots** and the **IQR method**
- Evaluate model performance using standard regression metrics

## Dataset

The dataset (`housing.csv`) contains various features of houses including:

- `area`: Square footage of the house  
- `bedrooms`: Number of bedrooms  
- `bathrooms`: Number of bathrooms  
- `stories`: Number of floors  
- `price`: Selling price of the house (target variable)

## Notebook Overview (`modeling.ipynb`)

The notebook includes the following steps:

1. **Data Loading** and initial inspection  
2. **Boxplot Visualization** for outlier detection  
3. **Outlier Removal** using IQR method  
4. **Simple Linear Regression** using individual features  
5. **Multiple Linear Regression** using all features  
6. **Model Evaluation** using:
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  
7. **Regression Line Plots** for simple models

## Results

- Multiple Linear Regression performed better than simple models
- Outlier removal improved the reliability of predictions
- Coefficients were interpretable and aligned with domain knowledge

## Getting Started

1. Open `modeling.ipynb` in Jupyter Notebook or any IDE that supports `.ipynb`  
2. Run each cell to:
   - Load and clean the data  
   - Visualize and remove outliers  
   - Build and evaluate regression models

## 📎 Requirements

Make sure the following Python libraries are installed:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`

You can install them with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

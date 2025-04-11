# Diamond Price Prediction

## Overview

This project focuses on predicting diamond prices using linear regression. The model is trained on a dataset containing various attributes of diamonds to estimate their market value. It includes preprocessing, visualization, model training, and evaluation steps to build an effective regression model.

## Dataset

The dataset used in this project contains characteristics of diamonds such as carat, cut, color, clarity, depth, and dimensions, which are used as features to predict the price. It is a widely used dataset in regression tasks and is available on platforms like Kaggle.

## Installation

Ensure you have Python installed, along with the necessary libraries. You can install the required dependencies using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diamond-linear-regression.git
   cd diamond-linear-regression
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook diamond-linear-regression.ipynb
   ```
3. Execute the notebook cells sequentially to perform data loading, EDA, preprocessing, model training, and evaluation.

## Features Implemented

- Exploratory Data Analysis (EDA) with visualizations using Seaborn and Matplotlib
- Feature selection and preprocessing
- One-hot encoding for categorical features
- Model training using `LinearRegression` from Scikit-learn
- Model performance evaluation using R² score and Mean Squared Error

## Results

The model demonstrates a good fit for predicting diamond prices based on the provided features, with a solid R² score indicating how well the model generalizes to unseen data.

## Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request with enhancements or additional modeling techniques.

## Contact

For any questions or suggestions, please feel free to reach out via GitHub Issues or contact me at [marawan.abdellah0@gmail.com](mailto:marawan.abdellah0@gmail.com).

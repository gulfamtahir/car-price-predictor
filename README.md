# Car Price Predictor

This project implements a linear regression model to predict car prices using a dataset from Kaggle. The data has been thoroughly cleaned, and various machine learning strategies such as OneHotEncoder, ColumnTransformer, and Pipelines were used to preprocess the data. After experimenting with multiple models, linear regression was chosen as it achieved an R² score of 85% with the current dataset.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Models Used](#models-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to predict the prices of cars using machine learning models, with a focus on linear regression. The dataset, available in the `CSV file/` folder, was cleaned and transformed to make it suitable for modeling. Various preprocessing techniques were applied before training the linear regression model.

## Features
- **Data Cleaning:** Conversion of raw data into useful data by handling missing values and irrelevant information.
- **Feature Engineering:** Applied OneHotEncoder, ColumnTransformer, and Pipelines to preprocess categorical and numerical data.
- **Model Selection:** After testing several models, linear regression was chosen for its performance with an 85% R² score on this dataset.

## Dataset
The dataset used for this project is provided in the `CSV file/` folder. It contains various attributes of cars such as model, brand, year, mileage, and other features that affect the car price.

## Usage

### Running the Predictor
To run the car price predictor, use the following script:

```bash
python app.py
```

Once the script is executed, it will load the dataset, preprocess the data, train the model, and output the predicted prices.

## Data Preprocessing
The following steps were taken to prepare the data for modeling:
- **Data Cleaning:** Removal of missing or irrelevant data.
- **Feature Transformation:** Used `OneHotEncoder` to encode categorical variables and `ColumnTransformer` to manage both numerical and categorical columns.
- **Pipeline Strategy:** Implemented a pipeline to streamline the preprocessing and modeling workflow.

## Models Used

- **Linear Regression:** Chosen as the final model for this project, achieving an R² score of 85% on the dataset.
- **Other Models:** Tried other machine learning models, but they did not perform as well as linear regression due to the small size of the dataset.

## Contributing
Contributions are welcome! If you have suggestions for improvements or find issues, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Home Data - Machine Learning Project

## Overview
This project aims to build a machine learning model to predict house prices based on various features. The dataset is sourced from the Kaggle Home Data for ML Course competition.

## Table of Contents
- Project Structure
- Installation
- Usage
- Data
- Modeling
- Evaluation
- Contributing
- License

## Project Structure
```
home-data-ml-project/
│
├── data/
│   ├── raw/                # Store raw data files
│   └── processed/          # Store processed data files
│
├── notebooks/              # Jupyter notebooks for EDA and modeling
│   ├── 01_EDA_and_PreProcessing.ipynb        # Exploratory Data Analysis and Preprocessing steps notebook
│   ├── 02_Modeling_and_Evaluation.ipynb      # Modeling, Evaluation and Conclusion notebook
│   ├── 03_SubmissionFile_Generator.ipynb     # Generation of the file to be loaded on the competition
│
├── requirements.txt        # List of dependencies
├── README.md               # Project overview and instructions
└── .gitignore              # Files and directories to ignore
```

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the necessary libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage
Clone the repository:
```bash
git clone https://github.com/Bladys0710/home-data-ml-project.git
cd home-data-ml-project
```
Open the Jupyter notebooks in your preferred environment (e.g., Google Colab, Jupyter Notebook). Follow the notebooks in order:
- **01_EDA_and_PreProcessing.ipynb**: combines exploratory data analysis and data cleaning/preparation.
- **02_Modeling_and_Evaluation.ipynb**: includes building and training machine learning models, as well as model evaluation and conclusions.

## Data
The dataset used in this project is the Home Data for ML Course dataset from Kaggle. It contains information about various features of houses, including square footage, number of bedrooms, and sale prices.

## Modeling
This project explores various machine learning algorithms, with a focus on those that have shown better results for house price prediction:
- **XGBoost**: Known for its performance and speed, often yielding high accuracy in regression tasks.
- **Random Forests**: Effective for handling non-linear relationships and interactions between features.
- **HistGradientBoosting**: A gradient boosting model that is efficient and can handle large datasets well.
- **Linear Regression**: A baseline model that provides a good starting point for understanding relationships in the data.

## Evaluation
Model performance is evaluated using metrics such as:
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R-squared**

Visualizations such as residual plots and feature importance charts are also included to assess model performance.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or suggestions are welcome!

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE License.
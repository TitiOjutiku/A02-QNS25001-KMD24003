# A02-QNS25001-KMD24003
AO2 Assignment OPIM5512 Group 4

What the project does: Thise project trains a regression model using the California Housing dataset. We will be splitting data into train/test sets, training an MLPRegressor with early_stopping=True and at least one custom hyperparameter, and generating and saving "Actual vs. Predicted" plots for both training and testing data.


## How to Run This Project

This project analyzes the California Housing dataset using machine learning regression models.

### Option 1: Run in Google Colab

1. Open `California_housing_improved_version.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. The notebook loads and prepares the California Housing dataset.
4. Run the modeling sections to train and evaluate the models.
5. Review the model evaluation metrics and plots.
6. Generated plots are saved in the `plots/` directory.

### Option 2: Clone the Repository

Clone the repository using:

git clone https://github.com/TitiOjutiku/A02-QNS25001-KMD24003.git

Then navigate to the project directory:

cd A02-QNS25001-KMD24003

### Project Outputs

The project includes:
- Data preparation and exploratory analysis
- Machine learning model training and evaluation
- Baseline MLP model
- MLP hyperparameter tuning
- Baseline vs. tuned MLP performance comparison
- Test-set evaluation using regression metrics
- Visualization of model results
- Saved plots in the `plots/` directory

### Model Improvement

Hyperparameter tuning improved the MLP test R² from approximately **0.5343** to **0.6216**.

## Collaborators

*   **Shruti Patel** netID-QNS25001
*   **Titilola Ojutiku** netID-KMD24003



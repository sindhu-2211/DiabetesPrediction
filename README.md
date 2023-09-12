# DiabetesPredictor

## Overview

This project aims to predict the risk of diabetes in individuals based on various health-related attributes. The model is built using a Random Forest classifier and utilizes a dataset containing information about age, gender, and symptoms related to diabetes.

## Dataset

The dataset used in this project is available in the file "diabetes_data_upload.csv." It includes the following attributes:

- Age 
- Gender (1. Male, 0. Female)
- Polyuria (1. Yes, 0. No)
- Polydipsia (1. Yes, 0. No)
- Sudden weight loss (1. Yes, 0. No)
- Weakness (1. Yes, 0. No)
- Polyphagia (1. Yes, 0. No)
- Genital thrush (1. Yes, 0. No)
- Visual blurring (1. Yes, 0. No)
- Itching (1. Yes, 0. No)
- Irritability (1. Yes, 0. No)
- Delayed healing (1. Yes, 0. No)
- Partial paresis (1. Yes, 0. No)
- Muscle stiffness (1. Yes, 0. No)
- Alopecia (1. Yes, 0. No)
- Obesity (1. Yes, 0. No)
- Class (1. Positive, 0. Negative)

## Model

The predictive model utilizes a Random Forest classifier. It takes input features such as age, gender, and various symptoms to predict whether an individual is at risk of diabetes or not.

## Usage

To use the diabetes prediction model:

1. Clone this GitHub repository to your local machine.

2. Install the required libraries and dependencies by running:

pip install -r requirements.txt

3. Run the Jupyter Notebook  to load the model and provide input data for prediction.

Diabetes_model.ipynb

You will be prompted to enter values for age, gender, and various symptoms to make a prediction.

4. The model will provide a prediction, indicating whether the person is at risk of diabetes or not.

## Evaluation

The model's performance is evaluated using various classification metrics, including accuracy, precision, recall, and F1 score. Additionally, a confusion matrix is generated to visualize the model's performance.

## Data Visualization

This project includes data visualization to gain insights from the dataset, such as age distribution, gender distribution, and more. Various plots and charts are provided in the Jupyter Notebook to explore the data.

## Author
Oladri Renuka (renukareddy.oladhri@gmail.com)
Avula Jhansy (avulajhansy6@gmail.com)
Bodapatla Sindhu Priya (bsindhupriya03@gmail.com)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.






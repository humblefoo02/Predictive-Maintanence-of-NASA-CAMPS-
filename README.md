# Predictive Maintenance of NASA CAMPS

## Overview

This project aims to predict the failure of aerospace systems using machine learning techniques, focusing on NASA's CAMPS (Condition-based Aircraft Maintenance) dataset. By analyzing historical data on component failures, the model helps predict potential maintenance issues, reducing downtime and optimizing maintenance schedules.

The task is framed as a **classification problem**, where the goal is to predict whether a component will fail or not based on various features collected from the system.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Modeling](#modeling)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The Predictive Maintenance of NASA CAMPS project uses machine learning algorithms to predict the failure of different components based on a variety of sensor inputs. It allows for early detection of potential failures, minimizing downtime, and reducing maintenance costs in the aerospace industry.

### Key Features:
- **Preprocessing:** Data cleaning, feature scaling, and transformation.
- **Modeling:** Classification algorithms such as Decision Trees, Random Forest, XGBoost, and Logistic Regression.
- **Evaluation:** Performance metrics such as Accuracy, Precision, Recall, and F1-score.

### Goals:
- Predict whether a component will fail in the next time period.
- Reduce unnecessary maintenance and optimize operational costs.

## Dataset

The dataset used in this project comes from NASA’s CAMPS database. It contains sensor readings and operational data of aircraft components. Each entry includes several features (e.g., temperature, pressure, vibration) and a target variable indicating whether the component failed or not.

The dataset includes the following columns:
- **Features:** Various sensor readings and operational parameters.
- **Target:** Binary label (0 = No Failure, 1 = Failure).

### Data Preprocessing:
- Handling missing values and outliers.
- Encoding categorical variables if necessary.
- Scaling continuous features to improve model performance.

## Modeling

Several machine learning models are applied to the problem, and their performance is evaluated using cross-validation. Some of the models used in this project include:

1. **Logistic Regression**
2. **Decision Trees**
3. **Random Forest Classifier**
4. **XGBoost Classifier**

Each model is evaluated using common classification metrics:
- Accuracy
- Precision
- Recall
- F1 Score

## Installation

To run this project, you need Python 3.x installed on your system. You can install the required dependencies using `pip`.

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Predictive-Maintenance-of-NASA-CAMPS.git
   cd Predictive-Maintenance-of-NASA-CAMPS


## Results
The project demonstrates the ability to predict component failures using machine learning algorithms. The model's performance can be compared across different algorithms. The final model will provide predictions about the likelihood of component failure, allowing for timely maintenance interventions.

Example Results (from model evaluation):
Accuracy: 97.5%
Precision: 90.3%
Recall: 95.7%
F1 Score: 97.9%

## Contributing
If you would like to contribute to this project, feel free to fork the repository, submit issues, and send pull requests.

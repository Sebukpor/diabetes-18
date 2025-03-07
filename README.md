# Diabetes Prediction Model

## Overview

Diabetes is the fourth leading cause of death worldwide and one of the most common endocrine disorders. Type 2 diabetes not only claims thousands of lives each year but also imposes significant costs on societies through expensive treatments, surgeries, and long-term management of complications. Early diagnosis and prediction of diabetes can therefore have a major impact on public health by enabling timely interventions and reducing healthcare expenses.

This repository contains a machine learning model built using TensorFlow.js that predicts diabetes risk based on clinical data. The model is trained on a high-quality dataset collected according to World Health Organization (WHO) standards.

## Dataset Description

This dataset is derived from a Chinese research study conducted in 2016. It comprises 1304 samples of patients who tested positive for diabetes, with participant ages ranging from 21 to 99 years old. The data collection adhered to WHO indicators and standards, ensuring a reliable source for building accurate diabetes diagnosis models.

## Features

The dataset includes the following 18 features:

- **Age**: Patient age in years
- **Gender**: Patient gender
- **BMI**: Body Mass Index
- **SBP**: Systolic Blood Pressure
- **DBP**: Diastolic Blood Pressure
- **FPG**: Fasting Plasma Glucose
- **FFPG**: Final Fasting Plasma Glucose
- **Cholesterol**: Cholesterol level
- **Triglyceride**: Triglyceride level
- **HDL**: High-Density Lipoprotein
- **LDL**: Low-Density Lipoprotein
- **ALT**: Alanine Aminotransferase
- **BUN**: Blood Urea Nitrogen
- **CCR**: Creatinine Clearance
- **Smoking Status**:  
  - 1: Current Smoker  
  - 2: Ever Smoker  
  - 3: Never Smoker
- **Drinking Status**:  
  - 1: Current Drinker  
  - 2: Ever Drinker  
  - 3: Never Drinker
- **Family History of Diabetes**:  
  - 1: Yes  
  - 0: No

## Data Source

The dataset is available on [Kaggle](https://www.kaggle.com/datasets/pkdarabi/diabetes-dataset-with-18-features) and serves as a reliable resource for training and testing diabetes prediction models.

## Model Overview

The web application included in this repository uses TensorFlow.js to normalize input clinical data, predict diabetes risk, and display the result along with a confidence score. The confidence is visually represented using a progress bar, which adapts its color and width based on the prediction outcome.

## Getting Started

### Prerequisites

- A modern web browser
- (Optional) Node.js if you plan to run a local development server

## Usage

1. Enter the required clinical data in the provided form.
2. Click the **"Assess Diabetes Risk"** button.
3. The model will process the data, output a prediction, and display a confidence score with a visual indicator.

## Contributing

Contributions are welcome! If you have ideas for improvements or have found any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the researchers who collected and published the dataset.
- Appreciation to the TensorFlow.js team and the open-source community for their contributions.

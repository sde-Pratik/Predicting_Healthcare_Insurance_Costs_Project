
# Predicting Healthcare Insurance Costs

## Overview
This project predicts healthcare insurance costs based on features such as age, sex, BMI, smoking habits, and location. The goal is to help estimate insurance premiums for new policyholders.

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/healthcare-insurance-cost-prediction.git
   cd healthcare-insurance-cost-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Data
The dataset includes the following columns:
- **Age**, **Sex**, **BMI**, **Children**, **Smoker**, **Region**, **Charges** (target variable)

## Usage

Run the prediction script with:
```bash
python predict_cost.py --input data/sample_data.csv
```

## Model
The model used in this project is **Linear Regression** to predict insurance charges based on the input features.

## License
This project is licensed under the MIT License.

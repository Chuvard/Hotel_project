# Title: Predictive Reservation System

=======================================================================================

## Problem Statement

The hotel chain "Hiltonview" faces losses due to room reservation cancellations. These cancellations result in financial setbacks, including purchasing supplies for guests' arrival or the inability to find alternative clients in time. To address this issue, a system is needed to predict reservation abandonment and prompt clients to pay a deposit if the model indicates a likely cancellation. The deposit is 80% of the room rate for one day and the one-time cleaning cost, debited if the reservation is eventually canceled.

## Features of the Project

- Prediction of reservation abandonment
- Deposit requests for at-risk reservations
- Dynamic deposit calculation (80% of room rate + one-time cleaning cost)
- Seasonal pricing adjustments (20% increase in spring and autumn, 40% increase in summer)
- Profit estimation without implementing deposits
- Machine learning model for reservation prediction
- Customer profiling based on exploratory data analysis
- Recommendations for business improvement

> [!IMPORTANT]
> ## Technologies

- Python
- Jupyter Notebooks
- Pandas, NumPy, Scikit-learn for data manipulation and machine learning
- Matplotlib, Seaborn for Data Visualization
- Data files: `/data/hotel_train.csv`, `/data/hotel_test.csv`

## Business Metrics and Other Data

The main business metric is the hotel's profit, calculated as the difference between room costs for all nights and service costs (room preparation and guest stay). The hotel has various room categories with different rates and cleaning frequencies. Seasonal coefficients influence pricing, with 20% and 40% increases in spring/autumn and summer, respectively. The system's development budget is 20,000 euros, aiming to cover costs during the test period.

## Licenses

This project is licensed under the [MIT License](LICENSE). You are free to modify and distribute the code for commercial or non-commercial purposes.

## Collaborators

This project was developed by @Chuvard and @Jaguar838



## Execution Instructions

### Step 1: Open the data files
- Training Data: `/data/hotel_train.csv`
- Testing Data: `/data/hotel_test.csv`

### Step 2: Pre-processing and EDA
- Review and correct data if needed.
- Conduct exploratory data analysis, describing features, omissions, and outliers.

### Step 3: Compute a Business Metric
- Estimate hotel profit without implementing deposits.

### Step 4: Developing an ML Model
- Train and evaluate different models through cross-validation.
- Choose the best model and test it on the provided sample.
- Select the training metric.
- Estimate the yearly profit with the selected model.

### Step 5: Identify Signs of an "Untrustworthy" Customer
- Describe characteristics of a customer prone to cancellation based on exploratory data analysis.

### Step 6: Write a General Conclusion
- Describe the model providing the most business benefit and offer recommendations based on the findings.

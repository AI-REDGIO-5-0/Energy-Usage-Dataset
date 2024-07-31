### Energy Usage Dataset
# Overview
This dataset was developed as part of the AI REDGIO 5.0 project, focusing on optimizing energy management through predictive modeling.

# Dataset Details
- Number of Entries: 3,466
- Number of Features: 17
- Data Includes: Power input/output, wattage predictions battery status, and more.
- Format: Numerical data with timestamps

# Model Information
- Model Type: Decision Tree Classifier
- Library Used: scikit-learn

# Usage Instructions
## Prerequisites
Ensure Python 3.9+ is installed along with the necessary libraries:

```bash
pip install scikit-learn pandas
```
# Loading the Data
```bash
import pandas as pd
data = pd.read_csv('Output_data.csv')
```
# Making Predictions
```bash
import joblib

model = joblib.load('model.joblib')
predictions = model.predict(data)
```
# License
This project is open source.

# Contact and Resources
- Contributors: PBN, am-LAB Digital Innovation Hub
- Contact Emails: gyula.gal@pbn.hu, martin.dan@pbn.hu

For more details, visit the [Energy Usage Dataset page](https://wiki.ai-redgio50.s5labs.eu/index.php?title=Energy_Usage_Dataset).
# Machine Failure Prediction

## Overview
This project focuses on analyzing and predicting machine failures using sensor data. The workflow includes data visualization, data refining, and predictive analysis to identify patterns and potential failures in machines.

## Features
- **Data Refinement:** Cleaning and preprocessing sensor data.
- **Data Visualization:** Graphical representation of key insights using Power BI.
- **Predictive Analysis:** Machine learning models for failure prediction.

## Dataset
The dataset contains sensor readings such as:
- Footfall
- Temperature Mode
- Air Quality Index (AQI)
- Ultrasonic Sensor (USS)
- Current Sensor (CS)
- Volatile Organic Compounds (VOC)
- Rotational Position (RP)
- Input Pressure (IP)
- Temperature
- Binary Failure Indicator

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/machine-failure-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd machine-failure-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Load the dataset:
   ```python
   import pandas as pd
   df = pd.read_csv('data/machine_failure_data.csv')
   ```
2. Run data visualization using Power BI:
   - Open Power BI and load the dataset.
   - Create reports and dashboards to visualize key sensor data trends.
3. Train the predictive model:
   ```python
   from model import train_model
   model = train_model(df)
   ```

## Technologies Used
- Python
- Pandas
- Matplotlib/Seaborn
- Scikit-learn
- Power BI
- Jupyter Notebook

## Results & Insights
- Identified significant sensor variables contributing to failures.
- Visualized correlations between sensor readings and failure rates using Power BI.
- Built a predictive model to forecast potential machine failures.

## Contributors
- P Sai Nikhitha reddy

## License
This project is licensed under the MIT License.

# Data_science_project
Data Science Machine Failure Prediction 

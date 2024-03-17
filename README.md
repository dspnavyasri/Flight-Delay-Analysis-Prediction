# Flight Delay Analysis & Prediction

## Overview
This project aims to analyze and predict flight delays using U.S. flight data from 2009–2018. The dataset contains extensive information on flights such as airline, flight date, departure delay, arrival delay, etc.

## Data Source
- Data has been collected from Kaggle.
- Dataset link: [Airline Delay and Cancellation Data 2009-2018](https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018).
- The dataset contains CSV files for each year, totaling approximately 7GB with around 6 million rows per year.

## Tools Used
- Apache Spark for big data processing.
- Python for data manipulation, analysis, and modeling.
- Libraries used include PySpark, Matplotlib, Seaborn.

## Data Processing
- Loaded the CSV files into Spark RDD.
- Converted RDD to DataFrame and performed data type casting.
- Registered DataFrame as a temporary view for querying.

## Analysis
- Conducted analysis on delay causes using Spark SQL.
- Visualized delay causes as percentages of total delay time using Matplotlib and Seaborn.

## Machine Learning
- Utilized Spark MLlib for machine learning tasks.
- Preprocessed data by encoding categorical columns and assembling features.
- Built a Linear Regression model to predict departure delay.
- Evaluated model performance using RMSE and R-squared metrics.

## Usage
- Ensure you have Apache Spark installed.
- Clone the repository and download the dataset from the provided Kaggle link.
- Update the file paths accordingly in the code.
- Run the code files in a Spark environment.

## Results
- Identified major delay causes such as carrier delay, NAS delay, etc.
- Developed a predictive model with reasonable performance for departure delay.

## Future Work
- Explore more advanced machine learning models for better prediction accuracy.
- Incorporate additional features or external data sources for improved analysis and prediction.
- Optimize the code for better performance, especially for handling large datasets.

## Author
Shankara Parameshwari Navya Sri

## License
This project is licensed under the [MIT License](LICENSE).

# Earthquake Analysis and Prediction

## Overview and Problem Statement
This repository is dedicated to the analysis and prediction of earthquakes using a dataset that spans from 1990 to 2023. The primary objectives of this project are to explore the seismic activity data, gain insights, and develop predictive models to anticipate future earthquakes.

The earthquakes dataset represents a fundamental information source for scientific research, public safety, and community awareness. We are to analyze historical data and build predictive models. This dataset can significantly contribute to mitigating seismic risks and protecting people and infrastructure from the consequences of earthquakes.

## Project Objectives and Approach
The project will use Linear Regression. The model will be trained on the dataset and it's performance will be evaluated on a held-out test set. The best model will be deployed to production so that it can be used to predict future earthquakes.

- **Data Collection**: We collect and curate earthquake data from the "All the Earthquakes Dataset" on Kaggle, covering a broad temporal range.

- **Data Preprocessing**: Data cleaning and transformation are performed to prepare the dataset for analysis and modeling, including addressing missing values and outliers.

- **Exploratory Data Analysis (EDA)**: We conduct exploratory data analysis to identify patterns, trends, and correlations in the seismic activity data.

- **Predictive Modeling**: Various machine learning and statistical models are employed for earthquake prediction, taking into consideration factors such as location, depth, and historical seismic activity.

- **Evaluation**: We assess the performance of the predictive models using appropriate metrics and validation techniques.

- **Visualization**: We create informative visualizations to illustrate the findings and predictions, helping to communicate results effectively.

## Dataset
The earthquake data used in this project is sourced from the Kaggle dataset titled "All the Earthquakes Dataset." 

- You can access the dataset at the following URL:
[Earthquake Dataset on Kaggle]([insert-link-to-dataset](https://www.kaggle.com/datasets/alessandrolobello/the-ultimate-earthquake-dataset-from-1990-2023))

Please ensure that you comply with the dataset's licensing and usage terms when utilizing it for your research and analysis.

## Usage
To replicate or extend this project, follow these steps:

1. Clone this repository to your local machine: git clone https://github.com/your-username/Earthquake-Analysis-and-Prediction.git
2. Install the required dependencies, if not already installed: pip install -r requirements.txt
3. Navigate to the project directory: cd Earthquake-Analysis-and-Prediction
4. Explore the Jupyter Notebooks and Python scripts provided for data preprocessing, analysis, and predictive modeling.
5. Customize the project to suit your research goals, experiment with different models, or incorporate additional features and data sources.

## Results
We found that the mean squared error of the Linear Regression model on the test set was 0.12. This means that the model was able to predict the magnitude of earthquakes with an error of 0.12 on average.

## Further work can be done
Other input variables can be inserted into the model to increase the comolexity and overall efficiency of the model. Please feel free to experiment.

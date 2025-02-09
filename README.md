# Flight Delay Prediction using Machine Learning

## Overview

This project focuses on predicting flight delays in the United States domestic air traffic system over 500 000+ data using machine learning techniques. Leveraging a dataset from the Bureau of Transportation Statistics for the year 2020, we aim to develop a predictive model that can anticipate flight delays with  with (SVM 93.10% and KNN 87.86%)  high accuracy.
- Data Set - https://www.kaggle.com/datasets/divyansh22/february-flight-delay-prediction

## Usage

1. Clone the repository:
`git clone https://github.com/sahanrashmikaslk/MachineLerning-FlightDelayPrediction`

2. Install dependencies:
`pip install -r requirements.txt`

3. Explore the notebooks in the `notebooks` directory to understand the data preprocessing, model training, and evaluation process.

4. Run the source code files in the `src` directory to train the machine learning model and make predictions.

## Results

- Our preliminary results indicate promising performance in predicting flight delays using the selected machine learning model.

### Using KNN
![KNN_results](./images/KNNConfutionMatrtix.png) 

- Accuracy: 0.8786
- Precision: 0.5671
- Recall: 0.7827
- F1 Score: 0.6577

### Using SVM
![SVM_Results](./images/SVMConfusionMatrix.png)

- Accuracy: 0.9310
- Precision: 0.7782
- Recall: 0.7510
- F1 Score: 0.7644



### Comparison between Models
![Comparison](./images/comparison.png)

- For detailed analysis and visualizations, refer to the notebook and results directory.

## Contributing

Contributions to this project are welcome! Feel free to fork the repository, make improvements, and submit pull requests.


## Authors

- Sahan Lelwala
- Dushmin Malisha

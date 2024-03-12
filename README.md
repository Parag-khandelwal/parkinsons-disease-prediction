# Parkinson's Disease Prediction

## Overview
This project aims to predict whether an individual is affected by Parkinson's disease using machine learning techniques. The dataset used for training and testing the model is provided in a CSV format.

## Dataset
The dataset used for this project contains various biomedical voice measurements from individuals with and without Parkinson's disease. It includes multiple voice recordings and features extracted from these recordings.

### Dataset Source
The dataset used in this project is sourced from [Parkinson's Disease Classification dataset]
https://www.kaggle.com/datasets/debasisdotcom/parkinson-disease-detection

## Model
The predictive model is built using machine learning algorithms to classify individuals as either having Parkinson's disease or being healthy based on the provided dataset. Various algorithms such as Decision Trees, Random Forest, and Support Vector Machines (SVM) are explored to find the best performing model.

## Requirements
- Python (version >= 3.0)
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage
1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Download the dataset (parkinsons.csv) from the provided source or use your own dataset in a compatible format.
4. Run the Jupyter notebook or Python script to train and test the model on the dataset.
5. Evaluate the model's performance using various metrics such as accuracy, precision, recall, and F1-score.
6. Use the trained model to make predictions on new data or integrate it into other applications as needed.

## Files Included
- `parkinsons.csv`: Dataset file containing biomedical voice measurements.
- `parkinsons_prediction.ipynb`: Jupyter notebook containing the Python code for model training, testing, and evaluation.

## Acknowledgements
- Dataset source: https://www.kaggle.com/datasets/debasisdotcom/parkinson-disease-detection
  
## License
This project is licensed under the [MIT License](LICENSE).

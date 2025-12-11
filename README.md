
# KNN Iris Classifier

This project demonstrates a K-Nearest Neighbors (KNN) classifier for the Iris dataset. The application allows users to:
1. Tune the hyperparameter `k` (number of neighbors).
2. Evaluate the model's performance (accuracy and balanced accuracy).
3. Predict the iris species based on user-provided input.

## Features
- Hyperparameter tuning for KNN (`k` selection).
- Model training and evaluation.
- Console-based user input for custom predictions.
- Performance metrics: Accuracy and Balanced Accuracy.

## Requirements
Ensure you have the following installed:
- Python 3.x
- pandas
- scikit-learn

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CAU-AID-Class.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CAU-AID-Class
   ```
3. Install required libraries:
   ```bash
   pip install pandas scikit-learn
   ```
4. Ensure the `iris.csv` dataset is available in the project directory.

## Usage
1. run the script:
```
python knn_iris_classifier.py
```
2. Enter the number of neighbors (`k`) when prompted.
3. View the model's accuracy in the console.
4. Input `sepal.length` and `petal.length` to predict the species.


## Notes
- ensure the input for predictions is numeric and follows the correct format(value1, value2)
- modify the dataset loading path in the script if necessary.


## License
the project is licensed under the mit License.


## Author
Developed by sanghunchoi
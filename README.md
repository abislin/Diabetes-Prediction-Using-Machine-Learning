Diabetes Prediction

This project uses a Support Vector Machine (SVM) to predict whether a person has diabetes based on medical data. The model is trained on the PIMA Diabetes dataset.

Dataset

The dataset used for this project is the PIMA Indians Diabetes Dataset. It contains the following features:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

The target variable is Outcome, where:

0 indicates the person does not have diabetes.

1 indicates the person has diabetes.

Requirements

To run this project, you need the following dependencies:

Python 3.x

NumPy

Pandas

scikit-learn

Installation

Clone the repository:

git clone https://github.com/your_username/diabetes-prediction.git
cd diabetes-prediction

Install the required Python packages:

pip install -r requirements.txt

Place the diabetes.csv dataset in the specified project directory.

Usage

Training the Model

The script reads the diabetes dataset, preprocesses the data using StandardScaler, and trains a Support Vector Machine (SVM) with a linear kernel.

Run the script:

python diabetes_prediction.py

Input Prediction

The script allows you to test the trained model with custom input data. Examples are provided in the code:

# Example input data
input_data = (0, 137, 40, 35, 168, 43.1, 2.288, 33)

The model will output whether the person is affected by diabetes or not based on the provided input.

Outputs

Training Accuracy: Accuracy of the model on the training dataset.

Test Accuracy: Accuracy of the model on the test dataset.

Predictions: Classification results for custom input data.

Example output:

Accuracy of training data: 0.78
Accuracy of test data: 0.77
Prediction: [1]
The person is affected with diabetes.

File Structure

diabetes_prediction.py: The main script for training and testing the model.

diabetes.csv: The dataset file (ensure it is in the same directory).

README.md: Documentation for the project.

License

This project is open-source and available under the MIT License.

Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

Acknowledgments

The PIMA Indians Diabetes Dataset is publicly available from the UCI Machine Learning Repository.

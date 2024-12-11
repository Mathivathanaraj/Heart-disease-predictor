# Heart Disease Prediction

## Overview
This project predicts the likelihood of heart disease in individuals using Logistic Regression, a widely used classification algorithm. The model is trained on patient data, including various health metrics and demographic information.

## Features
- Predicts heart disease risk based on patient data.
- Utilizes Logistic Regression for classification.
- User-friendly interface for inputting patient data and viewing predictions.
- Well-documented codebase for ease of understanding and modifications.

## Dataset
The dataset used for this project contains the following features:
- **Age**: Patient's age
- **Gender**: Male/Female
- **Blood Pressure**: Systolic and diastolic readings
- **Cholesterol Levels**: Total cholesterol in mg/dl
- **Smoking Status**: Smoker or Non-Smoker
- **Physical Activity**: Exercise frequency per week
- **Family History**: Presence of heart disease in the family

You can find the dataset [here](#). *(Replace with your dataset link)*

## Requirements
To run this project, you'll need:
- Python 3.8+
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib (optional for visualization)
  - flask (if deploying a web application)

Install dependencies using the command:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Install the required dependencies.

## Usage
1. **Training the Model**:
   - Place the dataset in the `data/` directory.
   - Run the training script:
     ```bash
     python train_model.py
     ```
   - The trained model will be saved in the `models/` directory.

2. **Making Predictions**:
   - Run the prediction script:
     ```bash
     python predict.py
     ```
   - Input patient data as prompted to receive a prediction.

3. **Web Application** *(Optional)*:
   - Start the Flask server:
     ```bash
     python app.py
     ```
   - Access the application in your browser at `http://127.0.0.1:5000`.

## File Structure
```
heart-disease-prediction/
├── data/
│   └── heart_disease_data.csv
├── models/
│   └── logistic_regression_model.pkl
├── notebooks/
│   └── EDA.ipynb
├── app.py
├── train_model.py
├── predict.py
├── requirements.txt
├── README.md
```

## Results
- Achieved an accuracy of **85%** on the test dataset.
- Confusion matrix and ROC curve analysis were performed for evaluation.

## Future Enhancements
- Incorporate additional health metrics for improved accuracy.
- Deploy the application on a cloud platform for broader accessibility.
- Experiment with other machine learning algorithms like Random Forest and XGBoost.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- The dataset used in this project was sourced from [UCI Machine Learning Repository](#).
- Special thanks to the open-source community for the tools and libraries used in this project.

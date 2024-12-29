
# Heart Disease Prediction using Logistic Regression

This project aims to predict the presence of heart disease in patients based on various health features using **Logistic Regression**. The model is trained on a dataset containing various health parameters such as age, cholesterol levels, blood pressure, and more. The goal is to predict whether a patient has heart disease (1) or is healthy (0).

## Dataset

The dataset used in this project is `heart_disease_data.csv`, which contains the following columns:

- **age**: Age of the person
- **sex**: Gender of the person (1 = Male, 0 = Female)
- **cp**: Chest pain type (4 types)
- **trestbps**: Resting blood pressure (mm Hg)
- **chol**: Serum cholesterol (mg/dl)
- **fbs**: Fasting blood sugar (> 120 mg/dl, 1 = True; 0 = False)
- **restecg**: Resting electrocardiographic results (values 0, 1, 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = Yes; 0 = No)
- **oldpeak**: Depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thalassemia (0, 1, 2, 3)
- **target**: Presence of heart disease (1 = Disease, 0 = Healthy)

## Objective

- **Train a Logistic Regression model** to classify patients as either having heart disease or being healthy.
- **Evaluate the model's performance** on test data.
- **Make predictions** for new patient data.

## Steps Involved

1. **Data Exploration and Preprocessing**:
   - Load and inspect the dataset.
   - Handle missing values, if any.
   - Split data into features (X) and target (Y).

2. **Model Training**:
   - Split the data into training and testing sets.
   - Train a **Logistic Regression** model using the training data.

3. **Model Evaluation**:
   - Evaluate the model’s accuracy on both the training and test datasets.

4. **Prediction for New Data**:
   - Make predictions for a single instance of input data (new patient).

## Requirements

To run the code, you'll need the following Python libraries:

- pandas
- numpy
- scikit-learn
- matplotlib (optional, for visualization)
  
You can install them using:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## How to Run the Code

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/Heart-Disease-Prediction-Logistic-Regression.git
   ```

2. **Place the dataset** (`heart_disease_data.csv`) in the project directory.

3. **Run the script**:

   ```bash
   python heart_disease_prediction.py
   ```

4. **Input new data**:
   - You can modify the `input_data` variable in the script to test the model with different patient data.

## Example Output

```bash
Accuracy on Training data: 0.85
Accuracy on Test data: 0.82
The Person does not have a Heart Disease
```

## Results and Insights

- The model was able to predict heart disease with an accuracy of **82%** on test data.
- Features such as age, cholesterol, and maximum heart rate are significant indicators for heart disease prediction.



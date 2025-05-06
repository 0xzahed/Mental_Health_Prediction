# 🧠 Mental Health Prediction

This project utilizes machine learning techniques to predict mental health outcomes based on survey data. It includes data preprocessing, model training, and a web application for user interaction.

## 📂 Project Structure

Mental_Health_Prediction/
├── app.py # Flask web application
├── mental_health.py # Data preprocessing and model training
├── project.ipynb # Jupyter notebook with exploratory analysis
├── survey.csv # Dataset containing survey responses
├── KNN.sav # Saved K-Nearest Neighbors model
├── Randomf.sav # Saved Random Forest model
├── logisticRegression.sav # Saved Logistic Regression model
├── Staking.sav # Saved Stacking model
├── mental_health_model.sav # Finalized model for deployment


## 📊 Dataset

The `survey.csv` file contains responses from individuals regarding various factors that may influence mental health. Features include:

- **Demographics**: Age, gender, etc.
- **Work-related factors**: Company size, remote work capability, etc.
- **Mental health history**: Family history, past diagnosis, etc.

## 🛠️ Features

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Implementation of multiple algorithms including Logistic Regression, K-Nearest Neighbors, Random Forest, and a Stacking ensemble.
- **Model Evaluation**: Assessment of model performance using appropriate metrics.
- **Web Application**: A Flask-based interface (`app.py`) allowing users to input data and receive mental health predictions.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/0xzahed/Mental_Health_Prediction.git
   cd Mental_Health_Prediction
📈 Model Performance
Include details about model accuracy, precision, recall, F1-score, or any relevant metrics here.

🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

📄 License
This project is licensed under the MIT License.


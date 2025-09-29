🌸 Iris Predictor

A simple machine learning web app to predict the species of an Iris flower based on its sepal and petal measurements. Built with Streamlit and scikit-learn.

Features

Predicts Iris species: Setosa, Versicolor, or Virginica.

User-friendly web interface with Streamlit.

Uses Random Forest Classifier for accurate predictions.

Real-time predictions from user input.

Installation

Clone the repository

git clone https://github.com/YourUsername/iris-predictor.git
cd iris-predictor


Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows


Install dependencies

pip install -r requirements.txt


Run the app

streamlit run app.py

Usage

Enter the sepal length, sepal width, petal length, and petal width in the input fields.

Click Predict.

The app will display the predicted Iris species.

Model Details

Dataset: Iris dataset from scikit-learn.

Algorithm: Random Forest Classifier.

Accuracy: High accuracy on default Iris dataset.

Technologies Used

Python

Streamlit

scikit-learn

pandas

Future Improvements

Add visualizations for feature importance and distribution.

Deploy the app online using Streamlit Cloud or Heroku.

Allow batch predictions from CSV uploads.

License

This project is open-source and available under the MIT License.

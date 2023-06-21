# Home Loan Prediction using Streamlit

This project aims to automate the loan eligibility process for a home loan using Streamlit. The goal is to develop a web application that allows users to input their details and receive a prediction on whether their loan application will be approved or not.

## Problem Statement

Dream Housing Finance company deals with home loans and receives loan applications from customers across different areas. The company wants to automate the loan eligibility process based on customer details provided in the online application form. The customer details include attributes such as gender, marital status, education, number of dependents, income, loan amount, credit history, and others. By automating this process, the company can efficiently identify eligible customers and streamline their loan approval process.

## Approach

The project follows a supervised classification approach to predict loan eligibility. The given dataset is used to train a machine learning model that learns patterns and relationships between the customer attributes and loan approval status. The model is then used to make predictions on new loan applications.

## Technologies Used

The project utilizes the following technologies:

#### Python: The programming language used for data preprocessing, model training, and prediction.
Streamlit: The web application framework used to create the user interface for loan prediction.
Machine Learning Libraries: Libraries such as scikit-learn are used for data preprocessing, model training, and evaluation.
How to Run the Application
To run the home loan prediction application:

Install the necessary dependencies by running pip install -r requirements.txt in your terminal.
Run the Streamlit application using the command streamlit run app.py.
Open your web browser and go to the provided local host URL (e.g., http://localhost:8501) to access the application.
Fill in the required details in the web form, including gender, marital status, education, number of dependents, income, loan amount, credit history, etc.

Click on the "Predict" button to receive the loan eligibility prediction.
Project Structure
The project directory is structured as follows:

app.py: The main script containing the Streamlit application code.

loan_prediction.ipynb: The script containing the code for data preprocessing, model training, and prediction.

data: The directory containing the dataset used for model training.

requirements.txt: The file specifying the dependencies required to run the application.

## Future Enhancements
Some potential enhancements for the project include:

Improving the model's accuracy and performance by trying different machine learning algorithms and techniques.
Adding visualizations to provide insights into the loan approval process.
Deploying the application to a cloud server for easy access and sharing.

## Conclusion
This project showcases the development of a home loan prediction application using Streamlit. By automating the loan eligibility process, the application helps users determine their chances of getting a home loan. This project serves as a starting point for further improvements and customization based on specific requirements.
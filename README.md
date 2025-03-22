
# Credit Card Fraud Detection using Machine Learning

This project demonstrates a machine learning approach to detect fraudulent credit card transactions. The dataset used is a collection of credit card transactions, which includes both legitimate and fraudulent transactions.


## Project Structure

- **Data Exploration**: Initial exploration of the dataset to understand its structure and distribution.
- **Data Preprocessing**: Handling missing values and balancing the dataset by undersampling the legitimate transactions.
- **Model Training**: Using Logistic Regression to train the model on the preprocessed data.
- **Evaluation**: Assessing the model's performance using accuracy scores on both training and test datasets.
- **Streamlit Application**: A web application built using Streamlit to allow users to input transaction features and predict whether a transaction is legitimate or fraudulent.

## Libraries


- NumPy
- Pandas
- scikit-learn
- Streamlit

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Manny61/Credit-Card-Fraud-Detection.git
   ```
2. Navigate to the project directory:
   ```bash   cd Credit-Card-Fraud-Detection
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure the `creditcard.csv` dataset is in the project directory.
2. Run the Jupyter Notebook to execute the code and see the results:
   ```bash
   jupyter notebook "Credit Card Fraud Detection using Machine Learning.ipynb"
   ```
3. To run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Streamlit Application

The Streamlit app provides a user-friendly interface to input transaction features and predict the transaction's legitimacy. Users can enter the features as a comma-separated list and submit them to get a prediction.

## Results

The model is evaluated based on its accuracy on both the training and test datasets. The results are printed at the end of the notebook and displayed in the Streamlit app.

## License

This project is licensed under the MIT License.
# House Price Prediction
  This Python code utilizes machine learning techniques to predict house prices based on key features. The code employs Linear Regression on a housing dataset and evaluates the model's performance using various metrics such as R2 score, Mean Absolute Error, and Mean Squared Error.

# Dependencies
* Python 3.0 or higher
  
     [Python](https://www.python.org/downloads/)
* Libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
  
    `pip install numpy pandas matplotlib seaborn scikit-learn`

  
# Dataset
The dataset used for this project is the "USA_Housing.csv" file, which contains essential information about house features and prices. It includes the following columns:

* Avg. Area Income
* Avg. Area House Age
* Avg. Area Number of Rooms
* Avg. Area Number of Bedrooms
* Area Population
* Price

  
Download Source: [USA_Housing](https://www.kaggle.com/datasets/vedavyasv/usa-housing)

# Running the Code
* Ensure all dependencies are installed.
* Make sure to upload the "USA_Housing.csv" dataset to either google drive or any IDE.
* Run the code in a Jupyter Notebook or any Python environment.

  
# Code Structure
* Loading the Dataset: Read the dataset using Pandas.
* Data Preprocessing: Check for missing values and perform feature scaling.
* Feature Selection: Visualize correlations and drop the "Address" column.
* Model Training: Split the data and train a Linear Regression model.
* Evaluation: Assess the model's performance using R2 score, Mean Absolute Error, and Mean Squared Error.



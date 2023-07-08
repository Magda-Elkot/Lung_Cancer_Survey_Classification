# Lung_Cancer_Survey_Classification

# Dataset
  The code reads a CSV file named "survey lung cancer.csv".
  
  Make sure to update the file path if your file is located elsewhere.

# Data Preprocessing
  The code performs several preprocessing steps on the dataset:

    1. Replace values 1 with 0 and values 2 with 1 in specific columns 
      (SMOKING, YELLOW_FINGERS, ANXIETY, PEER_PRESSURE, CHRONIC DISEASE, 
      WHEEZING, ALLERGY, ALCOHOL CONSUMING, SHORTNESS OF BREATH, 
      SWALLOWING DIFFICULTY, CHEST PAIN, FATIGUE, COUGHING).
      
    2. Map non-numeric values to numeric values for the GENDER and LUNG_CANCER columns.
    
# Exploratory Data Analysis
  The code performs exploratory data analysis to gain insights into the dataset. 
  
  It includes the following steps:
  
    1. Display information about the dataset (df.info()).
    
    2. Display the columns in the dataset (df.columns).
    
    3. Check for missing values in the dataset (df.isnull().sum()).
    
    4. Display basic statistics of the numerical columns in the dataset (df.describe()).
    
    5. Check for duplicated rows in the dataset (df.duplicated().sum()).
    
    6. Remove duplicated rows from the dataset (df = df.drop_duplicates()).
    
    7. Display unique values in the LUNG_CANCER and GENDER columns.
    
    8. Visualize the distribution of the LUNG_CANCER column using a pie chart and a bar chart.
    
    9. Visualize the correlation between features using a heatmap.
    
    10. Visualize the distribution of numerical features using histograms and box plots.
    
    11. Visualize the relationship between features using scatter plots, swarm plots, and kernel density estimation plots.
    
    12. Visualize the distribution of categorical features using bar plots.
    
    13. Visualize the pairwise relationships between features using a pair plot.
    
# Model Training and Evaluation
  The code trains and evaluates several machine learning models for lung cancer prediction. The models used are:
  
    1. Linear Regression
    
    2. Random Forest Classifier
    
    3. K Neighbors Classifier
    
    4. Decision Tree Classifier
    
    5. Gradient Boosting Classifier
    
    6. XGB Classifier
    
  The following steps are performed for each model:
  
    1. Split the dataset into training and test datasets.
    
    2. Apply data balancing using Random Over-sampling to handle the imbalanced dataset.
    
    3. Scale the features using StandardScaler.
    
    4. Train the model on the training data.
    
    5. Evaluate the model's accuracy on the test data.
    
    6. Display a confusion matrix and classification report for the model's predictions.
    
# Model Comparison
  Finally, the code compares the accuracy of all the trained models using a bar plot.

![image](https://github.com/Magda-Elkot/Lung_Cancer_Survey_Classification/assets/121414067/1f9af687-a1f4-41a5-bcb3-32fb230e2cdd)


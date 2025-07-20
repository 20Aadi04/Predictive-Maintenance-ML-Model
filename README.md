# Predictive-Maintenance-ML-Model
A project that helps in predicting and identifying machinery failure using ML. The project uses the predictive Machine Predictive Maintenance Classification dataset to perform exploratory data analysis (EDA), data preprocessing, SMOTE is used to create balance in the dataset, classification is done using RandomForestClassifier.

## Project
### 1.  Exploratory Data Analysis
- Visulaise the data by plotting histograms, boxplots. 
- Find correlations by plotting heatmaps, pairplots.

### 2. Data Preprocessing
- Find, remove null, duplicate values.
- Handle outliers
- using `SMOTE` to handle imbalance
- Scaling : StandardScalar

### 3. Model
`RandomForestClassifier`
  - Target: Binary Classification
  - Failure Type: Multi-Class Classification

### Results
ROC AUC score of about 96-97% for binary classification.
ROC AUC score of about 95-97% for multiple-class classification.
Also other evaluation metrics - precision, recall, f1 score, accuracy.

## Structure

    predictive-maintenance/
    │
    ├── predictive_maintenance.ipynb  
    ├── requirements.txt             
    ├── predictive_maintenance.csv  
    └── README.md                    

## Set-up
Git clone

    git clone https://github.com/your-username/predictive-maintenance.git
    cd predictive-maintenance

Dependencies

    pip install -r requirements.txt

Run

    jupyter notebook predictive_maintenance.ipynb


  



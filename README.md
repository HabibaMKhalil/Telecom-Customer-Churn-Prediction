
#  TELECOM CUSTOMER CHURN PREDICTION SYSTEM
Machine Learning | Python | Scikit-learn | Imbalanced Data                                 
A predictive analytics solution to identify at-risk customers in telecommunications using machine learning.

##  KEY FEATURES
- Comprehensive data analysis pipeline                           
- SMOTE implementation for class imbalance (14% churn rate)                    
- Feature engineering: total calls/minutes/charges                                            
- 4 ML algorithms compared with hyperparameter tuning                        
- Production-ready prediction system                                   

#3  MODEL PERFORMANCE
 1. Random Forest >>
    Accuracy:  0.92 
    Precision: 0.74 
    Recall:    0.74 
    AUC-ROC:   0.99  (BEST)

 2. SVM >>
    Accuracy:  0.89
    Precision: 0.63
    Recall:    0.68
    AUC-ROC:   0.88

 3. Decision Tree >>
    Accuracy:  0.84
    Precision: 0.49
    Recall:    0.82
    AUC-ROC:   0.82

 4. Naive Bayes >>
    Accuracy:  0.62
    Precision: 0.33
    Recall:    0.76
    AUC-ROC:   0.77                

##  INSTALLATION
$ git clone https://github.com/yourusername/telecom-churn-prediction.git                                            
$ cd telecom-churn-prediction                                      
$ pip install -r requirements.txt                                          

##  USAGE
1. Run EDA and data preprocessing:                           
$ python eda.py           

2. Train and evaluate models:                     
$ python train.py

3. Generate predictions:             
$ python predict.py                  


##  PROJECT STRUCTURE                              
telecom-churn-prediction/                                    
├── data/                                                               
│   ├── train.csv           # Training dataset                                        
│   └── test.csv            # Test dataset                                              
├── models/                                            
│   └── random_forest.pkl   # Saved best model                                             
├── notebooks/                                                   
│   └── analysis.ipynb      # Jupyter notebook for EDA                                    
├── eda.py                  # Data exploration                                           
├── train.py                # Model training                                  
├── predict.py              # Prediction script                               
└── requirements.txt        # Dependencies                                                                

### Overview
This project focuses on predicting stock prices using Machine Learning techniques. Financial markets are highly dynamic and influenced by various factors, making price prediction a challenging task. In this project, I analyze historical stock market data and build predictive models to forecast future stock prices.The goal is to provide insights that can assist investors in making informed decisions

### Technologies Used
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Scikit-learn
Visualization: Matplotlib, Seaborn
ML model: Random forest, KNN, SVM, Naive Bayes, Decision Tree

## Key steps
Data: Excel
Data Cleaning & Preprocessing:
  Handling missing values
  Outlier treatment
  Normalization & scaling
Model Building:
  Train-Test split
  Training ML/DL models
Model Evaluation:
  
Model	            Accuracy	Precision	Recall	F1-score
0	KNN            	0.940311	0.524178	0.411854	0.461277
1	Log Reg	        0.946912	0.666667	0.288754	0.402969
2	Naive Bayes	    0.916737	0.401055	0.693009	0.508078
3	Decision Tree  	0.954644	0.691974	0.484802	0.570152
4	Random forest	  0.955116	0.686475	0.509119	0.584642
5	SVM           	0.945875  0.689189	0.232523	0.347727

### Results and Observation
Random Forest performed the best overall with highest Accuracy (95.5%) and balanced Precision-Recall.
Naive Bayes had the highest Recall but lower Precision.
Logistic Regression and SVM showed decent performance but struggled with Recall.
Decision Tree also performed strongly, slightly behind Random Forest.








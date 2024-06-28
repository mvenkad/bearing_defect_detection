# bearing_fault_detection
Camaparative study on Chaos PSO-SVM and Genetic Algorithm-Gaussian Naive Bayes in effective detection of type of bearing defect 

Steps:
1. Clone this repository
2. Open src/bearing_fault_detection.ipynb in google colab
3. Upload the labeled data file (containing features eg. mean, kurtosis etc) data/feature_time_48k_2048_load_1.csv
4. Run the program

This will train ML model using Chaos PSO-SVM for bearing fault detection and capture the accuracy and performance metrics.
This will also train ML model using Genetic Algorithm-Gaussian Naive Bayes for bearing fault detection and capture the accuracy and performance metrics.

Performance metrics comparision:
Chaos PSO SVM Based Fault Detection Metrics
Accuracy: 96.74%
Objective function value: 0.967391304347826
Classification report:
              precision    recall  f1-score   support

           0       0.93      0.93      0.93        46
           1       0.98      0.90      0.94        50
           2       0.98      0.92      0.95        49
           3       0.97      1.00      0.99        37
           4       1.00      1.00      1.00        47
           5       0.95      1.00      0.97        39
           6       0.97      1.00      0.99        39
           7       1.00      1.00      1.00        54
           8       0.91      0.96      0.94        54
           9       0.98      0.98      0.98        45

    accuracy                           0.97       460
   macro avg       0.97      0.97      0.97       460
weighted avg       0.97      0.97      0.97       460

Genetic Algorithm - Gaussian Naive Bayes Based Fault Detection Metrics
Accuracy: 93.04%
Classification Report:
              precision    recall  f1-score   support

           0       0.93      0.93      0.93        46
           1       0.93      0.78      0.85        50
           2       1.00      0.76      0.86        49
           3       0.97      1.00      0.99        37
           4       1.00      1.00      1.00        47
           5       0.95      0.97      0.96        39
           6       1.00      1.00      1.00        39
           7       1.00      0.98      0.99        54
           8       0.72      0.94      0.82        54
           9       0.94      0.98      0.96        45

    accuracy                           0.93       460
   macro avg       0.94      0.93      0.94       460
weighted avg       0.94      0.93      0.93       460

## My-Work-on-Titanic-Dataset in Python

This is an assignment for the Machine Learning course (CS763). The required is to apply different machine learning techniques on Titanic dataset [1] using Scikit-learn library. The two Jupyter Notebooks have full details about each step in the work.

Data processing steps are the same in the two notebooks with referring to [2-3]. In the first Notebook 'train_test.ipynb', I used the train data and test data as is from Kaggle website. While for the second Notebook 'train_valid_test.ipynb', I split the train data into train and validation with 20%.


- **Results of 'train_test.ipynb'(Kaggle Test Results):**
    - DT ... 0.74162
    - Bagging DT .... 0.75598
    - AdaBoost ... 0.75598
    - Voting 5 models ... 0.76555
    - Voting all models ... 0.79425
    
    So, voting from all models had the best score.

- **Results of 'train_valid_test.ipynb'(Kaggle Test Results):**
  - DT2 ... 0.74162
  - Random Forest .... 0.79904
   - Naive Bayes ... 0.76555
   - KNN ... 0.76555
   - Voting all .... 0.77990
   - AdaBoost .. 0.73684
 
    So, Random Forest had the best score anmong the two notebooks.

**References:**
- [1] https://www.kaggle.com/c/titanic
- [2] https://www.kaggle.com/sinakhorami/titanic-best-working-classifier
- [3] https://www.kaggle.com/startupsci/titanic-data-science-solutions



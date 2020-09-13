# Spam-Classifier-Ensemble-Method
This project is built upon previous spam classifier project and tends to improve accuracy precision and f1score of spam classifier project.
# Getting Stated
In order to be able to run this project we will be needing following packages. 
- numpy
- sklearn
- pandas
- matplotlib
# Installing dependencies
```
pip install sklearn 
pip install numpy 
pip install pandas 
pip install matplotlib 
```
# Usage Example
```
First store message in string variable X
testing_data=message
### Predict using BaggingClassifier on the test data
b_predict=bagg.predict(testing_data)

### Predict using RandomForestClassifier on the test data
r_predict=random.predict(testing_data)

### Predict using AdaBoostClassifier on the test data
a_predict=ada.predict(testing_data)

```
This will output 0 or 1 depending upon spam or no spam
# License
This project is licensed under creative common 1.0.


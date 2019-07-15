# Project_2

## Multi-labels classification ##

<i>Python notebook created on October 2018. </i>
* Edited by <b>Karim Choukri.</b> (kchoukri012@gmail.com)
* Use case data extracted from <b>Mary Wahl</b> (https://gallery.azure.ai/Notebook/Predictive-Maintenance-Modelling-Guide-Python-Notebook-1)

The business problem for this example is about predicting problems caused by component failures such that the question "What is the probability that a machine will fail in the near future due to a failure of a certain component?" can be answered. The problem is formatted as a multi-class classification problem and a machine learning algorithm is used to create the predictive model that learns from historical data collected from machines. In the following sections, we go through the steps of implementing such a model which are feature engineering, label construction, training and evaluation. 

Common data sources for predictive maintenance problems are :

- Failure history: The failure history of a machine or component within the machine.
- Maintenance history: The repair history of a machine, e.g. error codes, previous maintenance activities or component replacements.
- Machine conditions and usage: The operating conditions of a machine e.g. data collected from sensors.
- Machine features: The features of a machine, e.g. engine size, make and model, location.
- Operator features: The features of the operator, e.g. gender, past experience

The data for this example comes from 4 different sources which are real-time telemetry data collected from machines, error messages, historical maintenance records that include failures and machine information such as type and age. Datasets are grouped as following:

- Fault history: The fault history of a machine or a component inside the machine.
- Maintenance history: The repair history of a machine, for example, error codes, previous maintenance activities or replacement of components.
- Conditions and use of the machines: The operating conditions of a machine, for example, data collected from the sensors.
- Characteristics of the machines: The characteristics of a machine, for example, engine size, make and model, age.



### Required Python libraries
- pandas
- numpy
- statsmodels
- scikit-learn
- scikitplot
- matplotlib
- seaborn
- tensorflow
- keras
- xgboost
- itertools

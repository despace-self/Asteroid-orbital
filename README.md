# Asteroid-orbital
this dataset which is officially maintained by Jet Propulsion Laboratory of California Institute of Technology which is an organization under NASA.

Data is used directly from the Kaggle Platform

This is a model predicting the orbital_period using the data features.

Model breakdown is as follows,

1) Data Importation
2) Defining Target
3) Data Preprocessing
4) Data Backup
5) Initiation of model - Random Forest Regressor - i used 100 estimators.
6) calculating the MAE, MSE &  R^2 Value.

Additionally, I also extended the model:

RFR as helper to a DNN Base but the result accuracy has been degraded than the first model, so i wont be including that
in this.

Model Metrics -
Random Forest Regression - Mean Squared Error: 34.323770564723
Random Forest Regression - R² Score: 0.991619243286325
Feature Importances:  [0.51837609 0.47346348 0.00334849 0.00219812 0.00261382]

Constructive feedbacks are highly appreciated.

Happy coding!

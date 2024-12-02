# This is ReadME file for the 'Predicting Mental Health' Predective model

# Definition
Given a sample dataset containing soci-economic chracterstics (features) of a population, the model tries to predicts
if an individual will suffer mental illness (Yes, No).

This is typical Data Science (Analytics) project and the approach developed here follows the Cross-Industry Standard Process 
for executing Data Science project.

Preprocessing of the datset is being carried out using Exploratory Data Analysis (EDA), suitable statistical tests are being carried out,
and most influential features (variables) that affect mental illness have been identified.

Appropriate AI/Machine Learning algorithm was chosen, and narratives for chosing the algorithm and limitations of the algorithm
were taken into consideration.

The predictive model has been built using the influential variables and fine-yunes for best performance.

The file for the saved final model is found inside 'test' folder of the Git repository.

The final best model will predict mental illness with 67% accuracy.

Given a test dataset, the model can be run in simple steps as follows:

 - Make sure you to locate the folder where the necessary source and datasets are
 - Make sure test dataset ('testfile.csv') is ready for running the model - with identical structure to the training dataset.
(Replace 'testfile' with your test file name)

To run the model:

1. Start Jupyter Notebook from command prompt
2. Go to 'test'folder and open the 'AXA 1872 - Trained Model.ipynb' python notebook - final model
4. Select 'Run' menu and then 'Run All cells' command from the menu options
 
Once the running is complete, you will have new csv dataset (prediction_test.csv) with a predicted response variable values.
 
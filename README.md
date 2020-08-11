# PLM
The CSV files provided has been uploaded to the AWS s3 bucket and then used for the further analysis using AWS SageMaker.
Tableau dashboard has been created for delivering the insights to the end user about the analysis. In which MySQL database has been used as a source and the code to create the 
MySQL database is also present in PLM-solution.py file.
You can directly run the plm.ipynb file to see the analysis performed on the data given. All the resultant data of the analysis is stored in analysis_data.csv which is also 
uploaded to the AWS S3 bucket to run the regression model over the data.
For the Regression Model:
symptom_severity_score is the prediction variable which is being predicted with the dependent variables like score, number_of_days (patient first reported) for each user.

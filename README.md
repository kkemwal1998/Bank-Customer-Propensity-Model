# Preface:
This project focuses on developing a predictive machine learning model that estimates the likelihood of HNI customers switching to competitive banking services in the European continent. This model will help the management to foster relations with the customers and tailor engagement strategies to retain at risk clients.  

The bank has compiled a database of five high-net-worth individuals, each maintaining a balance exceeding $1 million and holding an active membership. The objective is to assess the probabilistic likelihood of churn for 5 individuals aged 55 to 66 based on specific parameters. 

# 1. Project Objective:
The project’s objective is to identify:-

The likelihood of HNIs switching banking services for the foreseeable period.
Enhancing customer retention strategies through data insights.
Delivering an insight about which country’s branch has more attention in terms of customer oriented services. 
Enlightening the data teams with an opportunity to refine the machine learning model in the future projects.

# 2. Scope:

Data coverage: CustomerID, Surname, Credit Score, Geographical location,Gender, Age, Job tenure, Bank Balance, Number of Services Availed, Credit Information, Premium Membership Status, Yearly Salary & their churn status.
Prediction Target: Binary classification - Will Switch or Will Not Switch.
Geography: Pan international, covering all the branches across Europe.

# 3. Languages: Python (Pandas, Scikit Learn, Seaborn, Tensorflow, Numpy, & Spark) SQL, DAX

# 4. Tools: The model utilizes different tools to deliver an end to end solution to the stakeholders. Their   use cases can be explained as follows:-
-Sharepoint: Microsoft Sharepoint acts as a source for data collection from different teams.

-Azure (Blob, ADF & ML flow):

  Blob: Azure Blob acts as a data storage solution, making it feasible for multiple applications.
  ADF: ADF focuses on developing a pipeline with 30 minutes lag for the data migration between the Blob as its source and to Databricks notebook (With AI assistant) and 
  Snowflake.   
  
-Databricks: The notebook has been utilized to extract the database from the blob with respect to SAS token, ensuring data integrity. The platform mainly focuses on 
 developing the spark job session to  conduct cleaning,  feature engineering, and ML model “Customer Propensity Analysis” development with a workload allocation across 
 different nodes, ensuring accurate computation with respect to the cloud budget. The following also uses an AI agent, ensuring correct code syntaxes. 
 
-ML Flow: Azure's ML flow platform supports the registration of ML models making it feasible for the future data teams to call them as an API to perform repetitive work.

-Snowflake: The Snowflake has been leveraged to integrate and store the database in its virtual data warehouse, delivering auto scaling and enabling the team members to 
 develop and caching SQL queries to conduct churn analysis. Also, allowing the team members to migrate the same to its final destination for stakeholder communication.   
 
-Power BI: The Power BI has been applied to extract cashed SQL based databases for dashboard development, enabling the stakeholders to extract key insights based on the 
 requirement definition.

# 4. Feature Engineering Techniques:
The ML model leverages SHAP value technique to select the suitable features.
SHAP Method: 
A technique to quantify the contribution by each feature to predicting the customer churn of HNIs.

# 5. Algorithms Applied:  
The model applies the Logistics statistical algorithm formula to analyse the probabilistic likelihood of the customer to be in a binary class based on the customer dataset.
The algorithm delivers the probability output between 0 or 1.

# 6. Deliverable: 
The ML model delivers an output with the accuracy of 81%. 
Power BI dashboard facilitates the stakeholders with customers trend analysis. 
Setting up an API for ML model to help the organisation in deploying the solutions to help the management with retaining the at risk customers. 

# 7. Budget Analysis:
Total Budget for cloud platforms: $ 50

Accumulated Cost Incurred: $ 9

The project delivers accurate output with a cost savings of $41.

# 8. Conclusion: 
The analysis reveals that all five High Net-Worth Individual (HNI) clients currently associated with the bank are exhibiting behavioral patterns and transactional signals indicative of a heightened risk of attrition. These clients are actively engaging with competing financial institutions and demonstrating a potential disengagement with the bank’s premium offerings, suggesting a future inclination to switch their banking relationships.
Given the strategic importance of HNI clients, it is important to initiate immediate retention strategies, including personalized outreach, relationship management interventions, and tailored financial solutions to reinforce client loyalty and mitigate the risk of churn.

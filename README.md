# Classification-And-Causal-Modeling-Improving-Patient-Engagement-
Applying Artificial Intelligence &amp; Data Science to Health Care: Improving Patient Engagement at Clinicas del Azucar

Clinicas del Azucar serves a sizable population of people who live with diabetes in Mexico. The focus of the clinics is to serve the low-income population in pre-diabetes and diabetes management. We had access to datasets with clinical, demographical, and logistical information. Once we received the dataset, we performed exploratory data analysis and hypothesis testing. Afterwards, we performed a 'Clustering analysis' using historical data: historical activity records of patients associated with the clinic. We use these records to find the engagement level of the patients over time through their patient journey at CdA. We classify the activity records of the patients moving from the highest engagement level to the lowest levels.

Once we assimilate this information of all patients, we find the mean engagement level of the patients in each month of their patient journey. We created clusters of patients based on the engagement level. The output was three clusters, with “Low”, “Medium” and “High” engagement. We narrowed our population to those who have low-medium engagement levels. We performed 'Prediction modeling: Classification & Regression' to inform feature selection in our population of interest, and proposed an intervention that would address behaviors that impact our variables of interest.

The intervention we propose involves the creation of a cellular phone application whose main goals are twofold: to improve healthy eating and physical activity behaviors in the low-engagement populations at CdA as well as to improve the engagement scores of such populations over time. 

To identify features of importance, we selected a threshold value which separated the most important features from the least important after undergoing hyperparameter tuning. Then we performed 'Rubin Causal Modeling' to estimate the impact of our intervention in our selected behaviors, such as intaking coffee or refreshment and performing physical activities.
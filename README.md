# DAU_MAU
BigQuery_Floodit
In this project I used database "floodit" dataset available through the "firebase-public-project".
In definition folder there are three files
- declaration_floodit.sqlx -  Where is declared public data set 
- operation_floodit.sqlx - quiery to prepare preprocessed data, delete NULLs and dublicates
- DAUMAU.sqlx - Query where based on our set we found DAU(Daily Active Users), MAU (Monthly Active Users) and a ratio.
- 2023-11-22Retention_rate - first we create indexed table to make join command work more effisently. Here we count retention rate
- 2023-11-29_ Aquisition_ cohort_ analysis  - Set of queries to prepare data for cohort analysis

  As a result we have visualizations
 1. First one built in Looker MAU/DAU
  [Looker_Studio_Reporting_-_10_11_23,_6_34 PM.pdf](https://github.com/IrinaBogorad/DAU_MAU/files/13250810/Looker_Studio_Reporting_-_10_11_23._6_34.PM.pdf)
 2.The second visualisation built in Tableau
  https://public.tableau.com/app/profile/irina8030/viz/DAUMAUver2/Dashboard1
3.To analyse cohort
  https://public.tableau.com/app/profile/irina8030/viz/AquisitioncohortanalysisFirebase/Aquisitioncohortanalysis OR
https://public.tableau.com/views/AquisitioncohortanalysisFirebase/Aquisitioncohortanalysis?:language=en-US&:display_count=n&:origin=viz_share_link
  

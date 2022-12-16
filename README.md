# MINS
The possibility of the occurrence of Myocardial Injury after Noncardiac Surgery (MINS) is at a rate of 12 to 15 percent and is linked to an increased risk of 30-day mortality, 1-year mortality, and 2-year major vascular events. More than 90% of patients with MINS are asymptomatic which raises an important issue when the goal is the timely detection of MINS. In order to detect MINS, a routine monitoring of troponin levels is required. The troponin level laboratory test is done in 24 hour interval. The current Canadian Cardiovascular Society (CCS) perioperative guidelines recommend that the patients identified to be at high risk according to the Revised Cardiac Risk Index (RCRI) and BNP/NT-proB-type Natriuretic Peptide (NT-proBNP) receive daily postoperative troponin monitoring for three days to identify a MINS event.

There are multiple limitations to the current models of risk stratification. They can predict risk over the postoperative time period, but they are not able to identify when MINS may happen in the postoperative course, based on the patient’s changing conditions. Historic cohort studies have shown an association among intraoperative and postoperative disorder in the vital signs and MINS. Vital signs and troponin levels are important to detect or anticipate MINS. However, this analysis might become very complex when there is missing data.

In this study we experiment with various Imputation and Validation methods.

The data was aputed for 5%, 10%, 20%, 30%, 40% and 50%. Then these amputed values were imputed and then compared with the acutal values. 
The imputation methods we used are – Mean, Median, Linear Regression, Random Forest, Boosting and Bagging. 
The imputation was done on Diastolic Blood pressure, Systolic blood Pressure, Respiratory Rate and Pulse. These were vitals from the postoperative dataset. We selected these 4 variables as they had the least missing values(-999 or 0). 
The Validation methods used are 5 fold cross validation, 10 fold cross validation, Bootstrap validation, Fixed test bootstrap validation and 5 fold bootstrap validation. 
Fixed test bootstrap validation and 5 fold bootstrap validation are two variations of the standard bootstrap validation technique that we have implemented here.

# PSTAT175_Project13
### Final Project on Employee Turnover for Fall 2022 PSTAT 175: Group 13 (Ezra Aguimatang, Grace Nunnelley, Tetsuo Katsura),

## 1. Data Set Introduction

We chose to analyze the Employee Turnover dataset from the website Kaggle found here: https://www.kaggle.com/datasets/davinwijaya/employee-turnover. This Employer Turnover dataset contains 1129 observations with 17 covariates about how long it took until the employer quit the job. The covariates will be as follows:
stag, event, gender, age, industry, profession, traffic, coach, head_gender, greywage, way, extraversion, independence, selfcontrol, anxiety, novator. 
Our project will aim to predict the probability of an employee turning over or leaving versus not leaving based on the events and variables in the dataset. The outline of the covariates is as follows: 

stag:		Time until quitting (Units unsure)
event:		censored or not (1 = quit, 0 = censored)
gender:		f = female, m = male
age:		Employee’s age
industry:	Employee’s industry
profession:	Employee’s profession
traffic:	Where they learned about the company (advert, recNErab, referal, youjs, KA, friends, rabrecNErab, empjs)
coach: 	Whether a coach existed during the employee’s probation (my head = Yes & it was the head supervisor)
head_gender: 	Head supervisor’s gender
greywage: 	Whether the salary was given as the contract states (and paying the tax authority), or some payments done by envelopes (skipping tax authority).
way: 		method of transportation (bus, car, foot)
extraversion: 	Extraversion Score (float value 1-10) 
independence: Independence Score (float value 1-10)
selfcontrol: 	Self-control Score (float value 1-10)
anxiety: 	Anxiety Score (float value 1-10)
novator: 	Novator Score (float value 1-10)

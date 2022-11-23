# Airline Passenger Referral Prediction
![203225354-8607916b-35fe-4ef3-b4ba-74d58ffb6d1a](https://user-images.githubusercontent.com/96904369/203524955-9f0d492e-4312-45e4-a9e9-8342f77cc9d3.png)

# Objective:

Detail about airline passenger data referral The given data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scrapped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends. We have tested the data and done some Exploratory data analysis to build machine learning models for the prediction of the dependent factor which is the recommendation of airlines by the passenger to his\her friend.
# Abstract:
Air business as we know has been largely affected due to Covid-19 and most of the airline now is sitting on the verge of Bankruptcy because of this situation. Any bad decision may lead to severe outcomes where no stakeholder wants to invest without any future assurance. As an example of Singapore airlines who are among the hardest hit. As we know this situation is not permanent and it will be over but once this is over there will be a high surge as people will be back for holidays overseas. What can airlines do to tackle this situation? To answer this question, a machine learning model for classification is created from the airline_reviews dataset. This dataset has been provided to us by Almabetter in order to identify the important factors that lead to better customer satisfaction.
# Introduction:
The Airline passenger Referral system has become the most important criteria globally for the airline industry in order to address the surge which has been created after global pandemic so as to remain in the global market competition. Airline referral system generally works on customer reviews which is basically sentiment given by the customer depending upon various factor like seat comfort, their trip distance, route they have travelled, timing, the airline frequency, ground service etc. on the basis of which sentiment reviews are analysed and machine learning model on classification is prepared which helps airline industries to focus on the factor resolving which it can actually help them in business growth better than the competitors.
# Problem Statement:
Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.
# Data descriptions:
1.airline: Name of the airline.

2.overall: Overall point is given to the trip between 1 to 10.

3.author: Author of the trip

4.reviewdate: Date of the Review customer review: Review of the customers in free text format

5.aircraft: Type of the aircraft

6.travellertype: Type of traveler (e.g. business, leisure)

7.cabin: Cabin at the flight date flown: Flight date

8.seatcomfort: Rated between 1-5

9.cabin service: Rated between 1-5

10.foodbev: Rated between 1-5 entertainment: Rated between 1-5

11.groundservice: Rated between 1-5

12.valueformoney: Rated between 1-5

# Feature descriptions briefly as follows:
airline: Name of the airline in str fromat

overall: Overall point is given to the trip between 1 to 10 in float format.

author: Author of the trip in str format

reviewdate: Date of the Review customer review: Review of the customers in free text format in str need to be converted into DateTime Format

aircraft: Type of the aircraft in str format

travellertype: Type of traveler (e.g. business, leisure) consist of four class in str format

cabin: Cabin at the flight date flown: Flight date in str format consist of 4 class.

seatcomfort: Rated between 1-5 in float format

cabin service: Rated between 1-5 float format

foodbev: Rated between 1-5 entertainment: Rated between 1-5 in float format

groundservice: Rated between 1-5 in float format

valueformoney: Rated between 1-5 in float format

# Conclusion:
We can conclude following things from above:
* We Found that people have given both 1 or 0 which we will consider from now on as positive and negative recomendation so to interpret it effectively to the solo leisure. This may because of the poor infrastructure or the service recieved by the people and positive recommedation may be because of low price for solo. But this is approximate analysis based on the data provided.
* Also we can see that people gives the high positive recommendation to economic class in cabin. From this we can conclude that people love to travel in economic class as of low price also in same way we can see people give highest negative recomendation to economy class maybe because less infrastrure or service provided to them. Also we can see people have given higest positive recommedation to Business class it may be because of the quality of service provided to them in Business class and simmilarly negative recoomendation because of high price of business class or less travelling percentage.
* From month vs no. of recommendation. We can see that people tents to travel most in the month of July considering the total of positive and negative recommendation combined.
* From overall vs recommended graph we can see which is perfectly understandable that negative recommendation has been given to the overall rating of 1.0 and high positive recommendation has been given to the overall rating of 10. But it is very true that highest negative recommendation has been given to overall rating of 1.0 which is really a matter of concern.
* In seat comfort people has given highest positive recommended to the seat of class 5 as compared to very low negative recommendation to the same. Also we can see seat of class 1 have been given highest negative recommendation as compare to its positive recommendation. Here we come to a conclusion it must be removed as early as possible.
* In cabin service rating people has given highest recommendation to rating to cabin service rating 5 as compare to its counterpart. From this we can conclude that cabin service is doing pretty good.
* In food and beverage rating people have given highest negative recommendation to rating 1.0 from this we can conclude that airline service has to improve their food delivery and quality service.
* In entertainment also we can see most people has given highest negative recommendation to entertaiment rating 1 which shows that airline has to improve their entertainment system as well.
* In ground service also we can see most people has given highest negative recommendation to ground service rating 1 which shows that airline has to improve their ground service.
* In value for money also we can see most people has given highest negative recommendation to value for money rating 1 which shows that airline has to make their flight service more cost effective.
* In model Selection we can see that Random Forest and XGBoost Model is having the same high Model Accuracy with a score 0.957082 but we can also see that recall, precision, f1-score and roc_auc_score of XGBoost model combined is giving higher score than Random Forest from which we have chosen XGBoost Model for further prediction.
* In Shap JS summary we can see positive features overall, value for money,numeric_review combined red color block pushes the prediction toward right over base value and causing positive model prediction and it is common for all model.
* In Shap summary scatter plot we can see in scatter plot high overall,value for money,numeric_review,cabin service,ground_service positive features and low airline_British_airways is increasing positive prediction and it is common for all models. Also we can see that overall,value for money,numeric_review,cabin service,ground_service has high shap feature value.

# 📋 Execution Instruction:
The order of execution of the program files is as follows:

1) Airline referral capstone project.py

First, the Airline referral capstone project.py file must be executed to define all the functions and variables required for classification operations.

2) train.py

Then, the train.py file must be executed, which leads to the production of the model.txt file. At the beginning of this file, the Airline referral capstone project has been imported so that the functions defined in it can be used.

3) test.py

Finally, the test.py file must be executed to create the result.txt and evaluation.txt files. Just like the train.py file, at the beginning of this file, the Airline referral capstone project has been imported so that the functions defined in it can be used.

# 📜 Credits
<Shahfaissal I Dharwad> | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

Contact me for Data Science Project Collaborations

<a href='linkedin.com/in/shahfaissal-' target="_blank"><img alt='linkedin' src='https://img.shields.io/badge/Linkedin-100000?style=plastic&logo=linkedin&logoColor=white&labelColor=black&color=black'/></a> <a href='github.com/shahfaissalDharwad' target="_blank"><img alt='Github' src='https://img.shields.io/badge/GitHub-100000?style=plastic&logo=Github&logoColor=white&labelColor=black&color=black'/></a> <a href='https://medium.com/@shahfaissal21/reading-a-csv-file-in-python-7a834d906c3e' target="_blank"><img alt='Medium' src='https://img.shields.io/badge/Medium-100000?style=plastic&logo=Medium&logoColor=white&labelColor=black&color=black'/></a>

# References
1.Analytics vidhya

2.Kaggle

3.Tutorials point

4.W3school

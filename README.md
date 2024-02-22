# Luna Website (PCOS Risk Prediction App with Machine Learning)
This project aims to use the power of machine learning to predict any risk of PCOS (polycystic ovarian syndrome) in females based on their menstrual cycle pattern. 

The project involves the use of survey data from 200+ real subjects and was trained to predict the risk of the disease which may prompt her to have a health consultation with a doctor as soon as possible. 

The machine learning algorithm which I employed was linear regression and I carefully analyzed all the features before deploying the model into the streamlit application and hosting it on the streamlit community cloud.

I used several libraries like numpy pandas and matplotlib for the data cleaning and preprocessing before feeding it into the model. 

Then further getting rid of null values and splitting the dataset into training and testing data and scaling the features  I trained my model and it was dumped into a pickle file which was then used to build the web app.

The dataset is open sourced on Kaggle for people to contribute and it’s a real world problem based application where the scope of learning the dynamics of machine learning application.

## Description of the features:  
The dataset included the following features: 
- Number_of_peak: Number of peak bleeding instances
- Age: Age in years
- Length_of_cycle: Length of cycle
- Estimated_day_of_ovulution: Expected day of ovulation beginning
- Length_of_leutal_phase: Length of the gap between ovulation and menstrual phase
- Length_of_menses: Number of days the menstrual period lasts
- Unusual_Bleeding: To check if unusual bleeding happened
- Height: Height of person
- Weight: weight of person
- Income: Income of the person(in INR)

## How to Run the project?
To use the model the following steps need to be followed: 
- Make sure you have Python installed on your computer.
- Clone the project from the repository
- Activate the virtual environment (if used).
- Use ```pip install streamlit```
- Install required libraries (```streamlit```, ```pandas```, ```numpy```, ```scikit-learn```).
- Run the app.py file using the command ```streamlit run app.py```

## Benefits:
- Empowers women to monitor their health and seek timely medical care.
- Provides a valuable tool for medical professionals in early diagnosis.
- Offers a practical example of machine learning in healthcare.


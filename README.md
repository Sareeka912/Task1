About datasets 
I.Telco Customer Churn Data set
The telecoms churn dataset contains information about customers of  telecom company and whether they canceled their service (churn) or not churn. This data set  includes various features such as customer age, gender, etc and service usage data number of calls, minutes, billing method, etc.
This dataset consists of 7043 examples and 21 features, and is commonly used in machine learning and data analysis as a benchmark for predicting customer churn.This  can help to  create models that predict which customer is churn or not and allowing businesses to take actions according to prediction. By reducing customer losses, companies can improve customer loyalty and increase their earnings.

II.Brest Cancer Data set
This dataset contains information related to breast cancer, it includ various features such as tumor characteristics and patient demographics. It is used to develop models that can classify whether a tumor is malignant (cancerous) or benign (non-cancerous). Analyzing this data helps in understanding factors that contribute to cancer diagnosis and treatment decisions.


III.Student performance
This dataset  related to student performance. Each row is uniquely identified by an 'Id'. The dataset includes  information such as 'Student_Age' and 'Sex'. 'High_School_Type' categorizes the type of high school attended, while 'Scholarship' indicates  student have a scholarshipor not and if have then how much percentage student have, and 'Additional_Work' and involvement in 'Sports_activity' provide insights into extracurricular commitments.
'Transportation' outlines the mode of commuting for each student. Academic information is captured through 'Weekly_Study_Hours', 'Attendance', and through  'Reading', 'Notes', and 'Listening_in_Class'. These factors is reflected in the 'Grade' column, providing a comprehensive overview of student performance. This dats set features provide valuable insights of student academic performance.


Step 1: 
	Data_loading: Load data set by using pandas library 
	And I use three classification data sets 
I.Telco Customer Churn Data set
II.Brest Cancer Data set
III.Student performance

Step 2 :
	Data cleaning: Firstly, I check the is there any duplicate if it have then drop , and then I drop unnecessary feature from data set. I have applied other strategy to change the type of feature if needed but it through error in plotting time.

Step 3: 
	Missing Value handling: handle missing  if it have and I use mean strategy to handle missing value in features.

Step 4:
	EDA: By using this technique I make a function which show plotting according to types such as, for numeric attribute Histogram is used, for categorical attribute Bar chart is used, Box plot graph is for outlier detection and to find the relation I use correlation matrix sns.heatmap()  to show how strongly they are related.

Step 5: 
	Outlier Detect: detect outlier using IQR technique where it detect the outlier and handle by using mean now problem is in some data set we don not need to handle the outlier we just detect the outlier here I also in Brest cancer data set I avoid this handle technique.


These all steps I write in functions and I call these in function sequentially by making one master function.


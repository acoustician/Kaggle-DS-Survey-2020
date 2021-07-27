# Kaggle-DS-Survey-2020
This notebook is a exploratory data analysis (EDA) of the most comprehensive dataset available on the view of machine learning and data science today 2020 [Kaggle Machine Learning & Data Science Survey](https://www.kaggle.com/c/kaggle-survey-2020/data). The survey answers covered demographic, education, employment, and technology usage to learn more about data science practitioners in 2020.
  
  
 # Contents 
  1. Overview
  2. Packages used
  3. Exploratory data analysis
  4. Conclusion
 
 
 # Overview 
 
  Kaggle platform conducted an industry survey every year with the intent to present a genuinely comprehensive view of the current insights of data science and machine learning.The questionnaire collected 20,036 data by survey. 
  
  There are 39 main [Questions](https://drive.google.com/file/d/1FXmCuhZxkiEZb1_DG_1dlRHg3vJxIXvW/view?usp=sharing) and 16 supplementry questions.Each questions has number of choices, In some question, there are one or more choices can select and in some questions only one option can choose 
  Based on the results of this questions a EDA is performed to get the insights about the people behind the data, machine learning application across different industries and the most valued skills to break into the Data Science field
  
  
      
# Packages used   

1. [Pandas](https://pandas.pydata.org/about/)
2. [Numpy](https://numpy.org/)
3. [Seaborn](https://seaborn.pydata.org/)
4. [Matplotlib](https://matplotlib.org/)  


# EDA(Exploratory data analysis)  

  # 1.Countries have most number of data scientist(overall vs Experienced)
  This anlaysis focused on top most countries(3rd Question) which have maximum number of Data scientist.There are two bar plots first is for overall and second one is experience-wise.  
  There are lots of year range option in experience column which makes visualization little confusing therefore the Experience of the candidates are divided in three categories,   First is Proffesional(10+ year experience) second is Intermediate(3 to 10 year experience) and last one is Beginner(0-3 year of experience).  
        
  Here are the plots of the analysis
  
  
  ![EDA1a](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda1a.png?raw=true)

  
  ![EDA1b](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda%201b.png?raw=true)
 
 
 
 # 2.Programing Language recomended most for aspiring data scientist.
   Candidates have multiple choices for choosing the one programming language(8th Question) which they would recommend to the aspiring Data scientist.This analysis focused on the top 8 programming language which is mostly recommended by the candidate to the aspiring data scientist.Those who wants to become a data scientist,so this anlaysis will helpful to them.
   
   Here are the plot of the analysis
    
   ![EDA2](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda2.png?raw=true)
 
 
 # 3.Most popular Integrated development environments (IDE)
 An IDE or Integrated Development Environment, enables programmers to consolidate the different aspects of writing a computer program.IDEs increase programmer productivity by  combining common activities of writing software into a single application: editing source code, building executables, and debugging.
 
Candidates have multiple choices to select the one or more then one IDE.This analysis tells us about the popular IDE for data science.

Because of multiple choice, Data are present in diffrent number of column. For better visualization, a dictionary is defined for combining the all columns and count them in a single dataframe.

Here are the visualization for IDE


![EDA3](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda3.png?raw=true) 



# 4.Programming Language used on a regular basis

The surveyor asked to the candidate that which programming language they used in a regular basis.Based on these question a analysis was made for the most used programming languages.Here also, candidate can select more then one choices for the particular question.That's why data are present in the diffrent columns.Therfore, for better visualization a dictionary was defined and make a dataframe from the dictionary in which all options and its value count are stored.

These analysis tells us that which programming language is used mostly.

Here are the visualization for this challenge

![EDA4](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda4.png?raw=true)


# 5.Machine learning algorithms used on a regular basis

Machine learning algorithms are the engines of machine learning, meaning it is the algorithms that turn a data set into a model.ML algorithm is used for regression and classification problems.

Surveyor asked to the candidate that which ML algorithm used on a regular basis.Here also, candidate can select more then one choices for the particular question.That's why data are present in the diffrent columns.Therfore, for better visualization a dictionary was defined and make a dataframe from the dictionary in which all options and its value count are stored.

These analysis tells us that which ML algorithm is used mostly.

![EDA5](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda5.png?raw=true)


# 6.Business intelligence tools used on regular basis

Business Intelligence (BI) includes tools and techniques, for the transformation of raw data into meaningful and actionable information for Business analysis.In short, Business intelligence tool is used to provide insights from structured data.
Surveyor asked to the candidate that which BI tool used on a regular basis.Here also, candidate can select more then one choices for the particular question.That's why data are present in the diffrent columns.Therfore, for better visualization a dictionary was defined and make a dataframe from the dictionary in which all options and its value count are stored.

This analysis is focused on mostly used BI tool by the Data analyst.

![EDA6](https://github.com/acoustician/Kaggle-DS-Survey-2020/blob/main/anlaysis%20pictures/eda6.png?raw=true)


# 7.Platform where Publicly share or deploy data analysis or machine learning model.
  
  There are lots of community platform such as Kaggle, Github, Streamlit, Google colab etc. where project or model shared or deployed by data scientist.If project is publicly available than anyone around the World can access.

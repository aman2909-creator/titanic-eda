# Titanic EDA Project

This project explores the Titanic passenger dataset to uncover patterns related to survival rates. Key goals include:

- Cleaning and preparing data
- Visualizing survival by gender, class, and age
- Drawing insights from patterns in the data

## Dataset
[Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib 

## Data dictionary

- survival   =  passenger survived or not ; 0 for NO and 1 for Yes
- pclass     =  ticket class; 1 = 1st, 2=2nd, 3=3rd
- sex        =  sex
- Age        =  Age in years
- ticket     =  ticket number
- fare       =  passenger fare
- cabin      =  cabin number
- embarked   =  post of embarkation; C = Cherbourg; Q = Queenstone; S = Southampton

## Variable notes
pclass -> to know the status of socio-economic status of the passengers
        1-> upper class
        2-> middle class
        3-> lower class

sibsip -> family relations
          siblings -> brother,sister,stepbrother,stepsister
          spouse   -> husband, wife

parch  -> family relations
          parent -> father,mother
          child  -> son,stepson,daughter,stepdaughter
          some children travelled only with nanny, therfore parch = 0 for them

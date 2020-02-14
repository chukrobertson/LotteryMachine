# LotteryMachine
A data project with Pick3 lottery data from 1990 to present.
---

## The Goal:
Use Data from 1990-2019 to test predictions of 2020 picks

## The Path
 - Convert PDFs to csv dataframes 
  - *done*
   - _2009> needs PDF formatting before it can be used_
 - Clean all dataframes
  - *done*
 - Set useable column names 
  - *done* Columns = [Draw, Date, Pick3]
 - Remove uneccesary columns/NaNs 
  - *done*
 - Convert Date to useable DateString
  - *done*
 - Join all dataframes into one 30 year frame of data. 
  - *2010-2019 for now*
 - Clean 2020 dataframe for prediction testing 
  - *done*
 - Create prediction model to train on 30 years' data
  - Test for accuracy

## Tools Used:
 - Linux OS (Kubuntu 20.04)
 - Jupyter Notebook
 - VS Code
 - Python3
  - numpy
  - pandas
  - tabula-py
   - openjdk 11.0.6
  - matplotlib
  - More as I update

#### I know it's messy, I'll clean it up and rename the notebooks as I update.



##### This is a project to help me learn more about data science - NOT A GET RICH QUICK SCHEME
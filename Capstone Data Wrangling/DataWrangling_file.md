This file upload includes data wrangling steps taken towards cleaning the appeneded datasets. 

Note: 

Concerns -> A lot of '?' and -9 that did not get dropped off when I dropped NaNs from the dataset. 
Alternatively I chose to create a new dataframe that takes values that are not -9 or ?. Problem: I no longer have equal 
rows in my dataset. If I try and delete the rows with those entries I could go from 850 rows to 303 rows if I chose to 
keep all the variables. I proceeded to convert the columns in my dataframe into a float64 to plot them. 

I have included some plots to better understand the distribution of some variables. The latter still remains a concern
for me. 
# Data_analysis_Ipl
This project is made from python libraries matplotlib and pandas. In this there is analysis of different IPL statistics.In this I have used matplotlib and seaborn to reprenst data in graphical data.
The file has been read using read_csv command of pandas and stored in a variable 'data'. 
A pie diagram has been drawn using matplotlib to show how many tosses gave decision of bat and field.
.groupby(['team1', 'team2']): This part of the code groups the data by unique combinations of values in the 'team1' and 'team2' columns. It creates groups where each group represents a unique combination of 'team1' and 'team2'.

.size(): After grouping, the size() function is applied to each group. This function calculates the number of rows (or occurrences) in each group. As a result, we get a Series or DataFrame (depending on the data structure) that shows the count of occurrences for each unique combination of 'team1' and 'team2'.
So, the result of this code would be a data structure that contains the count of occurrences for each pair of teams ('team1' and 'team2') in  dataset, indicating how many times each combination appears in  data. This can be useful for various types of data analysis, such as understanding the frequency of matchups between teams or identifying patterns in the data related to these team combinations.
.value_counts() method counts the occurrences of each unique value in the specified column and returns a Series where the unique values are the index, and the corresponding counts are the values.So, man_of_the_match is be a Series where the unique player names are the index, and the values represent how many times each player has been named "Man of the Match" in the dataset.
Python is easy to use and has lot of useful libraries for analysis of dataset.

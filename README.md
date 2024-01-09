# Summary
This is a function that merges same-named columns of a pandas dataframe, retaining the maximum possible information. 
# Use Cases
(a) Use when you have more than one column in your dataframe that represents the same variable, and you want to merge all those columns into one. 
(b) If you have more than one dataframe that you'd like to merge together, first do pd.concat([list of your dataframes], axis=1) and then perform combine_dupes on the result.

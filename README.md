# pandas-challenge
Module 4 HW

I ran into an issue when trying to use .groupby().mean() to calculate values by school. I found the solution on stackoverflow(https://stackoverflow.com/questions/44522741/pandas-mean-typeerror-could-not-convert-to-numeric), the mean required numeric_only=True, otherwise an error would occur saying that the student names couldn't be converted into a numeric value.
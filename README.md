Preprocessing:
Import pandas, seaborn, matplotlib.pyplot, numpy.
Use files: "communities.csv", "Houses-by-suburb.csv“.
In "communities.csv", data that is not a number is converted to number in column "Equivalent household income <$600/week". And keep one decimal place for all the data in the column. "Equivalent household income <$600/week, %" and column "Holds degree or higher, %". Convert suburb names to uppercase to facilitate merging later.
In "Houses-by-suburb.csv“, delete rows which house price in 2013 is null, then sort it by the house price in 2013.
After merge these two together, suburbs are categorized into Low, Medium, and High based on their house prices. (the lowest 25% in the Low category, the middle 50% in Medium, and the highest 25% in High).


Data analysis:
Use "final_merged_data" from preprocessing, and switch the data to numeric firstly.
Draw boxplot for '2013' House Prices, 'Equivalent household income <$600/week, %', and 'Holds degree or higher, %'.
Draw scatter plot for '2013' vs 'Equivalent household income <$600/week, %', '2013' vs 'Holds degree or higher, %', 'Equivalent household income <$600/week, %' vs 'Holds degree or higher, %'.
Then use the custom function to calculate the Pearson Correlation Coefficient between house price and 'Equivalent household income <$600/week, %', between house price and 'Holds degree or higher, %', between 'Equivalent household income <$600/week, %' and 'Holds degree or higher, %'.

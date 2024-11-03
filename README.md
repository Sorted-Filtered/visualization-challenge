# visualization-challenge
Module 5

Project Description

Two databases were merged for analysis (mouse metadata and study results). Duplicate data was removed and the data was summarized by the drug regiment administered. From this drug regiment summary, four drugs were selected for further analysis. This further analysis includes quartiles, outliers, and box plots based on average tumor size. Mouse sex was also analyzed. One mouse (L509) was selected for line plot creation. Also, weight vs average tumor size was plotted and a linear regression model calculated based on mice under the Capomulin regiment.

Execution
File requires to be put into folder with one other folder, data. Raw .csv files must be put into the data folder named "Mouse_metadata.csv" and "Study_results.csv".

Features
File features .csv reader. The use of the pandas module to summarize .csv files using dataframes, database merging, and plotting. Matplotlib.pyplot was used for figure generation. Also, scipy.stats was used for creation of linear regression modeling.

Contributors
EdX class code examples were used in the entire project. The .duplicated function from <https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html> was used to find duplicates in the 3rd cell.

License
GPL-3.0 License.

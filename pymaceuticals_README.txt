**Pymaceuticals: Cancer Regimen Analysis**

*Project Description:*
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

**Analysis**
- There is a near equal number of male mice to female mice, limiting the influence of sex on the results.
- More mice were treated with Capomulin and Ramicane than any other drug; both yielded smaller tumors on average compared to other drug regimens by the end of the treatment timepoints. Relatedly, Mouse l509 (treated with Capomulin) saw a significant tumor volume decline over time.
- Overall, mouse weight and average tumor volume are strongly correlated (Pearson R: 0.84); this means the larger the mouse, the larger the tumor.
- It's recommended that equal numbers of mice are subjected to each treatment to increase robustness of results.

*To Use*
Run the script in Jupyter.

*Credits*
https://www.statology.org/pandas-find-duplicates/
https://www.youtube.com/watch?v=iYWKfUOtGaw&t=780s
https://www.geeksforgeeks.org/python-pandas-dataframe-aggregate/
https://www.geeksforgeeks.org/how-to-drop-rows-that-contain-a-specific-string-in-pandas/
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html
Grepper Chrome Extension
UCB DV Bootcamp Study Groups
AskBCS Support
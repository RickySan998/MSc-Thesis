# MSc-Thesis

Instructions on running the code:
1. Ensure that the relevant packages are installed. These include NumPy, Pandas, Matplotlib, NashPy, CVXPY, CVXOPT, seaborn, SciPy, and MOSEK.
2. Ensure that a mosek.lic file is present at the required directory
3. Functions to process raw Lichess and FICS data yearly can be found in pgn to dataframe.ipynb. For this function, ensure that the relevant datafiles (i.e. the pgn files of the Lichess or FICS montly games in that year) are present in the same directory as the notebook. 
4. Functions to replicate experiment results from the processed yearly Lichess and FICS data are found in Lichess Processing <year>.ipynb and FICS testing.ipynb respectively. Ensure that the processed files are present in the same directory as the notebooks.
5. Functions to replicate experiment results on theoretical games and the additional games in appendix, are found in Theoretical and Paper Games Nash Clustering.ipynb and Spinning Top Games.ipynb respectively. For the latter, ensure that spinning_top_payoffs.pkl (from "Real-World Games look like Spinning Top" paper) file is in the same directory as the notebook.
6. Functions to replicate the experiments on Chess player rating mappings can be found in Lichess Rating Conversion.ipynb. Ensure that the data file Lichess vs USCF vs FIDE.csv is in the same directory as the notebook.
7. Functions to replicate the plots in the report are found in Plotting Codes.ipynb. Ensure that all the data generated from the processing notebooks in points 4,5 and 6 are in the same directory as the notebook.


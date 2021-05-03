# Recurrent
Data-X: Helping SaverLife Fight Wealth Inequality by Driving Financial Savings

# Front-end / UI
A Tableau workbook has been developed to show individual model results to Saverlife users, along with further data to provide context for the model's predictions.
This visualization was designed through interviews with Saverlife to provide the most important and relevant information to users,
and will ideally be converted into a Tableau Server product for personal use or otherwise made available within the Saverlife app suite.

Each user sees their future predicted savings, their predicted versus actual savings for past months, and their income, spending, and balance history.
The future predicted savings are intended to motivate users to hit the 'goals' set for them, and may be adjusted in future to show model predictions + 10% as an 'aspiration'.
The past months of predicted versus actual savings along with the true financial history data shows the user their progress and performance to date.

Currently, this workbook relies on flat .csv input ('TS_'.csv) and output files from team members and imports the necessary columns.
To re-run the workbook, you would edit the Connections on the Data Source tab to point to the new files, which would then refresh the Tableau extracts behind the workbook.
Ideally, this workbook would be refactored to pull the necessary input data directly from the Saverlife database.
However, creating a direct connection between the model outputs and the Tableau workbook would require significantly more effort.

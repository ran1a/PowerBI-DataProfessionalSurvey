# PowerBI-DataProfessionalSurvey
This is a PowerBI project based on a dataset regarding Data Professionals.

PART 1: Cleaning the Data

Before loading the data, certain transformations took place. Firstly, some empty columns were deleted. Then, the columns that had the option "Other" were splitted in order to simplify the possible outcomes. The salary range column was transformed to an average of each row's range. In order for this to be implemented , the "Q1-Current Yearly Salary(in USD)" column was duplicated,splitted by digit to non digit which gave 3 new columns and only the ones with the minimum and maximum values were kept for the average to be calculated. For this last step, a new custom column was added with the formula that produces the average salary. Finally, the data was loaded.

PART 2: Creating the Visualisation


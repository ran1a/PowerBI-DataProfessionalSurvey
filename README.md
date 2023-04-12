# PowerBI-DataProfessionalSurvey
This is a PowerBI project based on a dataset regarding Data Professionals.

PART 1: Cleaning the Data

Before loading the data, certain transformations took place. Firstly, some empty columns were deleted. Then, the columns that had the option "Other" were splitted in order to simplify the possible outcomes. The salary range column was transformed to an average of each row's range. In order for this to be implemented , the "Q1-Current Yearly Salary(in USD)" column was duplicated,splitted by digit to non digit which gave 3 new columns and only the ones with the minimum and maximum values were kept for the average to be calculated. For this last step, a new custom column was added with the formula that produces the average salary. Finally, the data was loaded.

PART 2: Creating the Visualisation

To begin with, a text box was used to add a title at the top of the grid. In addition, the average age and the total number of participants were included at the top. The first graph was about demonstrating with a stacked bar chart the Average Salary per Job Title  Furthermore, a stacked column chart of the Favourite Programming Language per Job Title was added as well as a tree map to have a general view of the participants' countries. To conlcude, two gauge charts were used to show how happy the participants are regarding their salary and the Work-Life Balance and a donut chart to indicate the salary gender gap.



Dataset was provided by: 
https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx

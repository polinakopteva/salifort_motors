# Salifort Motors project
Project from Google Advanced Data Analytics course on Coursera

# Description of project "Salifort Motors project"

## Data
Data description
The file `HR_capstone_dataset.csv` stores data collected by the HR department.

* `satisfaction_level` - Employee-reported job satisfaction level [0-1]
* `last_evaluation` - Score of employee's last performance review [0-1]
* `number_project` - Number of projects employee contributes to
* `average_monthly_hours` - Average number of hours employee worked per month
* `time_spend_company` - How long the employee has been with the company (years)
* `Work_accident` - Whether or not the employee experienced an accident while at work
* `left` - Whether or not the employee left the company
* `promotion_last_5years` - Whether or not the employee was promoted in the last 5 years
* `Department` - The employee's department
* `salary` - The employee's salary (U.S. dollars)

## Goals of the project
Goals in this project are to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.

If we can predict employees likely to quit, it might be possible to identify factors that contribute to their leaving. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.

The project was created using the PACE strategy (Plan-Analyze-Construct-Execute). At the end, several models were built, of which, based on the metrics, the random forest model was selected as inference.

## Used libraries
*pandas*, *numpy*, *matplotlib*, *seaborn*, *xgboost*, *sklearn*, *pickle*

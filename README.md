# Propensity-to-Fund-Mortgages
 mortgage application information
 
# Description

Propensity to fund mortgages describes the natural tendency for a mortgage to be funded based on certain factors in a customer’s application data.

To predict whether a mortgage will be funded using only this application data, certain leading factors driving the loan’s ultimate status will be identified. Solvers will discover the specific aspects of the dataset that have the greatest impact, and build a model based on this information.
Objective

The objective of this contest is as follows:

    Develop a model to predict, given mortgage application information, whether the mortgage will be funded or not.
    Identify significant elements in customer mortgage application data that will ultimately lead to their mortgage being funded/declined.

Outcome: The successful solvers will have created the most accurate and robust predictive model to determine the propensity to fund based on the data provided by the Seeker.
Data

There are 20 fields in the dataset, which represent a past customer’s mortgage application data. The fields and descriptions are listed in Data tab in CAX_MortgageModeling_DataDictionary.docx

The dataset is divided into train and test set. The test set is further divided into public test and private test for public & private leaderboard scoring.

The following data files can be downloaded from data tab:

    CAX_MortgageModeling_Train.csv
    CAX_MortgageModeling_Test.csv
    CAX_MortgageModeling_SubmissionFormat.csv
    CAX_MortgageModeling_DataDictionary.docx

The variable to be predicted is “Result”.
Contest Tasks

The contest has 2 main tasks:

    Task 1: Public/Private Leaderboard Modelling Task
        In this task – solvers will use the given training data set to build their model and use the test set to submit scores in the submission format file provided. 
        Scores will be evaluated using macro F1 score and will be reflected on the task 1 leaderboard.
        This task will have auto leaderboard. Please only use the submission format provided in “Data” tab as a template to make your submission. 
        Public Leaderboard score is calculated on a subset of test set provided. Remaining is used to calculate a private leaderboard score which will be revealed at the end of the contest.
        5 Submission per day are allowed for each solver. Participants are encouraged to submit multiple entries before the deadline.
        Teams of size 4 are allowed (please note: contest once joined as part of team cannot be joined again as individual using same username)
    Task 2: Model/Report Submission Task (Mandatory)
        Conditional Winners will be determined using the private leaderboard from Task 1.
        Top 5 solvers will be selected from private LB to submit models/reports.

Please see “Task” Tab for Start and End dates for each task.

Submission File

You must submit a csv file (CAX_MortgageModeling_SubmissionFormat.csv) with the <CAX_Unique_id> and a <Result_Predicted>. Submission file should be same as provided. Files not adhering to the format will give error during submission.
Evaluation Criteria



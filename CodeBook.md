Variables:
subjectnumber: Numeric subject identifier
activity: Activity the subject was performing for each measurement.
          Factor variable with following levels:
            Laying
            Sitting
            Standing
            Walking
            Walking downstairs
            Walking upstairs

All other variables are measurements whose descriptions can be found in "features_info.txt"
Original data and codebooks taken from "UCI HAR Dataset" folder.

Cleaning:
Activity and feature labels were applied to the data, and the test and train data were appended to form a single dataset.
Only means and standard deviations of measurements were kept. The final dataset consists of the averages of these means and standard deviations, averaged across each subject and activity.

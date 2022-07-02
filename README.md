# Kickstarting with Excel
This analysis aims to find the optimal conditions for a kickstarter campaing using historical data from different projects that have been created in the kickstarter platform from 2009 to 2017. 

The information used for this dataset includes multiple media categories such as theater, music, film, videogames and journalism. Projects that have succeded or failed their funding goal, as well as cancelled projects are included in this dataset to avoid biased information.

## Overview of Project
![Outcomes vs goals](/Resources/Outcomes_vs_Goals.png)

This chart plots the amount of theater play kickstarter campaings that had a successful, failed or cancelled outcome depending on their goal amount range. To do this, all the relevant information from our dataset was filted using the countif function to get the appropriate information for each range and outcome category. The outcome percentage was obtained by dividing each outcome amount from the sumation of the 3 outcome categories.

![Outcomes vs launch date](/Resources/Theater_Outcomes_vs_Launch.png)

This chart plots the total count of theater-related kickstarter campaings depending on their launch month for years from 2009 to 2017. This was done by creating a pivot table from the kickstarter dataset and filtering this information according to the parent category which in this case is theater. This included the subcategories plays, musicals and spaces. 

Then, the shown pivot chart was created using the information from the pivot table. Plotting the outcomes in the columns and the count of outcomes as the values, against the created month. 

### Purpose
The purpose of this research is to provide our client Louise with a clear answer regarding when she should start her funding campaings, as well as the recommended goal for the theater category and the play subcategory, to maximize her chances of succesfully funding her play by analyzing historical data which is relevant to her current interest.

## Analysis and Challenges
The analysis was done using excel and a kickstarter dataset with information from 2009 to 2017 for the outcome of the project, the required and obtained amount, number of backers, start date, end date and a brief description of each kickstarter. By separating the data into parent categories and subcategories we were able to obtain the most relevant information for Louise's request. 

The relevant information, that was filtered according to the appropriate subcategory, was then plotted to show how the launch month, and the goal amount, relate to a kickstarter's success rate. 

### Analysis of Outcomes Based on Launch Date
Based on the analyzed information, Louise should get all her campaing ready to launch at the beggining of May, launching it on April would severly decrease the odds of successfully funding it. While launching it during June would not be as detrimental, May has the highest success rate for the theater related kickstarters.

### Analysis of Outcomes Based on Goals
According to the results that were obtained from the dataset, Louise's kickstarter should have a goal below 5000 dollars so her success rate regarding the goal amount does not drop below 70%. Kickstarters that have asked for more than 5000 dollars have a success rate around 50%.

### Challenges and Difficulties Encountered
A possible challenge for this project would be finding a common topic or interest that occurs within the successful and failed kickstartes. The dataset used for this project contains a brief description, which could be used to obtain the success rate of different themes in a theater play and get an estimated outcome for a play.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Funding campaigns launched on May and June have the highest success percentage, which is above 65%.
2. December and January have the lowest sucessful outcome percentage compared to the rest of the year.

- What can you conclude about the Outcomes based on Goals?
  1. Funding campaings that ask for less than $5000 dollars have the highest success rate. 
  2. Although the chart shows that plays between the 35000 to 44999 dollars has a success rate above 50%, the sample size is 9 campaings out of which 5 have succeded (4 out of 6 in the 35000 to 39999 range, and 2 out of 3 in the 40000 to 44999 range).

- What are some limitations of this dataset?
  1. The dataset for the Outcomes based on Goal relied on the play subcategory. For this specific section, the amount of campaings that asked for more than 15,000 dollars are few compared to the ones that asked for less than this amount (86 campaings required more than 15,000 dollars vs 961 that asked for less than this amount), thus the information for these campaings might not be entirely reliable.
  2. The dataset does not include information from 2017 to 2022, which means that current trends that could affect the interest in theater plays is not reflected in them.

- What are some other possible tables and/or graphs that we could create?
  1. We could include a theater play outcome per country to know which countries have the highest interest in watching or funding plays.
  2. Adding a column that shows the time it took to fund the kickstater (end date minus creation date) and its outcome would help us track the maximum expected time it takes to fund the campaings, as well as the threshold after which a campaing should be cancelled.
  3. We should also add a histogram to know what's the most common pledge amount range for theater plays.

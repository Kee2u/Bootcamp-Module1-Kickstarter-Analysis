# Kickstarting with Excel

## Overview of Project
Louise is a playwright who would like to start a crowdfunding campaign to fund her play. "Fever". This is her first fundraising campaign so she would like to understand what it would take for her campaign to be successful.

### Purpose
The purpose of the project is to analyze crowdfunding data using excel and to determine if there are specific factors that make similar campaigns successful. Lousie can use these insights to increase her probability of success.

## Analysis and Challenges
I began the analysis by looking at data from other kickstarter campaigns. The data included insightful information like goal and pledged amounts, country of origin, start and end dates, category and backers count.                     
1. **Analysis of Outcomes Based on Launch Date**
      - I created a pivot table and chart to see if there was a relationship between the month when a campaign was launched and its success. 
      ![Theater_Outcomes_vs_Launch](https://github.com/Kee2u/Bootcamp-Module1-Kickstarter-Analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png?raw=true)
      
2. **Analysis of Outcomes Based on Goals**
      - I also created a chart to see if there was a correlation between the goal amounts and outcome (success or failure) of the campaign.
      ![Outcomes_vs_Goals](https://github.com/Kee2u/Bootcamp-Module1-Kickstarter-Analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)
      
3. **Challenges and Difficulties Encountered**
     - A problem arose when I copied the COUNTIF() function from my initial cell to the other cells in the my Outcomes vs Goals table. It changed the column and row numbers            in the formula when I wanted them to stay constant. (Relative cell reference) I fixed this by adding dollar signs in front of the cell indexes. For example, if I                wanted the cell D14 to remain constant in my formula, I would replace it with $D$14. (Absolute cell reference) If I wanted the column D to remain constant while the rows        updated, I would add $D14 in my formula.

## Results

We can draw the following conclusions from looking at the graphs:
**Outcomes Based on Launch Dates graph**
1. The greatest number of successful projects were launched in the months of May and June. 
2. The number of failed projects remained fairly constant throughout the year. This means that other factors were responsible for their failure.

**Outcomes Based on Goals graph**
1. Campaigns which were less than $1000 were the most successful followed by campaigns that were between $45000 and $50000.

**Limitations of the dataset**
1. The kickstarter campaigns have probably included other features like exciting visuals. This is not reflected in the dataset but might be contributors to their success.
2. The genre of the plays are not included. This could be a factor to the plays' success since some genres are more popular than others.

**Other possible tables/graphs**
Here are some graphs that could be insightful:
1. The relationship between "spotlight" or "staff_pick" and outcome.
2. The relationship between the amount of time a campaign is live and its outcome.

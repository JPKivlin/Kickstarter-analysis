# Kickstarter-Analysis of Launch Dates & Funding Goals

## Project Overview:  

After Louise's play Fever missed its fundraising goal a request was made to assess the relationship between the Launch date of a Kickstarter project and it's funding Goal.  Using the provided Kickstarter dataset, an analysis was performed using Microsoft Excel as detailed below.  The results and conclusion of this analysis are included in this report   






## Analysis and Challenges
This analysis was performed using several of the tools/methods offered within excel.  Those tools included pivot tables, line graphs, and data extraction using formulas.  Details pertaining to the structure of the analysis, as well as challenges that were encountered, are explained below.

#### Analysis Details

  1.  Extracted the year from each launch data (Date Created Conversion Column) to populate a new column [Screen shot of Year Formula](resources/Year_Column.png)
  2.  Created a pivot table of outcomes by Launch Date and filtered the data for data only pertaining to theaters [Outcomes by Launch Date Pivot Table](resources/Pivot_Launch_Outcomes.png)
  3.  Based on the Pivot table a line chart was created to visualize the number of outcomes (successful/failed/canceled) over the course of the year by month [Theater Outcomes by Launch Date Chart](resources/Theater_Outcomes_vs_Launch.png)
  4.  Created new worksheet labeled "Outcomes Based on Goals"
  5.  Using the goal ranges provided, the countifs() function (see screen shot) was used to populate the table  [Outcomes Based on Goals](resources/Outcomes_Goals_Table.png)
  6.  Based on the Outcomes Based on Goals table a line chart was created to visualize the number of outcomes (successful/failed/canceled) based on the established goal ranges [Outcomes by Goals line chart](resources/Outcomes_vs_Goals.png)

#### Challenges
  1.  To make the code more efficient for the "Outcomes Based on Goals" worksheet I created a small reference table to the right.  That was tricky to get working at first, but I was able to achieve the desired outcome.
  2.  Other challenges could include using the logical operators in the Countifs function, difficulty sorting/filtering the pivot table data, or other formula writing issues.


## Results
The following conclusions have been interpreted from the results of this analysis:

#### Theater Outcomes by Launch Date
Based upon the [Theater Outcomes Based on Launch Date](resources/Theater_Outcomes_vs_Launch.png) line chart, it appears the best time to launch a Kickstarter campaign would be the 2nd or 3rd quarter of the year.  Specifically, the best month overall to start a Kickstarter campaign based on this data would be May.  As for failed outcomes, the number of failures by month is relatively steady throughout the year.

#### Theater Outcomes Based on Goal
After reviewing the results of the [Theater Outcomes Based on Goal](resources/Outcomes_Goals_Table.png) line chart, the most apparent conclusion is that goals of greater than $4,500 have little chance of success (13% or less).  The greatest chance for success would be a campaign goal of less than $5,000.

Based on the conclusions above, a Kickstarter Theater related campaign launched in May with a goal of less than $5,000 has the greatest chance for success based upon the data analyzed.  Some of the limitations of this data set include the location data, which is only specific to the country of the campaign, and whether this assessment holds true year after year.  To better assess the validity of these conclusions, additional line charts by year could be created to further support both the goal and launch data conclusions.

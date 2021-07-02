# Kickstarter-Analysis of Launch Dates & Funding Goals

## Project Overview:  

After Louise's play Fever missed its fundrasing goal a request was made to assess the relationship between the Launch date of a Kickstarter project and it's funding Goal.  Using the provided Kickstarter dataset, an analysis was performed using Microsoft Excel as detailed below.  The results and conclusion of this analysis are included in this report   






## Analysis and Challenges
This analysis was performed using several of the tools/methods offered within excel.  Those tools included pivot tables, line graphs, and data extraction using formulas.  Details pertaining to the structure of the analysis, as well as challenges that were encountered, are explained below.

#### Analysis Details

  1.  Extracted the year from each launch data (Date Created Conversion Column) to populate a new column [Screen shot of Year Formula](resources/Year_Column.png)
  2.  Created a pivot table of outcomes by Launch Date and filtered the data for data only pertaining to theaters [Outcomes by Launch Date Pivot Table](resources/Pivot_Launch_Outcomes)
  3.  Based on the Pivot table a line chart was created to visualize the number of outcomes (successful/failed/canceled) over the course of the year by month [Theater Outcomes by Launch Date Chart](resources/Theater_Outcomes_vs_Launch)
  4.  Created new worksheet labeled "Outcomes Based on Goals"
  5.  Using the goal ranges provided, the countifs() function (see screen shot) was used to populate the table  [Outcomes Based on Goals](Outcomes_Goals_Table)
  6.  Based on the Outcomes Based on Goals table a line chart was created to visualize the number of outcomes (successful/failed/canceled) based on the established goal ranges 

#### Challenges



## Results

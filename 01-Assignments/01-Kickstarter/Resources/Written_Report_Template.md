# Kickstarting with Excel

## Overview of Project
Import functions or data into table and that return output.
2. Apply Filters, conditional formatting, and formulas.
3. Calculator summary statistics such as measures of central tendency, standard deviation, and variance.
4. Generate and interpret pivot tables.
5. Emprise data to identify outliers in datasets.
6.Interpret common Excel visualizations. 

### Purpose
As part of a class assignment for the UT Data Boot camp, an initial analysis of Kickstarter data was conducted to assist 
  a client to determine the timing of her fundraising goal for a play. 
  After falling short of her fundraising goal, she asked for a follow up analysis. 

## Analysis and Challenges
  Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Launch Date
  Due to the client's interest in the theater data, the data was filtered by that category. 
  The number of live outcomes were nominal and were filtered from the data set.

### Analysis of Outcomes Based on Goals
  Due to the nominal number of live outcomes, the data was again filtered from the data set. 
  The client's main interest is in the plays subcategory, so an additional filter was applied. 
  The goals were then binned into groups of $5000. The total number of successful, failed, and
  canceled outcomes were calculated for each bin and then converted into percentages.                                                                                                                                                 

### Challenges and Difficulties Encountered
  The percentage of canceled projects had all zeros, which could have indicated a calculation error.
  The formulas were checked and verified for accuracy. The raw data was filtered to confirm 
  that no canceled plays existed.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1.Viewing the line graph, the key months to launch a successful theater project are May   
  and June, which declines through the end of the year.
  2.There are also very few canceled theater projects.

- What can you conclude about the Outcomes based on Goals?
  From the graph, the most successful percentages of outcomes are projects with goals that are less
  than $5000 goals or between $35000 and $50000.


- What are some limitations of this dataset?
  There is limited data on canceled theater project and There were no examples of canceled plays in the subcategories.
- What are some other possible tables and/or graphs that we could create?
  1. We could create a new calculaterd field that counts the number of months of days between the launch and dedline dates and cross the with the number of outcomes, and then turn that into a marked line graph. 
  2. In both analyses, the spotlight and staff pick were not investigated for impact on outcomes. 

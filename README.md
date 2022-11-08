# **Kickstarting with Excel**  

 
 

  

  

 
 

## **Overview of Project**  

 
 

#  

 
 

### **_Purpose_**  

 
 

##  

 
 

This is an analysis of numerous Kickstarter campaigns to predict the optimal launch date and fundraising goal to achieve success. First by analyzing how different Kickstarter campaigns fared in relation to their launch dates. Second by analyzing how different Kickstarter campaigns fare in relation to their funding goals. This is done by using formulas, PivotTables, PivotCharts, tables, and more. By visualizing different sets of data, it provides more efficient representation and coherence.  

 
 

#  

 
 

#  

 
 

## **Analysis and Challenges**  

 
 

#  

 
 

### **_Analysis of Outcomes Based on Launch Date_**  

 
 

##  

 
 

To perform this analysis, first a PivotTable was created from the whole of the data. The PivotTable was then filtered by the parent category of _“theater”_ to create a PivotChart based upon how the following outcomes: successful, failed, and canceled, compared to the date of launch. The value being the count of outcomes _(count of successful, failed, and canceled)_.  

 
 

  

  

 
 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/48533925/198401492-f6602d66-ef55-4208-9cfa-48ffb80aa59d.png)  

 
 

  

  

 
 

Looking at the PivotChart, we can observe the following:  

 
 

- The _highest_ count of successful Kickstarter campaigns were launched in the months of May, June, and July with February, April, and August not far behind.   

 
 

- The _lowest_ count of successful Kickstarter campaigns were launched in the months of January, March, September, November, and December.  

 
 

- The count of failed Kickstarter campaigns follows a _similar trend_.   

 
 

#  

 
 

### **_Analysis of Outcomes Based on Goals_**  

 
 

##  

 
 

A similar process was performed to create another PivotChart, however, this chart is not filtered by category like the previous, rather, by percentage of an outcome based on the goal range.  

 
 

#### _For example, we can see that out of all Kickstarter campaigns with a goal range of less than $1,000, %76 was successful and %24 failed._  

 
 

  

  

 
 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/48533925/200367247-87be6576-7c92-4e4a-aabe-99f13955025d.png)  

 
 

With the above PivotChart, the following can be observed:  

 
 

- Kickstarters with goals of **$45,000 - $49,99** have the highest observable percent of successful and the lowest observable percent of failed.  

 
 

- Kickstarters with goals of **$50,000 or more** have the second highest percent of success and second lowest percent of failure.  

 
 

- Kickstarters with goals of **$25,000 - $29,999** have the third highest percent of success and third lowest percent of failure.  

 
 

- Kickstarters with goals of **less than $1,000** have the fourth highest percent of success and fourth lowest percent of failure.  

 
 

#  

 
 

### **_Challenges and Difficulties Encountered_**  

 
 

##  

 
 

**Incorrect Observation of Data Visualization** 

 
 

While observing the "Outcomes based on Goals" chart, my eyes instantly took note of the observable pattern and shape the graph made. This caused me to investigate further into the graph. In conclusion, it has no pattern. This is because the lines that connect each new category carry no weight as far as value. Until I came to this conclusion, making a correct observation would prove difficult. 

 
 
 

#  

 
 

## **Results**  

 
 

  

  

 
 

**The following are two conclusions I can provide for "Outcomes based on Launch Date."**  

 
 

1. Launching a Kickstarter campaign in the month of May, June or July would be recommended.  

 
 

2. May, June, and July also have the largest gap between successful and failed, making the majority of each month's total a successful majority.  

 
 

- Additional observation: we cannot make any decisions based off the values of the canceled outcomes because we do not know why they canceled or if there was financial gain or loss.  

 
 

  

  

 
 

**Outcomes based on Goals Conclusion**  

 
 

1. It may seem obvious which goal range to choose, however, with this visual graph alone, it would not be possible to determine how many Kickstarter campaigns had each goal. _In other words, if the best choice (visually) only had 1 or 2 campaigns, it is not a large enough amount to confidently choose a campaign range, however, if the same choice had a number higher than most, one would be more inclined to make that choice._  

 
 

   - It would be best to verify the outliers, and then choose a range with the largest gap between successful and failed while keeping in mind the count of campaigns for each goal range.  

 
 

  

  

 
 

**Limitations of this dataset**  

 
 

  

 
 

- Cannot determine how many Kickstarter campaigns had each goal based on the visual data alone in the "Outcomes Based on Goal" graph.  

 
 

    - Which means there is no way to tell if there is an outlier present when making a financial decision.  

 
 

  

  

  

**Possible tables and/or graphs I would create**  

 
 

- A graph of the average length of successful campaigns in each month when choosing a launch date.  

 
 

- A graph showing the number of campaigns for each goal range.  

 
 

- A cluster graph to show a combination and variation of these graphs.  

 
 

 

 
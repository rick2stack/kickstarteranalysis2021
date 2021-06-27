# Kickstarting Challange (Module 1)

## 1 Overview of Project
Louise's play "Fever" came close to its fundraising goal. Louise wants a visual summary, from the Kick Starter data provided, to aid her decision on the best launch date and fundraising goal for her new campaign.    

### 1.1 Purpose
The purpose of this excercise is to examine how each fundraising campaign fared in relation to their launch date and their funding goals. This excerise will only focus on Louise's "Plays" category and not on the other types of fundraising categories. 

## 2 Analysis and Challenges
### 2.1 Analysis
The analysis consisted of two major exercises:  
- The first excercise involved comparing the launch dates (per month) of fundarisin Plays to outcomes of the campaign. 
- The second excercise involved comparing the outcomes of each compaign by the goal size (per $1k and $5K interval).  
* Outcomes were measured by the following: "successful", "failed", "canceled", or the play could be "live" and therefore the outcomes were yet to be determine.  

### 2.2 Challenges
 Most of the challanges encountered with excel were finding the correct syntax for the "countifs()" and trivial knowledge about the "datum date" for the "Date Created Conversion".   
 
 - The "Countifs()" formula required a logic command such as the "greater than" or "equal to". However, when I place the logic command it was not working and recieved an error.  A quick google search showed that the syntax for that command required quotation marks, see image below.
 ![Challange_with_Countifs](C:\Users\rdsm1\Documents\GitHub\kickstarteranalysis2021\Resources\Challange_with_Countifs.png). 
 
 - The  "Date Created Conversion" required the serial number time stamp to be convert to a nice date format such as dd/mm/yyyy.  The serial number which is a time stamp in seconds could be converted to quantity days with simple math.  However, the conversion only gave a quantity of days and therefore it required a datum date (a.k.a a start date) of 1/1/1970, see image below. 
![Challange_with_Date_Conversion](C:\Users\rdsm1\Documents\GitHub\kickstarteranalysis2021\Resources\Challange_with_Date_Conversion.png). 

### 2.3 Analysis of Outcomes Based on Launch Date
 Based on the Analysis of outcomes vs. launch date line graph, we can make two conclusions. 
 ![Theater_Outcomes_vs_Launch](C:\Users\rdsm1\Documents\GitHub\kickstarteranalysis2021\Resources\Theater_Outcomes_vs_Launch.png)
 - The first conclusion is that December is the best time for a succesfull campaign.  
 - The second conclusion is that after May the number of succesfull campaigns tapers off, making December the worst time for a succesfull campaign.  

### 2.4 Analysis of Outcomes Based on Goals
Based on the Analysis of Outcomes vs. Goals line graph we can make one conclusion.
![Outcomes_vs_Goals](C:\Users\rdsm1\Documents\GitHub\kickstarteranalysis2021\Resources\Outcomes_vs_Goals.png)
- There is a higher probability that the campaign will be succesfull the higher the campaign goal.

## 3 Limitations of Data
### 3.1 Limitations for the Outcomes vs. Launch date
The data for outcomes vs. goals has some limitations: 
- The data set is not specific to a country, so some of the data could vary depending on the location of the fundraising event.
### 3.2 Limitations for the Outcomes vs. Goals
- The graph does not show specific sample size for each goal bracket.  When looking deeper into the data, there is a low sample size for goals over $25K. That is probably why the graph shows a higher fluctuation after $25K.
- The second limitation is that the data is not filtered by country.  So the data shown in the line graph does not take the actual value in $USD.  
### 3.3 Possible Additional Tables
- In order to have a more accurate representation of the Outcomes vs. Goals graph, we would need to convert all non-USD currencies into USD currencies and create a new graph with only USD currencies for Outcomes vs. Goals. 
- The Outcomes vs. Goals graph could have a supplement graph, such as histogram for each goal bracket.  In this scenerio each outcome would get its own historgram. 



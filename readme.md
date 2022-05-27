# PROJECT: BUILD DATA DASHBOARD

In this project, I explored Poverty rates in US Counties (2015) using Tableau.

## INSIGHT 1

https://public.tableau.com/app/profile/mark.edosa/viz/AveragePovertyRatebyState/Sheet1?publish=yes

### Summary

The bar chart shows the average poverty rates at the various states of the United States in 2015.  Apparently, Puerto Rico had the highest average poverty rate (49.37%), followed by Mississippi (25.72%).
At the other end of the spectrum were New Hampshire (10.17%) and Connecticut (9.40%).

### Design

I chose a horizontal bar chart because positions are easy to see. Also, the user won’t have to tilt her head while viewing the state names. A single blue color was chosen because it does not interfere with the information on the chart.
_Resources:_ N/A

## INSIGHT 2

https://public.tableau.com/app/profile/mark.edosa/viz/AveragePovertyRatevs_AverageUnemploymentRatebyState/Sheet2?publish=yes

### Summary

The scatterplot shows the relationship between the average poverty rate and average unemployment rate in US at 2015. There seemed to be a linear relationship between the two variables (an increased average unemployment rate seems to associated with an increased average poverty rate)
Puerto Rico (an outlier), Mississippi, Arizona and Alabama (upper-right quadrant) led the highly poor, highly unemployed group while North Dakota and Nebraska (lower-left quadrant) led those with the least poverty and unemployment rates. Nebraska stood out as a state with below average poverty rate and above average unemployment rate.

### Design

Scatterplots are great way to visualize relationships (trends) between two numeric variables.  The plots were colored so that we can easily distinguish one state from another. The average lines were added so we can further group the states (or tell more stories) based on the average poverty rate and average unemployment rate.
_Resources:_ N/A

## INSIGHT 3

https://public.tableau.com/app/profile/mark.edosa/viz/AverageIncomeperCapitalbyState/Sheet3?publish=yes

### Summary

The map shows the average per capita income for each state. Connecticut (37,025), New Jersey (36,085) and Massachusetts (35,554) were among the highest while Puerto Rico was the lowest (9,618)

### Design

With a map, we quickly get an overview of the average per capita income across the states. The varying shades of color shows us differences/similarities in per capital income across the states.
_Resources:_ N/A

## INSIGHT 4

https://public.tableau.com/app/profile/mark.edosa/viz/10CountieswithHighestLowestChildPovertyRates/Sheet4?publish=yes

### Summary

This time I explored child poverty rates in the counties of various states. Using Puerto Rico as an example, we see that Maricao County had the highest rate of child poverty (81.60) while Toa Alta had the lowest child poverty rate (35.50).
In Alabama, Greene County had the highest child poverty rate (67.00) while Shelby had the lowest child poverty rate (10.40).

### Design

Since there a lot of counties in some states, it was necessary to get at the least the top 10 and bottom 10 in a bar chart to avoid clutter as well as promote easy visualization. A blue-orange color (friendly to those who are color blind) was chosen to easily demarcate the top 10 from the bottom 10. A state filter was added so that we see the top/bottom 10 counties for any state of interest or for the entire country.
_Resources:_ The code for the Top/Bottom 10 calculated field  was taken from https://www.rigordatasolutions.com/post/2018/02/03/tableau-tips-topbottom-n-members-indexsizeinteger#:~:text=Sort%20the%20chart%20in%20descending,Bottom%2010%20profitable%20customers'%20respectively.

## INSIGHT 5

https://public.tableau.com/app/profile/mark.edosa/viz/OverviewofPovertyRateandperCapitalIncomeinUS2015/Dashboard?publish=yes

### Summary

This dashboard combines insights 1 – 3 above enabling the viewer get a quick glance of the broader picture surrounding poverty rate at the US in 2015.

### Design

 I chose a dashboard here because it gives a broader story from a collection of findings (charts). The user doesn’t have to navigate through individual charts to get the general idea behind the analysis.
_Resources:_ N/A
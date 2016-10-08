# d3-project
project d3 for udacity.

Visualization can be found on bl.orgs.org found here: https://bl.ocks.org/crivera2013/raw/62335a5035a731b9cadff8a067447112/

#Summary:
I created a collection of multi-line line graphs showing loan disperment data from Prosper during, and after the 2009 financial crash.  Each line represents a different collection of loans from Prosper Loans (Safe, Moderate, Risky) and showing how each group was effected over each quarter.  The table is be dynamic and can switch between 4 time-series graphs:

1. A graph showing the number of loans per quarter Prosper dispersed to each risk group.
2. The average monthly payments of loans dispersed to each risk group
3. The average amount of loan dispersed to each risk group.
4. The average credit score for each risk group.

The graph shows that Prosper Loans becomes far more exacting in their loan dispersment process by increasing the number of safe and moderate loans as well as increasing the requirements for loans in every risk level after the crash.


#Design
I chose to create a multi-line graph as this project includes time series data.  I also decided to use the colors red. blue, and green associated with Risky, Safe, and Moderate so as to highlight that risky loans are high risk and "bad" while the other two categories are safer, better loans to be dispersing.  I also included a dotted line to show when the Financial Recession "officially ended" so that the audience can understand why there is an uptick in values across the board after April 2009. 

#Feedback
Peer Design Critique #1:
"Loans per quarter goes off the chart" - Evan Liang (friend)

Due, to the size limits of the graph on the webpage, it couldn't properly scale the number of "safe" loans during the later part of the data with data point values greater than 6000, Since the scaled Y axis, is only to 4000, the values went off the chart and bled into the title.  Since the point of the graph was made, I curtailed the two last datapoints to be 4000 instead so as to not distract from the chart's story.

Peer Design Critique #2:
"Am I supposed to know what a "risky" loan is compared with everything else?" - Valerie Piro (friend)

While, I thought my legend was descriptive enough with the larger bold print "Risky Loans", this critique showed that it was not the case.  As such I added smaller text in the legend to better describe the definition of "Risky Loans" and the other two by what their credit ratings are.

Peer Design Critique #3:
"The buttons aren't aethetically pleasing, you should use a drop down menu" - Ashutosh Singh (Udacity 1-1 tutor)
"OH I CAN TOGGLE IT? I had no idea what I was looking at since there were four bars below the graph." - Sarah Pereira (friend)

Originally, I had 4 buttons stacked vertically below my graph which were used to toggles to update the graph with different data.  However, it was neither aethetically pleasing, and apparently confusing to someone just looking at the graph, so I changed the buttons into a drop down menu.

#Sources:
http://www.w3schools.com/howto/howto_css_dropdown.asp  for dropdown menu

https://bl.ocks.org/mbostock/3884955  for multiple line graphs

https://bl.ocks.org/d3noob/7030f35b72de721622b8  for update buttons

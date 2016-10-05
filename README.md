# d3-project
project d3 for udacity

Goal: create a collection of multi-line line graphs showing loan disperment data from Prosper Loans before, during, and after the 2009 financial crash.  Each line represents a different collection of loans from Prosper Loans (Safe, Moderate, Risky) and showing how each group was effected over each quarter.  The table will be dynamic and can switch between 4 graphs:

1. A graph showing the number of loans per quarter Prosper dispersed to each risk group.
2. The average monthly payments of loans dispersed to each risk group
3. The average amount of loan dispersed to each risk group.
4. The average credit score for each risk group.

The graph shows that Prosper Loans becomes far more exacting in their loan dispersment process by increasing the number of safe and moderate loans as well as increasing the requirements for loans in every risk level after the crash.

Currently, the data does not fully refresh and scale whenever I press a button.  If i make it a single line graph, the data updates and the scales change just fine, but after adding multi-lines, only one line changes and the y-axis scale does not change.

I am also trying to add a dynamically changing Y Axis label, a dynamically changing Title for each graph, and a Legend showing each line.


# Green Stock Analysis

## Overview of Project
The purpose of this project was to analyze stock market data to determine objective insights and make investment recommendations.
The second purpose of this project was to practice refractoring existing functioning code to make the above purpose more efficient, so that it could be expanded from the existing data set of a dozen stocks to potentially thousands.

## Results
### Stock Results
The results show that in 2017 all the stocks with the lone exception of TERP showed positive returns.
Alternatively, in 2018 all the stocks in the dataset were negative, with the two exceptions of RUN and ENPH, which were positive.
### Refactoring Results on Run Times
Running the original code resulted in run times that were close to each other for 2017 and 2018:  0.621 and 0.633 seconds respectively.
Similarly, the refactored code resulted in run times that were close to each other for 2017 and 2018:  0.078 and 0.070 seconds respectively.  These are shown in linked the linked images.

It is noteworthy that on average the refactored code was approximately 89% faster than the original code.  These time savings are significant.


## Summary
1:  What are the advantages or disadvantages of refactoring code?
The advantages or refactoring code are the improved efficiencies; in the case time savings of approximately 89%.
In addition, another advantage is that by going through the code again, there are more opportunities to debug potentially missed issues, as well as more learning opportunities to practice more efficient code.
The only disadvantage of refactoring code is the increased initial time commitment to go through code that already works without a guarantee of improved efficiencies.

2:  How do these pros and cons apply to refactoring the original VBA script? 
In this case, the initial extra work put into refactoring the original VBA script was more than offset by the advantage of the improved efficiencies of 89%.

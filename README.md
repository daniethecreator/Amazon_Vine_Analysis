# Amazon_Vine_Analysis

## Overview of the analysis:

The overall objective of this project was to look at Amazon reviews regarding Automative and use Pyspark to peform the ETL process by extracting the data, transforming the data, and connecting to the database that was generated through the AWS webserver. Once the reviews were converted into a dataframe, the goal was to determine if there is favorable review bias from the Vine members in the data set.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions:

* How many Vine reviews and non-Vine reviews were there?
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Summary: 
Looking at the results, it is safe to assume that the data does not appear to have a more favorable bias because the percentages are both not significantly different thant the 52%, the paid are slightly higher at 53% and the unpaid reviews are slightly lower at 48%, but the difference is not enough to suggest a bias one way or the other. The next step would be to analyze another data set from the Amazon Reviews and see if it follows the same pattern or if there are any significant differences. 



# **Online Retail analysis using PySpark**

### #pyspark #sql #visualization #matplotlib

# Introduction

This is my practice as part of a self-study course to learn PySpark. PySpark is one of the most powerful libraries for working with large-scale data sets and is used for real-time processing tasks. In the scope of this analysis, PySpark library is applied for research a transaction dataset taken from the UCI website (you can download the dataset [**here**](https://archive.ics.uci.edu/dataset/352/online+retail)).

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Despite the period time of dataset, it doesn’t matter because my goal is to practice using PySpark to identify patterns in online trading activity by answering a number of questions:

1. In which countries did the company earn high revenues?

2. At what time of year did the company receive high income? 

3. At what time of day is purchasing power higher than at any other time?

# Structure
The analysis consists of 4 parts:

1. Import the necessary libraries and data
2. Pre-processing of data
3. Generate table result using SQL query
4. Visualization

# Conclusion
- In which countries did the company earn high revenues? Since this platform operates mainly in the UK, the total revenue here was much higher than in any other country (it reached 84% of the whole revenue of the company).
- At what time of year did the company receive high income? The highest total income was observed in the 4th quarter, which amounted to 38% of the company’s total revenue and was almost twice as high as the first quarter. Purchasing power especially increased in November, when buyers were preparing gifts for important holidays of the year: Christmas and New Year.
- At what time of day is purchasing power higher than at any other time? The last graph shows the total amount of money received by the company during the day. What's interesting here is that shoppers spent lots of money on products at 10 and 12 a.m. rather than in the evening, when people have time to relax after a hard-working day.

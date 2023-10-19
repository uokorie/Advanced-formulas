# Advanced-functions
**Application of Advanced functions in Excel.

**Advanced Excel functions for data analysis are more sophisticated functions that allow users to perform complex calculations and manipulate data effectively. 
These functions are especially valuable for in-depth data analysis.

**Task   Using the Sales Data, 
Calculate:
The average revenue generated from each sale of ‘Paseo’
The number of sales made in the Government and Midmarket segment
The total revenue generated from the sales of ‘Montana’ in Canada
In which Country, Segment and Month was the highest unit of goods sold?
What is the total profit made in December?

The underlisted functions were applied to achieve the results for the tasks above.

Average Revenue generated from Paseo =AVERAGEIF(L2:L701, "Paseo",A2:A701)

The Number of Sales made from Government and Midmarket Segment =SUM(COUNTIF(O2:O701,{"government","Midmarket"}))

The total revenue generated from the sales of ‘Montana’ in Canada =SUMIFS(A2:A701,D2:D701,"Canada",L2:L701,"Montana")

The Country highest units is sold =VLOOKUP(S14,C2:D701,2,FALSE)

The Segment that Recorded the highest units of sales =VLOOKUP(S14,C1:O701,13,FALSE)

The month when the Highest Unit of Goods was sold =VLOOKUP(S14,C1:J701,8,FALSE)

The total Profit recorded in December =SUMIF(J1:J701,"December",M2:M701)



# Market Basket Analysis

Market Basket Analysis is considered by many retail industries to recommend items for their customers based on their buying patterns. Association rules are generated as part of this process. This project aims to generate association rules based on customers purchase history with fixed support and confidence levels.

**Input**

Each user's purchase items list is taken as input in the form of a tab-delimited-text file.

**Method**

Aprior Algorithm is implemented to get the association rules. The main property of this algorithm says 'All subsets of a frequent itemset are perfect, but the converse may not be true. With the available data, frequent item sets of n-size(1,2,3,4) are identified with predefined support. Later, association rules are generated with predefined confidence set to 90%.

**Ouput**

The generated association rules are saved to a text file.

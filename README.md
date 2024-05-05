# Market-Basket-Analysis-Using-R
Frequent itemset mining / Association analysis. -Data mining technique

## Overview
Market basket analysis is a data mining technique that analyzes patterns of co-occurrence and determines the strength of the link between products purchased together. We also refer to it as frequent itemset mining or association analysis. It leverages these patterns recognized in any retail setting to understand the behavior of the customer by identifying the relationships between the items bought by them. To put it simply, market basket analysis helps the retailers know about the products frequently bought together so as to keep those items always available in their inventory.
## Key Concepts   
 
- Itemset: A group of items purchased together in a single transaction.                               
- Support: The proportion of transactions containing an itemset.            
- Confidence: The probability of buying a consequent itemset (B) given the purchase of an antecedent itemset (A).
- Lift: The ratio of the confidence of a rule to the overall support of the consequent itemset. It indicates if the presence of A strengthens the likelihood of buying B together.

## Algorithm    
    
Apriori: A widely used algorithm for frequent itemset mining. It employs an iterative approach to discover frequently occurring itemsets and generate association rules.
## Benefits of Market Basket Analysis

- Improved Sales and Revenue: By identifying frequently bought-together items, retailers can strategically place them, recommend complementary products, and develop targeted promotions.
- Enhanced Customer Experience: Personalized recommendations based on purchase history can lead to a more satisfying shopping experience.
- Optimized Inventory Management: Market basket analysis helps identify popular and slow-moving items, allowing for better inventory control.
- Data-Driven Decision Making: Retailers can leverage insights to make informed decisions about product placement, marketing campaigns, and store layout.
  Getting Started with R Packages

### Several R packages implement market basket analysis algorithms. Popular choices include:

`arules`
`basketMarket`
`mlxtend`
These packages offer functions for data preparation, frequent itemset mining, association rule generation, and visualization of results.

_Sources and Refrence - https://www.turing.com/kb/market-basket-analysis_

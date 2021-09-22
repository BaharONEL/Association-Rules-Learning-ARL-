# Association-Rules-Learning-ARL-
Association Rule learning is a rule-based machine learning technique which is used to find interesting relationships and associations hidden in large data-sets. 
This rule shows how frequently an itemset occurs in a dataset or transaction.

Market Based Analysis is one of the important methods used by large relations to show associations between items. 
Given a set of transactions or dataset, we can find rules that will predict the occurrence of specific item based on the occurrences of other items in the dataset.

Association Rule Learning works on the concept of if/then statements. These statements expose the associations and relationships between independent data and relational or other data in the dataset. These rules are used to identify the relationships between the objects or items which are generally used together.

The two basic patterns or functions used in Association rule Learning are Support and Confidence. The method identifies similarities and rules formed by decomposing data for frequently used if/then patterns. Association rules are usually used to satisfy a user-specified minimum support and a user- specified minimum resolution or determination simultaneously.

* Support :
Support indicates how frequently an item or item-set appears in the dataset or transaction.

* Confidence :
Confidence indicates how frequently a rule is found to be true.

* Lift :
Lift (A →B) indicates the rise in probability of occurrence of B when A has already occurred.

## Apriori Algorithm :
Apriori algorithm is a standard algorithm in Association Rule Learning in Data mining. It is used for drawing familiar item sets and their relevant association rules. It is designed to perform on a database.

It is very important for effective Market Basket Analysis and it helps in understanding the businessman that which items customers will buy together. It has also been used in healthcare field for the discovery of adverse drug reactions. It generates association rules that shows what are all combinations of medications and patient characteristics which will help in effective drug delivering.

 ## Business Problem :
Products to users at the basket stage
make a suggestion.

 ## Dataset Story : 
Online Retail II
The dataset named is a UK-based online sales
store's sales between 01/12/2009 and 09/12/2011
contains.
The product catalog of this company includes souvenirs. promotion
can be considered as products.
There is also information that most of its customers are wholesalers.


 ## Variables :
• Invoice : Invoice Number (If this code starts with C, it means that the transaction has been canceled)

• StockCode : Product code (Unique number for each product)

• Description : Product name

• Quantity : Number of products (Indicates how many of the products in the invoices have been sold)

• InvoiceDate : Invoice date

• UnitPrice : Invoice price (Sterling)

• CustomerID : Unique customer number

• Country : Country name

• UnitPrice : Invoice price (Sterling)

## Dataset : 
https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

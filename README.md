# KeepUp Data Science Interview Challenge
For this exercise, you will analyze a dataset from Amazon. The data format and a sample entry are shown on the next page.

### A. (Suggested duration: 90 mins)
With the given data for 548552 products, perform exploratory analysis and make suggestions for further analysis on the following aspects.

1. **Trustworthiness of ratings**  
Ratings are susceptible to manipulation, bias etc. What can you say (quantitatively speaking) about the ratings in this dataset?

2. **Category bloat**  
Consider the product group named 'Books'. Each product in this group is associated with categories. Naturally, with categorization, there are tradeoffs between how broad or specific the categories must be.  
For this dataset, quantify the following:  
a. Is there redundancy in the categorization? How can it be identified/removed?  
b. Is it possible to reduce the number of categories drastically (say to 10% of existing categories) by sacrificing relatively few category entries (say close to 10%)?  

### B. (Suggested duration: 30 mins)
Give the number crunching a rest! Just think about these problems.
1. **Algorithm thinking**    
How would build the product categorization from scratch, using similar/co-purchased information?

2. **Product thinking**    
Now, put on your 'product thinking' hat.    
a. Is it a good idea to show users the categorization hierarchy for items?  
b. Is it a good idea to show users similar/co-purchased items?  
c. Is it a good idea to show users reviews and ratings for items?  
d. For each of the above, why? How will you establish the same?  

-------------------------

### Data entry format:
• __Id__: Product id (number 0, ..., 548551)    
• __ASIN__: Amazon Standard Identification Number  
• __title__: Name/title of the product    
• __group__: Product group (Book, DVD, Video or Music)  
• __salesrank__: Amazon Salesrank  
• __similar__: ASINs of co-purchased products (people who buy X also buy Y)  
• __categories__: Location in product category hierarchy to which the product belongs (separated by |, category id in [])  
• __reviews__: Product review information: time, user id, rating, total number of votes on the review, total number of helpfulness votes (how many people found the review to be helpful)  

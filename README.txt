 Popular Engagement Ring Styles on BlueNile.com



 ## Reaserch Questions:

 1. What kind of engagement ring styles are popular on BuleNile.com?
    
    - What kind of gold is more popular?
    - Designs with or without side stone settings are more popular?
    - What price range are the best sellers at?
    - Has customers' choice changed over time?
    - Any difference in peferrence among segment groups?

2. What are the other factors contribute to sales?

    - Do popular styles have higher rating too?
    - Does reason of buying differ for popular and non-popular styles? 
    - Any pattern changed over time? Has COVID-19 influenced the business?


Research Goal: provide insights for production and sales team:
    
    1. Designers and Buyers: Do we have enough stock?
    2. What should be emphasized in marketing?


## Assumptions

1. The reviews are fair representation of selling.

   One review equals one sale.
   The more popular a style is, the heavier weight the style has in all sort of analysis.


2. The reviews are geniue and valid resources to reflect customers' true opinion on the product.

   This might not be the case since engagement rings are expensive purchases. It is more likely for a unsatisfied customer to return the purchase rather than keep it and complaint online, therefore we don't really see much of the dislikes from customers. But at least we can find out about what the good things customers like about the brand and the product.


### Define the popular styles

For each styles, there could several diffrent type of gold options, such as 14K White Gold, 18K Gold, or Platinum. 

The top 10 most popular styles of various gold options consist of 6260 rows of data, roughly consist 48.8% of all dataset. There for we identify these ten styles as the "popular styles" in the analysis.

There are 144 styles have no review data. In this case, we assume they are all 'non-popular' and kept in the analysis.


### Columns

The original scraped data frame include 13 columns, they are:

'product_name' : name of the ring styles
'avg_rating': average rating of all reviews for one style
'price': price of the item
'side_stone_weight': carat weight of the side stones
'metal': type and color of gold
'user_name': reviewer's name 
'verified': whether the reviewer is verified as an existing customer
'stars': reviewer's rating, ranging from 1 to 5.
'date': date of the review
'location': location of the reviewer
'expert_consulted': has the customer consulted an expert before making the purchase
'recommended': whether the reviewer recommend BlueNile to others
'why_buy': reason of making the purchase. a set of answers are provided for selection.

During the analysis, 4 more columns are created to facilitate the data manipulation.

'popular': whether the style is one of the top 10 best sellers.
'color': color of gold: white, yellow, rose and mix.
'gold': type of gold: Platinum, 14K, 18K, and mix.
'is_usa': whether the reviewer is in the USA or from other countries. 

### Data size and missing data

The original data set include 12829 rows. 3 rows were deleted due to incorrect information. 
There are 144 styles have no review data. They are kept in the analysis. 
Each columns are checked and cleaned individually to make up the missing/incorrect information. No more rows are exclued in the analysis.

For the unverified customer, by checking the average rating and individual stars given to the product, no significant difference in the distribution was found. Therefore, these 149 rows were kept in the analysis too.
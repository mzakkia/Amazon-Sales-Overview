**Amazon Sales Overview**

**Tools used**: Microsoft Excel, Microsoft PowerBI

**Datasets About**:
“Amazon Product's Ratings and Reviews” ( has 1351 rows )

**Source** - > https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset 

**Business Questions:**
1. What is the total sales revenue, and how much impact do discounts have on it?
2. Which product category generates the highest sales revenue?
3. Which products have the highest number of customer reviews?
4. Which categories receive the most customer reviews overall?
5. Which product is the top-rated, and which product needs improvement based on ratings?
6. What are the highest and lowest product ratings?
7. Which category offers the highest and lowest average discounts?
8. What is the contribution of each category to total sales?

**Data Preprocessing:**
- Before turning the data into a dashboard via PowerBI, i cleaned the data with Excel by utilizing Power Query and some Excel functions to make sure that there was no duplicated values, no blank values, and the datatypes were appropriate.
  
- I also divide the dataset into dimension and fact before putting it onto PowerBI, the fact data consists of numerical data used for calculating metrics. Meanwhile, the dimension data consists of primary key such as id category and id product type. The goal is to make sure the data is efficient during the visualizing process on PowerBI.
  
- After making sure that the dataset had been prepared. I downloaded the file to further be visualized on PowerBI. You can see the cleaned data i’d done by looking at the changes on ‘raw dataset.csv’  compared to ‘clean dataset.xlsx’.

**Key Insights:**
1. Sales Performance
- Total actual sales revenue amounted to ₹121.32 billion, with total discounts reaching ₹49.41 billion. This highlights the significant role that discounts play in   influencing net revenue.

- The Electronics category contributed the most to total revenue, with ₹59.18 billion, making it the most profitable product segment in the dataset.

2. Category Contribution and Discount Strategy
- Categories such as HomeImprovement and Computers & Accessories offered the highest average discounts (57.5% and 53.92% respectively), indicating an aggressive
  discounting approach.
  
- There is no direct correlation between high discounts and high revenue, indicating that discount effectiveness may vary depending on the category.

3. Customer Reviews and Product Ratings
- The most reviewed products include In-Ear, USB Cables, and Smartphones, with each receiving over 2 million reviews, suggesting high customer interest and
  purchase volume.

- Electronics is not only the top revenue generator but also the category with the highest volume of customer reviews, strengthening its dominance.

- InstantWaterHeaters received the highest ratings, while FanHeaters had the lowest, pointing to potential quality or satisfaction issues that require attention.

**Recommendations:**
1. Focus marketing and product development efforts on the Electronics category, especially top-reviewed and top-rated products.

2. Reassess discount strategies in categories where heavy discounts do not result in high revenue contribution.

3. Investigate low-rated products like FanHeaters to increase customer satisfaction and reduce negative sentiment.

4. Consider expanding promotional efforts on highly reviewed products to leverage their popularity and credibility.

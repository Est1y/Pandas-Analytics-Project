Project title:
# Analyze Supermarket Data Across the Country - Company XYZ
# Project description:
      Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen.
# Project Steps
      * Various libraries were imported such as os, glob, numpy, pandas, matplotlib.pyplot etc
      * The data containing information of each branch in the 3 major cities were loaded and combined using pd.concat to form a single dataframe with csv extension and then save as a new file in the local directory containing the project.
 # 1. The first major task was data exploration
       * The first 5 rows of the newly created file 'Market_data.csv' was displayed
       * no of rows and columns was checked using df.shape
       * check various column names in the dataset using df.columns 
       * statistical summary was checked using df.describe()
       * Missing data was checked using the isnull
       * General Information of the data was checked using .info
 # 2. The second: Dealing with datetime features
       * Convert the date column to datetime
       * The above was also done for the time column
       *  * Extract year, month, and day from the date column and also hour from the time column
       * Determine the unique ours of sales in the supermarket and return the result as an array.
 # 3. Check for unique values in columns
       * Get a list of the categorical column in the dataset, and check if each element in the column is of type object
       * generate the unique values in the categorical columns in this case, Payment, product line, gender, and customer type
       * Get a Series containing counts of unique values for various categories
 # 4.  Aggregation with GroupBy
       * Create a groupby object with the "City Column", and aggregation function of sum and mean.
       * Display a table that shows the gross income of each city, and determine the city with the highest total gross income.
 # 5. Data Visualization
       * Determine the branch with the highest sales record using countplot.
       * Determine the highest & lowest sold product line, using Countplot
       * Determine the Payment channel used by most customers to pay for each product line.
       * Determine the Payment channel for each branch.
       * Determine the branch with the lowest rating
       * Generate visualization for the "product line" per gender
       * Generate visualization for the "product line" per "Total" column
       * plot Product line per unit price, and Product line per Quantity
# Insights
      There are 3 different datasets (csv files): Dataset for Abuja_Branch, Lagos Branch, and Port Harcourt Branch
            * Lagos branch (A) consists of 340 rows and 17 columns
            * Abuja branch (B) consists of 332 rows and 17 columns
            * Port Harcourt branch (C) consists of 328 rows and 17 columns
      The datasets were combined to generate a single dataframe (dataset) which consists of 1000 rows and 17 columns
      The statistical summary shows the Standard Deviation (STD) of the unit price and gross income to be 9538.066205 and 4215.177173 respectively and also, the mean value of the unit price   and the gross income is 20041.966800 and 5536.572840 respectively.
      The dataset contains no null values
      The dataset contains records of 501 female customers and 499 male customers
      Port-Harcourt (C) records the highest revenue(gross income) while Lagos (A) follows next and then Abuja (B) as shown in Figure 1
      There are more member customers than normal customers which correspond to females and males in the gender count as shown in Figure 6 and Figure 7 respectively.
      The female spent more time in the City of Port Harcourt as shown in Figure 8
      'A' has the highest no of customers/sales followed by 'B' and the least is 'C' as can be seen in Figure 2.
      The most used payment method, in general, is EBAY and the least is Card
      The most sold product line in all 3 branches is 'food and beverages' in 'C', next is 'Home and lifestyle' in 'A' and the 3rd most sold product line is 'fashion and accessories' in 'C'.  However, in 'B', the most sold is 'Travel and sport' as can be seen in figure 3.
      The most used payment method for 'Product line' is Cash
      The branch with the lowest rating is "B" while 'C' has the highest as can be seen in Figure 4.
      It is observed that the most frequent customers are of the female gender and the most bought product is the 'Home and lifestyle' as can be seen in Figure 5.
      It is also observed that the most expensive 'product line' is the 'food and beverages' and it is mainly bought by the female gender.
# Future Work
      Explore the  dataset for types of customers to be sure that both new and old customers are maintained.
      Check for specific sales per month to know the monthly trend of the market
      Explore other data visualization framework to get a more understandable presentation.  

# Standout Section
      Inserted all required libraries in the first cell of my work for the purpose of orderliness unlike the import instruction stated in the notebook.
      Extracted the minute feature from the Time column and saved it to a new minute column
      Presented the percentage of normal customers Vs member customers.
      Presented the percentage of female Vs male
      Gave a visualization of the gender that spent the highest number time in each city


# Executive Summary.

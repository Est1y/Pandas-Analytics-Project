Project title:
# Analyze Supermarket Data Across the Country - Company XYZ

Project description:
Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen.

# Project Steps
* Various liberies were imported such as: os, glob, numpy, pandas, matplotlib.pyplot etc
* The data containing information of each branch in the 3 major cities were loaded and combined using pd.concat to form a single dataframe with csv extention and then   save as a new file in the local directory conataining the project.
    # The first major task was data exploration
       * The first 5 rows of the newly created file 'Market_data.csv' was displayed
       * no of rows and columns was checked using df.shape
       * check various column name in the dataset using df.columns 
       * statistical surmary was checked using df.describe()
       * Missing data was checked using the isnull
       * General Information of the data was checked using .info
    # The second: Dealing with datetime features
       * Convert the date column to datetime
       * The above was also done for the time column
       * Extract year, month and day from the date column and also hour from from the time column
       * Determine the unique ours of sales in the supermarket and return result as an array.
    # Check for unique value in columns
       * Get a list of the categorical column in the dataset, check if each element in the column is of type object
       * generate the unique values in the categorical columns in this case, Payment, product line, gender and customer type

To-Do - Explain in detail, the project steps and overview of different tasks completed here.

# Insights

To-Do - Explain the insights you were able to uncover from the analysing the datasets.

# Future Work

To-Do - Suggest tasks you might include in future work to make this project more robust.

# Standout Section

To-Do - Explain what you did differently in the project following the instructions in the notebook.

# Executive Summary.

To-Do - Include your Executive Summary document in your repository.

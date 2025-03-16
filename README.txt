In this project, I performed web scraping to collect data about washing machines from Flipkart, a popular e-commerce website. The goal was to gather information about various washing machine models, their features, and pricing, then clean and analyze the data for insights.

Web Scraping:

Using Python and the BeautifulSoup library, I scraped data from Flipkart’s washing machine category. This included details like the model name, brand, price, ratings, and key features.
I used requests to fetch the HTML of the product pages and BeautifulSoup to parse and extract relevant data into a structured format.

Creating a Dataset:

The scraped data was organized into a pandas DataFrame, which was then converted into a CSV file for easy analysis and further processing. This dataset contained key attributes such as product name, brand, price, ratings, and features of the washing machines.

Data Cleaning:

I carefully explored and cleaned the dataset to ensure the data was usable for analysis and visualization:
Removed Null Values: Missing or incomplete data was handled by identifying and dropping rows with missing values.
Data Transformation: Data was transformed where necessary, such as converting prices to a numerical format, parsing ratings into numeric values, and correcting inconsistencies in the dataset.

Data Visualization Preparation:

After cleaning, I created a cleaned DataFrame that was ready for visualization. This included creating visual representations of key aspects such as:
Distribution of washing machine prices.
Popular brands and their market share.
Ratings distribution and features comparison.

Tools & Libraries Used:
Python for web scraping and data manipulation.
BeautifulSoup and requests for web scraping.
Pandas for data cleaning and manipulation.

Matplotlib/Seaborn (optional, if you included visualization in the project) for data visualization.
Outcome:
By the end of this project, I successfully built a cleaned dataset from Flipkart's washing machine listings and was able to use this data to extract insights, perform statistical analysis, and prepare it for visualization. The cleaned data could now be used for deeper analysis, feature selection, or even predictive modeling.

POWER-BI Dashboard:-
  The Power BI dashboard provides key insights into the sales and performance ofwashing machines on Flipkart:
Total price sum: ₹7M, with a minimum discount of 5%.
Average rating: 4.24, with most products rated as "Excellent" or "Average".
Top discounts: Samsung, Voltas Beko, and Godrej offer the highest total discounts.
Price trends: IFB, Bosch, and Samsung have higher-priced models, while TCL and Motorola are more budget-friendly.
Whirlpool dominance: Many Whirlpool models are listed, mainly with average ratings.

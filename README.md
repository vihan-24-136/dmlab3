Overview:-
This Streamlit app provides interactive e-commerce product data analysis, including price trends, ratings, user reviews, and association rule mining.
Data-driven insights are enabled to facilitate better decision-making.
Features :-
Data Loading & Preprocessing

Loads product data from a CSV file.

Eliminates column headers and numeric data conversion.

Filtering Options

Select products by category.

Filter minimum rating.

Visualizations

 Price vs Discount: Scatter plot of original and discounted price.

 Top Rated Products: Top-rated products display.

Review Word Cloud: Generates a word cloud of customer reviews.

Market Basket Analysis

Uses Apriori algorithm to find frequent sets of products.

Generates association rules for product suggestion.

Process :-
I created this app for ease of e-commerce data analysis by condensing major insights into automation.
It starts with the loading and preprocessing of product data from a CSV file, in the proper format and numeric conversion.
I added interactive user filters to filter products based on category and rating. For visualizing trends,
I added price vs. discount scatter plots and review analysis word clouds.
I also employed the Apriori algorithm to perform market basket analysis to identify most purchased product pairs and create association rules.
The application is completely interactive and developed using Streamlit to give an end-to-end user experience for exploration and decision-making.

Setup & Installation :-
1.Clone the repository:
git clone https://github.com/your-repo/ecommerce-analysis.git
cd ecommerce-analysis
2.Install dependencies:
pip install -r requirements.txt
3.Run the Streamlit app:
streamlit run app.py

Required Data:- 
. Keep the amazon.csv file in the root directory.
. Alternatively, modify the script to use st.file_uploader() for dynamic file upload.

 Future Enhancements :-
. Use advanced filtering methods.
. Scale association rule mining for large data.
. Improve visualization design.

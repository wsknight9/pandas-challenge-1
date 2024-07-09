# pandas-challenge-1
# Module 4 Challenge - Data Analysis of a fictional e-commerce company
# Part 1: Explore the Data
# Import the data and use Pandas to learn more about the dataset.

# import pandas as pd

# df = pd.read_csv('Resources/client_dataset.csv')
# df.head()

# View the column names in the data
# print(df.columns.values)

# Use the describe function to gather some basic statistics
# df.describe()

# Use this space to do any additional research
# and familiarize yourself with the data.

# What three item categories had the most entries?

# For the category with the most entries, which subcategory had the most entries?

# Which five clients had the most entries in the data?

# Store the client ids of those top 5 clients in a list.

# How many total units (thqty column) did the client with the most entries order order?

# Part 2: Transform the Data
# Do we know that this client spent the more money than client 66037? If not, how would we find out? Transform the data using the steps below to prepare it for analysis.

# Create a column that calculates the subtotal for each line using the unit_price and the qty

# Create a column for shipping price.
# Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under.

# Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%

# Create a column for the cost of each line using unit cost, qty, and
# shipping price (assume the shipping cost is exactly what is charged to the client).

# Create a column for the profit of each line using line cost and line price

# Part 3: Confirm your work
# You have email receipts showing that the total prices for 3 orders. Confirm that your calculations match the receipts. Remember, each order has multiple lines.

# Order ID 2742071 had a total price of $152,811.89

# Order ID 2173913 had a total price of $162,388.71

# Order ID 6128929 had a total price of $923,441.25

# Check your work using the totals above

# Part 4: Summarize and Analyze
# Use the new columns with confirmed values to find the following information.

# How much did each of the top 5 clients by quantity spend? Check your work from Part 1 for client ids.

# Create a summary DataFrame showing the totals for the for the top 5 clients with the following information:
# total units purchased, total shipping price, total revenue, and total profit. 

# Format the data and rename the columns to names suitable for presentation.

# Define the money columns. 

# Define a function that converts a dollar amount to millions.

# Apply the currency_format_millions function to only the money columns. 

# Rename the columns to reflect the change in the money format. 

# Sort the updated data by "Total Profit (millions)" form highest to lowest and assign the sort to a new DatFrame.

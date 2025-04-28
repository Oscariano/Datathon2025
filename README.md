# Datathon2025 #

Welcome to our submission for the [Datathon 2025](https://web.archive.org/web/20250421124732/https://datathon2025.webflow.io/) (archived from [original](https://datathon2025.webflow.io/)) hosted by DubsTech. 

Our team comprises of Adelin Ma, Kevin Seng and Oscar Song and the theme that we would be tackling today is Retail: Accelerating the Sales of the Modecraft Ecommerce Store.

## Prompt: Retail: Accelerating the Sales of the Modecraft Ecommerce Store

Contents below copied from https://doc.clickup.com/26455927/p/h/t7bvq-3811/82e54fe4b879719/t7bvq-3871

### Intro
Modecraft (an anonymized real-world company) is an ecommerce store offering a wide range of household items such as mugs, cabinets, lanterns, etc. They have collected processed over 500,000  orders for a diverse global clientele as a business and have now hired you as a consultant to review their data and provide them with business recommendations.
They want to view metrics from both operations and marketing perspectives and seek guidance on areas performing well. As a consultant tasked with analyzing the data of the online retail store, your role is pivotal in understanding and optimizing the company's revenue generation. You'll be diving deep into the available data to uncover insights that will guide the company's strategic decisions for the upcoming year. 
This Datathon is your opportunity to delve into Modecraft's comprehensive data, uncover valuable insights, and develop innovative data-driven solutions that can propel their business to new heights.
### Tasks
Your task is to answer one or more of the following questions from the three categories below or any question that sparks curiosity in you and your team regarding the dataset: 
<!---
### Machine Learning Model
 * For a specific product (each one has a unique stock code) predict: 
 * Total Quantity it will sell in the next 3 months
 * Total Revenue it will earn in the next 3 months
 * For the store as a whole predict: 
 * Total Revenue it will earn in the next 3 months
 * For a specific country predict: 
 * Total Revenue it will earn in the next 3 months
--->
### Data Analytics and Data Visualization
The questions below can be attempted by both data analysis and data visualization members
**The questions we answered are bolded and underlined**
 * ~~Is there any seasonality in purchases for certain products?~~
 * ~~Which products have seen a significant increase or decrease in quantity ordered over the years?~~
 * ~~What trends do we notice in the basket size (total items in one receipt)?~~
 * ~~What trends do you notice for the website with respect to time?~~
 * ~~What are the peak sales periods for the business?~~

**<ins>Create a way to see a Monthly Analysis Report for a selected month and year that displays</ins>**
 * Products that sold the most
 * Products that sold the least
 * Products that generated the most revenue
 * Products that generated the least revenue
 * Customers who bought the most
 * Most popular days of the week
 * Most popular times for purchase during the week
 * In what ways can the store can increase revenue?
 * Regions that earned the most money

**<ins>Create a way to see a report for a specific product</ins>**
 * Quantity Sold by Country
 * Quantity Sold by Month
 * Quantity Sold by Time of Day
 * Quantity Sold by Day of Week
 * Total Quantity Sold 
 * Total Revenue Generated

**<ins>Customer Insights:</ins>**
 * Are there any customer behavioral patterns you notice
 * Geographical Analysis:
 * Visualize the distribution of sales across countries
 * Identify top-performing regions and potential areas for expansion
We recommend this question only be attempted by those also pursuing the Data Analysis Track

**<ins>Create a metric that ranks the products based on their performance. This metric should enable the company to know the product's health and whether they should focus on selling a product more or not.</ins>
 * When creating your metric think of different formula you can create for the same.
 * Be sure to describe the process behind creating your metric
 * Rank the products in the end based on your metric
 * ~~Any other question you can think of!~~

Download the Dataset

Download the Dataset here: 

https://docs.google.com/spreadsheets/d/14JpdZtBkG8mJtfRjrk01R-sQ1WPGgLJXKzZThHx-Zi8/edit?usp=sharing 

We have provided a list of columns in the dataset below. 

 * Dataset Columns

 * The dataset provided contains the following columns:

 * InvoiceNo (Unique Invoice ID)

 * StockCode (Unique Product ID)

 * Description (Product Name)

 * Quantity (Total Quantity of Product bought in that invoice)

 * InvoiceDate (Date and Time at which invoice was created)

 * UnitPrice (Price of One Unit of that Product - in UK Pounds)

 * CustomerID (Unique Customer ID)

 * Country (Country from which order came)

We recommend you also create additional columns such as:

 * Revenue (Quantity x Unit Price)

 * Day of Week

 * Time of Day

 * Weekday or Weekend

 * Quarter

 * Product Name 

We also recommend you get rid of dirty data in the dataset and blank rows

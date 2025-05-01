# Sumarket-Analysis
<br>
This project analyzes supermarket sales data to uncover insights and trends using Python and various data visualization techniques. The analysis is performed in a Jupyter Notebook.
<br>
## Project Structure
<br>
# Jupyter Notebook containing the analysis 
<br>
├── supermarket_sales.csv # Dataset used for the analysis ├──

## Dataset

The dataset, `supermarket_sales.csv`, contains information about supermarket transactions, including:

- **Invoice ID**: Unique identifier for each transaction
- **Branch**: Branch of the supermarket (A, B, C)
- **City**: City where the branch is located
- **Customer Type**: Membership status (Member or Normal)
- **Gender**: Gender of the customer
- **Product Line**: Category of products purchased
- **Unit Price**: Price per unit of the product
- **Quantity**: Number of units purchased
- **Tax 5%**: Tax applied to the transaction
- **Total**: Total amount paid
- **Date**: Date of the transaction
- **Time**: Time of the transaction
- **Payment**: Payment method (Cash, Credit Card, Ewallet)
- **COGS**: Cost of goods sold
- **Gross Margin Percentage**: Gross margin percentage
- **Gross Income**: Gross income from the transaction
- **Rating**: Customer rating of the transaction

## Analysis Overview

The analysis is divided into the following sections:

### 1. **Data Preprocessing**
   - Convert the `Date` column to datetime format.
   - Set the `Date` column as the index.
   - Handle duplicate rows and missing values.

### 2. **Univariate Analysis**
   - Distribution of customer ratings.
   - Histogram of all numeric columns.

### 3. **Bivariate Analysis**
   - Relationship between gross income and customer ratings.
   - Comparison of gross income across branches.
   - Analysis of payment methods and their usage.

### 4. **Time Series Analysis**
   - Time trend of gross income aggregated by day.

### 5. **Correlation Analysis**
   - Correlation between numeric variables.
   - Heatmap visualization of missing values.

## Visualizations

The project uses the following visualizations to present insights:

- **Histograms**: Distribution of numeric variables.
- **Countplots**: Frequency of categorical variables like `Branch` and `Payment`.
- **Boxplots**: Comparison of gross income across branches and genders.
- **Line Plot**: Time trend of gross income.
- **Pairplot**: Relationships between all numeric variables.

## Tools and Libraries

The project uses the following Python libraries:

- `pandas` for data manipulation
- `numpy` for numerical computations
- `matplotlib` and `seaborn` for data visualization
- `calmap` for calendar heatmaps

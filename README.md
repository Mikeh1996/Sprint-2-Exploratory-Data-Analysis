# Exploratory Data Analysis (EDA)
## Inspiration
This project is my first hands-on experience with Exploratory Data Analysis (EDA). It shows my progress in learning Python and working with real data. My goal was to understand how to clean, explore, and visualize data using simple tools and a clear step-by-step approach.

## Problem Statement
Instacart’s order data helps us learn about customer shopping behavior — when people shop, what they buy, and how often. The challenge is that raw data is often messy. This project focuses on:

* Cleaning and organizing Instacart datasets

* Removing duplicate or inconsistent entries

* Finding order patterns and popular products

* Using basic plots to visualize the data

Some questions I wanted to answer:

* Are there duplicate rows in the data?

* What days and times do most orders happen?

* Which products and departments are the most popular?

## What I Learned from This Project
I practiced using pandas, numpy, and matplotlib to work with CSV files, clean the data, and build helpful visualizations. I learned how to:

* Read and combine multiple datasets

* Remove duplicates

* Filter and query data

* Create simple bar charts and histograms

This project helped me understand the full process of exploring data from start to finish.

## Project Execution
### Setting Up the Environment
To run this project, install the following Python packages:

sh
Copy
Edit
pip install pandas numpy matplotlib

### Data Collection
This project uses five CSV files provided by Instacart:

instacart_orders.csv

products.csv

aisles.csv

departments.csv

order_products.csv

Each file was loaded and checked for duplicate or missing data. The datasets were cleaned and merged for analysis.

### Exploratory Data Analysis (EDA)
* Removed duplicate rows and checked for data quality

* Explored shopping trends by time and day

* Found the most ordered products, aisles, and departments

* Created plots using matplotlib to show patterns in the data

### How to Run the Project Locally
#### Clone the repository

sh
Copy
Edit
git clone https://github.com/YOUR-USERNAME/instacart-eda-project.git
cd instacart-eda-project

#### Set up a virtual environment and install dependencies

sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

#### Open the Jupyter Notebook

sh
Copy
Edit
jupyter notebook EDA.ipynb

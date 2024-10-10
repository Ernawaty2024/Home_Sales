# Home Sales Analysis using PySpark and SparkSQL

This project utilizes PySpark and SparkSQL to analyze a home sales dataset, focusing on calculating key metrics such as the average home price across various conditions. The project involves creating temporary views, caching, and partitioning data to optimize queries and measure runtime differences.

## Project Overview

The purpose of this project is to answer a series of analytical questions using SparkSQL, manipulate data, and optimize query performance through techniques like caching and partitioning. Key insights from the dataset include average home prices for different combinations of features (such as bedrooms, bathrooms, and square footage), and performance improvements when data is cached and partitioned.

## Data Source

The dataset used in this project is `home_sales_revised.csv`, which contains information about home sales, including:

- `price`: The sale price of the home.
- `date_sold`: The date the home was sold.
- `bedrooms`: The number of bedrooms.
- `bathrooms`: The number of bathrooms.
- `floors`: The number of floors.
- `sqft_living`: The square footage of the living space.
- `view`: A rating of the home's view.
- `date_built`: The year the home was built.

## Setup Instructions

To run this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/home_sales.git
    ```

2. **Install the necessary dependencies**:
   Ensure you have a working PySpark environment. You can install PySpark using pip:
   ```bash
   pip install pyspark





# Project Summary

## Project Name

EchoChain - Lifecycle Analytics of Second-Hand Electronics

## Objective

The main objective of this project is to analyze second-hand electronic products from different online marketplaces such as OLX, eBay, and the Used Devices dataset. The project focuses on understanding product availability, brand popularity, pricing trends, operating systems, and device characteristics. The insights are presented through interactive Power BI dashboards to help users understand the lifecycle of electronic products in the secondary market.

## Datasets Used

### OLX Dataset
- Contains advertisements posted on OLX.
- Includes information such as brand, category, location, price, and product title.

### eBay Dataset
- Contains electronic products listed on eBay.
- Includes manufacturer, price, seller rating, average rating, internal memory, screen size, color category, and product specifications.

### Used Devices Dataset
- Contains mobile device specifications.
- Includes brand, operating system, RAM, battery capacity, camera details, release year, 4G/5G support, screen size, and usage information.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI
- Git & GitHub

## Data Cleaning

Several preprocessing steps were performed before analysis.

- Removed duplicate records
- Checked and handled missing values
- Standardized column names
- Removed unnecessary columns
- Verified data types
- Prepared cleaned datasets for visualization

The cleaned datasets were saved in the `processed` folder for further analysis.


## Exploratory Data Analysis (EDA)

EDA was carried out to understand the datasets and identify useful insights.

Some of the analyses performed include:

- Brand distribution
- Price analysis
- Manufacturer comparison
- Operating system distribution
- Release year analysis
- 4G and 5G availability
- Device specification comparison
- Seller rating analysis

## Dashboard Development

Interactive dashboards were developed using Power BI.

The dashboards include:

- Total listings
- Total products
- Top brands
- Top manufacturers
- Brand distribution
- Operating system distribution
- Release year analysis
- 4G and 5G distribution
- Price analysis
- Product filters using slicers

These dashboards allow users to explore the data easily and gain meaningful insights.

## Key Insights

- Samsung, Apple, and Xiaomi are among the most frequently listed brands.
- Android devices dominate the used electronics market.
- Most listed devices support 4G, while fewer support 5G.
- Product prices vary significantly across manufacturers.
- Older devices continue to have an active resale market.
- Interactive dashboards help compare products and understand market trends effectively.

## Challenges Faced

During the project, several challenges were encountered:

- Different datasets had different structures.
- Missing values required preprocessing.
- Column names were inconsistent across datasets.
- Selecting meaningful visualizations for each dataset required experimentation.
- Integrating insights from multiple datasets into dashboards took additional effort.

These challenges were addressed through data cleaning, feature engineering, and careful dashboard design.

## Learning Outcomes

This project helped improve practical knowledge in:

- Data preprocessing
- Exploratory Data Analysis
- Python programming
- Pandas library
- Data visualization
- Power BI dashboard development
- Git and GitHub version control
- Presenting analytical insights

## Conclusion

The EchoChain project successfully analyzed multiple second-hand electronics datasets and transformed raw data into meaningful business insights. By combining Python for preprocessing and Power BI for visualization, the project demonstrates a complete data analytics workflow from data preparation to dashboard creation. The project also strengthened practical skills in analytics, visualization, and project management.
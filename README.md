# Analysis of the Oldest Businesses in the World

## Overview

This project analyzes a dataset of the oldest businesses in the world, compiled by BusinessFinancing.co.uk. The dataset includes businesses that have been operating for centuries, providing insights into how some companies manage to survive and thrive over long periods. The analysis is performed using SQL in a Jupyter notebook.

## Dataset

The dataset contains three tables:

### Table: categories
| column         | type    | meaning                                 |
|----------------|---------|-----------------------------------------|
| category_code  | varchar | Code for the category of the business.  |
| category       | varchar | Description of the business category.   |

### Table: countries
| column         | type    | meaning                                 |
|----------------|---------|-----------------------------------------|
| country_code   | varchar | Code for the country.                   |
| country        | varchar | Name of the country.                    |
| continent      | varchar | Continent where the country is located. |

### Table: businesses
| column         | type    | meaning                                  |
|----------------|---------|------------------------------------------|
| business_id    | varchar | Unique identifier for the business.      |
| name           | varchar | Name of the business.                    |
| year_founded   | int     | Year the business was founded.           |
| category_code  | varchar | Category code of the business.           |
| country_code   | varchar | Country code of the business.            |

## Analysis Sections

### 1. The Oldest Business in the World
![The entrance to St. Peter Stiftskeller](https://assets.datacamp.com/production/repositories/5851/datasets/7dded924c6dc418d4a828f2f4daba99953c27a5a/400px-Eingang_zum_St._Peter_Stiftskeller.jpg)
*Image: St. Peter Stiftskeller, founded in 803. Credit: [Pakeha](https://commons.wikimedia.org/wiki/File:Eingang_zum_St._Peter_Stiftskeller.jpg).*

### 2. Joining Tables for Comprehensive Analysis
Joining all three tables to facilitate comprehensive analysis, including identifying the oldest businesses by continent.

### 3. Counting Categories by Continent
Analyzing the most common business categories for the oldest businesses on each continent.

### 4. Filtering Results for Further Insights
Filtering the combined dataset to highlight the most significant continent-category pairs.




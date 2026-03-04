# Gender Pay Equality Analysis

## Project Overview

This project analyzes gender pay equality across different Daikibo factories using Microsoft Excel. The goal is to identify patterns of pay inequality across job roles and factory locations.
The analysis classifies equality scores into categories and visualizes the distribution using pivot tables and charts.


## Objective

The objective of this project is to :

* Analyze equality scores across factories
* Identify potential discrimination patterns
* Visualize fairness distribution across job roles
* Provide insights that could help decision makers review salary structures



## Dataset Description

The dataset contains three main columns:

| Column         | Description                                      |
| -------------- | ------------------------------------------------ |
| Factory        | Factory location                                 |
| Job Role       | Role within the organization                     |
| Equality Score | Numerical score representing gender pay equality |

Equality Score Range:

* 0 → Perfect equality
* Negative values → Potential discrimination
* Positive values → Potential inequality in the opposite direction



## Data Processing

A new column called **Equality Class** was created using Excel formulas to classify equality scores into categories.

Classification Logic:

* **Fair** → Scores between -10 and +10
* **Unfair** → Scores between -20 and -10 OR between +10 and +20
* **Highly Discriminative** → Scores less than -20 OR greater than +20

This classification helps identify areas requiring attention.


## Tools Used

* Microsoft Excel
* Logical formulas
* Conditional formatting
* Pivot tables
* Data visualization (Clustered column chart)



## Analysis Process

1. Data exploration and understanding of equality scores
2. Creation of an equality classification column
3. Application of conditional formatting for quick identification
4. Creation of pivot tables to summarize factory-wise equality patterns
5. Visualization using clustered column charts



## Key Findings

### Berlin

* Shows the best pay equality
* No highly discriminatory roles observed

### Meiyo

* Highest number of unfair roles
* Indicates potential salary imbalance

### Seiko

* Several highly discriminatory roles
* Requires review of compensation structure

### Shenzhen

* Mostly fair roles
* Minor inequality present



## Overall Summary

| Category              | Count |
| --------------------- | ----- |
| Fair                  | 19    |
| Unfair                | 11    |
| Highly Discriminative | 7     |
| Total Roles           | 37    |

The majority of job roles demonstrate fair pay equality, but some factories show signs of inequality that require further investigation.



## Visualization

The project includes a pivot chart that shows the distribution of equality classes across factories, allowing easy comparison between locations.


## Internship Experience

This project was completed as part of a **Data Analytics Internship**, where the objective was to analyze gender pay equality patterns using real-world datasets.


## Future Improvements

Possible improvements to this project include:

* Building an interactive Excel dashboard
* Implementing the analysis using Python and Pandas
* Creating a Power BI dashboard for better visualization
* Expanding the dataset with more job roles and locations



## Author
Yadhav R
BTech Student | Aspiring Data Analyst

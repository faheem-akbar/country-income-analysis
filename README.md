# Country GDP per Capita Analysis

## Project Overview

This project analyzes **GDP per capita (current US$)** for four countries — Pakistan, India, China, and the United Kingdom — from **2000 to 2025**.

The project uses Python and Pandas to clean, analyze, compare, and visualize the data obtained from the World Bank.

> **Note:** GDP per capita is not the same as an individual's salary or personal income. It represents a country's GDP divided by its population.

## Objectives

* Analyze GDP per capita trends from 2000 to 2025
* Compare Pakistan with India, China, and the United Kingdom
* Calculate average GDP per capita
* Measure the change between 2000 and 2025
* Calculate percentage growth
* Identify the highest and lowest values
* Create yearly comparison tables and visualizations
* Practice real-world data analysis using Pandas

## Countries

* Pakistan
* India
* China
* United Kingdom

## Data Source

**World Bank Open Data**

Indicator: **GDP per capita (current US$)**
Indicator Code: `NY.GDP.PCAP.CD`

Data period used: **2000–2025**

2025 is the latest available year in the dataset used for this analysis.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Requests
* OpenPyXL
* Jupyter Notebook

## Analysis Performed

The project includes:

1. Data collection using the World Bank API
2. Data cleaning
3. Missing-value checking
4. Data type conversion
5. Filtering data for 2000–2025
6. Average GDP per capita calculation
7. 2025 country comparison
8. Comparison with Pakistan
9. 2000–2025 growth analysis
10. Highest and lowest GDP per capita analysis
11. Pivot-table analysis
12. Data visualization
13. CSV and Excel export

## Key Results

### Average GDP per Capita (2000–2025)

| Country        | Average GDP per Capita |
| -------------- | ---------------------: |
| China          |              $6,699.84 |
| India          |              $1,452.54 |
| Pakistan       |              $1,148.51 |
| United Kingdom |             $42,794.89 |

### GDP per Capita in 2025

| Country        | GDP per Capita |
| -------------- | -------------: |
| China          |     $13,861.97 |
| India          |      $2,702.48 |
| Pakistan       |      $1,595.91 |
| United Kingdom |     $57,601.96 |

### Growth from 2000 to 2025

| Country        |   Growth |
| -------------- | -------: |
| China          | 1330.25% |
| India          |  510.38% |
| Pakistan       |  148.45% |
| United Kingdom |  102.94% |

## Project Files

```text
country income-analysis/
│
├── data/
│   ├── country_income_clean.csv
│   └── country_income_clean.xlsx
│
├── country_income_analysis.ipynb
├── country_income_analysis.xlsx
├── README.md
└── requirements.txt
```

## How to Run

Clone or download the project, install the required Python libraries, and open the Jupyter Notebook.

Install dependencies:

```bash
pip install -r requirements.txt
```

Then open:

```text
country_income_analysis.ipynb
```

and run the notebook cells.

## Skills Demonstrated

This project demonstrates practical skills in:

* Python
* Pandas
* NumPy
* Data cleaning
* Data transformation
* GroupBy analysis
* Merging DataFrames
* Pivot tables
* Data visualization
* API data collection
* CSV and Excel handling
* Exploratory data analysis

## Future Improvements

Possible future improvements include:

* Adding more countries
* Adding GDP growth rate
* Adding population analysis
* Adding inflation-related indicators
* Building an interactive dashboard
* Applying machine learning to economic indicators

## Author

**Faheem Akbar**

BS Computer Science | Aspiring AI/ML Engineer

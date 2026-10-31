# NYC_Airbnb_2019_Data_Visualization
PowerBI NYC 2019 Data Visualization 
# NYC Airbnb Data Analysis – Mini Project

## 1. Project Overview

This mini project focuses on analysing Airbnb listing data from New York City (NYC).

The objective is to explore listing distribution, pricing patterns, room types, customer reviews, and availability across different neighbourhoods.

The project uses Microsoft Excel for data cleaning and Power BI Desktop for data visualisation and analysis.

## 2. Dataset Information

- **Dataset:** New York City Airbnb Open Data
- **Source:** [Kaggle – NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **Original Dataset:** 48,895 rows and 16 columns
- **Sample Used:** 1,000 rows
- **File Format:** CSV / Excel

### Key Columns

- `ID` – Unique listing identifier
- `NAME` – Airbnb listing name
- `HOST_ID` – Host identifier
- `HOST_NAME` – Host name
- `NEIGHBOURHOOD_GROUP` – NYC borough
- `NEIGHBOURHOOD` – Specific neighbourhood
- `LATITUDE` – Geographic latitude
- `LONGITUDE` – Geographic longitude
- `ROOM_TYPE` – Type of accommodation
- `PRICE` – Listing price
- `MINIMUM_NIGHTS` – Minimum nights required
- `NUMBER_OF_REVIEWS` – Total number of reviews
- `LAST_REVIEW` – Date of the last review
- `REVIEWS_PER_MONTH` – Average monthly reviews
- `CALCULATED_HOST_LISTINGS_COUNT` – Number of listings per host
- `AVAILABILITY_365` – Availability throughout the year

## 3. Tools and Technologies

- Microsoft Excel
- Power Query
- Power BI Desktop

## 4. Data Cleaning and Preparation

Data cleaning was performed using Microsoft Excel and Power Query.

The following operations were completed:

1. Imported the NYC Airbnb dataset.
2. Limited the dataset to 1,000 rows for the mini project.
3. Replaced missing values in the `HOST_NAME` column with "Unknown".
4. Applied proper case formatting to text values.
5. Retained null values in `LAST_REVIEW` and `REVIEWS_PER_MONTH`.
6. Checked for duplicate records.
7. Verified that there were no duplicate rows.
8. Checked for data errors.
9. Verified numeric columns for negative values.
10. Reviewed column names and data types.

### Data Quality Summary

- Duplicate rows: None found.
- Data errors: 0.
- Negative values: None found.
- Missing host names: Replaced with "Unknown".
- Missing review dates and monthly review values: Retained as null.

## 5. Power BI Data Visualisation

The cleaned dataset was imported into Power BI Desktop to create a multi-page analytical report.

### Page 1 – Executive Summary

Created an overview of Airbnb listings and key metrics.

### Page 2 – Average Price by Neighbourhood Group

Analysed the average Airbnb listing price across NYC neighbourhood groups.

| Neighbourhood Group | Average Price (USD) |
|---|---:|
| Manhattan | 182.63 |
| Brooklyn | 145.86 |
| Queens | 92.70 |
| Staten Island | 75.77 |
| Bronx | 70.85 |

### Page 3 – Neighbourhood Analysis

Analysed listing distribution across neighbourhoods.

#### Top Neighbourhoods by Listing Count

| Neighbourhood | Listings |
|---|---:|
| Williamsburg | 112 |
| Harlem | 80 |
| Bedford-Stuyvesant | 71 |
| East Village | 69 |
| Greenpoint | 58 |

#### Average Price by Room Type

| Room Type | Average Price (USD) |
|---|---:|
| Entire Home/Apt | 196.28 |
| Private Room | 106.37 |
| Shared Room | 72.71 |

### Page 4 – Reviews and Availability Analysis

Created four visualisations:

1. **Total Reviews:** KPI card showing approximately 80K reviews.
2. **Average Reviews per Month by Room Type:** Compared monthly review activity across room types.
3. **Average Listing Availability by Neighbourhood Group:** Compared average annual availability.
4. **Relationship Between Airbnb Price and Number of Reviews:** Scatter plot exploring the relationship between listing price and review count.

#### Average Reviews per Month by Room Type

| Room Type | Average Reviews per Month |
|---|---:|
| Shared Room | 1.34 |
| Private Room | 1.05 |
| Entire Home/Apt | 0.85 |

#### Average Listing Availability by Neighbourhood Group

| Neighbourhood Group | Average Availability (Days) |
|---|---:|
| Bronx | 317.54 |
| Staten Island | 275.69 |
| Queens | 226.34 |
| Manhattan | 169.63 |
| Brooklyn | 157.50 |

## 6. Key Findings

- Brooklyn and Manhattan have the highest listing counts in the selected sample.
- Manhattan has the highest average listing price among the five neighbourhood groups.
- Entire homes and apartments have the highest average price among room types.
- Shared rooms have the highest average monthly review activity.
- Bronx listings have the highest average availability at 317.54 days.
- Brooklyn listings have the lowest average availability at 157.50 days.
- Most listings in the scatter plot are concentrated at lower price levels.
- The scatter plot does not show an obvious strong relationship between price and review count.

## 7. Project Learning Outcomes

Through this project, I gained practical experience in:

- Understanding the data analytics workflow.
- Working with datasets in Excel.
- Cleaning and transforming data.
- Handling missing values.
- Identifying duplicate records and data errors.
- Exploring and summarising data.
- Creating charts and visualisations in Power BI.
- Analysing trends and patterns.
- Communicating insights through visual reports.
- Using GitHub to document and share project work.

## 8. Project Limitations

- The analysis uses a sample of 1,000 rows from the original dataset.
- Findings represent the selected sample and may not reflect the complete NYC Airbnb market.
- Missing review dates and monthly review values were retained as null.
- The scatter plot provides visual observations and does not establish causation.

## 9. Conclusion

This project provided practical exposure to the data analytics process, from data preparation and cleaning to visualisation and interpretation.

The analysis helped identify differences in listing prices, neighbourhood distribution, room types, review activity, and availability across New York City.

It also helped strengthen my foundational skills in Microsoft Excel, Power Query, Power BI, and data analysis.

---

**Project Type:** Data Analytics Mini Project  
**Domain:** Hospitality and Accommodation  
**Dataset:** NYC Airbnb Open Data  
**Tools:** Excel, Power Query, Power BI Desktop, GitHub

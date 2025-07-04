# A View of the World's Nations: A Data Cleaning Project

Check out the project's Python Jupyter Notebook file [here](https://github.com/Mcfeenix/Data-Cleaning-with-Python/blob/main/global_country_information.ipynb)!
### Description
The goal of this project is to prepare a dataset using Python for further analysis by performing essential data cleaning tasks. The raw dataset (world-data-2023.csv), which contains information on 195 countries, was downloaded programmatically from Kaggle. It originates from the *Global Country Information Dataset 2023* by Nidula Elgiriyewithana. Access to the original dataset is [here](https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023/data).

Cleaning steps included:
<img alt="Earth" src="https://github.com/user-attachments/assets/b12ced17-b355-401b-8031-b0c009f038fd" width="180" align="right">
- Standardizing column names for consistency
- Removing special characters from string data
- Converting columns to appropriate data types
- Addressing encoding corruption in text
- Handling missing values

This project demonstrates the process of preparing and cleaning a dataset for analysis. While missing data was addressed in two specific columns as examples, other columns still contain missing values. A comprehensive treatment of all missing data is beyond the scope of this portfolio project. However, any columns selected for further analysis should undergo appropriate handling of missing values to ensure the validity and reliability of the results.

The final cleaned dataset (countries.csv) consists of 195 rows and 35 columns, representing various indicators across countries.

### Dataset Columns
- Country: Name of the country.
- Density (P/Km2): Population density measured in persons per square kilometer.
- Abbreviation: Abbreviation or code representing the country.
- Agricultural Land (%): Percentage of land area used for agricultural purposes.
- Land Area (Km2): Total land area of the country in square kilometers.
- Armed Forces Size: Size of the armed forces in the country.
- Birth Rate: Number of births per 1,000 population per year.
- Calling Code: International calling code for the country.
- Capital/Major City: Name of the capital or major city.
- CO2 Emissions: Carbon dioxide emissions in tons.
- CPI: Consumer Price Index, a measure of inflation and purchasing power.
- CPI Change (%): Percentage change in the Consumer Price Index compared to the previous year.
- Currency_Code: Currency code used in the country.
- Fertility Rate: Average number of children born to a woman during her lifetime.
- Forested Area (%): Percentage of land area covered by forests.
- Gasoline_Price: Price of gasoline per liter in local currency.
- GDP: Gross Domestic Product, the total value of goods and services produced in the country.
- Gross Primary Education Enrollment (%): Gross enrollment ratio for primary education.
- Gross Tertiary Education Enrollment (%): Gross enrollment ratio for tertiary education.
- Infant Mortality: Number of deaths per 1,000 live births before reaching one year of age.
- Largest City: Name of the country's largest city.
- Life Expectancy: Average number of years a newborn is expected to live.
- Maternal Mortality Ratio: Number of maternal deaths per 100,000 live births.
- Minimum Wage: Minimum wage level in local currency.
- Official Language: Official language(s) spoken in the country.
- Out of Pocket Health Expenditure (%): Percentage of total health expenditure paid out-of-pocket by individuals.
- Physicians per Thousand: Number of physicians per thousand people.
- Population: Total population of the country.
- Population: Labor Force Participation (%): Percentage of the population that is part of the labor force.
- Tax Revenue (%): Tax revenue as a percentage of GDP.
- Total Tax Rate: Overall tax burden as a percentage of commercial profits.
- Unemployment Rate: Percentage of the labor force that is unemployed.
- Urban Population: Percentage of the population living in urban areas.
- Latitude: Latitude coordinate of the country's location.
- Longitude: Longitude coordinate of the country's location.item

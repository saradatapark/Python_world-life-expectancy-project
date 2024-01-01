# python_world-life-expectancy-project

## STAGE ONE - Data Cleaning
### 1. Check for Incomplete Data
Ensure the dataset's completeness by reviewing all entries in the world_life_expectancy table.

### 2. Remove Duplicates
Identify and eliminate duplicate rows by combining the "Country" and "Year" columns, flagging rows with counts above 1.

### 3. Handle Blank Values in "Status"
Investigate and address blank values in the "Status" column. Update them based on distinct values.

### 4. Populate Empty "Life Expectancy" Values
Fill empty "Life Expectancy" entries using average data from adjacent years.

## STAGE TWO - EDA (Exploratory Data Analysis)
### 5. Explore Life Expectancy Data
#### Lowest, Highest, Mean Values
Identify the lowest, highest, and mean life expectancy values for each country.

#### Country-wise Life Expectancy Increase
Determine countries with the highest increase in life expectancy.

### 6. Analyze GDP and Life Expectancy
#### Correlation Analysis
Investigate the correlation between GDP and life expectancy.

#### GDP Range Analysis
Split GDP into high and low ranges, analyzing the average life expectancy in each range.

### 7. EDA on Adult Mortality
Explore the relationship between adult mortality and life expectancy.

These steps cover data cleaning and exploratory data analysis for the World Life Expectancy project, ensuring data integrity and providing insights into key indicators such as life expectancy, GDP, and adult mortality.

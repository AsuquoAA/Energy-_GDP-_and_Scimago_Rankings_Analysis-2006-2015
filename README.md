# Energy-_GDP-_and_Scimago_Rankings_Analysis-2006-2015

## Overview

This project combines three datasets—Energy Indicators, World Bank GDP data, and Scimago Journal and Country Rank data—to perform an analysis on the top 15 countries in the fields of energy supply, renewable energy, and their average GDP over the last decade. The objective is to clean and merge the datasets, apply necessary transformations, and answer questions about missing data, top countries by GDP, and their energy indicators.

## Dependencies and Installations

To use this repository and run the notebooks, you will need to have Python and the following libraries installed:
1. Pandas
2. NumPy
- code: pip install numpy pandas

To get started with this repository, clone it to your local machine:
- code: git clone https://github.com/AsuquoAA/Energy-_GDP-_and_Scimago_Rankings_Analysis-2006-2015.git
  
Navigating to directory
- code: cd Energy-_GDP-_and_Scimago_Rankings_Analysis-2006-2015

---

## Datasets

The following datasets were used:
1. <a href="https://github.com/AsuquoAA/Energy-_GDP-_and_Scimago_Rankings_Analysis-2006-2015/blob/main/Energy%20Indicators.xls">Energy_Indicators</a>
2. <a href="https://github.com/AsuquoAA/Energy-_GDP-_and_Scimago_Rankings_Analysis-2006-2015/blob/main/scimagojr-3.xlsx">Scimago_Ranking</a>
3. <a href="https://github.com/AsuquoAA/Energy-_GDP-_and_Scimago_Rankings_Analysis-2006-2015/blob/main/world_bank.csv">World_Bank.csv</a>

---

## Questions

1. Question 1:
- What are the top 15 countries based on energy supply, renewable energy, and GDP data for the year 2013?

2. Question 2:
- How many entries were lost during the merge process when combining the Energy, GDP, and Scimago datasets?

3. Question 3:
- What is the average GDP of the top 15 countries over the last 10 years (2006–2015)?

4. Question 4:
- By how much had the GDP changed over the 10-year span for the country with the 6th largest average GDP?

5. Question 5:
- What is the mean energy supply per capita?

6. Question 6:
- What country has the maximum % Renewable and what is the percentage?

7. Question 7:
- Create a new column that is the ratio of Self-Citations to Total Citations. What is the maximum value for this new column, and what country has the highest ratio?

8. Question 8:
- Create a column that estimates the population using Energy Supply and Energy Supply per capita. What is the third most populous country according to this estimate?

9. Question 9:
- Create a column that estimates the number of citable documents per person. What is the correlation between the number of citable documents per capita and the energy supply per capita?

10. Question 10:
- Create a new column with a 1 if the country's % Renewable value is at or above the median for all countries in the top 15, and a 0 if the country's % Renewable value is below the median.

11. Question 11:
- Use the following dictionary to group the countries by continent, then create a DataFrame that displays the sample size, sum, mean, and standard deviation for the estimated population of each country.

12. Question 12:
- Cut % Renewable into 5 bins. Group the top 15 by continent and the new % Renewable bins. How many countries are in each of these groups?

13. Question 13:
- Convert the population estimate series to a string with thousands separator (using commas). Use all significant digits (do not round the results).

---

## Conclusion

This analysis provides insights into how the energy sector and GDP correlate for the top 15 countries, offering a valuable resource for understanding global energy and economic trends.

---

## Acknowledgement

This project is part of the Applied Data Science with Python Specialization from the University of Michigan. I would like to thank the university and the instructors for providing such valuable resources that helped me build and enhance my data science and Python skills throughout this project.

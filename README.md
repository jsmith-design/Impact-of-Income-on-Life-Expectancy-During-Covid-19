# Project 1: Income, Poverty, and Wealth: Their Impact on Life Expectancy

The COVID-19 pandemic gravely impacted the lives of many people worldwide. According to the World Bank, it dealt the “biggest setback” to the 21st century. If we can understand the ways countries were affected when it occurred, we can develop better health outcomes for those countries. I hypothesized that financial disparities, as reflected by global income levels, directly affected life expectancy during the onset of COVID in 2019. The aim of this study is to investigate whether nations classified as low income also exhibit lower life expectancy and faced challenges in paying for healthcare services when COVID started.

# Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|country|object|_found in all datasets_|Name of the country for which the data is from| 
|1800|int|Life Expectancy; Gross National Income; Out of pocket Healthcare Expenditure|Year of which the data is from| 
|1800_gin|object|merged_dataframes|Gross National Income per capita for the year the data is from| 
|1800_life|object|merged_dataframes|Life Expenditure as ages per capita for which the data is from| 
|1800|int|merged_dataframes|Out of pocket healthcare expenditure per capita in Millions US$ for which the data is from


# Executive Summary

##### Background: 
The significant impact of the 2019 global pandemic affected numerous individuals worldwide, leading to substantial health and economic setbacks. [Because there was an increase in poverty levels during the pandemic](https://www.worldbank.org/en/news/podcast/2022/12/01/global-poverty-reduction-shared-prosperity-report-development-podcast), income levels may have influenced health outcomes, along with out-of-pocket healthcare spending. Given the various factors that can affect life expectancy such as socieoeconmic statuses, this project aims to examine the relationship between income, poverty, and wealth in relation to life expectancy. 

##### Methodology: 

Using descriptive statistics, a nationwide comparative study was conducted utilizing data from Gapminder and the World Health Organization, to examine 155 nations and categorize them based on their income levels.

Before conducting analysis, data cleaning was applied where appropriate. This involved removing countries entire rows missing rows and filling any remaining null values with median aggregation to limit the possibility of outliers. I retained relevant columns pertinent to my analysis, adjusted data types to align with column values (i.e. fixed columns that were integers but registering as objects). Column names were also adjusted to lowercase, and renamed when necessary. Additionally, I merged the datasets to facilitate my analysis.

Subsequently, questions pertaining to my problem statement were explored. An example of the type of questions is outlined below: 

- What was the life expectancy rate in the countries that were middle income during 2019?
  
- What was the out-of-pocket healthcare expedenditure in low income countries during 2019?

- What was the global median life expectancy during 2019?


##### Key Findings:
During the onset of the pandemic, the global life expectancy rate was 73.85 years. High income countries surpassed this measure of center, with their citizens expecting to live to 81.1 years. Middle income and low income countries fell below the average with life expectancies of 71.9 years and 63.8 years, respectively. Notably, high-income countries also exhibited the highest healthcare expenditure, totaling \\$528 million, compared to \\$73 million spent by middle-income countries and only \\$14 million by low-income countries. Overall, there was a positive correlation between life expectancy, yielding a correlation coefficient of 0.67. This value indicates that at the start of the pandemic, as income increased across all income levels, life expectancy incrceased as well.


##### Next Steps?
Comprehensive solutions such as implementing policies like universal healthcare, progressive taxation, and increased minimum wages could effectively remedy the disparities found between income, poverty, and wealth. According to an [NIH study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6153391/#:~:text=On%20average%2C%20life%20expectancy%20at,and%20LEAB%2066.77%20%C2%B1%208.59), on average, healthy life expectancy was significantly higher in countries that have universal healthcare than in countries that were yet to. By passing strategic income and healthcare legislation, policymakers can universally bridge income level imbalances and positively improve health outcomes for their citizens. I also encourage all legislative officials to address and resolve socioeconomic inequalities that may factor into this disparity as well. Moving forward, it is imperative that these considerations remain at the forefront of legislative agendas.
### RhoMain
### The completed code is found in "Combined Data"
#### the data file can be found in "2021_data.xlsx

# Census Data , Understanding factors that effect median income.

The main objective of this project is to analyze the demographic data and answer various questions of what impacts income levels . Some of the questions that can be answered using the Census API include:
Data Description.
The Census data containing information for Year 2020-1, which includes:
Income Brackets (Dependant Variable)
Type of Household
Race and Hispanic Origin of Householder
Age of Householder
Nativity of Householder
Region
Residence
Educational Attainment of Householder

To answer these questions, we will collect data using the Census API, and then use various statistical and data analysis tools to identify trends, patterns, and insights. 
The project will be conducted in several phases, including data collection, data cleaning and processing, data analysis, and report generation.

In the finish product we were able to understand the following answers, 

### 1. Does Age Effect Median Income? 
Largest age group of householders in 2020 and 2021: individuals under 65 years old
Second-largest age group: individuals aged 65 years and older
Relatively low margin of error for individuals under 65 years old: 771(2020) and 613(2021)
Relatively high margin of error for individuals aged 65 years and older: 976(2020) and 1037(2021)

Age may influence income levels

Older individuals may have accumulated more wealth and experienced career growth
Age group 45 - 54 had the highest median income leveles
Certain age groups may be more likely to have completed higher levels of education, impacting their income levels.


### 2. Does Education Level have an Effect on Median Income ?
In terms of changes between 2020 and 2021, we see that the median income has decreased for all education levels except for those with a bachelor's degree or higher, where it has increased from 112,393 in 2020 to 115,456 in 2021.

Overall, the data suggests that education level is strongly correlated with income, with higher levels of education generally leading to higher incomes.


### 3. Does the Household Type have an effect on Income level?
##### Types of households ( Families, Couples, Single Male, Single Female, Non Family, Both Men, Both Female )
##### Which effects the households median income?
Married-couple households have the highest median income, followed by male householder households, then female householder households.
Nonfamily households, particularly those headed by a male householder, have relatively high median incomes.
Female householder nonfamily households have the lowest median income and the highest variance, suggesting greater income inequality.

### Does your nativity effect your median income?
The data shows income distribution of native-born and foreign-born individuals in 2020 and 2021, categorized into naturalized citizens and non-citizens. In 2020, more native-born individuals had income, but naturalized citizens had a higher number of individuals with an income than non-citizens. In 2021, there was an increase in the number of individuals with income for all categories.


### 5. Does the Region you live in effect your median income?
In 2020, the South region had the highest number of households (49,759 thousand) but the lowest average income 64,355. The West region had the highest average income 78,755 but a relatively lower number of households (29,203 thousand).

Overall, the data suggests that the West region has the highest income and the lowest number of households among all regions, while the South region has the lowest income but the highest number of households. The data also indicates an overall increase in the number of households and income in most regions from 2020 to 2021, which could be attributed to various factors such as economic growth, population growth, and policy changes.

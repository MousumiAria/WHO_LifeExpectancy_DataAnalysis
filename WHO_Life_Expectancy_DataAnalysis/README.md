
<h1> <align="center">WHO_LifeExpectancy_DataAnalysis</h1>

## Developer: 

<a href="https://https://github.com/MousumiAria"> Mousumi Sen</a>

## Level: 
* Data Analyst


## The timeline of the project: 
**July-August 2023**


## Dataset details:
* The dataset is sourced from the World Health Organization and comprises various health and economic metrics for different countries across several years.It is downloaded from Kaggle website: https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who

## Description:

This project conducts an in-depth analysis of the World Health Organization's Life Expectancy dataset. The primary aim is to derive insights on global health trends, mortality rates, the impact of socio-economic factors on health, and other relevant indicators.

## Key Metrics
* Life Expectancy: Average number of years a person is expected to live.
* Adult Mortality: Adult mortality rate.
* Infant Deaths: Number of infant deaths per year.
* Health Factors: For diseases such as Hepatitis B, Polio, Diphtheria, Measles, Alcohol consumpsion.
* Economic Indicators: GDP, Income Composition of Resources, etc.
* Social Factors: Schooling, Population. 

## Columns Description 

* Country: Country
* Year: Year
* Status: Classification of countries as 'developed' or 'developing' based on their gross domestic product(GDP). 1 
* Life expectancy: Life expectancy (years of age).
* Adult Mortality: Adult Mortality Rates of both sexes (Probability of dying between 15 and 60 years per 1000 population).
* Infant deaths: Number of Infant (0-1 year of age) Deaths per 1000 population.
* Alcohol: Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol).
* Percentage expenditure: Expenditure on health as a percentage of GPD per capita. (%)
* Hepatitis B: Hepatitis B immunization coverage among 1-year-olds. (%)
* Measles: Number of reported cases per 1000 population.
* BMI: Average Body Mass index of entire population
* Under-five deaths: Number of under-five deaths per 1000 population
* Polio: Polio immunization coverage among 1-year-olds (%)
* Total expenditure: General government expenditure on health as a percentage of total government expenditure (%)
* Diphtheria: Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
* HIV/AIDS: Deaths per 1000 live births HIV/AIDS (0-4 years)
* GDP: Gross Domestic Product per capita (in USD)
* Population: Population of the country
* Thinness 1-19 years: Prevalence of thinness among children and adolescents for Age 10 to 19 (%)2 
* Thinness 5-9 years: Prevalence of thinness among children for Age 5 to 9 (%)
* Income composition of resources: Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
* Schooling: Number of years of Schooling (years)

## Tools & Technologies

* Power BI: Used for data visualization, transformation, and analysis.
* DAX: Employed for complex calculations and data modeling.

## Data Preparation

* Data Cleaning: Addressed missing values, outliers, and inconsistent data types.
* Data Modeling: Created relationships between various tables derived from the primary dataset.

## Visualizetion and Analysis

# Trends and Disparities in Life Expectancy:

![WHO_LifeExpectancy_DataAnalysis](https://github.com/MousumiAria/WHO_LifeExpectancy_DataAnalysis/blob/main/Trends_Disp_LE.JPG?raw=true)

* Overall Life Expectancy Trend by Year and Country-wise:
Inserted a line chart with the 'Year' and 'Country' column into the axis area and 'Life Expectancy' into the values area.  This chart gives a line for each country, allowing you to see disparities and trends at the same time.

* * Comparing Developed vs. Developing:
Here used a line chart to represent 'Year' to the axis and 'Life Expectancy' to values and 'Status' (Developed/Developing) in the legend.
This shows how developed countries' life expectancy trends compare to those of developing countries.

* * * Country with Highest & Lowest Life Expectancy:
For a specific year or range, to calculate countries with the highest and lowest life expectancy here used DAX formula and to show those used Cards.

* * * * Country-wise Average Life Expectancy:
Used a matrix with showing country wise average Life Expectancy and a bar chart where showing distribution of life Expectancy.

* * * * * Interactive Filtering:
Introduced slicers in dashboard, which allow users to select specific years or countries. This enabled users to focus on specific time frames or countries of interest.

* * * * * * Map Visualizetion:
Incorporated a map visual and used 'Life Expectancy' as a measure. This provides a geographical representation of life expectancy data, where users can identify regions with higher or lower life expectancy.

Insights:
Using the visuals, derive insights such as:
Countries that have seen a significant increase or decrease in life expectancy over time.
The gap between the highest and lowest life expectancy and how it's changing.
How external events, like wars or economic downturns, might have impacted life expectancy in certain regions.

## Mortality Analysis:

![WHO_LifeExpectancy_DataAnalysis](https://github.com/MousumiAria/WHO_LifeExpectancy_DataAnalysis/blob/main/MortalityAna_LE.JPG?raw=true)

To analysis Mortality  here used mortality-related columns such as 'Adult Mortality', 'Infant Deaths', and 'Under-Five Deaths'.

* Overall Mortality Trend Over Time:
Line Chart:
X-axis: Year
Y-axis: Adult Mortality, Infant Mortality and Under Five death.
This visualization gives a snapshot of how all type mortality has evolved over time.

* * Infant vs. Under Five vs. Adult Mortality:
Stacked Column Chart:
X-axis:  Country
Bars: Separate bars for 'Infant Deaths', 'Under Five Death' and 'Adult Mortality'.
This helps compare the rate of infant deaths, under five death to adult mortality across countries.

* * *  Mortality by Status (Developed vs. Developing):
Clustered Bar Chart:
X-axis: Status
Bars: Separate bars for 'Developed' and 'Developing' under each year or country, representing either 'Adult Mortality', 'Infant Deaths' and Under Five Death.
This chart allows you to identify disparities in mortality between developed and developing nations.


* * * * Correlation Analysis:
Examine the relationship between mortality and other factors.
Scatter Plot:
X-axis: Life Expectancy
Y-axis: Adult Mortality 
This provide insights into whether higher life expectancy is correlated with lower mortality.

* * * * * Interactive Filtering:
Introduce slicers to allow users to drill down into specifics:
Year Slicer: To focus on specific years or time frames.
Country Slicer: To zero in on a particular country's mortality data.
Status Slicer: To filter data based on 'Developed' or 'Developing' status.

* * * * * * Geographical Insights:
Map Visual:
Use 'Country' for location and 'Adult Mortality' for the value.
This visualization provides a global view of mortality rates, helping identify regions or continents with particularly high or low rates.

Insights:
Identify countries or regions with alarming mortality rates.
Analyze how mortality has trended over the years. Are there specific years where a spike occurred? What could be the reasons?
Explored the disparity in mortality between developed and developing nations.
Incorporate a consistent color scheme, clear labeling, and well-organized layout to ensure your dashboard effectively communicates these insights. Combining visuals with the dataset's context can help stakeholders understand and possibly address mortality issues more effectively.

## Vaccination and Disease Metrics in Life Expectancy :

![WHO_LifeExpectancy_DataAnalysis](https://github.com/MousumiAria/WHO_LifeExpectancy_DataAnalysis/blob/main/Vacc&DiseMatrics_LE.JPG?raw=true)

Analyzing "Disease Metrics in Relation to Life Expectancy" all related columns are 'Hepatitis B', 'Measles', 'Polio', 'Diphtheria', and 'HIV/AIDS'.

* Vaccination Trends Over Time:
Line Chart:
X-axis: Year
Y-axis: Vaccination metrics (like 'Hepatitis B', 'Polio', and 'Diphtheria')
Legend: Different diseases
This visualization shows how vaccination rates for various diseases have changed over the years.

* * Disease Prevalence Chart:
Stacked Bar Chart:
X-axis: Year
Y-axis: Disease metrics (like 'Measles' and 'HIV/AIDS' incidence/prevalence)
This provides a clear view of how disease incidence or prevalence has evolved over time.

* * *  Vaccination Rates by Country:
Column Chart:
Use separate charts for each vaccine type or use a combined stacked bar chart.
Sort countries based on vaccination rates to see which countries have the highest and lowest vaccination coverage.

* * * * Disease Prevalence by Country:
Bar Chart:
Use separate charts for each Disease type.
Sort countries based on Disease Prevalence to see which countries have the highest and lowest Disease Prevalence.

* * * * * Correlation Between Life Expectancy vs Hepatitis B and Life Expectancy Measles:
Scatter Plot:
X-axis: Life Expectancy
Y-axis: Hepatitis B and Measles
This helps explore if there's a direct relationship between vaccination coverage and higher life expectancy.

* * * * * * Interactive Filtering:
Slicers:
Year: To analyze specific years or time frames.
Country: To focus on a particular country.
Status (Developed/Developing): To compare metrics between developed and developing countries.

Insights:
Identify regions or countries with low vaccination rates and explore their life expectancy.
Analyze countries with high disease prevalence and understand how it affects their life expectancy.
Observe if there's a trend indicating that increased vaccination over the years has led to an increase in life expectancy.

## Diet and Health Indicators:

![WHO_LifeExpectancy_DataAnalysis](https://github.com/MousumiAria/WHO_LifeExpectancy_DataAnalysis/blob/main/DietHealth_LE.JPG?raw=true)

To extract insights on "Diet and Health Indicators" from the dataset in Power BI, used columns are BMI, thinness in different age groups, alcohol consumption, and how these correlate with life expectancy and other health metrics. Here's a step-by-step approach:

* Overall BMI Distribution:
Bar Plot:
This visualization can show you the distribution of BMI across the dataset, indicating how many countries or regions fall into various BMI categories.

* * Alcohol Consumption vs. Health Indicators:
Scatter Plot:
X-axis: Alcohol
Y-axis: Life Expectancy 
It provide insights into whether higher alcohol consumption correlates with certain health outcomes.

* * * Trends in Thinness:
Line Chart:
X-axis: Year
Y-axis: Different age groups (1-19 vs. 5-9 years)
This helps visualize if thinness trends are getting better or worse over time and whether there are significant differences between age groups.

* * * * BMI and Life Expectancy:
Scatter Plot:
X-axis: Average BMI for a country or region
Y-axis: Life Expectancy
By plotting these two metrics against each other, it shows a clear trend indicating that regions with higher BMI have different life expectancies.

* * * * * Correlation Matrix:
Using a matrix or a set of scatter plots, you can check correlations between:
Alcohol and Life Expectancy
BMI and Adult Mortality
This helps to understand if and how dietary indicators are related to health outcomes

* * * * * *  Geographical Analysis:
Map Visual:
Used 'Country' for location and 'BMI' for values to provide a geographical representation of these metrics.


Insights:
Use the insights derived from the visuals to draw conclusions, such as:
Countries with the highest and lowest BMIs.
Trends in thinness among younger populations.
Potential correlations between dietary indicators and health outcomes.

By analyzing these diet and health indicators, policymakers and health professionals can gain a clearer understanding of how dietary habits might be impacting health outcomes on both national and global scales.

## Relationship between Economic and Health Indicators:

![WHO_LifeExpectancy_DataAnalysis](https://github.com/MousumiAria/WHO_LifeExpectancy_DataAnalysis/blob/main/RelaBetw_EcoHealth_Indicators.JPG?raw=true)

Analyzing the relationship between economic and health indicators is essential to understand how a country's economic status can influence the health and well-being of its population. Using Power BI, you can visualize and analyze these relationships effectively. Here's how one can extract insights on the relationship between economic and health indicators from the dataset:

Ensure columns like 'GDP', 'Income composition of resources', and 'Life Expectancy' (or other health indicators) have appropriate data types.

* Time Series Analysis:
Line Chart:
X-axis: Year
Y-axis: Total GDP
Legend: Different countries or regions
Observed how GDP have evolved over time for different countries.

* * GDP vs. Life Expectancy:
Scatter Plot:
X-axis: Average GDP 
Y-axis: Life Expectancy
This plot can show how life expectancy correlates with GDP, highlighting if countries with higher GDPs have longer average lifespans.

* * * Income Composition vs. Adult Mortality:
Scatter Plot:
X-axis: Income composition of resources
Y-axis: A health metric like Adult Mortality
This visualization helps analyze if countries with better income distribution have better health outcomes.

* * * * Economic Status and Disease Prevalence:
Bar or Column Chart:
For a specific disease or health metric, compare its prevalence or rate across different GDP brackets or income compositions. This helps identify if certain diseases are more prevalent in richer or poorer countries.

* * * * * Geographical Analysis:
Map Visual:
Use 'Country' for location.
Use 'GDP' or 'Income composition of resources' for size and 'Life Expectancy' or another health metric for color intensity.
This visualization provides a global perspective on the relationship between economic and health indicators.


Insights and Analysis:
Identify countries that defy the norm, i.e., those with low GDP but high life expectancy or vice versa.
Determine if there's a clear threshold of GDP where health outcomes significantly improve.
Analyze how external events, such as economic crises, impact health indicators.
Dashboard Design:
Used consistent color schemes to represent economic and health metrics distinctly.
Make sure titles, labels, and legends are clear and descriptive.
Arrange visuals in a logical flow, possibly starting with global views and then narrowing down to specific country or region comparisons.
Exploring the relationship between economic and health indicators provides valuable insights that can guide policymakers, NGOs, and other stakeholders in making informed decisions about where and how to allocate resources for the best health outcomes.

## Socio-economic Indicators and Health:

![WHO_LifeExpectancy_DataAnalysis](https://github.com/MousumiAria/WHO_LifeExpectancy_DataAnalysis/blob/main/SocioEcoHi.JPG?raw=true)

To obtain insights from the relationship between socio-economic and health indicators it focus on columns and metrics that relate to societal structures and economic factors, as well as their potential impacts on health outcomes. Related columns like 'Schooling', 'Income composition of resources', 'GDP', 'Status' (Developed/Developing), and health indicators like 'Life Expectancy', 'Adult Mortality', etc.

* Life Expectancy vs. Schooling:
Scatter Plot:
X-axis: Average years of schooling
Y-axis: Life Expectancy
This can show if regions with higher educational attainment tend to have longer average lifespans.

* * GDP and Health Indicators:
Scatter Plot:
X-axis: GDP per capita
Y-axis: A specific health metric like 'Adult Mortality'
Analyze if countries with a higher GDP per capita tend to have better health outcomes.

* * * Income Composition vs. Health Metrics:
Bar or Column Chart:
Group countries based on their income composition (you can create buckets like Low, Medium, High).
Compare health metrics like life expectancy or infant mortality across these groups.

* * * * Geographical Insights:
Map Visual:
Use 'Country' for location.
Represent socio-economic data with color (e.g., deeper colors for higher GDP) and health metrics with the size of bubbles (larger circles for better health outcomes or vice versa).

* * * * * Correlation Analysis:
Investigate Trend of Socio Ecomic factor GDP per Capita
Time Series Analysis:
viii)Line Chart:
X-axis: Year
Y-axis: GDP per Capita
Observe how socio-economic factors have evolved over time for different countries or regions.

* * * * * * Stack Bar Chart with Line Chart:
Investigate the correlation of Total Expenditure and Income composition of resources with Country

Insights and Observations:
Identify countries that stand out, for instance, those with lower economic indicators but higher health outcomes, and vice versa.
Understand if certain socio-economic factors consistently correlate with specific health outcomes across different countries and over time.

Combining the insights from socio-economic and health indicators offers a comprehensive view of the factors that contribute to well-being. Such analyses can guide policy-making, resource allocation, and targeted interventions for improved public health.



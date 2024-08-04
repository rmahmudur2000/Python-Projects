# The Story of Palestine Through Data

**Situation:**

You were working with a dataset containing information about fatalities in the Israeli-Palestinian conflict from 2000 to 2023. The data included details such as dates of events, age and citizenship of victims, locations, and causes of death.

**Task:** Your task was to analyze this data to uncover trends, patterns, and insights about the fatalities over time. You aimed to create visualizations and statistical summaries to better understand the demographics of the victims and the nature of the conflict.

**Action:**

1.	Data Cleaning: 

Handled missing values

Parsed dates into proper datetime format

Standardized categorical values

Removed unnecessary columns

2.	Exploratory Data Analysis: 

Used libraries like pandas for data manipulation, matplotlib and seaborn for visualization, and folium for mapping

Analyzed temporal trends, regional impacts, causes of fatalities, and yearly patterns

Examined age and gender distribution, citizenship analysis, and geographic distribution

Investigated participation in hostilities and types of injuries

Provided historical context for significant events like the Jenin massacre and the 2014 Gaza War

3.	Visualization and Analysis: 

Created detailed visualizations comparing Palestinian and Israeli fatalities over the years

Generated correlation heatmaps to identify relationships between variables

Produced an interactive map to display fatality locations

Analyzed distribution of place of residence and participation in hostilities

**Results:**

1.	Data Cleaning 

  	 a.	The dataset initially had 11,124 entries with 16 columns. After cleaning, the dataset now contains 4,661 entries with the same number of columns. The cleaning 
         process involved:
  	
  	    i.	Standardizing column names.
        ii.	Dropping rows with missing values.
  	    iii.    Removing duplicate records.
        iv.	Converting the date column to datetime format.
  	
     b.	Here is a summary of the cleaned dataset:
  	
         i.	The dataset contains information such as name, date_of_event, age, citizenship, event_location, event_location_district, event_location_region, date_of_death, 
            gender, took_part_in_the_hostilities, place_of_residence, place_of_residence_district, type_of_injury, ammunition, killed_by, and notes.
         ii.	Columns like type_of_injury, ammunition, and notes have been significantly reduced due to the removal of rows with missing values.

3.	TEMPORAL TRENDS

a.	The line plot of fatalities over time shows fluctuations, with certain periods having significant peaks. These peaks likely correspond to major conflicts or escalations within the timeframe (2000 to 2023).

b.	There may be periods of relative calm or lower fatality rates, which can indicate ceasefires or peace negotiations.

4.	REGIONAL ANALYSIS 

a.	The distribution of fatalities by region highlights the areas most affected by the conflict. Specific regions (e.g., Gaza, West Bank) have higher fatality counts, indicating hotspots of violence and conflict.

b.	This distribution can help in understanding the geographical spread and focus areas of the conflict.

5.	CAUSES OF FATALITIES

a.	The count plot of fatalities by cause reveals that certain types of injuries (e.g., gunfire, missile) are more common.

b.	This provides insights into the nature of the conflict and the predominant methods of violence used.

6.	YEARLY TRENDS

a.	The bar plot showing the number of fatalities by year highlights specific years with notably higher or lower numbers of fatalities.

b.	This information can be correlated with historical events, such as major military operations, peace agreements, or changes in political leadership.

7.	CORRELATION ANALYSIS 

a.	The correlation heatmap helps in identifying relationships between different numerical variables in the dataset.

b.	However, given the nature of the data (mostly categorical), there may be limited numerical correlations. The primary numerical variable in this context is age, which may not show strong correlations with other factors.

8.	AVERAGE AGE OF DECEASED

a.	Average age: 26 years old.

b.	Age range: Youngest 1 year old, Oldest 112 years old.

9.	PRIMARY VICTIMS:

a.	Majority of fatalities are young people and children, particularly those aged between 15 and 30.

10.	EQUAL IMPACT ON GENDERS

a.	Both men and women are equally affected by the conflict with no differentiation.

11.	PREDOMINANTLY PALESTINIAN VICTIMS

a.	89.2% of the total fatalities are Palestinians, indicating a disproportionate impact on the Palestinian population.

12.	HIGH-FATALITY DISTRICTS

a.	Gaza city (represented by the blue line) consistently shows the highest number of fatalities throughout the period, with several significant spikes.

b.	There are notable peaks in fatalities for most locations around 2008-2009 and 2014, likely corresponding to major conflicts or operations in those years.

c.	The highest spike for Gaza city is around 2008-2009, reaching nearly 350 fatalities.

d.	Other locations like Rafah, Khan Yunis, and Jabalya R.C. also show significant fatalities, but generally lower than Gaza city.

e.	The year 2014 shows a significant spike for multiple locations, likely corresponding to a major conflict event.

13.	INTERACTIVE MAP 

a.	This visualization would provide a geographical representation of the fatalities, allowing viewers to quickly identify which areas have been most affected by the conflict. The color coding and size of the circles offer an immediate visual understanding of the severity of fatalities in each district.

b.	Purple for over 500 fatalities

c.	Bluefor 100-500 fatalities

d.	Red for 50-100 fatalities

e.	Green for less than 50 fatalities

14.	DISTRIBUTION OF PLACE OF RESIDENCE 

a.	This visualization provides a clear picture of which areas have suffered the most fatalities, highlighting the concentration of conflict-related deaths in certain locations, particularly within Gaza. It also shows the widespread nature of the conflict, as evidenced by the large "Other" category.

b.	Gaza city and "Other" have the highest counts, both around 1300-1400 fatalities.

c.	Khan Yunis and Rafah follow as the next highest, with approximately 300-400 fatalities each.

d.	There's a significant drop-off after the top 4 categories.

15.	DISTRIBUTION BASED ON PARTICIPATION IN HOSTILITIES

a.	The graph shows that the majority of the dead had no participation in the hostilities, accounting for about 50 percent of the total dead.

b.	Next, we can see that about 36 percent of the dead took part in the hostilities

c.	About 3 percent are not known, 11 percent were killed by the Israelis, while 4 percent of the dead were targeted.

16.	DISTRIBUTION OF TYPES OF INJURIES

a.	The graph shows that 90 percent of deaths were by firearm.

b.	We can also see deaths by explosion account for 10% of the total deaths recorded

17.	TOP 10 MOST USED AMMINITION AND TOP 10 MEANS OF KILLING 

a.	These visualizations provide a sobering look at the nature of the conflict, highlighting both the methods used and the parties most responsible for fatalities.

b.	The conflict involves a wide range of weaponry, with missiles being the predominant type of ammunition used.

c.	There's a stark imbalance in the means of killing, with Israeli security forces being responsible for significantly more fatalities than other groups.

d.	The data suggests that the conflict is largely one-sided in terms of fatalities, with Palestinian civilians suffering the most casualties.

e.	The use of various types of ammunition, including controversial ones like phosphorus shells, indicates the intensity and complexity of the conflict.

18.	AGE DISTRIBUTION OF VICTIMS AND GENDER DISTRIBUTION OF VICTIMS 

a.	These visualizations highlight the human toll of the conflict, showing that it impacts a wide range of ages but particularly young men. The data underscores the severity of the conflict and its broad impact on the population.

b.	The conflict disproportionately affects young adults and adolescents.

c.	There's a significant number of child victims.

d.	Men are much more likely to be victims than women in this conflict.

e.	The age distribution suggests that many victims are of fighting age, but the presence of very young and old victims indicates that civilians of all ages are affected.

19.	PALASTINIAN FATALITIES

a.	Total Palestinian Fatalities: The chart indicates a total of 4,159 Palestinian fatalities over the 2000-2023 period.

b.	Significant Spikes:

    i.	2002: The highest number of fatalities, around 750, coinciding with the Second Palestinian Intifada and events like the Jenin massacre.
    ii.	2014: Another major spike with approximately 700 fatalities, linked to the 2014 Gaza War (Operation Protective Edge).
    iii.	2009: A notable increase, with over 800 fatalities, possibly related to Operation Cast Lead (2008-2009).
    
c.	Moderate Peaks:

    i.	2001, 2003-2005: Elevated fatalities during these years, reflecting ongoing conflict and violence throughout the Second Intifada.
    ii.	2018: Another peak, likely due to escalated tensions and conflict incidents like the Great March of Return protests.
    
d.	Periods of Decrease:
    i.	2006-2008, 2010-2013, 2016-2017: Relatively lower fatality rates during these periods, indicating temporary reductions in fatal violence.
    
e.	Recent Trends:

    i.	2020-2023: Noticeable spikes, especially in 2021, which may be attributed to escalations such as the 2021 Gaza-Israel clashes.
    
20.	ISRAELI FATALITIES

a.	Total Israeli Fatalities: The chart indicates a total of 502 Israeli fatalities over the 2000-2023 period.

b.	Trend Observations:

    i.	The number of Israeli fatalities is generally lower compared to the Palestinian fatalities shown in the previous chart.
    ii.	The trend appears more stable, with fewer dramatic spikes or fluctuations over the years.
    iii.	The highest number of Israeli fatalities occurred in the early 2000s, particularly in 2002 and 2003, which likely corresponds to the Second Palestinian Intifada.
    iv.	After 2003, the number of Israeli fatalities declined and remained relatively lower, with some minor variations in the following years.
    
c.	Specific Years:

    i.	2002-2003: The peak years, with around 200 and 150 Israeli fatalities, respectively.
    ii.	2004-2007: Elevated but declining number of fatalities during this period.
    iii.	2008-2023: Relatively lower and more stable number of Israeli fatalities, with some minor fluctuations.

Overall, the Israeli Fatalities chart presents a contrasting picture to the Palestinian Fatalities chart, showing a less volatile trend and a significantly lower total number of fatalities on the Israeli side compared to the Palestinian side over the 2000-2023 period.


# Python-Projects

### Situation

I identified a need for practical, user-friendly tools to calculate Body Mass Index (BMI) and mortgage payments. Additionally, I saw an opportunity to demonstrate web scraping skills by extracting data from a real website.

### Task

1. Develop a BMI Calculator using Python
2. Create a Mortgage Calculator using Python
3. Implement a web scraping script to extract data from an actual website

### Action

1. BMI Calculator:
    - Designed a Python script to take user input for height and weight
    - Implemented the BMI calculation formula
    - Added logic to interpret the BMI result (underweight, normal, overweight, etc.)
    - Included error handling for invalid inputs
2. Mortgage Calculator:
    - Created a Python program to accept inputs for loan amount, interest rate, and loan term
    - Implemented the mortgage payment calculation algorithm
    - Added features to display monthly payment and total interest paid
    - Incorporated error checking for user inputs
3. Web Scraping:
    - Selected a suitable website with interesting data to scrape
    - Used Python libraries like BeautifulSoup or Scrapy for web scraping
    - Wrote a script to navigate the website's structure and extract relevant data
    - Implemented error handling and respect for the website's robots.txt file
    - Stored the scraped data in a structured format (e.g., CSV or database)

### Result

The project resulted in three functional Python applications:

1. A BMI Calculator that accurately computes and interprets BMI based on user input
2. A Mortgage Calculator that provides detailed payment information for home loans
3. A web scraping script that successfully extracts and stores data from a real website

### Key outcomes:

- Demonstrated practical application of Python programming skills
- Created useful tools for health and financial calculations
- Showcased ability to interact with web data through scraping
- Improved understanding of user input handling, error management, and data processing in Python

These applications not only serve practical purposes but also demonstrate a range of Python programming skills, from basic calculations to more complex web interactions.

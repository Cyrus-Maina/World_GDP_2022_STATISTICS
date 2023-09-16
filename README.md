# World_GDP_2022_STATISTICS

**OVERVIEW**

This dataset was sourced from Worldometer.It consists of  177 Countries' GDP statistical data year 2022.

Some countries are omitted as there was no confirmed GDP data by the  Worldbank.
They include: Cuba, Lebanon, Turkmenistan, Afghanistan, Guam, Aruba, Bhutan, Northern Mariana Islands, American Samoa, Tonga and Palau.

Two fields were introduced in the dataset for insights i.e., 

    1. Growth Status- separates countries that had positive growth **(x>0.00%)** from those that didn't **(x<0.00%)**
    
    2. Growth Rate Category- has countries that grew with 2 digits (x>=10) as 'High Growth Rate', those with (0<x<10) as 'Moderate Growth Rate' 
        and (x<0) as Low Growth Rate.

The other fields are:
  1.Country
  
  2. GDP (nominal, 2022)- income gained from production of goods and services the year 2022
 
  3. GDP (abbrev.)
 
  4. GDP growth (%)- percentage growth from previous year's GDP value
 
  5. Population (2022)
 
  6. GDP per capita- measure from GDP divided by Population. It shows average living standards of the citizens.
 
  7.Share of World GDP (%)- country's GDP divided by total World GDP

Sevral statistical operations were performed to deduct insights e.g., 
 
  1.Covariance- shows what degree of variance is caused by a variable to another.
 
  2.Correlation- deducts types of relationships between varialbles e.g., positive/negative.
 
  3.Descriptive analysis- gives all central measures of tendency

  4.Linear Regression- OLS method was used to deduct what percentage of GDP can be foreseen using Population.

**INSIGHTS**

1. 16 countries reported negative growth i.e., growth less than 0.00% e.g., Russia

2. 13 Countries grew by two digit rates

3. The highest GDP Per Capita was from Luxembourg ($127,046) followed by Norway, Ireland and Switzerland.

4. Lowest GDP Per Capita was reported from Burundi ($238) followed by Central African Republic, Sierra Leone, Madagascar and Niger.

5. Population and GDP have a strong positive growth suggesting that if population increases so will a country's GDP. Might explain India's and China's growth.

6. Population and GDP have a covariance value of 2.19 which suggests a strong positive relationship between the two variables

7. 17 countries had a Share of World GDP (%) greater than 1%

8. You can comfortably predict 34% of GDP via the Population of a country.

9. The OLS model used has a Prob (F-statistic) value of 1.49 suggesting that the model is statistically significant.

10. The mean World GDP is $558 B, mean Grwoth Rate is 4%, mean population is 400M people and mean GDP per capita is $16825

**IN-DEPTH INSIGHTS**

1. Russia and Ukraine reported negative growth rates due to their ongoing Conflict. This has went on to affect neighbouring nations like Belarus.

2. Sri-Lanka's negative gowth rate can be attributed to the Economic crisis they are still facing.

3. Sudan's and Libya's negative gowth rate can be attributed to the ongoing Civil Wars.

4. African countries may have high populations but report low GDP Per Capita as their populations are growing faster than their GDP.
   Their GDP might still be low due to low technological advancements, rampant corruption, poor governance, low value addition on their resources and  little to no exploitation of resources.
   
5.Majority of African countries have little industrialization and depend heavily on sustenance farming.
   
6. India and China have their population in billions but their high technological advancements and solid financial reforms have made their GDP values to catapault into Trillions.

7. Population can impact GDP Per Capita positively or negatively depending on Governance of the country.

8.Countries with high GDP Per capita are reportedly strong financial powerhouses e.g. Switzerland and Luxembourg and heavy energy exporters like Norway. 
  Luxembourg reportedly has 155 different Banks and Banking is their strongest economy sector.

9.Huge offshore oil discoveries have shot Guyana's economy to record growths,57.8% suggesting oil is a heavy ecoomic driver.

# A 3D-Printed Village: determining the location for the greatest impact

## Background
Mobile Loaves and Fishes (MLF) has just completed their Community First! Village 10 miles outside of Austin, TX. Through their first development, MLF provided affordable, permenant housing and a thriving community to 480 individuals who were formerly chronically homeless in a 51-acre master planned community, reducing Austin's chronically homeless population by roughly 40%. The Village offers a tight-knit community along with opportunities for dignified earning, however, all tenants must pay rent. In the pilot Village, ICON, a construction technologies company specializing in 3D printing, printed six microhomes and a 500 sq ft 'Welcome Center', which was built in under 27 hours across several days. ICON's 3D printed structures were built using a reinforced concrete, called Lavacrete, which has been proven to be mold- and fire-resistant and more resilient against severe weather compared to traditional building material. Upon hearing that the 3D-printed structures were unharmed during Texas's particularly harsh storms this year, Alan Graham, CEO of MLF, has planned to build exclusively with ICON for the next Community First! Village. 

## Opportunity
The ultimate goal of this project is to determine locations on the contiguous United States which would benefit most from a 3D-printed community. To have the greatest impact, this project focuses on rates of homelessness via point-in-time estimations and the costs to property associated with damage from severe weather events, which have been increasing in frequency and intensity with climate change, according to the [EPA](https://www.epa.gov/climate-indicators/weather-climate).

## Data Science Solution

<details><summary>Impact hypothesis</summary>
<p> 
   We hypothesize that looking at the cost of damaged property from severe weather events and point-in-time estimates of homeless populations on the state-level for 2020 will allow MLF to determine a location for the 3D-printed village which will have the greatest potential impact. 
  
  **Primary Impact:** determine the location for the 3D-printed village
  
  **Secondary Impacts:** reduce the amount of chronic homelessness in a given area, prevent the costs of damage, repair or rebuilding for tenants of the village and overall climatic vulnerability of area

</p>
</details>

<details><summary>Solution Path</summary>
<p> 
  
**Suggested Solution Path:** 
  Determine the location based on model which scores locations based upon the following features: <br>
- Previous costs of property damage in dollars per state
- Number of severe weather events
- Number of homeless individuals based upon point-in-time estimations
  
</p>
</details>

<details><summary>Measures of Success</summary>
<p> 
  
  **Technical:** relative scoring algorithm identifies reasonable locations for the 3D-printed village
  
  **Nontechnical:** rate of chronic homelessness reduced in and around the location of village, reduction in cost of property damage from severe weather events for village tenants 
  
</p>
</details>

## Data
- Severe Storms and Extreme Events data for 2020, acquired via NOAA, Climate.gov
- Point-in-Time (PIT) data for 2020 from the US Department of Housing and Urban Development (HUD) Exchange

## Algorithms
### Data Cleaning & EDA
Preliminary data cleaning was conducted with the pandas library, which included dropping unneccessary features and restricting the data to that of in the contiguous United States. 

Subsequently, the remaining data cleaning and initial exploratory data analysis was carried out in Google Sheets. 

### Visualization
The interactive Tableau dashboard can be accessed [here](https://public.tableau.com/app/profile/evelyn.johnson/viz/Biz_fun_project/Dashboard1?publish=yes)

### Modeling 
In future work, I plan to develop a scoring algorithm which determines the relative score of potential impact based primarily upon a location's homelessness population estimation, risk of costly property damage from severe weather events and financial feasibility of a particular location. 

## Tools
- Pandas for preliminary data acquisition and cleaning
- Google Sheets for data cleaning and exploratory data analysis
- Tableau for data visualization

## Communication
Along with this written report, I created a "pitch" presentation and have uploaded my Tableau dashboard online. 

<h1>Toronto Airbnb Business</h1>

<h2>Description</h2>
This project utilizes Airbnb data from the city of Toronto, ON, Canada, to find the best neighbourhood in town for starting an Airbnb business. Using SQL for data cleaning and exploration and Tableau to create a dashboard that compares neighbourhoods based on Yearly Revenue, Occupancy Rates, Prices per night and Competition.
<br />

<h2>Criteria for a Good Neighborhood for an Airbnb</h2>

- **Occupancy rate higher than the average** - property is occupied more than half the year.
- **Higher median yearly revenue** -  better chance of earning above average income.
- **Less competition** - fewer listings in the area, easier to stand out.

<h2>Final Dashboard:</h2>

- [Airbnb Neighbourhood Analysis](https://public.tableau.com/views/TorontoAirbnbAnalysis_16863412362360/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<p align="center">
<img src="https://i.imgur.com/8Qrg75h.jpeg" height="70%" width="70%" alt=""/>
<br />

<h2>Findings:</h2>
Based on the criteria for analysis those are the 5 best neighbourhoods to start and Airbnb.

| Neighbourhood | Number of Listings | Median yearly revenue  | Median occupancy rate |
| ------------- | ------------- | ------------- | ------------- |
| Roncesvalles  | 133 | 31K | 79% |
| Bay Street Corridor   | 438 | 39K | 80% |
| Regent Park  | 85 | 29K | 80% |
| Church-Younge Corridor | 416 | 29K | 75% |
| Niagara | 643 | 32K | 69% |

*Please note that further analyis on the cost of property and factors like access to public transportation, tourist attractions and overall state of the community, this project is a starting point and the findings need to be further evaluated before making an investment decision.*
  
<h2>Project walk-through:</h2>

<p align="center">
Organizing and Cleaning the Data: <br/>
<img src="https://i.imgur.com/gjDfAmX.png" height="70%" width="70%" alt=""/>
<img src="https://i.imgur.com/Rj1po6m.png" height="70%" width="70%" alt=""/>
<br />
<p align="left">
  Some important points from cleaning and understanding the dataset.

- The data is from 2010 to 2023 - for being accurate I will only use data from the last 5 years (2019 to 2023)
- The analysis will be of 11,489 listings and 7,665 hosts
- There is at least one listing for every neighbourhood

<p align="center"> 
<br />
Exploratory Data Analysis: <br/>
<img src="https://i.imgur.com/bb3npbF.png" height="70%" width="70%" alt=""/>
<img src="https://i.imgur.com/FXxNKT5.png" height="70%" width="70%" alt=""/>
<br />
<br />
Create Table to be Exported to Tableau (For dashboard creation):  <br/>
<img src="https://i.imgur.com/yT5V2du.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
  
<p align="left">
Some important thing from the EDA to keep in mind during the analysis:

- Average occupancy rate is 57%
- Average number of listings per neighbourhood is 118

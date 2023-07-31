# cyclistic-bike-sharing
## Google Data Analytics Capstone Project

## Client: Cyclistic

## Purpose: 
This project aims to help the Cyclistic executive team to understand how casual riders and annual members use Cyclistic bikes differently.
Patterns discovered in this dataset can provide insights into designing a new marketing strategy to convert casual riders into annual members.

## Prepare
**The dataset**
* The data is available by Motivate International Inc. under this [Licence](https://www.divvybikes.com/data-license-agreement).
* The datasets from the month of June 2022 to May 2023 are in CSV files.
* Although the datasets have some missing values, they answer the business question.
* Prior to cleaning, there were **5,829,030 rows**
* After cleaning, **4,494,606 rows** were left

## Cleaning Process
* I chose to use R because it can handle a large dataset and provide tools for visualization
* Compared data frames for compatibility before combining them into a data frame
* Checked for NA values, blanks
* Change the datatype of some columns to the proper type
* Computed new columns for calculation
* Removed records with NA values and blanks

## Findings
* Prior to deleting rows with blank station names, the data showed the highest number of rides originated from start and end stations without station_names.
* Although members have taken more rides than casual users, the **average ride** of a **casual** user is **22.72 minutes**, about double the average ride of a **member** - **12.19 minutes**.
* The twelfth to the eighteenth day of the month had the highest number of rides.
* 8 am, afternoons, and early evenings were the busiest times during the day.
* The rides taken by Casual users increase over the course of the week and are highest on Saturdays. On the contrary, members use Cyclistic just about every day of the week. However, the number of rides is highest during the week.
* The total number of rides each day by members exceeds the rides by casual users except on Saturday.
* The total rides are higher in the warmer months and lowest in the colder months. While this is generally the case, there is a slight increase in member rides in January.
* The longest ride recorded was by a **casual user**. It lasted **533.92 hours**.
* Cyclistic offers three types of bikes to its users. Namely classic_bike, docked_bike, and electric_bike. Yet, the dataset has no specific mention concerning its special bikes (reclining-bikes, hand tricycles, and cargo bikes) for people with disabilities and riders who can’t use a standard two-wheeled bike.
* Type of bike used: Electric_bike is the least used while Classic_bike is the most used for both users. Only Casual users used the docked_bike.

## Recommendations
* Cyclistic has 692 stations. Although initial inspection indicates 1,883 unique start and end stations used by users (including blank rows). Therefore, the knowledge of locations currently being used but not part of Cyclistics' network could provide more information on different user behaviour. These could help account for bikes without start or end station names.
* Maintain datasets that clearly state special bike offers (such as reclining bikes, hand tricycles, and cargo bikes). Cyclistic could benefit from the casual users in the 8% of riders **(~466,322 users)** that use the assistive options. 
* Certain hours (8am, 3pm to 6pm) during the day have been identified as the busiest. Cyclistic can make the rental process easier by having more staff at hand at those hours especially at the busiest stations. In addition, provide an easy but efficient record keeping method to help account for every transaction.

*Visualization in [Tableau](https://public.tableau.com/app/profile/joy.bassey/viz/dashboard_16905547216340/Dashboard3?publish=yes)*

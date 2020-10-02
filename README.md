# Heroes-of-Pymoli-Panda

Created a large report from data relating to video game purchases for the video game, Heroes of Pymoli. Imported the file purchase_data.csv from the Resources folder and stored it as a Pandas data frame, purchase_data_df. 
Purchase_data_df was the main data frame I reference throughout the report to create other data frames and no_duplicate_names_df was anouther. No_duplicate_names_df was a data frame I created which had each player's purchase data from purchase_data_df, however, all of the duplicate 'SN's were dropped.
To create a report that gave valuable insight relating to the total amount of players, count for gender demographics or count for age demographics; the duplicate 'SN' had to be removed from the main data frame. 

Other created data frames that provided insightful data are the Purchasing Analysis by Age, 
Top Spenders, the Most Popular Items purchased on the video game and the Most Profitable Items purchased on the video game. Purchases during gameplay after the initial purchase of the game has become a lucrative business for video game companies and I found the data presented in the last three data frames to be very useful for this analysis.



Please view HeroesOfPymoli_starter.ipynb in the HeroesOfPymoli folder to view all data frames.


Utilized Panda functions recently learned in class:

groupby()

unique()

pd.cut()

index()

.sort_values

sum(), count(), mean(), head()


## Conclusion:

1. Of the total 576 Heroes of Pymoli players, 84.03% were male players and 14.06% were female players. This is a large reason there is a higher Total Purchase Value from Male players over Female players.

2. The item name 'Final Critic' was the most popular item and the most profitable item in Heroes of Pymoli. It has a purchase count of 13 and has the highest Average Purchase Price among the other items.

3. According to Age Demographics, age group from 20 to 24 had the highest count and percentage of players at 44.79%. The second highest age group was 15 to 19 with percentage of players at 18.57%. The positive relationship between number of players and Total Purchase Value is also evident in Purchasing Analysis (Age) data frame. Players in the 20 to 24 age group had the highest Total Purchase Value among the other groups but the highest Average Purchase Price was for age group 35 to 39.

 

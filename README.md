# Heroes-of-Pymoli-Panda

Created a large report from data relating to video game purchases for the video game, Heroes of Pymoli. Imported the file purchase_data.csv from the Resources folder and stored it as a Pandas data frame, purchase_data_df. 
Purchase_data_df was the main data frame I reference throughout the report to create other data frames and no_duplicate_names_df was anouther. No_duplicate_names_df was a data frame I created which had each player's purchase data from purchase_data_df, however, all of the duplicate 'SN's were dropped.
To create a report that gave valuable insight relating to the total amount of players, count for gender demographics or count for age demographics; the duplicate 'SN' had to be removed from the main data frame. Other created data frames that provided insightful data are the Purchasing Analysis by Age, 
Top Spenders, the Most Popular Items purchased on the video game and the Most Profitable Items purchased on the video game. Video game purchases within the game after the initial purchase has become a lucrative business for video game companies. I found the data presented in hte last three data frames to be very useful for this analysis.



Please view HeroesOfPymoli_starter.ipynb in the HeroesOfPymoli folder to view all data frames.


Utilized Panda functions recently learned in class:

groupby()

unique()

pd.cut()

index()

.sort_values

round(), sum(), count(), mean(), head()






## PyPoll

Python script results:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.
  
Attempted to create a text file of the results using the With open(output, 'w') function but, I found this to be very difficult. Some of the information converted to a text file 
but not all of the information. Text files are found in the Analysis folder.


 

